#  Linux
- pip install -i https://pypi.tuna.tsinghua.edu.cn/simple numpy
- cythonize -3 -i -f -k *.py
- pyinstaller -D -w my_installer.spec
# Network Config
- vi /etc/sysconfig/network-scripts/ifcfg-网卡名称
- systemctl restart network
# delete dir
- rm -rf ./file_dir
# ssh
- ssh username@ip
- scp -r ./file_dir root@ip:/usr/local/
# ch
- chmod +x ./file_name
- chown -R root:root ./file_name
# ls
- 列表化显示文件
```
ls -l
或者
ll
```
- 显示所有文件
```
ls -a
```
# ln
- ln -s source_dir shortcut_dir
# useful config
- /etc/profile
- /etc/sysconfig/network-script/ifcfg-网卡名称
