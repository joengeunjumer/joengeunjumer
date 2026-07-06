# Eunju JUNG — Architecture × AI Creative Technologist

건축을 전공하고(ENSA Nantes, 프랑스 국립건축대학 석사과정), AI를 설계·콘텐츠 제작 파이프라인에 통합하는 작업을 합니다.
서울의 건축·XR 스튜디오 **Scale Architecture / Scale Virtual**에서 16주 인턴십을 하며, 아래 프로젝트들을 **바이브 코딩(vibe coding)** — Claude Code를 중심으로 한 AI 페어 프로그래밍 — 으로 기획부터 배포까지 직접 구축했습니다.

> Architecture master's student (ENSA Nantes) working at the intersection of architectural design, XR, and AI-assisted development. All projects below were built end-to-end with AI pair-programming workflows (Claude Code, Claude API, Gemini, Kie.ai).

---

## 🛠 어떻게 만들었나 — Vibe Coding 방법론

1. **요구사항을 한국어/프랑스어 자연어로 정의** → Claude Code와 대화하며 아키텍처 설계
2. **프롬프트 자산의 버전 관리** — 시스템 프롬프트를 코드처럼 `docs/system-prompts/`에 버전·체인지로그·롤백 절차와 함께 관리
3. **멀티모델 오케스트레이션** — 작업 성격에 따라 Claude(추론·구조화), Gemini(이미지·씬 플래닝), Kie.ai/Seedance(영상 생성)를 조합
4. **사람은 방향과 검증, AI는 구현** — 커밋 로그가 그 과정의 기록입니다

## 📌 프로젝트

| 저장소 | 한 줄 소개 | 스택 |
|---|---|---|
| [myvrs-pipeline](https://github.com/joengeunjumer/myvrs-pipeline) | Claude·Gemini·Kie.ai를 오케스트레이션해 멀티프레임 XR 댄스 영상을 자동 생성하는 풀스택 앱 | Next.js 16 · React 19 · TypeScript · Supabase · FFmpeg |
| [archi-prompt-builder](https://github.com/joengeunjumer/archi-prompt-builder) | 한국어 건축 설명 → Gemini/ChatGPT용 구조화 렌더링 프롬프트 생성기 (58개 유스케이스, 6-슬롯 프롬프트 엔진) | Vanilla JS · Canvas API · Python |
| [scale-arch-ai-agent](https://github.com/joengeunjumer/scale-arch-ai-agent) | 한국어 한 문장 → 조감도 + SVG 평면도 + PDF 슬라이드 자동 생성 (시민 워크숍 시연 시스템) | Python · Gradio · Claude API · Gemini · Playwright |
| [scale-build-jitda](https://github.com/joengeunjumer/scale-build-jitda) | 파사드 리노베이션 마케팅 리드 엔진 + 공공데이터(건축물대장) 처리 파이프라인 | HTML/JS · Python · Supabase · Kakao/Naver Maps |
| [scale-website](https://github.com/joengeunjumer/scale-website) | 건축사무소 SCALe 웹사이트 — Hugo 레거시에서 Next.js로 마이그레이션, 자산 카탈로그 자동화 | Next.js · TypeScript · CSS Modules |
| [myvrs-content-lab](https://github.com/joengeunjumer/myvrs-content-lab) | XR 콘텐츠 제작을 위한 프롬프트 엔지니어링 문서·워크플로우 다이어그램 모음 | Prompt Engineering · n8n · Weavy |
| [venue-market-analysis-toolkit](https://github.com/joengeunjumer/venue-market-analysis-toolkit) | 상권분석을 위한 인터랙티브 지도 도구 (마커 DB·필터·편집 패널을 단일 HTML로) | JavaScript · Leaflet |

## 🎨 AI × 건축 디자인 워크

코드 외에도 ChatGPT·Gemini(Nano Banana)·Enscape를 활용한 건축 시각화 프로젝트를 진행했습니다:
- 베트남 붕따우 콘도 설계공모 — Grasshopper 파라메트릭 + AI 렌더링 파이프라인
- 키네틱 파사드 스터디, 아트 레지던시 시각화 등 (클라이언트 프로젝트로 비공개)
- [건축 AI 프롬프트 허브 리서치](research/architecture-ai-prompt-hub-research.md) — 건축 시각화 프롬프트 리소스 12곳 검증 리서치

## 📫 Contact

- Email: joengeunjumer@gmail.com
