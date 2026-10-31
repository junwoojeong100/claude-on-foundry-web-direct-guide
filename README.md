# Claude on Foundry — Web Direct 구독 화면 가이드

기존 Entra 테넌트에서 **Web Direct(Pay-As-You-Go) 구독**을 만들고, Microsoft Foundry에서 **Claude**를 배포하기까지의 Azure Portal·Foundry 화면을 단계별로 정리한 1페이지 가이드입니다.

**바로 보기 → https://junwoojeong100.github.io/claude-on-foundry-web-direct-guide/**

- **PART A** — Web Direct 구독 만들기 (기존 테넌트 · Directory 확인)
- **PART B** — Foundry에서 Claude 배포
- **PART C** — `MarketplaceSubscriptionCannotBeCompleted`로 막혔을 때 (지원 요청 → 재배포 → Succeeded)
- **PART D** — 모든 리전이 ‘할당량 부족’일 때 (구독 쿼타 티어 확인 → 자동 승급 이해 → 쿼타 증가 신청). 화면 캡처 없이 Microsoft Learn만 근거로 작성

라이트/다크 모드를 지원하며(우측 상단 버튼) 대부분의 이미지는 `index.html`에 포함되어 있고, 2026-10-30에 현재 Foundry 화면으로 새로 찍은 3장(STEP 7~8)은 `assets/`에 있습니다. 화면의 계정·구독 ID·테넌트는 예시 값(Contoso)으로 바꾸고 입력란은 가렸습니다.

> 개인 저장소이며 Microsoft 공식 문서가 아닙니다. 화면은 2026-10-27~30, PART D의 Learn 내용은 2026-11-01 기준이므로 포털 화면과 [Microsoft Learn](https://learn.microsoft.com/azure/foundry/foundry-models/how-to/use-foundry-models-claude)의 최신 내용을 함께 확인하세요.

## 업데이트

`main` 브랜치에 push하면 GitHub Pages가 자동으로 다시 배포합니다(약 1~2분 후 반영).

```bash
git add index.html assets && git commit -m "update guide" && git push
```
