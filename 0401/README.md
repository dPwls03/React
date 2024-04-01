## Class0401 수업 정리

### 수업내용

<img width="800" src="./img/component.jpg" alt="component" >
<p>컴포넌트는 함수, 객체와 비슷하다.</p>
<p>리액트 자체가 컴포넌트로 구성 되어있다.</p>
<p>자바스크립트의 함수처럼 작동해서 리액트 엘리먼트를 리턴한다.</p>
<p>웹 페이지를 만드는 조각들을 모아서 웹 페이지를 만들 수 있다.</p>

<img width="800" src="./img/component2.jpg" alt="component" >
<p>리액트 컴포넌트는 입력이 props이고 출력이 React Element이다.</p>
<p>자바스크립트 객체 형태로 존재하며 화면에 보이는 것을 기술한다.</p>
<p>props는 component의 입력으로 들어간다.</p>
<p>입력만 바꾸면 출력되는 것이 다르게 나온다.</p>
<p>붕어빵 재료에 따라서 다양한 맛의 붕어빵이 나오는 것과 같다.</p>
<a href="https://www.airbnb.co.kr/">컴포넌트 구성 예시 사이트</a>

<img width="800" src="./img/component3.jpg" alt="component" >
<p>리액트 컴포넌트는 Class Component와 Function Component로 나뉜다.</p>
<p>Class Component는 class를 사용해서 만들어진 형태의 컴포넌트이고 render() 메소드를 호출한다.</p>
<p>리액트 컴포넌트는 pure 함수 같은 역할을 해야한다. 하나의 객체를 받아 React element를 리턴하면 React Component라고 할 수 있는데 이런 것을 Function Component라고 한다.</p>

<img width="800" src="./img/component4.jpg" alt="component" >
<p>컴포넌트는 항상 대문자로 시작해야한다. (사용자가 정의한 컴포넌트)</p>
<p>소문자로 시작하는 component는 DOM 태그로 인식한다. (HTML 태그)</p>
<p>이 두 개는 대소문자로 구분한다.</p>

<img width="800" src="./img/props.jpg" alt="props" >
<p>App.js가 Header.js, Main.js, Footer.js를 품었다. 그래서 Header.js, Main.js, Footer.js 파일의 부모는 App.js이다.</p>
<p>리액트 컴포넌트는 props를 이용해 서로 통신한다.</p>

<hr>

### 실습내용

#### Function Component

<img width="450vw" src="./img/funchead.jpg" alt="component practice" > <img width="450vw" src="./img/funcmain.jpg" alt="component practice" >
<p>Function Component Header.js 코드</p> <p>Function Component Main.js 코드</p>

<img width="450vw" src="./img/funcfoot.jpg" alt="component practice" > <img width="450vw" src="./img/funcapp.jpg" alt="component practice" >
<p>Function Component Footer.js 코드</p> <p>Function Component App.js 코드</p>

<p>rsf (React Stateless Function Component의 약자)</p>

<img width="800" src="./img/funcstart.jpg" alt="component practice" >
<p>실행화면</p>

<hr>

#### Class Component

<img width="450vw" src="./img/classhead.jpg" alt="component practice" > <img width="450vw" src="./img/classmain.jpg" alt="component practice" >
<p>Class Component Header.js 코드</p> <p>Class Component Main.js 코드</p>

<img width="450vw" src="./img/classfoot.jpg" alt="component practice" > <img width="450vw" src="./img/classapp.jpg" alt="component practice" >
<p>Class Component Footer.js 코드</p> <p>Class Component App.js 코드</p>

<p>rcc (React Class Component의 약자)</p>

<img width="800" src="./img/classstart.jpg" alt="component practice" >
<p>실행화면</p>

<hr>

#### 프로퍼티 예제

<img width="450vw" src="./img/propsexapp.jpg" alt="props" > <img width="450vw" src="./img/mycomp.jpg" alt="props" >
<p>프로퍼티 예제 App.js 코드</p> <p>프로퍼티 예제 MyComponent.js 코드</p>

<img width="800" src="./img/propsexstart.jpg" alt="props" >
<p>실행화면</p>

