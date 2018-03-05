## 快速架设SS服务器

这份教程主要用于手动、快速架设好SS服务器在你的运行Ubuntu或者其他Linux系统的私人服务器上。
全程手动架设，无需担心自动脚本失效或者隐私问题。

## 测试python
在终端输入```python```并按下回车。

如果你没有看到提示"```command not found```"就说明你的服务器已经安装了python，否则请使用```apt-get install python```命令来安装python。

## 安装pip
首先你需要安装pip到你的服务器上，使用```apt-get install python-pip```命令来安装pip。

如果有必要，请在安装完pip后，使用```pip install --upgrade pip```命令来更新pip到最新版本。

## 安装SS服务器
使用```pip install shadowsocks```命令来安装SS服务器，安装完成后，请使用```ssserver```命令来测试是否成功。

## 配置文件
你需要一份json文件来配置你的服务器，这个项目已经包含了一个配置文件的样本，你可以参考并修改其中内容来定制你的服务器。

## 如何使用
使用```ssserver -c YOUR_CONFIG_FILE_PATH -d start```来启动。
使用```ssserver -d stop```来停止。
使用```ssserver -c YOUR_CONFIG_FILE_PATH -d restart```来重启。

---------

## Quick Set Up Your Shadowsocks Server

This is a guide to lead you quick setup your shadowsocks server on you server running Ubuntu or any Linux server support Python.

## Check Python is Installed

Type```python```in terminal then press Enter.

If you didn't see such like "command not found" which means you have Python installed on your server, if not, using```apt-get install python```to install python.

## Install pip

Now you need to install pip for your server.

Using```apt-get install python-pip```to install pip service.

If needed, using```pip install --upgrade pip```to update pip to the newest version.

## Install Shadowsocks Server

Using```pip install shadowsocks```to install shadowsocks server on you server.

After done, try```ssserver```command in terminal to sure install successfully.

## Config File
You need a "```.json```" file to config your server.

This Git include a sample named "```ss-config.json```", replace the password and other options to make your own config file.

## Use 
Using```ssserver -c YOUR_CONFIG_FILE_PATH -d start```to start.
Using```ssserver -d stop```to stop.
Using```ssserver -c YOUR_CONFIG_FILE_PATH -d restart```to restart.
