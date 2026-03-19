# THE Hackathon - Knowledge Base

> THE 해커톤 Slack 채널의 공지사항, Q&A, 규칙을 정리한 레포지토리.
> Claude Code plugin으로 활용하여 해커톤 규칙/공지를 즉시 참조.

## 핵심 규칙 요약

### 매출 경쟁 규칙
- **매출 기준** 경쟁 (순이익 아님). 운영비(광고비, 도메인, Vercel, DB 등) 차감 안 함
- **초기 자본 제한**: 팀당 30만원. 이후 매출 내 재투자 허용
- **광고 집행 가능**: 대회 후 지출 증빙 필요
- **대회 종료 시 매출 - 비용 > 0** 이어야 함
- **비용 항목 제한**: 광고비(Paid Ad, 인플루언서 시딩) + 사용자 제공 LLM API 비용만
- **드랍쉬핑/중개**: IFRS 15 B34-B38 기준, 수수료율 x 거래액 = 매출
- **PB 매출**: 소프트웨어 판매만 인정 (강의/굿즈 불인정)
- **테스트/가상/예약 결제, 환불**: 매출 불인정

### PG 결제 준비
- 사전에 PG 벤더 선택 (Stripe, Polar, Toss 등) 및 계정 생성 필요
- 사업자 없는 팀: Polar 또는 Paddle (MoR 업체) 활용 권장
- 매출 리더보드: https://revenue.thehackathon.org/guide

### 크레딧 지원
- **OpenAI**: $200 크레딧 (Organization ID 필요)
- **Upstage**: 콘솔 계정으로 크레딧 지급

## 디렉토리 구조

```
announcements/   → 공지사항 (날짜별)
qa/              → Q&A 정리
CLAUDE.md        → 이 파일 (핵심 규칙 요약)
```

## 업데이트 방법

새 Slack 공지가 올라오면 `announcements/YYYY-MM-DD-제목.md` 파일로 추가.
Q&A는 `qa/` 폴더에 주제별로 정리.
