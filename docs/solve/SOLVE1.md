### 🚀 기능 목록

####  problem1 - solution()
- Person[] personList : name, leftPageNumber, rightPageNumber 를 생성자 인자로 갖는 Person 객체을 요소로 갖는 배열
- personList를 도는 for문
  - [예외처리] 페이지 번호 입력
    - isOutRange(): 책의 범위 (0<=x<=400)를 벗어난 경우
    - isOddNumber(): 왼쪽페이지가 홀수가 아닌 경우
    - isEvenNumber(): 오른쪽페이지가 짝수가 아닌 경우
    - 왼쪽 페이지와 오른쪽 페이지 차이가 1이 아닌 경우
  - [요구] 가장 큰 수 구하기
    - getDigitList(): 페이지 번호 자릿수 구하기
    - getPlusScore(): 페이지 번호 자릿수 모두 더한 값
    - getMultiplyScore(): 페이지 번호 자릿수 모두 곱한 값
    - (1) int leftScore: 왼쪽 페이지 번호 자릿수 모두 더한 값, 모두 곱한 값 중 가장 큰 수 구하기
    - (2) int rightScore: 오른쪽 페이지 번호 자릿수 모두 더한 값, 모두 곱한 값 중 가장 큰 수 구하기
    - (3) person.setMaxScore(): (1)과 (2) 중 가장 큰 수를 본인 점수로 한다.
- [요구] 게임 승자 구하기
  - 점수를 비교해 가장 높은 사람이 게임의 승자가 된다.
  - 승자와 같은 점수를 가진 사람이 있다면 무승부
- 결과 출력
    - pobi 승: 1
    - crong 승: 2
    - draw: 0
    - exception: -1