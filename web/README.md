## HTTP(HyperText Transfer Protocol)
* 웹상에서 데이터를 주고받기 위한 프로토콜
* 보통은 웹문서(HTML 파일)를 주고받는 데 사용된다.
* 클라이언트는 웹상에서 HTTP를 통신 프로토콜로 사용하여 요청의 목적에 따라 HTTP메서드를 이용하여 통신한다.
* GET요청시 HTML소스코드를 받아오고 클라이언트 프로그램은 이를 그대로 출력했을 뿐이다.

## HTTP 메서드
* GET(READ) - 특정 데이터의 조회를 요청한다 EX) 페이지 접속, 정보 검색
* POST(CREATE) - 특정 데이터의 생성을 요청한다 EX) 회원가입, 글쓰기
* PUT(UPDATE) - 특정 데이터의 수정을 요청한다 EX) 회원 정보 수정, 글수정
* DELETE(DELETE) - 특정 데이터의 삭제를 요청한다 EX) 회원 정보 삭제

## REST API
* 위의 메서드에서 GET을 굳이 READ용으로 사용하지 않아도 된다. 하지만 이러할 경우 혼돈이 생기므로 미리 약속을 하고
아키텍처를 만들어 사용하는 것이다.
* REST API는 위 메서드와 맞게 프로그램 개발하도록 권장한다.
* 각 자원(Resource)에 대하여 자원의 상태에 대한 정보를 주고받는 개발방식을 말한다. 
(서버의 자원을 어떠한 방식으로 접근해야하는지 구체적으로 명시한것 - REST 아키텍처를 따르는 API)

## REST API 규칙
1. 자원(Resource) : URI를 이용하여 표현 EX) https://www.example.com/users
2. 행위(Verb) : HTTP 메서드를 이용하여 표현 EX) 위 예시처럼 URI정하고 원하는 HTTP메서드 사용하여 서버로 요청
3. 표현(Representations)

## JSON (JavaScript Object Notation)
* 데이터를 주고받는데 사용하는 데이터 형식중 하나
* key-value 쌍으로 이루어진 데이터 객체 (javascript 객체형식)

## 서버사이드 렌더링 VS 클라이언트 사이드 렌더링 (SSR vs CSR)
https://jaroinside.tistory.com/24
https://subicura.com/2016/06/20/server-side-rendering-with-react.html
