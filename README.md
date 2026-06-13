# SimonKMarket

> 마케팅·시장조사·여론 분석 오케스트레이션 플러그인

오케스트레이션 진입점: `/skmarket`

## 설치
```
/plugin marketplace add Simon-YHKim/SimonKMarket
/plugin install simonk-market@simonk-market
```

## 의존
SimonKCore 권장 동반 설치 (agent-delegate, model-router, instincts 등 공유 인프라). 없으면 일부 기능 제한.

## 구조
- `skills/` — 도메인 스킬
- `agents/` — 서브에이전트
- `commands/` — 슬래시 커맨드

_스킬 목록은 분류 매니페스트 확정 후 채워집니다._
