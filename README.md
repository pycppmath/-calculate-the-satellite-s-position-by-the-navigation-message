# MTALAB 由导航电文计算卫星在地固坐标系中的坐标 
# calculate the satellite's position by the navigation message
## 使用说明：

### 第一步first：
删除brdc2470.01n文件中的头部分，使卫星号PRN顶行，数据呈现规律性。如brdc2470_clearhdr.01n文件所示。

Delete the head part in the brdc2470.01n file to make the satellite PRN top line and the data show regularity. As shown in the brdc2470_clearhdr.01n file.
### 第二步second：
调用函数readatandcomp.m，参数包括读入的去头广播星历文件，想要读取数据的卫星号PRN，观测时刻的UTC时。

invoking function **readatandcomp.m**. Parameters include the headless broadcast ephemeris file read in, the satellite PRN that wants to read the data, and the UTC at the time of observation.
### 第三步third：
运行函数，得出结果。

Run the function and get the result.

此外，程序已打包成独立的可执行文件，附在下面的链接里。

In addition, the program has been packaged as a separate executable, attached to the link below.

链接：https://pan.baidu.com/s/1X_VnrvES0krwW7GJaJVrVw

提取码：eqzt

*感谢**moein mehrtash**在MATLAB论坛里分享的UTC2GPST函数，原地址：https://ww2.mathworks.cn/matlabcentral/fileexchange/41364-gps-navigation-toolbox*

Contect : 1012181115@cugb.edu.cn

### 附第一次更新Attached is the first update

增加文件选择功能，并去除一些无效语句。

Added file selection function, and remove some invalid statements.
