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
+ 拷贝文件(file0 --> file1)
```
cp -r file0 file1
```
+ git 跳转至指定版本
```
git log
git reflog
> 44d4d0e HEAD@{0}: commit: 3
fe6cd0f HEAD@{1}: commit: 2
997b12c HEAD@{2}: commit: 1

git reset --hard hash
```
