### 百度网盘直接下载助手 直链加速版

#### 使用必读

本版本基于 [百度网盘直接下载助手 眾人拾柴版]) 修改, 大幅加快通过直链的下载速度, 实测100M光纤下载大文件速度高达11MB/s

小文件推荐使用 [下载助手]-[直接下载]

大文件推荐使用 [下载助手]-[显示链接]

均推荐使用 IDM 进行下载 ([IDM 下载地址](http://internetdownloadmanager.com/download.html))

Tips: 被列入百度黑名单的用户, 退出账号后获取链接即可达到最大速度

#### 三种下载方法说明：

*   1：使用百度云网盘获取下载的方法，得到的下载地址包含在一个302重定向中，当浏览器自动执行重定向时
    会调用浏览器下载工具去下载文件。如果第三方下载插件是监视浏览器的下载事件（例如IDM。迅雷应该是监视
    的链接的click事件，所以有可能迅雷不会下载），就会调用第三方下载软件。

        这个下载地址是可以在外部使用的，不需要cookie，所以没有办法调用下载工具的可以让浏览器先下载，再去
    复制下载链接到下载工具。（由于浏览器设计成收到302响应时，会自动执行跳转，没有办法用javascript去拦截，也就没有办法提取下载地址）

        这个链接有8h的时间限制，可能会被限速

        当下载对象为文件夹或者多个文件时，会生成打包后的下载地址，这个地址可以直接复制使用
*   2：使用APP软件获取下载链接的方法，得到的地址就是直接下载地址。该方法使用百度云的ID，这个地址需要cookie的支持，能够传递cookie
        下载工具可以使用。如果被限速则换用方法三测试
*   3：使用百度网盘客户端获取下载链接的方法，得到的是一组不同服务器的下载地址，这些地址可以复制使用，无需cookie
        下载时默认使用第一个地址下载

#### 更新日志:

**2018-03-15** : v1.0 替换外链下载高速通道

**2018-03-23** : v1.1 修复外链无法显示的问题