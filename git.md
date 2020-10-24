    
## git安装

  1、安装git客户端（windows操作）
                    git bash  支持linux命名的git控制台 （常用）
                    git CMD   支持windows命令的控制台

​		git GUI   git可视化界面

​                苹果电脑(自带git)

 2、VSCode 安装git插件(自己百度)
                    快捷键 ctrl + ~

  3、github官网网站  注册账号



## git操作的具体步骤

​                 1、cd 路径 进入当前目录
                  2、配置git基本操作
                        【注】没有消息就是好消息。

​                3、 git init   在本地进行初始化(建立暂存区)
                    .git 文件存储当前项目的所有版本信息
                
​                4、工作区 => 暂存区
                    git add 文件名
                    git add * 提交所有文件

​                    git commit -m "这一次提交的描述"

​                5、查看当前工作区的状态
                    git status

​                6、从暂存区恢复文件到工作区
                    git checkout 文件名
                
​                7、查看工作区和暂存区版本的区别
                    git diff

​                8、clear  清屏操作

​                9、git log
                    查看已经提交到暂存区的历史版本

​                10、恢复文件到指定的某一个版本
                    git reset --hard  版本号

​                11、生成ssh密匙
                    ssh-keygen -t rsa –C "你github邮箱"

​                windows电脑查找文件: 我的电脑 => 用户 => 用户名文件夹 => .ssh(隐藏文件) => id_rsa.pub(存有密匙)

​                12、github账户配置密匙

​                13、暂存区 => 远程仓库
                    git remote add origin https://github.com/BullFei/testDemo.git
                    git push -u origin master

​                【注】提交过程，可能需要你输入用户名，密码。

​                14、git clone
                    从远程仓库，克隆项目到本地

​                15、git pull
                    从远程仓库同步本地代码(更新)