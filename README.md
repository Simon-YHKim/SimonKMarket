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

## 수록 스킬 (32개)

진입점 `/skmarket` 가 의도를 진단해 아래 스킬로 라우팅합니다. 개별 직접 호출도 가능.

`aarrr-growth-planner` · `ad-monetization` · `aha-moment-optimizer` · `analytics-integrator` · `churn-recovery-planner` · `cohort-retention-analyzer` · `community-marketing` · `exit-strategy-planner` · `experiment-analyzer` · `export-channel` · `feedback-and-review-collector` · `global-payment-planner` · `growth-engine` · `idea-validation` · `lifecycle-campaign-designer` · `mobile-attribution-integrator` · `monetization-planner` · `nocode-monetization` · `onboarding-flow-builder` · `paid-ads-campaign` · `payment-integrator` · `paywall-designer` · `pink-tax-advisor` · `pmf-analyzer` · `referral-program-builder` · `revenue-scenario-tester` · `skmarket` · `store-launcher` · `subscription-manager-selector` · `tag-manager-integrator` · `unit-economics-modeler` · `viral-launch`
