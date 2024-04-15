## Class0408 수업 정리

### 수업내용

<img width="800" src="./img/hook1.jpg" alt="hook" >
<p>리액트 컴포넌트는 함수형 컴포넌트, 클래스형 컴포넌트로 나뉜다.</p>
<p>함수형 컴포넌트가 사용된 이유는 클래스형 컴포넌트의 대표적인 단점 때문이다.</p>
<p>코드의 구성이 어렵고 컴포넌트의 재사용성이 떨어진다. <br>컴파일 단계에서 코드 최적화를 어렵게 한다. <br>최신 기술의 적용이 효과적이지 않다.</p>
<p>이러한 클래스형 컴포넌트의 단점을 보안하여, 함수형 컴포넌트를 사용할 수 있도록 등장한 것이 React Hook이다.</p>
<p>Hook의 장점은 상태 로직 단순화, 코드 재사용성과 관심사 분리, 사이드 이펙트 감소가 있다.</p>

<img width="800" src="./img/hook2.jpg" alt="hook" >
<p>Hook은 두 가지 규칙을 준수해야한다.</p>
<p>최상위에서만 Hook을 호출해야한다.(반족문, 조건문 혹은 중첩된 함수 내에서 Hook을 호출하면 안된다.)</p>
<p>오직 React 함수 내에서 Hook을 호출해야 한다.</p>

<img width="450vw" src="./img/hook3.jpg" alt="hook" > <img width="450vw" src="./img/hook4.jpg" alt="hook" >
<p>Hook은 일반 자바스크립트 함수에서 Hook을 호출하지 말아야 한다.</p>
<p>대신, React함수 구성요소에서 Hook을 호출하고, 사용자 지정 Hook으로부터 Hook을 호출할 수 있다.</p>
<p>Hook은 조건이나 루프 내부에서 Hook을 호출하지 말아야한다.</p>
<p>Hook은 조건부 반환(return)문 뒤에 Hook을 호출하지 말아야 한다.</p>
<p>Hook은 이벤트 핸들러에서 Hook을 호출하지 않는다.</p>
<p>Hook은 클래스 컴포넌트 안에 Hook을 호출하지 말아야 한다.</p>

<img width="800" src="./img/usestate1.jpg" alt="useState" >
<p>컴포넌트에 state variable를 추가할 수 있다.</p>
<p>variable = expression 할당연산자</p>

<img width="800" src="./img/usestate2.jpg" alt="useState" >
<p>여러번 리렌더링 되는 것을 방지할 수 있다.</p>
<p>렌더링 중 set 함수 호출은 현재 렌더링 구성 요소 내에서만 허용된다.</p>

<img width="800" src="./img/usestate3.jpg" alt="useState" >
<p>usestate 하나 이상의 상태 변수를 선언하려면 구성 요소의 최상위 수준에서 호출해야 한다.</p>
<p>처음에 사용자가 제공한 초기 상태로 설정, 다음 상태 값을 가진 set함수를 호출하면 된다.</p>
<p>set 함수를 호출해도 이미 실행 중인 코드의 현재 상태는 변경되지않는다.</p>
<p>렌더링 부터 반환되는 항목에만 영향을 미친다.</p>

<hr>

### 실습내용

#### Basic useState examples - Counter (number)

<img width="450vw" src="./img/counterjs.jpg" alt="useState" ><img width="450vw" src="./img/counterapp.jpg" alt="useState" >
<p>Counter.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/counterstart.jpg" alt="useState" >
<p>실행화면</p>

<hr>

#### Basic useState examples - Text field (string)

<img width="450vw" src="./img/myinputjs.jpg" alt="useState" ><img width="450vw" src="./img/myinputapp.jpg" alt="useState" >
<p>MyInput.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/myinputstart.jpg" alt="useState" >
<p>실행화면</p>

<hr>

#### Basic useState examples - Checkbox (boolean)

