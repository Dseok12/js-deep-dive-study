# 09장 타입 변환과 단축 평가

### 사전 복습
<details>
  <summary>자바스크립트 타입 종류</summary>

  <div>

    📖 원시적 타입
      - 숫자(Number) 타입
      - 문자(String) 타입
      - 불리언(Boolean) 타입
      - undefined 타입
      - null 타입
      - 심벌(Symbol) 타입

    📖 객체 타입
      - 객체, 배열, 함수 등

  </div>
</details>

---
### 타입 변환이란?
<details>
  <summary>명시적 타입 변환</summary>
  <div>

  ## 📖 정의

  - <u>개발자가 의도적으로</u> 값의 타입을 변환하는 것을 **명시적 타입 변환** 또는 **타입 캐스팅** 이라 한다.
  - 타입 변환 방법은 여러 형태가 있다. 타입 변환을 하는 방법은 개발자의 스타일에 따라 다르거나 각 기업에 형식에 따르면 된다.

  ### 문자열 타입으로 변환

  ```javascript
  // 1. Stirng 생성자 함수를 new연산자 없이 호출하는 방법
  String(1);
  String(true);

  // 2. Object.prototpye.toString 메서드를 사용하는 방법
  (1).toString();
  (true).toString();

  // 3. 문자열 연결 연산자를 이용하는 방법
  1 + '';
  true + '';
  
  ```

  ### 숫자열 타입으로 변환

  ```javascript


  ```

  ### 불리언 타입으로 변환

  ```javascript


  ```
  
  </div>
</details>
<details>
  <summary>암시적 타입 변환</summary>
  <div>
  
  ## 📖 정의

  - <u>개발자의 의도와는 상관없이</u> 표현식을 평가하는 도중에 자바스크립트 엔진에 의해 암묵적으로 타입이 자동 변환되기도 한다. 이를 **암묵적 타입 변환** 또는 **타입 강제 변환**이라 한다.

  ### 문자열 타입으로 변환

  ```javascript
  // 문자열로 타입 변환 하는 방법들이다.
  // 가독성이 좋은 것으로 개인이 알아서 선택하여 사용.

  let str = 1 + '';
  console.log(typeof str) //string


  let str2 = 1;
  console.log(typeof String(str2))//string

  ```

  ### 숫자 타입으로 변환

  ```javascript
  // 숫자열로 타입 변환 하는 방법들이다.
  // 가독성이 좋은 것으로 개인이 알아서 선택하여 사용.

  let str = +'1';
  console.log(typeof str) // number


  let str2 = '1';
  console.log(typeof Number(str2))// number

  ```

  ### 불리언 타입으로 변환

  - 기본적으로 자바스크립트에서 **false 값을 <U>고정해서</U> 나타내주는 값**이 있다.
    
    - false
    - undefinded
    - null
    - 0, -0
    - NaN
    - ''(빈 문자열)

  ```javascript
  // 불리언으로 타입 변환 하는 방법들이다.
  // 가독성이 좋은 것으로 개인이 알아서 선택하여 사용.

  ```
  
  </div>
</details>
<details>
  <summary>기타 설명</summary>
  <div>
  
  - 명시적 타입 변환이나 암묵적 타입 변환이 **기존 원시 값을 직접 변경하는 것은 아니다.** 원시 값은 변경 불가능한 값(immutable value)이므로 변경할 수 없다. 타입 변환이란 <u>기존 원시 값을 사용해 다른 타입의 새로운 원시값을 생성하는 것이다.</u>

  ## 표준 빌트인 생성자 함수와 빌트인 메서드

  - 표준 빌트인 생성자 함수와 표준 빌트인 메서드는 자바스크립트에서 기본 제공하는 함수다.
  표준 빌트인 생성자 함수는 객체를 생성하기 위한 함수 이며 new연산자와 함께 호출한다.
  표준 빌트인 메서드는 자바스크립트에서 기본 제공하는 빌트인 객체의 메서드다.
  
  </div>
</details>

<details>
  <summary></summary>
  <div>
  

  
  </div>
</details>


---

