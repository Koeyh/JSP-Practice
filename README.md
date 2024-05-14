# JSP-Practice
JSP 개념 ~ 활용 학습

### JSP
- Java Server Page
- HTML 내부에 Java 언어를 삽입하는 형태

### Page Directive
- JSP 페이지의 속성을 지정하는데 사용
- JSP 페이지의 최상단에 위치하며 <%@  %> 태그 내부에 작성됨
- Page Directive 속성
 ![page_directive_info](https://github.com/Koeyh/JSP-Practice/assets/156414715/11844b79-a7bb-4ac7-aabd-fe041dc8c038)


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
