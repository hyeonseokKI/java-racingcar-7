# java-racingcar-precourse
프리코스 2주차: 자동차 경주

### 과제 진행 요구 사항
- [X] 미션은 자동차 경주 저장소를 포크하고 클론
- [X] 기능을 구현하기 전 README.md에 구현할 기능 목록을 정리
- [X] Git의 커밋 단위는 앞 단계에서 README.md에 정리한 기능 목록 단위로 추가
    - [X]  AngularJS Git Commit Message Conventions을 참고해 커밋 메시지를 작성한다.
- [X] 자세한 과제 진행 방법은 프리코스 진행 가이드 문서를 참고한다

### 기능 요구 사항
- [X] 주어진 횟수 동안 n대의 자동차는 전진 또는 정지
- [X] 각 자동차에 이름을 부여,  전진하는 자동차를 출력할 때 자동차 이름을 같이 출력
- [X] 자동차 이름은 쉼표(,)를 기준으로 구분하며 이름은 5자 이하만 가능
- [X] 사용자는 몇 번의 이동을 할 것인지를 입력
- [X] 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우
- [X] 자동차 경주 게임을 완료한 후 누가 우승했는지 출력, 우승자는 한 명 이상
- [X] 우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분
- [X] 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료

### 프로그래밍 요구 사항 1 
- [X] JDK 21 버전에서 실행 가능해야 한다.
- [X] 프로그램 실행의 시작점은 Application의 main()이다.
- [X] build.gradle 파일은 변경할 수 없으며, 제공된 라이브러리 이외의 외부 라이브러리는 사용하지 않는다.
- [X] 프로그램 종료 시 System.exit()를 호출하지 않는다.
- [X] 프로그래밍 요구 사항에서 달리 명시하지 않는 한 파일, 패키지 등의 이름을 바꾸거나 이동하지 않는다.
- [X] 자바 코드 컨벤션을 지키면서 프로그래밍한다.
    - 카멜 표기법(CamelCase) 클래스 경우 대문자 시작, 변수,메서드 경우 소문자 시작, 각 단어의 첫 글자 대문자, 상수는 언더스코어 이용
- [X] 기본적으로 Java Style Guide를 원칙으로 한다.
    - 블럭 들여쓰기: +4 스페이스
    - 들여쓰기 지속은 최소 +8 스페이스
    - Java 코드의 열 제한은 120자
    - 가독성 향상이 된다면 수직 빈줄 허용

### 프로그래밍 요구 사항 2
- [X] indent(인덴트, 들여쓰기) depth를 3이 넘지 않도록 구현
- [X] 3항 연산자 사용 금지
- [X] 함수(또는 메서드)가 한 가지 일만 하도록 최대한 작게 작성 
- [X] JUnit 5와 AssertJ를 이용하여 정리한 기능 목록이 정상적으로 작동하는지 테스트 코드로 확인

### 자동차 경주 기능 목록

### 기능 1: 입력 받기
- 기능 1 세부 사항
    - [X] 문자열과 횟수 입력
    - [X] 쉼표를 기준으로 분리
---
### 기능 2: 결과 출력
- 기능 2 세부사항
  - [X] 횟수별 자동차 이름, 위치
  - [X] 최종 우승한 자동차들의 이름
---
### 기능 3: 유효성 검사 
- 기능 3 세부사항
    - [X] 자동차 이름 5자 초과 예외 처리
    - [X] 빈 문자열 판단
    - [X] 숫자 판단
    - [X] 양수 판단
---
### 기능 4: Car 모델 생성 
- 기능 4 세부사항
    - [X] 이름, 위치 가져옴
    - [X] 조건부 전진 기능
    - [X] 난수 발생 기능
---
### 테스트 코드 작성
- [ ] 이름 입력 예외 테스트
- [ ] 횟수 입력 예외 테스트
- [ ] Car Test
  - [ ] 전진 테스트
- [ ] 최대 위치, 우승자 확인 테스트

