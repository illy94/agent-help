# Claude 실무 활용 가이드

AI 워크샵에서 공유된 리소스와 실무 프롬프트 예제 모음입니다.

---

## 목차

1. [AI Orchestration Platform](#1-ai-orchestration-platform)
2. [터미널 멀티 세션 도구](#2-터미널-멀티-세션-도구)
3. [실무 프롬프트 예제](#3-실무-프롬프트-예제)
4. [패키징 디자인 도구 비교](#4-패키징-디자인-도구-비교)
5. [Claude Code 플러그인 (k-skill)](#5-claude-code-플러그인-k-skill)

---

## 1. AI Orchestration Platform

여러 AI 에이전트를 조율하고 복잡한 워크플로우를 구성할 때 사용하는 플랫폼입니다.

| 도구 | 링크 | 특징 |
|------|------|------|
| **CrewAI** | https://crewai.com/ | 역할 기반 멀티 에이전트 프레임워크. 에이전트에게 역할·목표·백스토리를 부여해 팀처럼 협업 |
| **LangGraph** | https://www.langchain.com/langgraph | 그래프 구조로 에이전트 흐름을 설계. 복잡한 분기·루프 로직에 강점 |

---

## 2. 터미널 멀티 세션 도구

| 도구 | 링크 | 특징 |
|------|------|------|
| **Superset** | https://superset.sh/ | 터미널 여러 세션을 동시에 관리하는 플랫폼 |

---

## 3. 실무 프롬프트 예제

업무 현장에서 바로 쓸 수 있는 Claude 프롬프트 20선입니다.  
👉 **[office_prompts.md](./office_prompts.md)** 에서 확인하세요.

### 포함 분야

| 분야 | 예제 수 | 주요 내용 |
|------|---------|-----------|
| 일반 사무 | 10개 | 이메일, 회의록, 보고서, 계약서 검토, IR 발표 등 |
| 유통업 | 5개 | 재고 분석, 상품 카피, 공급업체 협상, 프로모션 기획 등 |
| 제조업 | 5개 | 공정 이슈 분석, 품질 불량 공문, 설비 정비 계획 등 |

---

## 4. 패키징 디자인 도구 비교

### Claude로 가능한 것

- **SVG/HTML 디자인 목업** — 박스, 라벨, 포장지 등의 2D 디자인 시각화
- **디자인 컨셉 제안** — 색상 팔레트, 타이포그래피, 레이아웃 아이디어
- **라벨 텍스트/카피 작성** — 제품 설명, 성분표, 마케팅 문구
- **간단한 로고/아이콘 SVG 제작**
- **인쇄용 PDF 레이아웃** (기본 수준)

### 전문 디자인 AI 도구

| 도구 | 링크 | 특징 |
|------|------|------|
| **Canva Magic Studio** | https://www.canva.com/ | 드래그앤드롭 방식의 직관적 인터페이스. 초보자·소규모 비즈니스에 적합. Magic Resize, Magic Media, Brand Kit 기능 제공 |
| **Adobe Express / Illustrator** | https://www.adobe.com/ | Adobe Sensei AI 탑재. 자동 색상 보정, 스마트 오브젝트 선택 등 복잡한 작업 자동화. 업계 표준 |
| **Fotor** | https://www.fotor.com/ | AI 기반 고품질 이미지 향상에 강점 |
| **Packify AI** | https://www.packify.ai/ | 패키징 디자인 전문 AI 툴 |

### 추천 사용 시나리오

```
빠른 컨셉 확인·텍스트 초안  →  Claude
실제 인쇄용 고품질 디자인    →  Adobe Illustrator / Canva
패키징 특화 시각화           →  Packify AI
```

---

## 5. Claude Code 플러그인 (k-skill)

Claude Code에서 사용할 수 있는 한국 서비스 연동 스킬 모음입니다.

| 항목 | 내용 |
|------|------|
| **GitHub** | https://github.com/NomaDamas/k-skill |
| **설명** | 날씨, 지하철, 법령, 맛집, 특허 등 한국 공공 API를 Claude Code에서 바로 사용할 수 있는 스킬 플러그인 |

---

## 관련 파일

| 파일 | 설명 |
|------|------|
| [`office_prompts.md`](./office_prompts.md) | 실무용 Claude 프롬프트 20선 |
| [`AI Agent 실전 워크플로우.pdf`](./AI%20Agent%20실전%20워크플로우.pdf) | AI Agent 워크샵 발표 자료 |
| [`prmpt.md`](./prmpt.md) | 워크샵에서 사용한 프롬프트 모음 |

---

> 궁금한 점은 편하게 문의해 주세요.
