# node-sass-
关于node-sass下载不下来的解决方法


下载地址：https://github.com/sass/node-sass/releases

1.险起见在npm cache clean -f 清个缓存，再重新安装

2.https://github.com/sass/node-sass/releases选择试用的运行包，我是win32-x64-72_binding.node，将其放入E:\binding-node的目录下（自己随机放）

3.在执行npm install失败的的目录下执行set SASS_BINARY_PATH=E:\binding-node\win32-x64-72_binding.node

4.执行npm install node-sass 

5.ok，成功下载




参考：https://www.cnblogs.com/sherlock-Ace/p/11095552.html
