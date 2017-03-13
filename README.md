IoT\_OceanConnect\_Device\_Profile\_Demo

Device Profile，即设备描述文件，是开发者上传到华为物联网平台OceanConnect之上的一系列json文件，用来描述设备“是什么”、“能干什么”。

该示例代码提供了两套设备描述文件：

* MultiSensor\_eSDK\_v01
	* 常规模式下的设备描述文件；
	* 包含温度、湿度、电池电量三个服务；
	* 每个服务包含1-2个属性和1-2个命令。
* YourDeviceType\_ManufacturerId\_v01
	* 透传模式下的设备描述文件；
	* 不推荐使用，建议仅在NB-IoT方案的调通阶段尝试；
	* 仅包含一个RawData服务。

上传的设备描述文件需为zip压缩包格式，压缩包名应为deviceType\_manufacturerId\_model.zip的格式。

版本更新

Device Profile Demo v1.0

相关文档

[华为IoT 设备能力描述文件profile开发指南](http://developer.huawei.com/ict/cn/resource/doc?ecologyID=383&productID=0&colname=1&key=%E5%8D%8E%E4%B8%BAIoT%20%E8%AE%BE%E5%A4%87%E8%83%BD%E5%8A%9B%E6%8F%8F%E8%BF%B0%E6%96%87%E4%BB%B6profile%E5%BC%80%E5%8F%91%E6%8C%87%E5%8D%97&curPage=1&pageNum=10&isOpen=undefined)

获取帮助

在开发过程中，您有任何问题均可以至DevCenter中提单跟踪。也可以在华为开发者社区中查找或提问。另外，华为技术支持热线电话：400-822-9999（转二次开发）