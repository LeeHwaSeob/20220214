- 1 gitignore
 > git init > .git 폴더 생성
 내가 굳이 이폴더는 올릴 필요가 없는 파일 혹은 디렉토리
아이디와 패스워드를 저장하는 text 파일
node_modules 코드가 많다
package-lock.json <--

git rm -r [파일명] # 로컬과 원격저장소를 다 지우는 행위 
git rm --cached -r [파일명] # 원격 저장소에서만 지움

프로젝트 폴더에서 .gitignore 파일을 생성해주세요

git clone [github주소]

- 2 Reset, Revert 커밋을 뒤로 돌아가는 행위

git reset --hard [돌아갈커밋Hash]
git log 에서 hash값 확인 가능
git revert [삭제할커밋Hash값]

- 3 branch > 커밋을 나누는 행위

브랜치 보기
git branch

브랜치 생성
git branch [브랜치명]
ex) git branch test

브랜치 바꾸기
git checkout [브랜치명]
ex) git checkout test

나는 master 브랜치이다

- 4 merge, rebase > 커밋을 합쳐주는 행위
