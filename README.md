# vimdoc
1全局设置:
git config --global user.name 'ptindog'
git config --global user.email 'ptindog@126.com'
2接下来:
您可以在本地创建新的 Git 仓库
mkdir vimdoc
cd vimdoc
git init
touch README.md
git add README.md
git commit -m 'first commit'
git remote add origin 'git@gitcafe.com:ptindog/vimdoc.git'
git push -u origin master
或者提交在本地已有 Git 仓库
cd existing_git_repo
git remote add origin 'git@gitcafe.com:ptindog/vimdoc.git'
git push -u origin master