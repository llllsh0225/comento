# IT 대기업 현업 개발자와 함께 하는 백엔드 개발 실무

### 1주차 개발환경 구성

1. Github 계정 생성 (완료)

2. JDK/Tomcat/Eclipse 설치 (완료)
- JDK 1.8u_241 버전 설치 및 환경변수 설정
- Tomcat 9.0.35 버전 설치
- Eclipse 2020.06 버전 설치 및 인코딩 설정 (UTF-8)

3. DB 환경 구축 (완료)
- Oracle 11g / SqlDeveloper 설치
- MOVIE 테이블 생성 및 테스트 데이터 insert

4. 스프링 환경 구축 (완료)
- Spring Framework 5.2.1 RELEASE 버전 설치
- pom.xml dependency 추가 (ojdbc6, spring-jdbc, commons-dbcp2, mybatis, mybatis-spring, log4jdbc)
- root-context.xml 작성
- mybatis-config.xml 작성
- logback.xml 작성
- log4jdbc.log4j2.properties 작성
- test.xml 작성 (MOVIE 테이블 데이터 조회 쿼리 등록)
- Model, View, Controller 코드 작성
- 서버 구동 후 브라우저에서 DB 데이터 조회 확인


### 2주차 API 가이드 문서 작성

1. API 가이드 문서 작성 (완료)
- 표지
- 문서 정보
- API 개요
- API 명세

2. 학습 내용
  - pathVariable : @PathVariable 어노테이션은 Spring에서 제공하는 기능이다. @PathVariable를 사용하면 URL에서 파라미터를 보내서 사용 할 수 있다. 
  
  - JSON (JavaScript Object Notation) : 데이터를 저장하거나 전송할 때 많이 사용되는 경량의 DATA 교환 형식을 의미한다. JSON 표현식은 사람과 기계 모두 이해하기 쉬우며 용량이 작아서, 최근에는 JSON이 XML을 대체하여 데이터 전송 등에 많이 사용되고 있다.
  
  - HTTP 통신 : Hyper Text Transfer Protocol으로, 말 그대로 Hyper Text를 전송하기 위한 프로토콜이다. HTTP 통신은 기본적으로 '요청(Request)'과 '응답(Response)'로 이루어져 있다. 서버에 요청을 보내고, 서버로부터 필요한 파일을 모두 받고 나면 접속이 종료된다. (Connection이 계속 연결되어 있지 않음)
