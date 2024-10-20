# java-calculator-precourse

# 기능 목록

### 사용자 입력 받기

- [x] camp.nextstep.edu.missionutils.Console의 readLine()을 활용한다.
- [x] 출력: `덧셈할 문자열을 입력해 주세요.`
- [x] 사용자가 문자열을 입력한다

### 문자열 구분하기

- [x] 구분자를 기준으로 입력 문자열을 분리한다.
    - [x] 문자열을 구분할 때, 구분자는 콤마(,)와 콜론(:)을 사용한다.
    - [x] 커스텀 구분자를 사용할 수 있다.
        - [x] 커스텀 구분자는 문자열 앞부분의 "//" 와 "\n" 사이에 위치한다.
- [x] 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시킨다.
    - [x] 숫자가 아닌 값을 입력할 경우
    - [x] 양수가 아닌 값를 입력할 경우
    - [x] 구분자가 아닌 값을 구분자로 사용할 경우
    - [x] 구분자와 양수로 구성된 문자열이 아닐 경우

### 문자열 계산하기

- [x] 추출한 숫자를 모두 더해서 반환한다.

### 출력하기

- [x] 결과 값을 출력한다.
    - 형식: `결과 : {결과값}`

# 개인 체크리스트

- 오버엔지니어링 안하기
- 객체의 책임을 명확히 하기
    - View: 사용자 인터페이스와의 상호작용, 기본적인 검증
    - Controller: View 와 Model 사이의 중개자, 비즈니스 로직을 호출하고 결과를 View에 전달
    - Model: 비즈니스 로직 작성, 컨트롤러와 뷰에 의존하면 안됨
- [x] 커스텀 예외 작성해서 예외 발생한 이유 출력하기
- [x] 비즈니스 로직 단위 테스트 작성하기
- [x] 구현
- [x] 리팩토링