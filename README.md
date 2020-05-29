# node-sass

在运行vue项目时，需要node-sass环境配置

1.运行node -p "[process.platform, process.arch, process.versions.modules].join('-')",可以查看需要的node-sass的版本

2.在https://github.com/sass/node-sass/releases找到对应版本下载

3.将下载的文件放在D:\nodejs\node_modules\npm文件夹下

4.在npmrc中添加SASS_BINARY_PATH=D:/nodejs/node_modules/npm/win32-x64-72_binding.node

5.执行npm install node-sass

