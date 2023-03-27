# docker容器中使用python

## 简单使用
### 1. pull image
0. 打开docker desktop
1. 打开powershell
2. 输入：`wsl` 
3. 输入：`docker pull python` 




### 2. run image
输入命令：`docker run -ti --rm -e DISPLAY=host.docker.internal:0.0 python` 


### 3. test
0. 打开Xluanch
1. 打开vscode
2. docker 
3. pip install matplotlib

``` python
import matplotlib.pyplot as plt
from matplotlib.font_manager import FontProperties 

dataX = [1,2,3,4]
dataY = [1,2,3,1]
plt.plot(dataX,dataY)#plot还有很多参数，可以查API修改，如颜色，虚线等
plt.title("draw line");
plt.xlabel("x axis");
plt.ylabel("y axis");
plt.show()

```

结果如下：
![a](/images/posts/testdrawline.png)