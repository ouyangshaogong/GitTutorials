# GitTutorials
GitTutorials

# github的默认分支有master改为main

防止遗忘，特记录以下例子：
## 案例1:

1.克隆

git clone https://github.com/ouyangshaogong/BookManagerSystem.git

2.添加文件

git add 1.txt

3.提交

git commit -m "1.txt"

4.push文件

git push origin main

## 案例2

1.本地创建目录并进入目录

mkdir githubTest

cd githubTest

2.初始化

git init

3.添加内容

git add 1.txt

4.将文件提交到暂时区

git commit -m "1.txt"

5.将本地仓库连接到远端仓库

git remote add origin https://github.com/ouyangshaogong/BookManagerSystem.git

6.将文件push到远端仓库

git push origin main


如果执行git remote add origin https://github.com/Flowerowl/stumansys.git，出现错误：fatal: remote origin already exists 
则执行以下语句：git remote rm origin.

再往后执行git remote add origin https://github.com/Flowerowl/stumansys.git 即可

在执行git push origin main时，报错：　error:failed to push som refs to

则执行以下语句：git pull origin main

先把远程服务器github上面的文件拉先来，再push 上去。

