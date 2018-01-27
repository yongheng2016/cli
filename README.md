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
> fe6cd0f HEAD@{1}: commit: 2
> 997b12c HEAD@{2}: commit: 1

git reset --hard hash
```
+ 公钥查询
```
cat ~/.ssh/id_rsa.pub
```
+ 合并分支
```
git xx xxx
```
+ window下打开文件目录
```
start .   //打开当前目录
```
+ 打印文件内容
```
cat a.html b.html   //输出两个文件内容
```
+ 移动、重命名文件
```
mv a.html ..  //移动a.html至上级目录
mv a.html b.html  //a.html重命名为b.html
```
+ 复制文件到目录
```
cp a.html ..  //复制a.html到上级目录
```
+ scp     
[http://linuxtools-rst.readthedocs.io/zh_CN/latest/tool/scp.html](http://linuxtools-rst.readthedocs.io/zh_CN/latest/tool/scp.html)
+ 删除当前版本,同时回到上个版本
```
git reset --hard HEAD^
```
+ 设置淘宝镜像
```
注：打开DOS面板，执行npm config set registry https://registry.npm.taobao.org

如果想恢复默认，打开DOS面板，执行npm config set registry https://registry.npmjs.org
```

+ 复制ssh的公钥
```
$ pbcopy < ~/.ssh/id_rsa.pub
```
