# Apache 및 php 설치 방법 #

Apache24.zip과 php7.zip을 C드라이브에 압축 풀기 (path가 C드라이브로 설정되어있으니 반드시 C드라이브로 이동할것)  

-	Win + R -> cmd -> “cd C:\Apache24\bin
-	httpd.exe -k install
-	windows 보안경고 액세스 허용

C:\Apache24\bin 폴더에 ApacheMonitor.exe를 실행시키기  
윈도우 하단 작업 표시줄에 아파치 아이콘 눌러 Apache 2.4 Start  
http://localhost 혹은 http://localhost:80/ 또는 http://127.0.0.1 로 접속 테스트 해보기  

*php7.zip을 압축 해제한 경우 php7 사용가능*  
php연동 확인방법 : C:\Apache24\htdocs\ 로 이동한다
 - index.html 파일을 삭제한다
 - index.php 파일을 붙여넣어 준다.
 - http://localhost 혹은 http://localhost:80/ 또는 http://127.0.0.1 로 접속

