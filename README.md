# skill_crane-smart_push
2016.09~11

# 작동 영상
![video_](https://user-images.githubusercontent.com/114469334/195970718-4bf11c1a-a08c-4a4d-b441-55537f46b372.gif)

# 작동 메커니즘
- 작동 스위치 한 개를 이용하여 진행된다. 
- 총 3단계로, 첫번째 입력은 작동 시작으로 x plot 방향으로 움직인다.
- 두번째 입력은 x plot방향의 움직임이 정지하고 z plot 방향으로 움직인다.
- 세번째 입력은 z plot 방향의 움직임이 정지하고 y plot 방향으로 push bar가 움직인다. 이후 경품을 내리는 모션을 취한 후에 원점으로 돌아온다. 이때 limit switch를 사용하여 원점위치를 파악한다. 
- 원점에 돌아온것을 인지하면 다시 초기 대기상태로 들어간다.

# 작품 의의
대학교에 들어오기 전에 Lego사의 mindstorm을 이용하여 여러 퍼포먼스를 구현해보았기에 lego와 atmega 128을 같이 이용해서 작품을 만들어보고 싶었다. 

# 사용된 품목
- 레고
- atmega 128
- DC motor x 2
- limit switch x 4
- push switch 
