# review

```bash


# 1. 파일 생성
## 사용자 정보 광역 설정
git config --global user.name "Your Name"

git config --global user.email "your.email@example.com"

## 줄바꿈 자동 변환 설정
git config --global core.autocrlf true

## 줄바꿈 안전 설정
git config --global core.safecrlf false

## 기본 편집기 설정 
git config --global core.editor 'code --wait'


## 기본 브랜치 이름을 'main'으로 설정
git config --global init.defaultBranch main

## 현재 작업 디렉토리
pwd

## 현재 작업 디렉토리에 있는 모든 파일과 디렉토리 자세한 정보 표시
ls -al
#2. 파일 비교(diff)

## 스테이징영역 변경사항 확인
git diff

## 스테이징 영역-최근 HEAD 변경사항 비교
git diff HEAD

## 스테이징 영역-이전 HEAD 변경사항 비교
git diff HEAD~

#3. 파일 삭제 및 복구

## 파일 삭제(스테이징&작업폴더)
git rm <file_name>

## 파일 삭제(스테이징)
git rm --cached<file_name>

## 파일 복구(작업폴더)
git restore <file_name>                           

## 파일 복구(스테이징 영역)
git restore --staged <file_name>                  

## 파일 복구(깃 저장소의 HEAD-작업 폴더)
git restore --source=HEAD --worktree <file_name> 

# 파일 복구(깃 저장소의 HEAD-스테이징,작업폴더)
git restore --source=HEAD --staged --worktree <file_name> 

#4. 
## 간단한 이름 설정(ex. oneline->lg1)
git config --global alias.lg1 'log --oneline'

# 
