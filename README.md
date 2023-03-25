# 콘웨이의 생존 게임, 일명 Conway's Game of Life
이제 마인크래프트에서 플레이 하실 수 있습니다!

## 맵
https://drive.google.com/file/d/1RLuL_ABxeDAZpnwDEdopYtD2ethK02qM/view?usp=share_link   
**1.19.3** 까지 작동 확인 하였습니다.

## 플레이
### 내부 명령(자동)   

  `/scoreboard players set board_size board_size <int>`   
  **보드의 사이즈를 조절**합니다. (검은색 부분) -- *기본 10*
   
   
  `/scoreboard players set b.random board_size <int>`   
  **보드에 노드를 랜덤하게 뿌릴 양**을 정의합니다. (하얀색 부분) -- *200*   
   
   
   
  `/function con:start`   
  **시뮬레이션을 작동**시킵니다.   
  
  
  `/function con:stop`   
  **시뮬레이션을 정지**시킵니다.   
   
   
  `/function con:set/s`   
  **시뮬레이션의 변경 사항을 적용**시킵니다.



### 내부 명령(수동)   

  `/function con:reset`   
  **보드를 초기화**합니다.
   
   
  `/scoreboard players set b.random board_size <int>`   
  **보드에 노드를 랜덤하게 뿌릴 양**을 정의합니다. (하얀색 부분) -- *200*   
   
   
   
  `/function con:start`   **시뮬레이션을 작동**시킵니다.   
  `/function con:stop`   **시뮬레이션을 정지**시킵니다.   
   
   
  `/function con:set/s`   **시뮬레이션의 변경 사항을 적용**시킵니다.