<img width="450vw" src="./img/mycheckboxjs.jpg" alt="useState" ><img width="450vw" src="./img/mycheckboxapp.jpg" alt="useState" >
<p>MyCheckbox.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/mycheckboxstart.jpg" alt="useState" >
<p>실행화면</p>

<hr>

#### Basic useState examples - From (two variables)

<img width="450vw" src="./img/fromjs.jpg" alt="useState" ><img width="450vw" src="./img/fromapp.jpg" alt="useState" >
<p>From.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/fromstart.jpg" alt="useState" >
<p>실행화면</p>

<hr>

#### The difference between passing an updater and passing the next state directly example - Passing the next state directly

<img width="450vw" src="./img/directcounterjs.jpg" alt="useState" ><img width="450vw" src="./img/counterapp.jpg" alt="useState" >
<p>Counter.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/directcounterstart.jpg" alt="useState" >
<p>실행화면</p>

<hr>

#### The difference between passing an updater and passing the next state directly example - Passing the updater function

<img width="450vw" src="./img/funccounterjs.jpg" alt="useState" ><img width="450vw" src="./img/counterapp.jpg" alt="useState" >
<p>Counter.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/funccounterstart.jpg" alt="useState" >
<p>실행화면</p>

<hr>

#### Examples of objects and arrays in state - From (object)

<img width="450vw" src="./img/objectfromjs.jpg" alt="useState" ><img width="450vw" src="./img/fromapp.jpg" alt="useState" >
<p>From.js 코드</p>
<p>App.js 코드</p>
<img width="800" src="./img/objectfromstart.jpg" alt="useState" >
<p>실행화면</p>

<hr>

#### Examples of objects and arrays in state - From (nested object)

<img width="450vw" src="./img/nestedfromjs1.jpg" alt="useState" ><img width="450vw" src="./img/nestedfromjs2.jpg" alt="useState" >
<p>From.js 코드</p>
<img width="450vw" src="./img/fromapp.jpg" alt="useState" >
<p>App.js 코드</p>
<img width="800" src="./img/nestedfromstart.jpg" alt="useState" >
<p>실행화면</p>

<hr>

#### Examples of objects and arrays in state - List (array)

<img width="450vw" src="./img/addtodojs.jpg" alt="useState" ><img width="450vw" src="./img/tasklistjs.jpg" alt="useState" >
<p>AddTodo.js 코드</p>
<p>TaskList.js 코드</p>
<img width="450vw" src="./img/listapp.jpg" alt="useState" >
<p>App.js 코드</p>
<img width="800" src="./img/liststart.jpg" alt="useState" >
<p>실행화면</p>

<hr>

#### The difference between passing an initializer and passing the initial state directly example - Passing the initializer function

<img width="450vw" src="./img/passingjs.jpg" alt="useState" >
<p>App.js 코드</p>
<img width="800" src="./img/passingstart.jpg" alt="useState" >
<p>실행화면</p>

<hr>

#### The difference between passing an initializer and passing the initial state directly example - Passing the initial state directly

<img width="450vw" src="./img/passingjs2.jpg" alt="useState" >
<p>App.js 코드</p>
<img width="800" src="./img/passingstart2.jpg" alt="useState" >
<p>실행화면</p>

<hr>

#### Resetting state with a key

<img width="450vw" src="./img/keyapp.jpg" alt="useState" >
<p>App.js 코드</p>
<img width="800" src="./img/keystart.jpg" alt="useState" >
<p>실행화면</p>

<hr>

#### Storing information from previous renders

<img width="450vw" src="./img/renderjs.jpg" alt="useState" > <img width="450vw" src="./img/countlabel.jpg" alt="useState" >
<p>App.js 코드</p>
<p>CountLabel.js 코드</p>
<img width="800" src="./img/renderstart1.jpg" alt="useState" ><img width="800" src="./img/renderstart2.jpg" alt="useState" >
<p>실행화면</p>

