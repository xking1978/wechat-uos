# wechat-uos
github上没找到2.1.3版的deb包，只好自己动手丰衣足食了

没有任何更改，用makedeb生成自https://aur.archlinux.org/wechat-uos.git

软件的退出要点任务栏里的退出，只点窗口的叉叉是退不了的。

需要自行按官网https://electronjs.org/

用npm install electron或yarn global add electron以全局方式安装electron

安装electron中遇到的问题请查官网说明文档

其它需要的依赖debian会自动安装，在debian11上运行良好

注：如果以前安装的是用makefile或其它方式打的包，最好先卸载再安装，否则容易发生异常，处理也有点麻烦。
