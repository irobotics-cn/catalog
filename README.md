# 产品型号

| 字段            | 格式                              | 位数
| --------------- | --------------------------------- | --------------- 
| 总型号          | AB0123C-D4E5F6G7H8I9J             | 20位
| 主型号          | AB0123C                           | 7位
| 子型号          | D4E5F6G7H8I9J                     | 13位

| A | B | 0 | 1 | 2 | 3 | C | D | 4 | E | 5 | F | 6 | G | 7 | H | 8 | I | 9 | J 
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
|机器类型|机器样式|尺寸高位|尺寸低位|载重高位|载重低位|附属功能|设备名一|设备号一|设备名二|设备号二|设备名三|设备号三|设备名四|设备号四|设备名五|设备号五|设备名六|设备号六|定制子类

## 机器类型(A)

| 代号 | 简称 | 状态 | 说明
| ---- | ---- | ---- | ----
| A    | acke | 有效 | 三轮前驱/单舵轮/阿克曼转向
| C    | carl | 有效 | 四轮前驱/类似轿车/阿克曼转向
| D    | diff | 可靠 | 差分双驱/多个万向轮
| O    | omni | 有效 | 全向三驱

## 机器样式(B)

| 代号 | 简称 | 状态 | 说明
| ---- | ---- | ---- | ----
| C    | circ | 可靠 | 圆形
| R    | rect | 可靠 | 长方形/长宽4:3比例
| S    | squa | 可靠 | 正方形

## 尺寸(01)

尺寸：以方形对角线长度或圆形直接为计量，以0.1米为单位，例如R10代表对角线1.0米的长方形，即长0.8米宽0.6米。

| 代号 | 简称 | 状态 | 说明
| ---- | ---- | ---- | ----
| 10   | 1.0m | 稳定 | R10=0.8m*0.6m

## 载重(23)

载重：以实际负载重量的测试数值为计量，以0.1吨为单位，例如12代表载重1.2吨。

| 代号 | 简称 | 状态 | 说明
| ---- | ---- | ---- | ----
| 01   | 0.1t | 稳定 | 01F=背负0.1t

## 附属功能(C)

| 代号 | 简称 | 状态 | 说明
| ---- | ---- | ---- | ----
| C    | cony | 有效 | 滚筒式
| F    | frei | 稳定 | 背负式
| L    | lift | 有效 | 顶升式
| S    | subm | 有效 | 潜伏式
| T    | trac | 有效 | 牵引式

## 设备(D4/E5/F6/G7/H8/I9)

设备：以设备启动顺序、重要性以及网口、串口、其他设备的顺序排列，最多列6个主要设备，缺省以0补齐。

