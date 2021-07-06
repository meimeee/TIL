# Git basic - 기초

**Git을 쓴다** 

​	폴더를 업그레이드한다. 즉, 해당 폴더 안에 하위 파일 및 폴더를 관리하는 것 



**Git bash 에서의 명령어**

cd ~ : 홈폴더로 가는 것

git init 을 하면 ~/git-practice (master) 라고 뜸   : 폴더를 리포로 업그레이드하는 것 

업그레이드 된 것 =  리포 (Repository) == 저장소

![image-20210705143055889](git-basic.assets/image-20210705143055889.png)



ls -a : 폴더가 뭐가 있는지 보는 것 

rm -rf git : 폴더를 삭제하는 것 



**git init / git add / git commit /** 

**git status / git log**



- git init : 디렉토리(폴더)를 리포로 만들어주는 것 (저장소 초기화하기)

- git status

- git add 파일이름.확장자 :  해당 파일이 있는 

  ​	터미널에서는 파일이름 오타가 많아서 몇글자써주고 tab쓰면 자동완성됨

  ​	만약에 수정 사항이 있으면 git add 파일이름.확장자 해주고 git commit 실행해	야함 

- git commit -m 'message' : 

- git log : 사진 찍는 것 

- git add .  : 전체 파일 넣기 

- 잘못눌렀으면 ctrl + c 누르면 취소할 수 있음 

