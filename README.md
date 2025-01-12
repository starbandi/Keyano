키아노

1. 프로젝트 소개
키아노(Kiano)는 사용자가 업로드한 악보를 자동으로 리듬 게임 차트로 변환하는 시스템입니다.
음악 학습과 게임을 결합하여 새로운 경험을 제공합니다.

2. 파일 실행 방법
프로그램_키아노_우유들.unitypackage: Unity 프로젝트에 패키지를 불러와 실행하세요.
Unity에서 불러오는 방법: Assets → Import Package → Custom Package → 해당 파일 선택
3. 사용한 Unity 버전
Unity 2021.3.1f

설명서
시작 화면에서 가이드를 누르게 되면 보기 쉽게 게임룰을 설명하는 글이 나옵니다.

게임시작을 눌러 메인화면으로 가게 되면 원하는 곡을 선택할 수 있도록 하였고, 가이드와 연습모드 또한 즐겨볼 수 있습니다.

여러 곡들 이미지 하단에 있는 재생 버튼을 통해 연주하려는 곡을 미리 들어볼 수 있도록 구현하였습니다.

하고 싶은 곡을 선택해 Start 버튼을 누르면 게임이 바로 시작됩니다.

키보드의 Q - W - E - R - T - Y - U - I - O - P -[ - ] 를 사용해 리듬게임을 즐길 수 있습니다.


게임에 대한 룰을 자세히 설명해 드리자면, 음악의 박자에 맞춰 내려오는 채보를 타이밍 맞게 키보드 특정 키를 누르게 되면 점수와 정확도 게이지가 올라갑니다.

단, 채보와 피아노 건반이 겹쳐있지 않을 때 키를 누르거나, 채보를 누르지 못했다면 정확도 게이지는 점점 떨어지게 됩니다.

정확도 게이지가 끝까지 떨어지게 된다면 게임오버가 된다는 점 꼭 유의해 주세요!

게임오버가 되면 게임 점수와 최고점수를 보여줍니다. 재시작과 메인화면 버튼도 구현하였고, 게임종료 버튼을 눌러 게임을 종료할 수 있습니다.


다음으로는 누른 채보 개수에 따라 점수가 증가되는 콤보 시스템을 설명하겠습니다.

틀리지 않고 누른 누적된 채보가 8개, 16개, 24개 이상이 되면 점수가 순서대로 2배, 3배, 4배가 되어 증가합니다.

하지만 채보를 누르지 못하거나, 겹쳐있지 않을 때 키를 누르게 되면 누적된 채보가 0개로 다시 바뀌게 됩니다.


연습모드는 음악과 채보가 내려오지 않고, 키를 눌렀을 때 피아노 소리만 나와 오직 피아노만 연주하고 싶은 사용자에게 좋은 기능입니다.

지금까지 키아노 사용 설명서였습니다. 즐거운 게임되세요 감사합니다.
