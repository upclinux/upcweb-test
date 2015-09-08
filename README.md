# upcweb-test

校园网络稳定性测试工具，可通过一系列常用网址来测试校园网（包括移动网、联通网）是否稳定。此外，此工具也可用于手机数据连接的测试。

测试工具有两组，可分别测试 IPv4 和 IPv6 网络。

该测试工具是跨平台的，支持 Windows、Linux、Mac、Android（需要 ROOT）、iOS（需要越狱）等系统。

## 特色

除了常见的网站（例如百度、百度百科、新浪微博、人人网）以外，该工具还会对常见的开发者网站（例如 RubyGems）进行测试，保证开发过程顺利进行。

## 安装

测试工具是自启动文件，只需放到指定位置，工具即可随系统启动而自动启动。

此外，不同工具可进行合并，以进行多个测试。

## 常见问题

1. 有的时候，在测试过程中，会产生“连接被重置”的错误。这时只需采用 SSL 连接（即手动将待测试网址改成 HTTPS），即可继续进行测试。
2. 由于网络基础设施的原因，以后校园网可能会更不稳定，甚至连接中断。
