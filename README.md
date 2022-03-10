## TopDownGame

# 게임 프로그래밍 프로젝트

강의로 배운 언리얼의 기본 개념을 사용해 게임을 제작했습니다.

- 애니메이션
- 물리 엔진
- AI와 네비게이션
- UI와 사운드
- 블루프린트와 C++
- 카메라와 ray

# Game
<img src="https://user-images.githubusercontent.com/59460871/155918774-229efb95-8311-494a-8d21-c0a4da92501b.PNG"  width="400" height="200"/>

- TopDown 뷰로 적들에게서 최대한 오래 살아남는 게임입니다.
- wasd로 이동이 가능
- 마우스로 캐릭터 회전, 좌클릭으로 총 발사 가능
- 총알이 제한 되어 있어, 맵에있는 총을 지속적으로 획득해야합니다.
- UI로 체력과 총알을 보여줍니다.


# TopDownView
<img src="https://user-images.githubusercontent.com/59460871/157593218-252bce6a-96ad-4c2d-8284-fc0dd963008a.PNG"  width="400" height="200"/>

- 가장 구현하기 어려웠던 View 부분 입니다.
- 탑다운 뷰는 블루프린트로 만들었습니다.
- 카메라는 플레이어를 따라다니고 ray를 쏘아 마우스를 통과해 바닥에 충돌체크를 합니다.
- 과정에서 월드 좌표와 로컬 좌표에 대해 알 수 있었습니다.

# AI
<img src="https://user-images.githubusercontent.com/59460871/157593656-fd223e29-6038-4263-9a5a-820c3a98d838.PNG"  width="400" height="200"/>

- AI를 위한 비해비어트리입니다
- Navmesh로 지역을 정한 곳에서 플레이어를 따라갑니다
- 충돌 시 플레이어에게 데미지를 주며 주기는 1초입니다.
- 플레이어의 위치는 블랙보드에서 변수로 저장하고 전달해 줍니다.

# Item
<img src="https://user-images.githubusercontent.com/59460871/157594129-6082a833-ebd0-4e50-bf5f-156def0d132c.PNG"  width="400" height="200"/>
<img src="https://user-images.githubusercontent.com/59460871/157595619-214163b7-22b6-4876-9dfd-79db7fc7982b.PNG"  width="400" height="200"/>

- 충돌 시 총알을 획득하는 총을 스폰하는 블루프린트입니다.
- 플레이어의 움직임을 강제하는 효과를 위해 넣었으며
- C++클래스에서 획득시 사운드를 함께 넣어 주었습니다.





