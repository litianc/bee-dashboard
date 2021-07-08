# bee-dashboard
管理多个bee节点

> 本代码Fork自[iokfine]()，主要解决对 MacOS 的支持。

### MacOS

1. 将nginx.conf配置文件拷贝至nginx配置目录。默认：/usr/local/etc/nginx/nginx.conf，如果没有找到，可以通过 `nginx -t` 命令查看。
2. 将html目录全部文件拷贝至www目录。默认：/usr/local/var/www。
3. 在浏览器上打开 http://localhost
   
*更新配置时，要注意Chrome浏览器的缓存机制，清理缓存文件后再刷新可生效*


### Windows 
1. git pull main分支  （不要放在中文路径下面）或者直接下载

2. 双击 nginx.exe 闪一下

3. 在浏览器上面打开 http://localhost
