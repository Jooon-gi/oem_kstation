---
{"dg-publish":true,"permalink":"/00-overview/kstation-master/","noteIcon":"","created":"2026-04-10T14:30:39.149+09:00","updated":"2026-04-10T16:34:44.468+09:00","dg-note-properties":{}}
---

# KSTATION Manufacturing — Master Index

> 버전: v1.2 | 생성: 2026-04-02 | 최종 수정: 2026-04-10
> 본 파일은 LLM 컨텍스트용이 아닌 프로젝트 맵핑(Mapping) 역할을 합니다.

---

## 프로젝트 원칙

> **Community_Painpoints → Spec → Marketing** 순서 유지.
>
> 1차 출시 철학: **합리적인 가격으로 진입장벽을 낮추고, 내 피부 타입에 맞는 가이드로 선택을 쉽게 만든다.**
> OEM 미확인 수치는 마케팅 클레임으로 사용하지 않는다.

---

## 📂 00_MASTER Modules

- 👑 **[`01_제품전략_핵심.md`](./01_제품전략_핵심.md)**
  - 제품 철학, 핵심 타겟(뉴비/고관여층 × Track A-C), 차별점, 절대 금지 사항 포함.

- ⚙️ **[`02_프로세스_프로토콜.md`](./02_프로세스_프로토콜.md)**
  - (프로세스 참고용)

- 🏷️ **[`03_브랜드_네이밍.md`](./03_브랜드_네이밍.md)**
  - (클라이언트 컨펌 대기)
  - 브랜드명 후보군(Vera Fill / Essen Fill / Purä Fill / Novo Fill) + 선정 기준 + 컨펌 프로세스.

---

## 📂 Vault Tree (핵심 구조)

```
Kstation_Manufacturing/
├── 00_Overview/
│   ├── 01_제품전략_핵심.md      
│   ├── 02_프로세스_프로토콜.md
│   ├── 03_브랜드_네이밍.md               ← 브랜드명 후보 + 클라이언트 컨펌 프로세스
│   └── KSTATION_마스터.md
├── 용어사전.md                          ← 용어 정의
├── 신제품_프로젝트_브리프.md         ← 1차 프로젝트 요약 브리프
└── 01_New_Product/                         ← 1차 출시 (LINE FILL 동일성분 OEM)
    ├── 01_Research/
    │   ├── 01_커뮤니티_페인포인트.md   ← 커뮤니티 신호 누적 (상시 업데이트)
    │   ├── 02_경쟁사_분석.md    ← 경쟁 제품 분석
    │   └── 03_타겟_페르소나.md         ← 구매자 페르소나 (뉴비/고관여층)
    ├── 02_Product_Design/
    │   ├── 01_스펙시트.md             ← 확정 스펙 + OEM 대기 항목
    │   ├── 02_OEM_QA_프로토콜.md        ← OEM 질의 목록 및 답변 기록
    │   └── 03_라인업_설계.md          ← FINE/DEEP/SUB-Q 라인업
    ├── 03_Marketing/
    │   ├── 01_메시지_프레임워크.md    ← 브랜드 메시지 구조 (뉴비/고관여층)
    │   ├── 02_커뮤니티_언어뱅크.md ← 채널별 언어 뱅크 (Track A-C)
    │   └── 03_론칭_시퀀스.md        ← 론칭 타임라인 + 콘텐츠 매트릭스
    ├── 04_Operations/
    │   ├── 01_OEM_벤더_로그.md         ← OEM 업체 접촉 이력 (AQUABANK INC.)
    │   ├── 02_COA_체크리스트.md          ← Lot별 COA 검수 체크리스트
    │   └── 03_Regulatory_Compliance.md  ← FDA/CE/Health Canada 규제 트래킹
    └── 05_Logs/
        ├── 01_의사결정_로그.md           ← 의사결정 이력
        └── 02_커뮤니티_신호_로그.md   ← 커뮤니티 신호 + 트랙별 반응 기록
```

---

## 🗺️ Copilot 사용 시작점

> 매 세션: `copilot/ROUTER.md` 또는 `SESSION_ROUTING_CHEAT_SHEET.md`에서 첨부 파일 확인 후 시작.

---

## 📂 파일 간 흐름 (Dependencies)

```
01_제품전략_핵심.md
        ↓ 방향 제시
01_New_Product/01_Research/01_커뮤니티_페인포인트.md
        ↓
01_New_Product/02_Product_Design/01_스펙시트.md  ←→  02_OEM_QA_프로토콜.md (OEM 협의)
        ↓ OEM [Confirmed] 항목만
01_New_Product/03_Marketing/02_커뮤니티_언어뱅크.md
        ↓
01_New_Product/03_Marketing/03_론칭_시퀀스.md
        ↓
01_New_Product/05_Logs/ (전 단계 기록)
```

---

## 🔗 연동 프로젝트

- **Kstation_Reddit**: J.S. 페르소나 마케팅 — 커뮤니티 신호 수집 및 론칭 후 트랙 반응 관찰
- **Manufacturing_Documents**: OEM 협의 가이드라인, 북미 필러 전략 참고 자료
