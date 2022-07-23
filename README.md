# vue-webapp

1. 왜 Vue.js인가
 > web-app을 만들 때 주로 사용
 즉 페이지가 새로고침되지 않고 부드럽게 전환되는 사이트 개발 시 주로 쓰인다.
 페이지 전환시 페이지를 새로 요청하는게 아니라, 자바스크립트로 HTML을 대체하며 부드럽게 구현하는 것인데

 Vue React Angular 등고 같은 FE라이브러리르 활용하면 더욱 쉽게 개발이 가능하다.
근데, 그래서 왜 Vue인가?

2. Vue.js vs. React? 
 (1) 뷰만의 쉬운 문법, 그에 대비 JS 기초가 중요한 리액트
 (2) 반복문이나 조건문을 사용할 때, 
      Vue.js : 하나만 사용 ex. v-for, v-if, v-else
      React : 여러가지 존재 ex. {map}, forEach, for for in for of, if else, enum, ... 
      > Vue.js : 협업에 좋음, 접근성 좋음, HTML 렌더링 좋음 (실시간으로 데이터가 많이 바뀌는 코인거랫 등), 업데이트가 잘됨, 등등
      
      
3. Vue.js 설치
 (1) Node.js 설치
 (2) 터미널에서 npm install -g @vue/cli 
   ** npm이란? JS 오픈소스 패키지 모음집
 (3) VS Code 등의 IDE 설치
    ** 코딩을 편리하게 해주는 부가기능 (Extensions) : Vue 3 Snnippets, HTML CSS support, Vetur
    
4. Vue Project 만들기
 (1) vue create [프로젝트명] 
 (2) Open Folder as [프로젝트명]
 (3) App.vue 메인 확인
 (4) 서버 구동 : npm run serve
 
 - npm이라 웹개발에 필요한 라이브러리 설치 모음집, 이를 위해 Node.js 사전 설치 필요
 - 사실상 브라우저는 .vue를 읽지 못함
 - 그래서, public>index.html을 참고하면, App.vue에서 짠 코드를 HTML로 변환하여 크롬에서 읽게 해줌
   -- 여기서 해당 소스 세팅은 main.js에서 해줌

정리하자면, 실행 순서는 아래와 같다.
 > (1) main.js 에서 ./App.vue를 읽어와서 mount 시킴
   (2) App.vue 에서 HelloWorld.vue를 import 시킴
   (3)  
 - src : 소스코드
   -- main.js : 가장 최초로 실행되는 JS
 - package.json : 라이브러리 버전 및 프로젝트 설정 (like pom.xml..)
 - package-lock.json : dependency 관리
 - public : html, 정적 파일 보관

6. 데이터 바인딩
 (1) {{변수명}}
 (2) :style="변수명"
 (3) 데이터 갖다쓰는 법
   - import/export
   - import [변수명] from [경로] / export default {}
 (4)  
 
 * keywords
 img src 변수 바인딩관련
 

 - 그래서, public>index.html을 참고하면, App.vue에서 짠 코드를 HTML로 변환하여 크롬에서 읽게 해줌

7. 컴포넌트 갖다 쓰는법
(1) import / export
(2) 
8. ㄴㅇㄹ
9. ㄴㄹㄴㅇㄹ
10. ㄴㅇㄹㄴㅇ
11. ㄴㅇㄹ
12. ㄴㅇㄹㄴ
13. ㅇㄹㄴ
14. ㅇㄹㄴ
15. ㅇㄹㄴ
16. ㅇㄹㄴ
17. ㄹ
