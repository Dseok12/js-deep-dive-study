# 08장 제어문

<details>
  <summary>블록문</summary>

  <div markdown = "1">

  - 0개 이상의 문을 <U>중괄호 {}</U>로 묶은 것으로, 코드 블록 또는 **블록**이라고 부르기도 한다.

  - 자체 종결성을 가지므로 세미콜론( <U>;</U> )을 붙이지 않는다.

  ```javascript
  // 블록문
  {
    const foo = 10;
  }

  // 제어문
  var x = 1;
  if( x < 10 ){
    x++;
  }

  // 함수 선언문
  function sum (a, b) {
    return a + b;
  }

  <!-- 주의 -->
  // 이것은 객체임. 블록문과의 차이점이 있음
  const 객체 = {
    name = '객체',
    age = 30
  }
  ```

  </div>

  
</details>

---

<details>
  <summary>조건문</summary>
  <div markdown = "2">

  ---
  ## if...else문

  - 조건식의 *참과 거짓*을 통해 실행을 함
  
  - 사용법

  ```javascript
    if(/* 조건식 */){
      // 조건식이 참!!이면 이 블록이 실행
    } else {
      // 조건식이 거짓!!이면 이 블록이 실행
    }

    if(/* !조건식 */){
      // 조건식이 거짓!!이면 이 블록이 실행
    } else {
      // 조건식이 참!!이면 이 블록이 실행
    }
  ```
  ---

  ## switch문

  - *표현식을 조건*으로 case문과 default가 실행이 됨.
  
  - 사용법

  ```javascript
    switch (/* 표현식 */) {
      case 표현식1:
        switch 문의 표현식과 표현식1이 일치하면 실행될 문;
        break;
      
      case 표현식2:
        switch 문의 표현식과 표현식2가 일치하면 실행될 문;
        break;

      // ...

      default:
        switch 문의 표현식과 일치하는 case문이 없을 때 실행;
    }
  ```
  
  </div>
</details>

---

<details>
  <summary>반복문</summary>
  <div>

  ## for문



  ## while문



  ## do...while문




  
  </div>
</details>

---

<details>
  <summary>break문</summary>
  <div>

  ## break와 return의 차이는?

  - break문

    - 루프 탈출용

    - **for문, switch문, while문 등** 여러번 반복되는 루프를 빠져나게 하는 용도.

  ```javascript
  
  ```

  </div>
</details>

---

<details>
  <summary>continue문</summary>
  <div>
  
  </div>
</details>















