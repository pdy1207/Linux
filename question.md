<p align="center">
  <img src="https://www.pngarts.com/files/3/Linux-PNG-High-Quality-Image.png" height="160">
  
  <h2 align="center">Question</h2>
  <p align="center">Never give up! <p>
 
  </p>
</p>

###  su (Swich User)

      Swich User 사용자 전환 명령어

- 로그아웃 없이, 다른 사용자로 로그인을 가능하게하는 리눅스 명령어
- 파라미터가 없으면 "su"는 "su root"와 동일(=root 계정으로 로그인)
- 로그인 하려는 계정의 패스워드가 필요하다
- 전환 하려는 계정의 환경변수는 가져오지 않는다.

### sudo (Substitute User Do)


      sudo 명령어는 유닉스 및 유닉스 계열 운영 체제에서, 다른 사용자의 보안 권한, 
      보통 슈퍼유저로서 프로그램을 구동할 수 있도록 하는 프로그램
      
- 로그아웃 없이, 다른 사용자의 권한으로 명령을 실행 가능하게하는 리눅스 명령어
- 파라미터가 없는 "sudo"는 "sudo -u root"와 동일(=root 권한으로 실행)
- 현재 로그인된 계정의 패스워드가 필요
- sudo -l : sudo 사용 시 관련 권한을 확인하는 방법


<hr>

<p align="center">
  <img src="https://www.kibrispdr.org/data/600/git-png-10.png" height="250">
  
</p>


### ll의 기본정리

    rw-/r--/r-- : 권한
    r : read (읽기)
    w : write (쓰기)
    x : execute (실행)

A : 파일 소유자 권한 => rw-
B : 그룹 권한 => r--
C : 외부인 권한 => r--

 - :wq	변경내용 저장하고, 저장모드 종료
 - :q!	변경내용 저장하지 않고 저장모드 종료

 - ls (List)	=>  <br>
      현재 경로에 있는 파일 및 폴더를 보여줌 (사용빈도율 99%)<br>

 - pwd (Print Working Directory)=> <br>
        현재 내가 어디 경로에 있는지? <br>

 - cd (Change Directory) => <br>
      폴더 이동 <br>
      cd .. (뒤로 가기~) <br>
      cd ~ 맨 처음으로 돌아간다 첫경로로 돌아간다 (root) <br>
      Ctrl + c : 탈출 <br>

 - mkdir (Make Directory) =>  <br>
   폴더 만들기<br>

  - clear => <br>
    명령어 창 깔끔하게 정리 <br>

  - vim => ex) vim abc.txt <br>
      에디터 만들어주는 명령어 처음에 i를 눌러 insert 모드로 변경 <br>
      작성 완료 후 esc를 누르고  <br>
      : wq! 입력하면 최종 저장 

  - rm (remove) => <br>
      파일 혹은 폴더를 삭제할 때 사용하는 명령어 	<br>
      rm -rf (권한 무시 강제 삭제) <br>
      ex) rm -rf hello.txt <br>

  - history => <br>
      사용자가 사용한 명령어 내역 보여줌! <br>
      $ history >> history.txt <br>
      내가 사용한 명령어들 택스트로 저장할 수 있다. <br>

  - ll
      ls가 단순 폴더와 파일을 확인 했다면, <br>
      ll은 만든사람, 날짜, 용량, 권한까지 <br>
      더 상세하게 알 수 있다. (자세한 설명은 위를다시보도록.) <br>

  - tail -f <파일이름> <br>
      : 해당 파일을 모니터링할 때 사용하는 명령어

 - `MySQL 나가기 quit이라고 쳐주면 bye라고 해주며 종료된다.`
