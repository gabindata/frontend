# 스네이크 게임 :snake:
## 게임 설명 
### 한 줄 소개
사용자가 벽에 부딪히지 않게 뱀을 움직이면서 먹이를 먹으며 score를 얻는 게임
### 작동방식
- 뱀:
  1. 상하좌우 키를 통해 사용자가 뱀의 이동 방향을 조절
  2. 방향에 따라 계속해서 직진으로 이동
  3. 먹이와 닿을 때마다 꼬리가 하나씩 생김
  4. 꼬리, 벽에 닿으면 게임 오버 -> 게임 오버 화면
- 먹이:
  1. 뱀이 한 차례 먹이와 닿을 때마다 다음 판으로 이동, 벽 안에서 랜덤으로 위치
  2. 닿으면 score가 1씩 증가함
- 게임 오버:
  1. 게임 오버 화면에 Final Score가 공개됨
  2. Restart 버튼을 누르면 score가 0부터 다시 시작
