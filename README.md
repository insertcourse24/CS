# CS 과제

위의 내용을 모두.md 파일에 정리하여 PR 올려 주시면 될 것 같습니다~<br>
모두 개념 정도만 적어 주시면 되고 너무 깊게 공부하시지 않으셔도 됩니다.<br>
아래에 핵심적인 부분만 자세하게 적어주시면 될 것 같아요<br>

핵심적으로 공부해야할 부분 : <mark>HTTP, json<mark><br>

- - -

## IP란?
> 인터넷에 연결되어 있는 모든 장치들(컴퓨터, 서버 장비, 스마트폰 등)을 식별할 수 있도록 각각의 장비에게 부여되는 고유 주소이다. IPv4, IPV6 두 종류로 나뉜다. IPv4가 전 세계적으로 사용된 첫번째 인터넷 프로토콜이다. 일반적으로 IP주소 라고 하면 IPv4를 말한다. 4개의 숫자를 점으로 분리된 10진수로 표현한 192.168.52.11 의 형태를 가진다. 이를 2진법으로 표현하면 32비트 숫자가 된다. 즉, IPv4는 약 43억개의 주소를 가질 수 있다. 하지만 전세계적으로 인터넷 사용자 수가 급증하면서 IPv4는 고갈될 위기에 처했다. 이러한 고갈 문제를 해결하기 위해 등장한 주소가 IPv6이다. IPv6은 IPv4의 주소체계를 128비트 크기로 확장한 주소이다. 16비트씩 8자리로 각 자리를 콜론으로 구분한다. IPv6은 2<sup>128</sup>개의 주소를 가지고 있어 거의 무한대로 쓸 수 있다. 하지만 비용 문제로 완전히 상용화 되진 못했다.

## DNS란?
> 도메인 네임 시스템의 약자로 IP네트워크에서 사용하는 시스템이다. 원래 IP주소는 숫자로 이루어져 있는데 사람이 외우기 힘들다. 그래서 naver.com 과 같이 사람이 알아볼 수 있도록 ‘별명’을 지어 정리하고 접근하기 쉽게 해준다. 이걸 또 컴퓨터가 알아볼 수 있게 다시 숫자로 바꿔주는 역할도 한다. 아래와 같은 동작과정을 거친다.
<p>
  <ol>
    <li>사용자가 naver.com을 입력하면 도메인 주소들을 가지고 있는 DNS서버에 접속된다.</li>
    <li>naver.com의 IP주소(223.130.192.200)를 확인하고, 사용자 PC에 저달한다.</li>
    <li>사용자가 전달받은 IP주소로 접속하고 화면에 홈페이지가 나타난다.</li>
  </ol>
</p>

## Stateful과 Stateless란?
> 내용

### Stateful과 Stateless의 차이점

## HTTP란?
> 내용
### HTTP 메세지 기본 구조 알아보기
- Start Line
- Header
  - Content-Length
  - Content-Type
  - Host
  - Date
  - User-Agent
  - Accept
- Body
### 상태 코드란?
- 200
- 201
- 300
- 400
- 401
- 403
- 404
- 500
### http 메서드 알아보기 ([참고](https://inpa.tistory.com/entry/WEB-%F0%9F%8C%90-HTTP-%EB%A9%94%EC%84%9C%EB%93%9C-%EC%A2%85%EB%A5%98-%ED%86%B5%EC%8B%A0-%EA%B3%BC%EC%A0%95-%F0%9F%92%AF-%EC%B4%9D%EC%A0%95%EB%A6%AC))
- GET
- POST
- PUT
- PATCH
- DELETE
### http와 https의 차이 알아보기

## 세계표준시(UTC)란?
> 국제적인 표준 시간의 기준으로 쓰이는 시각을 말한다. 1972년 1월 1일부터 시행된 국제 표준시로 국제사회가 사용하는 과학적 시간의 표준이다. UTC에서 0시, 즉 기준점에 달하는 도시는 런던이다.
### 대한민국의 표준시는 무엇인지 **간단**하게 알아보기
<p>
  우리나라는 런던을 기준으로 +9시인 UTC+9가 표준시이다.
</p>

## 캐시란?
>  한번 조회된 데이터를 미리 특정 공간에 저장해놓고 똑같은 요청이 발생하게 되면 저장한 데이터를 제공해서 빠르게 서비스를 제공해주는 것을 의미한다. 즉, 결과를 미리 저장하고 나중에 요청이 오면 그 요청에 대해서 DB또는 API를 참조하지 않고 캐시를 접근하여 요청을 처리하는 기법이다.

## 프록시란?
>  Proxy는 “대리”의 의미를 가지며 프로토콜에 있어서는 대리 응답 등에서 사용하는 개념이다. 인터넷 접속을 할 때 빠른 액세스나 안전한 통신 등을 확보하기 위한 중계서버를 “프록시 서버” 라고 한다. 클라이언트와 웹서버의 중간에 위치하고 있어 대신 통신을 받아준다.

## json이란?
> 내용
### 자신의 이름, 학번, 나이가 들어가는 json배열을 만들어서 아래의 코드 블럭에 적으세요
안예성, 2209, 18의 데이터 한 개와 자신의 정보를 적은 데이터를 만들어 총 2개의 데이터를 만드세요
```json
json 작성하기
```

## .gitignore란?
> 프로젝트에 원하지 않는 백업 파일이나 로그 파일 혹은 컴파일 된 파일들을 Git에서 제외할 수 있는 설정 파일을 말한다.

## URL, URI, URN이란?
> 내용

## .md(markdown)이란?
> 내용
### 많이 쓰는 문법 적기

## 스레드란?
> 하나의 프로세스 내에서 동시에 진행되는 작업 갈래, 흐름의 단위를 말한다.

## 세션이란?
> 비밀번호 등 클라이언트의 민감한 인증 정보를 브라우저가 아닌 서버 측에 저자아고 관리하낟. 서버의 메모리에 저장하기도 하고, 서버의 로컬파일이나 데이터 베이스에 저장하기도 한다.

## 쿠키란?
> 사용자의 웹 브라우저에 정보를 저장한다. 웹 서버는 쿠키를 생성하여 브라우저로 전송하고, 브라우저는 향후 HTTP 요청에 해당 쿠키를 포함한다.
