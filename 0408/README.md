## Class0408 수업 정리

### 수업내용

<img width="800" src="./img/imgprops.jpg" alt="props" >
<p>img/는 public에 있는 img폴더를 가리킨다.</p>

<img width="800" src="./img/imgprops2.jpg" alt="props" >
<p>app.js를 수정해서 해도 되지만 index.html를 수정해도 실행이 가능하다.</p>

<img width="800" src="./img/state1.jpg" alt="state" >
<p>state는 어떠한 값을 가지는 것이다.</p>
<p>값이 바뀌면 재 렌더링 되어 화면이 바뀐다.</p>
<p>state는 간단하게 말해서 변수이다.</p>
<p>props는 부모, 상위에서 전달 받기때문에 값을 바꿀수 없지만,</p>
<p>state는 값을 바꿀수있다. 그럼 재 렌더링이 된다.</p>
<p>컴포넌트 자신 만의 값을 가지고 있다.</p>

<img width="800" src="./img/state2.jpg" alt="state" >
<p>컴포넌트의 데이터라는 의미가 가깝다.</p>
<p>컴포넌트가 가질 수 있는 값이다.</p>
<p>시간이 지남에 따라 변하는 데이터이다.</p>
<p>컴포넌트의 메모리</p>

<img width="800" src="./img/state3.jpg" alt="state" >
<p>상태에 따라 변하는 동적 데이터</p>
<p>명시적으로 state를 기술해야한다.</p>
<p>내부적으로 상태를 관리해야 하는 일이 필요하다.</p>

<hr>

### 실습내용

#### imgtext 컴포넌트

<img width="450vw" src="./img/fphotojs.jpg" alt="fphoto" ><img width="450vw" src="./img/fphotoapp.jpg" alt="fphoto" >
<p>RList.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/fphotostart.jpg" alt="fphoto" >
<p>실행화면</p>

#### 리스트 컴포넌트

<img width="450vw" src="./img/listjs.jpg" alt="list" ><img width="450vw" src="./img/listapp.jpg" alt="list" >
<p>RList.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/liststart.jpg" alt="list" >
<p>실행화면</p>

#### 화살표 함수

<img width="800" src="./img/arrowindex.jpg" alt="arrow" >
<p>arrow.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/arrowstart.jpg" alt="arrow" >
<p>실행화면</p>

<hr>

#### 댓글 컴포넌트



#### 댓글 컴포넌트 스타일 입히기



#### 댓글 컴포넌트 props 추가하기



#### 댓글 컴포넌트 데이터 객체로 분리하기



<hr>

#### state 일반 변수

<img width="450vw" src="./img/counterjs.jpg" alt="state" ><img width="450vw" src="./img/counterapp.jpg" alt="state" >
<p>Counter.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/counterstart.jpg" alt="state" >
<p>실행화면</p>

#### state 사용

<img width="450vw" src="./img/counterjs2.jpg" alt="state" ><img width="450vw" src="./img/counterapp.jpg" alt="state" >
<p>Counter.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/counterstart2.jpg" alt="state" >
<p>실행화면</p>

#### state 비동기적 작동

<img width="450vw" src="./img/counterjs3.jpg" alt="state" ><img width="450vw" src="./img/counterapp.jpg" alt="state" >
<p>Counter.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/counterstart3.jpg" alt="state" >
<p>실행화면</p>

#### state 비동기적 작동 3증가

<img width="450vw" src="./img/setstatecounterjs.jpg" alt="state" ><img width="450vw" src="./img/setstatecounterapp.jpg" alt="state" >
<p>Counter.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/setstatecounterstart.jpg" alt="state" >
<p>실행화면</p>

#### state 비동기적 작동 콜백 함수 사용

<img width="450vw" src="./img/callback.jpg" alt="state" ><img width="450vw" src="./img/setstatecounterapp.jpg" alt="state" >
<p>Counter.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/callbackstart.jpg" alt="state" >
<p>실행화면</p>

