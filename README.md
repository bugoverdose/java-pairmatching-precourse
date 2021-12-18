# 페어매칭관리 애플리케이션 미션

## 구현할 기능 목록

## 메인 화면

- [x] 메인화면에서 실행할 기능을 선택할 수 있다.
  - [x] 1,2,3,Q 이외의 값을 입력하면 예외로 간주한다.
  - [x] 예외 발생시, 에러 메시지 출력 후 해당 부분의 입력을 다시 받는다.
- [x] Q를 입력하면 프로그램을 종료한다.
- [x] 메인 화면에서 3을 입력하면 페어 매칭 정보를 전부 초기화한다.

## 페어 매칭 화면

- [x] 메인 화면에서 1을 입력하면 페어 매칭 화면으로 이동한다.
- [x] 페어 매칭 화면에서 과정, 레벨, 미션을 입력받는다.
  - [ ] 입력 형식에 부합하지 않으면 예외로 간주한다.
- [x] 입력 형식에 부합하는 경우 페어 매칭을 진행하고 저장한다.
  - 미션을 함께 수행할 페어를 두명씩 매칭한다.
  - 페어 매칭 대상이 홀수인 경우 한 페어는 3인으로 구성한다.
  - [x] 같은 레벨에서 함께 페어를 맺은 크루들의 정보를 저장한다.
  
- 페어 재매칭 시도
  - [ ] 같은 레벨에서 이미 페어를 맺은 크루와 페어로 매칭된 경우 예외로 간주한다.
  - [ ] 페어 매칭이 실패한 경우, 사용자로부터 재매칭 해당 입력 값으로 다시 재매칭을 진행하고자 하는지의 여부를 입력받는다.
    - [ ] 예를 선택한 경우, 크루 목록의 순서를 다시 랜덤으로 섞어서 매칭을 시도한다.
    - [ ] 아니오를 선택할 경우 코스, 레벨, 미션을 다시 입력받는다.
  - [ ] 3회 재매칭 시도까지 매칭이 되지 않거나 매칭을 할 수 있는 경우의 수가 없으면 예외로 간주한다.

- [ ] 페어 매칭 화면에서 입력값을 통해 페어 매칭 결과를 출력한다.
- [x] 이미 실행된 매칭 정보가 존재하는 경우 새로 매칭을 실행할지를 입력받는다.
  - [x] 네, 아니오 이외의 값을 입력하면 예외로 간주한다.
  - [x] 예외 발생시, 에러 메시지 출력 후 해당 부분의 입력을 다시 받는다.

## 페어 조회 화면

- [ ] 메인 화면에서 2를 입력하면 페어 조회 화면으로 이동한다.
- [ ] 페어 조회 화면에서 과정, 레벨, 미션을 입력받는다.
- [ ] 페어 조회 화면에서 해당 페어 매칭 결과를 출력한다.
- [ ] 해당되는 매칭 결과가 없는 경우 매칭 이력이 없다고 안내한다.
