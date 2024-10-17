登录 GitHub 网站,创建建一个新的 abc 仓库
开始始一个新项目,假设当在abc目录下,执行如下代三


echo "# abc" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/wyqjx/abc.git
git push -u origin main




##### 注释  begin ######
git init
信息提示: Initialized empty Git repository in /Users/wyq/Desktop/abc/.git/

每一个 Git 项目都需要一个对包进行描述的 README.md 文件

添加所有文件到仓库
git add README.md main.go Makefile

标记为第一个版本
git commit -m "first commit"
##### 注释  end ######
