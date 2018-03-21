# fast-delete
快速删除 node_modules、Android项目等一些目录结构比较深或小文件比较多的文件夹
## 使用环境
* windows 系统
* [node.js](https://nodejs.org)，推荐 8.x 版本

## 使用说明
* 首次使用，在项目根目录执行 ```npm install``` 命令，会在根目录生成 ```build``` 注册表文件
```
-build
  -install.reg 添加注册表
  -uninstall.reg 删除注册表
```
* 运行 ```install.reg``` 将会添加删除程序到邮件菜单，鼠标右键选择要删除的目录就可以在看到"快速删除"功能了; 运行 ```uninstall.reg``` 删除相应的功能
* 在项目根目录打开cmd，执行 ```npm run reg``` 命令生成新的注册表文件
* 无聊的话也可以通过 ```node ./src 路径1 路径2 ...``` 删除文件

## 感谢
😂 参考了 [itvincent-git/fast-delete](https://github.com/itvincent-git/fast-delete) 同学的实现



