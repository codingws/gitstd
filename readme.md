# 개발자 git 기본 학습 시작

## 기본명령어 학습
git clone https://github.com/leader337/gitstd.git

git pull origin master

git push origin master

git commit -m "변경 사항을 기록"

git log: 지금까지 작업한 커밋을 모두 확인합니다.

git checkout: 원하는 지점으로 파일을 돌릴 수 있습니다. 커밋체크섬값 활용 예)  git checkout a86c319

$ git branch: 브렌치 확인


## git으로 고나리하는 파일의 네가지 상태
- 추적안됨(untracked): 파일만 생성했을때
- 스테이지됨(staged): add 명령어를 이용.(추적안됨에서 스테이지됨)  로컬저장소 등록 준비, 이후 계속 추적됨
- 커밋(commited): 로컬저장소에 하나의 스냅샷형태로 기록
- 원격저장소(push): 원격저장소에 기록
