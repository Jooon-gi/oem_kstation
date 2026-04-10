---
{"dg-publish":true,"permalink":"/01-new-product/04-operations/02-coa-checklist/","dg-note-properties":{}}
---

# COA Checklist — Lot별 검수 체크리스트

> 목적: COA 수령 시 내용 검수 기준 정의
> 최종 수정: 2026-04-10
> 상태: [Draft — OEM COA 발행 확인 전]

---

> ⚠️ **선행 조건:** OEM이 Lot별 COA 발행 가능하다고 확인된 후에 이 문서를 적용한다.
> COA 발행 여부는 `02_Product_Design/02_OEM_QA_프로토콜.md` Q10 답변으로 확인.
> OEM이 COA 발행을 거부하는 경우, 이 체크리스트는 해당 사항 없음.

---

## COA 항목 구분

---

## 확인 항목

| #   | 항목                   | 목표값          | 허용 범위       | 확인  |
| --- | -------------------- | ------------ | ----------- | --- |
| 1   | Lot Number           | 명시           | —           | [ ] |
| 2   | Manufacturing Date   | 명시           | —           | [ ] |
| 3   | Expiry Date          | 명시           | —           | [ ] |
| 4   | HA 농도                | OEM 확인값      | ±1 mg/mL    | [ ] |
| 5   | Sterility            | Pass         | —           | [ ] |
| 6   | Endotoxin            | < 0.25 EU/mL | —           | [ ] |
| 7   | pH                   | OEM 확인값      | ±0.2        | [ ] |
| 8   | G' (Elastic Modulus) | OEM 확인값      | ±20%        | [ ] |
| 9   | Osmolality           | OEM 확인값      | ±20 mOsm/kg | [ ] |
| 10  | Residual BDDE        | < 2 ppm (목표) | —           | [ ] |

> **항목 7-10:** OEM이 COA에 포함하는 경우에만 기재. 포함 여부는 `02_OEM_QA_프로토콜.md` Q10 답변 참조.
> **항목 10 (Residual BDDE):** OEM COA에 포함 시 제품 페이지 표기 가능.

---

## Lot 기록 테이블

| Lot # | 수령일 | HA (mg/mL) | pH | G' (Pa) | BDDE (ppm) | Sterility | 이상 여부 | 조치 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| (미기재) | | | | | | | | |

---

## 이상 발생 시 프로세스

1. 허용 범위 초과 항목 발견 → OEM에 즉시 통보
2. 해당 Lot 출고 보류
3. `05_Logs/01_의사결정_로그.md`에 이상 내용 및 조치 기록
4. 재검 또는 반품 여부 결정
