# Catalina10.5-Error
Problems after installation of the Catalina system

Problems after installation of the system


App 在macOS 10.5 Catalina 下提示已损坏无法打开解决办法：

在终端输入以下命令：
sudo xattr -d com.apple.quarantine /Applications/xxxx.app（换成你的报错的App路径）
重新打开 App 即可运行
