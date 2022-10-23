# day01
JavaScript 수업 내용 정리
## 01. 개요
### Web(Front-end)의 3요소
-HTML <br>
-CSS <br>
-JavaScript

### 자바스크립트 개요
1. 스크립트 언어란?
2. 자바스크립트란?
3. 장단점
4. 자바스크립트 소스코드 작성 위치에 따른 종류
    1) inline
    2) internal
    3) external

***
## 02. 자바스크립트에서의 입출력
0. 자바스크립트 데이터 입출력 관련 객체들
    1) window
    2) document
1. 데이터 출력하는 기본 구문
    1) window.alert('알림창에 출력할 문구');
    2) window.console.log('콘솔창에 출력할 문구');
    3) document.write('화면에 출력할 문구');
    4) 선택한요소.innerHTML/innerText = '해당 요소에 출력할 문구';
2. 데이터를 입력받는 기본 구문(변수에 대입 가능)
    1) 변수 = window.confirm("질문내용");
    2) 변수 = window.prompt("질문내용");
    3) 변수 = 선택한요소.속성;(id, className, innerHTML, innerText, ...);
    4) 변수 = 선택한input요소.value;
 
