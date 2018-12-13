## Anaconda安装 ##
    bash Anaconda3-5.0.1-Linux-x86_64.sh
-	安装完成之后需要重启`Terminal`终端，Anaconda才能生效。

-	在安装的过程中，会问你安装路径，直接回车`Enter`默认就可以了。有个地方问你是否将Anaconda安装路径加入到`bash`资源文件`.bashrc`中，输入`yes`，默认的是`no`。

-	如果没输入`yes`就要配置环境变量，在`Terminal`终端输入以下命令使用`gedit`文本编辑器打开`profile`文件：

		sudo gedit /etc/profile

-	在`profile`文件中添加以下语句后，`Ctrl`+`S`保存，然后退出`gedit`。

		export PATH=/home/xiaer/anaconda3/bin:$PATH

-	重启`Terminal`终端，如果还是不行，则重启Linux系统。

-	配置好`PATH`后，可以通过以下命令检查是否正确：

		conda –version

## TensorFlow安装 ##
    conda install tensorflow==1.3.0

## Python版本 ##
	Python 3.6.3