## 사이트 개발 순서
### Resource 준비
* img, favicon 등

### Header 설정
* meta data 설정
* title 설정
* og 설정
* twitter card 설정
* favicon 설정(IE, PC, SmartPhone)
* Font 설정 (Google Font)
* CSS Reset (css 중에 가장 위에 올라와야 함) CDN을 사용하자

### 공통 부분 설정
* Body 태그를 대신할 wrapper class를 가지는 div를 추가해서 body대신 사용한다.
* 글씨체, 굵기, 색상, 크기 고정으로 설정
* CSS 작명 규칙 설정(Block Element Modifier)
    * __ : ~의 일부분(~의 자식)
    * -- : ~의 상태(btn--success)
    * \- : 이름 띄어쓰기, 일반적인 작명 
* 반복적으로 사용되는 컴포넌트 작성
    * 버튼, 입력 양식 등

### 구조 파악
* Header 작업
    * 로고, 메뉴 Search/로그인/회원가입 버튼 등
    * float 처리에 대한 clearfix를 common으로 작성해 놓는다.
    * a 태그의 underline과 기본 색상을 설정을 common으로 작성해 놓는다.
    * 문서의 텍스트를 지우지 않고 hidden 처리할 때에는 text-intent를 -9999로 한다.(로고 처리)


