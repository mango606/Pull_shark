# git-test

## …or create a new repository on the command line
```
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mango606/test.git
git push -u origin main
```
## …or push an existing repository from the command line
```
git remote add origin https://github.com/mango606/test.git
git branch -M main
git push -u origin main
```
## …or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

## git command
```
git add .                                    // 현재 directory 의 모든 파일을 Staging Area 로 이동
git commit -m "messsage"                     // Staging 의 파일들 commit 하기
git push                                     // 저장소에 commit 반영하기

git pull                                     // 저장소에서 commit 가지고 오기
git merge origin/development                 // remote origin의 development branch merge

git config --global user.name                // Set user name
git config --global user.email               // Set user email

git init                                     // git 저장소로 등록

git branch -M main                           //  최초 등록된 master branch 대신 main branch 사용하도록 변경

git remote add origin [url]                  // 원격 remote repository에 추가

git fetch --all                              // Download objects and refs from another repository
git reset --hard origin/master               // Reset current HEAD to the specified state
git pull                                     // Fetch from and integrate with another repository or a local branch SYNOPSIS
```