#### state 설정 및 사용 1

<img width="450vw" src="./img/statesettingjs.jpg" alt="state" ><img width="450vw" src="./img/statesettingapp.jpg" alt="state" >
<p>Member.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/statesettingstart.jpg" alt="state" >
<p>실행화면</p>

#### state 설정 및 사용 2

<img width="450vw" src="./img/counterjs4.jpg" alt="state" ><img width="450vw" src="./img/counterindex.jpg" alt="state" >
<p>Counter.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/counterstart4.jpg" alt="state" >
<p>실행화면</p>

#### state 설정 및 사용 2

<img width="450vw" src="./img/counterjs5.jpg" alt="state" ><img width="450vw" src="./img/counterindex.jpg" alt="state" >
<p>Counter.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/counterstart5.jpg" alt="state" >
<p>실행화면</p>

<hr>

#### 리액트 이벤트 문법

<img width="450vw" src="./img/eventjs.jpg" alt="event" ><img width="450vw" src="./img/eventapp.jpg" alt="event" >
<p>Main.js 코드</p>
<p>App.js 코드</p>
<img width="420vw" src="./img/eventstart1.jpg" alt="event" ><img width="420vw" src="./img/eventstart2.jpg" alt="event" >
<p>실행화면</p>

#### 너비와 높이 증가시키기

<img width="450vw" src="./img/Areajs.jpg" alt="event" ><img width="450vw" src="./img/areaapp.jpg" alt="event" >
<p>Area.js 코드</p>
<p>App.js 코드</p>
<img width="450vw" src="./img/areastart.jpg" alt="event" >
<p>실행화면</p>

#### 경고창 띄우기

<img width="800" src="./img/warninghtml.jpg" alt="event" >
<p>warning.html 코드</p>
<img width="800" src="./img/warningstart.jpg" alt="event" >
<p>실행화면</p>

#### 클릭했을 때 메소드 호출

<img width="800" src="./img/clickhtml.jpg" alt="event" >
<p>click.html 코드</p>
<img width="800" src="./img/clickstart.jpg" alt="event" >
<p>실행화면</p>

#### 간단한 체크박스 구현

<img width="800" src="./img/checkhtml.jpg" alt="event" >
<p>check.html 코드</p>
<img width="800" src="./img/checkstart.jpg" alt="event" >
<p>실행화면</p>

#### 스톱워치 만들기

<img width="450vw" src="./img/stopcss.jpg" alt="event" ><img width="450vw" src="./img/stopjs.jpg" alt="event" >
<p>Stopwatch.css 코드</p>
<p>Stopwatch.js 코드</p>
<img width="450vw" src="./img/stopapp.jpg" alt="event" >
<p>App.js 코드</p>
<img width="800" src="./img/stopstart.jpg" alt="event" >
<p>실행화면</p>

#### 간단한 입력 양식

<img width="450vw" src="./img/simplejs.jpg" alt="event" ><img width="450vw" src="./img/simpleapp.jpg" alt="event" >
<p>SimpleForm.js 코드</p>
<p>App.js 코드</p>
<img width="450vw" src="./img/simplestart.jpg" alt="event" >
<p>실행화면</p>

#### 숫자만 입력받는 텍스트 박스

<img width="450vw" src="./img/numjs.jpg" alt="event" ><img width="450vw" src="./img/numapp.jpg" alt="event" >
<p>NumberForm.js 코드</p>
<p>App.js 코드</p>
<img width="450vw" src="./img/numstart.jpg" alt="event" >
<p>실행화면</p>

#### 여러개의 입력 항목을 가진 입력 양식 만들기

<img width="450vw" src="./img/multijs.jpg" alt="event" ><img width="450vw" src="./img/multiapp.jpg" alt="event" >
<p>MultiForm.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/multistart.jpg" alt="event" >
<p>실행화면</p>
