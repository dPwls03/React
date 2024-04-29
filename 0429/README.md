## Class0429 수업 정리

### 클로저 발표
<a href="https://dpwls03.github.io/React/0429/클로저.pdf">[발표자료]</a>

[발표내용]

클로저 함수에 대한 내용입니다.

클로저는 외부 함수의 컨텍스트에 접근할 수 있는 내부 함수를 뜻하고, 

외부 함수의 실행이 종료된 후에도, 클로저 함수는 외부 함수가 선언된 어휘적 횐경에 접근할 수 있습니다.

<hr>

### 수업내용

### 실습내용

#### init 함수를 사용하지 않는 counter 예시

<img width="450vw" src="./img/initxcounterjs.jpg" alt="hook" ><img width="450vw" src="./img/initxappjs.jpg" alt="hook" >
<p>Counter.js 코드</p>
<p>App.js 코드</p>

<img width="800" src="./img/initxstart.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### init 함수를 사용하여 counter 예시

<img width="450vw" src="./img/initocounterjs.jpg" alt="hook" ><img width="450vw" src="./img/initxappjs.jpg" alt="hook" >
<p>Counter.js 코드</p>
<p>App.js 코드</p>

<img width="800" src="./img/initostart.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### useState 사용

<img width="450vw" src="./img/usestatecounterjs.jpg" alt="hook" ><img width="450vw" src="./img/initxappjs.jpg" alt="hook" >
<p>Counter.js 코드</p>
<p>App.js 코드</p>

<img width="800" src="./img/usestatestart.jpg" alt="hook" >
<p>실행화면</p>

<hr>

####  state와 props만 사용해서 만든 웹사이트

<img width="450vw" src="./img/propsapp.jpg" alt="hook" ><img width="450vw" src="./img/page.jpg" alt="hook" >
<p>App.js 코드</p>
<p>Page.js 코드</p>
<img width="420vw" src="./img/header.jpg" alt="hook" ><img width="450vw" src="./img/contentjs.jpg" alt="hook" >
<p>Header.js 코드</p>
<p>Content.js 코드</p>
<img width="450vw" src="./img/footer.jpg" alt="hook" >
<p>Footer.js 코드</p>

<img width="450vw" src="./img/propstart1.jpg" alt="hook" ><img width="450vw" src="./img/propsstart2.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### context를 사용해서 만든 웹사이트

<img width="450vw" src="./img/conapp.jpg" alt="hook" ><img width="450vw" src="./img/conpage.jpg" alt="hook" >
<p>App.js 코드</p>
<p>Page.js 코드</p>
<img width="420vw" src="./img/conheader.jpg" alt="hook" ><img width="450vw" src="./img/concontent.jpg" alt="hook" >
<p>Header.js 코드</p>
<p>Content.js 코드</p>
<img width="450vw" src="./img/confooter.jpg" alt="hook" ><img width="450vw" src="./img/theme.jpg" alt="hook" >
<p>Footer.js 코드</p>
<p>ThemeContext.js 코드</p>

<img width="450vw" src="./img/contextstart1.jpg" alt="hook" ><img width="450vw" src="./img/contextstart2.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### context의 값 변경하기

<img width="800" src="./img/conchangeapp.jpg" alt="hook" >
<p>App.js 코드</p>

<img width="800" src="./img/conchangestart.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### useRef 사용 예시 - 변수 관리

<img width="800" src="./img/userefapp.jpg" alt="hook" >
<p>App.js 코드</p>

<img width="450vw" src="./img/userefvarstart1.jpg" alt="hook" ><img width="450vw" src="./img/userefvarstart2.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### useRef 사용 예시 - DOM 요소 선택 1

<img width="450vw" src="./img/domfocusjs.jpg" alt="hook" ><img width="450vw" src="./img/domfocusapp.jpg" alt="hook" >
<p>DOMFocus.js 코드</p>
<p>App.js 코드</p>

<img width="800" src="./img/domfocusstart.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### useRef 사용 예시 - DOM 요소 선택 2

<img width="450vw" src="./img/inputjs.jpg" alt="hook" ><img width="450vw" src="./img/inputapp.jpg" alt="hook" >
<p>InputSample.js 코드</p>
<p>App.js 코드</p>

<img width="800" src="./img/inputstart.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### 부모 컴포넌트에 커스텀 함수 노출하기 1

<img width="450vw" src="./img/childcomjs.jpg" alt="hook" ><img width="450vw" src="./img/parentcomjs.jpg" alt="hook" >
<p>ChildComponent.js 코드</p>
<p>ParentComponent.js 코드</p>
<img width="800" src="./img/usehandleapp.jpg" alt="hook" >
<p>App.js 코드</p>

<img width="800" src="./img/usehandlestart.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### 부모 컴포넌트에 커스텀 함수 노출하기 2

<img width="450vw" src="./img/myinputjs.jpg" alt="hook" ><img width="450vw" src="./img/formjs.jpg" alt="hook" >
<p>MyInput.js 코드</p>
<p>Form.js 코드</p>
<img width="800" src="./img/usehandleapp2.jpg" alt="hook" >
<p>App.js 코드</p>

<img width="800" src="./img/usehandlestart2.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### useEffect - 기본 사용법

<img width="800" src="./img/effectbaseapp.jpg" alt="hook" >
<p>App.js 코드</p>

<img width="800" src="./img/effectstart1.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### useEffect - 세 가지 사용법 1. 무한반복

<img width="800" src="./img/useeffect1app.jpg" alt="hook" >
<p>App.js 코드</p>

<img width="800" src="./img/useeffect1start.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### useEffect - 세 가지 사용법 2. 처음에만 실행

<img width="800" src="./img/useeffect2app.jpg" alt="hook" >
<p>App.js 코드</p>

<img width="800" src="./img/useeffect2start.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### useEffect - 세 가지 사용법 3. 의존성 배열 사용

<img width="800" src="./img/useeffect3app.jpg" alt="hook" >
<p>App.js 코드</p>

<img width="800" src="./img/useeffect3start.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### useEffect - cleanup

<img width="800" src="./img/cleanupapp.jpg" alt="hook" >
<p>App.js 코드</p>

<img width="800" src="./img/cleanupstart.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### useLayoutEffect - useEffect 사용

<img width="800" src="./img/layout1app.jpg" alt="hook" >
<p>App.js 코드</p>

<img width="800" src="./img/layout1start.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### useLayoutEffect - useLayoutEffect 사용

<img width="800" src="./img/layout2app.jpg" alt="hook" >
<p>App.js 코드</p>

<img width="800" src="./img/layout2start.jpg" alt="hook" >
<p>실행화면</p>

<hr>

#### useLayoutEffect

<img width="450vw" src="./img/practicejs.jpg" alt="hook" ><img width="450vw" src="./img/uselayoutapp.jpg" alt="hook" >
<p>Practice.js 코드</p>
<p>App.js 코드</p>

<img width="800" src="./img/uselayoutstart.jpg" alt="hook" >
<p>실행화면</p>

