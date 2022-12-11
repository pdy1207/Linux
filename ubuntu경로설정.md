### ubuntu

        웹 서버를 실행할 때,기본 경로를 html 혹은 사용자 지정 경로로 설정하는 방법은 다음과 같다.

경로 이동 : `cd /etc/apache2/sites-available` `vim 000-default.conf` 입력 <br>            
            
        약 12번째 줄의 DocumentRoot /var/www/html 부분을 희망하는 경로로 수정 Esc, :,wq로 저장 후 종료   

경로 이동 : `cd /etc/apache2/`  `vim apache2.conf`입력<br>

약 164번 줄의 directory /var/www/html 부분을 희망하는 경로로 수정 Esc, :,wq로 저장 후 종료

#### `service apache2 restart`

※ 주의사항
html을 기본 경로로 설정하려면 index.php를 제거 혹은 다른 경로로 옮겨야 한다.


### `<Directory> 설정`

Require all `granted`: 무조건 허용<br>
Require all `denied`: 무조건 금지<br>
Require ip 10 172.20 192.168.2: 특정 아이피만 접근 허용. <br>
여기서는 10으로 시작하는 아이피, 172.20으로 시작하는 아이피, 192.168.2로 시작하는 아이피 세 개를 허용한 것 같다

`AllowOverride`: .htaccess 파일 작동을 허용할 조건을 설정한다. 보통 All 아니면 None을 쓴다.

