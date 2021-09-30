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
