# :sparkles: [2주차] 자동차 경주 게임 기능 목록 :sparkles:

## 1. 사용자 입력 및 예외 처리

* 자동차 이름 입력 받기
    * 각 자동차 이름은 쉼표로 구분
    * 유효한 자동차 이름은 5글자 이하
* 게임 시도 횟수 입력 받기

* 유효하지 않은 사용자 입력 시, IllegalArgumentException 예외 처리
    * 자동차 이름이 6글자 이상이거나, 게임 시도 횟수가 숫자가 아닌 경우

## 2. 자동차 전진 조건 설정

* 자동차 전진 조건을 위한 랜덤 수 생성
    * 0 ~ 9 사이 랜덤 숫자 생성
* 생성된 랜덤 숫자가 4 이상인 경우 해당 자동차 이동 횟수를 1회 증가

## 3. 실행 결과 및 우승자 결과 목록 생성 및 출력

* 각 입력 받은 게임 경주 횟수마다 실행 결과 출력 
* 우승자 목록 생성
    * 우승자가 2명 이상인 경우 쉼표로 구분
* 우승자 안내 메시지 출력