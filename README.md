# SPACE RESCUE — 주데렐라 구출 작전

브라우저에서 실행하는 3D 우주 탐험 게임 프로토타입입니다.

## 실행
- 저장소의 `index.html`을 브라우저에서 열거나 GitHub Pages로 배포합니다.
- Three.js는 jsDelivr CDN에서 불러오므로 인터넷 연결이 필요합니다.

## GitHub Pages 배포
1. 저장소의 **Settings → Pages**로 이동합니다.
2. **Build and deployment**에서 **Deploy from a branch**를 선택합니다.
3. Branch는 **main**, 폴더는 **/(root)**로 지정하고 Save를 누릅니다.
4. 배포가 완료되면 `https://yjh31415.github.io/SpaceGame/`에서 접속할 수 있습니다.

## 조작
- WASD: 우주선 추진 방향 입력
- Q / E: 상하 방향 입력
- ↑ / ↓: 전진·후진 입력
- 왼쪽 패널: 추진력, X/Y/Z 회전각, 시뮬레이션 배속
- PC 우클릭: 천체 정보
- 모바일 길게 누르기: 천체 정보
- 11레벨: SPACE 또는 FIRE 버튼으로 공격

## 저장
랭킹은 브라우저 LocalStorage에 저장됩니다. 브라우저 데이터 삭제 시 기록이 사라지며, 기기 간 자동 동기화는 지원하지 않습니다. CSV, JSON, TXT, HTML, XLSX 내보내기와 인쇄/PDF 저장을 지원합니다.

## 참고
현재 버전은 게임 플레이 기반을 갖춘 프로토타입입니다. 천체 중력·궤도 예측은 게임용 단위의 뉴턴 역학 근사이며, 블랙홀 렌즈·웜홀·상대론 효과는 시각적 연출입니다. 실제 일반상대론 광선 추적 시뮬레이터는 아닙니다.