<hr>

#### 1개의 프로퍼티 넘기기

<img width="450vw" src="./img/onepropsapp.jpg" alt="props" > <img width="450vw" src="./img/onepropsmain.jpg" alt="props" >
<p>1개의 프로퍼티 넘기기 App.js 코드</p> <p>1개의 프로퍼티 넘기기 Main.js 코드</p>

<img width="800" src="./img/onepropsstart.jpg" alt="props" >
<p>실행화면</p>

<hr>

#### 2개의 프로퍼티 넘기기

<img width="450vw" src="./img/twopropsapp.jpg" alt="props" > <img width="450vw" src="./img/twopropsmain.jpg" alt="props" >
<p>2개의 프로퍼티 넘기기 App.js 코드</p> <p>2개의 프로퍼티 넘기기 Main.js 코드</p>

<img width="800" src="./img/twopropsstart.jpg" alt="props" >
<p>실행화면</p>

<hr>

#### 숫자 프로퍼티 넘기기

<img width="450vw" src="./img/numpropsapp.jpg" alt="props" > <img width="450vw" src="./img/numpropsmain.jpg" alt="props" >
<p>숫자 프로퍼티 넘기기 App.js 코드</p> <p>숫자 프로퍼티 넘기기 Main.js 코드</p>

<img width="800" src="./img/numpropsstart.jpg" alt="props" >
<p>실행화면</p>

<hr>

#### 프로퍼티의 기본값 설정

<img width="450vw" src="./img/propsbaseapp.jpg" alt="props" > <img width="450vw" src="./img/propsbasemain.jpg" alt="props" >
<p>프로퍼티의 기본값 설정 App.js 코드</p> <p>프로퍼티의 기본값 설정 Main.js 코드</p>

<img width="800" src="./img/propsbasestart.jpg" alt="props" >
<p>실행화면</p>

<hr>

#### 프로퍼티의 필수값 설정

<img width="450vw" src="./img/propsneceapp.jpg" alt="props" > <img width="450vw" src="./img/propsnecemain.jpg" alt="props" >
<p>프로퍼티의 필수값 설정 App.js 코드</p> <p>프로퍼티의 필수값 설정 Main.js 코드</p>

<img width="800" src="./img/propsnecestart.jpg" alt="props" >
<p>실행화면</p>

<hr>

#### 불리언 프로퍼티 사용하기

<img width="450vw" src="./img/boolpropsapp.jpg" alt="props" > <img width="450vw" src="./img/boolpropsmain.jpg" alt="props" >
<p>불리언 프로퍼티 사용하기 App.js 코드</p> <p>불리언 프로퍼티 사용하기 Main.js 코드</p>

<img width="800" src="./img/boolpropsstart.jpg" alt="props" >
<p>실행화면</p>

<hr>

#### props.children 활용하기

<img width="450vw" src="./img/propschildappx.jpg" alt="props" > <img width="450vw" src="./img/wrapperx.jpg" alt="props" >
<p>props.children 활용하기(Main 안 보임) App.js 코드</p> <p>props.children 활용하기(Main 안 보임) Wrapper.js 코드</p>

<img width="800" src="./img/propschildstartx.jpg" alt="props" >
<p>실행화면</p>

<img width="450vw" src="./img/propschildappo.jpg" alt="props" > <img width="450vw" src="./img/wrappero.jpg" alt="props" >
<p>props.children 활용하기(Main 보임) App.js 코드</p> <p>props.children 활용하기(Main 보임) Wrapper.js 코드</p>

<img width="800" src="./img/propschildstarto.jpg" alt="props" >
<p>실행화면</p>

<hr>

#### props.children 활용하기 (여러 개의 자식 사용)

<img width="450vw" src="./img/propschildsapp.jpg" alt="props" > <img width="450vw" src="./img/propschildswrap.jpg" alt="props">
<p>props.children 활용하기 (여러 개의 자식 사용)App.js 코드</p> <p>props.children 활용하기 (여러 개의 자식 사용) Wrapper.js 코드</p>

<img width="800" src="./img/propschildsstart.jpg" alt="props" >
<p>실행화면</p>