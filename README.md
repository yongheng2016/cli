# command-line interface
+ curl代码，重定向到指定文件名
```
curl -L https://raw.githubusercontent.com/FrankFang/nodejs-test/master/index.js > index.js
```
+ 修改bash的命令
```
vim ~/.bashrc  //打开文件
内容：
alias    gst='git status -sb'   //修改命令
```
+ 更改npm配置文件（progress）
```
npm config set key value
npm config set progress:true  //显示进度信息
```
参考：   
[https://docs.npmjs.com/cli/config](https://docs.npmjs.com/cli/config)   
[https://docs.npmjs.com/misc/config](https://docs.npmjs.com/misc/config)
