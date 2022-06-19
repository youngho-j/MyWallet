# 이더리움 지갑 배포
  목표 : 자바스크립트 및 노드, HEROKU 활용하여 이더리움 지갑 배포하기

### 1. 궁금한 내용 정리 
---
1. [NodeJS?](#nodejs)  
2. [Express?](#express)  
---

### 2. 수정 목록
----
1. [지갑배포](#지갑-배포)  
2. [지갑 Bootstrap 적용](#지갑-bootstrap-적용)    
3. [QR 코드 생성 기능 추가](#qr-코드-생성-기능-추가)    
----

### NodeJS
<details>
  <summary>자세히</summary>

#### NodeJS?  
  - Chrome V8 JavaScript 엔진으로 빌드 된 JavaScript 런타임  
    - 즉, 노드를 통해 `다양한 JavaScript Application을 실행` 가능, 주로 서버 실행에 많이 사용됨  
    - JavaScript를 서버에서도 사용할 수 있도록 만든 프로그램  
    - V8이라는 JavaScript 엔진 위에서 동작하는 `자바스크립트 런타임(환경)`  
    - 서버사이트 스크립트 언어가 이닌 `프로그램(환경)`  
    - 웹서버와 같이 `확장성 있는 네트워크 프로그램을 제작`하기 위해 만들어짐
  - 자바스크립트를 브라우저 밖에서 사용하게 해주는 프로그램
  - [참고](https://velopert.com/294)  
  - [참고2 - 노드 개념이해](https://hanamon.kr/nodejs-%EA%B0%9C%EB%85%90-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0/)  
  
</details>

### Express?
<details>
  <summary>자세히</summary>

#### Express
  - NodeJS를 위한 빠르고 간결한 웹 어플리케이션 프레임워크  
  - 프레임워크?  
    - 소프트웨어의 구체적인 부분에 해당하는 설계와 구현을 재사용이 가능하게끔 일련의 협업화된 형태로 클래스들을 제공하는 것  
    - 프레임 -> `뼈대`  
  - NodeJS로 간편하게 웹 서버를 구축할 수 있도록 도와주는 웹 프레임워크 

</details>

----

#### 지갑 배포
<details>
    <summary>펼치기</summary>

1. 지갑 계좌 주소 생성 기능 추가
    
2. 계좌 주소로 계좌 조회 기능 추가  
    
3. 계좌 송금 기능 추가
   - 계좌 비밀번호 및 송신 계좌 주소, 보낼 코인 입력 필요  
    
4. 생성한 HTML 배포
   - [HEROKU](https://www.heroku.com) 와 깃헙 연동하여 Deploy  

</details>

#### 지갑 Bootstrap 적용
<details>
    <summary>펼치기</summary>

  1. 기존 기능에 Bootstrap 적용하여 UI 개선  
     - css 파일 추가

</details>

#### QR 코드 생성 기능 추가
<details>
    <summary>펼치기</summary>

  1. 송신 지갑 주소를 통해 QR 코드 생성하는 기능 추가
     - QR 생성 영역 및 생성에 필요한 스크립트 추가

</details>

