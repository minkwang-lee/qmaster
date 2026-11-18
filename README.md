# 🥚 품질 마스터 (Quality Master)

### 🏆 [해커톤 출품작 소개 페이지](https://minkwang-lee.github.io/qmaster/hackathon.html)

휴대폰에서 링크를 직접 눌러 읽고 게임을 실행할 수 있습니다. QR 스캔은 필요하지 않습니다.


**50초 결함 검출 아케이드 게임** · 모바일/PC 지원 · 설치 불필요

### 🎮 [바로 플레이하기](https://minkwang-lee.github.io/qmaster/)

[![모바일 접속용 QR 코드](qr.svg)](https://minkwang-lee.github.io/qmaster/)

QR코드를 스마트폰 카메라로 스캔하면 게임이 바로 열립니다. 앱을 다운로드할 필요가 없습니다.

### 게임 규칙
- 결함 계란: 판정선에서 클릭/터치
- 정상 동작: 건드리지 않고 통과
- 연결 결함: 드래그로 한꺼번에 검출
- 크리티컬 폭탄: 판정선에서 3번 터치 (초반 연습 폭탄 등장)
- 긴급 패치: 3초간 속도 저하
- 25초에 데드라인 모드, 50초에 종료
- 최종 결과 이미지 저장 후 점수 제출

### 첫 배포 시 GitHub Pages 설정
저장소 관리자만 한 번 설정하면 이후 `main/index.html` 변경이 자동으로 반영됩니다.

1. [Settings → Pages](https://github.com/minkwang-lee/qmaster/settings/pages) 이동
2. **Build and deployment → Source:** `Deploy from a branch`
3. **Branch:** `main`, **Folder:** `/(root)`
4. **Save** 클릭

공개 주소: https://minkwang-lee.github.io/qmaster/

> 이 게임의 점수는 브라우저에서 계산됩니다. 상품이 걸린 대회라면 제출 이미지의 임의 조작 가능성을 고려하세요.
