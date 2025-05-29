# ZVISIONVIEW 说明书

## 安装与注意事项

- 安装路径当中不能有中文路径

- 目前上位机支持的激光雷达版本
  
  ZVISION EZ6
  
  ZVISION NZ1
  
  ZVISION NZ2

## 上位机概览

![上位机说明书图片制作.jpg](C:\Users\zvision2\Downloads\上位机说明书图片制作.jpg)

![](http://10.1.133.11:8090/download/attachments/138478440/%E4%B8%8A%E4%BD%8D%E6%9C%BA%E8%AF%B4%E6%98%8E%E4%B9%A6%E5%9B%BE%E7%89%87%E5%88%B6%E4%BD%9C.png?version=5&modificationDate=1748504897360&api=v2)

|        |                                                                                                                                                                                                               |                                        |                  |                                                        |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------- | ---------------- | ------------------------------------------------------ |
| 按键功能列表 | 图标                                                                                                                                                                                                            | 功能说明（中文）                               | 功能说明（英文）         | 操作指南                                                   |
| 1      | ![](http://10.1.133.11:8090/download/thumbnails/138478440/%E8%BF%9E%E6%8E%A5.png?version=1&modificationDate=1747895917205&api=v2 "ZP010007-Proton > 上位机说明书 > 连接.png")                                         | 连接传感器                                  | Connect LiDAR    | <br>                                                   |
| 2      | ![](http://10.1.133.11:8090/download/thumbnails/138478440/%E6%96%87%E4%BB%B6.png?version=1&modificationDate=1747895946675&api=v2 "ZP010007-Proton > 上位机说明书 > 文件.png")                                         | 打开离线文件                                 | Offline Data     | 打开离线PCAP文件Load offline PCAP files                      |
| 3      | ![](http://10.1.133.11:8090/download/thumbnails/138478440/%E7%BD%91%E6%A0%BC.png?version=1&modificationDate=1747895977100&api=v2 "ZP010007-Proton > 上位机说明书 > 网格.png")                                         | 网格线设置                                  | Grid Setting     | 对网格线的类型，范围，显示间隔和颜色进行设置                                 |
| 4      | ![](http://10.1.133.11:8090/download/thumbnails/138478440/%E7%BD%91%E6%A0%BC%E7%BA%BF.png?version=1&modificationDate=1747895977341&api=v2 "ZP010007-Proton > 上位机说明书 > 网格线.png")                               | 网格线开关                                  | Grid Switch      | 网格线的显示与隐藏                                              |
| 5      | ![](http://10.1.133.11:8090/download/thumbnails/138478440/%E5%9D%90%E6%A0%87%E8%BD%B4.png?version=1&modificationDate=1747896007207&api=v2 "ZP010007-Proton > 上位机说明书 > 坐标轴.png")                               | 坐标轴开关                                  | Axis             | 坐标轴的显示与隐藏                                              |
| 6      | ![](http://10.1.133.11:8090/download/thumbnails/138478440/%E6%81%A2%E5%A4%8D%E8%A7%86%E5%9B%BE.png?version=1&modificationDate=1747896036901&api=v2 "ZP010007-Proton > 上位机说明书 > 恢复视图.png")                     | 恢复默认视图开关                               | Reset Camera     | <br>                                                   |
| 7      | ![](http://10.1.133.11:8090/download/thumbnails/138478440/%E6%AD%A3%E4%BA%A4.png?version=1&modificationDate=1747896037161&api=v2 "ZP010007-Proton > 上位机说明书 > 正交.png")                                         | 正交视图                                   | Orthographic     | <br>                                                   |
| 8      | ![](http://10.1.133.11:8090/download/thumbnails/138478440/%E3%80%90%E8%A7%86%E5%9B%BE%E3%80%91%E9%80%8F%E8%A7%86.png?version=1&modificationDate=1747896066809&api=v2 "ZP010007-Proton > 上位机说明书 > 【视图】透视.png") | 透视视图                                   | Perspective      | <br>                                                   |
| 9      | ![](http://10.1.133.11:8090/download/thumbnails/138478440/%E5%85%A8%E5%B1%8F..png?version=1&modificationDate=1747896066948&api=v2 "ZP010007-Proton > 上位机说明书 > 全屏..png")                                       | 全屏显示                                   | Fullscreen       | <br>                                                   |
| 10     | ![](http://10.1.133.11:8090/download/thumbnails/138478440/mti-POI%E4%BF%A1%E6%81%AF.png?version=1&modificationDate=1747896096988&api=v2 "ZP010007-Proton > 上位机说明书 > mti-POI信息.png")                           | POI显示                                  | Area of Interest | Show Pointcloud ares of interest                       |
| 11     | ![](http://10.1.133.11:8090/download/thumbnails/138478440/%E9%80%89%E6%8B%A9%E7%82%B9%E5%87%BB.png?version=1&modificationDate=1747896127298&api=v2 "ZP010007-Proton > 上位机说明书 > 选择点击.png")                     | 单点监控<br>                               | Point Monitor    | Show statistics about the selected point               |
| 12     | ![](http://10.1.133.11:8090/download/thumbnails/138478440/%E9%80%89%E6%8B%A9.png?version=1&modificationDate=1747896216693&api=v2 "ZP010007-Proton > 上位机说明书 > 选择.png")                                         | 点云片选                                   | Points Selection | Show related information regarding the selected points |
| 13     | ![](http://10.1.133.11:8090/download/thumbnails/138478440/%E8%A1%A8-%E8%A1%A8%E6%A0%BC_jurassic.png?version=1&modificationDate=1747896187045&api=v2 "ZP010007-Proton > 上位机说明书 > 表-表格_jurassic.png")           | 显示/隐藏 Spreedsheet & Point Monitor 数据区域 | Spreedsheet      | Show / Hide the Spreesheet & point Monitor panels      |
| 14     | ![](http://10.1.133.11:8090/download/thumbnails/138478440/image2025-5-2_17-5-4.png?version=1&modificationDate=1747896186701&api=v2 "ZP010007-Proton > 上位机说明书 > image2025-5-2_17-5-4.png")                     | 导出指定点云数据                               | Save PCD         | Save the current fram data as PCD file                 |

## 点云播放

### 在线点云播放

- 选择对应的IP端口，寻找IP是192.168.10.108的选项
- 选择传感器类型
  - NZ1 和 NZ2 的数据均选择 LIDARNZ1_A2
  - EZ6 选择 LiDarEz6_B2
- 点击连接

![](http://10.1.133.11:8090/download/attachments/138478440/image2025-5-29_15-51-27.png?version=1&modificationDate=1748505086405&api=v2 "ZP010007-Proton > 上位机说明书 > image2025-5-29_15-51-27.png")

### 离线点云播放

- 选定传感器类型
  - NZ1 和 NZ2 的数据均选择 LIDARNZ1_A2
  - EZ6 选择 LiDarEz6_B2
- 点击 Load

- 离线数据存储的路径不能有中文路径
- 前版本离线文件加载性能待优化，建议单次加载的文件大小不b超过500Mb
- 当前的版本读取离线文件的时候，是使用的默认角度文件，可能会造成点云浏览时候的角度不对的问题。（待解决）

![](http://10.1.133.11:8090/download/attachments/138478440/image2025-5-22_14-50-50.png?version=1&modificationDate=1747896650595&api=v2 "ZP010007-Proton > 上位机说明书 > image2025-5-22_14-50-50.png")

![](http://10.1.133.11:8090/download/attachments/138478440/image2025-5-22_14-51-47.png?version=1&modificationDate=1747896707315&api=v2 "ZP010007-Proton > 上位机说明书 > image2025-5-22_14-51-47.png")

## 点云操作

### 点云观察视角

- 鼠标左键拖动：旋转点云
- 鼠标右键拖动：缩放点云
- 鼠标中键拖动：平移点云
- Shift+左键：平移点云
- Ctrl+左键：点云按视角方向轴（即视点到坐标原点的连线）旋转
- Shift+右键：缩放点云

### 点云感兴趣区域

- 该功能支持离线和在线数据的设置
- 点击![](http://10.1.133.11:8090/download/thumbnails/138478440/image2025-5-29_15-53-37.png?version=1&modificationDate=1748505216150&api=v2 "ZP010007-Proton > 上位机说明书 > image2025-5-29_15-53-37.png")按键，弹出设置对话框
- 可以根据航向角，或者坐标轴，或者距离灰度，去保留特定段落的点云

![](http://10.1.133.11:8090/download/thumbnails/138478440/image2025-5-29_15-54-22.png?version=1&modificationDate=1748505261130&api=v2 "ZP010007-Proton > 上位机说明书 > image2025-5-29_15-54-22.png")

### 点云外参调整

暂不支持

## 点云存储

### 离线PCAP的保存

### PCD数据的保存

## 点云数据分析

### 单点监控

单点监控功能可以对选定的特定点进行统计计算，可以选定点在特定帧数内的距离的平均值，标准差；反射率的平均值和标准差。

- 点击![](http://10.1.133.11:8090/download/thumbnails/138478440/%E9%80%89%E6%8B%A9%E7%82%B9%E5%87%BB.png?version=1&modificationDate=1747896127298&api=v2 "ZP010007-Proton > 上位机说明书 > 选择点击.png")，激活点云片选功能；  Click![](http://10.1.133.11:8090/download/thumbnails/138478440/%E9%80%89%E6%8B%A9%E7%82%B9%E5%87%BB.png?version=1&modificationDate=1747896127298&api=v2 "ZP010007-Proton > 上位机说明书 > 选择点击.png") to activate "Pointcloud selection " function

- 激活后，在视窗右侧会自动弹出Point Monitor显示页面。 After activation, the Point Monitor window will pop up.

- 在某个点云上点击鼠标左键，即可选定点云。 Press the left key of mouse to select pointcloud.

- 在点云片选功能激活的情况下，仍可以通过加shift键实现点云视角的操作; During pointcloud selection, you can move around the camera by using SHIFT key

- - Shift+左键：平移点云
  - Shift+右键：旋转
  - Shift+滚轮：缩放点云

- 被选定的点云，会以加粗瑰红色以显示
- 可以利用PointID 和 ![](http://10.1.133.11:8090/download/thumbnails/138478440/image2025-5-26_17-30-24.png?version=1&modificationDate=1748251824578&api=v2 "ZP010007-Proton > 上位机说明书 > image2025-5-26_17-30-24.png")实现点云的增加和删除。 点击![](http://10.1.133.11:8090/download/thumbnails/138478440/image2025-5-26_17-40-33.png?version=1&modificationDate=1748252433023&api=v2 "ZP010007-Proton > 上位机说明书 > image2025-5-26_17-40-33.png")可以迅速删除所有选定点
- 统计的总帧数可以通过Frame Count去设置
- 点击![](http://10.1.133.11:8090/download/thumbnails/138478440/image2025-5-26_17-41-22.png?version=1&modificationDate=1748252482834&api=v2 "ZP010007-Proton > 上位机说明书 > image2025-5-26_17-41-22.png")可以将当前所有计算结果清除，点击![](http://10.1.133.11:8090/download/thumbnails/138478440/image2025-5-26_17-41-50.png?version=1&modificationDate=1748252510210&api=v2 "ZP010007-Proton > 上位机说明书 > image2025-5-26_17-41-50.png")可以保存当前显示的计算结果

![](http://10.1.133.11:8090/download/attachments/138478440/Point%20Monitor.png?version=2&modificationDate=1748252205687&api=v2)

### 点云片选

- 点击![](http://10.1.133.11:8090/download/thumbnails/138478440/%E9%80%89%E6%8B%A9.png?version=1&modificationDate=1747896216693&api=v2 "ZP010007-Proton > 上位机说明书 > 选择.png")，激活点云片选功能；  Click![](http://10.1.133.11:8090/download/thumbnails/138478440/%E9%80%89%E6%8B%A9.png?version=1&modificationDate=1747896216693&api=v2 "ZP010007-Proton > 上位机说明书 > 选择.png") to activate "Pointcloud selection " function

- 激活后，在视窗右侧会自动弹出spreedsheet显示页面。 After activation, the spreedsheet window will pop up.

- 按住鼠标左键，即可实现片选点云。 Press the left key of mouse to select pointcloud.

- 在点云片选功能激活的情况下，仍可以通过加shift键实现点云视角的操作; During pointcloud selection, you can move around the camera by using SHIFT key

- - Shift+左键：平移点云
  - Shift+右键：旋转
  - Shift+滚轮：缩放点云

- 被选定的点云，会以加粗瑰红色以显示
- 可以利用PointID 和 ![](http://10.1.133.11:8090/download/thumbnails/138478440/image2025-5-26_17-30-24.png?version=1&modificationDate=1748251824578&api=v2 "ZP010007-Proton > 上位机说明书 > image2025-5-26_17-30-24.png")实现点云的增加和删除
- 点击![](http://10.1.133.11:8090/download/thumbnails/138478440/image2025-5-26_17-30-57.png?version=1&modificationDate=1748251857281&api=v2 "ZP010007-Proton > 上位机说明书 > image2025-5-26_17-30-57.png")，可以对要显示的元素进行选择（Point, X, Y, Z, Distance, Elevation, Azimuth, Reflectivity, Timestamp）
- 点击![](http://10.1.133.11:8090/download/thumbnails/138478440/image2025-5-26_17-32-31.png?version=1&modificationDate=1748251950986&api=v2 "ZP010007-Proton > 上位机说明书 > image2025-5-26_17-32-31.png")，可以保存当前帧，或者当前帧以后n帧的spreedsheet数据，保存为csv文件

![](http://10.1.133.11:8090/download/attachments/138478440/Spreedsheet.png?version=2&modificationDate=1748251698605&api=v2)

=========================================================================================================================================================================================

![](http://10.1.133.11:8090/download/attachments/138478440/%E5%8A%9F%E8%83%BD%E8%AF%B4%E6%98%8E.png?version=2&modificationDate=1747895871015&api=v2)
