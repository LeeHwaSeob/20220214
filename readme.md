- 1 gitignore
 > git init > .git 폴더 생성
 내가 굳이 이폴더는 올릴 필요가 없는 파일 혹은 디렉토리
아이디와 패스워드를 저장하는 text 파일
node_modules 코드가 많다
package-lock.json <--

git rm -r [파일명] # 로컬과 원격저장소를 다 지우는 행위 
git rm --cached -r [파일명] # 원격 저장소에서만 지움

프로젝트 폴더에서 .gitignore 파일을 생성해주세요