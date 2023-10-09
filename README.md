# wechat-uos
最新2.1.8版：https://theshare.lanzoue.com/iDUIk1a2q8qj
debian12安装运行正常
注：1.包来自deepin论坛，体积大，放不上来，需要可以自行下载。
2.安装前需要先安装依赖：deepin-elf-verify_1.2.0.6-1_amd64
3.安装前需要把之前来自aur库的版本卸载，否则装不上
-----------------------------
github上没找到2.1.3版的deb包，只好自己动手丰衣足食了

没有任何更改，用makedeb生成自https://aur.archlinux.org/wechat-uos.git

软件的退出要点任务栏里的退出，只点窗口的叉叉是退不了的。

需要自行按官网https://electronjs.org/

用npm install electron或yarn global add electron以全局方式安装electron

安装electron中遇到的问题请查官网说明文档，我装的是18.2版本，运行正常

其它需要的依赖debian会自动安装，在debian11上运行良好

注：如果以前安装的是用makefile或其它方式打的包，最好先卸载再安装，否则容易发生异常，处理也有点麻烦。
