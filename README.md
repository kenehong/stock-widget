# Big Tech Dashboard

MAG7 + AMD 8개 빅테크 기업의 재무 지표를 한눈에 비교하는 싱글 파일 대시보드.

## Features

- **A-F 등급 시스템** — 밸류에이션, 성장성, 수익성, 현금흐름 4단계 분석
- **기업 카드** — P/E, PEG, 매출성장, GM, EPS성장, OP Margin 한눈에
- **랭킹 사이드바** — 카테고리별 TOP 3 실시간 표시
- **디테일 모달** — 12개 지표 + 초보자용 비유 설명
- **뉴스 해설** — 기업별 최신 뉴스 3건, 초등학생도 이해하는 설명 + 원본 출처
- **FMP API 연동** — Financial Modeling Prep API로 데이터 새로고침

## 종목

AAPL · MSFT · GOOGL · AMZN · NVDA · META · TSLA · AMD

## 사용법

`index.html`을 브라우저에서 열면 됩니다. 별도 설치 불필요.

API 데이터 새로고침을 원하면 [FMP](https://financialmodelingprep.com/developer)에서 무료 API 키를 발급받아 설정하세요 (일 250건).

## Tech Stack

- Single HTML file (no build)
- Chart.js 4.4
- CSS Variables + Grid
- LocalStorage (API key 캐싱)
