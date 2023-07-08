# 개발자 git 기본 학습 시작

## 기본명령어 학습
git clone https://github.com/leader337/gitstd.git

git pull origin master

git push origin master

git commit -m "변경 사항을 기록"

git log: 지금까지 작업한 커밋을 모두 확인합니다.

git checkout: 원하는 지점으로 파일을 돌릴 수 있습니다. 커밋체크섬값 활용 예)  git checkout a86c319

$ git branch: 브렌치 확인


## git으로 관리하는 파일의 네가지 상태
## 파일은 총 4가지 상태
- untracked: 추적안됨.
- tracked: 수정없음, 수정함, 수테이지됨(add 명령어를 이용)

## 아래 명령어로 실제 관리
- 커밋(commited): 로컬저장소에 하나의 스냅샷형태로 기록
- 원격저장소(push): 원격저장소에 기록

## 브랜치 이해
- 기본 브렌치
- 분기된 브렌치
- HEAD를 이용해 위 2개의 브렌치를 포인터 형태로 가르켜 개발자가 보는 시점을 정함.
- 만일 이전 커밋으로 HEAD를 이동해서 해당 시점의 파일을 볼경우 분리된 HEAD(Detached Head) 상태가 된다.

detail-page 에서 작업