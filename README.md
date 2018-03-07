# Play Up&Down
범위를 지정하여 랜덤넘버 생성, 빠른 시간 내에 맞추는 게임
(https://simbyungki.github.io/updown/)

1. **시나리오 ver 1.2**
  - ~~사용자에게 'START' 버튼을 출력한다.~~
  - ~~별칭 입력 후 사용자가 'START' 버튼을 누른다.~~
  - ~~1부터 100까지 숫자 중 랜덤으로 숫자를 생성한다.~~
  - ~~화면 중앙에는 인풋박스와 'OK' 버튼이 위치한다.~~
  - ~~사용자가 숫자를 입력 후 엔터 또는 'OK' 버튼을 클릭(터치)하면 생성된 숫자와 비교한다.~~
  - ~~점수 산정을 위해 기회를 사용할때마다 배열에 숫자를 담는다.~~
  - ~~생성된 숫자보다 입력한 숫자가 alert('Down'),
      그 반대라면 alert('Up')을 출력한다.~~
  - ~~위 내용을 반복하다가 숫자가 일치하면 화면에 'COMPLETE' 메세지를 출력 한다.~~
  - ~~배열의 원소 수를 세어 점수를 반환한다.~~
  - ~~(with jQuery)~~

---
## Work History
- 2018.03.07 v1.2
  > 게임 닫기(종료) 버튼 추가
  > 화면 UI 수정
    > 숫자 입력 후 up & down 알림을 alert창에서 아이콘으로 변경 with fontawesome
    > 해상도 모바일 대응토록 변경
    > 애니메이션 추가
  > 별칭 입력 추가

- 2018.03.06 v1.2
  > 프로젝트 생성, 시나리오 구상, 화면 구성
  > 첫번쨰 목표(ver1.2)까지 완료 (모든 기능 작업 완료)
  > 모바일 이슈 확인

---
## Issue History
- ~~모바일(IOS) 키패드 문제 (input number로 했더니 ANDROID에서는 숫자키패드가 뜨지만 IOS에서는 숫자+특수문자 조합의 키패드가 오픈됨 > input tel로 변경 >> 2018.03.07)~~

---
## Schedule
- 랭킹 표시
  - 사용자의 닉네임 받아서 저장해야됨 (로컬 저장)
  - 사용자의 닉네임 받아서 저장해야됨 (DB 저장) > 최종버전
  - 닉네임 입력하지 않으면 'GUEST' + n 으로 자동생성 필요 (저장 및 비교 필요)
  - 정확한 순위계산을 위한 타이머 기능 (소요시간 체크)
- 게임 난이도 조절 (범위지정)
  - 사용자가 선택가능한 3가지 타입으로 조정 (1~100, 1~1000, 1~10000)

