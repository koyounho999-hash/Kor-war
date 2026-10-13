# 6·25 전쟁 전선 이동 인터랙티브 아카이브

정적 HTML/CSS/JavaScript 웹앱입니다. GitHub 저장소에 그대로 올리거나 Vercel에 배포할 수 있습니다.

## 구조
- `index.html`: 화면 마크업과 SVG 한반도 지도
- `css/style.css`: 공통 UI와 세피아/아카이브 디자인
- `css/intro.css`: 시작 화면/긴급 방송 보조 스타일
- `css/map.css`: 지도 전용 보조 스타일
- `data/events.js`: 6·25 전쟁 주요 사건, 날짜, 기간, 설명, 단계별 전선 y좌표
- `data/frontlines.js`: 전선 SVG 기준 x좌표
- `data/locations.js`: 사건 장소와 애니메이션 중간 지점 좌표
- `js/app.js`: 앱 상태, 지도 렌더링, 사건 전환, 자동 재생, 시작 연출을 연결하는 핵심 런타임
- `js/map.js`: 지도 모듈 확장 지점
- `js/timeline.js`: 연표 모듈 확장 지점
- `js/animation.js`: 애니메이션 설정 모듈
- `js/audio.js`: 합성 경보/나레이션 설정 모듈
- `js/intro.js`: 시작 연출 설정 모듈
- `assets/`: 추후 오디오·사진·지도 원본을 분리 저장하는 폴더

> 전선은 역사 학습을 위한 단순화된 표현이며 실제 날짜별 군사지도를 정밀 복원한 선이 아닙니다.
