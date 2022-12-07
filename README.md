- [sample](https://github.com/loafcheck/branchtest/blob/sample/sample.txt)
- [classnote](##Classnote)
- [how to clone] (#branchtest-git-clone-practice)


-[보이는용](https://www.google.com/)


- [1](#1)
- [1_1](#1-1)
 
# 1 
 
## 1-1

# branchtest-git-clone-practice

- 터미널 창 열기 </br>
- github에서 repository 생성 -> code https 복사하기 (To clone the repository using HTTPS, under "HTTPS", click .)

> 터미널 다시 돌아오기

--먼저 터미널 초기 위치 확인하기/ 바탕화면으로 오기 --

- git clone https주소값복사</br>
예시) </br>
rachelskim@MacBook-Air ~ % git clone https://github.com/loafcheck/branchtest.git 

- cd 파일명</br>
예시) </br>
rachelskim@MacBook-Air ~ % cd branchtest

- git branch // 브랜치 목록 확인

- git branch a

- git checkout a // git switch a 와 같다.

- echo '#hello world a'>> 'hello1.txt'  // 리눅스 명령어 # hello world a 를 써서  hello1.txt 파일 만드세요~</br>
예시)</br>
rachelskim@MacBook-Air branchtest % echo '#hello world a'>> 'hello1.txt'

- git status //현재 내용 확인 가능</br>
예시) </br>
rachelskim@MacBook-Air branchtest % git status
On branch a
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	hello1.txt
nothing added to commit but untracked files present (use "git add" to track)

- git add . 

- git commit -m "a1"

- git push --set-upstream origin a 
	
<br/>
<br/>

## Classnote
-------------

##### $ git branch // 브랜치 목록 확인
##### $ git branch a
##### (main) $ git checkout a // git switch a 와 같다.
##### (a) $ echo '# hello world a' >> 'hello1.txt' // 리눅스 명령어 # hello world a 를 써서  hello1.txt 파일 만드세요~
##### (a) $ git status
##### (a) $ git add .
##### (a) $ git commit -m "a1"
##### (a) $ git push --set-upstream origin a (branch 처음 땄을 때)

![Screen Shot 2022-12-08 at 12 42 15 AM](https://user-images.githubusercontent.com/106638262/206224074-a3e9a9a8-ffe1-4e17-aec8-af098556982e.png)

