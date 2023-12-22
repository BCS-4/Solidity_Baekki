## 시험 (제출 : 12/25 까지 클래스매니저에게 DM으로 제출)

```javascript
  여러분은 선생님입니다. 학생들의 정보를 관리하려고 합니다.
  학생의 정보는 이름, 번호, 점수, 학점 그리고 듣는 수업들이 포함되어야 합니다.

  번호는 1번부터 시작하여 정보를 기입하는 순으로 순차적으로 증가합니다.

  학점은 점수에 따라 자동으로 계산되어 기입하게 합니다. 90점 이상 A, 80점 이상 B, 70점 이상 C, 60점 이상 D, 나머지는 F 입니다.

  필요한 기능들은 아래와 같습니다.

  * 학생 추가 기능 - 특정 학생의 정보를 추가
  * 학생 조회 기능(1) - 특정 학생의 번호를 입력하면 그 학생 전체 정보를 반환
  * 학생 조회 기능(2) - 특정 학생의 이름을 입력하면 그 학생 전체 정보를 반환
  * 학생 점수 조회 기능 - 특정 학생의 이름을 입력하면 그 학생의 점수를 반환
  * 학생 전체 숫자 조회 기능 - 현재 등록된 학생들의 숫자를 반환
  * 학생 전체 정보 조회 기능 - 현재 등록된 모든 학생들의 정보를 반환
  * 학생들의 전체 평균 점수 계산 기능 - 학생들의 전체 평균 점수를 반환
  * 선생 지도 자격 자가 평가 시스템 - 학생들의 평균 점수가 70점 이상이면 true, 아니면 false를 반환
  * 보충반 조회 기능 - F 학점을 받은 학생들의 숫자와 그 전체 정보를 반환
  -------------------------------------------------------------------------------
  * S반 조회 기능 - 가장 점수가 높은 학생 4명을 S반으로 설정하는데, 이 학생들의 전체 정보를 반환하는 기능 (S반은 4명으로 한정)

  기입할 학생들의 정보는 아래와 같습니다. (듣는 수업정보는 아무거나 기입)

  Alice, 1, 85
  Bob,2, 75
  Charlie,3,60
  Dwayne, 4, 90
  Ellen,5,65
  Fitz,6,50
  Garret,7,80
  Hubert,8,90
  Isabel,9,100
  Jane,10,70
```

## 퀴즈 복습하기

- test.sol

  > 숫자들만 들어가는 array 구현하고 그 array를 숫자를 넣는 함수  
  > 전체 array를 반환하는 함수  
  > 특정 요소를 확인할 수 있는 함수  
  > array에 들어간 숫자들의 평균을 구하는 함수를 구현하세요

- test2.sol

  > 숫자만 들어가는 array를 구현하세요.  
  > 그 array에서 2의 배수들만 출력하는 함수를 구현하세요.

- enum.sol

  > 색깔이라는 enum 형 변수를 설정하고 white, red, yellow, green 상태를 선언하세요.  
  > 기본은 white 이고 red, yellow, green으로 상태를 변경하는 함수를 각각 구현하세요.  
  > 현재 어떤 상태인지 반환하는 함수도 구현하세요.