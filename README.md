# ErikaDCF — 스토리로 배우는 가치평가 (데모)

**목표**  
스토리를 바탕으로 가정치(성장률, 마진, WACC, CAPEX/매출)를 입력/시연하고, 간단 DCF 계산 결과를 보여주는 정적 웹앱입니다.  
AI 없이도 동작하며, 추후 API를 붙이면 확장 가능합니다.

## 배포 (Vercel)
1) GitHub에 이 리포지토리를 생성/업로드  
2) [Vercel](https://vercel.com) 로그인 → New Project → 이 리포지토리 선택  
3) Framework: Other → Deploy → `https://<project>.vercel.app` 발급

## 사용법
- 스토리 입력 → (선택) 시장가격 입력 →  
- (선택) 자동 시연 가정치 버튼 →  
- DCF 계산하기 → 결과/코멘트 확인

## 확장 아이디어
- Gemini/OpenAI 호출로 스토리→가정치 자동화
- 민감도 차트(± 성장률, ± WACC)
- 무료/유료 모드 분리(입력 유도 vs 자동 보완)
- 커뮤니티 공유(결과 링크/이미지 캡처)
