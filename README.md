# TIL

> 오늘 배운 것을 기록합니다.
> GITHUB 연습입니다.

명령어

1. 파일 생성
touch a.txt
touch b.txt c.txt d.txt (여러 개를 한번에)

2. 폴더 생성
mkdir

3. 폴더 내 파일 목록 보기
ls
ls -a 숨길파일 보이기

4. 이름변경, 위치 이동 
(이동) mv 이름.txt 폴더
ex) mv b.txt test1
(변동) mv (전)이름.txt (후)이름.txt
ex) mv b.txt c.txt

5. 경로 변경
cd 폴더
ex) cd .. 상대경로를 통해 상위 폴더로

6. 삭제
rm (주의 휴지통 안 거치고 바로 삭제)
-r 폴더 삭제

7. 여러가지
pwd 절대 경로의 나의 경로

화면
ctrl + l : 스크롤 올리기
clear : 아예 지우기

start . 
현재 폴더 (gui) 열기


-------------------------------------------------
GIT

1. git 시작하기
git init

2. git 초기 설정
git config --global user.name "이름"
git config --global user.email "깃허브메일"

3. git 파일들의 상태 확인
git status

4. 변경사항 내역 확인
git log
--oneline 한줄로 보기 옵션

5. 무대 위로 올리기
git add 파일명

6. 기록하기
git commit -m "변경 사유"

7. 올리기
git push origin master

-------------------------------------------------