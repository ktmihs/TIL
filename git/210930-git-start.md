# 210930 git start

## init

1. 저장할 git dir생성
2. cd dir
3. git init
4. ~~ 내용 변경 ~~
5. git add filename
6. git remote add remotename git-addr
7. git branch -M rename	(master->main)
8. git push -u remotename branchname	(init으로 첫 push할 때 -u 로 async 맞춰주기)

0. git status	(현재 상태 확인)


## clone

1. github에서 repo 생성
	checked README.md file
2. clone 할 dir로 이동
3. git clone git-addr
4. ~~ 내용 변경 ~~
5. git add filename
6. git commit
	message 작성
7. git push origin branchname
	clone으로 받았을 때, 기본 remotename==origin

0. git status	(현재 상태 확인)


### git 사용 시, 주의사항

1. git add , 전체를 add 하는 `.` 사용 지양
2. commit은 최소한으로 나누어서 하기
	commit message는 한글 대신 영어로, prefix를 달아 구분짓기
	ex) docs: commit-message
3. commit message 작성 시, -m 사용 지양
	message 작성 시, 다음 줄로 넘어가면 수정할 수 없기 때문

