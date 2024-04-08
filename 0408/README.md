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

<img width="800" src="./img/imgprops2.jpg" alt="props" >

<img width="800" src="./img/imgprops2.jpg" alt="props" >

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

#### state 설정 및 사용 