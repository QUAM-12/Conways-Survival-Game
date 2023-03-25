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

--------------

### 내부 명령(수동)   

  `/function con:reset`   
  **보드를 초기화**합니다.
   
   
  `수동으로 설치`   
  **보드에 직접 설치**하세요.   
   
  `/function con:go`   
  **시뮬레이션을 작동**시킵니다.   



## 주의사항

### 맵에 처음 들어간 경우 `/reload`를 실행해주세요.

너무 많은 수의 노드는 렉을 유발시킬 수 있습니다.   
명령어로 일부 막기는 하였으나 매우 서서히 작동 됩니다.

### **2차 수정 및 2차 배포**는 금지합니다.   

2차 수정을 막아놓았지만 제3자가 커맨드를 수정하여 고장이난 경우에는 특별한 답변을 드리지 못합니다.   


# 끝

한 개발자의 소중한 맵입니다. 잘 즐겨주세요.
