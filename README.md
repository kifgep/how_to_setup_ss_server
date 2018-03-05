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
