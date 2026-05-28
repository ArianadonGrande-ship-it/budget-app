# 📒 가계부

Google Sheets 연동 개인 가계부 웹앱입니다.

## 배포 방법

### 1. GitHub 저장소 만들기
1. [github.com](https://github.com) → New repository
2. 이름: `budget-app` (공개/비공개 무관)
3. `index.html`, `vercel.json` 업로드

### 2. Vercel 배포
1. [vercel.com](https://vercel.com) 로그인
2. **Add New Project** → GitHub 저장소 선택
3. 설정 변경 없이 **Deploy** 클릭
4. 완료되면 URL 생성 (`https://budget-app-xxx.vercel.app`)

## Google Sheets 연동
`index.html` 내 `GAS_URL` 값이 이미 설정되어 있습니다.
Apps Script 재배포 시 해당 값만 교체하면 됩니다.

## 기능
- 대시보드 (1/2/3개월, 막대/원형 차트)
- 지출 캘린더
- 내역 관리 (검색, 카테고리 필터)
- 예산 관리 (고정/변동 소계)
- 소비 패턴 + 카드별 분석
- 반복 내역 자동 적용
- 예산 초과 임박 알림 / 페이스 체크
- PC·모바일 동기화 (Google Sheets)
