# 

##


##


## 
<img width="710" alt="image" src="https://github.com/SongJwans/comento/assets/104306841/c2f7ed1e-b312-4fbd-bbd6-f4a95569c403">
1. 웹 브라우저가 웹 서버에 요청 대상을 가르키는 URL을 담은 요청(HTTP Request)을 전달한다.
2. 웹브라우저로부터 웹서버에 전달된 요청을 Spring Web MVC 엔진이 받는다. 스프링 엔진은 요청된 URL과 일치하는 컨트롤러 액션 메소드를 찾아서 호출한다.
3. 컨트롤러의 액션 메소드는 데이터를 Model 객체에 넣고 뷰의 이름을 리턴한다.
4. 그 이름의 뷰는 실행되고 HTML태그들도 출력한다.
5. 뷰가 출력한 HTML 태그들이 웹브라우저에 전송된다. 이 전송은 최초 웹브라우저의 요청(http request)에 대한 응답(http response)이다.
6. 웹 서버로부터 전송된 HTML 태그들이 웹브라우저에 표시된다.
