# git-test
- "mango606/git-test" repository 기준으로 작성
## ✅ repository 생성 시 git command
### …or create a new repository on the command line
```
echo "# git-test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mango606/git-test.git
git push -u origin main
```
### …or push an existing repository from the command line
```
git remote add origin https://github.com/mango606/git-test.git
git branch -M main
git push -u origin main
```
### …or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

## ✅ [git command 모음](https://git-scm.com/book/en/v2)
### 사용자 정보 (최초)
```
git config --global user.name mango606
git config --global user.email mango606@email.com
```
### 설정 확인
```
git config --list
```
### 기존 디렉토리를 Git 저장소로 만들기 (최초)
```
cd /c/user/git-test
git init
git add .
git commit -m "initial project version"
```
### 📌 기존 저장소를 Clone 하기 (최초)
```
cd /c/user
git clone https://github.com/mango606/git-test.git
```
### 파일의 상태를 짧게 확인하기
```
git status -s
```
### 커밋 히스토리 조회하기
```
git log
```
### 📌 새 브랜치 생성하기 & 브랜치 이동하기
```
git checkout -b develop
```
### main 브랜치에 Merge 하기
```
git checkout main
git merge develop
```
### 필요없는 브랜치 삭제하기
```
git branch -d develop
```
### 📌 파일 업로드하기
```
git add .
git commit -m "commit"
git push
```
### 📌 파일 강제 업데이트하기
```
git fetch --all
git reset --hard origin/master
git pull
```
### 기존 repository의 remote 제거
```
git remote remove origin
```
### 새 repository의 remote 추가
```
git remote add origin https://github.com/mango606/git-test.git
```
