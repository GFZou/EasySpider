# 客户端开发编译方式

0. 安装VS2019或以上版本，勾选windows应用程序开发（.Net Framework 4.7.2版本及以上）。

1. 拷贝客户端（可执行程序）servicewrapper文件夹内所有文件到\ServiceWrapperEntry\bin\x64\Debug文件夹（包括Chrome文件夹）

2. 打开sln文件，右键点击解决方案，点击“清理解决方案”后，再点击“还原Nuget包”。

3. 右键点击项目，点击“清理”后，再点击“重新生成项目”。

4. 编译即成功。
