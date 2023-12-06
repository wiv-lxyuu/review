# review

```bash



# 사용자 정보 광역 설정
git config --global user.name "Your Name"

git config --global user.email "your.email@example.com"

# 줄바꿈 자동 변환을 위한 autocrlf 설정
git config --global core.autocrlf true

# 줄바꿈 안전 설정을 위한 safecrlf 설정
git config --global core.safecrlf false

# 기본 편집기 설정 
git config --global core.editor 'code --wait'


# 기본 브랜치 이름을 'main'으로 설정
git config --global init.defaultBranch main

# 현재 작업 디렉토리
pwd

# 현재 작업 디렉토리에 있는 모든 파일과 디렉토리 자세한 정보 표시
ls -al

# 간단한 이름 설정(ex. oneline->lg1)
git config --global alias.'log --oneline' lg1
