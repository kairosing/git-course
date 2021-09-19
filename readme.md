# Git and Github Course

Crash course for Git

What were the teams
git init
1 git status
2 git add .  
3 git commit -m "..." закомитить
4 git branch список веток
5 git branch new branch создать ветку
6 git branch -D new branch удолить ветку
7 git checkout new branch  переключатся между веткаими
8 git checkout -b new new branch  переключить и создать новую ветку
9 git merge new branch     совмистить ветки

Вести наши данные чтобы Гит смог связаться с нами

git config --global user.name
Если мы хотим его изменить
git config --global user.name "пишим новое имя"
точно такая же команда для email
git config --global user.email


git remote add origin git@github.com:kairosing/git-course.git
git push -u origin master

fatal: 'master' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
