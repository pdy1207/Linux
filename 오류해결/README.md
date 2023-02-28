## php파일 실행시 다운로드 되는 현상

```
etc/apache2/mods-enabled php8.1.conf

<IfModule mod_userdir.c>
   <Directory /home/*/public_html>
       #php_admin_value engine Off        // 주석처리
   </Directory>
</IfModule>
```
## 아파치 서버 재실행 및 home으로 바로가기

```
sudo service restart apache2 

cd ~ //home으로 바로감 
```
## 우분투에 http가 없어요..

```
최신 우분투는 기본적으로 httpd.conf를 사용하지 않습니다. 대신 전역 설정파일인 /etc/apache2/apache2.conf  를 사용합니다.
```
