# 임베디드 시스템을 활용한 <아두이노 보드게임>

# 어플 설명
  - 아날로그 보드게임과 디지털 스마트폰의 결합 
  - 사용자의 편리성을 높인 보드게임

# 구현한 기능 
파이어베이스 연결
- 아두이노와 파이어베이스 연동
- flutter앱과 파이어베이스 연동

랜덤 주사위 버튼
- 주사위 값 파이어베이스로 전송
- 파이어베이스를 통해 어플이 주사위 값 받아 숫자 표시

플레이어 자동 이동
- 3색 led이용하여 빛을 통해 플레이어 표시
- 주사위 값 만큼 플레이어 자동 이동

다 인원 사용
- ESP-32 WIFI 모듈 이용
- 와이파이를 firebase에 연결
- Firebase를 통해 어플에 정보전송

하이브리드 앱
- 안드로이드와 IOS 모두 설치 가능
