# code-crush-saga

웹에서 간단한 3-match 퍼즐 게임을 구현합니다! 


## 스켈레톤 코드

https://codesandbox.io/s/naughty-lamport-t5xgw?file=/src/index.js



## 기본 스펙
0. 구글 크롬에서 동작. index.html파일을 열어서 실행

1. form을 이용하여, width(6 ~ 10), height(6 ~ 10)의 보드가 초기화된다.

2. Cube의 색은 6가지로 이루어진다.

3. 유저가 인접한 두 cube를 선택하면, 두 cube의 위치가 바뀐다.

4. 바뀐 cube의 위치로 인해 3-match가 이루어지면 
 - 3 match된 블록들이 파괴된다.
 - 파괴된 블록 수만큼 점수가 늘어난다.
 - 빈 공간에 새로운 블록이 생성된다.

6. 3-match가 일어나지 않을 때까지 5가 반복되서 수행된다.

## 감점 요인

- 기능 오동작(버그)
- example...
  - 점수판의 미동작
  - 보드 크기 이하 or 이상으로 생성 가능
  - 함수가 무한루프로 동작
  - 인접하지 않은 블록끼리 스왑이 됨
  - 3-match가 제대로 일어나지 않음
  - 블록이 새로 생성되지 않음
  - 새로 생성된 블럭에서 3-match가 일어나지 않음
  
- 변수명이 난잡할 경우
- 함수의 역할이 너무 방대할 경우
- 쓸모없는 코드들이 필요 이상 작성된 경우
- 블록 색 판별이 불가능한 등의 채점을 필요 이상으로 방해하는 UI
- 파일 형식이 잘못된 경우

## 추가 스펙 (가점)


1. 처음 입력을 받을 시 cube의 색을 추가로 받는다(5~8)

2. 처음 생성된 보드에 3 match가 형성이 되지 않는다.

3. 4-3 이 수행되기 전에, 파괴된 블록 위에 위치한 블록들이 아래로 위치가 재조정된다.



## ETC
본인의 학번이름으로 index.html을 포함한 파일을 zip으로 압축하여 제출(2007-11186.zip)

5월 2일 23:59:59까지 제출이며, 5.5일까지 추가로 받을 예정. 딜레이 하루당 5%씩 감점.

질문은 github 이슈를 통해 받습니다.
