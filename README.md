# JSP-Practice
JSP 개념 ~ 활용 학습

### JSP
- Java Server Page
- HTML 내부에 Java 언어를 삽입하는 형태

### Page Directive
- JSP 페이지의 속성을 지정하는데 사용
- JSP 페이지의 최상단에 위치하며 <%@  %> 태그 내부에 작성됨
- Page Directive 속성
 ![page_directive_info](https://github.com/Koeyh/JSP-Practice/assets/156414715/4839687e-bcf8-4236-8f1c-b6e11f18a3d2)



### _JSP 스크립팅 요소_
1. 스크립트릿 <%  %> : Java 코드 블럭
2. 표현식 <%=  %> : 값 출력 시 사용
3. 선언식 <%!  %> : Java 클래스 멤버 변수, 메서드 선언 시 사용

### JSP 페이지 내장 객체
- 내장 객체 : 자주 사용되어지는 객체
- 별도의 선언(import) 없이 사용 가능한 객체
##### 내장 객체 종류
- Request : 웹 브라우저의 요청 정보가 저장된 객체
      - [Request Sample](JSP1/src/main/webapp/RequestLogin.jsp)
- Response : 
- out
- session
- application
- pageContext
- page
- config
- exception

#### JSP를 View로 활용하기
  - 최근 SpringBoot 사용 시 View 구현을 위해 JSP보다 Thymeleaf가 많이 사용되는 추세
  - 그럼에도 활용되는 곳이 많으니 활용법 숙지 필요
  - SpringBoot 프로젝트에서 JSP 활용하기
  - [JSP를 사용한 팀 프로젝트(크라우드 펀딩 사이트 제작)](https://github.com/PUK-Java/PUK-Groupware.git)
