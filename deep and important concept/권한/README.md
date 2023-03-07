## Permission File & Directory / Read & Write & Excute 

#### 권한
```
권한을 주려면 우선 그 해당 파일에 관하여 권한 을 봐야한다 
```
즉, ex) ls -l result.txt 

***-rw-/rw-r/r-- / pdyme  pdyem / 795 / 2월 24 09:46 / result.txt***

1. 소유자 즉 owner 의 권한
2. group의 권한 
3. other의 권한 


이러한 식으로 쪼개서 봐야한다. 이러한 것을 **access mode** 라고 합니다.

- r : read <br>
  w : write <br>
  e : excute 실행 <br>

즉, mod 를 바꿔야한다 확인이 완료가 되었으면 권한을 주고싶은 사용자에게 주면된다. 

--- 

이러한 방법은 다음과 같다.

<details><summary>other 에 read 권한을 제외한다.
</summary>
 <br>
**chmod o-r result.txt**
  
= cat result.txt 파일 실행
</details>


<details><summary>모든 사용자에게 읽음을 추가한다
</summary>
<br>  
  **chmod o+r result.txt**
  
= 모드를 바꾼다 권한을 어떤파일에게
</details>

<details><summary>파일의 소유자가 파일의 내용을 읽을수 없게?
</summary>
<br>
  
**chmod u(user)-r result.txt**
  
이러한 경우는 없지만 가능은하다.
</details>









