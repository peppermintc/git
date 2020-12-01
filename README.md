### git config --list: git 설정 보기

### git config --global -e: 설정 에디터로 켜기

### git blame: 커밋을 식별 할 때 사용, 소스의 각 줄을 마지막으로 수정한 사람이 누구인지, 어떤 커밋에서 변경사항이 적용되었는지 알려줌

### git ls -al

- -a는 all, 모든 항목
- -l는 long format, 긴 형식
- -al은 모든 항목을 긴 형식으로

### git rm -rf .git

- -r은 recursive, 하위 디렉토리를 포함하여 모든 내용 삭제
- -f는 force, 강제로 삭제

### git config --global alias.st status: 단축명령어 설정

- alias: 별명

### Staging Area

- 저장소에 커밋되기 전, 거치는 중간 단계

### echo 명령어

- 문자열 출력 명령어

### start . 폴더 위치 탐색기로 열기

### echo

- '>' : write or overwrite
- '>>' : append

### cat a.txt b.txt c.txt: 한개 이상의 파일을 이어서 출력

### git log --pretty: log option format 설정

### alias

- git config --global alias.hist: hist 라는 이름의 명령어 만들기

### Merge Conflict를 해결 할 때는 다른 코드를 추가하는것은 지양하는 것이 좋다

### mergetool: vscode, p4merge

### Stash

- 작업하던 내용을 커밋하지 않고 잠시 stash stack에 보관시킬 수 있다
- 다른 브랜치를 체크아웃해서 확인해야하는 경우 작업 내용을 stash stack에 보관 시킨 뒤 확인한다. 확인이 완료된 후 다시 작업 내용을 불러와 작업을 다시 시작 할 수 있다.

### WIP stash

### git reflog로 이전 commit 내역을 볼 수 있고 reset을 이용해서 예전으로 돌아갈수 있다.

### git revert (commit 번호)

- 뜻 돌아가다, 복귀하다, 취소하다
- 특정 commit 선택 취소
- log에 commit 취소 기록을 남길 수 있음
- reset, rebase는 기록이 남지 않음
- commit을 따로 만들지 않는 것도 가능 (--no-commit 옵션)

### git rebase -i (commit 번호)

- interactive rebase

### merge squash

- 하나의 commit으로 병합 merge