| 代号 | 简称 | 状态 | 说明
| ---- | ---- | ---- | ----
| A0   | aqmd | 可靠 | [艾思控6010BLS驱动器(10A)](https://item.taobao.com/item.htm?spm=a1z10.3-c.w1017-1832298033.10.ikPLgk&id=43611304677&)/[中大Z4BLD60-24GN/4GN-30K电机减速器(60w)](https://item.taobao.com/item.htm?spm=2013.1.w4023-15046185396.4.cg7mWB&id=521925201994)
| A1   | aqmd | 稳定 | [艾思控6010BLS驱动器(10A)](https://item.taobao.com/item.htm?spm=a1z10.3-c.w1017-1832298033.10.ikPLgk&id=43611304677&)/[中大Z5BLD100-24GN/5GU-30KB电机减速器(100w)](https://item.taobao.com/item.htm?spm=2013.1.w4023-15046185396.4.cg7mWB&id=521938724571)
| A2   | aqmd | 有效 | [艾思控6020BLS驱动器(20A)](https://item.taobao.com/item.htm?spm=a1z10.3-c.w1017-1832298033.14.ikPLgk&id=40349035788&)/[中大Z5BLD200-24GU-30S/5GU-15KB电机减速器(200w)](https://item.taobao.com/item.htm?spm=2013.1.w4023-15046185396.4.cg7mWB&id=531085187774)
| A3   | aqmd | 有效 | [艾思控6030BLS驱动器(30A)](https://item.taobao.com/item.htm?spm=a1z10.3-c.w1017-1832298033.18.ikPLgk&id=527343077948&)/[中大Z5BLD400-24GU/5GU-5KB电机减速器(400w)](https://item.taobao.com/item.htm?spm=2013.1.w4023-15046185396.4.cg7mWB&id=521935657506)
| A4   | aqmd | 有效 | [艾思控6030BLS驱动器(30A)](https://item.taobao.com/item.htm?spm=a1z10.3-c.w1017-1832298033.18.ikPLgk&id=527343077948&)/[中大Z5BLD400-24GU-M/5GU-36KB电机减速器(400w)](https://item.taobao.com/item.htm?spm=2013.1.w4023-15046185396.4.cg7mWB&id=521926395578)
| B0   | batt | 可靠 | 电池(待分类)
| C0   | kine | 有效 | [微软KINECT立体相机(3.5m/仅室内)](https://item.taobao.com/item.htm?spm=a1z10.3-c.w4002-10586654395.42.1TMZHl&id=526244283637)
| C1   | xtio | 稳定 | [华硕XTION立体相机(3.5m/仅室内)](https://item.taobao.com/item.htm?spm=a1z10.3-c.w4002-10586654395.33.1TMZHl&id=44561650295)
| C2   | real | 有效 | [英特尔REALSENSE-R200立体相机(3.5m/仅室内)](https://item.taobao.com/item.htm?spm=a1z10.3-c.w4002-10586654395.48.1TMZHl&id=45304310641)
| C3   | ster | 有效 | [双目ZED立体相机(20m)](https://item.taobao.com/item.htm?spm=a1z10.3-c.w4002-10586654395.54.1TMZHl&id=535754347237)
| E0   | tool | 可靠 | 电气工具/耗材
| E1   | tool | 可靠 | 空气开关/急停开关/自锁开关/复位开关/旋钮开关
| E2   | utek | 有效 | [宇泰UT-8801转换线(usb转232)](https://detail.tmall.com/item.htm?spm=a230r.1.14.1.u1PX70&id=19905046101&ns=1&abbucket=10)
| E3   | slzd | 有效 | [深联智达CP2102(usb转ttl)](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.WkqyC2&id=521060723445&_u=52rjb5b3bad)
| E4   | utek | 稳定 | [宇泰UT-891转换线(usb转485/422)](https://detail.tmall.com/item.htm?spm=a230r.1.14.1.i0D3OT&id=27211688588&ns=1&abbucket=10)
| E7   | tool | 稳定 | 网口交换机/usb集线器hub/延长线/扩展线
| E8   | tool | 可靠 | 航空插头/连接器/分线器/端子排
| E9   | tool | 可靠 | 人机交互设备(声/光/电)
| G4   | jyzk | 有效 | [维特JY-901B/MPU9250/GPS惯导模块(9轴/GPS)](https://item.taobao.com/item.htm?spm=2013.1.0.0.xfyuXv&id=528753863432)
| G5   | jyzk | 有效 | [君悦JY-901B/MPU9250/GPS惯导模块(9轴/GPS)](https://item.taobao.com/item.htm?spm=2013.1.0.0.xfyuXv&id=520651228572)
| G6   | jyzk | 稳定 | [君悦JY-61/MPU6050惯导模块(6轴)](https://item.taobao.com/item.htm?spm=2013.1.0.0.jqJ8EB&id=520648845395&scm=1007.10115.11446.100200300000000&pvid=98cf8d80-e8ac-4d1f-864d-a7623449a006)
| G7   | jyzk | 有效 | [君悦JY-901B/MPU9250惯导模块(9轴)](https://item.taobao.com/item.htm?spm=2013.1.0.0.jqJ8EB&id=42861201221&scm=1007.10115.11446.100200300000000&pvid=869e2471-f413-4fff-a540-a2219dbe83d2)
| G8   | uran | 有效 | [超核6/MPU6050惯导模块(6轴)](https://item.taobao.com/item.htm?spm=a1z10.3-c.w4002-11186056617.30.OuVeRx&id=26915396185)
| G9   | uran | 有效 | [超核9/MPU9250惯导模块(9轴)](https://item.taobao.com/item.htm?spm=a1z10.3-c.w4002-11186056617.12.OuVeRx&id=10036936488)
| H0   | hoku | 有效 | [北阳UST-05LN/LA激光雷达(4m/仅避障/仅室内)](http://www.hokuyo-aut.jp/02sensor/07scanner/ust_05ln_05la.html)
| H1   | hoku | 可靠 | [北阳UST-10LX激光雷达(10m/仅室内)](http://www.hokuyo-aut.jp/02sensor/07scanner/ust_10lx_20lx.html)
| H2   | hoku | 可靠 | [北阳UST-20LX激光雷达(20m/仅室内)](http://www.hokuyo-aut.jp/02sensor/07scanner/ust_10lx_20lx.html)
| H3   | hoku | 可靠 | [北阳UTM-30LX-EW激光雷达(30m)](http://www.hokuyo-aut.jp/02sensor/07scanner/utm_30lx_ew.html)
| I5   | inte | 可靠 | [英特尔NUC-D54250WYK工控机(i5-4250U)](https://item.taobao.com/item.htm?spm=a1z10.5-c-s.w4002-15021568328.19.1hp8qX&id=37602604919)
| I6   | inte | 可靠 | [英特尔NUC-6i7KYK工控机(i7-6770HQ)](https://item.taobao.com/item.htm?spm=a1z10.5-c-s.w4002-15021568328.29.j034JL&id=529495909029)
| I7   | inte | 可靠 | [英特尔NUC-5i7RYH工控机(i7-5557U)](https://item.taobao.com/item.htm?spm=a1z10.5-c-s.w4002-15021568328.19.M25shb&id=45304992800)
| L1   | slam | 稳定 | [思岚A1激光雷达(6m/仅室内)](https://item.taobao.com/item.htm?spm=a1z10.3-c.w4002-14130416734.15.qutj8h&id=530250208226)
| L2   | slam | 有效 | [思岚A2激光雷达(6m/仅室内)](https://item.taobao.com/item.htm?spm=a1z10.3-c.w4002-14130416734.12.qutj8h&id=530545450824)
| L3   | quan | 有效 | [固态S3激光雷达(150m/乱序扫描)](http://www.quanergy.com/products/)
| L4   | velo | 有效 | [威力登VLP-16激光雷达(100m/16线)](http://www.velodynelidar.com/vlp-16.html)
| L8   | quan | 有效 | [全向M8-1激光雷达(150m/4线)](http://www.quanergy.com/products/)
| M0   | tool | 可靠 | 机械工具/耗材
| M1   | tool | 稳定 | 联轴器/法兰
| M2   | tool | 稳定 | 轴承
| M9   | tool | 稳定 | 机械扩展设备(升降销/牵引挂钩)
| P1   | siem | 稳定 | [西门子S7-200SMART/SR20模块(PLC)](https://item.taobao.com/item.htm?spm=a230r.1.14.1.6d5u0E&id=537405774390&ns=1&abbucket=10#detail)
| P2   | siem | 稳定 | [西门子S7-200CN/224XP模块(PLC)](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.F4TxxK&id=12568845358&_u=f2rjb5be16f)
| R0   | rout | 可靠 | 无线wifi路由器
| R1   | rech | 待定 | 有线自动充电器
| R2   | rech | 待定 | 无线自动充电器
| R3   | rfid | 待定 | 自动进出电梯
| T0   | tool | 可靠 | [罗技F710无线手柄](https://detail.tmall.com/item.htm?spm=a230r.1.14.1.ZuXyJi&id=7835436172&ns=1&abbucket=10&skuId=77236990620)
| T1   | tool | 可靠 | [树莓派2.4G迷你无线鼠标键盘](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.F4TxxK&id=521081934189&_u=f2rjb5b8f3a)
| T2   | tool | 可靠 | [树莓派7寸通用HDMI触摸屏](https://detail.tmall.com/item.htm?spm=a230r.1.14.4.wq2AXR&id=524214970841&ns=1&abbucket=7)
| T3   | tool | 可靠 | [金沙滩LA1010逻辑分析仪](https://item.taobao.com/item.htm?spm=a230r.1.14.1.jbvFw4&id=20369792793&ns=1&abbucket=4#detail)
| S0   | sick | 有效 | [西克TIM310激光雷达(4m/仅避障/仅室内)](https://www.sick.com/cn/zh/tim3xx/tim310-1030000/p/p244048)
| S1   | sick | 可靠 | [西克TIM561激光雷达(10m/仅室内)](https://www.sick.com/cn/zh/tim5xx/tim561-2050101/p/p369446)
| S2   | sick | 可靠 | [西克LMS111激光雷达(20m)](https://www.sick.com/cn/zh/lms1xx/lms111-10100/p/p109842)
| S3   | sick | 可靠 | [西克TIM571激光雷达(25m/仅室内)](https://www.sick.com/cn/zh/tim5xx/tim571-2050101/p/p412444)
| S5   | sick | 稳定 | [西克LMS141激光雷达(40m)](https://www.sick.com/cn/zh/lms1xx/lms141-05100-security-core/p/p389544)
| S5   | sick | 可靠 | [西克LMS151激光雷达(50m)](https://www.sick.com/cn/zh/lms1xx/lms151-10100/p/p141840)
| S8   | sick | 稳定 | [西克LMS511激光雷达(80m)](https://www.sick.com/cn/zh/lms5xx/lms511-11100-lite/p/p246747)

## 定制子类/型号校验(J)

校验：A-Z分别代表10-35，合并0-9后即有0-35。

| A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X | Y | Z 
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
| 10| 11| 12| 13| 14| 15| 16| 17| 18| 19| 20| 21| 22| 23| 24| 25| 26| 27| 28| 29| 30| 31| 32| 33| 34| 35

校验位使型号20位编码求和后对35取模为0，即使“ sum(型号20位编码) mod 35 = 0 ”成立，并编入程序计算；
否则为定制子类，依照以下表格说明。

| 代号 | 简称 | 状态 | 说明
| ---- | ---- | ---- | ----
| X    | todo | 待定 | todo

## 示例说明

| 说明            | 型号
| --------------- | --------------------- 
| continental     | DR1001F-S2A1G6I50000W
| 差分双驱/多个万向轮 | D
| 长方形/长宽4:3比例 | R
| R10=0.8m*0.6m | 10
| 01F=背负0.1t | 01
| 背负式 | F
| 主型号          | DR1001F
| 西克LMS111激光雷达(20m) | S2
| 艾思控6010BLS驱动器/中大Z5BLD100-24GN/5GU-30KB电机减速器(100w) | A1
| 君悦JY-61/MPU6050惯导模块(6轴) | G6
| 英特尔NUC-D54250WYK工控机(i5-4250U) | I5
| sum(型号前19位编码 = 143) mod 35 = 3 故校验位取 35 - 3 = 32 | W
| 子型号          | S2A1G6I50000W

## 状态说明

| 状态            | 说明
| --------------- | --------------- 
| 待定            | 准备阶段/技术论证/产品调研/诸事不宜
| 有效            | 满足有效性/实验阶段/不宜签订订单/可以技术合作
| 稳定            | 满足稳定性/测试阶段/可以签订订单/可以延期发售
| 可靠            | 满足可靠性/成熟阶段/可以即期发售
