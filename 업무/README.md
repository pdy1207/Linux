## SFTP 접속 명령어
```
1. sftp -P 포트 계정@IP주소

2. Are you sure you want to continue connecting (yes/no)? yes 를 입력

3. 패스워드 입력
```
- [서버접속하는법](https://parkdoyoung98.tistory.com/40)

## 쉘 접속 -> 해당 계정 user 보기 
```
- ssh id@ip 
- cat /etc/passwd
```
#### 해당 그 유저로 들어가기
```
$ su <유저 이름> # 유저 계정으로 이동
$ su - <유저 이름> # 유저 계정의 환경 변수를 가져오며 이동
```
#### 여기서 잠깐 👏
```
whoami
현재 사용자를 확인하는 명령어 입니다.

exit
전환 전 계정으로 돌아가는 명령어 입니다.
```
- [관련링크](https://velog.io/@gusdnr814/%EB%A6%AC%EB%88%85%EC%8A%A4-%EC%82%AC%EC%9A%A9%EC%9E%90-%EB%B0%8F-%EA%B6%8C%ED%95%9C-%EA%B4%80%EB%A6%AC)
- [관련링크2](https://velog.io/@dhkim1522/%EB%A6%AC%EB%88%85%EC%8A%A4-%EA%B6%8C%ED%95%9C-%EA%B4%80%EB%A6%AC)
