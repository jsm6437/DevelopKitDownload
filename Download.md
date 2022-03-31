# DevelopKitDownload
Downloads required for development

## 개발 툴 다운로드 (윈도우환경)

### --> JDK Download
https://www.oracle.com/java/technologies/downloads/

###  --> ECLIPSE IDE Download
https://www.eclipse.org/downloads/

### --> VISUAL STUDIO CODE Download
https://code.visualstudio.com/download

### --> INTELLIJ IDEA Download
https://www.jetbrains.com/idea/download/#section=windows  
설치가이드  
https://goddaehee.tistory.com/195  
플러그인 세팅(Spring 등등 plugin에서 적합하게 추가)    
https://tychejin.tistory.com/327  
단축키 정리  
https://jaimemin.tistory.com/1549  

### --> ORACLE Database 11g EE Download
http://www.easyspub.co.kr/20_Menu/BookView/277/PUB

### --> SQL Developer
https://www.oracle.com/tools/downloads/sqldev-downloads.html

### --> Tomcat Download
https://tomcat.apache.org/

### --> 이클립스에 exERD 설치
-- 이클립스 상단 메뉴 Help > Install New Software > Add > Location에 http://exerd.com/update 입력 > Add > Next > Finish

### --> Scene Builder Download
https://gluonhq.com/products/scene-builder/

### --> 파일질라(FTP) 설치
https://filezilla.softonic.kr/download

### --> Putty(SSH) Download
https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html

### --> 이클립스 마켓플레이스 웹 개발 도구
이클립스 -> help -> marketplace -> eMmet 검색 설치 (사용태그 입력후 tab 키로 자동생성)

### --> Python Download
https://www.python.org/downloads/windows/

### --> JSTL 2.0.0 라이브러리
https://jarcasting.com/artifacts/org.glassfish.web/jakarta.servlet.jsp.jstl/2.0.0/

### --> 이클립스 다국어 아스키 코드로 변환 기능 Properties Editor
이클립스 -> Help -> Install New Software

  Work with에 http://propedit.sourceforge.jp/eclipse/updates 주소 추가

### --> 파일업로드 라이브러리
https://commons.apache.org/proper/commons-io/download_io.cgi

https://commons.apache.org/proper/commons-fileupload/download_fileupload.cgi

##### 톰캣10버전부터 List items = upload.parseRequest(new ServletRequestContext(request)); 로 변경 후 기본 아파치 톰캣 업로드 임포트
##### moveFileToDirectory메서드 쓰려면 commons io 라이브러리 추가 후 org.apache.commons.io.FileUtils; import 필요

### --> 다중톰캣 구현
https://wookoa.tistory.com/102

### --> Maven Download
https://maven.apache.org/

### --> STS4 Download
https://spring.io/tools

### --> 전자정부표준프레임워크 포털
https://www.egovframe.go.kr/home/main.do  
설치가이드  
https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:dev4.0:clntinstall  
서버환경 가이드  
https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:dev4.0:svrinstall  
공통컴포넌트  
https://www.egovframe.go.kr/home/sub.do?menuNo=47  
https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=nuberus&logNo=221572217360  
*오라클을 쓸때는 pom.xml에 따로 ojdbc 라이브러리를 추가해준다,  
global properties를 변경해주고 resource/egovframework/egovprops/spring/com 내부의 context-datasource.xml의   
<property name="password" value="${Globals.oracle.Password}"/>로 수정해주자 (연결 비밀번호가 암호화 되있음)


