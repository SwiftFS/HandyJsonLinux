# HandyJsonLinux

HandyJsonLinux 完全基于 [HandyJson](https://github.com/alibaba/HandyJSON)使HandyJson能在Linux上运行便于开发SwiftWeb开发，需要配套使用swift-mysql

并作出了一下改动
1. 添加对Date反序列化转换的支持，切为空时不显示
2. 添加对swift-mysql的AutoincrementID 自增对象反序列化支持
3. 删除和修改了一些linux 上编译出错的库，是能够运行在linux上


使用
>.Package(url: "https://github.com/kuhippo/HandyJsonLinux.git", majorVersion: 0, minor: 0),

更多使用请参考[HandyJson](https://github.com/alibaba/HandyJSON)

