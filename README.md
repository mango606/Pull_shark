# git-test

## 현재 directory 의 모든 파일을 Staging Area 로 이동
git add .

## Staging 의 파일들 commit 하기
git commit -m "messsage"

## 저장소에 commit 반영하기
git push

## 저장소에서 commit 가지고 오기
git pull

## remote origin의 development branch merge
git merge origin/development

## Setup
git config --global user.name
git config --global user.email

## git 저장소로 등록
git init

## 최초 등록된 master branch 대신 main branch 사용하도록 변경
git branch -M main

## 원격 remote repository에 추가
git remote add origin [url]
