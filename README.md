Open JDK 다운로드 : https://jdk.java.net/archive/
<br>
이클립스 톰캣 8080포트 오류 해결법 (CMD 관리자 권한으로 실행)<br>
netstat -ano | findstr :8080  //8080포트 사용조회<br>
taskkill /f /pid pid번호      //사용중인 PID번호 종료<br>
<br>
<br>
<br>
jeommechu database <br>
CREATE TABLE lunch ( <br>
    id INT AUTO_INCREMENT PRIMARY KEY, <br>
    menu VARCHAR(255) NOT NULL UNIQUE <br>
);
<br>
