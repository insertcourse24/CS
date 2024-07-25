# CS 과제

위의 내용을 모두.md 파일에 정리하여 PR 올려 주시면 될 것 같습니다~<br>
모두 개념 정도만 적어 주시면 되고 너무 깊게 공부하시지 않으셔도 됩니다.<br>
아래에 핵심적인 부분만 자세하게 적어주시면 될 것 같아요<br>

핵심적으로 공부해야할 부분 : <mark>HTTP, json<mark><br>

- - -

## IP란?
> Internet Protocol의 약어
> 인터넷에서 컴퓨터 간(송신 호스트, 수신 호스트)의 패킷데이터를 전달하는데 사용되는 규칙과 규약

## DNS란?
> Domain Name System
> 호스트의 도메인 이름과 호스트의 네트워크 주소를 변환

## Stateful과 Stateless란?
> 내용
### Stateful과 Stateless의 차이점

## HTTP란?
> Hypertext Transfer Protocol의 약어
> 웹브라우저와 웹서버 간 정보를 주고받기 위한 통신 규약
### HTTP 메세지 기본 구조 알아보기
- Start Line : 요청과 응답을 정의하는 첫 번째 줄
- Header : 브라우저가 필요한 정보 전달
  - Content-Length : 메시지 본문의 길이를 바이트 단위로 지정
  - Content-Type : 본문의 데이터 형식을 나타내는 MIME 타입을 지정
  - Host : 요청을 보내는 서버의 도메인 이름 또는 IP 주소와 포트 번호 지정
  - Date : 메시지가 전송된 날짜와 시간을 지정
  - User-Agent : 요청을 보내는 사용자의 식별 정보 `ex) User-Agent: <product 식별자> / <product-version 버전번호> <comment 식별자의 정보>`
  - Accept : 클라이언트가 서버로부터 받고자 하는 콘텐츠 타입을 지정
- Body : 클라이언트가 서버로 데이터를 전송할 때 사용되는 영역
### 상태 코드란?
- 200 : 요청성공 + 서버가 요청한 리소스를 클라이언트에게 반환
- 201 : 요청성공 + 서버에 새로운 리소스 생성
- 300 : 요청된 리소스에 대한 여러가지 응답을 클라이언트가 선택해야함
- 400 : 클라이언트의 요청이 잘못됨
- 401 : 요청된 리소스를 접근하기 위해 클라이언트가 인증되지 않았음
- 403 : 클라이언트의 권한 문제로 인해 요청을 거부함
- 404 : 요청된 리소스를 찾을 수 없음
- 500 : 요청을 처리하는 중 예상치 못한 문제 발생
### http 메서드 알아보기 ([참고](https://inpa.tistory.com/entry/WEB-%F0%9F%8C%90-HTTP-%EB%A9%94%EC%84%9C%EB%93%9C-%EC%A2%85%EB%A5%98-%ED%86%B5%EC%8B%A0-%EA%B3%BC%EC%A0%95-%F0%9F%92%AF-%EC%B4%9D%EC%A0%95%EB%A6%AC))
- GET
- POST
- PUT
- PATCH
- DELETE
### http와 https의 차이 알아보기

## 세계표준시(UTC)란?
> 본초 자오선을 기준으로 지역별로 정한 기준시간
### 대한민국의 표준시는 무엇인지 **간단**하게 알아보기

## 캐시란?
> 내용

## 프록시란?
> 내용

## json이란?
> 내용
### 자신의 이름, 학번, 나이가 들어가는 json배열을 만들어서 아래의 코드 블럭에 적으세요
안예성, 2209, 18의 데이터 한 개와 자신의 정보를 적은 데이터를 만들어 총 2개의 데이터를 만드세요
```json
json 작성하기
```

## .gitignore란?
> git 버전관리에서 제외할 파일목록을 지정하는 파일

## URL, URI, URN이란?
> 내용

## .md(markdown)이란?
> 내용
### 많이 쓰는 문법 적기

## 스레드란?
> 내용

## 세션이란?
> 내용

## 쿠키란?
> 내용
