Open JDK 다운로드 : https://jdk.java.net/archive/
<br><br>
이클립스 톰캣 8080포트 오류 해결법 (CMD 관리자 권한으로 실행)<br>
netstat -ano | findstr :8080  //8080포트 사용조회<br>
taskkill /f /pid pid번호      //사용중인 PID번호 종료<br>
아니면 8081포트 같은 안 쓰는 포트번호로 바꾸세요<br>

