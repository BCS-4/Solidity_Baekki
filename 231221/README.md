## 비트코인 백서 pdf 포함되어 있습니다.

## 퀴즈 복습하기

- if2.sol

  > input 값이 40 ~ 60 사이 혹은 100 ~ 150 혹은 5의 배우인 경우 A, 3의 배수이면 B, 아니면 C 인 함수를 만드세요.

- while.sol

  ```javascript
    uint STATE = 1;
    function while_1(uint _n) public returns(uint, uint) {
      uint a;
      while(_n > a) {
          STATE *= 2;
          a++;
      }
      return (STATE, a);
    }
  ```

  > while_1 함수에서 \_n = 5 일경우 STATE와 a 의 값은 어떻게 될까요?  
  > numbers 라는 array 안에 \_n 개의 짝수가 들어가는 식을 while을 이용하여 구현하세요.  
  > 특정 숫자의 자릿수를 알아내는 방법을 while을 이용하여 구현해보세요. (예시: 12345 -> 5자리, 5492 -> 4자리)

- AAA.sol

  > 점수를 입력했을 때, 90이상이면 A, 80이상이면 B, 70이상이면 C 그 외에는 F를 내는 setGrade함수를 구현하세요.  
  > 이름, 번호, 점수, 학점(string)을 가진 학생 구조체를 구현하세요.  
  > 학생들이 들어가는 array 를 만들고 그 array에 학생 정보를 입력하는 함수를 구현하세요.  
  > 학생 정보를 입력하는 함수는 3개의 input 값만 받게 하고 grade는 setGrade 함수를 이용하여 자동으로 기입되도록 구현하세요.  
  > 학생 전체 수를 반환받는 함수를 구현하세요

- review.sol

  > 숫자형 상태변수 a를 선언하세요.  
  > 상태변수 a와 input 값 \_a을 더하고 반환하는 함수를 만드세요.  
  > 상태변수 a를 변경하는 함수를 만드세요.  
  > 지역변수 \_a 와 \_b를 더하고 반환하는 함수를 만드세요.  
  > 상태변수 a의 \_b 제곱을 반환하는 함수를 만드세요.  
  > 두 개의 숫자를 곱하고 반환하는 함수를 만드세요.