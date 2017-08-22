/*桌面启动器,
创建图标,双击即可运行程序*/
1、首先在下载一张图片,jpg就可以用,如果jpg不能用,用画图打开图片另存为png格式
2、创建一个名字为xxx.desktop文件,写入一下内容


[Desktop Entry]
Name=pacp
Exec=sudo /home/sti/Desktop/roadtest/run
Icon=/home/sti/Desktop/roadtest/pcap.png
Terminal=true
Encoding=UTF-8
Type=Application
Categories=Application;Development;

	Name:快捷方式显示的名字.
	Exec:只有在Type=Application的时候有效,应用程序的路径
	Terminal:文件是否可在终端中运行.
	Type:类型.
	Categories:应用程序在菜单中显示的类别.
3、chmod +x xxx.desktop(文件加上可执行权限,图标就编程了快捷方式了)
