# 261100_seoul — 남선초등학교 서울 1박 2일 스마트 가이드북

Tourmaker VIP 스마트 가이드북 (안내 초안).

## 배포

- GitHub Pages: https://indadady.github.io/261100_seoul/
- 저장소: `Indadady/261100_seoul` · `main` · `/`

## 행사 개요

| 항목 | 내용 |
|------|------|
| 학교 | 남선초등학교 |
| 일정 | 1박 2일 · **날짜 미정** (안내 초안) |
| 인원 | 학생 15 + 교사 5 = **20명** |
| 이동 | 전용버스만 |
| 숙소 | 밀리토피아 호텔 바이 마린 (성남 위례) · 031-8097-9000 |

## 일정 요약

**1일차**  
09:00 학교 출발 → 13:00 키자니아(중식·체험) → 17:30 애슐리퀸즈 → 19:30 겨울왕국 뮤지컬 → 21:00 호텔

**2일차**  
06:00 조식 → 09:00 호텔 출발 → 10:00–15:00 롯데월드 → 학교 귀가

## 비상 연락망

| 역할 | 이름 | 연락처 |
|------|------|--------|
| 인솔·현장 | 조혁 | 010-4249-4026 |
| 안전 매니저 | 이재명 | 010-9443-7881 |
| 호텔 프론트 | 밀리토피아 | 031-8097-9000 |
| 현지 가이드 | 미정 | — |

## 로컬 파일

```
261100_seoul/
├── index.html
├── README.md
├── .gitignore
└── assets/
    ├── IMAGE_CREDITS.md
    └── images/
        ├── hero.jpg
        ├── og-thumb.jpg
        ├── hotel.jpg
        ├── day1-kidzania.jpg
        ├── day1-jamsil.jpg
        ├── day1-musical.jpg
        └── day2-lotteworld.jpg
```

## 기술 메모

- GA4: `G-JLH9GD9SVR`
- localStorage prefix: `tm_261100_seoul_`
- 날짜 확정 전 D-day 배지: `안내 초안` (`TOUR_START` / `TOUR_END` = `null`)
- 인쇄: 헤더 **일정표 인쇄하기** 1개 · A4 `#print-area` 이중 DOM
