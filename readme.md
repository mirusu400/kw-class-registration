# 광운대학교 수강신청 연습 프로그램

![0](assets/title.png)

광운대학교 학생들을 위한 수강신청 모의 연습 프로그램입니다.

<br>

## 설명

![1](readme/1.png)

실제 수강신청 프로그램과 완전히 동일한 인터페이스를 갖추고 있습니다.

`수강신청 연습 시작하기` 버튼을 누르면 수강신청 시작 10초 전 상황을 가정합니다.

수강신청이 시작되면 실제 프로그램과 동일하게 시작 알림창이 뜨며

과목별로 `조회` 버튼을 누르고 `수강신청` 버튼을 눌러 수강신청을 진행합니다.

<br>

## 기능

- 과목 수 지정
  
![2](readme/3.png)

수강신청 할 과목 수를 직접 지정할 수 있습니다. (최대 10개)

<br>

- 과목 자동 추가 및 세부 내용 변경

![3](readme/4.png)

지정한 과목 수 만큼 자동으로 과목이 즐겨찾기에 추가되며

과목명과 같은 세부 정보를 수정할 수 있습니다.

<br>

- 과목 조회 딜레이

![4](readme/5.png)

실제 수강신청 시 서버 간 통신으로 인해 과목 조회 버튼 클릭 시

일정시간 딜레이가 발생하는 현상을 연습 프로그램에도 동일하게 적용시켰습니다.

딜레이는 일정하지 않고 `0.3초` ~ `0.5초` 사이만큼 랜덤하게 발생합니다.

<br>

- 만석인 상황 대비

![5](readme/2.png)

실제 상황에서 원하던 과목이 만석이 되는 상황을 겪을 수 있습니다.

이 때는 당황하지 않고 빠르게 창을 내리고 다른 과목의 수강신청을 이어나가야 합니다.

이에 대비할 수 있게 **일정 확률**로 신청하려는 과목이 `만석`이 되게끔 구현했습니다.

한 번 만석이 된 과목은 신청할 수 없으며, 만석이 되는 확률과 수강 신청 속도와는 무관합니다.

<br>

- 프로그램 설치 조건

이 프로그램은 실제 수강신청 프로그램과 동일하게 실행을 위해서 `.Net Framework` 가 필요합니다.

따라서 이 프로그램의 실행 여부로 실제 수강신청 프로그램이 실행 가능한 지 판별할 수 있습니다.

<br>

프로그램 사용 방법 문의: yjyoon-dev@gmail.com

