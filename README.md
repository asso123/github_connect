# github_connect

##1. 깃 설치하기(https://git-scm.com/)
깃에 올려야 할 폴더에 들어가서 shift+우클릭 powershell 창 열기 

      git init     입력 후 엔터
      
      -.git폴더가 생성됨

----------------------------------------------------------------------
##2. 깃 설치 후 git bash 열기(폴더에 우클릭해서 선택) ✅:

 🧔 유저 이름 설정
 
            git config --global user.name "asso"
            
 🧔 유저 이메일 설정(반드시 github에 가입했던 이메일 주소와 동일해야한다)
 
            git config --global user.email "seeeun68@naver.com"
            
🧔 내 정보 확인하기

            git config --list
            

⬆️위 연결은 해당 컴퓨터에 한번에 실행하면 됨

-----------------------------------------------------------------------
#github에 코드 입력하기


🍬초기화

            git init

🍬추가할 파일(폴더안에 내용을 모두 올림, .은 모든 파일을 의미한다)

            git add .


🍬히스토리 만들기(-m은 메세지를 의미 "" 안에는 히스토리 이름을 적는다 한글도 상관없음!)

            git commit -m "first commit"

🍬github에 repository를 만들고 그 주소와 연결하기

            git remote add origin https://github.com/asso123/css_flex.git
            

🍬연결이 잘 되었는지 확인하기

            git remote -v (origin이라고 뜨면 잘 연결된거)

github에 올리기

            git push origin master
            
 ------------------------------------------
수정하여 다시 업로드 할 때
1. 기존의 코드를 다운받는 행위를 해야함
    
            git push origin master
            
2. 다시 push 해야함
 
            git push origin master           
            
--------------------------------------------
#git hub협업하는 방법

#사원입장--------------------
1.소스코드 다운로드
 git clone 주소
주소 다운 받는 방법 .
code눌러서 http로 나오는 주소 복사하면 됨
![image](https://github.com/asso123/github_connect/assets/129017021/3cd13144-d249-4b41-bf3f-493a54ad3d53)

드라이브에 빈폴더 하나 만들고 비주얼 스튜디오에서 폴더 열고 뉴터미널에 
git clone 주소
  git clone https://github.com/asso123/Hana_card.git 이거 입력하면 됨
  
  2.브랜치 만들기
  수정해서 다시 깃허브에 올리는거
  
  git checkout -b브랜치 이름  
 git checkout -b seeeun
 
 git add . 
 git commit -m "하나카드"
 ![image](https://github.com/asso123/github_connect/assets/129017021/bb6e9cd9-df96-4880-a810-937bb2e106be)
![image](https://github.com/asso123/github_connect/assets/129017021/a4ec449d-49f2-4505-9275-e1d9aab985b2)

  
  
            
                 
                  
                  
                  
            
            

