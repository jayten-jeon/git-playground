# git-playground
git 을 연습하는 놀이터
### 1. git basic commands

git은 프로젝트 버전 관리를 위한 도구로, 스냅샷을 기록한다고 생각하면된다.

게임에서의 체크포인트 혹은 세이브를 생각하면 된다.

`git config`

- 유저 이름, 유저 이메일 등 과 같은 주요 설정 파일을 수정한다.
- `git config --user.name="NAME" --user.email="EMAIL"` 처럼 사용한다.

`git init`

- 현재 디렉토리를 git으로 버전관리를 시작한다.
- `git init` 을 프로젝트의 루트 디렉토리에서 실행한다.

`git clone`

- 원격에 있는 git repository(저장소) 를 로컬로 복사한다.
- `git clone GIT-URL` 처럼 사용하며, GIT-URL에 있는 저장소를 복사한다.

`git add`

- 현재 작업 디렉토리에 있는 변경 사항들을 커밋 대상으로 추가한다.
- `git add name` name이라는 파일을 추가한다.
- `git add .` 현재 디렉토리의 모든 파일을 추가한다.

`git status`-
- 현재 추가된 (`git add`) 파일 목록을 볼수 있다.

`git commit` 

- 추가된(`git add`) 변경 정보를 커밋한다(저장한다? 기록한다?)
- `git cmmit -m "Write Commit Message"`

`git log`

- 커밋 내역을 볼 수 있다.

`git branch`

- 단독으로 쓸 경우 모든 branch를 보여준다
- `git branch NAME` 으로 쓸 경우, 현재 커밋을 가르키고 `NAME`을 이름으로 갖는 새로운브랜치를 생성한다.

`git checkout`

- 다른 브랜치로 변경한다.
- `git checkout NAME` <NAME> 브랜치로 변경한다.
- `git checkout -b NAME` -b 옵션을 사용할 경우 `git branch NAME; git checkout NAME` 와 동일하다.

`git push`

- 변경 사항들을 원격 저장소에 기록한다?
- `git push REMOTE BRANCH` BRANCH의 변경사항들을 REMOTE에 기록한다.
- `git push origin master` 이렇게 자주 사용한다.
