# Class_GamePX_Design
여기는 2020년 2학기 GamePX_Design 수업에서 만든 프로젝트를 기록하고 있습니다

해당 수업을 따라온다면 다음과 같이 만들수있습니다

1. Dodge Game

![dodge](https://user-images.githubusercontent.com/71004742/187075374-7a56e076-a163-49fe-a877-ba2873c47d4b.JPG)

W,A,S,D를 사용해 화면의 좌우에서 날라오는 새를 피하는 게임입니다.

고양이는 화면 밖으로 나갈수없으며 한번 부딪친다면 게임오버입니다

spawner actor를 통해 새를 생성하고 새는 지정된 방향으로 움직이는 기능,
화면밖으로 나가면 삭제되는 기능을 구현했습니다

2. Platformer Game
![platformer](https://user-images.githubusercontent.com/71004742/187076019-f88339d8-81a9-49e9-8b57-aa59fb087f15.JPG)
W,A,S,D를 사용해 이동을 하며 space bar를 이용해 점프를, 마우스 오른쪽 버튼을 이용하여 적을 공격하는 platformer게임입니다

적과 부딪친다면 왼쪽 위에 있는 하트가 하나 줄어들고 뒤로 넉백이 됩니다.
만약 세번 적과 부딪쳐 목숨을 전부 잃는다면 게임오버가 됩니다

필드에는 총 두마리의 적이 있고 둘을 모두 쓰러트린다면 게임이 끝나게 됩니다

이 예제를 통해 중력이 있는 플레이어의 움직임, 적과 충돌시 넉백과 같은 물리엔진
타일맵을 통한 필드 제작과 
