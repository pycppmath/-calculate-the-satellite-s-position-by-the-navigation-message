# calculate the satellite's position by the navigation message
# MTALAB 由导航电文计算卫星在地固坐标系中的坐标 calculate the satellite's position by the navigation message
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
