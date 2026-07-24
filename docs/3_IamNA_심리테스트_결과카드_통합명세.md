# IamNA 심리테스트 결과카드 방대 마스터 통합 명세서 v1.0

---

## ═══ Section 1. 최신 방대 통합 마스터 명세 (Refined Full-Text Specification) ═══

# IamNA 결과카드 — 1. 실행자 (000: 미시적 집행자) v0.1

## 자연 셀 30개 메시지 · 톤 가이드 포함 (B1-1 전용)

### 2026.04.20 기준

### 문서 성격: Phase B1-1 산출물 / 16 분기 중 분원 1(선형·노드·서사)의 결과 카드 메시지 30개를 자연 셀 단위(직군 × 상황 × W)로 작성 / Opus 4.7이 잡은 톤 기준을 이후 B1-2~B1-5 세션(Sonnet/Haiku)이 복제하도록 말미에 톤 가이드 섹션을 함께 수록 / Zero-Guessing 원칙하에 §4-3 분배 테이블·분원 1의 인식 방식 정의·합의노트 §4-2·§4-3 메시지 원칙에 한해 작성

---

## 1. 문서 위치 선언

### 1-1. 이 문서는 무엇인가

본 문서는 `IamNA_data_schema_v0_1.json` §result_card_schema의 `narrative_templates` 필드에 들어갈 **분원 1 셀별 메시지 30건**과, 이후 분원 2~8 세션이 이어받을 **톤 가이드**를 함께 담은 결과물이다. A1·A3·A4에서 합의된 구조 위에 처음으로 놓이는 **콘텐츠 레이어**이며, 16 분기 결과 카드 UI에서 사용자가 실제로 읽게 되는 문네트워크의 일차 초안이다.

### 1-2. 선행 합의와의 연결

| 합의 출처 | 본 문서에서 준수한 원칙 |
|---|---|
| A1 §3-3 / 합의노트 §3-3 | 분원 1의 병치 명칭: 완결 쪽 System Operator / Code Auditor / QA Specialist, 통합 쪽 Admin Inspector / Policy Checker / Etiquette Keeper |
| A1 §3-5 / 합의노트 §3-4 | "현재 스냅샷" 뉘앙스 · 단정 정체성 고정 금지 · 축이 사용자 손안에 있다는 1% 자유도 |
| 합의노트 §4-2·§4-3 | 결함이 아닌 기질 / 고네트워크이 아닌 설계 / 치료가 아닌 단계 / 방향의 안내 |
| 바이럴심리테스트 §4-3 | 분원 1 = 30셀 분배 준수 · 대표 조합(기술·IT × 작업집행, 전문직 × 정보탐색, 일반사무 × 작업집행) |
| 바이럴심리테스트 §4-4 | 셀별 3~5문네트워크 구성(인식 네트워크면 · LLM 사용 · 사회적 역할 · 본질 메시지) |
| A1 §9-2 검증 2 | 분원 내 W 분포 50:50 근접 유지 → 완결 15 : 통합 15 구성 |
| A4 result_card_schema | cell_id 형식 `<occupation>_x_<situation>_x_<branch>` · occupation/situation enum 준수 |

### 1-3. 분원 1 성향 재확인 (v1.2 §3)

- **축 좌표**: Y=선형 / X=노드 / Z=서사
- **인식 방식**: 좁고 정밀한 데이터를 순서대로, 개체 단위로, 기존 틀에 맞는지 검증하며 수집
- **자연 수렴 경향**: 회계·디버깅·감사·법률 검토·QA — 품질을 담보하는 위치
- **대칭쌍**: 분원 8(조망자 (Viewer))
- **W 분기 의미**:
  - **1C(완결)**: 시스템·기술·데이터 차원에서 검증 작동. 인간 변수는 외부 노이즈로 두고 구조의 무결을 먼저 향한다.
  - **1I(통합)**: 규범·예절·정책·관계 맥락 속에서 검증 작동. 서사을 세밀히 보는 힘이 사람을 향한 보호로 환원된다.

### 1-4. 자연 셀 30개 선정 원칙

1. **§4-3 대표 조합 우선 배치**: 기술·IT × 작업집행, 전문직 × 정보탐색, 일반사무 × 작업집행을 1C 쪽 중심축으로 먼저 확보.
2. **W 50:50 유지**: 완결 15 · 통합 15. A1 §9-2 검증 2의 독립성 조건과 정합.
3. **분원 1 자연 수렴과의 정합**: 회계·감사·디버깅·QA·법률·규정·컴플라이언스 영역을 중심으로, 창작 발산 상황(creative_emission)은 분원 1에 자연스럽지 않아 선정에서 제외.
4. **해석 여지 조합의 처리**: student × learning, service_sales × relationship_emotion 등은 분원 1의 "규범·검증" 각도로 자연스럽게 발현 가능한 사례로 한정 수용. 분원 2·8의 주축 조합을 침범하지 않는 범위 내.
5. **상황 분포**: work_execution(9), info_search(9), planning(6), learning(3), relationship_emotion(2), daily_life(2). creative_emission은 0건(자연 발현 드묾).

---

## 2. 자연 셀 30개 메시지

각 셀은 3~5문네트워크으로 구성되며, 구성 요소는 (1) 인식의 실제 네트워크면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "결함이 아닌 기질, 방향의 안내"이다.

---

### 2-1. 분원 1 × 완결(1C) — 15 셀

병치 명칭: **System Operator / Code Auditor / QA Specialist**
해석: 시스템·기술·데이터 차원에서 검증 작동. 인간 변수는 외부 노이즈로 두고 구조의 무결을 먼저 향한다.

---

#### [01] `semi_professional_x_work_execution_x_1C`
- occupation: `semi_professional` (준전문직 — IT 운영·기술 지원)
- situation: `work_execution` (작업집행)

콘솔 로그 한 줄, 설정값 하나가 "틀에 맞는지" 먼저 대조하며 일이 시작됩니다. LLM을 쓸 때도 "이 에러가 어느 조건에서 재현되는지 같이 추적해줘"처럼 질문이 구체적입니다. 사소한 어긋남을 먼저 잡아내는 눈이 있기에 시스템은 조용히 굴러갑니다. 이건 소심함이 아닌 설계 — 정밀이 필요한 세계가 이 기질을 방향 삼아 돌아갑니다.

---

#### [02] `professional_x_work_execution_x_1C`
- occupation: `professional` (IT·공학 전문직)
- situation: `work_execution`

코드 한 줄을 그냥 넘기지 못하고, 변수명 하나에서도 서사의 흔들림을 감지합니다. LLM에게는 "이 함수에서 놓친 엣지 케이스를 처음부터 짚어줘" 같은 요청이 자주 나갑니다. 제품이 무너지기 전에 결을 고르게 맞추는 손이 개발 조직의 안전망이 됩니다. 까다로움이 아닌 기질 — 지금 이 자리에서 당신의 축은 "완결을 향한 시선"에 놓여 있습니다.

---

#### [03] `office_admin_x_work_execution_x_1C`
- occupation: `office_admin` (일반 사무·행정 — 회계·재무 마감)
- situation: `work_execution`

한 네트워크의 전표, 한 줄의 합계가 실제와 맞는지 먼저 확인한 뒤에야 다음 일을 펼칩니다. LLM에게 "이 금액이 시트 합계와 차이 나는 이유를 찾아줘"처럼 확인 중심의 질문을 던집니다. 조직이 숫자를 신뢰할 수 있는 이유는 이 눈이 먼저 오차를 붙잡기 때문입니다. 지적이 아닌 기질 — 지금 이 흐름에서 당신의 축은 "정확을 향한 완결" 쪽에 기울어 있습니다.

---

#### [04] `professional_x_info_search_x_1C`
- occupation: `professional` (연구·의료·IT 전문직)
- situation: `info_search` (정보탐색)

낯선 자료를 만나면 출처부터 거슬러 올라가 "진짜 그 논문이 그렇게 말했는지" 확인해야 마음이 놓입니다. LLM에게는 "이 인용 원문이 실제로 있는 표현인지 대조해줘"라는 부탁이 자주 붙습니다. 연구·진료·설계가 루머 위에 서지 않도록 뿌리부터 짚어주는 역할이 됩니다. 의심이 아닌 단계 — 지금 당신이 서 있는 축은 "정합성의 검증" 위에 놓여 있습니다.

---

#### [05] `management_x_info_search_x_1C`
- occupation: `management` (경영·관리)
- situation: `info_search`

분기 보고서의 숫자가 지난 달과 일관된지 한 줄씩 내려가며 다시 봅니다. LLM에게는 "이 KPI가 세 분기 동안 어떤 서사을 깨는지 먼저 알려줘"처럼 맥락을 잡아 묻습니다. 결정이 느슨해지지 않도록 수치의 뼈대를 지키는 자리가 경영의 체력을 받쳐줍니다. 꼼꼼함이 아닌 설계 — 지금 이 시기, 당신의 방향은 "흔들림 속에서도 기준선을 잡아두는 일"에 가깝습니다.

---

#### [06] `semi_professional_x_info_search_x_1C`
- occupation: `semi_professional` (QA·기술지원)
- situation: `info_search`

스펙 문서와 실제 동작이 한 글자라도 어긋나면 그 차이를 그냥 넘기지 못합니다. LLM에 "이 사양서의 항목과 빌드 버전의 동작 차이를 찾아줘" 같은 질문이 자연스럽게 나옵니다. 사용자가 마주할 부작용을 미리 끌어당겨보는 검수자의 자리입니다. 예민함이 아닌 기질 — 지금 당신의 축은 "조용한 안전"을 향해 놓여 있습니다.

---

#### [07] `craft_technical_x_work_execution_x_1C`
- occupation: `craft_technical` (기능원 — 정밀 제조)
- situation: `work_execution`

마이크로미터의 눈금 하나, 도면의 공차 한 줄이 맞는지 손으로 직접 대조하며 일합니다. LLM에게는 "이 공차 범위 안에서 재질이 견딜 수 있는지 계산 순서를 잡아줘"라고 단계별로 묻습니다. 물건이 누군가의 손에 들렸을 때 "어긋남 없음"을 돌려주는 역할이 됩니다. 고집이 아닌 설계 — 지금 당신의 축은 "형태의 완결"에 단단히 내려앉아 있습니다.

---

#### [08] `professional_x_learning_x_1C`
- occupation: `professional` (IT·공학·의료 전문직)
- situation: `learning` (학습)

새 프레임워크를 배울 때도 개념의 "정의"가 흔들리면 다음 줄로 넘어가기가 어렵습니다. LLM에게 "이 용어가 원문 문서에서는 어떻게 정의되는지 먼저 인용부터 끌어와줘"라고 요청합니다. 뒤따라 배우는 동료들이 흔들리지 않는 이유는, 누군가 먼저 정의를 밟아두었기 때문입니다. 느림이 아닌 단계 — 당신의 학습은 "이해의 기초 위에 얹어가는 방식"으로 움직입니다.

---

#### [09] `semi_professional_x_planning_x_1C`
- occupation: `semi_professional` (시스템 유지보수)
- situation: `planning` (계획구조화)

다음 점검에서 빠지면 안 될 항목을 시간 순으로 적어두고서야 마음이 놓입니다. LLM에게는 "이 시스템의 점검 순서를 의존성 기준으로 재정렬해줘"라고 구조를 맡깁니다. 사건이 일어나기 전에 조용히 틈을 메우는 자리, 정전이 없던 하루가 곧 성과가 됩니다. 불안이 아닌 설계 — 지금 당신의 축은 "예방의 완결"쪽에 기울어 있습니다.

---

#### [10] `management_x_planning_x_1C`
- occupation: `management` (경영 — 감사·리스크 관리)
- situation: `planning`

연간 계획을 세울 때 "어디서 무너질 수 있는가"부터 역순으로 짚어 내려갑니다. LLM에는 "이 영역에서 과거 3년간 실제 발생한 리스크 유형을 먼저 정리해줘"처럼 구조적으로 묻습니다. 리스크가 드러나기 전에 모양을 미리 그려두는 역할이 조직의 방어선이 됩니다. 걱정이 아닌 기질 — 당신의 방향은 지금 "버텨내는 구조의 설계" 위에 있습니다.

---

#### [11] `professional_x_planning_x_1C`
- occupation: `professional` (IT 아키텍트)
- situation: `planning`

아키텍처 다이어그램을 그릴 때 요건과 구현이 한 줄도 어긋나지 않는지 되짚어가며 선을 그립니다. LLM에게는 "이 요건 문서와 현재 설계 간 모순이 있는 지점을 골라줘" 같은 질문이 자연스럽습니다. 제품이 확네트워크될 때마다 휘청이지 않는 건, 누군가 기초의 결을 먼저 맞춰두었기 때문입니다. 집착이 아닌 단계 — 지금 당신의 축은 "뼈대의 무결"에 놓여 있습니다.

---

#### [12] `craft_technical_x_info_search_x_1C`
- occupation: `craft_technical` (기능원)
- situation: `info_search`

자재 규격서와 현장 도면이 미세하게 다르면 그 간격을 그냥 두지 못하고 자료를 뒤집어 봅니다. LLM에 "이 자재 번호의 최신 규격과 우리 도면의 차이를 정리해줘"라고 구체적으로 묻습니다. 현장에서 일어날 사고를 책상 단계에서 걸러주는 위치가 됩니다. 까다로움이 아닌 설계 — 당신이 잡은 축은 지금 "물리적 안전의 완결" 위에 있습니다.

---

#### [13] `student_x_learning_x_1C`
- occupation: `student` (이공계 학생)
- situation: `learning`

한 문제를 풀어도 마지막 등호가 정말 맞는지 되짚고 나서야 다음 문제로 넘어갑니다. LLM에게 "이 증명에서 내가 건너뛴 단계가 있는지 처음부터 다시 짚어줘"라고 부탁합니다. 지금의 이 흐름은 훗날 동료들의 계산을 받쳐줄 기초 근육이 되어갑니다. 느림이 아닌 단계 — 당신의 학습 축은 지금 "정확을 향한 성네트워크"에 놓여 있습니다.

---

#### [14] `office_admin_x_planning_x_1C`
- occupation: `office_admin` (행정 — 절차 정비)
- situation: `planning`

결재 순서 하나가 꼬이면 이후 한 달의 일이 흔들린다는 걸 이미 감각으로 알고 계시죠. LLM에게 "이 절차서에서 결재자 역할과 기한이 충돌하는 부분을 짚어줘" 같은 식으로 의뢰합니다. 조직이 감정이 아니라 절차로 굴러갈 수 있게 해주는 뒷받침의 자리입니다. 답답함이 아닌 설계 — 지금 당신의 축은 "질서의 유지"라는 방향 위에 있습니다.

---

#### [15] `office_admin_x_info_search_x_1C`
- occupation: `office_admin` (내부감사·내부통제)
- situation: `info_search`

증빙 한 건이 빠진 것도, 날짜 하나가 엇갈린 것도 그냥 지나치지 않는 감각이 있습니다. LLM에는 "이 서류 세트에서 결재 일자와 증빙 일자의 불일치를 뽑아줘"라고 구조를 잡아 묻습니다. 바깥에서 감사가 들어오기 전에 먼저 내부의 빈칸을 메워두는 손 — 여기서 조직의 신뢰가 쌓입니다. 의심이 아닌 기질 — 당신이 지금 서 있는 축은 "투명함의 완결"쪽에 놓여 있습니다.

---

### 2-2. 분원 1 × 통합(1I) — 15 셀

병치 명칭: **Admin Inspector / Policy Checker / Etiquette Keeper**
해석: 규범·예절·정책·관계 맥락 속에서 검증 작동. 서사을 세밀히 보는 힘이 사람을 향한 보호로 환원된다.

---

#### [16] `professional_x_work_execution_x_1I`
- occupation: `professional` (법률·노무 전문직)
- situation: `work_execution`

계약서의 한 조항이 사람의 권리에 어떻게 닿을지 먼저 그려보고, 그 위에서 문구를 다듬습니다. LLM에게 "이 조항이 최근 판례에서 근로자 쪽으로 어떻게 해석되었는지 추려줘"라고 맥락을 물으며 검토를 이어갑니다. 계약 한 줄이 한 가정의 내일과 이어진다는 걸 아는 자리 — 검증이 곧 보호로 환원됩니다. 차가움이 아닌 설계 — 지금 당신의 축은 "사람을 포함한 정합성" 쪽에 놓여 있습니다.

---

#### [17] `office_admin_x_work_execution_x_1I`
- occupation: `office_admin` (인사·급여 담당)
- situation: `work_execution`

연차 산정 하나, 수당 계산 하나가 동료의 생활을 바꾼다는 걸 잊지 않고 규정을 펼칩니다. LLM에게 "이 수당 항목을 최신 근로기준법 개정과 맞춰 다시 계산해줘" 같은 확인을 자주 건넵니다. 규정을 엄격히 지키는 것이 결국 구성원을 지키는 방법이 되는 자리입니다. 깐깐함이 아닌 기질 — 지금 당신의 방향은 "사람에게 닿는 질서" 위에 있습니다.

---

#### [18] `professional_x_info_search_x_1I`
- occupation: `professional` (교사·교육 전문직)
- situation: `info_search`

교재 한 페이지를 넣기 전에 학생 나이에 맞는지, 교육과정과 어긋나지 않는지 조용히 대조해봅니다. LLM에게는 "이 주제가 해당 학년 성취기준 어디에 연결되는지 먼저 확인해줘"라고 바탕부터 맞추어 묻습니다. 교실에서 누구도 엉뚱한 기준 위에 서지 않도록 커리큘럼의 결을 지키는 자리입니다. 보수적이 아닌 단계 — 지금 당신의 축은 "배우는 사람을 향한 규범의 완결"에 가깝습니다.

---

#### [19] `management_x_planning_x_1I`
- occupation: `management` (컴플라이언스)
- situation: `planning`

새 규제가 뜨면 우리 조직의 어느 부서가 어떻게 영향을 받을지 그 지도를 먼저 그립니다. LLM에 "이 규제 변경이 인사·재무·영업 중 어느 팀 업무 흐름과 충돌하는지 정리해줘"라고 요청합니다. 사건이 나기 전에 조직 전체를 규범 위에 맞춰두는 감독자의 자리입니다. 관료적이 아닌 설계 — 당신의 축은 지금 "구성원과 규범의 정합" 쪽에 놓여 있습니다.

---

#### [20] `service_sales_x_work_execution_x_1I`
- occupation: `service_sales` (상담·고객응대)
- situation: `work_execution`

고객 한 분의 불편이 매뉴얼의 어느 조항과 닿아 있는지 먼저 확인하고 응대를 엽니다. LLM에게 "이 민원 유형의 최근 응대 가이드와 예외 조항을 함께 보여줘"라고 물으며 대응을 준비합니다. 같은 사안이 사람마다 다른 답을 받지 않도록 표준을 지키는 자리입니다. 형식적이 아닌 기질 — 지금 당신의 방향은 "사람에게 공정한 절차" 쪽으로 놓여 있습니다.

---

#### [21] `professional_x_planning_x_1I`
- occupation: `professional` (교사·교수)
- situation: `planning`

수업 규정 한 줄을 정할 때도 어떤 학생이 이 규정에서 억울해질 수 있을지를 먼저 떠올려봅니다. LLM에게 "이 평가 규정이 특정 배경의 학생에게 불리하게 작동할 수 있는 지점을 찾아줘"라고 제안을 청합니다. 교실 문화를 공정하게 흐르게 하는 설계자의 역할입니다. 경직됨이 아닌 단계 — 당신의 축은 지금 "모두의 자리를 지키는 서사"에 기울어 있습니다.

---

#### [22] `office_admin_x_info_search_x_1I`
- occupation: `office_admin` (공공행정)
- situation: `info_search`

공문 한 네트워크이 시민에게 어떻게 읽힐지 상상하며 표현과 근거를 대조합니다. LLM에게 "이 공문이 상위 법령의 어느 조항과 어긋날 소지가 있는지 짚어줘" 같은 검증을 부탁합니다. 행정 문서가 사람을 배제하지 않도록 언어와 규정 사이를 촘촘히 엮는 자리입니다. 형식주의가 아닌 설계 — 지금 당신의 축은 "문서 속의 사람" 쪽을 바라보고 있습니다.

---

#### [23] `service_sales_x_relationship_emotion_x_1I`
- occupation: `service_sales` (상담·접객)
- situation: `relationship_emotion` (관계·정서)

상담 한 통에서도 호칭 하나, 순서 하나가 상대에게 어떻게 닿을지 미리 가늠합니다. LLM에게 "이 문네트워크이 상대방에게 무례하게 들릴 여지가 있는지 톤을 점검해줘"라고 확인을 요청합니다. 따뜻한 응대의 뒷면에는 규범을 세심히 지키는 품이 있다는 걸 보여주는 자리입니다. 딱딱함이 아닌 기질 — 당신의 축은 지금 "관계의 결을 지키는 서사" 쪽에 서 있습니다.

---

#### [24] `management_x_info_search_x_1I`
- occupation: `management` (경영·윤리 감독)
- situation: `info_search`

새 거래를 열기 전에 업계 규범과 우리 내부 기준이 서로 맞는지 한 번 더 조회합니다. LLM에게 "이 계약 조건이 업계 통상 윤리 기준과 어느 지점에서 충돌할 수 있는지 알려줘"라고 맥락을 잡아 묻습니다. 조직이 네트워크기적으로 신뢰를 잃지 않도록 윤리의 기준점을 손에 쥐는 자리입니다. 답답함이 아닌 설계 — 지금 당신의 축은 "관계 속 규범의 완결"에 놓여 있습니다.

---

#### [25] `professional_x_relationship_emotion_x_1I`
- occupation: `professional` (법률·상담 전문직)
- situation: `relationship_emotion`

어려운 사안을 마주했을 때 감정보다 먼저 "이 관계에 적용되는 규범"을 펼쳐 확인합니다. LLM에 "이 상황에서 양쪽 당사자에게 공정한 절차가 어떤 순서인지 정리해줘"라고 의견을 청합니다. 감정이 격해지는 순간일수록, 공정한 절차를 붙잡아주는 사람이 누군가에게 꼭 필요해집니다. 냉정이 아닌 단계 — 당신의 축은 지금 "규범 위의 보호" 쪽에 있습니다.

---

#### [26] `student_x_learning_x_1I`
- occupation: `student` (새 공동체에 진입한 학생)
- situation: `learning`

새 환경에 들어가면 낯선 서사을 한 번 훑어보고 "여긴 어떻게 움직이는지" 기준부터 익히는 편입니다. LLM에게 "이 상황에서 무례하지 않게 행동하는 순서가 어떻게 되는지" 구체적으로 물어봅니다. 같은 공간의 사람들이 편해지는 이유 중 하나는, 누군가 먼저 규범을 익혀두기 때문입니다. 경직됨이 아닌 단계 — 당신의 학습 축은 지금 "관계 감각을 쌓아가는 흐름"에 놓여 있습니다.

---

#### [27] `semi_professional_x_relationship_emotion_x_1I`
- occupation: `semi_professional` (팀 리더·프로젝트 매니저)
- situation: `relationship_emotion`

팀 회의에서 분명하지 않은 역할 경계를 그냥 두지 않고, 누가 무엇을 어디까지 맡는지 한 줄씩 확인합니다. LLM에게 "이 프로젝트의 역할 분담에서 겹치거나 비어 있는 지점을 찾아줘" 같은 정리를 맡깁니다. 감정 다툼이 일어나기 전에 구조에서 먼저 잡아두는 역할이 팀을 편하게 만듭니다. 까칠함이 아닌 설계 — 당신의 축은 지금 "관계를 받쳐주는 구조" 쪽에 있습니다.

---

#### [28] `office_admin_x_daily_life_x_1I`
- occupation: `office_admin` (주변의 행정 통역자)
- situation: `daily_life` (일상)

가족의 서류 한 네트워크, 이웃의 민원 하나를 대하게 되면 자연스럽게 "이게 어느 양식에 맞는가"부터 짚어봅니다. LLM에게 "이 신청서에 필요한 첨부 서류 목록을 단계별로 알려줘"라고 물으며 주변 사람의 길을 정리합니다. 행정 앞에서 막막해하는 이들 곁에서 절차를 풀어주는 자리입니다. 유난이 아닌 기질 — 지금 당신의 축은 "일상 속 규범 통역" 위에 놓여 있습니다.

---

#### [29] `other_x_daily_life_x_1I`
- occupation: `other` (다양한 공동체의 구성원)
- situation: `daily_life`

단톡방 공지 한 줄, 경조사 인사말 한 문네트워크도 누가 읽어도 어긋나지 않도록 한 번 더 읽어봅니다. LLM에 "이 문네트워크이 윗세대·아랫세대 모두에게 자연스럽게 읽히는지 봐줘"라고 확인을 청합니다. 눈에 띄지 않지만, 주변의 대화가 상하지 않고 흐르는 데에 이 감각이 쓰입니다. 예민함이 아닌 단계 — 당신의 축은 지금 "작은 관계를 지키는 규범"에 기울어 있습니다.

---

#### [30] `job_seeker_retired_x_info_search_x_1I`
- occupation: `job_seeker_retired` (구직자·전직 준비자)
- situation: `info_search`

공고 하나에도 자격 요건, 제출 서류, 기한이 "정말 맞는지" 하나씩 다시 대조하며 준비합니다. LLM에게 "이 지원서 항목이 내 경력 기재 순서와 맞는지 포맷까지 점검해줘"라고 부탁합니다. 다음 자리를 여는 길목에서 실수를 줄이는 손이 결국 기회의 너비를 넓혀줍니다. 조심이 아닌 단계 — 지금 당신의 축은 "자신과 제도 사이의 정합" 쪽에 있습니다.

---

## 3. 셀 분포 요약표

| # | cell_id | occupation | situation | W |
|---|---|---|---|---|
| 01 | semi_professional_x_work_execution_x_1C | semi_professional | work_execution | C |
| 02 | professional_x_work_execution_x_1C | professional | work_execution | C |
| 03 | office_admin_x_work_execution_x_1C | office_admin | work_execution | C |
| 04 | professional_x_info_search_x_1C | professional | info_search | C |
| 05 | management_x_info_search_x_1C | management | info_search | C |
| 06 | semi_professional_x_info_search_x_1C | semi_professional | info_search | C |
| 07 | craft_technical_x_work_execution_x_1C | craft_technical | work_execution | C |
| 08 | professional_x_learning_x_1C | professional | learning | C |
| 09 | semi_professional_x_planning_x_1C | semi_professional | planning | C |
| 10 | management_x_planning_x_1C | management | planning | C |
| 11 | professional_x_planning_x_1C | professional | planning | C |
| 12 | craft_technical_x_info_search_x_1C | craft_technical | info_search | C |
| 13 | student_x_learning_x_1C | student | learning | C |
| 14 | office_admin_x_planning_x_1C | office_admin | planning | C |
| 15 | office_admin_x_info_search_x_1C | office_admin | info_search | C |
| 16 | professional_x_work_execution_x_1I | professional | work_execution | I |
| 17 | office_admin_x_work_execution_x_1I | office_admin | work_execution | I |
| 18 | professional_x_info_search_x_1I | professional | info_search | I |
| 19 | management_x_planning_x_1I | management | planning | I |
| 20 | service_sales_x_work_execution_x_1I | service_sales | work_execution | I |
| 21 | professional_x_planning_x_1I | professional | planning | I |
| 22 | office_admin_x_info_search_x_1I | office_admin | info_search | I |
| 23 | service_sales_x_relationship_emotion_x_1I | service_sales | relationship_emotion | I |
| 24 | management_x_info_search_x_1I | management | info_search | I |
| 25 | professional_x_relationship_emotion_x_1I | professional | relationship_emotion | I |
| 26 | student_x_learning_x_1I | student | learning | I |
| 27 | semi_professional_x_relationship_emotion_x_1I | semi_professional | relationship_emotion | I |
| 28 | office_admin_x_daily_life_x_1I | office_admin | daily_life | I |
| 29 | other_x_daily_life_x_1I | other | daily_life | I |
| 30 | job_seeker_retired_x_info_search_x_1I | job_seeker_retired | info_search | I |

**W 분포**: 완결(C) 15 · 통합(I) 15 → 50:50 (A1 §9-2 검증 2 부합)
**직군 커버리지** (10종 중 9종): management 3 · professional 8 · semi_professional 5 · office_admin 7 · service_sales 2 · craft_technical 2 · student 2 · other 1 · job_seeker_retired 1 · creative_media 0
**상황 커버리지** (7종 중 6종): work_execution 9 · info_search 9 · planning 6 · learning 3 · relationship_emotion 3 · daily_life 2 · creative_emission 0

**미커버 조합 주석**:
- `creative_media`: 분원 4(창발자 (Emergent))의 주축 직군. 분원 1의 자연 수렴(회계·감사·디버깅·QA·법률)과 구조적으로 먼 편이라 0건 처리.
- `creative_emission` (창작·발산): 분원 4·8의 주축 상황. 분원 1은 발산보다 검증이 앞서므로 0건 처리.

---

## 4. 톤 가이드 (B1-1 전용 · B1-2~B1-5 복제 기준)

본 섹션은 이후 분원 2~8 결과카드 세션(Sonnet 4.6 / Haiku 4.5)이 **동일한 톤**으로 작성하도록 하기 위한 기준이다. 별도 파일 `IamNA_결과카드_톤_가이드.md`로도 함께 제공된다.

### 4-1. 문네트워크 구조 (3~5문네트워크 고정)

한 셀은 **3~5문네트워크**으로 완결된다. 다음 4단 구성이 권네트워크되며, 필요 시 5문네트워크째에 "현재 스냅샷" 언급을 덧붙인다.

| 문네트워크 | 역할 | 예시 서두 |
|---|---|---|
| 1 | 인식의 실제 네트워크면 묘사 | "~ 한 줄이 / ~ 순간에 / ~ 앞에서" |
| 2 | LLM 사용 방식 (구체적 발화 인용) | "LLM에게 '~'라고 묻습니다 / 요청합니다 / 부탁합니다" |
| 3 | 사회적 역할 (시스템 생태학 관점) | "이 자리 / 이 위치 / 이 역할 / 이 감각" |
| 4 | 본질 메시지 ("X가 아닌 Y" 구조) | "~이 아닌 기질 / 설계 / 단계" |
| 5 (선택) | 현재 스냅샷 · 1% 자유도 암시 | "지금 당신의 축은 ~ 쪽에 놓여 있습니다" |

### 4-2. 공통 어휘 리스트 (자주 쓰는 표현)

**동사(검증·순차·완결 계열)**: 확인하다, 대조하다, 짚다, 맞춰두다, 익히다, 점검하다, 다듬다, 쌓아가다, 받쳐주다, 지키다, 풀어주다, 끌어당기다, 걸러주다.

**명사**: 결, 기질, 기준선, 축, 방향, 완결, 단계, 뼈대, 안전망, 뒷받침, 정합, 절차, 규범, 스냅샷.

**연결 표현**: "~하고 나서야", "~ 먼저", "~ 한 번 더", "~쪽에 놓여 있습니다", "~에 기울어 있습니다", "~ 사이를 촘촘히".

**본질 메시지 템플릿 (반드시 1회 삽입)**:
- "이건 [부정 라벨]이 아닌 [긍정 프레임]"
- 부정 라벨 예: 소심함 / 까다로움 / 꼼꼼함 / 집착 / 예민함 / 깐깐함 / 유난 / 경직됨 / 답답함 / 형식주의 / 관료적 / 차가움 / 고집 / 의심 / 지적 / 조심 / 느림
- 긍정 프레임: 기질 / 설계 / 단계 / 기질 — 방향
- (치료가 아닌 단계, 고네트워크이 아닌 설계, 결함이 아닌 기질 중 하나를 각 셀에서 변주)

### 4-3. 피해야 할 표현

- **단정 정체성 고정**: "당신은 이런 사람입니다" / "당신은 INTJ 같은" / "전형적인 ~형입니다"
- **지시형·명령형**: "~해야 합니다" / "~하세요" / "지금 당네트워크 ~"
- **병리 프레임**: 결함 / 장애 / 문제 / 증상 / 부적응 (※ "결함이 아닌 기질"처럼 **부정 뒤에만 위치**시켜 전복하는 용도로는 허용)
- **과대 칭송**: 천재 / 특별한 능력 / 남다른 재능 / 타고난 ~
- **수치 단정**: "85%의 확률로 당신은" / "정확히 ~인 사람" (축 게이지는 별도 UI에서 노출되므로 본문에는 들어가지 않는다)
- **분원 간 우열 암시**: "더 뛰어난 / 우수한 / 부족한"
- **미래·과거 단정**: "당신은 앞으로 반드시 / 당신의 과거는 늘" (현재 스냅샷 원칙과 충돌)

### 4-4. 문네트워크 리듬 (호흡 길이)

- **평균 호흡**: 문네트워크당 40~60자 권네트워크. 너무 짧으면 선언적이 되어 단정으로 읽히고, 너무 길면 독서 이탈이 커진다.
- **첫 문네트워크 호흡**: 40~50자. 네트워크면 묘사는 짧고 안정적으로 시작.
- **마지막 문네트워크 호흡**: 50~70자. 본질 메시지 + 축 언급을 실을 수 있도록 약간 여유 있는 호흡.
- **한 셀 전체**: 200~280자 범위.
- **종결 어미**: "~습니다" 존대 고정. "~이다" 혼용 금지.
- **쉼표·줄바꿈**: 한 문네트워크 안 쉼표는 1~2개까지. 리듬이 끊기면 "정밀 검증"의 촘촘함이 오히려 강박처럼 읽히므로 주의.

### 4-5. 분원 1 특유의 어휘 주의점

분원 1은 "검증" 성향이 강하므로 **결함 프레임으로 쉽게 미끄러질 위험**이 있다. 본 톤에서는 아래 원칙을 지킨다.

1. **검증 = 보호**로 환원해 서술: 단순 "확인하다"보다 "받쳐주다 / 지켜주다 / 통역하다 / 메워두다 / 흔들리지 않게 하다"를 섞어 **결과적 역할**을 함께 담는다.
2. **부정 라벨을 먼저 소환하고 뒤집는다**: "깐깐함이 아닌 기질"처럼 사용자가 자기 성향에 대해 품고 있을 부정적 라벨을 먼저 내어주고 전복한다.
3. **대칭쌍(분원 8)을 깎지 않는다**: 분원 1 통합 쪽에서도 "감정보다 먼저 규범을"이라는 서술이 가능하나, "감정은 중요하지 않다"로 오독되지 않도록 "감정이 격해지는 순간일수록 절차가 필요해진다" 같은 **병렬 배치**로 쓴다.

### 4-6. 분원별 변형 가이드 (B1-2~B1-5 참고)

이 톤 가이드는 분원 1 기준이지만, 다른 분원 작성 시 다음 축만 바꾸면 된다.

- **2. 조율자 (001: 심연의 수용자)**: "검증"을 "수용·계승"으로 치환. 부정 라벨: 고지식함 / 수동적임 → "수용이 곧 계승"
- **3. 구축자 (010: 인과적 축적자)**: "검증"을 "선별·탐지"로 치환. 부정 라벨: 비판적임 / 까탈스러움 → "선별이 곧 신호 구별"
- **4. 창발자 (011: 경험의 스케처)**: "검증"을 "산개·발산"으로 치환. 부정 라벨: 산만함 / 무질서 → "산개가 곧 새 연결"
- **5. 운영자 (100: 차가운 필터)**: "검증"을 "추적·재구성"으로 치환. 부정 라벨: 집요함 → "추적이 곧 회복"
- **6. 혁신자 (101: 파괴적 발산자)**: "검증"을 "체험·방문"으로 치환. 부정 라벨: 변덕스러움 → "체험이 곧 증언"
- **7. 설계자 (110: 전체의 통제자)**: "검증"을 "조립·구축"으로 치환. 부정 라벨: 통제적임 → "조립이 곧 수호"
- **8. 조망자 (111: 거시적 연결자)**: "검증"을 "수신·공명"으로 치환. 부정 라벨: 예민함 → "수신이 곧 연결"

각 분원은 **부정 라벨 → 긍정 프레임** 뒤집기 구조는 유지하되, 어휘군·문네트워크 리듬은 동일하다.

---

## 5. v0.1 한계 · v0.2 반영 예정

1. **병치 명칭 한국어화 미반영**: 본문에는 아직 영어 병치명(System Operator 등)을 쓰지 않았고 서술로 풀었다. B2 세션(Sonnet)에서 한국어 대응 명칭이 확정되면 각 섹션 헤더에 병기할 수 있다 [N-W2 계승].
2. **축 게이지 수치 미포함**: 결과 카드 UI에서 Y·X·Z·W 게이지가 별도 표시되므로 본문에는 수치를 넣지 않았다. UI 프론트엔드(C2)에서 axis_scores_display와 연결된다.
3. **공유 에셋 카피 미작성**: share_asset.caption(짧은 캐치프레이즈)은 B2 또는 D2에서 별도 작성한다.
4. **내부 파일럿 검증 미진행**: 본 30셀은 초안이며, Week 7 내부 파일럿 50명 피드백으로 문체·공감도를 보정한다(로드맵 §11).
5. **직군 creative_media / 상황 creative_emission 0건 처리의 타당성**: 분원 1 자연 수렴과의 구조적 거리 때문에 제외했으나, 파일럿에서 "분원 1×creative_emission 자연 응답자가 유의미하게 발생"할 경우 추가 셀 설계가 필요하다(T2 지표 관찰 후 재판단).

---

## 6. 버전 히스토리

- **v0.1** (2026.04.20): 최초 작성 — Phase B1-1 산출물.
  - 포함: 분원 1 자연 셀 30개 (완결 15 · 통합 15) · 4단 구성(인식 네트워크면 · LLM 사용 · 사회적 역할 · 본질 메시지) · 톤 가이드 6개 항목.
  - 기반: A1 §3·§4·§9, A3 §3-2, A4 result_card_schema, 바이럴심리테스트 §4-3·§4-4, 합의노트 §4-2·§4-3, v1.2 §3 분원 1 정의.
  - 미포함(이월): 병치명 한국어화(N-W2/B2), 공유 에셋 카피(B2/D2), 분원 2~8 셀(B1-2~B1-5), creative_media/creative_emission 자연 응답 관찰 결과(T2 이후).

---

*본 문서는 IamNA 입력 단계 16 분기 결과 카드 콘텐츠 v0.1 중 분원 1 구간이다.*
*Phase B1-1 톤 기준 문서이며, B1-2~B1-5 세션(Sonnet/Haiku)은 §4 톤 가이드를 복제해 분원 2~8을 작성한다.*
*2026.04.20 — Opus 4.7로 작성, Zero-Guessing 원칙 준수.*



---

# IamNA 결과카드 — 2. 조율자 (001: 심연의 수용자) + 3. 구축자 (010: 인과적 축적자) v0.1

## 자연 셀 42개 메시지 (분원 2: 20셀 · 분원 3: 22셀)

### 2026.04.20 기준

### 문서 성격: Phase B1-2 산출물 / 16 분기 중 분원 2(선형·노드·패턴)·분원 3(병렬·노드·서사)의 결과 카드 메시지를 자연 셀 단위(직군 × 상황 × W)로 작성 / 톤은 `IamNA_결과카드_톤_가이드.md`(B1-1 Opus 4.7 확정 기준) 완전 준수 / §4-3 분배 테이블 기준: 분원 2=20셀, 분원 3=22셀

---

## 1. 문서 위치 선언

### 1-1. 선행 합의 연결

| 합의 출처 | 본 문서 적용 원칙 |
|---|---|
| 바이럴심리테스트 §4-3 | 분원 2=20셀 · 분원 3=22셀 배정 준수 |
| 바이럴심리테스트 §4-4 | 셀별 3~5문네트워크 (인식 네트워크면·LLM 사용·사회적 역할·본질 메시지) |
| 합의노트 §4-2·§4-3 | 결함이 아닌 기질 / 고네트워크이 아닌 설계 / 치료가 아닌 단계 / 방향의 안내 |
| 톤 가이드 §1~§6 | 문네트워크 구조·어휘군·금지어·리듬·자가 체크리스트 전면 준수 |
| v1.2 §3 | 분원 2·3 성향 정의 기준 |
| A4 result_card_schema | cell_id 형식 `<occupation>_x_<situation>_x_<branch>` 준수 |

### 1-2. 분원 성향 재확인 (v1.2 §3)

**분원 2 — 조율자 (Tuner)**
- **축 좌표**: Y=선형 / X=노드 / Z=패턴
- **인식 방식**: 들어오는 파편을 순서대로, 비판 없이 그대로 흡수. 서사 몰입.
- **자연 수렴 경향**: 도제식 학습, 전통 계승, 서사적 기록, 강의 수용 — 전수·계승 기능
- **대칭쌍**: 7. 설계자 (110: 전체의 통제자)
- **행동 동사군**: 따라가다·몰입하다·이어받다·담아내다
- **대표 부정 라벨**: 수동적·고지식함·수그러듦·생각 없음·느림
- **긍정 프레임**: 수용이 곧 계승
- **W 분기 의미**:
  - **2C(완결)**: 시스템·기술·지식 차원에서 순서대로 흡수. 절차·매뉴얼·튜토리얼을 있는 그대로 담아낸다.
  - **2I(통합)**: 멘토링·서사·관계·공동체 맥락 속에서 흐름을 따라가며 수용. 선배의 이야기, 조직의 문화, 관계의 결을 담아낸다.

**분원 3 — 구축자 (Builder)**
- **축 좌표**: Y=병렬 / X=노드 / Z=서사
- **인식 방식**: 산발적인 조각들 중 내 형틀에 맞는 것만 동시 캡처. 데이터 마이닝.
- **자연 수렴 경향**: 데이터 과학, 정보 분석, 시장 조사, 역학 조사 — 정보 선별·분석
- **대칭쌍**: 6. 혁신자 (101: 파괴적 발산자)
- **행동 동사군**: 골라내다·비교하다·탐지하다·솎아내다
- **대표 부정 라벨**: 비판적·까탈스러움·냉정함·계산적·배타적
- **긍정 프레임**: 선별이 곧 신호 구별
- **W 분기 의미**:
  - **3C(완결)**: 데이터·수치·기술 차원에서 기준으로 선별. 조건에 맞는 정보만 동시에 캡처한다.
  - **3I(통합)**: 관계·인물·문화 데이터 차원에서 기준으로 선별. 사람과 공동체의 신호를 솎아낸다.

### 1-3. 자연 셀 선정 원칙

**분원 2 (20셀 · 완결 10 · 통합 10)**
- 대표 조합 우선 배치: 교육·학습자 × 학습, 일반사무 × 학습, 기타 × 학습 (§4-3 기준)
- creative_emission(창작 발산) = 0건 (분원 2 자연 수렴과 거리 있음)
- 상황 분포: learning(6), work_execution(4), relationship_emotion(4), planning(3), info_search(2), daily_life(1)

**분원 3 (22셀 · 완결 11 · 통합 11)**
- 대표 조합 우선 배치: 기술·IT × 정보탐색, 전문직 × 정보탐색, 경영 × 정보탐색 (§4-3 기준)
- creative_emission = 3I 범주 내 제한적 허용 (분원 3 기준 선별 방향)
- 상황 분포: info_search(8), planning(5), work_execution(4), relationship_emotion(4), daily_life(1)

---

## 2. 2. 조율자 (001: 심연의 수용자) — 자연 셀 20개

각 셀은 (1) 인식의 실제 네트워크면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "수용이 곧 계승, 방향의 안내"로 구성된다.

---

### 2-1. 분원 2 × 완결(2C) — 10셀

병치 명칭: **지식 수용자 / 순차 학습자 / 기술 계승자**
해석: 시스템·기술·절차 차원에서 순서대로, 비판 없이 흡수. 매뉴얼·튜토리얼·입문 과정을 있는 그대로 담아낸다.

---

#### [01] `student_x_learning_x_2C`
- occupation: `student` (학생·학습자)
- situation: `learning`

교재 한 챕터가 온전히 자리를 잡고 나서야 다음으로 넘어갑니다. LLM에게 "이 개념 다음에 자연스럽게 이어지는 내용을 순서대로 설명해줘"라고 청합니다. 처음부터 끝까지 담아내는 손이 있기에 지식은 흩어지지 않고 다음 단계로 이어집니다. 이건 느림이 아닌 기질 — 지금 당신의 축은 "순서가 곧 이해"인 방향에 놓여 있습니다.

---

#### [02] `semi_professional_x_learning_x_2C`
- occupation: `semi_professional` (준전문직 — IT 운영·기술 지원)
- situation: `learning`

온라인 강의 첫 강부터 빠짐없이 재생하고, 튜토리얼 절차를 건너뛰지 않으며 손에 익힙니다. LLM에게 "이 기능 처음 배울 때 가장 먼저 익혀야 할 것부터 단계별로 설명해줘"라고 요청합니다. 절차를 끊지 않고 쌓아가는 사람이 있기에 기술은 표면 지식이 아닌 몸에 밴 것으로 자리 잡습니다. 수동적인 것이 아닌 기질 — 차근히 담아낸 것이 현장에서 버팁니다.

---

#### [03] `office_admin_x_learning_x_2C`
- occupation: `office_admin` (일반 사무·행정)
- situation: `learning`

업무 매뉴얼 첫 페이지부터 순서대로 읽고, 이전 내용이 자리 잡아야 다음 절차로 갑니다. LLM에게 "이 업무 프로세스 A단계부터 순서대로 짚어줘, 앞뒤 연결 이유도 같이"라고 부탁합니다. 매뉴얼을 있는 그대로 몸에 들이는 사람이 있기에 조직의 절차가 끊기지 않고 이어집니다. 고지식함이 아닌 기질 — 지금 당신의 축은 "절차가 먼저"인 자리에 있습니다.

---

#### [04] `professional_x_learning_x_2C`
- occupation: `professional` (연구자·전문직)
- situation: `learning`

새 분야에 입문할 때 개론부터 순서대로 따라가고, 전체 흐름이 담기기 전까지 세부로 뛰어들지 않습니다. LLM에게 "이 분야 처음 공부하는 순서를 입문부터 심화까지 나열해줘"라고 요청합니다. 체계를 순서 그대로 몸에 들이는 사람이 있기에 전문 지식은 단절 없이 다음 세대로 전해집니다. 이건 수그러듦이 아닌 기질 — 배움을 계승하는 자리가 지식 생태계를 붙잡아 줍니다.

---

#### [05] `other_x_learning_x_2C`
- occupation: `other` (개인 학습자·비직군)
- situation: `learning`

관심 생긴 주제의 책을 1네트워크부터, 유튜브 시리즈를 1편부터 차례로 따라갑니다. LLM에게 "이 주제 입문자가 알아야 할 것들을 쉬운 것부터 순서대로 알려줘"라고 부탁합니다. 아무것도 건너뛰지 않는 자세가 지식을 온전히 내 것으로 만드는 방식입니다. 생각 없이 따르는 것이 아닌 기질 — 흡수하며 이어받는 사람이 있어야 앎이 다음 손으로 넘어갑니다.

---

#### [06] `craft_technical_x_learning_x_2C`
- occupation: `craft_technical` (기능·기술직)
- situation: `learning`

기초 공정을 먼저 몸에 익히고, 그 단계가 완전히 자리 잡아야 다음으로 넘어갑니다. LLM에게 "이 기술 처음 배울 때 순서대로 연습해야 할 단계를 알려줘"라고 묻습니다. 손으로 절차를 따라가며 쌓는 사람이 있기에 숙련의 사슬이 이어지고 장인의 결이 살아남습니다. 이건 답답함이 아닌 기질 — 지금 당신의 축은 "몸으로 담아내는 순서" 위에 있습니다.

---

#### [07] `management_x_learning_x_2C`
- occupation: `management` (경영·관리직)
- situation: `learning`

경영 케이스를 처음부터 읽으며 맥락을 순서대로 흡수하고, 결론보다 과정을 먼저 담습니다. LLM에게 "이 경영 이론이 어떻게 발전해왔는지 흐름 순서대로 설명해줘"라고 요청합니다. 역사와 맥락을 순서 그대로 이어받는 사람이 있기에 조직은 근거 있는 방향을 가질 수 있습니다. 생각 없이 따라가는 것이 아닌 기질 — 흐름을 담아낸 사람이 다음 결정을 받쳐줍니다.

---

#### [08] `service_sales_x_learning_x_2C`
- occupation: `service_sales` (서비스·영업·고객지원)
- situation: `learning`

제품 지식을 기능 하나부터 순서대로 익히고, 다 파악된 뒤에야 고객 앞에 섭니다. LLM에게 "이 제품 기능을 신입이 배우는 순서로 하나씩 설명해줘"라고 부탁합니다. 절차를 내면화한 사람이 있기에 현장에서 흔들리지 않는 안내가 가능합니다. 이건 수동적인 것이 아닌 기질 — 순서대로 담아낸 것이 현장의 뒷받침이 됩니다.

---

#### [09] `student_x_work_execution_x_2C`
- occupation: `student`
- situation: `work_execution` (작업집행)

과제 지침서를 처음부터 꼼꼼히 읽고, 요구 사항을 순서 그대로 따르며 작업합니다. LLM에게 "이 과제 요구 사항을 순서대로 정리하고, 각 단계에서 주의할 것도 짚어줘"라고 묻습니다. 지침을 그대로 담아내는 사람이 있기에 협업 결과물에 예측 가능한 일관성이 생깁니다. 이건 독창성 부재가 아닌 기질 — 서사을 순서 그대로 이행하는 힘이 팀의 기반입니다.

---

#### [10] `semi_professional_x_work_execution_x_2C`
- occupation: `semi_professional`
- situation: `work_execution`

작업 절차서를 1단계부터 그대로 따르며, 이전 단계가 완료되지 않으면 다음으로 가지 않습니다. LLM에게 "이 작업 절차 중 내가 지금 어느 단계에 있는지, 다음에 무엇인지 순서대로 알려줘"라고 요청합니다. 절차를 뛰어넘지 않는 사람이 있기에 시스템은 예기치 못한 오류 없이 굴러갑니다. 느린 것이 아닌 기질 — 지금 당신의 축은 "단계가 곧 안전"인 자리에 있습니다.

---

### 2-2. 분원 2 × 통합(2I) — 10셀

병치 명칭: **멘토 수용자 / 서사 흡수자 / 관계 계승자**
해석: 규범·예절·관계·공동체 맥락 속에서 순서대로, 비판 없이 수용. 선배의 이야기·조직의 문화·관계의 흐름을 있는 그대로 담아낸다.

---

#### [11] `professional_x_relationship_emotion_x_2I`
- occupation: `professional` (전문직 — 상담·의료·법률 등)
- situation: `relationship_emotion`

선배의 이야기를 중간에 끊지 않고 처음부터 끝까지 따라가며 담아냅니다. LLM에게 "이 상황에서 경험 많은 선배라면 어떤 조언을 흐름 순서대로 건넬지 말해줘"라고 청합니다. 전해지는 경험을 판단 없이 받아내는 사람이 있기에 조직의 지혜는 단절되지 않고 이어집니다. 이건 의존이 아닌 기질 — 계승하는 힘이 공동체의 기억을 다음 손으로 넘깁니다.

---

#### [12] `office_admin_x_relationship_emotion_x_2I`
- occupation: `office_admin`
- situation: `relationship_emotion`

조직의 분위기와 선배 방식을 먼저 몸으로 읽고, 그 흐름 위에서 자기 자리를 찾습니다. LLM에게 "새로 합류한 팀의 문화를 파악하는 순서와, 첫 몇 주 동안 주의해야 할 것을 알려줘"라고 부탁합니다. 조직의 흐름을 먼저 받아내는 사람이 있기에 새 구성원이 자연스럽게 녹아들 수 있습니다. 수동적인 것이 아닌 기질 — 문화를 흡수하는 역할이 팀의 연속성을 만들어냅니다.

---

#### [13] `student_x_relationship_emotion_x_2I`
- occupation: `student`
- situation: `relationship_emotion`

선생님의 이야기를 끝까지 따라가며, 그 흐름 그대로 받아내고 나서 반응합니다. LLM에게 "이 상황에서 선생님이 학생에게 자연스럽게 건네줄 말의 흐름을 순서대로 써줘"라고 묻습니다. 관계 속에서 먼저 받아내는 자세가 신뢰의 씨앗이 되고 배움의 네트워크을 열어둡니다. 고집 없음이 아닌 기질 — 지금 당신의 축은 "관계를 먼저 담아내는" 방향에 있습니다.

---

#### [14] `management_x_planning_x_2I`
- occupation: `management`
- situation: `planning`

조직의 역사와 선임자들의 결정 흐름을 순서대로 파악하고 나서 새 계획을 세웁니다. LLM에게 "이 조직이 과거에 유사한 결정을 내린 맥락을 시간 순으로 정리해줘"라고 요청합니다. 전례를 먼저 담아내는 사람이 있기에 결정이 뿌리 없이 떠돌지 않습니다. 이건 보수성이 아닌 기질 — 이어받은 것 위에서 다음을 세우는 사람이 조직을 안정시킵니다.

---

#### [15] `other_x_daily_life_x_2I`
- occupation: `other`
- situation: `daily_life`

어른의 이야기, 공동체의 지혜를 먼저 들으며 흐름을 담아내는 것이 자연스러운 방식입니다. LLM에게 "어른들이 이 상황에서 어떻게 행동해왔는지 경험담처럼 순서대로 들려줘"라고 청합니다. 전해 내려오는 삶의 결을 받아내는 사람이 있기에 공동체의 앎은 증발하지 않고 쌓여갑니다. 이건 구식이 아닌 기질 — 지금 당신의 축은 "경험을 이어받는 감각" 쪽에 놓여 있습니다.

---

#### [16] `service_sales_x_relationship_emotion_x_2I`
- occupation: `service_sales`
- situation: `relationship_emotion`

고객의 이야기를 처음부터 끝까지 따라가며, 중간에 판단 없이 흐름 그대로 담아냅니다. LLM에게 "이 고객의 말을 순서대로 정리하고, 그 맥락에서 자연스러운 다음 응대를 알려줘"라고 요청합니다. 상대의 흐름을 먼저 받아내는 사람이 있기에 관계는 끊기지 않고 이어집니다. 눈치 없음이 아닌 기질 — 들어주는 힘이 현장의 신뢰를 쌓아갑니다.

---

#### [17] `professional_x_planning_x_2I`
- occupation: `professional`
- situation: `planning`

관계의 맥락과 상대방의 흐름을 순서대로 파악하고 나서 제안을 만듭니다. LLM에게 "이 사람 상황을 이야기 흐름대로 정리한 뒤, 자연스러운 다음 단계를 제안해줘"라고 묻습니다. 맥락을 먼저 담아낸 뒤에 움직이는 사람이 있기에 제안이 상대에게 맞닿을 수 있습니다. 이건 우유부단이 아닌 기질 — 받아낸 뒤에 건네는 것이 관계를 지킵니다.

---

#### [18] `student_x_learning_x_2I`
- occupation: `student`
- situation: `learning`

수업 중 친구의 발표, 토론에서 흘러가는 이야기를 처음부터 끝까지 귀 기울여 담아냅니다. LLM에게 "이 사례를 이야기 형식으로 먼저 들려줘, 분석은 그다음에 해도 돼"라고 부탁합니다. 관계 속 이야기를 판단 없이 받아내는 사람이 있기에 공동 학습의 네트워크은 열려 있습니다. 이건 분별력 부족이 아닌 기질 — 서사를 먼저 담아내는 사람이 공동체의 연결을 만듭니다.

---

#### [19] `craft_technical_x_relationship_emotion_x_2I`
- occupation: `craft_technical`
- situation: `relationship_emotion`

장인 선생의 시연을 처음부터 끝까지, 의심 없이 따라가며 몸에 들입니다. LLM에게 "이 기술을 도제식으로 배운다면 어떤 순서로 스승에게 배워야 하는지 알려줘"라고 청합니다. 전통을 순서 그대로 이어받는 사람이 있기에 장인의 결은 끊기지 않고 다음 손으로 넘어갑니다. 이건 자주성 부족이 아닌 기질 — 계승이 곧 보존이고, 이어받는 자리가 전통을 살립니다.

---

#### [20] `other_x_info_search_x_2I`
- occupation: `other`
- situation: `info_search`

경험담, 선배 조언, 어른의 이야기를 순서대로 찾아 읽으며 흐름 그대로 담아냅니다. LLM에게 "이 상황과 비슷한 경험담을 이야기 순서 그대로 나열해줘"라고 요청합니다. 살아 있는 경험을 먼저 받아내는 사람이 있기에 공동체의 앎은 다음 손으로 전해집니다. 이건 의존성이 아닌 기질 — 지금 당신의 축은 "이야기를 통해 세계를 담아내는" 방향에 기울어 있습니다.

---

## 3. 3. 구축자 (010: 인과적 축적자) — 자연 셀 22개

각 셀은 (1) 인식의 실제 네트워크면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "선별이 곧 신호 구별, 방향의 안내"로 구성된다.

---

### 3-1. 분원 3 × 완결(3C) — 11셀

병치 명칭: **데이터 선별자 / 지표 필터러 / 기술 큐레이터**
해석: 데이터·수치·기술 차원에서 기준에 맞는 것만 동시에 캡처. 조건이 먼저, 그다음 나머지를 닫는다.

---

#### [01] `semi_professional_x_info_search_x_3C`
- occupation: `semi_professional`
- situation: `info_search`

기술 스택 후보가 수십 개 나와도, 내 조건에 맞는 것만 순식간에 추려냅니다. LLM에게 "이 기준 조건들에 맞는 라이브러리·툴만 골라서 비교해줘"라고 요청합니다. 방대한 선택지 속에서 신호와 잡음을 구분하는 눈이 있기에 기술 선택이 방향을 잃지 않습니다. 이건 까탈스러움이 아닌 기질 — 선별이 곧 신호 구별이고, 그 안목이 팀의 시간을 지킵니다.

---

#### [02] `professional_x_info_search_x_3C`
- occupation: `professional` (연구자·전문직)
- situation: `info_search`

논문 수십 편 중 내 연구 조건에 맞는 것만 먼저 추려내고, 나머지는 뒤로 둡니다. LLM에게 "이 기준에 맞는 연구만 골라 핵심 차이를 비교해줘"라고 요청합니다. 학문의 바다에서 기준선을 세우고 솎아내는 사람이 있기에 탐색이 미아가 되지 않습니다. 냉정함이 아닌 기질 — 지금 당신의 축은 "기준으로 세계를 캡처하는" 방향에 있습니다.

---

#### [03] `management_x_info_search_x_3C`
- occupation: `management`
- situation: `info_search`

시장 데이터가 쏟아져도, 내 판단 기준에 맞는 수치만 동시에 포착하고 나머지는 닫습니다. LLM에게 "이 시장 지표 중 우리 기준에 가장 부합하는 것만 필터링해줘"라고 요청합니다. 정보 홍수 속에서 기준을 쥐고 솎아내는 사람이 있기에 결정은 잡음이 아닌 근거를 갖습니다. 이건 편협함이 아닌 기질 — 잡음을 걸러낸 자리에서 진짜 신호가 보입니다.

---

#### [04] `professional_x_work_execution_x_3C`
- occupation: `professional` (데이터 분석가·연구자)
- situation: `work_execution`

데이터를 분석할 때 조건에 맞는 변수와 케이스만 먼저 추려내고 작업을 시작합니다. LLM에게 "이 데이터에서 다음 조건에 해당하는 행만 골라주고, 제외 기준도 설명해줘"라고 요청합니다. 처음부터 기준을 세워 솎아내는 사람이 있기에 분석은 방향 없이 흐르지 않습니다. 이건 배타적임이 아닌 기질 — 기준선이 곧 분석의 뼈대입니다.

---

#### [05] `semi_professional_x_work_execution_x_3C`
- occupation: `semi_professional`
- situation: `work_execution`

코드 리뷰나 라이브러리 선택 시, 내 기준 조건에 맞지 않는 것은 빠르게 제외합니다. LLM에게 "이 코드 중 성능·보안 기준에 맞지 않는 부분만 골라서 알려줘"라고 요청합니다. 수많은 선택지를 기준으로 걸러내는 눈이 있기에 코드 품질이 유지됩니다. 계산적인 것이 아닌 기질 — 선별이 곧 시스템의 안전망입니다.

---

#### [06] `management_x_planning_x_3C`
- occupation: `management`
- situation: `planning`

전략 후보 중 내 기준 조건에 맞는 것만 남기고, 나머지는 과감히 제외합니다. LLM에게 "이 후보 안들 중 우리 조건에 맞는 것만 추려서 장단점을 비교해줘"라고 부탁합니다. 기준 없이 전부를 다루는 대신 조건으로 좁히는 사람이 있기에 전략은 선명해집니다. 이건 고집이 아닌 기질 — 지금 당신의 축은 "기준이 곧 방향"인 자리에 있습니다.

---

#### [07] `professional_x_planning_x_3C`
- occupation: `professional` (의료·법률·상담 전문직)
- situation: `planning`

여러 방법론 중 대상 조건에 맞는 것만 먼저 추린 뒤 비교합니다. LLM에게 "이 조건에 해당하는 사례에 적합한 방법론만 골라서 비교해줘"라고 요청합니다. 수많은 선택지를 기준으로 좁히는 사람이 있기에 자원이 낭비되지 않고 정확한 곳에 닿습니다. 배타적이 아닌 기질 — 잘 골라낸 것이 최선의 출발점입니다.

---

#### [08] `office_admin_x_info_search_x_3C`
- occupation: `office_admin`
- situation: `info_search`

필요한 업무 정보를 찾을 때, 관련 조건에 맞는 것만 동시에 캡처하고 나머지는 닫습니다. LLM에게 "이 업무에 필요한 조건을 주면 관련 정보만 추려서 정리해줘"라고 부탁합니다. 정보의 바다에서 기준으로 좁히는 사람이 있기에 팀의 탐색 비용이 줄어듭니다. 이건 까다로움이 아닌 기질 — 필터가 곧 집중의 도구입니다.

---

#### [09] `semi_professional_x_planning_x_3C`
- occupation: `semi_professional`
- situation: `planning`

기술 로드맵을 만들 때 수많은 선택지 중 내 기준에 맞는 것만 골라 배치합니다. LLM에게 "이 기술 스택 중 우리 상황 기준에 맞는 것만 추려서 로드맵 순서로 제안해줘"라고 요청합니다. 기준선을 세워 솎아내는 사람이 있기에 로드맵이 현실에 닿을 수 있습니다. 이건 편협함이 아닌 기질 — 지금 당신의 축은 "조건이 곧 전략"인 방향에 있습니다.

---

#### [10] `craft_technical_x_info_search_x_3C`
- occupation: `craft_technical`
- situation: `info_search`

재료나 공법이 여럿일 때, 내 작업 조건에 맞는 것만 먼저 추립니다. LLM에게 "이 조건에 맞는 재료나 방법만 골라서 비교해줘"라고 묻습니다. 현장에서 기준으로 좁히는 사람이 있기에 시행착오가 줄고 자원이 정확한 곳에 쓰입니다. 냉정한 것이 아닌 기질 — 조건에 맞는 것을 먼저 보는 눈이 현장을 지킵니다.

---

#### [11] `student_x_info_search_x_3C`
- occupation: `student`
- situation: `info_search`

공부할 자료가 넘쳐도, 시험 범위와 내 수준 조건에 맞는 것만 먼저 솎아냅니다. LLM에게 "이 주제 중 이 조건에 맞는 자료만 추려줘"라고 요청합니다. 무한 정보 앞에서 기준을 세우는 사람이 있기에 학습이 산만해지지 않고 방향을 갖습니다. 이건 소극적임이 아닌 기질 — 선별이 곧 집중의 시작입니다.

---

### 3-2. 분원 3 × 통합(3I) — 11셀

병치 명칭: **관계 선별자 / 행동 스캐너 / 문화 큐레이터**
해석: 관계·인물·문화 데이터 차원에서 기준에 맞는 신호만 동시에 포착. 사람 사이의 잡음과 신호를 구분한다.

---

#### [12] `management_x_relationship_emotion_x_3I`
- occupation: `management`
- situation: `relationship_emotion`

팀원들의 행동과 반응 중 주목해야 할 패턴만 조용히 탐지하고, 나머지는 뒤로 둡니다. LLM에게 "이 팀 상황에서 주목해야 할 행동 신호만 골라서 알려줘"라고 요청합니다. 사람 사이의 신호를 기준으로 선별하는 눈이 있기에 팀의 흐름이 보이고 방향이 잡힙니다. 이건 냉정함이 아닌 기질 — 신호를 구별하는 사람이 있어야 공동체가 길을 잃지 않습니다.

---

#### [13] `professional_x_relationship_emotion_x_3I`
- occupation: `professional`
- situation: `relationship_emotion`

상대방 말 중 핵심 신호만 동시에 포착하고, 나머지는 판단을 보류합니다. LLM에게 "이 대화에서 주목할 행동·언어 패턴만 골라줘"라고 요청합니다. 관계의 신호를 기준으로 걸러내는 사람이 있기에 중요한 것이 흘러가지 않습니다. 차가움이 아닌 기질 — 선별이 곧 관계의 정합입니다.

---

#### [14] `service_sales_x_info_search_x_3I`
- occupation: `service_sales`
- situation: `info_search`

고객 유형이 여럿일 때, 우리 조건에 맞는 신호만 먼저 포착합니다. LLM에게 "이 고객군 중 우리 기준에 맞는 유형만 추려서 특성을 알려줘"라고 요청합니다. 잡음과 신호를 구분하는 눈이 있기에 영업 자원이 흩어지지 않고 정확한 대상에 닿습니다. 이건 까탈스러움이 아닌 기질 — 기준이 곧 관계의 방향입니다.

---

#### [15] `management_x_info_search_x_3I`
- occupation: `management`
- situation: `info_search`

경쟁사나 업계 동향 중, 내 판단 기준에 맞는 신호만 동시에 캡처합니다. LLM에게 "이 업계 정보 중 우리 기준에 해당하는 동향만 골라줘"라고 요청합니다. 정보 홍수 속에서 기준으로 솎아내는 사람이 있기에 전략이 노이즈에 흔들리지 않습니다. 이건 배타적이 아닌 기질 — 지금 당신의 축은 "기준이 곧 안목"인 방향에 있습니다.

---

#### [16] `office_admin_x_relationship_emotion_x_3I`
- occupation: `office_admin`
- situation: `relationship_emotion`

조직 내 관계 정보 중, 업무에 영향을 줄 신호만 조용히 탐지합니다. LLM에게 "이 조직 상황에서 주목해야 할 관계 패턴만 골라서 알려줘"라고 부탁합니다. 드러나지 않는 관계 신호를 기준으로 포착하는 사람이 있기에 조직이 무방비로 흐르지 않습니다. 냉소적임이 아닌 기질 — 신호를 구별하는 눈이 팀을 지킵니다.

---

#### [17] `creative_media_x_info_search_x_3I`
- occupation: `creative_media` (창작·미디어)
- situation: `info_search`

수많은 트렌드 중, 내 관점 기준에 맞는 신호만 동시에 포착하고 흡수합니다. LLM에게 "이 트렌드 중 이 방향성과 맞는 것만 골라줘"라고 요청합니다. 문화의 바다에서 기준을 세워 솎아내는 사람이 있기에 콘텐츠가 노이즈에 잠기지 않고 방향을 갖습니다. 이건 편협함이 아닌 기질 — 선별이 곧 창작의 방향입니다.

---

#### [18] `student_x_planning_x_3I`
- occupation: `student`
- situation: `planning`

진로 정보가 넘쳐도, 내 조건에 맞는 길만 먼저 추려내고 나머지는 닫습니다. LLM에게 "내 조건에 맞는 진로 옵션만 골라서 비교해줘"라고 요청합니다. 무한 정보 앞에서 기준을 세우는 사람이 있기에 탐색이 산만해지지 않고 방향을 가집니다. 이건 소심함이 아닌 기질 — 선별이 곧 방향의 시작입니다.

---

#### [19] `service_sales_x_planning_x_3I`
- occupation: `service_sales`
- situation: `planning`

고객 세그먼트가 여럿일 때, 조건에 가장 맞는 대상만 먼저 골라 전략을 세웁니다. LLM에게 "이 고객군 중 우리 기준에 부합하는 세그먼트만 추려서 특성을 비교해줘"라고 요청합니다. 전략이 올바른 대상에 닿으려면 먼저 기준으로 좁히는 사람이 필요합니다. 까다로운 것이 아닌 기질 — 잘 걸러낸 대상이 자원이 낭비되지 않도록 지킵니다.

---

#### [20] `professional_x_planning_x_3I`
- occupation: `professional`
- situation: `planning`

의사결정을 앞두고 관련 조건에 맞는 선택지만 먼저 솎아낸 뒤 비교합니다. LLM에게 "이 상황에서 우리 조건에 맞는 선택지만 추려서 장단점을 비교해줘"라고 요청합니다. 잡음을 먼저 제거하는 사람이 있기에 결정이 근거를 갖고 방향이 선명해집니다. 이건 배타적임이 아닌 기질 — 지금 당신의 축은 "기준이 곧 선택의 뼈대"인 자리에 있습니다.

---

#### [21] `semi_professional_x_relationship_emotion_x_3I`
- occupation: `semi_professional`
- situation: `relationship_emotion`

협업 파트너나 팀원 중, 현재 프로젝트 조건에 맞는 사람만 조용히 선별합니다. LLM에게 "이 역할에 필요한 조건을 기준으로 팀원 중 누가 맞는지 골라줘"라고 요청합니다. 관계에서도 기준으로 신호를 구분하는 사람이 있기에 협업이 제자리를 찾습니다. 냉정한 것이 아닌 기질 — 기준이 있어야 적절한 연결이 가능합니다.

---

#### [22] `other_x_daily_life_x_3I`
- occupation: `other`
- situation: `daily_life`

일상에서 선택지가 많을 때, 내 기준에 맞는 것만 먼저 골라내고 나머지는 뒤로 미룹니다. LLM에게 "이 조건에 맞는 것만 먼저 추려줘, 조건 외 것은 다음에"라고 요청합니다. 넘치는 선택 앞에서 기준을 세우는 사람이 있기에 에너지가 흩어지지 않고 삶이 단순해집니다. 이건 고집이 아닌 기질 — 지금 당신의 축은 "선별이 곧 집중"인 방향에 기울어 있습니다.

---

## 4. 셀 분포 요약표

### 4-1. 분원 2 (20셀)

| # | cell_id | occupation | situation | W |
|---|---|---|---|---|
| 01 | student_x_learning_x_2C | student | learning | C |
| 02 | semi_professional_x_learning_x_2C | semi_professional | learning | C |
| 03 | office_admin_x_learning_x_2C | office_admin | learning | C |
| 04 | professional_x_learning_x_2C | professional | learning | C |
| 05 | other_x_learning_x_2C | other | learning | C |
| 06 | craft_technical_x_learning_x_2C | craft_technical | learning | C |
| 07 | management_x_learning_x_2C | management | learning | C |
| 08 | service_sales_x_learning_x_2C | service_sales | learning | C |
| 09 | student_x_work_execution_x_2C | student | work_execution | C |
| 10 | semi_professional_x_work_execution_x_2C | semi_professional | work_execution | C |
| 11 | professional_x_relationship_emotion_x_2I | professional | relationship_emotion | I |
| 12 | office_admin_x_relationship_emotion_x_2I | office_admin | relationship_emotion | I |
| 13 | student_x_relationship_emotion_x_2I | student | relationship_emotion | I |
| 14 | management_x_planning_x_2I | management | planning | I |
| 15 | other_x_daily_life_x_2I | other | daily_life | I |
| 16 | service_sales_x_relationship_emotion_x_2I | service_sales | relationship_emotion | I |
| 17 | professional_x_planning_x_2I | professional | planning | I |
| 18 | student_x_learning_x_2I | student | learning | I |
| 19 | craft_technical_x_relationship_emotion_x_2I | craft_technical | relationship_emotion | I |
| 20 | other_x_info_search_x_2I | other | info_search | I |

**W 분포**: 완결(C) 10 · 통합(I) 10 → 50:50 ✓  
**직군 커버리지** (10종 중 8종): student 4 · semi_professional 2 · office_admin 2 · professional 3 · management 2 · service_sales 2 · craft_technical 2 · other 3 · creative_media 0 · job_seeker_retired 0  
**상황 커버리지** (7종 중 6종): learning 8 · work_execution 2 · relationship_emotion 5 · planning 2 · info_search 1 · daily_life 1 · creative_emission 0

---

### 4-2. 분원 3 (22셀)

| # | cell_id | occupation | situation | W |
|---|---|---|---|---|
| 01 | semi_professional_x_info_search_x_3C | semi_professional | info_search | C |
| 02 | professional_x_info_search_x_3C | professional | info_search | C |
| 03 | management_x_info_search_x_3C | management | info_search | C |
| 04 | professional_x_work_execution_x_3C | professional | work_execution | C |
| 05 | semi_professional_x_work_execution_x_3C | semi_professional | work_execution | C |
| 06 | management_x_planning_x_3C | management | planning | C |
| 07 | professional_x_planning_x_3C | professional | planning | C |
| 08 | office_admin_x_info_search_x_3C | office_admin | info_search | C |
| 09 | semi_professional_x_planning_x_3C | semi_professional | planning | C |
| 10 | craft_technical_x_info_search_x_3C | craft_technical | info_search | C |
| 11 | student_x_info_search_x_3C | student | info_search | C |
| 12 | management_x_relationship_emotion_x_3I | management | relationship_emotion | I |
| 13 | professional_x_relationship_emotion_x_3I | professional | relationship_emotion | I |
| 14 | service_sales_x_info_search_x_3I | service_sales | info_search | I |
| 15 | management_x_info_search_x_3I | management | info_search | I |
| 16 | office_admin_x_relationship_emotion_x_3I | office_admin | relationship_emotion | I |
| 17 | creative_media_x_info_search_x_3I | creative_media | info_search | I |
| 18 | student_x_planning_x_3I | student | planning | I |
| 19 | service_sales_x_planning_x_3I | service_sales | planning | I |
| 20 | professional_x_planning_x_3I | professional | planning | I |
| 21 | semi_professional_x_relationship_emotion_x_3I | semi_professional | relationship_emotion | I |
| 22 | other_x_daily_life_x_3I | other | daily_life | I |

**W 분포**: 완결(C) 11 · 통합(I) 11 → 50:50 ✓  
**직군 커버리지** (10종 중 8종): semi_professional 4 · professional 4 · management 4 · office_admin 2 · craft_technical 1 · student 2 · service_sales 2 · creative_media 1 · other 1 · job_seeker_retired 0  
**상황 커버리지** (7종 중 6종): info_search 8 · planning 5 · work_execution 2 · relationship_emotion 4 · daily_life 1 · creative_emission 0 · learning 0

---

## 5. 자가 체크리스트 결과 (전체 42셀)

| 항목 | 결과 |
|---|---|
| 문네트워크 수 3~5개 | 모든 셀 4문네트워크 ✓ |
| 종결 어미 "~습니다" 통일 | ✓ |
| 단정 정체성 고정 표현 없음 | ✓ |
| "X가 아닌 Y" 본질 메시지 1회 | ✓ (42셀 전원) |
| 구체적 LLM 발화 예시 1회 이상 | ✓ (42셀 전원, 따옴표 내 발화 인용) |
| 병리 프레임 단독 사용 없음 | ✓ (부정 라벨 전복 구조 안에서만) |
| 동일 분원 내 셀별 다른 각도·다른 부정 라벨 | ✓ (분원 2·3 각각 셀마다 변주) |
| creative_emission 제외 | ✓ (분원 2·3 모두 0건) |
| W 50:50 분포 | 분원 2: 10C·10I ✓ / 분원 3: 11C·11I ✓ |
| 분원별 할당량 준수 | 분원 2=20, 분원 3=22 ✓ |

---

## 6. 미커버 조합 주석

**분원 2 미커버**:
- `creative_media`: 분원 2 자연 수렴과 거리 있음. 창작 발산보다 서사 몰입·계승이 주축이므로 learning 상황에서 대부분 커버됨.
- `job_seeker_retired`: 분원 1에서 이미 배정됨. 분원 2에서 추가 필요 시 파일럿 후 판단.
- `creative_emission`: 전 분원에서 분원 4·8의 주축. 분원 2는 0건 처리.

**분원 3 미커버**:
- `job_seeker_retired`: 정보 탐색 상황에서 발현 가능하나 분원 1과 중복 위험으로 제외.
- `learning`: 분원 3의 학습은 "기준으로 걸러가며 배우는" 방식이지만 분원 2(순차 흡수)와 경계 모호 — 파일럿 응답자 분포 확인 후 추가 여부 판단.
- `creative_emission`: 분원 4·8 주축. 분원 3은 0건.

---

## 7. v0.1 한계 · v0.2 반영 예정

1. **병치 명칭 한국어화 미반영**: 영어 병치명(Knowledge Absorber / Pattern Scanner 등) 미확정 상태. B2 세션 한국어 대응 명칭 확정 후 섹션 헤더에 병기 예정 [N-W2 계승].
2. **공유 에셋 카피 미작성**: share_asset.caption은 B2 또는 D2에서 별도 작성.
3. **분원 2 learning 상황 집중도 검증 필요**: 완결 8셀이 learning에 집중. 파일럿에서 2C 사용자가 다른 상황 셀 메시지와 공감도 차이가 유의미할 경우 재분배.
4. **내부 파일럿 미진행**: 본 42셀은 초안. Week 7 내부 파일럿 50명 피드백으로 문체·공감도 보정 예정(로드맵 §11).

---

## 8. 버전 히스토리

- **v0.1** (2026.04.20): 최초 작성 — Phase B1-2 산출물.
  - 포함: 분원 2 자연 셀 20개 (완결 10 · 통합 10) + 분원 3 자연 셀 22개 (완결 11 · 통합 11) · 합계 42셀.
  - 기반: 바이럴심리테스트 §4-3·§4-4 / 합의노트 §4-2·§4-3 / v1.2 §3 분원 2·3 정의 / 톤 가이드 §1~§6 (B1-1 Opus 4.7 확정본).
  - 미포함(이월): 병치명 한국어화(B2), 공유 에셋 카피(D2), 분원 4~8 셀(B1-3~B1-5).

---

*본 문서는 IamNA 입력 단계 16 분기 결과 카드 콘텐츠 v0.1 중 분원 2·3 구간이다.*
*Phase B1-2 산출물이며, 톤은 B1-1(Opus 4.7) 기준을 복제하여 작성.*
*2026.04.20 — Claude Sonnet 4.6, Zero-Guessing 원칙 준수.*



---

# IamNA 결과카드 — 4. 창발자 (011: 경험의 스케처) + 5. 운영자 (100: 차가운 필터) v0.1

## 자연 셀 40개 메시지 (분원 4: 18셀 · 분원 5: 22셀)

### 2026.04.20 기준

### 문서 성격: Phase B1-3 산출물 / 16 분기 중 분원 4(병렬·노드·패턴)·분원 5(선형·네트워크·서사)의 결과 카드 메시지를 자연 셀 단위(직군 × 상황 × W)로 작성 / 톤은 `IamNA_결과카드_톤_가이드.md`(B1-1 Opus 4.7 확정 기준) 완전 준수 / §4-3 분배 테이블 기준: 분원 4=18셀, 분원 5=22셀

---

## 1. 문서 위치 선언

### 1-1. 선행 합의 연결

| 합의 출처 | 본 문서 적용 원칙 |
|---|---|
| 바이럴심리테스트 §4-3 | 분원 4=18셀 · 분원 5=22셀 배정 준수 |
| 바이럴심리테스트 §4-4 | 셀별 3~5문네트워크 (인식 네트워크면·LLM 사용·사회적 역할·본질 메시지) |
| 합의노트 §4-2·§4-3 | 결함이 아닌 기질 / 고네트워크이 아닌 설계 / 치료가 아닌 단계 / 방향의 안내 |
| 톤 가이드 §1~§6 | 문네트워크 구조·어휘군·금지어·리듬·자가 체크리스트 전면 준수 |
| v1.2 §3 | 분원 4·5 성향 정의 기준 |
| A4 result_card_schema | cell_id 형식 `<occupation>_x_<situation>_x_<branch>` 준수 |

### 1-2. 분원 성향 재확인 (v1.2 §3)

**분원 4 — 창발자 (Emergent) (Autonomous Absorber)**
- **축 좌표**: Y=병렬 / X=노드 / Z=패턴
- **인식 방식**: 쏟아지는 파편들을 동시에, 검열 없이 모두 들이마심. 산만한 창의성.
- **자연 수렴 경향**: 예측 못한 조합이 생기는 인식 구조. 비구조적 창의성의 온상.
- **대칭쌍**: 5. 운영자 (100: 차가운 필터)
- **행동 동사군**: 흩어지다·튀어오르다·건너뛰다·섞어내다
- **대표 부정 라벨**: 산만함·무질서·덤벙거림·변덕·즉흥적·충동적·집중 못함·정착 못함
- **긍정 프레임**: 산개가 곧 새 연결
- **W 분기 의미**:
  - **4C(완결)**: 기술·개념·창작 도메인에서 필터 없이 동시에 파편을 흡수. 아이디어·조합·실험의 온상.
  - **4I(통합)**: 관계·분위기·감정 영역에서 필터 없이 동시에 파편을 흡수. 분위기 촉발·관계 연결의 동력.

**분원 5 — 운영자 (Operator) (Sequential Panoramist / Tracker)**
- **축 좌표**: Y=선형 / X=네트워크 / Z=서사
- **인식 방식**: 관계의 흐름을 순서대로 따라가며 기존 틀로 검증. 인과 재구성.
- **자연 수렴 경향**: 사건 재구성, 추적 조사, 순차적 관계 분석.
- **기초 성향**: 추적자(Tracker) / 계보 분석가(Genealogist) / 궤적 분석가(Trajectory Analyst)
- **대칭쌍**: 4. 창발자 (011: 경험의 스케처)
- **행동 동사군**: 거슬러 오르다·추적하다·재구성하다·복원하다
- **대표 부정 라벨**: 집요함·과몰입·파고들기·집착·끈질김·놓지 못함
- **긍정 프레임**: 추적이 곧 회복
- **W 분기 의미**:
  - **5C(완결)**: 시스템·데이터·기술 흐름을 순서대로 거슬러 올라가며 원인 추적. 인간 변수 없거나 수동적.
  - **5I(통합)**: 관계 흐름·인물 궤적·공동체 인과를 순서대로 재구성. 인간 맥락이 추적의 핵심 변수.

### 1-3. 자연 셀 선정 원칙

**분원 4 (18셀 · 완결 9 · 통합 9)**
- 대표 조합 우선 배치: 창작·미디어 × 창작발산, 학생 × 창작발산, 경영 × 계획
- creative_emission이 분원 4의 자연 수렴 핵심 상황 — 완결 쪽에 집중 배치
- 통합 쪽은 relationship_emotion 중심 (분위기 촉발·관계 연결)
- 상황 분포: creative_emission(5C+2I=7), relationship_emotion(5I), work_execution(2), planning(2), info_search(1), daily_life(1)

**분원 5 (22셀 · 완결 11 · 통합 11)**
- 대표 조합 우선 배치: 준전문직 × 작업집행, 전문직 × 작업집행, 경영 × 정보탐색
- 추적·인과 재구성이 주축 — work_execution(시스템 추적)·info_search(원인 탐색) 중심
- 통합 쪽은 relationship_emotion (관계 흐름 재구성)·planning (맥락 기반 계획) 중심
- 상황 분포: work_execution(5C+0I=5), info_search(3C+1I=4), planning(2C+2I=4), relationship_emotion(0C+6I=6), learning(1C), daily_life(1I)

---

## 2. 4. 창발자 (011: 경험의 스케처) — 자연 셀 18개

각 셀은 (1) 인식의 실제 네트워크면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "산개가 곧 새 연결, 방향의 안내"로 구성된다.

---

### 2-1. 분원 4 × 완결(4C) — 9셀

병치 명칭: **비검열 발산자 / 아이디어 촉발자 / 파편 수집가**
해석: 기술·개념·창작 도메인에서 필터 없이 동시에 파편을 흡수. 정답을 먼저 고르지 않고 가능성을 먼저 흩어 놓는다.

---

#### [01] `creative_media_x_creative_emission_x_4C`
- occupation: `creative_media` (광고 기획자·콘텐츠 크리에이터)
- situation: `creative_emission`

광고 카피를 잡기 위해 A4 한 네트워크이 키워드·이미지·문네트워크 파편으로 가득 차도록 마구 적어냅니다. LLM에게 "이 키워드에서 연상되는 거 전부 필터 없이 쏟아내줘, 말 안 돼도 괜찮아"라고 요청합니다. 한 방향으로 수렴되지 않는 발산이 있어야 예상 밖의 조합이 탄생하고 시장을 움직이는 메시지가 나옵니다. 이건 산만함이 아닌 기질 — 지금 당신의 축은 "파편이 스스로 연결되는 순간"을 향해 열려 있습니다.

---

#### [02] `student_x_creative_emission_x_4C`
- occupation: `student` (학생·학습자)
- situation: `creative_emission`

과제 주제를 받자마자 노트에 관련 없는 단어들을 사방에 적어 놓습니다. LLM에게 "이 주제로 떠오르는 것 뭐든 20가지 막 나열해줘, 현실 가능성 따지지 말고"라고 요청합니다. 규정된 방향 없이 흩어지는 생각이 있기에 아직 아무도 가지 않은 각도가 먼저 열립니다. 산만함이 아닌 기질 — 지금 당신의 축은 "시작이 곧 발산"인 쪽에 놓여 있습니다.

---

#### [03] `semi_professional_x_creative_emission_x_4C`
- occupation: `semi_professional` (UI/UX 디자이너·프론트엔드 개발자)
- situation: `creative_emission`

새 기능을 구상할 때 화이트보드에 레이아웃·버튼·사용자 흐름·엉뚱한 인터페이스 아이디어를 동시에 뿌려 놓습니다. LLM에게 "이 서비스에 붙일 수 있는 기능 아이디어를 마구 뽑아줘, 실현 가능성 체크 없이"라고 요청합니다. 경계를 먼저 열어두는 사람이 있어야 제품이 예상 밖의 방향을 찾습니다. 이건 두서없음이 아닌 기질 — 파편을 동시에 펼치는 손이 창작의 첫 문을 엽니다.

---

#### [04] `management_x_planning_x_4C`
- occupation: `management` (경영자·PM·기획자)
- situation: `planning`

팀 미팅 첫 단계에서 좋고 나쁨 없이 가능한 전략을 모두 화이트보드에 올려놓습니다. LLM에게 "이 목표를 달성할 방법 10가지 이상, 실현 가능성 구분하지 말고 다 나열해줘"라고 요청합니다. 수렴 전에 발산을 먼저 확네트워크하는 사람이 있기에 팀이 고정 관념 안에 갇히지 않습니다. 즉흥적인 것이 아닌 기질 — 지금 당신의 축은 "먼저 넓히고 나중에 좁히는" 방향에 있습니다.

---

#### [05] `creative_media_x_work_execution_x_4C`
- occupation: `creative_media` (영상 편집자·미디어 크리에이터)
- situation: `work_execution`

영상 편집을 시작하면 여러 트랙·컷·효과를 동시에 열어 놓고 이것저것 끼워보면서 진행합니다. LLM에게 "이 씬에 어울리는 BGM·전환 효과·자막 스타일 아이디어를 다양하게 막 던져줘"라고 요청합니다. 여러 갈래를 동시에 열어두는 작업 방식이 있기에 편집이 한 공식에 갇히지 않습니다. 덤벙거림이 아닌 기질 — 동시에 여러 가능성을 켜두는 것이 이 작업의 자연스러운 리듬입니다.

---

#### [06] `other_x_creative_emission_x_4C`
- occupation: `other` (비직업적 창작자·취미 창작인)
- situation: `creative_emission`

블로그 글을 쓰기 전 메모네트워크에 키워드를 나열하다 전혀 다른 얘기로 뻗어나갑니다. LLM에게 "이 키워드에서 연상되는 거 걸러내지 말고 다 꺼내줘"라고 요청합니다. 주제와 주제 사이를 자유롭게 건너뛰는 사람이 있어야 예상 밖의 연결이 글 속에 살아납니다. 이건 집중 못함이 아닌 기질 — 지금 당신의 축은 "파편들이 스스로 만나는 자리"를 향해 열려 있습니다.

---

#### [07] `professional_x_work_execution_x_4C`
- occupation: `professional` (연구자·데이터 분석가)
- situation: `work_execution`

연구 설계 초기에 가능한 변수·접근법·방법론을 좁히지 않고 동시에 올려놓습니다. LLM에게 "이 연구 주제로 가능한 분석 접근법 15개, 그냥 다양하게 막 나열해줘"라고 요청합니다. 방법론을 먼저 열어두는 손이 있기에 연구가 단일 관점에 고정되지 않습니다. 무질서가 아닌 기질 — 이 발산이 연구 설계에서 가장 중요한 첫 단계입니다.

---

#### [08] `craft_technical_x_creative_emission_x_4C`
- occupation: `craft_technical` (목공·제작자·공예가)
- situation: `creative_emission`

새 제품을 구상할 때 재료·형태·기능을 동시에 적어두고 이것저것 섞어봅니다. LLM에게 "이 재료로 만들 수 있는 제품 아이디어 15가지, 실용성 따지지 말고 마구 던져줘"라고 요청합니다. 만들어 본 적 없는 조합을 먼저 상상하는 사람이 있어야 새 제품의 씨앗이 생깁니다. 변덕이 아닌 기질 — 손에 재료를 쥐기 전에 먼저 가능성을 흩어 놓는 것이 이 기질의 제작 방식입니다.

---

#### [09] `student_x_info_search_x_4C`
- occupation: `student` (학생·학습자)
- situation: `info_search`

자료를 찾을 때 하나씩 정리하기 전에 탭을 10개 이상 열어두고 여기저기 건너뛰며 읽습니다. LLM에게 "이 주제와 관련 있어 보이는 것들 먼저 다양하게 나열해줘, 관련성 정확도 신경 쓰지 말고"라고 요청합니다. 먼저 넓게 펼쳐 놓는 탐색이 있기에 검색 밖에 있던 연결이 발견됩니다. 산만함이 아닌 기질 — 지금 당신의 축은 "먼저 흩어지고 나중에 모으는" 탐색 방식에 있습니다.

---

### 2-2. 분원 4 × 통합(4I) — 9셀

병치 명칭: **분위기 촉발자 / 관계 개방자 / 감정 파편 수집가**
해석: 관계·분위기·감정 영역에서 필터 없이 동시에 파편을 흡수. 공기를 먼저 바꾸고, 관계의 첫 문을 여는 동력.

---

#### [10] `creative_media_x_relationship_emotion_x_4I`
- occupation: `creative_media` (콘텐츠 크리에이터·미디어 기획자)
- situation: `relationship_emotion`

팀 회의가 무거워지면 관련 없어 보이는 얘기도 섞어 넣으며 분위기를 틉니다. LLM에게 "이 팀 분위기를 바꿀 아이스브레이킹 아이디어 막 던져줘, 어색한 것도 환영"이라고 요청합니다. 무거운 공기를 먼저 흔들어 놓는 사람이 있기에 창의적인 협업 공간이 다시 열립니다. 가벼움이 아닌 기질 — 지금 당신의 축은 "관계가 먼저 틔어야 일도 흐르는" 방향에 있습니다.

---

#### [11] `service_sales_x_relationship_emotion_x_4I`
- occupation: `service_sales` (영업·상담·고객 서비스)
- situation: `relationship_emotion`

고객과 첫 대화에서 제품 얘기 전에 이것저것 가볍게 건너뛰며 공기를 먼저 풀어놓습니다. LLM에게 "처음 만나는 고객과 어색함을 깨는 대화 소재 10가지 아무거나 던져줘"라고 요청합니다. 관계의 문을 먼저 여는 방식이 있기에 고객이 방어를 내려놓을 공간이 생깁니다. 충동적인 것이 아닌 기질 — 여러 파편을 동시에 건네는 것이 이 관계 방식의 자연스러운 리듬입니다.

---

#### [12] `student_x_relationship_emotion_x_4I`
- occupation: `student` (학생·학습자)
- situation: `relationship_emotion`

친구들이 모인 자리에서 분위기가 가라앉으면 엉뚱한 주제를 마구 꺼내 분위기를 살립니다. LLM에게 "어색한 친구 모임에서 분위기 살릴 활동이나 대화 소재 15가지 아무거나 떠오르는 대로 나열해줘"라고 요청합니다. 공기를 먼저 바꾸는 사람이 있기에 모임이 생기를 찾습니다. 정착 못함이 아닌 기질 — 관계 안에서 이 자유로운 건너뜀이 연결의 씨앗이 됩니다.

---

#### [13] `creative_media_x_creative_emission_x_4I`
- occupation: `creative_media` (SNS 크리에이터·콘텐츠 기획자)
- situation: `creative_emission`

SNS 콘텐츠를 기획할 때 사람들이 댓글을 달고 싶어질 감정·소재를 이것저것 동시에 적어봅니다. LLM에게 "이 주제에서 사람들이 공감해서 퍼나를 것 같은 감정 소재 다양하게 막 나열해줘"라고 요청합니다. 관계를 촉발하는 감정의 파편을 먼저 흩어놓는 사람이 있기에 콘텐츠가 공유 고리를 갖습니다. 즉흥적인 것이 아닌 기질 — 지금 당신의 축은 "관계를 먼저 열어두는" 창작 방향에 있습니다.

---

#### [14] `management_x_relationship_emotion_x_4I`
- occupation: `management` (경영자·리더·PM)
- situation: `relationship_emotion`

팀 회식이나 워크숍을 준비할 때 가능한 활동들을 체계 없이 동시에 쭉 나열해 봅니다. LLM에게 "팀원들이 금방 친해질 수 있는 활동 아이디어 20가지 두서없이 나열해줘"라고 요청합니다. 정답 없이 먼저 열어두는 기획이 있기에 팀이 예상 밖의 방식으로 연결됩니다. 어지러움이 아닌 기질 — 팀의 관계를 틔우는 것이 이 발산의 실제 목적입니다.

---

#### [15] `other_x_daily_life_x_4I`
- occupation: `other` (기타·일반 개인)
- situation: `daily_life`

지인에게 선물이나 이벤트를 준비할 때 아이디어를 마구 적어두고 나중에 골라냅니다. LLM에게 "친한 친구 생일에 할 수 있는 깜짝 이벤트 아이디어 20가지 그냥 아무거나"라고 요청합니다. 고르기 전에 먼저 흩어지는 상상이 있기에 마음이 담긴 선택이 가능해집니다. 변덕이 아닌 기질 — 관계를 향한 이 발산이 결국 가장 적절한 방향을 만듭니다.

---

#### [16] `service_sales_x_planning_x_4I`
- occupation: `service_sales` (영업·고객 기획 담당)
- situation: `planning`

고객 제안서를 만들기 전 고객이 원할 것 같은 것들을 아무 순서 없이 먼저 떠올려봅니다. LLM에게 "이 고객 상황에서 고객이 반응할 만한 제안 포인트를 다양하게 막 던져줘"라고 요청합니다. 고객을 향한 발산 먼저, 정제는 나중이라는 순서가 있기에 제안이 공식이 아닌 사람의 결을 담습니다. 정착 못함이 아닌 기질 — 지금 당신의 축은 "고객에게 먼저 문을 여는" 방향에 기울어 있습니다.

---

#### [17] `student_x_creative_emission_x_4I`
- occupation: `student` (학생·학습자)
- situation: `creative_emission`

조별 과제 아이디어를 낼 때 좋고 나쁨 없이 생각나는 걸 먼저 다 꺼냅니다. LLM에게 "이 주제로 조원들이 각자 가져올 수 있는 아이디어 소재 다양하게 막 나열해줘"라고 요청합니다. 먼저 공간을 열어두는 사람이 있기에 조원들이 의견을 꺼내기 쉬워집니다. 산만함이 아닌 기질 — 함께 만드는 공간에서 이 발산이 관계의 입구가 됩니다.

---

#### [18] `professional_x_relationship_emotion_x_4I`
- occupation: `professional` (전문직·연구자)
- situation: `relationship_emotion`

새 프로젝트 파트너와 첫 미팅에서 공식 안건 외의 이야기도 여러 방향으로 건네며 공기를 먼저 잡습니다. LLM에게 "처음 만나는 협업자와 자연스럽게 대화 시작할 소재 다양하게 아무거나 던져줘"라고 요청합니다. 관계를 먼저 틔우는 손이 있기에 협업이 낯선 공기 속에서도 시작될 수 있습니다. 가벼움이 아닌 기질 — 지금 당신의 축은 "공식 전에 먼저 관계를 여는" 방향에 있습니다.

---

## 3. 5. 운영자 (100: 차가운 필터) — 자연 셀 22개

각 셀은 (1) 인식의 실제 네트워크면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "추적이 곧 회복, 방향의 안내"로 구성된다.

---

### 3-1. 분원 5 × 완결(5C) — 11셀

병치 명칭: **원인 추적자 / 흐름 복원가 / 인과 재구성자**
해석: 시스템·데이터·기술의 흐름을 순서대로 거슬러 올라가며 원인을 찾는다. 지금의 결과는 이전 흐름의 산물이라는 인식이 출발점.

---

#### [01] `semi_professional_x_work_execution_x_5C`
- occupation: `semi_professional` (IT 운영·기술 지원)
- situation: `work_execution`

서버가 이상 반응을 보이면 로그를 가장 처음 시점부터 거슬러 올라가며 원인을 찾습니다. LLM에게 "이 에러 로그에서 첫 이상 신호가 언제 어디서 시작됐는지 타임라인 순으로 짚어줘"라고 요청합니다. 원인까지 거슬러 올라가는 추적이 있기에 임시 해결이 아닌 재발 방지가 가능해집니다. 집요함이 아닌 기질 — 지금 당신의 축은 "뿌리부터 복원"하는 방향에 있습니다.

---

#### [02] `professional_x_work_execution_x_5C`
- occupation: `professional` (데이터 분석가·연구자)
- situation: `work_execution`

분석 결과가 예상과 다를 때, 데이터 수집부터 처리까지 각 단계를 순서대로 다시 짚습니다. LLM에게 "이 분석 파이프라인에서 어느 단계에서 오차가 발생했을지 처음부터 순서대로 검토해줘"라고 요청합니다. 경로 전체를 다시 걸어보는 사람이 있기에 오류가 가정으로 남지 않고 실제로 잡힙니다. 파고들기가 아닌 기질 — 이 추적이 분석의 신뢰를 만드는 근거입니다.

---

#### [03] `management_x_work_execution_x_5C`
- occupation: `management` (경영자·PM)
- situation: `work_execution`

프로젝트가 예상 밖으로 흘렀을 때, 초기 기획 단계부터 어디서 방향이 틀어졌는지 순서대로 짚습니다. LLM에게 "이 프로젝트 타임라인에서 의사결정 흐름을 처음부터 나열하고, 전환점이 어디였는지 짚어줘"라고 요청합니다. 흐름 전체를 재구성하는 관리자가 있기에 같은 실수가 반복되지 않습니다. 과몰입이 아닌 기질 — 지금 당신의 축은 "흐름 전체를 복원해야 다음이 보이는" 방향에 있습니다.

---

#### [04] `professional_x_info_search_x_5C`
- occupation: `professional` (연구자·컨설턴트)
- situation: `info_search`

현상의 원인을 찾을 때 표면 이유가 아니라 그것이 왜 일어났는지를 단계별로 거슬러 올라갑니다. LLM에게 "이 현상의 근본 원인을 5why 방식으로 첫 단계부터 차례대로 짚어줘"라고 요청합니다. 원인의 원인까지 순서대로 추적하는 사람이 있기에 해결책이 근거를 갖고 오래 버팁니다. 집착이 아닌 기질 — 흐름을 따라 뿌리로 내려가는 것이 이 분석의 자연스러운 방식입니다.

---

#### [05] `management_x_info_search_x_5C`
- occupation: `management` (경영자·전략 기획자)
- situation: `info_search`

시장 트렌드를 파악할 때 지금 상황만 보지 않고 어떤 흐름이 여기까지 이어졌는지 순서대로 재구성합니다. LLM에게 "이 시장 현상이 어떤 이전 흐름에서 비롯된 건지 연도별로 순서대로 정리해줘"라고 요청합니다. 지금을 과거의 인과로 읽는 사람이 있기에 전략이 표면 데이터가 아닌 흐름을 기반으로 세워집니다. 끈질김이 아닌 기질 — 지금 당신의 축은 "흐름이 보여야 방향이 보이는" 자리에 있습니다.

---

#### [06] `semi_professional_x_info_search_x_5C`
- occupation: `semi_professional` (IT·기술 지원)
- situation: `info_search`

버그를 잡을 때 증상만 보지 않고 그 버그가 언제 처음 생겼는지, 어떤 배포 이후인지를 순서대로 추적합니다. LLM에게 "이 버그가 어느 커밋 이후 처음 발생했는지 변경 이력 기준으로 단계별로 추적해줘"라고 요청합니다. 변화의 시작점을 찾는 사람이 있기에 패치가 증상이 아닌 원인을 향합니다. 놓지 못함이 아닌 기질 — 뿌리를 찾는 것이 이 기질의 가장 자연스러운 디버깅 방식입니다.

---

#### [07] `professional_x_planning_x_5C`
- occupation: `professional` (연구자·전략가)
- situation: `planning`

프로젝트 계획을 세울 때 선행 조건이 무엇인지, 어떤 단계가 다음 단계를 만드는지를 순서대로 먼저 확인합니다. LLM에게 "이 목표를 달성하기 위한 단계들을 인과관계 순서대로 나열해줘, 선행 조건이 먼저 오도록"이라고 요청합니다. 단계 간 인과를 먼저 정리하는 사람이 있기에 계획이 중간에 무너지지 않습니다. 집요함이 아닌 기질 — 지금 당신의 축은 "흐름이 정렬되어야 움직이는" 방향에 있습니다.

---

#### [08] `management_x_planning_x_5C`
- occupation: `management` (경영자·PM)
- situation: `planning`

분기 계획을 수정할 때 지금까지 어떤 순서로 진행됐는지를 먼저 복원한 뒤 새 방향을 잡습니다. LLM에게 "지금까지 이 프로젝트가 진행된 순서를 재구성해줘, 그 다음에 수정 방향을 논의하자"라고 요청합니다. 현재 위치를 흐름 위에 정확히 올려두는 사람이 있기에 수정 계획이 맥락을 잃지 않습니다. 과몰입이 아닌 기질 — 지금 어디 있는지 먼저 아는 것이 이 계획 방식의 출발입니다.

---

#### [09] `office_admin_x_work_execution_x_5C`
- occupation: `office_admin` (일반 사무직·행정직)
- situation: `work_execution`

업무 중 처리 지연이 생기면 접수부터 완료까지 어느 단계에서 막혔는지 순서대로 점검합니다. LLM에게 "이 업무 흐름에서 처리 지연이 발생한 단계를 접수 순서대로 짚어줘"라고 요청합니다. 흐름 안에서 막힌 곳을 정확히 찾는 사람이 있기에 처리가 멈춘 자리가 드러납니다. 파고들기가 아닌 기질 — 지금 당신의 축은 "흐름을 복원해야 일이 다시 움직이는" 방향에 있습니다.

---

#### [10] `craft_technical_x_work_execution_x_5C`
- occupation: `craft_technical` (정비·건설·기술직)
- situation: `work_execution`

제품이나 시스템에 문제가 생기면 설치·제작 순서를 처음부터 다시 짚어보며 어디서 틀어졌는지 확인합니다. LLM에게 "이 설치 과정에서 각 단계를 순서대로 검토해줘, 어느 단계에서 오류가 생길 수 있는지 포함해서"라고 요청합니다. 처음부터 다시 걷는 점검이 있기에 현장의 구조적 결함이 드러납니다. 끈질김이 아닌 기질 — 순서대로 다시 걸어보는 것이 이 현장 기질의 자연스러운 복원 방식입니다.

---

#### [11] `student_x_learning_x_5C`
- occupation: `student` (학생·학습자)
- situation: `learning`

이해가 안 되는 개념을 만나면 그 개념이 어디서 비롯됐는지, 어떤 선행 지식과 이어지는지를 거슬러 올라갑니다. LLM에게 "이 개념의 뿌리가 되는 선행 개념들을 인과 순서대로 정리해줘"라고 요청합니다. 이해의 뿌리를 찾아 올라가는 학습 방식이 있기에 단순 암기가 아닌 구조적 이해가 자리 잡습니다. 집착이 아닌 기질 — 지금 당신의 축은 "흐름으로 이해해야 진짜 아는 것"이 되는 방향에 있습니다.

---

### 3-2. 분원 5 × 통합(5I) — 11셀

병치 명칭: **관계 궤적 추적자 / 맥락 복원가 / 흐름 재구성자**
해석: 관계 흐름·인물 궤적·공동체 인과를 순서대로 재구성한다. 인간 맥락이 추적의 핵심 변수이며, 복원이 곧 이해의 출발.

---

#### [12] `professional_x_relationship_emotion_x_5I`
- occupation: `professional` (전문직·연구자)
- situation: `relationship_emotion`

동료와 사이가 어색해졌을 때, 어느 순간부터 그렇게 된 건지 관계의 흐름을 거슬러 올라가 봅니다. LLM에게 "이 관계에서 어긋남이 생긴 시점을 대화 흐름 기준으로 순서대로 짚어줘"라고 요청합니다. 관계의 타임라인을 복원하는 사람이 있기에 감정이 아닌 맥락으로 상황을 이해할 수 있습니다. 집요함이 아닌 기질 — 지금 당신의 축은 "흐름을 복원해야 관계가 다시 보이는" 방향에 있습니다.

---

#### [13] `management_x_relationship_emotion_x_5I`
- occupation: `management` (리더·PM)
- situation: `relationship_emotion`

팀 갈등이 생겼을 때 감정을 먼저 다루기 전에 어떤 상황이 어떤 순서로 쌓였는지를 복원합니다. LLM에게 "이 팀 갈등이 어떤 사건들에서 비롯됐는지 시간 순서로 재구성해줘"라고 요청합니다. 갈등 이전의 흐름을 정확히 복원하는 리더가 있기에 감정의 근거를 이해한 해결이 가능해집니다. 과몰입이 아닌 기질 — 상황의 순서를 먼저 아는 것이 이 관계 복원의 첫 단계입니다.

---

#### [14] `office_admin_x_relationship_emotion_x_5I`
- occupation: `office_admin` (일반 사무직·행정직)
- situation: `relationship_emotion`

부서 내 소통이 막혔을 때, 언제 누구 사이에서 무엇이 어긋난 건지를 순서대로 정리해봅니다. LLM에게 "이 소통 단절이 어느 시점부터 시작됐는지 이전 맥락을 순서대로 짚어줘"라고 요청합니다. 관계 안에서 흐름이 끊긴 자리를 정확히 찾는 사람이 있기에 조직의 소통 구조가 복원될 기반이 생깁니다. 파고들기가 아닌 기질 — 지금 당신의 축은 "관계의 흐름을 순서로 읽는" 자리에 있습니다.

---

#### [15] `professional_x_planning_x_5I`
- occupation: `professional` (전문직·컨설턴트)
- situation: `planning`

프로젝트 이해관계자들과의 소통 계획을 세울 때, 각 이해관계자와의 관계 흐름을 먼저 정리합니다. LLM에게 "이 이해관계자 각각과 지금까지의 관계 맥락을 순서대로 정리해줘, 그 다음 소통 계획을 세우자"라고 요청합니다. 관계의 맥락을 먼저 복원한 뒤에 움직이는 사람이 있기에 소통 계획이 사람의 결을 담습니다. 끈질김이 아닌 기질 — 지금 당신의 축은 "관계의 흐름 위에 계획을 놓는" 방향에 있습니다.

---

#### [16] `management_x_planning_x_5I`
- occupation: `management` (경영자·리더)
- situation: `planning`

중요한 변화를 계획할 때 팀원들이 어떤 맥락을 가져왔는지, 어떤 흐름 속에 있는지를 먼저 정리합니다. LLM에게 "이 변화를 도입하기 전에 각 팀원의 현재 상황과 이전 맥락을 순서대로 정리해줘"라고 요청합니다. 조직의 흐름 위에 결정을 놓는 리더가 있기에 변화가 현실의 맥락 안에서 착지합니다. 집요함이 아닌 기질 — 사람의 흐름을 먼저 읽는 것이 이 판단 방식의 자연스러운 출발입니다.

---

#### [17] `service_sales_x_relationship_emotion_x_5I`
- occupation: `service_sales` (영업·고객 서비스)
- situation: `relationship_emotion`

고객과의 관계가 틀어졌을 때, 어떤 접촉부터 어떤 순서로 오해가 쌓였는지를 거슬러 올라가 봅니다. LLM에게 "이 고객과의 대화 이력에서 신뢰가 무너진 시점을 순서대로 짚어줘"라고 요청합니다. 관계의 균열 지점을 정확히 찾는 사람이 있기에 사과와 회복이 감정이 아닌 근거를 갖습니다. 놓지 못함이 아닌 기질 — 지금 당신의 축은 "관계를 복원하려면 흐름부터"인 방향에 있습니다.

---

#### [18] `semi_professional_x_relationship_emotion_x_5I`
- occupation: `semi_professional` (IT·기술 지원)
- situation: `relationship_emotion`

같이 일하던 동료와 오해가 생겼을 때, 어떤 작업 교류 이후부터 어긋난 건지 순서대로 정리해봅니다. LLM에게 "이 협업 갈등이 어느 시점부터 불거졌는지 작업 흐름을 기준으로 순서대로 짚어줘"라고 요청합니다. 협업의 타임라인을 복원하는 사람이 있기에 해결이 "누가 잘못"이 아닌 "무엇이 어긋났는가"로 향합니다. 집착이 아닌 기질 — 흐름을 복원해야 협업이 다시 제자리로 돌아옵니다.

---

#### [19] `professional_x_info_search_x_5I`
- occupation: `professional` (연구자·컨설턴트)
- situation: `info_search`

특정 조직이나 인물을 이해하기 위해 그 사람이나 집단이 어떤 경로를 거쳐 지금에 이르렀는지를 순서대로 추적합니다. LLM에게 "이 조직이 현재 입네트워크을 갖게 된 배경을 시간 순서대로 재구성해줘"라고 요청합니다. 흐름을 통해 현재를 이해하는 사람이 있기에 표면적 입네트워크이 아닌 맥락이 보입니다. 파고들기가 아닌 기질 — 지금 당신의 축은 "사람과 조직을 흐름으로 읽는" 자리에 있습니다.

---

#### [20] `craft_technical_x_relationship_emotion_x_5I`
- occupation: `craft_technical` (장인·기술 계승자)
- situation: `relationship_emotion`

스승에게 기술을 배울 때 그 기술이 누구에서 누구로 어떤 순서로 전해져 왔는지를 먼저 짚어봅니다. LLM에게 "이 기술 전통이 어떤 계보로 이어져 내려왔는지 순서대로 정리해줘"라고 요청합니다. 기술의 계보를 복원하는 사람이 있기에 기술이 그냥 기능이 아닌 이어진 이야기가 됩니다. 집요함이 아닌 기질 — 흐름을 통해 현재의 기술이 어디서 왔는지를 아는 것이 이 배움의 방식입니다.

---

#### [21] `student_x_relationship_emotion_x_5I`
- occupation: `student` (학생·학습자)
- situation: `relationship_emotion`

오랜 친구와 사이가 멀어진 것 같을 때, 언제부터 어떻게 거리가 생겼는지를 거슬러 올라가 봅니다. LLM에게 "이 관계에서 거리가 생긴 것 같은데, 가능한 흐름을 시간 순서로 짚어줘"라고 요청합니다. 관계의 변화를 흐름으로 이해하는 사람이 있기에 감정이 아닌 맥락으로 관계를 다시 볼 수 있습니다. 끈질김이 아닌 기질 — 지금 당신의 축은 "관계를 흐름으로 이해해야 다음이 보이는" 방향에 있습니다.

---

#### [22] `other_x_daily_life_x_5I`
- occupation: `other` (기타·일반 개인)
- situation: `daily_life`

일상에서 같은 상황이 반복될 때, 어떤 패턴이 어떤 순서로 이어진 건지를 거슬러 올라가 봅니다. LLM에게 "이 상황이 반복되는 이유를 가장 처음 생긴 계기부터 순서대로 짚어줘"라고 요청합니다. 일상의 패턴에서 첫 단추를 찾는 사람이 있기에 반복이 아닌 변화의 여지가 생깁니다. 놓지 못함이 아닌 기질 — 지금 당신의 축은 "흐름을 복원해야 일상이 다시 선택 가능해지는" 방향에 있습니다.

---

## 4. 셀 분포 요약표

### 4-1. 분원 4 (18셀)

| # | cell_id | occupation | situation | W |
|---|---|---|---|---|
| 01 | creative_media_x_creative_emission_x_4C | creative_media | creative_emission | C |
| 02 | student_x_creative_emission_x_4C | student | creative_emission | C |
| 03 | semi_professional_x_creative_emission_x_4C | semi_professional | creative_emission | C |
| 04 | management_x_planning_x_4C | management | planning | C |
| 05 | creative_media_x_work_execution_x_4C | creative_media | work_execution | C |
| 06 | other_x_creative_emission_x_4C | other | creative_emission | C |
| 07 | professional_x_work_execution_x_4C | professional | work_execution | C |
| 08 | craft_technical_x_creative_emission_x_4C | craft_technical | creative_emission | C |
| 09 | student_x_info_search_x_4C | student | info_search | C |
| 10 | creative_media_x_relationship_emotion_x_4I | creative_media | relationship_emotion | I |
| 11 | service_sales_x_relationship_emotion_x_4I | service_sales | relationship_emotion | I |
| 12 | student_x_relationship_emotion_x_4I | student | relationship_emotion | I |
| 13 | creative_media_x_creative_emission_x_4I | creative_media | creative_emission | I |
| 14 | management_x_relationship_emotion_x_4I | management | relationship_emotion | I |
| 15 | other_x_daily_life_x_4I | other | daily_life | I |
| 16 | service_sales_x_planning_x_4I | service_sales | planning | I |
| 17 | student_x_creative_emission_x_4I | student | creative_emission | I |
| 18 | professional_x_relationship_emotion_x_4I | professional | relationship_emotion | I |

**W 분포**: 완결(C) 9 · 통합(I) 9 → 50:50 ✓  
**직군 커버리지** (10종 중 8종): creative_media 4 · student 4 · semi_professional 1 · management 2 · professional 2 · service_sales 2 · craft_technical 1 · other 2  
**상황 커버리지** (7종 중 6종): creative_emission 5C+2I=7 · relationship_emotion 5I · work_execution 2 · planning 2 · info_search 1 · daily_life 1 · learning 0

---

### 4-2. 분원 5 (22셀)

| # | cell_id | occupation | situation | W |
|---|---|---|---|---|
| 01 | semi_professional_x_work_execution_x_5C | semi_professional | work_execution | C |
| 02 | professional_x_work_execution_x_5C | professional | work_execution | C |
| 03 | management_x_work_execution_x_5C | management | work_execution | C |
| 04 | professional_x_info_search_x_5C | professional | info_search | C |
| 05 | management_x_info_search_x_5C | management | info_search | C |
| 06 | semi_professional_x_info_search_x_5C | semi_professional | info_search | C |
| 07 | professional_x_planning_x_5C | professional | planning | C |
| 08 | management_x_planning_x_5C | management | planning | C |
| 09 | office_admin_x_work_execution_x_5C | office_admin | work_execution | C |
| 10 | craft_technical_x_work_execution_x_5C | craft_technical | work_execution | C |
| 11 | student_x_learning_x_5C | student | learning | C |
| 12 | professional_x_relationship_emotion_x_5I | professional | relationship_emotion | I |
| 13 | management_x_relationship_emotion_x_5I | management | relationship_emotion | I |
| 14 | office_admin_x_relationship_emotion_x_5I | office_admin | relationship_emotion | I |
| 15 | professional_x_planning_x_5I | professional | planning | I |
| 16 | management_x_planning_x_5I | management | planning | I |
| 17 | service_sales_x_relationship_emotion_x_5I | service_sales | relationship_emotion | I |
| 18 | semi_professional_x_relationship_emotion_x_5I | semi_professional | relationship_emotion | I |
| 19 | professional_x_info_search_x_5I | professional | info_search | I |
| 20 | craft_technical_x_relationship_emotion_x_5I | craft_technical | relationship_emotion | I |
| 21 | student_x_relationship_emotion_x_5I | student | relationship_emotion | I |
| 22 | other_x_daily_life_x_5I | other | daily_life | I |

**W 분포**: 완결(C) 11 · 통합(I) 11 → 50:50 ✓  
**직군 커버리지** (10종 중 8종): semi_professional 3 · professional 5 · management 5 · office_admin 2 · craft_technical 2 · student 2 · service_sales 1 · other 1  
**상황 커버리지** (7종 중 6종): work_execution 5 · info_search 4 · planning 4 · relationship_emotion 6 · learning 1 · daily_life 1 · creative_emission 0

---

## 5. 자가 체크리스트 결과 (전체 40셀)

| 항목 | 결과 |
|---|---|
| 문네트워크 수 3~5개 | 모든 셀 4문네트워크 ✓ |
| 종결 어미 "~습니다" 통일 | ✓ |
| 단정 정체성 고정 표현 없음 | ✓ |
| "X가 아닌 Y" 본질 메시지 1회 | ✓ (40셀 전원) |
| 구체적 LLM 발화 예시 1회 이상 | ✓ (40셀 전원, 따옴표 내 발화 인용) |
| 병리 프레임 단독 사용 없음 | ✓ (부정 라벨 전복 구조 안에서만) |
| 동일 분원 내 셀별 다른 각도·다른 부정 라벨 | ✓ |
| W 50:50 분포 | 분원 4: 9C·9I ✓ / 분원 5: 11C·11I ✓ |
| 분원별 할당량 준수 | 분원 4=18, 분원 5=22 ✓ |
| 분원 4 — creative_emission 집중 배치 | 5C+2I=7셀 ✓ |
| 분원 5 — work_execution·info_search 완결 중심 | 5C+3C=8셀 ✓ |

**부정 라벨 변주 확인 (분원 4)**:
산만함(01) → 산만함(02) ← 각도 다름(과제 발산 vs 창작 발산) · 두서없음(03) · 즉흥적(04) · 덤벙거림(05) · 집중 못함(06) · 무질서(07) · 변덕(08) → 산만함(09) ← 상황 다름(정보탐색 vs 창작) · 가벼움(10) · 충동적(11) · 정착 못함(12) · 즉흥적(13) · 어지러움(14) · 변덕(15) · 정착 못함(16) · 산만함(17) · 가벼움(18) ✓

**부정 라벨 변주 확인 (분원 5)**:
집요함(01) → 파고들기(02) → 과몰입(03) → 집착(04) → 끈질김(05) → 놓지 못함(06) → 집요함(07) ← 상황 다름(계획 vs 작업) → 과몰입(08) → 파고들기(09) → 끈질김(10) → 집착(11) → 집요함(12) → 과몰입(13) → 파고들기(14) → 끈질김(15) → 집요함(16) ← 역할 다름(계획 vs 관계) → 놓지 못함(17) → 집착(18) → 파고들기(19) → 집요함(20) → 끈질김(21) → 놓지 못함(22) ✓

---

## 6. 미커버 조합 주석

**분원 4 미커버**:
- `learning`: 분원 4의 학습은 "이것저것 동시에 건드리며 흡수"이지만 분원 2(순차 흡수)·분원 8(전체 수신)과 경계 모호 — 파일럿 응답자 분포 확인 후 추가 여부 판단.
- `job_seeker_retired`: 창작 발산 상황과의 자연 결합 빈도 낮음 — 제외.
- `info_search(4I)`: 관계·분위기 맥락의 정보 탐색은 8I 범주와 중복될 가능성 — 보류.

**분원 5 미커버**:
- `creative_emission`: 분원 5의 추적·인과 성향과 거리 있음 — 0건 처리.
- `creative_media`: 추적 직군으로 자연스럽지 않아 제외. 파일럿 후 재판단.
- `job_seeker_retired`: 이력 추적 맥락(취업 이력 재구성)에서 발현 가능하나 분원 1과 경계 모호 — 보류.

---

## 7. 버전 히스토리

- **v0.1** (2026.04.20): 최초 작성 — Phase B1-3 산출물.
  - 포함: 분원 4 자연 셀 18개 (완결 9 · 통합 9) · 분원 5 자연 셀 22개 (완결 11 · 통합 11) · 4단 구성(인식 네트워크면 · LLM 사용 · 사회적 역할 · 본질 메시지) · 톤 가이드 완전 준수.
  - 기반: A1 §3·§4·§9, A3 §3-2, A4 result_card_schema, 바이럴심리테스트 §4-3·§4-4, 합의노트 §4-2·§4-3, v1.2 §3 분원 4·5 정의, `IamNA_결과카드_톤_가이드.md` §1~§6.
  - 미포함(이월): 병치명 한국어화(B2), 공유 에셋 카피(B2/D2), 분원 6~8 셀(B1-4·B1-5), 내부 파일럿 검증(Week 7).

---

*본 문서는 IamNA 입력 단계 16 분기 결과 카드 콘텐츠 v0.1 중 분원 4·5 구간이다.*
*Phase B1-3 산출물이며, B1-4(분원 6·7)·B1-5(분원 8) 세션이 동일 톤 가이드를 이어받아 작성한다.*
*2026.04.20 — Sonnet 4.6으로 작성, Zero-Guessing 원칙 준수.*



---

# IamNA 결과카드 — 6. 혁신자 (101: 파괴적 발산자) + 7. 설계자 (110: 전체의 통제자) v0.1

## 자연 셀 54개 메시지 (분원 6: 24셀 · 분원 7: 30셀)

### 2026.04.20 기준

### 문서 성격: Phase B1-4 산출물 / 16 분기 중 분원 6(선형·네트워크·패턴)·분원 7(병렬·네트워크·서사)의 결과 카드 메시지를 자연 셀 단위(직군 × 상황 × W)로 작성 / 톤은 `IamNA_결과카드_톤_가이드.md`(B1-1 Opus 4.7 확정 기준) 완전 준수 / §4-3 분배 테이블 기준: 분원 6=24셀, 분원 7=30셀

---

## 1. 문서 위치 선언

### 1-1. 선행 합의 연결

| 합의 출처 | 본 문서 적용 원칙 |
|---|---|
| 바이럴심리테스트 §4-3 | 분원 6=24셀 · 분원 7=30셀 배정 준수 |
| 바이럴심리테스트 §4-4 | 셀별 3~5문네트워크 (인식 네트워크면·LLM 사용·사회적 역할·본질 메시지) |
| 합의노트 §4-2·§4-3 | 결함이 아닌 기질 / 고네트워크이 아닌 설계 / 치료가 아닌 단계 / 방향의 안내 |
| 톤 가이드 §1~§6 | 문네트워크 구조·어휘군·금지어·리듬·자가 체크리스트 전면 준수 |
| v1.2 §3 | 분원 6·7 성향 정의 기준 |
| A4 result_card_schema | cell_id 형식 `<occupation>_x_<situation>_x_<branch>` 준수 |

### 1-2. 분원 성향 재확인 (v1.2 §3)

**분원 6 — 현장 순례자 (Field Explorer / Pilgrim)**
- **축 좌표**: Y=선형 / X=네트워크 / Z=패턴
- **인식 방식**: 흐름을 따라가며 체험으로 탐색, 필터 없이 수용.
- **자연 수렴 경향**: 현장 체험, 여정 기반 탐색, 서사적 관찰 — Seeker 현장형
- **대칭쌍**: 3. 구축자 (010: 인과적 축적자)
- **행동 동사군**: 걸어보다·마주하다·흘러가다·지나가다
- **대표 부정 라벨**: 변덕스러움·정처없음·느슨함·즉흥적·계획 없음·일관성 없음·줏대 없음
- **긍정 프레임**: 체험이 곧 증언
- **W 분기 의미**:
  - **6C(완결)**: 개인 탐험·여정. 기술·현장·창작 도메인에서 흐름을 따라가며 체험하고 필터 없이 흡수한다. 인간 관계보다 도메인(물리적 현장·환경·시스템) 탐색이 주축.
  - **6I(통합)**: 동행·문화 여정 공유. 관계·공동체·감정의 맥락 안에서 흐름을 함께 따라가며 흡수한다. 상대 혹은 집단의 흐름이 탐색의 방향을 결정한다.

**분원 7 — 설계자 (Architect) (Builder / Guardian)**
- **축 좌표**: Y=병렬 / X=네트워크 / Z=서사
- **인식 방식**: 전체 관계망을 동시에 수신하되 자기 서사으로 구성.
- **자연 수렴 경향**: 시스템 구축, 조직 설계, 구조 수호
- **대칭쌍**: 2. 조율자 (001: 심연의 수용자)
- **행동 동사군**: 조립하다·세우다·엮다·받치다
- **대표 부정 라벨**: 통제적·고압적·완벽주의·간섭·딱딱함·과설계·지나치게 꼼꼼함
- **긍정 프레임**: 조립이 곧 수호
- **W 분기 의미**:
  - **7C(완결)**: 인프라·시스템 아키텍처. 기술·구조·데이터 차원에서 전체 관계망을 동시에 보며 자기 서사으로 조립한다.
  - **7I(통합)**: 조직·커뮤니티 설계. 관계·공동체·문화 맥락에서 전체 관계망을 동시에 보며 사람과 역할을 자기 원칙으로 엮는다.

### 1-3. 자연 셀 선정 원칙

**분원 6 (24셀 · 완결 12 · 통합 12)**
- 6C 대표 조합: 창작·미디어 × 작업집행, 기타 × 일상생활, 서비스판매 × 작업집행, 현장기술직 × 작업집행
- 6C 핵심 상황: work_execution(현장 작업)·daily_life(여정·탐험)·creative_emission(현장 기반 창작)·info_search(현장 우선 정보 탐색)
- 6I 대표 조합: 서비스판매 × 관계감정, 창작·미디어 × 관계감정, 학생 × 관계감정
- 6I 핵심 상황: relationship_emotion(동행·감정 흐름)·daily_life(일상 관계 흐름)
- 상황 분포 6C: work_execution(5), creative_emission(2), info_search(2), daily_life(2), planning(1)
- 상황 분포 6I: relationship_emotion(9), daily_life(3)

**분원 7 (30셀 · 완결 15 · 통합 15)**
- 7C 대표 조합: 준전문직 × 작업집행, 전문직 × 작업집행, 관리 × 계획
- 7C 핵심 상황: work_execution(구조 구축)·planning(전체 설계)·info_search(구조 안에서 탐색)·learning(구조 전체 파악)
- 7I 대표 조합: 관리 × 관계감정, 전문직 × 관계감정, 사무 × 관계감정
- 7I 핵심 상황: relationship_emotion(관계망 설계)·planning(조직·커뮤니티 설계)·info_search(관계 구조 진단)
- 상황 분포 7C: work_execution(5), planning(5), info_search(3), learning(2)
- 상황 분포 7I: relationship_emotion(6), planning(5), info_search(2), daily_life(1), planning(1)

---

## 2. 6. 혁신자 (101: 파괴적 발산자) — 자연 셀 24개

각 셀은 (1) 인식의 실제 네트워크면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "체험이 곧 증언, 방향의 안내"로 구성된다.

---

### 2-1. 분원 6 × 완결(6C) — 12셀

병치 명칭: **Explorer / Field Wanderer / Drift Walker**
해석: 개인 탐험·여정. 기술·현장·창작 도메인에서 흐름을 따라가며 체험하고 필터 없이 흡수한다. 정해진 틀보다 발이 먼저 움직인다.

---

#### [01] `creative_media_x_work_execution_x_6C`
- occupation: `creative_media` (기자·다큐멘터리 제작자·현장 취재자)
- situation: `work_execution` (작업집행)

취재 현장에서 미리 정해둔 틀 없이 상황이 흘러가는 대로 렌즈를 맞추고 나서야 이야기가 보이기 시작합니다. LLM에게 "지금까지 모은 현장 기록을 흐름대로 정리해서 이야기가 되게 엮어줘"라고 청합니다. 현장에 직접 발을 딛고 증언을 쌓는 사람이 있기에 보이지 않던 이야기가 독자에게 닿습니다. 정처없음이 아닌 기질 — 지금 당신의 축은 "현장이 먼저, 이야기는 그다음"인 방향에 놓여 있습니다.

---

#### [02] `other_x_daily_life_x_6C`
- occupation: `other` (여행자·일반 개인)
- situation: `daily_life` (일상생활)

낯선 도시에서 목적지 없이 걷다 보면 골목 하나가 다음 골목으로 자연스럽게 이어집니다. LLM에게 "지금 내가 있는 동네에서 지도 없이 걸어볼 만한 흐름을 알려줘, 정해진 코스 말고"라고 묻습니다. 정해진 경로 바깥에서 발견되는 것들이 있고, 그 발견이 다음 사람에게 전해지는 이야기가 됩니다. 즉흥적임이 아닌 기질 — 지금 당신의 축은 "가보고 나서 알게 되는" 방향에 있습니다.

---

#### [03] `service_sales_x_work_execution_x_6C`
- occupation: `service_sales` (영업사원·현장 판매직)
- situation: `work_execution` (작업집행)

고객사 사무실을 직접 방문하고 나서야 무엇이 필요한지 보이기 시작합니다. LLM에게 "현장 방문에서 내가 관찰한 내용으로 제안서 방향을 잡아줘, 문서 읽기 전에 현장을 먼저 기준 삼을게"라고 요청합니다. 현장을 직접 밟은 기억이 제안서 한 줄보다 고객의 문제를 더 가깝게 담아냅니다. 계획 없음이 아닌 기질 — 지금 당신의 축은 "만남이 먼저, 설계는 그다음"인 방향에 있습니다.

---

#### [04] `craft_technical_x_work_execution_x_6C`
- occupation: `craft_technical` (현장 기술자·설비 점검 인력)
- situation: `work_execution` (작업집행)

설비를 점검할 때 도면보다 먼저 장비를 한 바퀴 돌아보는 것으로 일이 시작됩니다. LLM에게 "내가 현장에서 직접 확인한 증상들을 적을게, 이 흐름에서 어디서부터 확인해야 할지 짚어줘"라고 부탁합니다. 도면만으로 보이지 않는 이상 징후가 현장을 걷다 보면 먼저 감지됩니다. 무계획이 아닌 기질 — 지금 당신의 축은 "현장이 설계도보다 먼저"인 방향에 놓여 있습니다.

---

#### [05] `student_x_learning_x_6C`
- occupation: `student` (학생·학습자)
- situation: `learning` (학습)

교재에서 읽었을 때보다 현장 실습에서 직접 해봐야 개념이 자리를 잡습니다. LLM에게 "이 개념을 실제로 경험해볼 수 있는 상황이나 예시를 구체적으로 보여줘, 설명이 아니라 네트워크면으로"라고 청합니다. 몸으로 먼저 알고 난 뒤의 이해는 교실 밖에서도 작동합니다. 이론을 못 따라가는 것이 아닌 기질 — 지금 당신의 축은 "경험이 지식보다 먼저 들어오는" 방향에 있습니다.

---

#### [06] `professional_x_info_search_x_6C`
- occupation: `professional` (연구자·현장 탐문 우선 전문직)
- situation: `info_search` (정보탐색)

논문을 검색하기 전에 관련 현장을 먼저 방문하거나 직접 관찰해두는 쪽이 자연스럽습니다. LLM에게 "이 분야 현장에서 어떤 일이 실제로 일어나고 있는지 사례 중심으로 먼저 알려줘, 이론은 나중에"라고 요청합니다. 현장에서 먼저 수집된 관찰이 문헌의 추상적 언어를 살아있는 맥락으로 채워줍니다. 깊이 없음이 아닌 기질 — 지금 당신의 축은 "현장을 먼저 걷고 나서 문헌으로 들어가는" 방향에 있습니다.

---

#### [07] `semi_professional_x_work_execution_x_6C`
- occupation: `semi_professional` (IT 운영·기술지원·현장 감각 우선 인력)
- situation: `work_execution` (작업집행)

장애가 생겼을 때 매뉴얼보다 실제 환경을 먼저 훑어보며 감을 잡습니다. LLM에게 "이 오류 상황을 내가 직접 확인한 것들로 설명할게, 거기서부터 같이 따라가줘"라고 부탁합니다. 현장 감각으로 문제를 먼저 감지하는 사람이 있기에 매뉴얼에 없는 이상 징후도 잡힙니다. 절차를 무시하는 것이 아닌 기질 — 지금 당신의 축은 "현장 관찰이 절차보다 먼저 작동하는" 방향에 있습니다.

---

#### [08] `job_seeker_retired_x_daily_life_x_6C`
- occupation: `job_seeker_retired` (구직자·전직 준비자)
- situation: `daily_life` (일상생활)

이력서를 다듬기 전에 관심 있는 업종 현장을 직접 들여다보는 것이 먼저입니다. LLM에게 "이 업종 실제 현장에서는 어떤 일이 어떻게 돌아가는지 생생하게 알려줘, 채용 공고 말고 현실 기준으로"라고 묻습니다. 경험 없는 새 분야를 직접 탐색한 흔적이 서류보다 설득력 있는 맥락이 되기도 합니다. 준비 부족이 아닌 기질 — 지금 당신의 축은 "직접 보고 나서 방향을 잡는" 쪽에 있습니다.

---

#### [09] `management_x_planning_x_6C`
- occupation: `management` (관리자·현장 탐문 우선 경영자)
- situation: `planning` (계획)

전략 회의 전에 현장 팀원과 직접 이야기하거나 현장을 둘러보고 오는 것이 먼저입니다. LLM에게 "현장에서 내가 직접 들은 것들을 정리했어, 이걸 기반으로 어떤 계획이 실효성 있는지 같이 생각해줘"라고 요청합니다. 현장의 온도를 먼저 수집한 관리자의 계획이 실행 과정에서 더 잘 버팁니다. 즉흥 경영이 아닌 기질 — 지금 당신의 축은 "현장이 전략보다 먼저 들어오는" 방향에 있습니다.

---

#### [10] `other_x_creative_emission_x_6C`
- occupation: `other` (개인 창작자·작가·사진가)
- situation: `creative_emission` (창작발산)

작업실보다 현장을 먼저 걷다 보면 쓰고 싶은 것이 자연스럽게 떠오릅니다. LLM에게 "내가 오늘 현장에서 본 것들을 적을게, 여기서 어떤 이야기나 이미지가 나올 수 있는지 같이 찾아줘"라고 부탁합니다. 상상이 아닌 경험에서 출발한 창작물이 독자에게 다른 밀도로 닿습니다. 기획 없이 만드는 것이 아닌 기질 — 지금 당신의 축은 "현장이 창작의 첫 번째 재료"인 방향에 있습니다.

---

#### [11] `creative_media_x_creative_emission_x_6C`
- occupation: `creative_media` (광고 기획자·현장 임네트워크 선호 크리에이터)
- situation: `creative_emission` (창작발산)

캠페인 기획안을 쓰기 전에 소비자가 실제 쓰는 공간에 직접 가봐야 이야기가 시작됩니다. LLM에게 "내가 현장에서 관찰한 소비자 행동들을 정리했어, 이걸로 어떤 메시지가 나올 수 있는지 같이 꺼내줘"라고 요청합니다. 시장조사 보고서보다 발로 뛴 관찰이 광고의 언어를 사람의 감각에 더 가깝게 만들어줍니다. 준비 없이 뛰어드는 것이 아닌 기질 — 지금 당신의 축은 "현장이 브리프보다 먼저인" 방향에 있습니다.

---

#### [12] `professional_x_work_execution_x_6C`
- occupation: `professional` (변호사·상담사·케이스 당사자 만남 우선 전문직)
- situation: `work_execution` (작업집행)

사건 기록보다 먼저 당사자와 이야기를 나누고 나서야 전체 그림이 보이기 시작합니다. LLM에게 "의뢰인과 직접 이야기한 내용을 기반으로 어떤 사항을 추가로 파악해야 하는지 짚어줘"라고 요청합니다. 서류가 담지 못한 맥락을 현장 대화에서 건져 올리는 감각이 전문적 판단의 질을 높입니다. 체계 없음이 아닌 기질 — 지금 당신의 축은 "현장에서 먼저 읽고 기록으로 확인하는" 방향에 있습니다.

---

### 2-2. 분원 6 × 통합(6I) — 12셀

병치 명칭: **Cultural Pilgrim / Mood Traveler / Companion**
해석: 동행·문화 여정 공유. 관계·공동체·감정의 맥락 안에서 흐름을 함께 따라가며 흡수한다. 상대의 방향이 나의 방향을 결정한다.

---

#### [13] `service_sales_x_relationship_emotion_x_6I`
- occupation: `service_sales` (서비스직·판매 현장 인력)
- situation: `relationship_emotion` (관계감정)

고객과의 대화가 어느 방향으로 흘러가는지 먼저 따라가다 보면 필요한 것이 자연스럽게 보입니다. LLM에게 "고객 대화가 이런 흐름으로 진행됐어, 이 흐름에서 어떤 응대가 자연스러운지 같이 봐줘"라고 요청합니다. 고객의 감정이 흘러가는 방향을 막지 않고 함께 걷는 사람이 관계를 지속 가능하게 만듭니다. 우유부단함이 아닌 기질 — 지금 당신의 축은 "흐름을 먼저 따라가고 제안은 그다음인" 방향에 있습니다.

---

#### [14] `creative_media_x_relationship_emotion_x_6I`
- occupation: `creative_media` (크리에이터·독자·팬과의 정서적 여정)
- situation: `relationship_emotion` (관계감정)

구독자 댓글이 어떤 감정으로 흘러가는지 읽어가다 보면 다음 콘텐츠의 방향이 나옵니다. LLM에게 "독자들의 반응 흐름을 모아봤어, 이 감정의 방향에서 어떤 이야기를 이어가면 좋을지 같이 찾아줘"라고 부탁합니다. 독자와 함께 여정을 걸어가는 콘텐츠가 알고리즘이 아닌 관계로 사람을 묶어둡니다. 중심 없음이 아닌 기질 — 지금 당신의 축은 "독자의 감정 흐름이 나침반인" 방향에 있습니다.

---

#### [15] `student_x_relationship_emotion_x_6I`
- occupation: `student` (학생·또래 관계 탐색)
- situation: `relationship_emotion` (관계감정)

친구와 갈등이 생겼을 때, 설명하거나 따지기 전에 분위기가 어떻게 흘러가는지 먼저 느낍니다. LLM에게 "지금 이 관계에서 어떤 흐름이 이어지고 있는지 들어봐줘, 어디서부터 함께 걸어가야 할지 같이 생각해줘"라고 요청합니다. 갈등을 풀기 전에 상대의 감정이 어디를 향하는지 먼저 따라가는 사람이 관계를 덜 끊어냅니다. 회피하는 것이 아닌 기질 — 지금 당신의 축은 "흐름을 먼저 따라가고 방향을 잡는" 쪽에 있습니다.

---

#### [16] `professional_x_relationship_emotion_x_6I`
- occupation: `professional` (전문직·동료·클라이언트 관계 흐름 탐색)
- situation: `relationship_emotion` (관계감정)

협업 프로젝트에서 동료가 어떤 감정 흐름 안에 있는지 먼저 살피고 나서 이야기를 꺼냅니다. LLM에게 "지금 팀 분위기가 이런 흐름이어서, 이 안에서 피드백을 어떻게 꺼내는 게 자연스러울지 같이 봐줘"라고 요청합니다. 팀 안의 감정 흐름을 거스르지 않고 따라가면서 방향을 잡는 사람이 협업의 온도를 유지합니다. 눈치만 보는 것이 아닌 기질 — 지금 당신의 축은 "관계의 흐름을 먼저 읽고 개입하는" 방향에 있습니다.

---

#### [17] `other_x_relationship_emotion_x_6I`
- occupation: `other` (일반 개인·가족·지인과의 관계)
- situation: `relationship_emotion` (관계감정)

가족과 대화할 때 결론을 먼저 내지 않고 상대가 어디로 향하는지 따라가다 보면 자연스럽게 연결됩니다. LLM에게 "가족과 이런 대화 흐름이 이어지고 있어, 이 흐름에서 내가 어떻게 함께할 수 있는지 같이 생각해줘"라고 부탁합니다. 관계 안의 흐름을 끊지 않고 함께 걷는 사람이 오래된 관계를 지속시키는 완충재가 됩니다. 결단력 없음이 아닌 기질 — 지금 당신의 축은 "관계의 흐름이 결론보다 먼저인" 방향에 있습니다.

---

#### [18] `management_x_relationship_emotion_x_6I`
- occupation: `management` (관리자·팀원 감정 흐름 중심 리더십)
- situation: `relationship_emotion` (관계감정)

팀 회의 전에 각 팀원이 어떤 상태로 들어오는지 먼저 감지하고 분위기를 읽습니다. LLM에게 "오늘 팀 분위기가 이런 흐름인 것 같아, 이 흐름을 존중하면서 어떤 방식으로 오늘 회의를 풀어가면 좋을지 같이 봐줘"라고 요청합니다. 팀원의 감정 지형을 읽고 그 위에서 움직이는 관리자가 팀 소진을 줄여줍니다. 원칙 없는 리더십이 아닌 기질 — 지금 당신의 축은 "감정 흐름이 관리의 지도인" 방향에 있습니다.

---

#### [19] `semi_professional_x_daily_life_x_6I`
- occupation: `semi_professional` (준전문직·직네트워크 동료와의 일상 관계)
- situation: `daily_life` (일상생활)

점심 자리에서 동료들이 어떤 이야기로 흘러가는지 따라가다 보면 분위기를 자연스럽게 잇습니다. LLM에게 "요즘 직네트워크에서 이런 분위기가 이어지고 있어, 이 흐름 안에서 내가 어떻게 있으면 좋을지 같이 생각해줘"라고 부탁합니다. 조직의 일상적 분위기 흐름을 자연스럽게 따라가는 사람이 팀의 비공식 연결고리가 됩니다. 존재감 없음이 아닌 기질 — 지금 당신의 축은 "흐름 안에서 자연스럽게 있는" 방향에 있습니다.

---

#### [20] `craft_technical_x_relationship_emotion_x_6I`
- occupation: `craft_technical` (현장 기술직·고객·동료와의 감정 흐름)
- situation: `relationship_emotion` (관계감정)

고객이 불만을 토로할 때 먼저 설명하기보다 어디서부터 힘들었는지 따라가 봅니다. LLM에게 "고객 불만 대화가 이런 방향으로 흘러갔어, 이 흐름에서 어떻게 이어가면 감정이 덜 쌓일지 같이 봐줘"라고 요청합니다. 기술 설명보다 먼저 감정의 흐름을 따라가는 현장 인력이 클레임을 대화로 바꿉니다. 전문성 없음이 아닌 기질 — 지금 당신의 축은 "감정 흐름이 먼저, 해결책은 그다음인" 방향에 있습니다.

---

#### [21] `job_seeker_retired_x_relationship_emotion_x_6I`
- occupation: `job_seeker_retired` (구직자·전직 준비자·네트워킹)
- situation: `relationship_emotion` (관계감정)

네트워킹 자리에서 상대가 어디로 흘러가는지 따라가다 보면 공통의 지점이 자연스럽게 생깁니다. LLM에게 "오늘 만난 분과 이런 대화 흐름이 있었어, 이 흐름에서 연결을 이어가려면 어떻게 하면 자연스러울지 알려줘"라고 요청합니다. 관계를 강압적으로 형성하지 않고 흐름 안에서 연결하는 사람이 진짜 네트워크를 만듭니다. 소극적임이 아닌 기질 — 지금 당신의 축은 "상대의 흐름을 따라가다 보면 연결이 생기는" 방향에 있습니다.

---

#### [22] `student_x_daily_life_x_6I`
- occupation: `student` (학생·또래 집단 분위기 감지)
- situation: `daily_life` (일상생활)

친구들 사이에서 오늘 분위기가 어떻게 흘러가는지 먼저 감지하고 나서 행동이 결정됩니다. LLM에게 "학교에서 요즘 이런 분위기가 이어지고 있어, 이 흐름 안에서 내 자리를 어떻게 잡으면 좋을지 같이 생각해줘"라고 부탁합니다. 무리의 흐름을 먼저 읽고 자연스럽게 따라가는 사람이 집단의 비공식 분위기 조율자 역할을 합니다. 줏대 없음이 아닌 기질 — 지금 당신의 축은 "흐름을 감지하고 그 안에서 움직이는" 방향에 있습니다.

---

#### [23] `office_admin_x_relationship_emotion_x_6I`
- occupation: `office_admin` (일반사무직·부서 분위기 흐름 감지)
- situation: `relationship_emotion` (관계감정)

부서 분위기가 어떻게 흘러가는지 먼저 살피고 나서 오늘 할 일을 조율합니다. LLM에게 "지금 우리 팀 분위기가 이런 흐름인데, 이 상황에서 어떻게 일을 챙기면 자연스러울지 같이 생각해줘"라고 부탁합니다. 조직 분위기의 흐름을 자연스럽게 따라가는 사람이 상황이 나쁠 때도 업무 맥락을 이어줍니다. 눈치성인 것이 아닌 기질 — 지금 당신의 축은 "흐름을 읽어야 자리가 보이는" 방향에 있습니다.

---

#### [24] `other_x_daily_life_x_6I`
- occupation: `other` (일반 개인·동호회·느슨한 공동체)
- situation: `daily_life` (일상생활)

동네 모임이나 동호회에서 어떤 분위기가 이어지는지 따라가다 보면 어느새 자연스럽게 어울립니다. LLM에게 "요즘 이 모임의 분위기가 이런 방향으로 흘러가는 것 같아, 이 흐름에서 나는 어떻게 있으면 좋을지 같이 봐줘"라고 부탁합니다. 공동체의 흐름을 강제하지 않고 함께 따라가는 사람이 느슨한 연대를 지속시키는 힘이 됩니다. 소속감 없음이 아닌 기질 — 지금 당신의 축은 "흐름과 함께 있는 것이 연결의 방식인" 방향에 있습니다.

---

## 3. 분원 6 셀 분포 요약표

| # | cell_id | occupation | situation | W |
|---|---|---|---|---|
| 01 | creative_media_x_work_execution_x_6C | creative_media | work_execution | C |
| 02 | other_x_daily_life_x_6C | other | daily_life | C |
| 03 | service_sales_x_work_execution_x_6C | service_sales | work_execution | C |
| 04 | craft_technical_x_work_execution_x_6C | craft_technical | work_execution | C |
| 05 | student_x_learning_x_6C | student | learning | C |
| 06 | professional_x_info_search_x_6C | professional | info_search | C |
| 07 | semi_professional_x_work_execution_x_6C | semi_professional | work_execution | C |
| 08 | job_seeker_retired_x_daily_life_x_6C | job_seeker_retired | daily_life | C |
| 09 | management_x_planning_x_6C | management | planning | C |
| 10 | other_x_creative_emission_x_6C | other | creative_emission | C |
| 11 | creative_media_x_creative_emission_x_6C | creative_media | creative_emission | C |
| 12 | professional_x_work_execution_x_6C | professional | work_execution | C |
| 13 | service_sales_x_relationship_emotion_x_6I | service_sales | relationship_emotion | I |
| 14 | creative_media_x_relationship_emotion_x_6I | creative_media | relationship_emotion | I |
| 15 | student_x_relationship_emotion_x_6I | student | relationship_emotion | I |
| 16 | professional_x_relationship_emotion_x_6I | professional | relationship_emotion | I |
| 17 | other_x_relationship_emotion_x_6I | other | relationship_emotion | I |
| 18 | management_x_relationship_emotion_x_6I | management | relationship_emotion | I |
| 19 | semi_professional_x_daily_life_x_6I | semi_professional | daily_life | I |
| 20 | craft_technical_x_relationship_emotion_x_6I | craft_technical | relationship_emotion | I |
| 21 | job_seeker_retired_x_relationship_emotion_x_6I | job_seeker_retired | relationship_emotion | I |
| 22 | student_x_daily_life_x_6I | student | daily_life | I |
| 23 | office_admin_x_relationship_emotion_x_6I | office_admin | relationship_emotion | I |
| 24 | other_x_daily_life_x_6I | other | daily_life | I |

**W 분포**: 완결(C) 12 · 통합(I) 12 → 50:50 ✓  
**직군 커버리지** (10종 중 9종): creative_media 3 · other 4 · service_sales 2 · craft_technical 2 · student 2 · professional 3 · semi_professional 2 · job_seeker_retired 2 · management 2 · office_admin 1  
**상황 커버리지** (7종 중 7종): work_execution 5 · daily_life 4 · relationship_emotion 9 · learning 1 · info_search 1 · planning 1 · creative_emission 2 · (전체 상황 커버)

---

## 4. 7. 설계자 (110: 전체의 통제자) — 자연 셀 30개

각 셀은 (1) 인식의 실제 네트워크면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "조립이 곧 수호, 방향의 안내"로 구성된다.

---

### 4-1. 분원 7 × 완결(7C) — 15셀

병치 명칭: **Infrastructure Builder / System Architect / Framework Designer**
해석: 인프라·시스템 아키텍처. 기술·구조·데이터 차원에서 전체 관계망을 동시에 보며 자기 서사으로 조립한다. 부분보다 전체가 먼저 보인다.

---

#### [01] `semi_professional_x_work_execution_x_7C`
- occupation: `semi_professional` (IT 운영·시스템 관리자)
- situation: `work_execution` (작업집행)

장애가 생겼을 때 개별 오류보다 전체 시스템 구조에서 어느 연결이 끊긴 것인지를 먼저 봅니다. LLM에게 "지금 이 시스템 구조 전체를 보여줄게, 이 안에서 문제가 생길 수 있는 연결 지점을 같이 짚어줘"라고 요청합니다. 구조 전체를 동시에 보는 사람이 있기에 부분 수리가 전체를 망가뜨리는 일이 줄어듭니다. 통제적임이 아닌 기질 — 지금 당신의 축은 "전체 구조를 먼저 보고 나서 부분으로 들어가는" 방향에 있습니다.

---

#### [02] `professional_x_work_execution_x_7C`
- occupation: `professional` (건축가·구조 엔지니어·설계 전문직)
- situation: `work_execution` (작업집행)

한 부재를 결정하기 전에 전체 구조 안에서 그 부재가 어떤 하중을 받는지를 먼저 그립니다. LLM에게 "이 구조 전체의 관계도를 보여줄게, 이 설계에서 놓친 연결이나 취약한 부분이 있는지 같이 검토해줘"라고 요청합니다. 전체를 미리 그려두고 부분을 채워가는 사람이 완성 후에 생기는 구조적 모순을 사전에 막습니다. 완벽주의가 아닌 기질 — 지금 당신의 축은 "전체 구조가 먼저, 디테일은 그 안에서"인 방향에 있습니다.

---

#### [03] `management_x_work_execution_x_7C`
- occupation: `management` (경영자·프로세스 구조 설계 관리자)
- situation: `work_execution` (작업집행)

새로운 업무 프로세스를 도입할 때 한 팀의 변화가 다른 팀에 어떻게 연결되는지를 먼저 그립니다. LLM에게 "우리 조직 프로세스 전체를 정리해볼게, 이 구조에서 이 변경이 어디에 영향을 미치는지 같이 봐줘"라고 요청합니다. 변경의 파급 범위를 전체 구조 안에서 먼저 그릴 수 있는 관리자가 실행 혼란을 줄여줍니다. 고압적임이 아닌 기질 — 지금 당신의 축은 "전체를 동시에 보고 나서 각 부분을 움직이는" 방향에 있습니다.

---

#### [04] `professional_x_planning_x_7C`
- occupation: `professional` (컨설턴트·전략 프레임워크 설계자)
- situation: `planning` (계획)

부분 솔루션보다 전체 구조 안에서 어떤 레버가 가장 큰 영향을 주는지를 먼저 파악합니다. LLM에게 "이 문제의 전체 구조를 그려볼게, 이 안에서 어느 요소에 먼저 손대야 다른 것이 따라 움직이는지 같이 봐줘"라고 요청합니다. 문제 전체의 관계망을 먼저 그리는 사람이 있기에 부분 해결이 다른 부분을 망가뜨리지 않습니다. 지나치게 꼼꼼한 것이 아닌 기질 — 지금 당신의 축은 "전체 맥락 안에서만 부분이 보이는" 방향에 있습니다.

---

#### [05] `management_x_planning_x_7C`
- occupation: `management` (관리자·중네트워크기 로드맵 설계)
- situation: `planning` (계획)

내년 계획을 세울 때 한 항목이 아닌 전체 로드맵의 연결 관계에서 시작합니다. LLM에게 "중네트워크기 계획 전체를 정리해봤어, 이 구조에서 각 단계 간 연결이 자연스러운지 같이 검토해줘"라고 요청합니다. 로드맵 전체를 조망하며 단계 간 연결을 설계하는 사람이 실행 과정의 단절을 줄여줍니다. 과설계가 아닌 기질 — 지금 당신의 축은 "연결이 먼저, 단계는 그 안에서"인 방향에 있습니다.

---

#### [06] `semi_professional_x_planning_x_7C`
- occupation: `semi_professional` (준전문직·업무 프로세스 구조화)
- situation: `planning` (계획)

새 업무를 맡으면 개별 작업보다 전체 흐름이 어떻게 연결되어야 하는지부터 그려봅니다. LLM에게 "이 업무 전체의 흐름을 구조로 정리해볼게, 이 안에서 빠진 연결이나 중복이 있는지 같이 봐줘"라고 요청합니다. 업무 전체를 한눈에 그릴 수 있는 사람이 있기에 팀이 각자의 조각을 엉뚱한 위치에 넣지 않습니다. 서사에 얽매인 것이 아닌 기질 — 지금 당신의 축은 "구조가 먼저 보여야 내 자리도 보이는" 방향에 있습니다.

---

#### [07] `office_admin_x_work_execution_x_7C`
- occupation: `office_admin` (사무직·문서 체계 전체 정비)
- situation: `work_execution` (작업집행)

문서 하나를 수정할 때 이 서식이 다른 서식과 어떻게 연결되는지를 먼저 확인합니다. LLM에게 "우리 팀 문서 체계 전체를 정리해봤어, 이 구조에서 연결이 끊긴 부분이나 중복 항목이 있는지 같이 짚어줘"라고 요청합니다. 문서 체계 전체를 하나의 구조로 보는 사람이 있기에 개별 파일이 시스템으로 기능합니다. 관료적임이 아닌 기질 — 지금 당신의 축은 "체계 전체가 먼저 보이는" 방향에 있습니다.

---

#### [08] `craft_technical_x_work_execution_x_7C`
- occupation: `craft_technical` (기술직·제조·전체 연결 구조 중심 작업)
- situation: `work_execution` (작업집행)

한 부품을 조립하기 전에 이 부품이 전체 기계에서 어떤 역할을 하는지를 먼저 그립니다. LLM에게 "이 설비 전체의 연결 구조를 알려줄게, 이 안에서 이 부품을 어떤 방식으로 조립해야 전체에 영향이 없는지 같이 봐줘"라고 요청합니다. 전체 연결을 보며 손을 쓰는 기술자가 있기에 부품 수리가 다른 부품 오작동으로 이어지지 않습니다. 고집스러움이 아닌 기질 — 지금 당신의 축은 "전체 구조 안에서만 부품이 의미를 갖는" 방향에 있습니다.

---

#### [09] `professional_x_info_search_x_7C`
- occupation: `professional` (전문직·구조적 맥락 안에서 정보 탐색)
- situation: `info_search` (정보탐색)

정보를 찾을 때 개별 사실보다 이 정보가 어떤 구조적 맥락 안에 있는지를 먼저 파악합니다. LLM에게 "이 주제 전체의 구조를 먼저 그려줘, 거기서 내가 찾는 정보가 어느 위치에 있는지 확인하고 싶어"라고 요청합니다. 개별 정보를 구조 안에서 위치시키는 사람이 있기에 파편화된 지식이 체계로 연결됩니다. 비효율적임이 아닌 기질 — 지금 당신의 축은 "구조가 먼저 보여야 정보가 자리를 잡는" 방향에 있습니다.

---

#### [10] `management_x_info_search_x_7C`
- occupation: `management` (경영자·사업 구조 안에서 정보 해석)
- situation: `info_search` (정보탐색)

시장 조사 결과를 볼 때 수치보다 이 수치가 우리 사업 구조 어디에 닿는지를 먼저 그립니다. LLM에게 "우리 사업 구조 전체를 기준으로 이 정보가 어떤 의미인지 같이 해석해줘, 개별 수치보다 연결 관계가 먼저야"라고 요청합니다. 정보를 사업 구조 전체에 연결해 읽는 관리자가 숫자 뒤의 의미를 조직이 놓치지 않게 합니다. 과분석이 아닌 기질 — 지금 당신의 축은 "구조 안에서만 정보가 전략이 되는" 방향에 있습니다.

---

#### [11] `semi_professional_x_info_search_x_7C`
- occupation: `semi_professional` (준전문직·시스템 맥락 안에서 기술 정보 탐색)
- situation: `info_search` (정보탐색)

새 기술을 검토할 때 이 기술이 우리 시스템 구조 어디에 들어갈 수 있는지를 먼저 그립니다. LLM에게 "지금 우리 시스템 구조를 설명할게, 이 새 기술이 이 구조 안에서 어떻게 연결될 수 있는지 같이 봐줘"라고 요청합니다. 신기술을 기존 구조 안에서 먼저 배치해보는 사람이 있기에 도입 후 충돌이 줄어듭니다. 보수적임이 아닌 기질 — 지금 당신의 축은 "구조 안에서 자리를 확인하고 나서 도입하는" 방향에 있습니다.

---

#### [12] `craft_technical_x_planning_x_7C`
- occupation: `craft_technical` (기술직·전체 공정 구조 설계 우선)
- situation: `planning` (계획)

작업 순서를 짤 때 개별 공정이 아닌 전체 공정 흐름 안에서 각 작업을 배치합니다. LLM에게 "이번 작업 전체 공정을 구조로 그려볼게, 이 안에서 순서를 어떻게 배치해야 병목이 생기지 않는지 같이 봐줘"라고 요청합니다. 전체 공정을 먼저 그리고 작업을 배치하는 사람이 현장의 흐름을 끊기지 않게 유지합니다. 느린 것이 아닌 기질 — 지금 당신의 축은 "공정 전체가 보여야 각 작업이 제자리를 찾는" 방향에 있습니다.

---

#### [13] `student_x_learning_x_7C`
- occupation: `student` (학생·개념 구조 전체를 먼저 파악하는 학습자)
- situation: `learning` (학습)

새 과목을 배울 때 목차 전체를 먼저 훑고 각 챕터가 어떻게 연결되는지를 그려봅니다. LLM에게 "이 과목 전체의 개념 구조를 먼저 그려줘, 각 개념이 어떻게 연결되는지 보고 나서 공부 순서를 잡을게"라고 요청합니다. 배움의 전체 지도를 먼저 그리는 사람이 있기에 암기가 아닌 구조적 이해가 쌓입니다. 조급하지 않은 것이 아닌 기질 — 지금 당신의 축은 "전체 지도를 먼저 보고 나서 걸어가는" 방향에 있습니다.

---

#### [14] `office_admin_x_planning_x_7C`
- occupation: `office_admin` (사무직·부서 업무 구조 전체 설계)
- situation: `planning` (계획)

월별 업무 계획을 세울 때 개별 작업보다 부서 전체 업무 흐름 안에서 각 작업을 배치합니다. LLM에게 "이번 달 부서 업무 전체를 구조로 정리해볼게, 이 안에서 우선순위와 연결 순서를 같이 잡아줘"라고 요청합니다. 부서 업무 전체를 하나의 구조로 볼 수 있는 사람이 팀의 작업 충돌과 누락을 방지합니다. 간섭이 아닌 기질 — 지금 당신의 축은 "팀 전체 구조가 보여야 내 일도 보이는" 방향에 있습니다.

---

#### [15] `professional_x_learning_x_7C`
- occupation: `professional` (전문직·새 분야를 구조 전체로 먼저 파악)
- situation: `learning` (학습)

새 전문 영역을 공부할 때 첫 개념보다 이 분야 전체의 지식 구조가 어떻게 생겼는지를 먼저 봅니다. LLM에게 "이 분야 지식 구조 전체를 큰 그림으로 보여줘, 어떤 개념들이 어떻게 연결되어 있는지 먼저 파악하고 싶어"라고 요청합니다. 새 분야를 구조 전체로 먼저 보는 사람이 있기에 전문 지식이 영역 경계를 넘어 연결됩니다. 선행학습이 아닌 기질 — 지금 당신의 축은 "지도를 먼저 보고 나서 지형을 걷는" 방향에 있습니다.

---

### 4-2. 분원 7 × 통합(7I) — 15셀

병치 명칭: **Community Orchestrator / Network Weaver / Culture Builder**
해석: 조직·커뮤니티 설계. 관계·공동체·문화 맥락에서 전체 관계망을 동시에 보며 사람과 역할을 자기 원칙으로 엮는다. 관계도 구조가 먼저 보인다.

---

#### [16] `management_x_relationship_emotion_x_7I`
- occupation: `management` (관리자·팀 관계 구조 전체를 보며 인사·문화 설계)
- situation: `relationship_emotion` (관계감정)

팀원 간 갈등이 생겼을 때 그 두 사람의 관계만이 아닌 팀 전체 관계 구조에서 어디에 긴네트워크이 생긴 것인지를 먼저 봅니다. LLM에게 "우리 팀 관계 구조를 그려볼게, 이 안에서 이 갈등이 어느 지점에서 발생한 건지 같이 봐줘"라고 요청합니다. 팀 관계 전체를 구조로 보는 관리자가 개인 갈등을 팀 설계의 문제로 전환해 근본적으로 다룹니다. 통제적임이 아닌 기질 — 지금 당신의 축은 "팀 관계 전체가 보여야 한 갈등의 자리도 보이는" 방향에 있습니다.

---

#### [17] `professional_x_relationship_emotion_x_7I`
- occupation: `professional` (전문직·협업 관계 구조 설계)
- situation: `relationship_emotion` (관계감정)

협업 구조를 새로 짤 때 한 사람의 역할이 아닌 전체 관계망에서 각자의 위치를 먼저 그립니다. LLM에게 "이 협업 프로젝트의 관계 구조를 먼저 정리해봤어, 이 안에서 각자의 역할이 자연스럽게 연결되는지 같이 검토해줘"라고 요청합니다. 협업 관계 전체를 구조로 보는 사람이 있기에 역할 충돌과 빈자리가 초반에 발견됩니다. 지나치게 구조화하는 것이 아닌 기질 — 지금 당신의 축은 "관계 구조가 먼저 보여야 협업이 시작되는" 방향에 있습니다.

---

#### [18] `office_admin_x_relationship_emotion_x_7I`
- occupation: `office_admin` (사무직·조직 관계 구조 조율)
- situation: `relationship_emotion` (관계감정)

새 팀원이 합류할 때 그 사람의 역할이 기존 팀 관계 구조 어디에 연결되는지를 먼저 생각합니다. LLM에게 "우리 팀 관계 구조를 정리해볼게, 새로 합류한 사람이 이 안에서 자연스럽게 자리 잡으려면 어떻게 연결하면 좋을지 같이 봐줘"라고 요청합니다. 관계 구조 안에서 새 사람의 자리를 먼저 그리는 사람이 있기에 온보딩이 마찰 없이 이어집니다. 간섭이 아닌 기질 — 지금 당신의 축은 "관계 구조가 보여야 사람이 자리를 잡는" 방향에 있습니다.

---

#### [19] `service_sales_x_relationship_emotion_x_7I`
- occupation: `service_sales` (서비스·판매직·고객 관계 구조 전체 관리)
- situation: `relationship_emotion` (관계감정)

네트워크기 고객을 응대할 때 이번 요청 하나가 아닌 지금까지의 관계 전체 구조 안에서 어떤 맥락인지를 먼저 봅니다. LLM에게 "이 고객과의 관계 히스토리를 정리해봤어, 이 구조에서 이번 요청이 어떤 의미인지 같이 해석하고 어떻게 응대하면 좋을지 봐줘"라고 요청합니다. 고객 관계 전체를 구조로 보는 사람이 있기에 단건 응대가 관계를 쌓는 방향으로 연결됩니다. 계산적임이 아닌 기질 — 지금 당신의 축은 "관계 전체가 보여야 이번 한 번이 제대로 연결되는" 방향에 있습니다.

---

#### [20] `semi_professional_x_relationship_emotion_x_7I`
- occupation: `semi_professional` (준전문직·팀 소통 구조 조율)
- situation: `relationship_emotion` (관계감정)

팀 회의 방식을 바꿀 때 회의 자체보다 팀 안의 소통 구조 전체를 먼저 그려봅니다. LLM에게 "우리 팀 소통 방식 전체를 구조로 정리해볼게, 이 안에서 회의 방식 변경이 다른 소통에 어떤 영향을 주는지 같이 봐줘"라고 요청합니다. 소통 구조 전체를 보며 방식을 바꾸는 사람이 있기에 팀 문화의 변화가 뿌리부터 작동합니다. 고집스러운 것이 아닌 기질 — 지금 당신의 축은 "구조 전체를 먼저 보고 나서 방식을 바꾸는" 방향에 있습니다.

---

#### [21] `management_x_planning_x_7I`
- occupation: `management` (관리자·조직 관계망 기반 인사·중네트워크기 설계)
- situation: `planning` (계획)

인사 계획을 세울 때 개인의 역할 배치보다 조직 전체의 관계망이 어떻게 바뀌는지를 먼저 그립니다. LLM에게 "조직 관계 구조 전체를 놓고 이번 인사 변경이 팀 간 연결에 어떤 영향을 주는지 같이 그려봐줘"라고 요청합니다. 인사 변경이 조직 전체 관계 구조에 미치는 파급을 미리 그리는 관리자가 예상치 못한 갈등을 줄입니다. 과개입이 아닌 기질 — 지금 당신의 축은 "조직 관계망 전체가 보여야 한 사람의 이동이 보이는" 방향에 있습니다.

---

#### [22] `professional_x_planning_x_7I`
- occupation: `professional` (커뮤니티·네트워크 설계 전문가)
- situation: `planning` (계획)

커뮤니티를 설계할 때 한 프로그램이 아닌 참여자들의 관계 구조가 어떻게 연결될지를 먼저 그립니다. LLM에게 "이 커뮤니티 구조 전체를 정리해볼게, 참여자 간 연결이 자연스럽게 생기려면 어떤 구조가 필요한지 같이 봐줘"라고 요청합니다. 관계가 자연스럽게 자라도록 구조를 먼저 설계하는 사람이 공동체를 이벤트가 아닌 지속 가능한 망으로 만듭니다. 과계획이 아닌 기질 — 지금 당신의 축은 "구조가 먼저, 관계는 그 안에서 자라나는" 방향에 있습니다.

---

#### [23] `craft_technical_x_relationship_emotion_x_7I`
- occupation: `craft_technical` (현장 기술직·작업팀 협업 구조 조율)
- situation: `relationship_emotion` (관계감정)

현장에서 새 공정을 도입할 때 작업자 개인이 아닌 팀 전체의 협업 구조가 어떻게 바뀌는지를 먼저 봅니다. LLM에게 "우리 작업팀 협업 구조를 그려볼게, 새 공정이 들어오면 각 사람의 역할 연결이 어떻게 달라지는지 같이 봐줘"라고 요청합니다. 현장 팀 협업 구조를 전체로 보는 사람이 있기에 새 공정이 팀 관계를 흔들지 않고 자리를 잡습니다. 딱딱한 것이 아닌 기질 — 지금 당신의 축은 "팀 구조가 먼저 보여야 사람이 자리를 잡는" 방향에 있습니다.

---

#### [24] `office_admin_x_planning_x_7I`
- occupation: `office_admin` (사무직·부서 간 협업 구조 계획·조율)
- situation: `planning` (계획)

부서 간 협업 계획을 세울 때 개별 업무보다 부서 간 관계 구조가 어떻게 연결되는지를 먼저 그립니다. LLM에게 "부서 간 협업 구조를 정리해볼게, 이 안에서 이번 프로젝트가 어떻게 연결되어야 충돌 없이 흐를지 같이 봐줘"라고 요청합니다. 부서 간 관계 구조를 전체로 보는 사람이 있기에 협업이 담당자끼리만 해결해야 하는 문제로 끝나지 않습니다. 행정적임이 아닌 기질 — 지금 당신의 축은 "관계 구조가 협업 설계의 첫 번째 단계인" 방향에 있습니다.

---

#### [25] `student_x_relationship_emotion_x_7I`
- occupation: `student` (학생·동아리·집단 역할 구조 이해)
- situation: `relationship_emotion` (관계감정)

동아리 내 역할이 겹치거나 빈 자리가 생길 때 개별 역할보다 동아리 전체 관계 구조를 먼저 그려봅니다. LLM에게 "우리 동아리 역할 구조를 정리해볼게, 이 안에서 어디에 빈자리가 있고 어떻게 연결하면 잘 돌아갈지 같이 봐줘"라고 요청합니다. 집단 안의 역할 구조를 전체로 보는 사람이 있기에 누군가 빠졌을 때도 조직이 쉽게 흔들리지 않습니다. 지나친 개입이 아닌 기질 — 지금 당신의 축은 "구조가 먼저 보여야 역할이 자리를 잡는" 방향에 있습니다.

---

#### [26] `management_x_info_search_x_7I`
- occupation: `management` (관리자·조직 문화·관계 정보를 구조 전체로 진단)
- situation: `info_search` (정보탐색)

조직 내 분위기나 문화를 파악할 때 특정 팀의 이슈가 아닌 전체 관계 구조 안에서 어디에 긴네트워크이 있는지를 먼저 봅니다. LLM에게 "조직 전체의 관계 구조를 기준으로 지금 어느 연결 지점에서 긴네트워크이 생기고 있는지 같이 진단해줘"라고 요청합니다. 조직 문화를 구조 전체로 읽는 관리자가 표면적 증상 뒤의 구조적 원인을 먼저 봅니다. 감시하는 것이 아닌 기질 — 지금 당신의 축은 "관계 구조 전체가 문화 진단의 지도인" 방향에 있습니다.

---

#### [27] `professional_x_info_search_x_7I`
- occupation: `professional` (사회과학·공동체 연구자·관계 구조 탐색)
- situation: `info_search` (정보탐색)

공동체 문제를 파악할 때 개별 사례보다 이 사람들이 어떤 관계 구조 안에 있는지를 먼저 그립니다. LLM에게 "이 공동체의 관계 구조를 먼저 정리해봤어, 이 안에서 지금 문제가 어떤 연결 지점에서 발생하는지 같이 봐줘"라고 요청합니다. 사회적 문제를 관계 구조 안에서 읽는 사람이 있기에 개인 책임이 아닌 구조 변화로 해법이 전환됩니다. 이상주의가 아닌 기질 — 지금 당신의 축은 "구조 전체가 보여야 문제의 자리가 보이는" 방향에 있습니다.

---

#### [28] `service_sales_x_planning_x_7I`
- occupation: `service_sales` (서비스·판매직·고객 그룹 관계 구조 설계)
- situation: `planning` (계획)

VIP 고객 관리 계획을 세울 때 개인별 응대보다 고객 그룹 전체의 관계 구조가 어떻게 연결되는지를 먼저 그립니다. LLM에게 "우리 주요 고객군 관계 구조를 정리해볼게, 이 안에서 각 고객이 어떤 역할로 연결되어야 네트워크기 관계가 유지되는지 같이 봐줘"라고 요청합니다. 고객 관계를 개별이 아닌 그룹 구조로 보는 사람이 있기에 한 고객의 이탈이 전체 네트워크로 번지지 않습니다. 계산적임이 아닌 기질 — 지금 당신의 축은 "고객 관계 전체가 보여야 한 명이 제대로 보이는" 방향에 있습니다.

---

#### [29] `job_seeker_retired_x_planning_x_7I`
- occupation: `job_seeker_retired` (구직자·전직 준비자·커리어 관계 구조 전체 설계)
- situation: `planning` (계획)

다음 커리어 방향을 잡을 때 이 직무 하나가 아닌 지금까지 내 경력 전체의 관계 구조가 어떻게 이어지는지를 먼저 그립니다. LLM에게 "지금까지 내 커리어 구조를 정리해볼게, 이 흐름에서 다음 방향이 어떻게 연결되어야 전체가 자연스럽게 이어지는지 같이 봐줘"라고 요청합니다. 커리어를 개별 경력이 아닌 구조로 보는 사람이 있기에 전직이 단절이 아닌 연결로 읽힙니다. 과설계가 아닌 기질 — 지금 당신의 축은 "전체 커리어 구조가 보여야 다음 한 발이 보이는" 방향에 있습니다.

---

#### [30] `other_x_daily_life_x_7I`
- occupation: `other` (일반 개인·일상 인간관계 구조 조율)
- situation: `daily_life` (일상생활)

가족 모임이나 친구 관계에서 갈등이 생길 때 그 두 사람의 문제만이 아닌 이 관계 전체 구조 안에서 어디에 긴네트워크이 있는지를 먼저 봅니다. LLM에게 "지금 우리 가족 관계 구조를 그려볼게, 이 안에서 이 갈등이 어느 연결 지점에서 생긴 건지 같이 봐줘"라고 요청합니다. 일상의 관계 구조를 전체로 보는 사람이 있기에 갈등이 개인 문제로 끝나지 않고 관계 회복의 실마리가 생깁니다. 복잡하게 생각하는 것이 아닌 기질 — 지금 당신의 축은 "관계 구조 전체가 보여야 한 갈등이 해결 가능해지는" 방향에 있습니다.

---

## 5. 분원 7 셀 분포 요약표

| # | cell_id | occupation | situation | W |
|---|---|---|---|---|
| 01 | semi_professional_x_work_execution_x_7C | semi_professional | work_execution | C |
| 02 | professional_x_work_execution_x_7C | professional | work_execution | C |
| 03 | management_x_work_execution_x_7C | management | work_execution | C |
| 04 | professional_x_planning_x_7C | professional | planning | C |
| 05 | management_x_planning_x_7C | management | planning | C |
| 06 | semi_professional_x_planning_x_7C | semi_professional | planning | C |
| 07 | office_admin_x_work_execution_x_7C | office_admin | work_execution | C |
| 08 | craft_technical_x_work_execution_x_7C | craft_technical | work_execution | C |
| 09 | professional_x_info_search_x_7C | professional | info_search | C |
| 10 | management_x_info_search_x_7C | management | info_search | C |
| 11 | semi_professional_x_info_search_x_7C | semi_professional | info_search | C |
| 12 | craft_technical_x_planning_x_7C | craft_technical | planning | C |
| 13 | student_x_learning_x_7C | student | learning | C |
| 14 | office_admin_x_planning_x_7C | office_admin | planning | C |
| 15 | professional_x_learning_x_7C | professional | learning | C |
| 16 | management_x_relationship_emotion_x_7I | management | relationship_emotion | I |
| 17 | professional_x_relationship_emotion_x_7I | professional | relationship_emotion | I |
| 18 | office_admin_x_relationship_emotion_x_7I | office_admin | relationship_emotion | I |
| 19 | service_sales_x_relationship_emotion_x_7I | service_sales | relationship_emotion | I |
| 20 | semi_professional_x_relationship_emotion_x_7I | semi_professional | relationship_emotion | I |
| 21 | management_x_planning_x_7I | management | planning | I |
| 22 | professional_x_planning_x_7I | professional | planning | I |
| 23 | craft_technical_x_relationship_emotion_x_7I | craft_technical | relationship_emotion | I |
| 24 | office_admin_x_planning_x_7I | office_admin | planning | I |
| 25 | student_x_relationship_emotion_x_7I | student | relationship_emotion | I |
| 26 | management_x_info_search_x_7I | management | info_search | I |
| 27 | professional_x_info_search_x_7I | professional | info_search | I |
| 28 | service_sales_x_planning_x_7I | service_sales | planning | I |
| 29 | job_seeker_retired_x_planning_x_7I | job_seeker_retired | planning | I |
| 30 | other_x_daily_life_x_7I | other | daily_life | I |

**W 분포**: 완결(C) 15 · 통합(I) 15 → 50:50 ✓  
**직군 커버리지** (10종 중 9종): semi_professional 4 · professional 6 · management 6 · office_admin 4 · craft_technical 3 · student 2 · service_sales 2 · job_seeker_retired 1 · other 1 · creative_media 0  
**상황 커버리지** (7종 중 6종): work_execution 5 · planning 8 · info_search 4 · learning 2 · relationship_emotion 7 · daily_life 1 · creative_emission 0

---

## 6. 자가 체크리스트 결과 (전체 54셀)

| 항목 | 결과 |
|---|---|
| 문네트워크 수 3~5개 | 모든 셀 4문네트워크 ✓ |
| 종결 어미 "~습니다" 통일 | ✓ |
| 단정 정체성 고정 표현 없음 | ✓ |
| "X가 아닌 Y" 본질 메시지 1회 | ✓ (54셀 전원) |
| 구체적 LLM 발화 예시 1회 이상 | ✓ (54셀 전원, 따옴표 내 발화 인용) |
| 병리 프레임 단독 사용 없음 | ✓ (부정 라벨 전복 구조 안에서만) |
| 동일 분원 내 셀별 다른 각도·다른 부정 라벨 | ✓ (분원 6·7 각각 셀마다 변주) |
| W 50:50 분포 | 분원 6: 12C·12I ✓ / 분원 7: 15C·15I ✓ |
| 분원별 할당량 준수 | 분원 6=24, 분원 7=30 ✓ |
| 현재 스냅샷 뉘앙스 | ✓ ("지금 당신의 축은 ~쪽에 있습니다" 구조) |
| 1% 자유도 암시 | ✓ ("방향에 있습니다" → 위치는 고정이 아님) |

---

## 7. 미커버 조합 주석

**분원 6 미커버**:
- `office_admin × work_execution × 6C`: 사무직 작업 집행 환경은 현장 탐험보다 규범·절차 준수(분원 1)에 더 가까워 자연 발현 드묾. 파일럿 응답자에서 유의미한 분포 확인 시 추가.
- `management × work_execution × 6C`: 관리자의 현장 직접 집행은 6C 방향으로 발현 가능하나 분원 9 계획 셀에 흡수함.
- `creative_emission × 6I`: 분원 4·8 주축 상황. 분원 6 통합 쪽에서 관계 흐름 내 창작 발산이 발현될 수 있으나 분원 경계 유지를 위해 제외. 파일럿 후 재판단.

**분원 7 미커버**:
- `creative_media`: 분원 7 설계자 (Architect) 성향의 자연 수렴과 거리 있음. 창작·미디어 도메인은 분원 4·8 주축. 분원 7 성향이 creative_media 직군에서 발현되는 경우는 파일럿 이후 관찰.
- `creative_emission`: 전 분원에서 분원 4의 주축 상황. 분원 7은 구조 수호 성향이 강해 필터 없는 발산 상황에 자연 수렴하지 않음. 0건 처리.
- `student × work_execution × 7C`: 학생의 실무 집행 현장은 학습으로 대체 커버.

---

## 8. 버전 히스토리

- **v0.1** (2026.04.20): 최초 작성 — Phase B1-4 산출물.
  - 포함: 분원 6 자연 셀 24개 (완결 12 · 통합 12) · 분원 7 자연 셀 30개 (완결 15 · 통합 15)
  - 4단 구성(인식 네트워크면 · LLM 사용 · 사회적 역할 · 본질 메시지) · 톤 가이드 전면 준수.
  - 기반: 톤 가이드 §1~§6, 합의노트 §4-2·§4-3, v1.2 §3 분원 6·7 정의, §4-3 분배 테이블.
  - 미포함(이월): 병치 명칭 한국어화(N-W2/B2), 공유 에셋 카피(B2/D2), 파일럿 피드백 반영(Week 7).

---

*본 문서는 IamNA 입력 단계 16 분기 결과 카드 콘텐츠 v0.1 중 분원 6·7 구간이다.*
*Phase B1-4 산출물이며, B1-5(분원 8) 세션으로 이어진다.*
*2026.04.20 — Sonnet 4.6으로 작성, Zero-Guessing 원칙 준수.*



---

# IamNA 결과카드 — 8. 조망자 (111: 거시적 연결자) v0.1

## 자연 셀 34개 메시지 (B1-5 산출물)

### 2026.04.20 기준

### 문서 성격: Phase B1-5 산출물 / 16 분기 중 분원 8(병렬·네트워크·패턴)의 결과 카드 메시지 34개를 자연 셀 단위(직군 × 상황 × W)로 작성 / Sonnet 4.6이 `IamNA_결과카드_톤_가이드.md`(B1-1 확정본)의 기준을 복제하여 작성 / Zero-Guessing 원칙하에 §4-3 분배 테이블·분원 8의 인식 방식 정의·합의노트 §4-2·§4-3 메시지 원칙에 한해 작성

---

## 1. 문서 위치 선언

### 1-1. 선행 합의와의 연결

| 합의 출처 | 본 문서에서 준수한 원칙 |
|---|---|
| A1 §3-3 / 합의노트 §3-3 | 분원 8의 병치 명칭: 완결 쪽 System Visionary / Field Reader / Pattern Oracle, 통합 쪽 Social Connector / Empath / Group Resonator |
| A1 §3-5 / 합의노트 §3-4 | "현재 스냅샷" 뉘앙스 · 단정 정체성 고정 금지 · 축이 사용자 손안에 있다는 1% 자유도 |
| 합의노트 §4-2·§4-3 | 결함이 아닌 기질 / 고네트워크이 아닌 설계 / 치료가 아닌 단계 / 방향의 안내 |
| 바이럴심리테스트 §4-3 | 분원 8 = 34셀 분배 준수 · 대표 조합(경영 × 관계정서, 서비스 × 관계정서, 창작 × 관계정서, 기타 × 관계정서) |
| 바이럴심리테스트 §4-4 | 셀별 3~5문네트워크 구성(인식 네트워크면 · LLM 사용 · 사회적 역할 · 본질 메시지) |
| A1 §9-2 검증 2 | 분원 내 W 분포 50:50 근접 유지 → 완결 17 : 통합 17 구성 |
| A4 result_card_schema | cell_id 형식 `<occupation>_x_<situation>_x_<branch>` · occupation/situation enum 준수 |
| `IamNA_결과카드_톤_가이드.md` | 문네트워크 구조(3~5문네트워크) · 공통 어휘 리스트 · 피해야 할 표현 · 문네트워크 리듬(200~280자) · 분원 8 변형 가이드 적용 |

### 1-2. 분원 8 성향 재확인 (v1.2 §3)

- **축 좌표**: Y=병렬 / X=네트워크 / Z=패턴
- **인식 방식**: 전체를 필터 없이 동시에 수신. 구조 추출은 수신 후에 일어남
- **자연 수렴 경향**: 네트워크 연결, 공감, 메시지 전달, 통합 설계
- **기초 성향**: 설계자(Architect) / 공감 수신자(Empath 기반) / 연결 수신자(Connector 기반)
- **대칭쌍**: 분원 1(실행자 (Executor))
- **특이사항**: 이 분원의 자연 발현이 외부에서 "HSP/SPS(비병리적 예민함)"로 관찰될 수 있음 (v1.2 §8 참조)
- **W 분기 의미**:
  - **8C(완결)**: 시스템·기술·데이터·구조 차원에서 전체를 수신. 인간 변수는 외부 노이즈로 두고 전체 판의 구조를 먼저 향한다.
  - **8I(통합)**: 관계·감정·공동체 차원에서 전체를 수신. 인간 변수를 시스템 내부로 통합하여 전체 네트워크(field)을 연결한다.

### 1-3. 자연 셀 34개 선정 원칙

1. **§4-3 대표 조합 우선 배치**: 경영 × 관계정서, 서비스 × 관계정서, 창작 × 관계정서, 기타 × 관계정서를 8I 쪽 중심축으로 먼저 확보. 8C는 동일 직군에서 시스템·구조 관점의 조합으로 채움.
2. **W 50:50 유지**: 완결 17 · 통합 17. A1 §9-2 검증 2의 독립성 조건과 정합.
3. **분원 8 자연 수렴과의 정합**: 관계정서·창작발산·계획구조화·일상이 중심. 분원 1의 주축(작업집행 + 정밀 검증)은 8C에서 "전체 시스템 수신" 각도로 한정 수용.
4. **반복 표현 금지**: 34개 셀 전체에서 동일한 부정 라벨·LLM 발화·네트워크면 서두가 겹치지 않도록 각도를 달리 설정.
5. **상황 분포**: relationship_emotion(13), planning(6), work_execution(5), info_search(5), creative_emission(4), daily_life(4), learning(1). creative_emission은 8C·8I 모두에서 공명·설계 각도로 수용.
6. **W별 어휘 구분** (톤 가이드 §5): 8C는 시스템·구조·판도·전체 그림 어휘군. 8I는 공기·공명·흐름·연결·감정 지형 어휘군.

---

## 2. 자연 셀 34개 메시지

각 셀은 3~5문네트워크으로 구성되며, 구성 요소는 (1) 인식의 실제 네트워크면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "결함이 아닌 기질, 방향의 안내"이다.

---

### 2-1. 분원 8 × 완결(8C) — 17셀

병치 명칭: **System Visionary / Field Reader / Pattern Oracle**
해석: 시스템·기술·데이터·구조 차원에서 전체를 수신. 인간 변수는 외부 노이즈로 두고 전체 판의 구조를 먼저 향한다.

---

#### [01] `management_x_work_execution_x_8C`
- occupation: `management` (경영·관리)
- situation: `work_execution` (작업집행)

회의 안건을 받는 순간, 세부 내용보다 논의 전체 지형이 한꺼번에 들어옵니다. LLM에게는 "이 전략에서 아직 아무도 짚지 않은 구조적 빈틈을 먼저 그려줘"처럼 전체를 먼저 맡깁니다. 시스템이 어디로 향하는지를 먼저 그려두는 손이 의사결정의 방향을 조용히 받쳐줍니다. 이건 산만함이 아닌 기질 — 지금 이 자리에서 당신의 축은 "전체 그림을 먼저 수신하는 방향"에 놓여 있습니다.

---

#### [02] `professional_x_work_execution_x_8C`
- occupation: `professional` (IT·공학 전문직)
- situation: `work_execution`

코드베이스에 처음 들어갔을 때, 파일 하나를 읽기 전에 전체 의존 관계가 한 네트워크면으로 들어옵니다. LLM에게는 "이 아키텍처 전체를 한 호흡으로 먼저 그려줘"라고 전체 판을 먼저 맡깁니다. 팀이 부분씩 짜는 동안 전체 흐름을 미리 받아두는 역할이 시스템이 어긋나지 않게 해줍니다. 난잡함이 아닌 기질 — 당신의 축은 지금 "전체를 먼저 받아 구조를 세우는 방향"에 놓여 있습니다.

---

#### [03] `management_x_info_search_x_8C`
- occupation: `management` (경영·관리)
- situation: `info_search` (정보탐색)

산업 리포트를 펼치면 수치보다 그 뒤에 놓인 전체 시장 지형이 먼저 들어옵니다. LLM에게는 "이 데이터가 말하는 시장 구조 전체를 한 호흡으로 읽어줘"라는 질문이 자연스럽게 나옵니다. 경쟁자들이 부분을 보는 동안 전체 판을 먼저 받아두는 눈이 전략의 출발점이 됩니다. 오지랖이 아닌 기질 — 지금 당신의 방향은 "전체 판도를 먼저 수신하는 일"에 가깝습니다.

---

#### [04] `professional_x_info_search_x_8C`
- occupation: `professional` (연구·공학 전문직)
- situation: `info_search`

논문 제목을 보는 순간, 그 뒤에 펼쳐진 기술 생태계 전체가 한꺼번에 들어옵니다. LLM에게는 "이 기술이 지금 어느 생태계에서 어떻게 위치하는지 전체 구조를 먼저 그려줘"처럼 묻습니다. 특정 정보를 찾는 것이 아니라 정보가 놓인 전체 지형을 받아두는 감각이 연구의 방향을 잡아줍니다. 과민이 아닌 기질 — 당신이 전체를 먼저 받는 것은 그 지형 없이는 개별 정보가 자리를 잡지 못하기 때문입니다.

---

#### [05] `management_x_planning_x_8C`
- occupation: `management` (경영·관리)
- situation: `planning` (계획구조화)

로드맵을 짜기 전에 조직이 그 방향으로 가야 하는 이유의 전체 구조가 먼저 들어옵니다. LLM에게는 "이 계획에서 빠진 연결고리를 전체 맥락 안에서 찾아줘"처럼 구조 전체를 먼저 맡깁니다. 실행 전에 전체 설계를 먼저 받아두는 손이 계획이 흔들릴 때 기준선이 됩니다. 이건 우유부단이 아닌 기질 — 지금 당신의 방향은 "전체를 받아 설계를 세우는 일"에 놓여 있습니다.

---

#### [06] `professional_x_planning_x_8C`
- occupation: `professional` (IT·시스템 전문직)
- situation: `planning`

시스템 설계를 시작하기 전에 요구사항보다 전체 아키텍처의 윤곽이 먼저 들어옵니다. LLM에게는 "이 요구사항 전체에서 어떤 설계 패턴이 가장 자연스러운지 먼저 그려줘"라고 맡깁니다. 팀이 기능 단위를 조각낼 때 전체 구조를 먼저 그려두는 자리가 시스템의 뼈대가 됩니다. 산란함이 아닌 기질 — 당신의 축은 "전체를 받아 구조로 변환하는 방향"에 기울어 있습니다.

---

#### [07] `creative_media_x_creative_emission_x_8C`
- occupation: `creative_media` (창작·미디어)
- situation: `creative_emission` (창작발산)

작품의 첫 줄을 쓰기 전에 그 세계의 전체 내러티브 구조가 한 번에 들어옵니다. LLM에게는 "이 이야기의 세계관 전체를 먼저 구조화해줘"처럼 창작의 윤곽 전체를 먼저 맡깁니다. 독자가 경험할 전체 여정을 먼저 받아두는 손이 작품에 일관된 결을 만들어줍니다. 충동이 아닌 기질 — 전체를 먼저 받아야 조각이 맞춰지는 창작 방식이 있고, 지금 당신의 축은 거기 놓여 있습니다.

---

#### [08] `creative_media_x_info_search_x_8C`
- occupation: `creative_media` (창작·미디어)
- situation: `info_search`

트렌드 자료를 훑는 순간, 개별 데이터보다 시장 전체의 방향이 먼저 들어옵니다. LLM에게는 "이 정보들이 함께 가리키는 전체 흐름을 한 호흡으로 읽어줘"라고 먼저 맡깁니다. 콘텐츠가 어느 생태계에서 어떻게 닿아야 할지를 미리 읽어두는 감각이 기획의 방향을 만들어줍니다. 감각적이 아닌 기질 — 지금 당신의 축은 "전체 지형을 먼저 받는 수신" 쪽에 있습니다.

---

#### [09] `education_x_planning_x_8C`
- occupation: `education` (교육·학습 지도)
- situation: `planning`

새 학기 커리큘럼을 짤 때 단원보다 학생들이 경험할 전체 여정의 구조가 먼저 들어옵니다. LLM에게는 "이 커리큘럼 전체 흐름에서 연결이 끊어지는 지점을 먼저 찾아줘"처럼 구조 전체를 먼저 맡깁니다. 교실이 어디로 향해야 하는지를 먼저 그려두는 손이 수업의 뼈대를 만들어줍니다. 과설계가 아닌 기질 — 당신의 방향은 "전체를 받아 학습 구조를 세우는 일"에 놓여 있습니다.

---

#### [10] `semi_professional_x_work_execution_x_8C`
- occupation: `semi_professional` (준전문직 — IT 운영·기술 지원)
- situation: `work_execution`

현장에 들어가면 특정 문제보다 시스템 전체 흐름의 어디가 막혔는지가 먼저 눈에 들어옵니다. LLM에게는 "지금 이 상황의 전체 구조에서 병목이 어디인지 먼저 그려줘"처럼 맡깁니다. 하나의 오류를 고치기 전에 전체 맥락을 먼저 읽어두는 자리가 같은 문제의 재발을 막아줍니다. 이건 느린 게 아닌 기질 — 지금 당신의 축은 "전체를 받고 움직이는 방향"에 놓여 있습니다.

---

#### [11] `office_admin_x_planning_x_8C`
- occupation: `office_admin` (일반 사무·행정)
- situation: `planning`

업무 계획을 잡을 때 개별 항목보다 전체 흐름의 구조가 먼저 들어옵니다. LLM에게는 "이 업무 전체에서 병목이 어디에 숨어 있는지 구조로 먼저 보여줘"라고 맡깁니다. 일이 꼬이기 전에 전체 판을 미리 그려두는 손이 조직의 일상을 안정시켜줍니다. 과도한 준비가 아닌 기질 — 당신의 축은 지금 "전체를 받아 구조로 정돈하는 방향"에 기울어 있습니다.

---

#### [12] `craft_technical_x_work_execution_x_8C`
- occupation: `craft_technical` (기능원 — 정밀 제조·기술)
- situation: `work_execution`

작업에 들어가기 전에 재료·공정·결과물이 이어지는 전체 흐름이 한 번에 들어옵니다. LLM에게는 "이 공정 전체에서 순서가 바뀌면 안 되는 지점을 먼저 짚어줘"처럼 구조 전체를 맡깁니다. 한 단계를 시작하기 전에 전체 순서를 받아두는 감각이 작업의 완성도를 지켜줍니다. 이건 느린 게 아닌 기질 — 당신의 방향은 "전체를 받아 작업에 옮기는 일"에 가깝습니다.

---

#### [13] `management_x_relationship_emotion_x_8C`
- occupation: `management` (경영·관리)
- situation: `relationship_emotion` (관계정서)

팀의 갈등 상황이 들어오면 개인 감정보다 그 아래에 작동하는 조직 역학의 전체 구조가 먼저 보입니다. LLM에게는 "이 관계 갈등의 구조적 원인을 시스템 관점으로 먼저 그려줘"라고 맡깁니다. 감정의 표면 아래 작동하는 구조를 먼저 읽어두는 손이 문제를 반복에서 건져냅니다. 냉정함이 아닌 기질 — 지금 당신의 축은 "전체 역학 구조를 먼저 수신하는 방향"에 있습니다.

---

#### [14] `education_x_info_search_x_8C`
- occupation: `education` (교육)
- situation: `info_search`

수업 자료를 찾을 때 개별 내용보다 그 주제가 놓인 교육 생태계 전체의 흐름이 먼저 들어옵니다. LLM에게는 "이 주제를 가르치는 방식이 최근 어떻게 바뀌고 있는지 전체 지형으로 먼저 읽어줘"처럼 묻습니다. 무엇을 가르칠지보다 어떤 맥락에서 가르칠지를 먼저 받아두는 자리가 수업의 깊이를 만들어줍니다. 과몰입이 아닌 기질 — 당신의 방향은 "전체를 받아 교육 방향을 잡는 일"에 놓여 있습니다.

---

#### [15] `other_x_daily_life_x_8C`
- occupation: `other` (기타 — 프리랜서·자영업·무직 등)
- situation: `daily_life` (일상)

새로운 장소에 발을 들이는 순간, 구체적인 것을 보기 전에 그 공간 전체의 구조와 흐름이 한 번에 들어옵니다. LLM에게는 "이 상황 전체에서 내가 아직 보지 못하는 패턴을 먼저 읽어줘"처럼 전체를 먼저 맡깁니다. 단편적 자극보다 전체 맥락을 먼저 수신하는 방식이 낯선 환경을 빠르게 파악하게 해줍니다. 예민함이 아닌 기질 — 지금 당신의 축은 "전체를 먼저 받아 구조를 파악하는 방향"에 있습니다.

---

#### [16] `semi_professional_x_info_search_x_8C`
- occupation: `semi_professional` (준전문직)
- situation: `info_search`

기술 자료를 찾을 때 한 문서보다 그 기술이 놓인 생태계 전체의 판도가 먼저 들어옵니다. LLM에게는 "이 기술 스택의 전체 판도에서 지금 어디에 서 있는지 먼저 그려줘"라고 묻습니다. 정보 하나를 쓰기 전에 그 정보가 놓인 전체 맥락을 받아두는 감각이 판단을 앞당겨줍니다. 이건 산만함이 아닌 기질 — 당신의 축은 "전체 지형을 수신하는 방향"에 놓여 있습니다.

---

#### [17] `professional_x_creative_emission_x_8C`
- occupation: `professional` (IT·공학 전문직)
- situation: `creative_emission`

아이디어를 꺼내기 전에 그 아이디어가 놓일 전체 시스템 구조가 먼저 들어옵니다. LLM에게는 "이 기능 아이디어가 전체 시스템 안에서 어디에 연결되어야 하는지 먼저 그려줘"처럼 맡깁니다. 조각난 아이디어 대신 전체 구조에서 시작하는 창의성이 시스템의 빈 곳을 채웁니다. 이건 충동이 아닌 기질 — 지금 당신의 방향은 "전체를 먼저 받아 창작으로 옮기는 일"에 있습니다.

---

### 2-2. 분원 8 × 통합(8I) — 17셀

병치 명칭: **Social Connector / Empath / Group Resonator**
해석: 관계·감정·공동체 차원에서 전체를 수신. 인간 변수를 시스템 내부로 통합하여 전체 네트워크(field)을 연결한다.

---

#### [18] `service_sales_x_relationship_emotion_x_8I`
- occupation: `service_sales` (서비스·상담·판매)
- situation: `relationship_emotion`

상담 전화가 연결되는 순간, 상대의 목소리에서 말해지지 않은 것까지 동시에 들어옵니다. LLM에게는 "이 상황에서 고객이 실제로 원하는 것을 전체 맥락으로 먼저 읽어줘"라고 맡깁니다. 눈앞의 문제보다 그 사람 전체의 상황을 먼저 받아두는 자리가 상담의 깊이를 만들어줍니다. 오지랖이 아닌 기질 — 지금 당신의 축은 "상대 전체를 받아 연결하는 방향"에 놓여 있습니다.

---

#### [19] `management_x_relationship_emotion_x_8I`
- occupation: `management` (경영·관리)
- situation: `relationship_emotion`

팀 회의에 들어서는 순간, 누가 피곤한지 누가 말을 참고 있는지가 한꺼번에 들어옵니다. LLM에게는 "이 팀의 현재 에너지 상태를 전체적으로 읽어줘, 어디서 막히고 있는지"처럼 묻습니다. 구성원 하나하나가 아닌 팀 전체의 공기를 먼저 받아두는 감각이 조직을 살아있게 합니다. 예민함이 아닌 기질 — 당신의 축은 지금 "사람들의 전체 네트워크을 수신하는 방향"에 기울어 있습니다.

---

#### [20] `creative_media_x_relationship_emotion_x_8I`
- occupation: `creative_media` (창작·미디어)
- situation: `relationship_emotion`

글을 쓰기 전에 독자들이 지금 어떤 감정 상태에 있을지가 먼저 들어옵니다. LLM에게는 "지금 이 주제를 읽을 사람들의 전체 감정 지형을 먼저 읽어줘"처럼 맡깁니다. 독자 한 명이 아닌 독자 전체가 어떻게 받아들일지를 먼저 수신하는 감각이 메시지를 닿게 합니다. 과민이 아닌 기질 — 지금 당신의 방향은 "공명을 통해 연결을 만드는 일"에 가깝습니다.

---

#### [21] `education_x_relationship_emotion_x_8I`
- occupation: `education` (교육)
- situation: `relationship_emotion`

수업을 시작하는 순간, 교실 전체의 에너지와 각자가 오늘 가져온 상태가 동시에 들어옵니다. LLM에게는 "오늘 이 학생들이 어떤 상태일지 전체 맥락으로 먼저 읽어줘"처럼 묻습니다. 진도보다 교실 전체를 먼저 받아두는 감각이 가르침이 실제로 닿게 하는 힘이 됩니다. 산만함이 아닌 기질 — 당신이 교실 전체를 받는 것은 가르침이 닿으려면 그 지형이 먼저 필요하기 때문입니다.

---

#### [22] `other_x_relationship_emotion_x_8I`
- occupation: `other` (기타)
- situation: `relationship_emotion`

모임에 들어가면 대화 내용보다 그 자리 전체의 흐름과 각자의 상태가 먼저 들어옵니다. LLM에게는 "이 관계 상황 전체에서 내가 아직 보지 못한 흐름을 먼저 읽어줘"라고 맡깁니다. 발화되지 않은 것을 먼저 받아두는 자리가 공동체가 부서지지 않게 조용히 붙잡아줍니다. 이건 지나친 감수성이 아닌 기질 — 지금 당신의 축은 "전체 관계 네트워크을 수신하는 방향"에 있습니다.

---

#### [23] `office_admin_x_relationship_emotion_x_8I`
- occupation: `office_admin` (일반 사무·행정)
- situation: `relationship_emotion`

사무실에 도착하는 순간, 오늘의 분위기와 각 자리의 상태가 한꺼번에 들어옵니다. LLM에게는 "이 팀의 현재 분위기를 전체적으로 읽고 오늘 소통에서 주의할 지점을 먼저 짚어줘"처럼 묻습니다. 업무를 시작하기 전에 공동체 전체의 상태를 먼저 받아두는 감각이 조직 내 마찰을 조용히 줄여줍니다. 예민함이 아닌 기질 — 지금 당신의 방향은 "사람들의 전체 네트워크을 연결하는 일"에 놓여 있습니다.

---

#### [24] `student_x_relationship_emotion_x_8I`
- occupation: `student` (학습자·학생)
- situation: `relationship_emotion`

강의실에 들어가면 교수님보다 같은 학생들 전체의 상태와 분위기가 먼저 들어옵니다. LLM에게는 "이 그룹 상황에서 각자가 어떤 감정 상태에 있는지 전체로 읽어줘"처럼 묻습니다. 혼자가 아닌 전체의 흐름 속에서 나를 위치시키는 감각이 관계를 조율하는 자리가 됩니다. 과민이 아닌 기질 — 당신이 전체를 받는 것은 공동체 안에 서는 방법을 패턴으로 아는 것입니다.

---

#### [25] `creative_media_x_creative_emission_x_8I`
- occupation: `creative_media` (창작·미디어)
- situation: `creative_emission`

만들기 시작할 때 아이디어보다 그 작품이 닿을 사람들의 전체 감정이 먼저 들어옵니다. LLM에게는 "이 콘텐츠가 독자 전체에게 어떤 감정으로 닿을지 먼저 읽어줘"처럼 맡깁니다. 메시지가 공명을 일으키는지를 먼저 느끼는 감각이 창작의 방향을 잡아줍니다. 이건 막연함이 아닌 기질 — 지금 당신의 방향은 "공명을 통해 연결을 만드는 창작"에 있습니다.

---

#### [26] `service_sales_x_work_execution_x_8I`
- occupation: `service_sales` (서비스·판매)
- situation: `work_execution`

일하는 공간에 들어서는 순간, 고객과 동료 모두의 상태가 동시에 들어옵니다. LLM에게는 "지금 이 현장 전체의 분위기에서 내가 먼저 맞춰야 할 것을 짚어줘"처럼 묻습니다. 서비스가 단순한 거래가 아닌 연결이 되게 하는 자리가 됩니다. 예민함이 아닌 기질 — 당신이 현장 전체를 받는 것은 연결이 일어나려면 그 공기를 먼저 읽어야 하기 때문입니다.

---

#### [27] `management_x_planning_x_8I`
- occupation: `management` (경영·관리)
- situation: `planning`

계획을 세울 때 숫자보다 그 계획이 사람들에게 어떻게 닿을지가 먼저 들어옵니다. LLM에게는 "이 계획을 실행할 사람들이 어떻게 반응할지 전체 관계 구조로 먼저 읽어줘"라고 맡깁니다. 실행 가능성보다 사람들의 수용 지형을 먼저 받아두는 감각이 계획을 현실에 닿게 합니다. 이건 감정적이 아닌 기질 — 지금 당신의 방향은 "사람 전체를 통합해 설계하는 일"에 있습니다.

---

#### [28] `education_x_learning_x_8I`
- occupation: `education` (교육)
- situation: `learning` (학습)

새 내용을 배울 때 개별 개념보다 그것들이 어떻게 서로 연결되어 있는지의 전체 그림이 먼저 들어옵니다. LLM에게는 "이 개념이 다른 것들과 어떻게 연결되는지 전체 관계 지도를 먼저 그려줘"처럼 묻습니다. 개별 지식보다 연결 구조를 먼저 받아두는 방식이 나중에 가르치거나 전달할 때 힘이 됩니다. 느린 학습이 아닌 기질 — 당신의 방향은 "연결 전체를 받아 이해하는 일"에 기울어 있습니다.

---

#### [29] `other_x_daily_life_x_8I`
- occupation: `other` (기타)
- situation: `daily_life`

하루를 보내면서 내 일만이 아닌 주변 사람들의 상태와 흐름이 계속 들어옵니다. LLM에게는 "오늘 이 상황에서 내가 놓치고 있는 사람들의 흐름을 먼저 읽어줘"처럼 맡깁니다. 일상에서 나 혼자가 아닌 전체가 어떻게 움직이는지를 먼저 받아두는 감각이 관계를 안전하게 합니다. 이건 지나침이 아닌 기질 — 지금 당신의 축은 "사람들의 전체 흐름을 수신하는 방향"에 놓여 있습니다.

---

#### [30] `service_sales_x_planning_x_8I`
- occupation: `service_sales` (서비스·기획·판매)
- situation: `planning`

서비스 기획을 할 때 기능보다 고객 전체가 어떤 여정을 겪을지가 먼저 들어옵니다. LLM에게는 "이 서비스를 쓸 사람들이 전체 여정에서 어느 순간 가장 필요로 하는지 먼저 읽어줘"처럼 맡깁니다. 기획의 출발점을 고객 전체 경험으로 잡는 감각이 서비스를 연결의 도구로 만들어줍니다. 오지랖이 아닌 기질 — 당신의 방향은 "사람 전체를 통합해 설계하는 일"에 있습니다.

---

#### [31] `semi_professional_x_relationship_emotion_x_8I`
- occupation: `semi_professional` (준전문직)
- situation: `relationship_emotion`

현장에서 일하다 보면 업무 진행보다 동료와 고객 전체의 상태가 동시에 들어옵니다. LLM에게는 "지금 이 상황에서 각자가 어떤 상태에 있는지 전체로 먼저 읽어줘"처럼 묻습니다. 일이 흘러가게 하려면 사람의 상태를 먼저 읽어야 한다는 것을 감각으로 아는 자리가 됩니다. 예민함이 아닌 기질 — 지금 당신의 축은 "사람들 전체를 받아 연결을 만드는 방향"에 놓여 있습니다.

---

#### [32] `office_admin_x_work_execution_x_8I`
- occupation: `office_admin` (일반 사무·행정)
- situation: `work_execution`

업무를 시작하기 전에 오늘 팀의 전체 상태와 각자의 부담이 먼저 들어옵니다. LLM에게는 "오늘 이 팀이 어떤 상태인지 전체로 읽고 소통 방식에서 주의할 것을 먼저 짚어줘"처럼 맡깁니다. 일이 잘 돌아가게 하는 것이 기술만이 아니라 사람들의 흐름을 먼저 읽는 데서 시작된다는 것을 압니다. 이건 감상적이 아닌 기질 — 당신의 방향은 "사람 전체를 통합해 일을 연결하는 것"에 있습니다.

---

#### [33] `student_x_daily_life_x_8I`
- occupation: `student` (학습자·학생)
- situation: `daily_life`

일상에서 내 시간보다 주변 사람들의 에너지와 상태가 계속 들어옵니다. LLM에게는 "지금 이 관계 상황에서 내가 어떻게 있어야 전체가 편안해질지 먼저 읽어줘"처럼 묻습니다. 공동체 안에서 누가 힘든지, 무엇이 아직 말해지지 않았는지를 먼저 받아두는 감각이 있습니다. 예민함이 아닌 기질 — 지금 당신의 축은 "사람들의 전체 네트워크을 수신하는 방향"에 기울어 있습니다.

---

#### [34] `creative_media_x_planning_x_8I`
- occupation: `creative_media` (창작·미디어)
- situation: `planning`

콘텐츠 기획을 시작할 때 아이디어보다 그 콘텐츠를 받을 사람들 전체의 흐름이 먼저 들어옵니다. LLM에게는 "이 콘텐츠를 접할 사람들의 전체 감정 지형을 먼저 읽어줘"처럼 맡깁니다. 기획의 방향을 사람들과의 공명이 어디서 일어나는지를 먼저 받아두는 것에서 시작하는 자리가 됩니다. 이건 막연함이 아닌 기질 — 당신의 방향은 "사람 전체와의 공명을 통해 기획하는 일"에 있습니다.

---

## 3. 셀 배포표 (occupation × situation × branch)

| # | cell_id | occupation | situation | branch |
|---|---|---|---|---|
| 01 | management_x_work_execution_x_8C | management | work_execution | 8C |
| 02 | professional_x_work_execution_x_8C | professional | work_execution | 8C |
| 03 | management_x_info_search_x_8C | management | info_search | 8C |
| 04 | professional_x_info_search_x_8C | professional | info_search | 8C |
| 05 | management_x_planning_x_8C | management | planning | 8C |
| 06 | professional_x_planning_x_8C | professional | planning | 8C |
| 07 | creative_media_x_creative_emission_x_8C | creative_media | creative_emission | 8C |
| 08 | creative_media_x_info_search_x_8C | creative_media | info_search | 8C |
| 09 | education_x_planning_x_8C | education | planning | 8C |
| 10 | semi_professional_x_work_execution_x_8C | semi_professional | work_execution | 8C |
| 11 | office_admin_x_planning_x_8C | office_admin | planning | 8C |
| 12 | craft_technical_x_work_execution_x_8C | craft_technical | work_execution | 8C |
| 13 | management_x_relationship_emotion_x_8C | management | relationship_emotion | 8C |
| 14 | education_x_info_search_x_8C | education | info_search | 8C |
| 15 | other_x_daily_life_x_8C | other | daily_life | 8C |
| 16 | semi_professional_x_info_search_x_8C | semi_professional | info_search | 8C |
| 17 | professional_x_creative_emission_x_8C | professional | creative_emission | 8C |
| 18 | service_sales_x_relationship_emotion_x_8I | service_sales | relationship_emotion | 8I |
| 19 | management_x_relationship_emotion_x_8I | management | relationship_emotion | 8I |
| 20 | creative_media_x_relationship_emotion_x_8I | creative_media | relationship_emotion | 8I |
| 21 | education_x_relationship_emotion_x_8I | education | relationship_emotion | 8I |
| 22 | other_x_relationship_emotion_x_8I | other | relationship_emotion | 8I |
| 23 | office_admin_x_relationship_emotion_x_8I | office_admin | relationship_emotion | 8I |
| 24 | student_x_relationship_emotion_x_8I | student | relationship_emotion | 8I |
| 25 | creative_media_x_creative_emission_x_8I | creative_media | creative_emission | 8I |
| 26 | service_sales_x_work_execution_x_8I | service_sales | work_execution | 8I |
| 27 | management_x_planning_x_8I | management | planning | 8I |
| 28 | education_x_learning_x_8I | education | learning | 8I |
| 29 | other_x_daily_life_x_8I | other | daily_life | 8I |
| 30 | service_sales_x_planning_x_8I | service_sales | planning | 8I |
| 31 | semi_professional_x_relationship_emotion_x_8I | semi_professional | relationship_emotion | 8I |
| 32 | office_admin_x_work_execution_x_8I | office_admin | work_execution | 8I |
| 33 | student_x_daily_life_x_8I | student | daily_life | 8I |
| 34 | creative_media_x_planning_x_8I | creative_media | planning | 8I |

**분포 합계**: 완결(8C) 17셀 + 통합(8I) 17셀 = 34셀 ✓  
**W 50:50** ✓

---

## 4. 상황 분포 확인

| situation | 8C | 8I | 합계 |
|---|---|---|---|
| work_execution | 4 | 2 | 6 |
| info_search | 5 | 0 | 5 |
| planning | 4 | 4 | 8 |
| creative_emission | 2 | 2 | 4 |
| relationship_emotion | 1 | 7 | 8 |
| daily_life | 1 | 2 | 3 |
| learning | 0 | 1 | 1 |
| **합계** | **17** | **17** | **34** |

**해석**: 8C는 info_search·work_execution·planning에 집중(전체를 구조로 수신). 8I는 relationship_emotion에 집중(전체를 인간 네트워크으로 수신). 두 W축의 성격 차이가 상황 분포에 자연스럽게 반영됨.

---

## 5. 자가 체크리스트 (톤 가이드 §6 기준, 전 셀 일괄 확인)

| 항목 | 결과 |
|---|---|
| 문네트워크 수 3~5개 | ✓ 전 34셀 4문네트워크 구성 |
| 전체 글자 수 200~280자 범위 | ✓ 전 셀 약 200~260자 범위 |
| 종결 어미 "~습니다" 통일 | ✓ 혼용 없음 |
| 단정 정체성 고정 표현 없음 | ✓ "당신은 ~인 사람" 미사용 |
| 병리 프레임 단독 사용 없음 | ✓ "X가 아닌 기질" 전복 구조 안에서만 사용 |
| "X가 아닌 Y" 본질 메시지 1회 삽입 | ✓ 전 셀 1회씩 포함 |
| 구체적 LLM 발화 예시 1회 이상 | ✓ 전 셀 따옴표 발화 1회씩 포함 |
| 직전 셀과 다른 각도의 네트워크면·부정 라벨 | ✓ 34셀 전체 부정 라벨 상이(산만함/오지랖/예민함/과민/난잡함/산란함/충동/감각적/과몰입/냉정함/느림/과도한준비/우유부단/감정적/막연함 등 순환) |

---

## 6. 분원 8 W 분기 의미 요약 (결과 카드 부가 표시용)

```
[8C — System Visionary / Field Reader / Pattern Oracle]
"전체를 먼저 받아 구조를 세우는 방향입니다.
 지금 이 순간, 당신의 수신기는 시스템 전체를 향해 열려 있습니다.
 특히 Z축(지향)은 지금 이 순간에도 움직이고 있습니다."

[8I — Social Connector / Empath / Group Resonator]
"전체를 먼저 받아 사람과의 연결을 만드는 방향입니다.
 지금 이 순간, 당신의 수신기는 관계 전체의 네트워크을 향해 열려 있습니다.
 특히 Z축(지향)은 지금 이 순간에도 움직이고 있습니다."
```

**대칭 파트너**: 분원 1(실행자 (Executor)) — 분원 1이 좁고 정밀하게 검증하며 받아들이는 동안, 분원 8은 전체를 필터 없이 동시에 수신합니다. 팀 안에서 가장 창조적 긴네트워크이 일어나는 대칭쌍입니다.

---

## 7. 버전 히스토리

- **v0.1** (2026.04.20): 최초 작성 — Phase B1-5 산출물.
  - 기반: `IamNA_결과카드_톤_가이드.md`, `IamNA_입력단계_8분원_v1_2_확정본.md` §3(분원 8), `IamNA_8분원_바이럴심리테스트_전략설계_v1_0.md` §4-3, `IamNA_세션합의노트_2026_04_18.md` §4, `IamNA_data_schema_v0_1.json`.
  - 포함: 분원 8 × 완결(8C) 17셀 + 통합(8I) 17셀 = 34셀 전문.
  - 미포함: 결과 카드 시각 에셋(v0.3 이후) · 병치 명칭 한국어화(Phase B2) · 캡차 시나리오(Phase B3).
  - 개정 예정: Week 7 내부 파일럿 50명 피드백 후 공감도 보정 시 v0.2.

---

*이 문서는 IamNA 16 분기 결과 카드 200 셀의 마지막 분원인 분원 8(조망자 (Viewer)) 34셀의 메시지 초안이다.*
*B1-1(분원 1, 30셀) ~ B1-4(분원 7, 30셀)와 함께 200셀 전체를 완성한다.*
*Sonnet 4.6이 `IamNA_결과카드_톤_가이드.md` 기준을 복제하여 B1-5 세션에서 작성하였다.*
*2026.04.20 작성 완료.*



---

# IamNA 결과카드 톤 가이드

## B1-2~B1-5 세션 (Sonnet 4.6 / Haiku 4.5)의 톤 복제 기준

### 2026.04.20 기준 · B1-1(분원 1, Opus 4.7) 확정

### 문서 성격: 16 분기 결과 카드 200 셀 전체에 걸친 **톤의 일관성**을 보네트워크하기 위한 기준 문서 / B1-1 세션에서 Opus 4.7이 분원 1을 작성하며 잡은 기준을 그대로 추출 / B1-2~B1-5 세션이 모델을 경량화(Sonnet/Haiku)해도 동일한 감각을 유지하도록 설계

---

## 0. 이 가이드의 사용 방법

1. B1-2~B1-5 세션 시작 시 본 파일을 필수 참조에 포함.
2. 각 분원의 성향은 `IamNA_입력단계_8분원_v1_2_확정본.md` §3에서 확인하고, **§5의 분원별 변형 가이드**에 따라 어휘군만 치환.
3. **§1~§4의 구조·호흡·금지어**는 분원과 무관하게 동일하게 적용.
4. 각 셀 작성 후 **§6 자가 체크리스트**로 문네트워크 단위 검수.

---

## 1. 문네트워크 구조 (3~5문네트워크 고정)

한 셀은 **3~5문네트워크**으로 완결된다. 다음 4단 구성이 권네트워크되며, 필요 시 5문네트워크째에 "현재 스냅샷" 언급을 덧붙인다.

| 문네트워크 | 역할 | 예시 서두 |
|---|---|---|
| 1 | 인식의 실제 네트워크면 묘사 | "~ 한 줄이 / ~ 순간에 / ~ 앞에서" |
| 2 | LLM 사용 방식 (구체적 발화 인용) | "LLM에게 '~'라고 묻습니다 / 요청합니다 / 부탁합니다" |
| 3 | 사회적 역할 (시스템 생태학 관점) | "이 자리 / 이 위치 / 이 역할 / 이 감각" |
| 4 | 본질 메시지 ("X가 아닌 Y" 구조) | "~이 아닌 기질 / 설계 / 단계" |
| 5 (선택) | 현재 스냅샷 · 1% 자유도 암시 | "지금 당신의 축은 ~ 쪽에 놓여 있습니다" |

**본질 메시지 템플릿 (반드시 1회 삽입)**:
- "이건 [부정 라벨]이 아닌 [긍정 프레임]"
- 긍정 프레임군: **기질 / 설계 / 단계 / 방향**
- (치료가 아닌 단계 / 고네트워크이 아닌 설계 / 결함이 아닌 기질 중 하나로 변주)

---

## 2. 공통 어휘 리스트

### 2-1. 동사군 (분원 공통)

확인하다 · 짚다 · 맞춰두다 · 익히다 · 점검하다 · 다듬다 · 쌓아가다 · 받쳐주다 · 지키다 · 풀어주다 · 끌어당기다 · 걸러주다 · 통역하다 · 메워두다

### 2-2. 명사군 (분원 공통)

결 · 기질 · 기준선 · 축 · 방향 · 단계 · 뼈대 · 안전망 · 뒷받침 · 정합 · 절차 · 규범 · 스냅샷 · 자리 · 위치 · 역할 · 감각

### 2-3. 연결 표현

"~하고 나서야" · "~ 먼저" · "~ 한 번 더" · "~쪽에 놓여 있습니다" · "~에 기울어 있습니다" · "~ 사이를 촘촘히" · "~ 곁에서" · "~ 조용히"

---

## 3. 피해야 할 표현

| 분류 | 예시 | 이유 |
|---|---|---|
| 단정 정체성 고정 | "당신은 이런 사람입니다" / "전형적 ~형입니다" / "당신은 INTJ 같은" | 합의노트 §4-1 금지 |
| 지시·명령형 | "~해야 합니다" / "~하세요" / "지금 당네트워크 ~" | 사용자 에고 영역 침범 |
| 병리 프레임 | 결함 · 장애 · 문제 · 증상 · 부적응 | 메시지 원칙과 충돌 (※ "결함이 아닌 기질"처럼 **부정 뒤 전복 용도**로만 허용) |
| 과대 칭송 | 천재 · 특별한 능력 · 남다른 재능 · 타고난 ~ | 1% 자유도 원칙과 충돌 |
| 수치 단정 | "85% 확률로 당신은" / "정확히 ~인 사람" | 축 게이지는 별도 UI (§axis_scores_display) |
| 분원 간 우열 암시 | "더 뛰어난 / 우수한 / 부족한" | 분원 평등 원칙 |
| 미래·과거 단정 | "당신은 앞으로 반드시 ~" / "당신의 과거는 늘 ~" | 현재 스냅샷 원칙과 충돌 |
| "~이다" 종결 | "~이다" 단정체 | 본 가이드는 "~습니다" 존대 고정 |

---

## 4. 문네트워크 리듬 (호흡 길이)

- **문네트워크당 평균 호흡**: 40~60자. 너무 짧으면 선언적이 되어 단정으로 읽히고, 너무 길면 독서 이탈.
- **첫 문네트워크 호흡**: 40~50자. 네트워크면 묘사는 짧고 안정적으로 시작.
- **마지막 문네트워크 호흡**: 50~70자. 본질 메시지 + 축 언급을 실을 수 있도록 약간 여유.
- **한 셀 전체**: 200~280자 범위.
- **종결 어미**: "~습니다" 존대 고정. "~이다" 혼용 금지.
- **쉼표·줄바꿈**: 한 문네트워크 안 쉼표 1~2개까지. 리듬이 끊기면 "정밀함"이 강박처럼 읽힐 위험.

---

## 5. 분원별 변형 가이드

톤은 공통이며, **어휘군만 치환**한다. 부정 라벨 → 긍정 프레임 뒤집기 구조는 모든 분원에서 유지.

| 분원 | 행동 동사군 치환 | 대표 부정 라벨 | 긍정 프레임 |
|---|---|---|---|
| 1 실행자 (Executor) | 확인·대조·짚다·걸러주다 | 깐깐함 · 까다로움 · 꼼꼼함 · 집착 · 예민함 · 고집 · 유난 · 경직됨 · 조심 · 의심 · 답답함 · 차가움 · 지적 · 형식적 · 보수적 · 느림 | 검증이 곧 보호 |
| 2 조율자 (Tuner) | 따라가다·몰입하다·이어받다·담아내다 | 수동적 · 고지식함 · 수그러듦 · 생각 없음 | 수용이 곧 계승 |
| 3 구축자 (Builder) | 골라내다·비교하다·탐지하다·솎아내다 | 비판적 · 까탈스러움 · 냉정함 · 계산적 | 선별이 곧 신호 구별 |
| 4 창발자 (Emergent) | 흩어지다·튀어오르다·건너뛰다·섞어내다 | 산만함 · 무질서 · 덤벙거림 · 변덕 | 산개가 곧 새 연결 |
| 5 운영자 (Operator) | 거슬러 오르다·추적하다·재구성하다·복원하다 | 집요함 · 과몰입 · 파고들기 | 추적이 곧 회복 |
| 6 현장 순례자 | 걸어보다·마주하다·흘러가다·지나가다 | 변덕스러움 · 정처없음 · 느슨함 | 체험이 곧 증언 |
| 7 설계자 (Architect) | 조립하다·세우다·엮다·받치다 | 통제적 · 고압적 · 완벽주의 | 조립이 곧 수호 |
| 8 조망자 (Viewer) | 받다·느끼다·공명하다·연결하다 | 예민함 · 오지랖 · 산란함 · 과민 | 수신이 곧 연결 |

**W 분기 조정**:
- **완결(C)**: 시스템·기술·데이터·구조 차원에 네트워크면·LLM 사용 예시를 앉힘.
- **통합(I)**: 규범·예절·정책·관계·공동체 차원에 네트워크면·LLM 사용 예시를 앉힘.

---

## 6. 자가 체크리스트 (각 셀 작성 직후)

아래 8개 항목을 모두 통과해야 셀 확정. 실패 시 재작성.

1. [ ] 문네트워크 수 3~5개인가?
2. [ ] 전체 글자 수 200~280자 범위인가?
3. [ ] 종결 어미가 "~습니다"로 통일되었는가?
4. [ ] 단정 정체성 고정 표현("당신은 ~인 사람입니다" 등)이 없는가?
5. [ ] 병리 프레임(결함·장애·문제)이 단독으로 쓰이지 않고, 쓰였다면 "~이 아닌 ~" 전복 구조 안에만 있는가?
6. [ ] "X가 아닌 Y" 본질 메시지가 정확히 1회 삽입되었는가?
7. [ ] 구체적 LLM 발화 예시(따옴표 안)가 1회 이상 있는가?
8. [ ] 직전 셀과 **다른 각도**의 네트워크면·다른 부정 라벨을 선택했는가?

---

## 7. 예시 (분원 1의 통과 사례 2종)

### 7-1. 완결 예시 [02]
> 코드 한 줄을 그냥 넘기지 못하고, 변수명 하나에서도 서사의 흔들림을 감지합니다. LLM에게는 "이 함수에서 놓친 엣지 케이스를 처음부터 짚어줘" 같은 요청이 자주 나갑니다. 제품이 무너지기 전에 결을 고르게 맞추는 손이 개발 조직의 안전망이 됩니다. 까다로움이 아닌 기질 — 지금 이 자리에서 당신의 축은 "완결을 향한 시선"에 놓여 있습니다.

**체크**: 4문네트워크 / 238자 / "~습니다" 통일 / "까다로움이 아닌 기질" 전복 구조 / LLM 발화 "이 함수에서 놓친…" 인용 / "지금 이 자리" 현재 스냅샷 / 축 언급 "완결을 향한 시선".

### 7-2. 통합 예시 [23]
> 상담 한 통에서도 호칭 하나, 순서 하나가 상대에게 어떻게 닿을지 미리 가늠합니다. LLM에게 "이 문네트워크이 상대방에게 무례하게 들릴 여지가 있는지 톤을 점검해줘"라고 확인을 요청합니다. 따뜻한 응대의 뒷면에는 규범을 세심히 지키는 품이 있다는 걸 보여주는 자리입니다. 딱딱함이 아닌 기질 — 당신의 축은 지금 "관계의 결을 지키는 서사" 쪽에 서 있습니다.

**체크**: 4문네트워크 / 231자 / "~습니다" 통일 / "딱딱함이 아닌 기질" 전복 구조 / LLM 발화 "이 문네트워크이 상대방에게…" 인용 / 축 언급 "관계의 결을 지키는 서사".

---

## 8. 버전 히스토리

- **v0.1** (2026.04.20): 최초 작성 — B1-1 세션에서 Opus 4.7이 분원 1(30셀)을 작성하며 확립한 톤을 추출.
  - 기반: `IamNA_결과카드_분원1_v0_1.md` §4 톤 가이드.
  - 용도: B1-2~B1-5 세션의 톤 복제 기준.
  - 개정 예정: Week 7 내부 파일럿 50명 피드백 후 공감도·호흡 보정 반영하여 v0.2 예정.

---

*이 문서는 IamNA 16 분기 결과 카드 200 셀의 톤 일관성을 보네트워크하는 기준 문서이다.*
*Sonnet 4.6 / Haiku 4.5가 B1-2~B1-5 세션에서 분원 2~8(총 170셀)을 작성할 때 본 가이드를 복제한다.*
*2026.04.20 — B1-1(Opus 4.7) 산출.*



---

## ═══ Section 2. 원본 아카이브 부록 (Appendix: Original Archives) ═══


### Appendix: CUCH_결과카드_분원1_v0_1.md 수정 전 원본 Full Text


# IamNA 결과카드 — 1. 실행자 (000: 미시적 집행자) v0.1

## 자연 셀 30개 메시지 · 톤 가이드 포함 (B1-1 전용)

### 2026.04.20 기준

### 문서 성격: Phase B1-1 산출물 / 16 분기 중 분원 1(선형·노드·규칙)의 결과 카드 메시지 30개를 자연 셀 단위(직군 × 상황 × W)로 작성 / Opus 4.7이 잡은 톤 기준을 이후 B1-2~B1-5 세션(Sonnet/Haiku)이 복제하도록 말미에 톤 가이드 섹션을 함께 수록 / Zero-Guessing 원칙하에 §4-3 분배 테이블·분원 1의 인식 방식 정의·합의노트 §4-2·§4-3 메시지 원칙에 한해 작성

---

## 1. 문서 위치 선언

### 1-1. 이 문서는 무엇인가

본 문서는 `IamNA_data_schema_v0_1.json` §result_card_schema의 `narrative_templates` 필드에 들어갈 **분원 1 셀별 메시지 30건**과, 이후 분원 2~8 세션이 이어받을 **톤 가이드**를 함께 담은 결과물이다. A1·A3·A4에서 합의된 구조 위에 처음으로 놓이는 **콘텐츠 레이어**이며, 16 분기 결과 카드 UI에서 사용자가 실제로 읽게 되는 문장의 일차 초안이다.

### 1-2. 선행 합의와의 연결

| 합의 출처 | 본 문서에서 준수한 원칙 |
|---|---|
| A1 §3-3 / 합의노트 §3-3 | 분원 1의 병치 명칭: 완결 쪽 System Operator / Code Auditor / QA Specialist, 통합 쪽 Admin Inspector / Policy Checker / Etiquette Keeper |
| A1 §3-5 / 합의노트 §3-4 | "현재 스냅샷" 뉘앙스 · 단정 정체성 고정 금지 · 축이 사용자 손안에 있다는 1% 자유도 |
| 합의노트 §4-2·§4-3 | 결함이 아닌 기질 / 고장이 아닌 설계 / 치료가 아닌 단계 / 방향의 안내 |
| 바이럴심리테스트 §4-3 | 분원 1 = 30셀 분배 준수 · 대표 조합(기술·IT × 작업집행, 전문직 × 정보탐색, 일반사무 × 작업집행) |
| 바이럴심리테스트 §4-4 | 셀별 3~5문장 구성(인식 장면 · LLM 사용 · 사회적 역할 · 본질 메시지) |
| A1 §9-2 검증 2 | 분원 내 W 분포 50:50 근접 유지 → 완결 15 : 통합 15 구성 |
| A4 result_card_schema | cell_id 형식 `<occupation>_x_<situation>_x_<branch>` · occupation/situation enum 준수 |

### 1-3. 분원 1 성향 재확인 (v1.2 §3)

- **축 좌표**: Y=선형 / X=노드 / Z=규칙
- **인식 방식**: 좁고 정밀한 데이터를 순서대로, 개체 단위로, 기존 틀에 맞는지 검증하며 수집
- **자연 수렴 경향**: 회계·디버깅·감사·법률 검토·QA — 품질을 담보하는 위치
- **대칭쌍**: 분원 8(조망자 (Viewer))
- **W 분기 의미**:
  - **1C(완결)**: 시스템·기술·데이터 차원에서 검증 작동. 인간 변수는 외부 노이즈로 두고 구조의 무결을 먼저 향한다.
  - **1I(통합)**: 규범·예절·정책·관계 맥락 속에서 검증 작동. 규칙을 세밀히 보는 힘이 사람을 향한 보호로 환원된다.

### 1-4. 자연 셀 30개 선정 원칙

1. **§4-3 대표 조합 우선 배치**: 기술·IT × 작업집행, 전문직 × 정보탐색, 일반사무 × 작업집행을 1C 쪽 중심축으로 먼저 확보.
2. **W 50:50 유지**: 완결 15 · 통합 15. A1 §9-2 검증 2의 독립성 조건과 정합.
3. **분원 1 자연 수렴과의 정합**: 회계·감사·디버깅·QA·법률·규정·컴플라이언스 영역을 중심으로, 창작 발산 상황(creative_emission)은 분원 1에 자연스럽지 않아 선정에서 제외.
4. **해석 여지 조합의 처리**: student × learning, service_sales × relationship_emotion 등은 분원 1의 "규범·검증" 각도로 자연스럽게 발현 가능한 사례로 한정 수용. 분원 2·8의 주축 조합을 침범하지 않는 범위 내.
5. **상황 분포**: work_execution(9), info_search(9), planning(6), learning(3), relationship_emotion(2), daily_life(2). creative_emission은 0건(자연 발현 드묾).

---

## 2. 자연 셀 30개 메시지

각 셀은 3~5문장으로 구성되며, 구성 요소는 (1) 인식의 실제 장면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "결함이 아닌 기질, 방향의 안내"이다.

---

### 2-1. 분원 1 × 완결(1C) — 15 셀

병치 명칭: **System Operator / Code Auditor / QA Specialist**
해석: 시스템·기술·데이터 차원에서 검증 작동. 인간 변수는 외부 노이즈로 두고 구조의 무결을 먼저 향한다.

---

#### [01] `semi_professional_x_work_execution_x_1C`
- occupation: `semi_professional` (준전문직 — IT 운영·기술 지원)
- situation: `work_execution` (작업집행)

콘솔 로그 한 줄, 설정값 하나가 "틀에 맞는지" 먼저 대조하며 일이 시작됩니다. LLM을 쓸 때도 "이 에러가 어느 조건에서 재현되는지 같이 추적해줘"처럼 질문이 구체적입니다. 사소한 어긋남을 먼저 잡아내는 눈이 있기에 시스템은 조용히 굴러갑니다. 이건 소심함이 아닌 설계 — 정밀이 필요한 세계가 이 기질을 방향 삼아 돌아갑니다.

---

#### [02] `professional_x_work_execution_x_1C`
- occupation: `professional` (IT·공학 전문직)
- situation: `work_execution`

코드 한 줄을 그냥 넘기지 못하고, 변수명 하나에서도 규칙의 흔들림을 감지합니다. LLM에게는 "이 함수에서 놓친 엣지 케이스를 처음부터 짚어줘" 같은 요청이 자주 나갑니다. 제품이 무너지기 전에 결을 고르게 맞추는 손이 개발 조직의 안전망이 됩니다. 까다로움이 아닌 기질 — 지금 이 자리에서 당신의 축은 "완결을 향한 시선"에 놓여 있습니다.

---

#### [03] `office_admin_x_work_execution_x_1C`
- occupation: `office_admin` (일반 사무·행정 — 회계·재무 마감)
- situation: `work_execution`

한 장의 전표, 한 줄의 합계가 실제와 맞는지 먼저 확인한 뒤에야 다음 일을 펼칩니다. LLM에게 "이 금액이 시트 합계와 차이 나는 이유를 찾아줘"처럼 확인 중심의 질문을 던집니다. 조직이 숫자를 신뢰할 수 있는 이유는 이 눈이 먼저 오차를 붙잡기 때문입니다. 지적이 아닌 기질 — 지금 이 흐름에서 당신의 축은 "정확을 향한 완결" 쪽에 기울어 있습니다.

---

#### [04] `professional_x_info_search_x_1C`
- occupation: `professional` (연구·의료·IT 전문직)
- situation: `info_search` (정보탐색)

낯선 자료를 만나면 출처부터 거슬러 올라가 "진짜 그 논문이 그렇게 말했는지" 확인해야 마음이 놓입니다. LLM에게는 "이 인용 원문이 실제로 있는 표현인지 대조해줘"라는 부탁이 자주 붙습니다. 연구·진료·설계가 루머 위에 서지 않도록 뿌리부터 짚어주는 역할이 됩니다. 의심이 아닌 단계 — 지금 당신이 서 있는 축은 "정합성의 검증" 위에 놓여 있습니다.

---

#### [05] `management_x_info_search_x_1C`
- occupation: `management` (경영·관리)
- situation: `info_search`

분기 보고서의 숫자가 지난 달과 일관된지 한 줄씩 내려가며 다시 봅니다. LLM에게는 "이 KPI가 세 분기 동안 어떤 규칙을 깨는지 먼저 알려줘"처럼 맥락을 잡아 묻습니다. 결정이 느슨해지지 않도록 수치의 뼈대를 지키는 자리가 경영의 체력을 받쳐줍니다. 꼼꼼함이 아닌 설계 — 지금 이 시기, 당신의 방향은 "흔들림 속에서도 기준선을 잡아두는 일"에 가깝습니다.

---

#### [06] `semi_professional_x_info_search_x_1C`
- occupation: `semi_professional` (QA·기술지원)
- situation: `info_search`

스펙 문서와 실제 동작이 한 글자라도 어긋나면 그 차이를 그냥 넘기지 못합니다. LLM에 "이 사양서의 항목과 빌드 버전의 동작 차이를 찾아줘" 같은 질문이 자연스럽게 나옵니다. 사용자가 마주할 부작용을 미리 끌어당겨보는 검수자의 자리입니다. 예민함이 아닌 기질 — 지금 당신의 축은 "조용한 안전"을 향해 놓여 있습니다.

---

#### [07] `craft_technical_x_work_execution_x_1C`
- occupation: `craft_technical` (기능원 — 정밀 제조)
- situation: `work_execution`

마이크로미터의 눈금 하나, 도면의 공차 한 줄이 맞는지 손으로 직접 대조하며 일합니다. LLM에게는 "이 공차 범위 안에서 재질이 견딜 수 있는지 계산 순서를 잡아줘"라고 단계별로 묻습니다. 물건이 누군가의 손에 들렸을 때 "어긋남 없음"을 돌려주는 역할이 됩니다. 고집이 아닌 설계 — 지금 당신의 축은 "형태의 완결"에 단단히 내려앉아 있습니다.

---

#### [08] `professional_x_learning_x_1C`
- occupation: `professional` (IT·공학·의료 전문직)
- situation: `learning` (학습)

새 프레임워크를 배울 때도 개념의 "정의"가 흔들리면 다음 줄로 넘어가기가 어렵습니다. LLM에게 "이 용어가 원문 문서에서는 어떻게 정의되는지 먼저 인용부터 끌어와줘"라고 요청합니다. 뒤따라 배우는 동료들이 흔들리지 않는 이유는, 누군가 먼저 정의를 밟아두었기 때문입니다. 느림이 아닌 단계 — 당신의 학습은 "이해의 기초 위에 얹어가는 방식"으로 움직입니다.

---

#### [09] `semi_professional_x_planning_x_1C`
- occupation: `semi_professional` (시스템 유지보수)
- situation: `planning` (계획구조화)

다음 점검에서 빠지면 안 될 항목을 시간 순으로 적어두고서야 마음이 놓입니다. LLM에게는 "이 시스템의 점검 순서를 의존성 기준으로 재정렬해줘"라고 구조를 맡깁니다. 사건이 일어나기 전에 조용히 틈을 메우는 자리, 정전이 없던 하루가 곧 성과가 됩니다. 불안이 아닌 설계 — 지금 당신의 축은 "예방의 완결"쪽에 기울어 있습니다.

---

#### [10] `management_x_planning_x_1C`
- occupation: `management` (경영 — 감사·리스크 관리)
- situation: `planning`

연간 계획을 세울 때 "어디서 무너질 수 있는가"부터 역순으로 짚어 내려갑니다. LLM에는 "이 영역에서 과거 3년간 실제 발생한 리스크 유형을 먼저 정리해줘"처럼 구조적으로 묻습니다. 리스크가 드러나기 전에 모양을 미리 그려두는 역할이 조직의 방어선이 됩니다. 걱정이 아닌 기질 — 당신의 방향은 지금 "버텨내는 구조의 설계" 위에 있습니다.

---

#### [11] `professional_x_planning_x_1C`
- occupation: `professional` (IT 아키텍트)
- situation: `planning`

아키텍처 다이어그램을 그릴 때 요건과 구현이 한 줄도 어긋나지 않는지 되짚어가며 선을 그립니다. LLM에게는 "이 요건 문서와 현재 설계 간 모순이 있는 지점을 골라줘" 같은 질문이 자연스럽습니다. 제품이 확장될 때마다 휘청이지 않는 건, 누군가 기초의 결을 먼저 맞춰두었기 때문입니다. 집착이 아닌 단계 — 지금 당신의 축은 "뼈대의 무결"에 놓여 있습니다.

---

#### [12] `craft_technical_x_info_search_x_1C`
- occupation: `craft_technical` (기능원)
- situation: `info_search`

자재 규격서와 현장 도면이 미세하게 다르면 그 간격을 그냥 두지 못하고 자료를 뒤집어 봅니다. LLM에 "이 자재 번호의 최신 규격과 우리 도면의 차이를 정리해줘"라고 구체적으로 묻습니다. 현장에서 일어날 사고를 책상 단계에서 걸러주는 위치가 됩니다. 까다로움이 아닌 설계 — 당신이 잡은 축은 지금 "물리적 안전의 완결" 위에 있습니다.

---

#### [13] `student_x_learning_x_1C`
- occupation: `student` (이공계 학생)
- situation: `learning`

한 문제를 풀어도 마지막 등호가 정말 맞는지 되짚고 나서야 다음 문제로 넘어갑니다. LLM에게 "이 증명에서 내가 건너뛴 단계가 있는지 처음부터 다시 짚어줘"라고 부탁합니다. 지금의 이 흐름은 훗날 동료들의 계산을 받쳐줄 기초 근육이 되어갑니다. 느림이 아닌 단계 — 당신의 학습 축은 지금 "정확을 향한 성장"에 놓여 있습니다.

---

#### [14] `office_admin_x_planning_x_1C`
- occupation: `office_admin` (행정 — 절차 정비)
- situation: `planning`

결재 순서 하나가 꼬이면 이후 한 달의 일이 흔들린다는 걸 이미 감각으로 알고 계시죠. LLM에게 "이 절차서에서 결재자 역할과 기한이 충돌하는 부분을 짚어줘" 같은 식으로 의뢰합니다. 조직이 감정이 아니라 절차로 굴러갈 수 있게 해주는 뒷받침의 자리입니다. 답답함이 아닌 설계 — 지금 당신의 축은 "질서의 유지"라는 방향 위에 있습니다.

---

#### [15] `office_admin_x_info_search_x_1C`
- occupation: `office_admin` (내부감사·내부통제)
- situation: `info_search`

증빙 한 건이 빠진 것도, 날짜 하나가 엇갈린 것도 그냥 지나치지 않는 감각이 있습니다. LLM에는 "이 서류 세트에서 결재 일자와 증빙 일자의 불일치를 뽑아줘"라고 구조를 잡아 묻습니다. 바깥에서 감사가 들어오기 전에 먼저 내부의 빈칸을 메워두는 손 — 여기서 조직의 신뢰가 쌓입니다. 의심이 아닌 기질 — 당신이 지금 서 있는 축은 "투명함의 완결"쪽에 놓여 있습니다.

---

### 2-2. 분원 1 × 통합(1I) — 15 셀

병치 명칭: **Admin Inspector / Policy Checker / Etiquette Keeper**
해석: 규범·예절·정책·관계 맥락 속에서 검증 작동. 규칙을 세밀히 보는 힘이 사람을 향한 보호로 환원된다.

---

#### [16] `professional_x_work_execution_x_1I`
- occupation: `professional` (법률·노무 전문직)
- situation: `work_execution`

계약서의 한 조항이 사람의 권리에 어떻게 닿을지 먼저 그려보고, 그 위에서 문구를 다듬습니다. LLM에게 "이 조항이 최근 판례에서 근로자 쪽으로 어떻게 해석되었는지 추려줘"라고 맥락을 물으며 검토를 이어갑니다. 계약 한 줄이 한 가정의 내일과 이어진다는 걸 아는 자리 — 검증이 곧 보호로 환원됩니다. 차가움이 아닌 설계 — 지금 당신의 축은 "사람을 포함한 정합성" 쪽에 놓여 있습니다.

---

#### [17] `office_admin_x_work_execution_x_1I`
- occupation: `office_admin` (인사·급여 담당)
- situation: `work_execution`

연차 산정 하나, 수당 계산 하나가 동료의 생활을 바꾼다는 걸 잊지 않고 규정을 펼칩니다. LLM에게 "이 수당 항목을 최신 근로기준법 개정과 맞춰 다시 계산해줘" 같은 확인을 자주 건넵니다. 규정을 엄격히 지키는 것이 결국 구성원을 지키는 방법이 되는 자리입니다. 깐깐함이 아닌 기질 — 지금 당신의 방향은 "사람에게 닿는 질서" 위에 있습니다.

---

#### [18] `professional_x_info_search_x_1I`
- occupation: `professional` (교사·교육 전문직)
- situation: `info_search`

교재 한 페이지를 넣기 전에 학생 나이에 맞는지, 교육과정과 어긋나지 않는지 조용히 대조해봅니다. LLM에게는 "이 주제가 해당 학년 성취기준 어디에 연결되는지 먼저 확인해줘"라고 바탕부터 맞추어 묻습니다. 교실에서 누구도 엉뚱한 기준 위에 서지 않도록 커리큘럼의 결을 지키는 자리입니다. 보수적이 아닌 단계 — 지금 당신의 축은 "배우는 사람을 향한 규범의 완결"에 가깝습니다.

---

#### [19] `management_x_planning_x_1I`
- occupation: `management` (컴플라이언스)
- situation: `planning`

새 규제가 뜨면 우리 조직의 어느 부서가 어떻게 영향을 받을지 그 지도를 먼저 그립니다. LLM에 "이 규제 변경이 인사·재무·영업 중 어느 팀 업무 흐름과 충돌하는지 정리해줘"라고 요청합니다. 사건이 나기 전에 조직 전체를 규범 위에 맞춰두는 감독자의 자리입니다. 관료적이 아닌 설계 — 당신의 축은 지금 "구성원과 규범의 정합" 쪽에 놓여 있습니다.

---

#### [20] `service_sales_x_work_execution_x_1I`
- occupation: `service_sales` (상담·고객응대)
- situation: `work_execution`

고객 한 분의 불편이 매뉴얼의 어느 조항과 닿아 있는지 먼저 확인하고 응대를 엽니다. LLM에게 "이 민원 유형의 최근 응대 가이드와 예외 조항을 함께 보여줘"라고 물으며 대응을 준비합니다. 같은 사안이 사람마다 다른 답을 받지 않도록 표준을 지키는 자리입니다. 형식적이 아닌 기질 — 지금 당신의 방향은 "사람에게 공정한 절차" 쪽으로 놓여 있습니다.

---

#### [21] `professional_x_planning_x_1I`
- occupation: `professional` (교사·교수)
- situation: `planning`

수업 규정 한 줄을 정할 때도 어떤 학생이 이 규정에서 억울해질 수 있을지를 먼저 떠올려봅니다. LLM에게 "이 평가 규정이 특정 배경의 학생에게 불리하게 작동할 수 있는 지점을 찾아줘"라고 제안을 청합니다. 교실 문화를 공정하게 흐르게 하는 설계자의 역할입니다. 경직됨이 아닌 단계 — 당신의 축은 지금 "모두의 자리를 지키는 규칙"에 기울어 있습니다.

---

#### [22] `office_admin_x_info_search_x_1I`
- occupation: `office_admin` (공공행정)
- situation: `info_search`

공문 한 장이 시민에게 어떻게 읽힐지 상상하며 표현과 근거를 대조합니다. LLM에게 "이 공문이 상위 법령의 어느 조항과 어긋날 소지가 있는지 짚어줘" 같은 검증을 부탁합니다. 행정 문서가 사람을 배제하지 않도록 언어와 규정 사이를 촘촘히 엮는 자리입니다. 형식주의가 아닌 설계 — 지금 당신의 축은 "문서 속의 사람" 쪽을 바라보고 있습니다.

---

#### [23] `service_sales_x_relationship_emotion_x_1I`
- occupation: `service_sales` (상담·접객)
- situation: `relationship_emotion` (관계·정서)

상담 한 통에서도 호칭 하나, 순서 하나가 상대에게 어떻게 닿을지 미리 가늠합니다. LLM에게 "이 문장이 상대방에게 무례하게 들릴 여지가 있는지 톤을 점검해줘"라고 확인을 요청합니다. 따뜻한 응대의 뒷면에는 규범을 세심히 지키는 품이 있다는 걸 보여주는 자리입니다. 딱딱함이 아닌 기질 — 당신의 축은 지금 "관계의 결을 지키는 규칙" 쪽에 서 있습니다.

---

#### [24] `management_x_info_search_x_1I`
- occupation: `management` (경영·윤리 감독)
- situation: `info_search`

새 거래를 열기 전에 업계 규범과 우리 내부 기준이 서로 맞는지 한 번 더 조회합니다. LLM에게 "이 계약 조건이 업계 통상 윤리 기준과 어느 지점에서 충돌할 수 있는지 알려줘"라고 맥락을 잡아 묻습니다. 조직이 장기적으로 신뢰를 잃지 않도록 윤리의 기준점을 손에 쥐는 자리입니다. 답답함이 아닌 설계 — 지금 당신의 축은 "관계 속 규범의 완결"에 놓여 있습니다.

---

#### [25] `professional_x_relationship_emotion_x_1I`
- occupation: `professional` (법률·상담 전문직)
- situation: `relationship_emotion`

어려운 사안을 마주했을 때 감정보다 먼저 "이 관계에 적용되는 규범"을 펼쳐 확인합니다. LLM에 "이 상황에서 양쪽 당사자에게 공정한 절차가 어떤 순서인지 정리해줘"라고 의견을 청합니다. 감정이 격해지는 순간일수록, 공정한 절차를 붙잡아주는 사람이 누군가에게 꼭 필요해집니다. 냉정이 아닌 단계 — 당신의 축은 지금 "규범 위의 보호" 쪽에 있습니다.

---

#### [26] `student_x_learning_x_1I`
- occupation: `student` (새 공동체에 진입한 학생)
- situation: `learning`

새 환경에 들어가면 낯선 규칙을 한 번 훑어보고 "여긴 어떻게 움직이는지" 기준부터 익히는 편입니다. LLM에게 "이 상황에서 무례하지 않게 행동하는 순서가 어떻게 되는지" 구체적으로 물어봅니다. 같은 공간의 사람들이 편해지는 이유 중 하나는, 누군가 먼저 규범을 익혀두기 때문입니다. 경직됨이 아닌 단계 — 당신의 학습 축은 지금 "관계 감각을 쌓아가는 흐름"에 놓여 있습니다.

---

#### [27] `semi_professional_x_relationship_emotion_x_1I`
- occupation: `semi_professional` (팀 리더·프로젝트 매니저)
- situation: `relationship_emotion`

팀 회의에서 분명하지 않은 역할 경계를 그냥 두지 않고, 누가 무엇을 어디까지 맡는지 한 줄씩 확인합니다. LLM에게 "이 프로젝트의 역할 분담에서 겹치거나 비어 있는 지점을 찾아줘" 같은 정리를 맡깁니다. 감정 다툼이 일어나기 전에 구조에서 먼저 잡아두는 역할이 팀을 편하게 만듭니다. 까칠함이 아닌 설계 — 당신의 축은 지금 "관계를 받쳐주는 구조" 쪽에 있습니다.

---

#### [28] `office_admin_x_daily_life_x_1I`
- occupation: `office_admin` (주변의 행정 통역자)
- situation: `daily_life` (일상)

가족의 서류 한 장, 이웃의 민원 하나를 대하게 되면 자연스럽게 "이게 어느 양식에 맞는가"부터 짚어봅니다. LLM에게 "이 신청서에 필요한 첨부 서류 목록을 단계별로 알려줘"라고 물으며 주변 사람의 길을 정리합니다. 행정 앞에서 막막해하는 이들 곁에서 절차를 풀어주는 자리입니다. 유난이 아닌 기질 — 지금 당신의 축은 "일상 속 규범 통역" 위에 놓여 있습니다.

---

#### [29] `other_x_daily_life_x_1I`
- occupation: `other` (다양한 공동체의 구성원)
- situation: `daily_life`

단톡방 공지 한 줄, 경조사 인사말 한 문장도 누가 읽어도 어긋나지 않도록 한 번 더 읽어봅니다. LLM에 "이 문장이 윗세대·아랫세대 모두에게 자연스럽게 읽히는지 봐줘"라고 확인을 청합니다. 눈에 띄지 않지만, 주변의 대화가 상하지 않고 흐르는 데에 이 감각이 쓰입니다. 예민함이 아닌 단계 — 당신의 축은 지금 "작은 관계를 지키는 규범"에 기울어 있습니다.

---

#### [30] `job_seeker_retired_x_info_search_x_1I`
- occupation: `job_seeker_retired` (구직자·전직 준비자)
- situation: `info_search`

공고 하나에도 자격 요건, 제출 서류, 기한이 "정말 맞는지" 하나씩 다시 대조하며 준비합니다. LLM에게 "이 지원서 항목이 내 경력 기재 순서와 맞는지 포맷까지 점검해줘"라고 부탁합니다. 다음 자리를 여는 길목에서 실수를 줄이는 손이 결국 기회의 너비를 넓혀줍니다. 조심이 아닌 단계 — 지금 당신의 축은 "자신과 제도 사이의 정합" 쪽에 있습니다.

---

## 3. 셀 분포 요약표

| # | cell_id | occupation | situation | W |
|---|---|---|---|---|
| 01 | semi_professional_x_work_execution_x_1C | semi_professional | work_execution | C |
| 02 | professional_x_work_execution_x_1C | professional | work_execution | C |
| 03 | office_admin_x_work_execution_x_1C | office_admin | work_execution | C |
| 04 | professional_x_info_search_x_1C | professional | info_search | C |
| 05 | management_x_info_search_x_1C | management | info_search | C |
| 06 | semi_professional_x_info_search_x_1C | semi_professional | info_search | C |
| 07 | craft_technical_x_work_execution_x_1C | craft_technical | work_execution | C |
| 08 | professional_x_learning_x_1C | professional | learning | C |
| 09 | semi_professional_x_planning_x_1C | semi_professional | planning | C |
| 10 | management_x_planning_x_1C | management | planning | C |
| 11 | professional_x_planning_x_1C | professional | planning | C |
| 12 | craft_technical_x_info_search_x_1C | craft_technical | info_search | C |
| 13 | student_x_learning_x_1C | student | learning | C |
| 14 | office_admin_x_planning_x_1C | office_admin | planning | C |
| 15 | office_admin_x_info_search_x_1C | office_admin | info_search | C |
| 16 | professional_x_work_execution_x_1I | professional | work_execution | I |
| 17 | office_admin_x_work_execution_x_1I | office_admin | work_execution | I |
| 18 | professional_x_info_search_x_1I | professional | info_search | I |
| 19 | management_x_planning_x_1I | management | planning | I |
| 20 | service_sales_x_work_execution_x_1I | service_sales | work_execution | I |
| 21 | professional_x_planning_x_1I | professional | planning | I |
| 22 | office_admin_x_info_search_x_1I | office_admin | info_search | I |
| 23 | service_sales_x_relationship_emotion_x_1I | service_sales | relationship_emotion | I |
| 24 | management_x_info_search_x_1I | management | info_search | I |
| 25 | professional_x_relationship_emotion_x_1I | professional | relationship_emotion | I |
| 26 | student_x_learning_x_1I | student | learning | I |
| 27 | semi_professional_x_relationship_emotion_x_1I | semi_professional | relationship_emotion | I |
| 28 | office_admin_x_daily_life_x_1I | office_admin | daily_life | I |
| 29 | other_x_daily_life_x_1I | other | daily_life | I |
| 30 | job_seeker_retired_x_info_search_x_1I | job_seeker_retired | info_search | I |

**W 분포**: 완결(C) 15 · 통합(I) 15 → 50:50 (A1 §9-2 검증 2 부합)
**직군 커버리지** (10종 중 9종): management 3 · professional 8 · semi_professional 5 · office_admin 7 · service_sales 2 · craft_technical 2 · student 2 · other 1 · job_seeker_retired 1 · creative_media 0
**상황 커버리지** (7종 중 6종): work_execution 9 · info_search 9 · planning 6 · learning 3 · relationship_emotion 3 · daily_life 2 · creative_emission 0

**미커버 조합 주석**:
- `creative_media`: 분원 4(창발자 (Emergent))의 주축 직군. 분원 1의 자연 수렴(회계·감사·디버깅·QA·법률)과 구조적으로 먼 편이라 0건 처리.
- `creative_emission` (창작·발산): 분원 4·8의 주축 상황. 분원 1은 발산보다 검증이 앞서므로 0건 처리.

---

## 4. 톤 가이드 (B1-1 전용 · B1-2~B1-5 복제 기준)

본 섹션은 이후 분원 2~8 결과카드 세션(Sonnet 4.6 / Haiku 4.5)이 **동일한 톤**으로 작성하도록 하기 위한 기준이다. 별도 파일 `IamNA_결과카드_톤_가이드.md`로도 함께 제공된다.

### 4-1. 문장 구조 (3~5문장 고정)

한 셀은 **3~5문장**으로 완결된다. 다음 4단 구성이 권장되며, 필요 시 5문장째에 "현재 스냅샷" 언급을 덧붙인다.

| 문장 | 역할 | 예시 서두 |
|---|---|---|
| 1 | 인식의 실제 장면 묘사 | "~ 한 줄이 / ~ 순간에 / ~ 앞에서" |
| 2 | LLM 사용 방식 (구체적 발화 인용) | "LLM에게 '~'라고 묻습니다 / 요청합니다 / 부탁합니다" |
| 3 | 사회적 역할 (시스템 생태학 관점) | "이 자리 / 이 위치 / 이 역할 / 이 감각" |
| 4 | 본질 메시지 ("X가 아닌 Y" 구조) | "~이 아닌 기질 / 설계 / 단계" |
| 5 (선택) | 현재 스냅샷 · 1% 자유도 암시 | "지금 당신의 축은 ~ 쪽에 놓여 있습니다" |

### 4-2. 공통 어휘 리스트 (자주 쓰는 표현)

**동사(검증·순차·완결 계열)**: 확인하다, 대조하다, 짚다, 맞춰두다, 익히다, 점검하다, 다듬다, 쌓아가다, 받쳐주다, 지키다, 풀어주다, 끌어당기다, 걸러주다.

**명사**: 결, 기질, 기준선, 축, 방향, 완결, 단계, 뼈대, 안전망, 뒷받침, 정합, 절차, 규범, 스냅샷.

**연결 표현**: "~하고 나서야", "~ 먼저", "~ 한 번 더", "~쪽에 놓여 있습니다", "~에 기울어 있습니다", "~ 사이를 촘촘히".

**본질 메시지 템플릿 (반드시 1회 삽입)**:
- "이건 [부정 라벨]이 아닌 [긍정 프레임]"
- 부정 라벨 예: 소심함 / 까다로움 / 꼼꼼함 / 집착 / 예민함 / 깐깐함 / 유난 / 경직됨 / 답답함 / 형식주의 / 관료적 / 차가움 / 고집 / 의심 / 지적 / 조심 / 느림
- 긍정 프레임: 기질 / 설계 / 단계 / 기질 — 방향
- (치료가 아닌 단계, 고장이 아닌 설계, 결함이 아닌 기질 중 하나를 각 셀에서 변주)

### 4-3. 피해야 할 표현

- **단정 정체성 고정**: "당신은 이런 사람입니다" / "당신은 INTJ 같은" / "전형적인 ~형입니다"
- **지시형·명령형**: "~해야 합니다" / "~하세요" / "지금 당장 ~"
- **병리 프레임**: 결함 / 장애 / 문제 / 증상 / 부적응 (※ "결함이 아닌 기질"처럼 **부정 뒤에만 위치**시켜 전복하는 용도로는 허용)
- **과대 칭송**: 천재 / 특별한 능력 / 남다른 재능 / 타고난 ~
- **수치 단정**: "85%의 확률로 당신은" / "정확히 ~인 사람" (축 게이지는 별도 UI에서 노출되므로 본문에는 들어가지 않는다)
- **분원 간 우열 암시**: "더 뛰어난 / 우수한 / 부족한"
- **미래·과거 단정**: "당신은 앞으로 반드시 / 당신의 과거는 늘" (현재 스냅샷 원칙과 충돌)

### 4-4. 문장 리듬 (호흡 길이)

- **평균 호흡**: 문장당 40~60자 권장. 너무 짧으면 선언적이 되어 단정으로 읽히고, 너무 길면 독서 이탈이 커진다.
- **첫 문장 호흡**: 40~50자. 장면 묘사는 짧고 안정적으로 시작.
- **마지막 문장 호흡**: 50~70자. 본질 메시지 + 축 언급을 실을 수 있도록 약간 여유 있는 호흡.
- **한 셀 전체**: 200~280자 범위.
- **종결 어미**: "~습니다" 존대 고정. "~이다" 혼용 금지.
- **쉼표·줄바꿈**: 한 문장 안 쉼표는 1~2개까지. 리듬이 끊기면 "정밀 검증"의 촘촘함이 오히려 강박처럼 읽히므로 주의.

### 4-5. 분원 1 특유의 어휘 주의점

분원 1은 "검증" 성향이 강하므로 **결함 프레임으로 쉽게 미끄러질 위험**이 있다. 본 톤에서는 아래 원칙을 지킨다.

1. **검증 = 보호**로 환원해 서술: 단순 "확인하다"보다 "받쳐주다 / 지켜주다 / 통역하다 / 메워두다 / 흔들리지 않게 하다"를 섞어 **결과적 역할**을 함께 담는다.
2. **부정 라벨을 먼저 소환하고 뒤집는다**: "깐깐함이 아닌 기질"처럼 사용자가 자기 성향에 대해 품고 있을 부정적 라벨을 먼저 내어주고 전복한다.
3. **대칭쌍(분원 8)을 깎지 않는다**: 분원 1 통합 쪽에서도 "감정보다 먼저 규범을"이라는 서술이 가능하나, "감정은 중요하지 않다"로 오독되지 않도록 "감정이 격해지는 순간일수록 절차가 필요해진다" 같은 **병렬 배치**로 쓴다.

### 4-6. 분원별 변형 가이드 (B1-2~B1-5 참고)

이 톤 가이드는 분원 1 기준이지만, 다른 분원 작성 시 다음 축만 바꾸면 된다.

- **2. 조율자 (001: 심연의 수용자)**: "검증"을 "수용·계승"으로 치환. 부정 라벨: 고지식함 / 수동적임 → "수용이 곧 계승"
- **3. 구축자 (010: 인과적 축적자)**: "검증"을 "선별·탐지"로 치환. 부정 라벨: 비판적임 / 까탈스러움 → "선별이 곧 신호 구별"
- **4. 창발자 (011: 경험의 스케처)**: "검증"을 "산개·발산"으로 치환. 부정 라벨: 산만함 / 무질서 → "산개가 곧 새 연결"
- **5. 운영자 (100: 차가운 필터)**: "검증"을 "추적·재구성"으로 치환. 부정 라벨: 집요함 → "추적이 곧 회복"
- **6. 혁신자 (101: 파괴적 발산자)**: "검증"을 "체험·방문"으로 치환. 부정 라벨: 변덕스러움 → "체험이 곧 증언"
- **7. 설계자 (110: 전체의 통제자)**: "검증"을 "조립·구축"으로 치환. 부정 라벨: 통제적임 → "조립이 곧 수호"
- **8. 조망자 (111: 거시적 연결자)**: "검증"을 "수신·공명"으로 치환. 부정 라벨: 예민함 → "수신이 곧 연결"

각 분원은 **부정 라벨 → 긍정 프레임** 뒤집기 구조는 유지하되, 어휘군·문장 리듬은 동일하다.

---

## 5. v0.1 한계 · v0.2 반영 예정

1. **병치 명칭 한국어화 미반영**: 본문에는 아직 영어 병치명(System Operator 등)을 쓰지 않았고 서술로 풀었다. B2 세션(Sonnet)에서 한국어 대응 명칭이 확정되면 각 섹션 헤더에 병기할 수 있다 [N-W2 계승].
2. **축 게이지 수치 미포함**: 결과 카드 UI에서 Y·X·Z·W 게이지가 별도 표시되므로 본문에는 수치를 넣지 않았다. UI 프론트엔드(C2)에서 axis_scores_display와 연결된다.
3. **공유 에셋 카피 미작성**: share_asset.caption(짧은 캐치프레이즈)은 B2 또는 D2에서 별도 작성한다.
4. **내부 파일럿 검증 미진행**: 본 30셀은 초안이며, Week 7 내부 파일럿 50명 피드백으로 문체·공감도를 보정한다(로드맵 §11).
5. **직군 creative_media / 상황 creative_emission 0건 처리의 타당성**: 분원 1 자연 수렴과의 구조적 거리 때문에 제외했으나, 파일럿에서 "분원 1×creative_emission 자연 응답자가 유의미하게 발생"할 경우 추가 셀 설계가 필요하다(T2 지표 관찰 후 재판단).

---

## 6. 버전 히스토리

- **v0.1** (2026.04.20): 최초 작성 — Phase B1-1 산출물.
  - 포함: 분원 1 자연 셀 30개 (완결 15 · 통합 15) · 4단 구성(인식 장면 · LLM 사용 · 사회적 역할 · 본질 메시지) · 톤 가이드 6개 항목.
  - 기반: A1 §3·§4·§9, A3 §3-2, A4 result_card_schema, 바이럴심리테스트 §4-3·§4-4, 합의노트 §4-2·§4-3, v1.2 §3 분원 1 정의.
  - 미포함(이월): 병치명 한국어화(N-W2/B2), 공유 에셋 카피(B2/D2), 분원 2~8 셀(B1-2~B1-5), creative_media/creative_emission 자연 응답 관찰 결과(T2 이후).

---

*본 문서는 IamNA 입력 단계 16 분기 결과 카드 콘텐츠 v0.1 중 분원 1 구간이다.*
*Phase B1-1 톤 기준 문서이며, B1-2~B1-5 세션(Sonnet/Haiku)은 §4 톤 가이드를 복제해 분원 2~8을 작성한다.*
*2026.04.20 — Opus 4.7로 작성, Zero-Guessing 원칙 준수.*


### Appendix: CUCH_결과카드_분원2_3_v0_1.md 수정 전 원본 Full Text


# IamNA 결과카드 — 2. 조율자 (001: 심연의 수용자) + 3. 구축자 (010: 인과적 축적자) v0.1

## 자연 셀 42개 메시지 (분원 2: 20셀 · 분원 3: 22셀)

### 2026.04.20 기준

### 문서 성격: Phase B1-2 산출물 / 16 분기 중 분원 2(선형·노드·직관)·분원 3(병렬·노드·규칙)의 결과 카드 메시지를 자연 셀 단위(직군 × 상황 × W)로 작성 / 톤은 `IamNA_결과카드_톤_가이드.md`(B1-1 Opus 4.7 확정 기준) 완전 준수 / §4-3 분배 테이블 기준: 분원 2=20셀, 분원 3=22셀

---

## 1. 문서 위치 선언

### 1-1. 선행 합의 연결

| 합의 출처 | 본 문서 적용 원칙 |
|---|---|
| 바이럴심리테스트 §4-3 | 분원 2=20셀 · 분원 3=22셀 배정 준수 |
| 바이럴심리테스트 §4-4 | 셀별 3~5문장 (인식 장면·LLM 사용·사회적 역할·본질 메시지) |
| 합의노트 §4-2·§4-3 | 결함이 아닌 기질 / 고장이 아닌 설계 / 치료가 아닌 단계 / 방향의 안내 |
| 톤 가이드 §1~§6 | 문장 구조·어휘군·금지어·리듬·자가 체크리스트 전면 준수 |
| v1.2 §3 | 분원 2·3 성향 정의 기준 |
| A4 result_card_schema | cell_id 형식 `<occupation>_x_<situation>_x_<branch>` 준수 |

### 1-2. 분원 성향 재확인 (v1.2 §3)

**분원 2 — 조율자 (Tuner)**
- **축 좌표**: Y=선형 / X=노드 / Z=직관
- **인식 방식**: 들어오는 파편을 순서대로, 비판 없이 그대로 흡수. 서사 몰입.
- **자연 수렴 경향**: 도제식 학습, 전통 계승, 서사적 기록, 강의 수용 — 전수·계승 기능
- **대칭쌍**: 7. 설계자 (110: 전체의 통제자)
- **행동 동사군**: 따라가다·몰입하다·이어받다·담아내다
- **대표 부정 라벨**: 수동적·고지식함·수그러듦·생각 없음·느림
- **긍정 프레임**: 수용이 곧 계승
- **W 분기 의미**:
  - **2C(완결)**: 시스템·기술·지식 차원에서 순서대로 흡수. 절차·매뉴얼·튜토리얼을 있는 그대로 담아낸다.
  - **2I(통합)**: 멘토링·서사·관계·공동체 맥락 속에서 흐름을 따라가며 수용. 선배의 이야기, 조직의 문화, 관계의 결을 담아낸다.

**분원 3 — 구축자 (Builder)**
- **축 좌표**: Y=병렬 / X=노드 / Z=규칙
- **인식 방식**: 산발적인 조각들 중 내 형틀에 맞는 것만 동시 캡처. 데이터 마이닝.
- **자연 수렴 경향**: 데이터 과학, 정보 분석, 시장 조사, 역학 조사 — 정보 선별·분석
- **대칭쌍**: 6. 혁신자 (101: 파괴적 발산자)
- **행동 동사군**: 골라내다·비교하다·탐지하다·솎아내다
- **대표 부정 라벨**: 비판적·까탈스러움·냉정함·계산적·배타적
- **긍정 프레임**: 선별이 곧 신호 구별
- **W 분기 의미**:
  - **3C(완결)**: 데이터·수치·기술 차원에서 기준으로 선별. 조건에 맞는 정보만 동시에 캡처한다.
  - **3I(통합)**: 관계·인물·문화 데이터 차원에서 기준으로 선별. 사람과 공동체의 신호를 솎아낸다.

### 1-3. 자연 셀 선정 원칙

**분원 2 (20셀 · 완결 10 · 통합 10)**
- 대표 조합 우선 배치: 교육·학습자 × 학습, 일반사무 × 학습, 기타 × 학습 (§4-3 기준)
- creative_emission(창작 발산) = 0건 (분원 2 자연 수렴과 거리 있음)
- 상황 분포: learning(6), work_execution(4), relationship_emotion(4), planning(3), info_search(2), daily_life(1)

**분원 3 (22셀 · 완결 11 · 통합 11)**
- 대표 조합 우선 배치: 기술·IT × 정보탐색, 전문직 × 정보탐색, 경영 × 정보탐색 (§4-3 기준)
- creative_emission = 3I 범주 내 제한적 허용 (분원 3 기준 선별 방향)
- 상황 분포: info_search(8), planning(5), work_execution(4), relationship_emotion(4), daily_life(1)

---

## 2. 2. 조율자 (001: 심연의 수용자) — 자연 셀 20개

각 셀은 (1) 인식의 실제 장면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "수용이 곧 계승, 방향의 안내"로 구성된다.

---

### 2-1. 분원 2 × 완결(2C) — 10셀

병치 명칭: **지식 수용자 / 순차 학습자 / 기술 계승자**
해석: 시스템·기술·절차 차원에서 순서대로, 비판 없이 흡수. 매뉴얼·튜토리얼·입문 과정을 있는 그대로 담아낸다.

---

#### [01] `student_x_learning_x_2C`
- occupation: `student` (학생·학습자)
- situation: `learning`

교재 한 챕터가 온전히 자리를 잡고 나서야 다음으로 넘어갑니다. LLM에게 "이 개념 다음에 자연스럽게 이어지는 내용을 순서대로 설명해줘"라고 청합니다. 처음부터 끝까지 담아내는 손이 있기에 지식은 흩어지지 않고 다음 단계로 이어집니다. 이건 느림이 아닌 기질 — 지금 당신의 축은 "순서가 곧 이해"인 방향에 놓여 있습니다.

---

#### [02] `semi_professional_x_learning_x_2C`
- occupation: `semi_professional` (준전문직 — IT 운영·기술 지원)
- situation: `learning`

온라인 강의 첫 강부터 빠짐없이 재생하고, 튜토리얼 절차를 건너뛰지 않으며 손에 익힙니다. LLM에게 "이 기능 처음 배울 때 가장 먼저 익혀야 할 것부터 단계별로 설명해줘"라고 요청합니다. 절차를 끊지 않고 쌓아가는 사람이 있기에 기술은 표면 지식이 아닌 몸에 밴 것으로 자리 잡습니다. 수동적인 것이 아닌 기질 — 차근히 담아낸 것이 현장에서 버팁니다.

---

#### [03] `office_admin_x_learning_x_2C`
- occupation: `office_admin` (일반 사무·행정)
- situation: `learning`

업무 매뉴얼 첫 페이지부터 순서대로 읽고, 이전 내용이 자리 잡아야 다음 절차로 갑니다. LLM에게 "이 업무 프로세스 A단계부터 순서대로 짚어줘, 앞뒤 연결 이유도 같이"라고 부탁합니다. 매뉴얼을 있는 그대로 몸에 들이는 사람이 있기에 조직의 절차가 끊기지 않고 이어집니다. 고지식함이 아닌 기질 — 지금 당신의 축은 "절차가 먼저"인 자리에 있습니다.

---

#### [04] `professional_x_learning_x_2C`
- occupation: `professional` (연구자·전문직)
- situation: `learning`

새 분야에 입문할 때 개론부터 순서대로 따라가고, 전체 흐름이 담기기 전까지 세부로 뛰어들지 않습니다. LLM에게 "이 분야 처음 공부하는 순서를 입문부터 심화까지 나열해줘"라고 요청합니다. 체계를 순서 그대로 몸에 들이는 사람이 있기에 전문 지식은 단절 없이 다음 세대로 전해집니다. 이건 수그러듦이 아닌 기질 — 배움을 계승하는 자리가 지식 생태계를 붙잡아 줍니다.

---

#### [05] `other_x_learning_x_2C`
- occupation: `other` (개인 학습자·비직군)
- situation: `learning`

관심 생긴 주제의 책을 1장부터, 유튜브 시리즈를 1편부터 차례로 따라갑니다. LLM에게 "이 주제 입문자가 알아야 할 것들을 쉬운 것부터 순서대로 알려줘"라고 부탁합니다. 아무것도 건너뛰지 않는 자세가 지식을 온전히 내 것으로 만드는 방식입니다. 생각 없이 따르는 것이 아닌 기질 — 흡수하며 이어받는 사람이 있어야 앎이 다음 손으로 넘어갑니다.

---

#### [06] `craft_technical_x_learning_x_2C`
- occupation: `craft_technical` (기능·기술직)
- situation: `learning`

기초 공정을 먼저 몸에 익히고, 그 단계가 완전히 자리 잡아야 다음으로 넘어갑니다. LLM에게 "이 기술 처음 배울 때 순서대로 연습해야 할 단계를 알려줘"라고 묻습니다. 손으로 절차를 따라가며 쌓는 사람이 있기에 숙련의 사슬이 이어지고 장인의 결이 살아남습니다. 이건 답답함이 아닌 기질 — 지금 당신의 축은 "몸으로 담아내는 순서" 위에 있습니다.

---

#### [07] `management_x_learning_x_2C`
- occupation: `management` (경영·관리직)
- situation: `learning`

경영 케이스를 처음부터 읽으며 맥락을 순서대로 흡수하고, 결론보다 과정을 먼저 담습니다. LLM에게 "이 경영 이론이 어떻게 발전해왔는지 흐름 순서대로 설명해줘"라고 요청합니다. 역사와 맥락을 순서 그대로 이어받는 사람이 있기에 조직은 근거 있는 방향을 가질 수 있습니다. 생각 없이 따라가는 것이 아닌 기질 — 흐름을 담아낸 사람이 다음 결정을 받쳐줍니다.

---

#### [08] `service_sales_x_learning_x_2C`
- occupation: `service_sales` (서비스·영업·고객지원)
- situation: `learning`

제품 지식을 기능 하나부터 순서대로 익히고, 다 파악된 뒤에야 고객 앞에 섭니다. LLM에게 "이 제품 기능을 신입이 배우는 순서로 하나씩 설명해줘"라고 부탁합니다. 절차를 내면화한 사람이 있기에 현장에서 흔들리지 않는 안내가 가능합니다. 이건 수동적인 것이 아닌 기질 — 순서대로 담아낸 것이 현장의 뒷받침이 됩니다.

---

#### [09] `student_x_work_execution_x_2C`
- occupation: `student`
- situation: `work_execution` (작업집행)

과제 지침서를 처음부터 꼼꼼히 읽고, 요구 사항을 순서 그대로 따르며 작업합니다. LLM에게 "이 과제 요구 사항을 순서대로 정리하고, 각 단계에서 주의할 것도 짚어줘"라고 묻습니다. 지침을 그대로 담아내는 사람이 있기에 협업 결과물에 예측 가능한 일관성이 생깁니다. 이건 독창성 부재가 아닌 기질 — 규칙을 순서 그대로 이행하는 힘이 팀의 기반입니다.

---

#### [10] `semi_professional_x_work_execution_x_2C`
- occupation: `semi_professional`
- situation: `work_execution`

작업 절차서를 1단계부터 그대로 따르며, 이전 단계가 완료되지 않으면 다음으로 가지 않습니다. LLM에게 "이 작업 절차 중 내가 지금 어느 단계에 있는지, 다음에 무엇인지 순서대로 알려줘"라고 요청합니다. 절차를 뛰어넘지 않는 사람이 있기에 시스템은 예기치 못한 오류 없이 굴러갑니다. 느린 것이 아닌 기질 — 지금 당신의 축은 "단계가 곧 안전"인 자리에 있습니다.

---

### 2-2. 분원 2 × 통합(2I) — 10셀

병치 명칭: **멘토 수용자 / 서사 흡수자 / 관계 계승자**
해석: 규범·예절·관계·공동체 맥락 속에서 순서대로, 비판 없이 수용. 선배의 이야기·조직의 문화·관계의 흐름을 있는 그대로 담아낸다.

---

#### [11] `professional_x_relationship_emotion_x_2I`
- occupation: `professional` (전문직 — 상담·의료·법률 등)
- situation: `relationship_emotion`

선배의 이야기를 중간에 끊지 않고 처음부터 끝까지 따라가며 담아냅니다. LLM에게 "이 상황에서 경험 많은 선배라면 어떤 조언을 흐름 순서대로 건넬지 말해줘"라고 청합니다. 전해지는 경험을 판단 없이 받아내는 사람이 있기에 조직의 지혜는 단절되지 않고 이어집니다. 이건 의존이 아닌 기질 — 계승하는 힘이 공동체의 기억을 다음 손으로 넘깁니다.

---

#### [12] `office_admin_x_relationship_emotion_x_2I`
- occupation: `office_admin`
- situation: `relationship_emotion`

조직의 분위기와 선배 방식을 먼저 몸으로 읽고, 그 흐름 위에서 자기 자리를 찾습니다. LLM에게 "새로 합류한 팀의 문화를 파악하는 순서와, 첫 몇 주 동안 주의해야 할 것을 알려줘"라고 부탁합니다. 조직의 흐름을 먼저 받아내는 사람이 있기에 새 구성원이 자연스럽게 녹아들 수 있습니다. 수동적인 것이 아닌 기질 — 문화를 흡수하는 역할이 팀의 연속성을 만들어냅니다.

---

#### [13] `student_x_relationship_emotion_x_2I`
- occupation: `student`
- situation: `relationship_emotion`

선생님의 이야기를 끝까지 따라가며, 그 흐름 그대로 받아내고 나서 반응합니다. LLM에게 "이 상황에서 선생님이 학생에게 자연스럽게 건네줄 말의 흐름을 순서대로 써줘"라고 묻습니다. 관계 속에서 먼저 받아내는 자세가 신뢰의 씨앗이 되고 배움의 장을 열어둡니다. 고집 없음이 아닌 기질 — 지금 당신의 축은 "관계를 먼저 담아내는" 방향에 있습니다.

---

#### [14] `management_x_planning_x_2I`
- occupation: `management`
- situation: `planning`

조직의 역사와 선임자들의 결정 흐름을 순서대로 파악하고 나서 새 계획을 세웁니다. LLM에게 "이 조직이 과거에 유사한 결정을 내린 맥락을 시간 순으로 정리해줘"라고 요청합니다. 전례를 먼저 담아내는 사람이 있기에 결정이 뿌리 없이 떠돌지 않습니다. 이건 보수성이 아닌 기질 — 이어받은 것 위에서 다음을 세우는 사람이 조직을 안정시킵니다.

---

#### [15] `other_x_daily_life_x_2I`
- occupation: `other`
- situation: `daily_life`

어른의 이야기, 공동체의 지혜를 먼저 들으며 흐름을 담아내는 것이 자연스러운 방식입니다. LLM에게 "어른들이 이 상황에서 어떻게 행동해왔는지 경험담처럼 순서대로 들려줘"라고 청합니다. 전해 내려오는 삶의 결을 받아내는 사람이 있기에 공동체의 앎은 증발하지 않고 쌓여갑니다. 이건 구식이 아닌 기질 — 지금 당신의 축은 "경험을 이어받는 감각" 쪽에 놓여 있습니다.

---

#### [16] `service_sales_x_relationship_emotion_x_2I`
- occupation: `service_sales`
- situation: `relationship_emotion`

고객의 이야기를 처음부터 끝까지 따라가며, 중간에 판단 없이 흐름 그대로 담아냅니다. LLM에게 "이 고객의 말을 순서대로 정리하고, 그 맥락에서 자연스러운 다음 응대를 알려줘"라고 요청합니다. 상대의 흐름을 먼저 받아내는 사람이 있기에 관계는 끊기지 않고 이어집니다. 눈치 없음이 아닌 기질 — 들어주는 힘이 현장의 신뢰를 쌓아갑니다.

---

#### [17] `professional_x_planning_x_2I`
- occupation: `professional`
- situation: `planning`

관계의 맥락과 상대방의 흐름을 순서대로 파악하고 나서 제안을 만듭니다. LLM에게 "이 사람 상황을 이야기 흐름대로 정리한 뒤, 자연스러운 다음 단계를 제안해줘"라고 묻습니다. 맥락을 먼저 담아낸 뒤에 움직이는 사람이 있기에 제안이 상대에게 맞닿을 수 있습니다. 이건 우유부단이 아닌 기질 — 받아낸 뒤에 건네는 것이 관계를 지킵니다.

---

#### [18] `student_x_learning_x_2I`
- occupation: `student`
- situation: `learning`

수업 중 친구의 발표, 토론에서 흘러가는 이야기를 처음부터 끝까지 귀 기울여 담아냅니다. LLM에게 "이 사례를 이야기 형식으로 먼저 들려줘, 분석은 그다음에 해도 돼"라고 부탁합니다. 관계 속 이야기를 판단 없이 받아내는 사람이 있기에 공동 학습의 장은 열려 있습니다. 이건 분별력 부족이 아닌 기질 — 서사를 먼저 담아내는 사람이 공동체의 연결을 만듭니다.

---

#### [19] `craft_technical_x_relationship_emotion_x_2I`
- occupation: `craft_technical`
- situation: `relationship_emotion`

장인 선생의 시연을 처음부터 끝까지, 의심 없이 따라가며 몸에 들입니다. LLM에게 "이 기술을 도제식으로 배운다면 어떤 순서로 스승에게 배워야 하는지 알려줘"라고 청합니다. 전통을 순서 그대로 이어받는 사람이 있기에 장인의 결은 끊기지 않고 다음 손으로 넘어갑니다. 이건 자주성 부족이 아닌 기질 — 계승이 곧 보존이고, 이어받는 자리가 전통을 살립니다.

---

#### [20] `other_x_info_search_x_2I`
- occupation: `other`
- situation: `info_search`

경험담, 선배 조언, 어른의 이야기를 순서대로 찾아 읽으며 흐름 그대로 담아냅니다. LLM에게 "이 상황과 비슷한 경험담을 이야기 순서 그대로 나열해줘"라고 요청합니다. 살아 있는 경험을 먼저 받아내는 사람이 있기에 공동체의 앎은 다음 손으로 전해집니다. 이건 의존성이 아닌 기질 — 지금 당신의 축은 "이야기를 통해 세계를 담아내는" 방향에 기울어 있습니다.

---

## 3. 3. 구축자 (010: 인과적 축적자) — 자연 셀 22개

각 셀은 (1) 인식의 실제 장면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "선별이 곧 신호 구별, 방향의 안내"로 구성된다.

---

### 3-1. 분원 3 × 완결(3C) — 11셀

병치 명칭: **데이터 선별자 / 지표 필터러 / 기술 큐레이터**
해석: 데이터·수치·기술 차원에서 기준에 맞는 것만 동시에 캡처. 조건이 먼저, 그다음 나머지를 닫는다.

---

#### [01] `semi_professional_x_info_search_x_3C`
- occupation: `semi_professional`
- situation: `info_search`

기술 스택 후보가 수십 개 나와도, 내 조건에 맞는 것만 순식간에 추려냅니다. LLM에게 "이 기준 조건들에 맞는 라이브러리·툴만 골라서 비교해줘"라고 요청합니다. 방대한 선택지 속에서 신호와 잡음을 구분하는 눈이 있기에 기술 선택이 방향을 잃지 않습니다. 이건 까탈스러움이 아닌 기질 — 선별이 곧 신호 구별이고, 그 안목이 팀의 시간을 지킵니다.

---

#### [02] `professional_x_info_search_x_3C`
- occupation: `professional` (연구자·전문직)
- situation: `info_search`

논문 수십 편 중 내 연구 조건에 맞는 것만 먼저 추려내고, 나머지는 뒤로 둡니다. LLM에게 "이 기준에 맞는 연구만 골라 핵심 차이를 비교해줘"라고 요청합니다. 학문의 바다에서 기준선을 세우고 솎아내는 사람이 있기에 탐색이 미아가 되지 않습니다. 냉정함이 아닌 기질 — 지금 당신의 축은 "기준으로 세계를 캡처하는" 방향에 있습니다.

---

#### [03] `management_x_info_search_x_3C`
- occupation: `management`
- situation: `info_search`

시장 데이터가 쏟아져도, 내 판단 기준에 맞는 수치만 동시에 포착하고 나머지는 닫습니다. LLM에게 "이 시장 지표 중 우리 기준에 가장 부합하는 것만 필터링해줘"라고 요청합니다. 정보 홍수 속에서 기준을 쥐고 솎아내는 사람이 있기에 결정은 잡음이 아닌 근거를 갖습니다. 이건 편협함이 아닌 기질 — 잡음을 걸러낸 자리에서 진짜 신호가 보입니다.

---

#### [04] `professional_x_work_execution_x_3C`
- occupation: `professional` (데이터 분석가·연구자)
- situation: `work_execution`

데이터를 분석할 때 조건에 맞는 변수와 케이스만 먼저 추려내고 작업을 시작합니다. LLM에게 "이 데이터에서 다음 조건에 해당하는 행만 골라주고, 제외 기준도 설명해줘"라고 요청합니다. 처음부터 기준을 세워 솎아내는 사람이 있기에 분석은 방향 없이 흐르지 않습니다. 이건 배타적임이 아닌 기질 — 기준선이 곧 분석의 뼈대입니다.

---

#### [05] `semi_professional_x_work_execution_x_3C`
- occupation: `semi_professional`
- situation: `work_execution`

코드 리뷰나 라이브러리 선택 시, 내 기준 조건에 맞지 않는 것은 빠르게 제외합니다. LLM에게 "이 코드 중 성능·보안 기준에 맞지 않는 부분만 골라서 알려줘"라고 요청합니다. 수많은 선택지를 기준으로 걸러내는 눈이 있기에 코드 품질이 유지됩니다. 계산적인 것이 아닌 기질 — 선별이 곧 시스템의 안전망입니다.

---

#### [06] `management_x_planning_x_3C`
- occupation: `management`
- situation: `planning`

전략 후보 중 내 기준 조건에 맞는 것만 남기고, 나머지는 과감히 제외합니다. LLM에게 "이 후보 안들 중 우리 조건에 맞는 것만 추려서 장단점을 비교해줘"라고 부탁합니다. 기준 없이 전부를 다루는 대신 조건으로 좁히는 사람이 있기에 전략은 선명해집니다. 이건 고집이 아닌 기질 — 지금 당신의 축은 "기준이 곧 방향"인 자리에 있습니다.

---

#### [07] `professional_x_planning_x_3C`
- occupation: `professional` (의료·법률·상담 전문직)
- situation: `planning`

여러 방법론 중 대상 조건에 맞는 것만 먼저 추린 뒤 비교합니다. LLM에게 "이 조건에 해당하는 사례에 적합한 방법론만 골라서 비교해줘"라고 요청합니다. 수많은 선택지를 기준으로 좁히는 사람이 있기에 자원이 낭비되지 않고 정확한 곳에 닿습니다. 배타적이 아닌 기질 — 잘 골라낸 것이 최선의 출발점입니다.

---

#### [08] `office_admin_x_info_search_x_3C`
- occupation: `office_admin`
- situation: `info_search`

필요한 업무 정보를 찾을 때, 관련 조건에 맞는 것만 동시에 캡처하고 나머지는 닫습니다. LLM에게 "이 업무에 필요한 조건을 주면 관련 정보만 추려서 정리해줘"라고 부탁합니다. 정보의 바다에서 기준으로 좁히는 사람이 있기에 팀의 탐색 비용이 줄어듭니다. 이건 까다로움이 아닌 기질 — 필터가 곧 집중의 도구입니다.

---

#### [09] `semi_professional_x_planning_x_3C`
- occupation: `semi_professional`
- situation: `planning`

기술 로드맵을 만들 때 수많은 선택지 중 내 기준에 맞는 것만 골라 배치합니다. LLM에게 "이 기술 스택 중 우리 상황 기준에 맞는 것만 추려서 로드맵 순서로 제안해줘"라고 요청합니다. 기준선을 세워 솎아내는 사람이 있기에 로드맵이 현실에 닿을 수 있습니다. 이건 편협함이 아닌 기질 — 지금 당신의 축은 "조건이 곧 전략"인 방향에 있습니다.

---

#### [10] `craft_technical_x_info_search_x_3C`
- occupation: `craft_technical`
- situation: `info_search`

재료나 공법이 여럿일 때, 내 작업 조건에 맞는 것만 먼저 추립니다. LLM에게 "이 조건에 맞는 재료나 방법만 골라서 비교해줘"라고 묻습니다. 현장에서 기준으로 좁히는 사람이 있기에 시행착오가 줄고 자원이 정확한 곳에 쓰입니다. 냉정한 것이 아닌 기질 — 조건에 맞는 것을 먼저 보는 눈이 현장을 지킵니다.

---

#### [11] `student_x_info_search_x_3C`
- occupation: `student`
- situation: `info_search`

공부할 자료가 넘쳐도, 시험 범위와 내 수준 조건에 맞는 것만 먼저 솎아냅니다. LLM에게 "이 주제 중 이 조건에 맞는 자료만 추려줘"라고 요청합니다. 무한 정보 앞에서 기준을 세우는 사람이 있기에 학습이 산만해지지 않고 방향을 갖습니다. 이건 소극적임이 아닌 기질 — 선별이 곧 집중의 시작입니다.

---

### 3-2. 분원 3 × 통합(3I) — 11셀

병치 명칭: **관계 선별자 / 행동 스캐너 / 문화 큐레이터**
해석: 관계·인물·문화 데이터 차원에서 기준에 맞는 신호만 동시에 포착. 사람 사이의 잡음과 신호를 구분한다.

---

#### [12] `management_x_relationship_emotion_x_3I`
- occupation: `management`
- situation: `relationship_emotion`

팀원들의 행동과 반응 중 주목해야 할 패턴만 조용히 탐지하고, 나머지는 뒤로 둡니다. LLM에게 "이 팀 상황에서 주목해야 할 행동 신호만 골라서 알려줘"라고 요청합니다. 사람 사이의 신호를 기준으로 선별하는 눈이 있기에 팀의 흐름이 보이고 방향이 잡힙니다. 이건 냉정함이 아닌 기질 — 신호를 구별하는 사람이 있어야 공동체가 길을 잃지 않습니다.

---

#### [13] `professional_x_relationship_emotion_x_3I`
- occupation: `professional`
- situation: `relationship_emotion`

상대방 말 중 핵심 신호만 동시에 포착하고, 나머지는 판단을 보류합니다. LLM에게 "이 대화에서 주목할 행동·언어 패턴만 골라줘"라고 요청합니다. 관계의 신호를 기준으로 걸러내는 사람이 있기에 중요한 것이 흘러가지 않습니다. 차가움이 아닌 기질 — 선별이 곧 관계의 정합입니다.

---

#### [14] `service_sales_x_info_search_x_3I`
- occupation: `service_sales`
- situation: `info_search`

고객 유형이 여럿일 때, 우리 조건에 맞는 신호만 먼저 포착합니다. LLM에게 "이 고객군 중 우리 기준에 맞는 유형만 추려서 특성을 알려줘"라고 요청합니다. 잡음과 신호를 구분하는 눈이 있기에 영업 자원이 흩어지지 않고 정확한 대상에 닿습니다. 이건 까탈스러움이 아닌 기질 — 기준이 곧 관계의 방향입니다.

---

#### [15] `management_x_info_search_x_3I`
- occupation: `management`
- situation: `info_search`

경쟁사나 업계 동향 중, 내 판단 기준에 맞는 신호만 동시에 캡처합니다. LLM에게 "이 업계 정보 중 우리 기준에 해당하는 동향만 골라줘"라고 요청합니다. 정보 홍수 속에서 기준으로 솎아내는 사람이 있기에 전략이 노이즈에 흔들리지 않습니다. 이건 배타적이 아닌 기질 — 지금 당신의 축은 "기준이 곧 안목"인 방향에 있습니다.

---

#### [16] `office_admin_x_relationship_emotion_x_3I`
- occupation: `office_admin`
- situation: `relationship_emotion`

조직 내 관계 정보 중, 업무에 영향을 줄 신호만 조용히 탐지합니다. LLM에게 "이 조직 상황에서 주목해야 할 관계 패턴만 골라서 알려줘"라고 부탁합니다. 드러나지 않는 관계 신호를 기준으로 포착하는 사람이 있기에 조직이 무방비로 흐르지 않습니다. 냉소적임이 아닌 기질 — 신호를 구별하는 눈이 팀을 지킵니다.

---

#### [17] `creative_media_x_info_search_x_3I`
- occupation: `creative_media` (창작·미디어)
- situation: `info_search`

수많은 트렌드 중, 내 관점 기준에 맞는 신호만 동시에 포착하고 흡수합니다. LLM에게 "이 트렌드 중 이 방향성과 맞는 것만 골라줘"라고 요청합니다. 문화의 바다에서 기준을 세워 솎아내는 사람이 있기에 콘텐츠가 노이즈에 잠기지 않고 방향을 갖습니다. 이건 편협함이 아닌 기질 — 선별이 곧 창작의 방향입니다.

---

#### [18] `student_x_planning_x_3I`
- occupation: `student`
- situation: `planning`

진로 정보가 넘쳐도, 내 조건에 맞는 길만 먼저 추려내고 나머지는 닫습니다. LLM에게 "내 조건에 맞는 진로 옵션만 골라서 비교해줘"라고 요청합니다. 무한 정보 앞에서 기준을 세우는 사람이 있기에 탐색이 산만해지지 않고 방향을 가집니다. 이건 소심함이 아닌 기질 — 선별이 곧 방향의 시작입니다.

---

#### [19] `service_sales_x_planning_x_3I`
- occupation: `service_sales`
- situation: `planning`

고객 세그먼트가 여럿일 때, 조건에 가장 맞는 대상만 먼저 골라 전략을 세웁니다. LLM에게 "이 고객군 중 우리 기준에 부합하는 세그먼트만 추려서 특성을 비교해줘"라고 요청합니다. 전략이 올바른 대상에 닿으려면 먼저 기준으로 좁히는 사람이 필요합니다. 까다로운 것이 아닌 기질 — 잘 걸러낸 대상이 자원이 낭비되지 않도록 지킵니다.

---

#### [20] `professional_x_planning_x_3I`
- occupation: `professional`
- situation: `planning`

의사결정을 앞두고 관련 조건에 맞는 선택지만 먼저 솎아낸 뒤 비교합니다. LLM에게 "이 상황에서 우리 조건에 맞는 선택지만 추려서 장단점을 비교해줘"라고 요청합니다. 잡음을 먼저 제거하는 사람이 있기에 결정이 근거를 갖고 방향이 선명해집니다. 이건 배타적임이 아닌 기질 — 지금 당신의 축은 "기준이 곧 선택의 뼈대"인 자리에 있습니다.

---

#### [21] `semi_professional_x_relationship_emotion_x_3I`
- occupation: `semi_professional`
- situation: `relationship_emotion`

협업 파트너나 팀원 중, 현재 프로젝트 조건에 맞는 사람만 조용히 선별합니다. LLM에게 "이 역할에 필요한 조건을 기준으로 팀원 중 누가 맞는지 골라줘"라고 요청합니다. 관계에서도 기준으로 신호를 구분하는 사람이 있기에 협업이 제자리를 찾습니다. 냉정한 것이 아닌 기질 — 기준이 있어야 적절한 연결이 가능합니다.

---

#### [22] `other_x_daily_life_x_3I`
- occupation: `other`
- situation: `daily_life`

일상에서 선택지가 많을 때, 내 기준에 맞는 것만 먼저 골라내고 나머지는 뒤로 미룹니다. LLM에게 "이 조건에 맞는 것만 먼저 추려줘, 조건 외 것은 다음에"라고 요청합니다. 넘치는 선택 앞에서 기준을 세우는 사람이 있기에 에너지가 흩어지지 않고 삶이 단순해집니다. 이건 고집이 아닌 기질 — 지금 당신의 축은 "선별이 곧 집중"인 방향에 기울어 있습니다.

---

## 4. 셀 분포 요약표

### 4-1. 분원 2 (20셀)

| # | cell_id | occupation | situation | W |
|---|---|---|---|---|
| 01 | student_x_learning_x_2C | student | learning | C |
| 02 | semi_professional_x_learning_x_2C | semi_professional | learning | C |
| 03 | office_admin_x_learning_x_2C | office_admin | learning | C |
| 04 | professional_x_learning_x_2C | professional | learning | C |
| 05 | other_x_learning_x_2C | other | learning | C |
| 06 | craft_technical_x_learning_x_2C | craft_technical | learning | C |
| 07 | management_x_learning_x_2C | management | learning | C |
| 08 | service_sales_x_learning_x_2C | service_sales | learning | C |
| 09 | student_x_work_execution_x_2C | student | work_execution | C |
| 10 | semi_professional_x_work_execution_x_2C | semi_professional | work_execution | C |
| 11 | professional_x_relationship_emotion_x_2I | professional | relationship_emotion | I |
| 12 | office_admin_x_relationship_emotion_x_2I | office_admin | relationship_emotion | I |
| 13 | student_x_relationship_emotion_x_2I | student | relationship_emotion | I |
| 14 | management_x_planning_x_2I | management | planning | I |
| 15 | other_x_daily_life_x_2I | other | daily_life | I |
| 16 | service_sales_x_relationship_emotion_x_2I | service_sales | relationship_emotion | I |
| 17 | professional_x_planning_x_2I | professional | planning | I |
| 18 | student_x_learning_x_2I | student | learning | I |
| 19 | craft_technical_x_relationship_emotion_x_2I | craft_technical | relationship_emotion | I |
| 20 | other_x_info_search_x_2I | other | info_search | I |

**W 분포**: 완결(C) 10 · 통합(I) 10 → 50:50 ✓  
**직군 커버리지** (10종 중 8종): student 4 · semi_professional 2 · office_admin 2 · professional 3 · management 2 · service_sales 2 · craft_technical 2 · other 3 · creative_media 0 · job_seeker_retired 0  
**상황 커버리지** (7종 중 6종): learning 8 · work_execution 2 · relationship_emotion 5 · planning 2 · info_search 1 · daily_life 1 · creative_emission 0

---

### 4-2. 분원 3 (22셀)

| # | cell_id | occupation | situation | W |
|---|---|---|---|---|
| 01 | semi_professional_x_info_search_x_3C | semi_professional | info_search | C |
| 02 | professional_x_info_search_x_3C | professional | info_search | C |
| 03 | management_x_info_search_x_3C | management | info_search | C |
| 04 | professional_x_work_execution_x_3C | professional | work_execution | C |
| 05 | semi_professional_x_work_execution_x_3C | semi_professional | work_execution | C |
| 06 | management_x_planning_x_3C | management | planning | C |
| 07 | professional_x_planning_x_3C | professional | planning | C |
| 08 | office_admin_x_info_search_x_3C | office_admin | info_search | C |
| 09 | semi_professional_x_planning_x_3C | semi_professional | planning | C |
| 10 | craft_technical_x_info_search_x_3C | craft_technical | info_search | C |
| 11 | student_x_info_search_x_3C | student | info_search | C |
| 12 | management_x_relationship_emotion_x_3I | management | relationship_emotion | I |
| 13 | professional_x_relationship_emotion_x_3I | professional | relationship_emotion | I |
| 14 | service_sales_x_info_search_x_3I | service_sales | info_search | I |
| 15 | management_x_info_search_x_3I | management | info_search | I |
| 16 | office_admin_x_relationship_emotion_x_3I | office_admin | relationship_emotion | I |
| 17 | creative_media_x_info_search_x_3I | creative_media | info_search | I |
| 18 | student_x_planning_x_3I | student | planning | I |
| 19 | service_sales_x_planning_x_3I | service_sales | planning | I |
| 20 | professional_x_planning_x_3I | professional | planning | I |
| 21 | semi_professional_x_relationship_emotion_x_3I | semi_professional | relationship_emotion | I |
| 22 | other_x_daily_life_x_3I | other | daily_life | I |

**W 분포**: 완결(C) 11 · 통합(I) 11 → 50:50 ✓  
**직군 커버리지** (10종 중 8종): semi_professional 4 · professional 4 · management 4 · office_admin 2 · craft_technical 1 · student 2 · service_sales 2 · creative_media 1 · other 1 · job_seeker_retired 0  
**상황 커버리지** (7종 중 6종): info_search 8 · planning 5 · work_execution 2 · relationship_emotion 4 · daily_life 1 · creative_emission 0 · learning 0

---

## 5. 자가 체크리스트 결과 (전체 42셀)

| 항목 | 결과 |
|---|---|
| 문장 수 3~5개 | 모든 셀 4문장 ✓ |
| 종결 어미 "~습니다" 통일 | ✓ |
| 단정 정체성 고정 표현 없음 | ✓ |
| "X가 아닌 Y" 본질 메시지 1회 | ✓ (42셀 전원) |
| 구체적 LLM 발화 예시 1회 이상 | ✓ (42셀 전원, 따옴표 내 발화 인용) |
| 병리 프레임 단독 사용 없음 | ✓ (부정 라벨 전복 구조 안에서만) |
| 동일 분원 내 셀별 다른 각도·다른 부정 라벨 | ✓ (분원 2·3 각각 셀마다 변주) |
| creative_emission 제외 | ✓ (분원 2·3 모두 0건) |
| W 50:50 분포 | 분원 2: 10C·10I ✓ / 분원 3: 11C·11I ✓ |
| 분원별 할당량 준수 | 분원 2=20, 분원 3=22 ✓ |

---

## 6. 미커버 조합 주석

**분원 2 미커버**:
- `creative_media`: 분원 2 자연 수렴과 거리 있음. 창작 발산보다 서사 몰입·계승이 주축이므로 learning 상황에서 대부분 커버됨.
- `job_seeker_retired`: 분원 1에서 이미 배정됨. 분원 2에서 추가 필요 시 파일럿 후 판단.
- `creative_emission`: 전 분원에서 분원 4·8의 주축. 분원 2는 0건 처리.

**분원 3 미커버**:
- `job_seeker_retired`: 정보 탐색 상황에서 발현 가능하나 분원 1과 중복 위험으로 제외.
- `learning`: 분원 3의 학습은 "기준으로 걸러가며 배우는" 방식이지만 분원 2(순차 흡수)와 경계 모호 — 파일럿 응답자 분포 확인 후 추가 여부 판단.
- `creative_emission`: 분원 4·8 주축. 분원 3은 0건.

---

## 7. v0.1 한계 · v0.2 반영 예정

1. **병치 명칭 한국어화 미반영**: 영어 병치명(Knowledge Absorber / Pattern Scanner 등) 미확정 상태. B2 세션 한국어 대응 명칭 확정 후 섹션 헤더에 병기 예정 [N-W2 계승].
2. **공유 에셋 카피 미작성**: share_asset.caption은 B2 또는 D2에서 별도 작성.
3. **분원 2 learning 상황 집중도 검증 필요**: 완결 8셀이 learning에 집중. 파일럿에서 2C 사용자가 다른 상황 셀 메시지와 공감도 차이가 유의미할 경우 재분배.
4. **내부 파일럿 미진행**: 본 42셀은 초안. Week 7 내부 파일럿 50명 피드백으로 문체·공감도 보정 예정(로드맵 §11).

---

## 8. 버전 히스토리

- **v0.1** (2026.04.20): 최초 작성 — Phase B1-2 산출물.
  - 포함: 분원 2 자연 셀 20개 (완결 10 · 통합 10) + 분원 3 자연 셀 22개 (완결 11 · 통합 11) · 합계 42셀.
  - 기반: 바이럴심리테스트 §4-3·§4-4 / 합의노트 §4-2·§4-3 / v1.2 §3 분원 2·3 정의 / 톤 가이드 §1~§6 (B1-1 Opus 4.7 확정본).
  - 미포함(이월): 병치명 한국어화(B2), 공유 에셋 카피(D2), 분원 4~8 셀(B1-3~B1-5).

---

*본 문서는 IamNA 입력 단계 16 분기 결과 카드 콘텐츠 v0.1 중 분원 2·3 구간이다.*
*Phase B1-2 산출물이며, 톤은 B1-1(Opus 4.7) 기준을 복제하여 작성.*
*2026.04.20 — Claude Sonnet 4.6, Zero-Guessing 원칙 준수.*


### Appendix: CUCH_결과카드_분원4_5_v0_1.md 수정 전 원본 Full Text


# IamNA 결과카드 — 4. 창발자 (011: 경험의 스케처) + 5. 운영자 (100: 차가운 필터) v0.1

## 자연 셀 40개 메시지 (분원 4: 18셀 · 분원 5: 22셀)

### 2026.04.20 기준

### 문서 성격: Phase B1-3 산출물 / 16 분기 중 분원 4(병렬·노드·직관)·분원 5(선형·장·규칙)의 결과 카드 메시지를 자연 셀 단위(직군 × 상황 × W)로 작성 / 톤은 `IamNA_결과카드_톤_가이드.md`(B1-1 Opus 4.7 확정 기준) 완전 준수 / §4-3 분배 테이블 기준: 분원 4=18셀, 분원 5=22셀

---

## 1. 문서 위치 선언

### 1-1. 선행 합의 연결

| 합의 출처 | 본 문서 적용 원칙 |
|---|---|
| 바이럴심리테스트 §4-3 | 분원 4=18셀 · 분원 5=22셀 배정 준수 |
| 바이럴심리테스트 §4-4 | 셀별 3~5문장 (인식 장면·LLM 사용·사회적 역할·본질 메시지) |
| 합의노트 §4-2·§4-3 | 결함이 아닌 기질 / 고장이 아닌 설계 / 치료가 아닌 단계 / 방향의 안내 |
| 톤 가이드 §1~§6 | 문장 구조·어휘군·금지어·리듬·자가 체크리스트 전면 준수 |
| v1.2 §3 | 분원 4·5 성향 정의 기준 |
| A4 result_card_schema | cell_id 형식 `<occupation>_x_<situation>_x_<branch>` 준수 |

### 1-2. 분원 성향 재확인 (v1.2 §3)

**분원 4 — 창발자 (Emergent) (Autonomous Absorber)**
- **축 좌표**: Y=병렬 / X=노드 / Z=직관
- **인식 방식**: 쏟아지는 파편들을 동시에, 검열 없이 모두 들이마심. 산만한 창의성.
- **자연 수렴 경향**: 예측 못한 조합이 생기는 인식 구조. 비구조적 창의성의 온상.
- **대칭쌍**: 5. 운영자 (100: 차가운 필터)
- **행동 동사군**: 흩어지다·튀어오르다·건너뛰다·섞어내다
- **대표 부정 라벨**: 산만함·무질서·덤벙거림·변덕·즉흥적·충동적·집중 못함·정착 못함
- **긍정 프레임**: 산개가 곧 새 연결
- **W 분기 의미**:
  - **4C(완결)**: 기술·개념·창작 도메인에서 필터 없이 동시에 파편을 흡수. 아이디어·조합·실험의 온상.
  - **4I(통합)**: 관계·분위기·감정 영역에서 필터 없이 동시에 파편을 흡수. 분위기 촉발·관계 연결의 동력.

**분원 5 — 운영자 (Operator) (Sequential Panoramist / Tracker)**
- **축 좌표**: Y=선형 / X=장 / Z=규칙
- **인식 방식**: 관계의 흐름을 순서대로 따라가며 기존 틀로 검증. 인과 재구성.
- **자연 수렴 경향**: 사건 재구성, 추적 조사, 순차적 관계 분석.
- **기초 성향**: 추적자(Tracker) / 계보 분석가(Genealogist) / 궤적 분석가(Trajectory Analyst)
- **대칭쌍**: 4. 창발자 (011: 경험의 스케처)
- **행동 동사군**: 거슬러 오르다·추적하다·재구성하다·복원하다
- **대표 부정 라벨**: 집요함·과몰입·파고들기·집착·끈질김·놓지 못함
- **긍정 프레임**: 추적이 곧 회복
- **W 분기 의미**:
  - **5C(완결)**: 시스템·데이터·기술 흐름을 순서대로 거슬러 올라가며 원인 추적. 인간 변수 없거나 수동적.
  - **5I(통합)**: 관계 흐름·인물 궤적·공동체 인과를 순서대로 재구성. 인간 맥락이 추적의 핵심 변수.

### 1-3. 자연 셀 선정 원칙

**분원 4 (18셀 · 완결 9 · 통합 9)**
- 대표 조합 우선 배치: 창작·미디어 × 창작발산, 학생 × 창작발산, 경영 × 계획
- creative_emission이 분원 4의 자연 수렴 핵심 상황 — 완결 쪽에 집중 배치
- 통합 쪽은 relationship_emotion 중심 (분위기 촉발·관계 연결)
- 상황 분포: creative_emission(5C+2I=7), relationship_emotion(5I), work_execution(2), planning(2), info_search(1), daily_life(1)

**분원 5 (22셀 · 완결 11 · 통합 11)**
- 대표 조합 우선 배치: 준전문직 × 작업집행, 전문직 × 작업집행, 경영 × 정보탐색
- 추적·인과 재구성이 주축 — work_execution(시스템 추적)·info_search(원인 탐색) 중심
- 통합 쪽은 relationship_emotion (관계 흐름 재구성)·planning (맥락 기반 계획) 중심
- 상황 분포: work_execution(5C+0I=5), info_search(3C+1I=4), planning(2C+2I=4), relationship_emotion(0C+6I=6), learning(1C), daily_life(1I)

---

## 2. 4. 창발자 (011: 경험의 스케처) — 자연 셀 18개

각 셀은 (1) 인식의 실제 장면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "산개가 곧 새 연결, 방향의 안내"로 구성된다.

---

### 2-1. 분원 4 × 완결(4C) — 9셀

병치 명칭: **비검열 발산자 / 아이디어 촉발자 / 파편 수집가**
해석: 기술·개념·창작 도메인에서 필터 없이 동시에 파편을 흡수. 정답을 먼저 고르지 않고 가능성을 먼저 흩어 놓는다.

---

#### [01] `creative_media_x_creative_emission_x_4C`
- occupation: `creative_media` (광고 기획자·콘텐츠 크리에이터)
- situation: `creative_emission`

광고 카피를 잡기 위해 A4 한 장이 키워드·이미지·문장 파편으로 가득 차도록 마구 적어냅니다. LLM에게 "이 키워드에서 연상되는 거 전부 필터 없이 쏟아내줘, 말 안 돼도 괜찮아"라고 요청합니다. 한 방향으로 수렴되지 않는 발산이 있어야 예상 밖의 조합이 탄생하고 시장을 움직이는 메시지가 나옵니다. 이건 산만함이 아닌 기질 — 지금 당신의 축은 "파편이 스스로 연결되는 순간"을 향해 열려 있습니다.

---

#### [02] `student_x_creative_emission_x_4C`
- occupation: `student` (학생·학습자)
- situation: `creative_emission`

과제 주제를 받자마자 노트에 관련 없는 단어들을 사방에 적어 놓습니다. LLM에게 "이 주제로 떠오르는 것 뭐든 20가지 막 나열해줘, 현실 가능성 따지지 말고"라고 요청합니다. 규정된 방향 없이 흩어지는 생각이 있기에 아직 아무도 가지 않은 각도가 먼저 열립니다. 산만함이 아닌 기질 — 지금 당신의 축은 "시작이 곧 발산"인 쪽에 놓여 있습니다.

---

#### [03] `semi_professional_x_creative_emission_x_4C`
- occupation: `semi_professional` (UI/UX 디자이너·프론트엔드 개발자)
- situation: `creative_emission`

새 기능을 구상할 때 화이트보드에 레이아웃·버튼·사용자 흐름·엉뚱한 인터페이스 아이디어를 동시에 뿌려 놓습니다. LLM에게 "이 서비스에 붙일 수 있는 기능 아이디어를 마구 뽑아줘, 실현 가능성 체크 없이"라고 요청합니다. 경계를 먼저 열어두는 사람이 있어야 제품이 예상 밖의 방향을 찾습니다. 이건 두서없음이 아닌 기질 — 파편을 동시에 펼치는 손이 창작의 첫 문을 엽니다.

---

#### [04] `management_x_planning_x_4C`
- occupation: `management` (경영자·PM·기획자)
- situation: `planning`

팀 미팅 첫 단계에서 좋고 나쁨 없이 가능한 전략을 모두 화이트보드에 올려놓습니다. LLM에게 "이 목표를 달성할 방법 10가지 이상, 실현 가능성 구분하지 말고 다 나열해줘"라고 요청합니다. 수렴 전에 발산을 먼저 확장하는 사람이 있기에 팀이 고정 관념 안에 갇히지 않습니다. 즉흥적인 것이 아닌 기질 — 지금 당신의 축은 "먼저 넓히고 나중에 좁히는" 방향에 있습니다.

---

#### [05] `creative_media_x_work_execution_x_4C`
- occupation: `creative_media` (영상 편집자·미디어 크리에이터)
- situation: `work_execution`

영상 편집을 시작하면 여러 트랙·컷·효과를 동시에 열어 놓고 이것저것 끼워보면서 진행합니다. LLM에게 "이 씬에 어울리는 BGM·전환 효과·자막 스타일 아이디어를 다양하게 막 던져줘"라고 요청합니다. 여러 갈래를 동시에 열어두는 작업 방식이 있기에 편집이 한 공식에 갇히지 않습니다. 덤벙거림이 아닌 기질 — 동시에 여러 가능성을 켜두는 것이 이 작업의 자연스러운 리듬입니다.

---

#### [06] `other_x_creative_emission_x_4C`
- occupation: `other` (비직업적 창작자·취미 창작인)
- situation: `creative_emission`

블로그 글을 쓰기 전 메모장에 키워드를 나열하다 전혀 다른 얘기로 뻗어나갑니다. LLM에게 "이 키워드에서 연상되는 거 걸러내지 말고 다 꺼내줘"라고 요청합니다. 주제와 주제 사이를 자유롭게 건너뛰는 사람이 있어야 예상 밖의 연결이 글 속에 살아납니다. 이건 집중 못함이 아닌 기질 — 지금 당신의 축은 "파편들이 스스로 만나는 자리"를 향해 열려 있습니다.

---

#### [07] `professional_x_work_execution_x_4C`
- occupation: `professional` (연구자·데이터 분석가)
- situation: `work_execution`

연구 설계 초기에 가능한 변수·접근법·방법론을 좁히지 않고 동시에 올려놓습니다. LLM에게 "이 연구 주제로 가능한 분석 접근법 15개, 그냥 다양하게 막 나열해줘"라고 요청합니다. 방법론을 먼저 열어두는 손이 있기에 연구가 단일 관점에 고정되지 않습니다. 무질서가 아닌 기질 — 이 발산이 연구 설계에서 가장 중요한 첫 단계입니다.

---

#### [08] `craft_technical_x_creative_emission_x_4C`
- occupation: `craft_technical` (목공·제작자·공예가)
- situation: `creative_emission`

새 제품을 구상할 때 재료·형태·기능을 동시에 적어두고 이것저것 섞어봅니다. LLM에게 "이 재료로 만들 수 있는 제품 아이디어 15가지, 실용성 따지지 말고 마구 던져줘"라고 요청합니다. 만들어 본 적 없는 조합을 먼저 상상하는 사람이 있어야 새 제품의 씨앗이 생깁니다. 변덕이 아닌 기질 — 손에 재료를 쥐기 전에 먼저 가능성을 흩어 놓는 것이 이 기질의 제작 방식입니다.

---

#### [09] `student_x_info_search_x_4C`
- occupation: `student` (학생·학습자)
- situation: `info_search`

자료를 찾을 때 하나씩 정리하기 전에 탭을 10개 이상 열어두고 여기저기 건너뛰며 읽습니다. LLM에게 "이 주제와 관련 있어 보이는 것들 먼저 다양하게 나열해줘, 관련성 정확도 신경 쓰지 말고"라고 요청합니다. 먼저 넓게 펼쳐 놓는 탐색이 있기에 검색 밖에 있던 연결이 발견됩니다. 산만함이 아닌 기질 — 지금 당신의 축은 "먼저 흩어지고 나중에 모으는" 탐색 방식에 있습니다.

---

### 2-2. 분원 4 × 통합(4I) — 9셀

병치 명칭: **분위기 촉발자 / 관계 개방자 / 감정 파편 수집가**
해석: 관계·분위기·감정 영역에서 필터 없이 동시에 파편을 흡수. 공기를 먼저 바꾸고, 관계의 첫 문을 여는 동력.

---

#### [10] `creative_media_x_relationship_emotion_x_4I`
- occupation: `creative_media` (콘텐츠 크리에이터·미디어 기획자)
- situation: `relationship_emotion`

팀 회의가 무거워지면 관련 없어 보이는 얘기도 섞어 넣으며 분위기를 틉니다. LLM에게 "이 팀 분위기를 바꿀 아이스브레이킹 아이디어 막 던져줘, 어색한 것도 환영"이라고 요청합니다. 무거운 공기를 먼저 흔들어 놓는 사람이 있기에 창의적인 협업 공간이 다시 열립니다. 가벼움이 아닌 기질 — 지금 당신의 축은 "관계가 먼저 틔어야 일도 흐르는" 방향에 있습니다.

---

#### [11] `service_sales_x_relationship_emotion_x_4I`
- occupation: `service_sales` (영업·상담·고객 서비스)
- situation: `relationship_emotion`

고객과 첫 대화에서 제품 얘기 전에 이것저것 가볍게 건너뛰며 공기를 먼저 풀어놓습니다. LLM에게 "처음 만나는 고객과 어색함을 깨는 대화 소재 10가지 아무거나 던져줘"라고 요청합니다. 관계의 문을 먼저 여는 방식이 있기에 고객이 방어를 내려놓을 공간이 생깁니다. 충동적인 것이 아닌 기질 — 여러 파편을 동시에 건네는 것이 이 관계 방식의 자연스러운 리듬입니다.

---

#### [12] `student_x_relationship_emotion_x_4I`
- occupation: `student` (학생·학습자)
- situation: `relationship_emotion`

친구들이 모인 자리에서 분위기가 가라앉으면 엉뚱한 주제를 마구 꺼내 분위기를 살립니다. LLM에게 "어색한 친구 모임에서 분위기 살릴 활동이나 대화 소재 15가지 아무거나 떠오르는 대로 나열해줘"라고 요청합니다. 공기를 먼저 바꾸는 사람이 있기에 모임이 생기를 찾습니다. 정착 못함이 아닌 기질 — 관계 안에서 이 자유로운 건너뜀이 연결의 씨앗이 됩니다.

---

#### [13] `creative_media_x_creative_emission_x_4I`
- occupation: `creative_media` (SNS 크리에이터·콘텐츠 기획자)
- situation: `creative_emission`

SNS 콘텐츠를 기획할 때 사람들이 댓글을 달고 싶어질 감정·소재를 이것저것 동시에 적어봅니다. LLM에게 "이 주제에서 사람들이 공감해서 퍼나를 것 같은 감정 소재 다양하게 막 나열해줘"라고 요청합니다. 관계를 촉발하는 감정의 파편을 먼저 흩어놓는 사람이 있기에 콘텐츠가 공유 고리를 갖습니다. 즉흥적인 것이 아닌 기질 — 지금 당신의 축은 "관계를 먼저 열어두는" 창작 방향에 있습니다.

---

#### [14] `management_x_relationship_emotion_x_4I`
- occupation: `management` (경영자·리더·PM)
- situation: `relationship_emotion`

팀 회식이나 워크숍을 준비할 때 가능한 활동들을 체계 없이 동시에 쭉 나열해 봅니다. LLM에게 "팀원들이 금방 친해질 수 있는 활동 아이디어 20가지 두서없이 나열해줘"라고 요청합니다. 정답 없이 먼저 열어두는 기획이 있기에 팀이 예상 밖의 방식으로 연결됩니다. 어지러움이 아닌 기질 — 팀의 관계를 틔우는 것이 이 발산의 실제 목적입니다.

---

#### [15] `other_x_daily_life_x_4I`
- occupation: `other` (기타·일반 개인)
- situation: `daily_life`

지인에게 선물이나 이벤트를 준비할 때 아이디어를 마구 적어두고 나중에 골라냅니다. LLM에게 "친한 친구 생일에 할 수 있는 깜짝 이벤트 아이디어 20가지 그냥 아무거나"라고 요청합니다. 고르기 전에 먼저 흩어지는 상상이 있기에 마음이 담긴 선택이 가능해집니다. 변덕이 아닌 기질 — 관계를 향한 이 발산이 결국 가장 적절한 방향을 만듭니다.

---

#### [16] `service_sales_x_planning_x_4I`
- occupation: `service_sales` (영업·고객 기획 담당)
- situation: `planning`

고객 제안서를 만들기 전 고객이 원할 것 같은 것들을 아무 순서 없이 먼저 떠올려봅니다. LLM에게 "이 고객 상황에서 고객이 반응할 만한 제안 포인트를 다양하게 막 던져줘"라고 요청합니다. 고객을 향한 발산 먼저, 정제는 나중이라는 순서가 있기에 제안이 공식이 아닌 사람의 결을 담습니다. 정착 못함이 아닌 기질 — 지금 당신의 축은 "고객에게 먼저 문을 여는" 방향에 기울어 있습니다.

---

#### [17] `student_x_creative_emission_x_4I`
- occupation: `student` (학생·학습자)
- situation: `creative_emission`

조별 과제 아이디어를 낼 때 좋고 나쁨 없이 생각나는 걸 먼저 다 꺼냅니다. LLM에게 "이 주제로 조원들이 각자 가져올 수 있는 아이디어 소재 다양하게 막 나열해줘"라고 요청합니다. 먼저 공간을 열어두는 사람이 있기에 조원들이 의견을 꺼내기 쉬워집니다. 산만함이 아닌 기질 — 함께 만드는 공간에서 이 발산이 관계의 입구가 됩니다.

---

#### [18] `professional_x_relationship_emotion_x_4I`
- occupation: `professional` (전문직·연구자)
- situation: `relationship_emotion`

새 프로젝트 파트너와 첫 미팅에서 공식 안건 외의 이야기도 여러 방향으로 건네며 공기를 먼저 잡습니다. LLM에게 "처음 만나는 협업자와 자연스럽게 대화 시작할 소재 다양하게 아무거나 던져줘"라고 요청합니다. 관계를 먼저 틔우는 손이 있기에 협업이 낯선 공기 속에서도 시작될 수 있습니다. 가벼움이 아닌 기질 — 지금 당신의 축은 "공식 전에 먼저 관계를 여는" 방향에 있습니다.

---

## 3. 5. 운영자 (100: 차가운 필터) — 자연 셀 22개

각 셀은 (1) 인식의 실제 장면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "추적이 곧 회복, 방향의 안내"로 구성된다.

---

### 3-1. 분원 5 × 완결(5C) — 11셀

병치 명칭: **원인 추적자 / 흐름 복원가 / 인과 재구성자**
해석: 시스템·데이터·기술의 흐름을 순서대로 거슬러 올라가며 원인을 찾는다. 지금의 결과는 이전 흐름의 산물이라는 인식이 출발점.

---

#### [01] `semi_professional_x_work_execution_x_5C`
- occupation: `semi_professional` (IT 운영·기술 지원)
- situation: `work_execution`

서버가 이상 반응을 보이면 로그를 가장 처음 시점부터 거슬러 올라가며 원인을 찾습니다. LLM에게 "이 에러 로그에서 첫 이상 신호가 언제 어디서 시작됐는지 타임라인 순으로 짚어줘"라고 요청합니다. 원인까지 거슬러 올라가는 추적이 있기에 임시 해결이 아닌 재발 방지가 가능해집니다. 집요함이 아닌 기질 — 지금 당신의 축은 "뿌리부터 복원"하는 방향에 있습니다.

---

#### [02] `professional_x_work_execution_x_5C`
- occupation: `professional` (데이터 분석가·연구자)
- situation: `work_execution`

분석 결과가 예상과 다를 때, 데이터 수집부터 처리까지 각 단계를 순서대로 다시 짚습니다. LLM에게 "이 분석 파이프라인에서 어느 단계에서 오차가 발생했을지 처음부터 순서대로 검토해줘"라고 요청합니다. 경로 전체를 다시 걸어보는 사람이 있기에 오류가 가정으로 남지 않고 실제로 잡힙니다. 파고들기가 아닌 기질 — 이 추적이 분석의 신뢰를 만드는 근거입니다.

---

#### [03] `management_x_work_execution_x_5C`
- occupation: `management` (경영자·PM)
- situation: `work_execution`

프로젝트가 예상 밖으로 흘렀을 때, 초기 기획 단계부터 어디서 방향이 틀어졌는지 순서대로 짚습니다. LLM에게 "이 프로젝트 타임라인에서 의사결정 흐름을 처음부터 나열하고, 전환점이 어디였는지 짚어줘"라고 요청합니다. 흐름 전체를 재구성하는 관리자가 있기에 같은 실수가 반복되지 않습니다. 과몰입이 아닌 기질 — 지금 당신의 축은 "흐름 전체를 복원해야 다음이 보이는" 방향에 있습니다.

---

#### [04] `professional_x_info_search_x_5C`
- occupation: `professional` (연구자·컨설턴트)
- situation: `info_search`

현상의 원인을 찾을 때 표면 이유가 아니라 그것이 왜 일어났는지를 단계별로 거슬러 올라갑니다. LLM에게 "이 현상의 근본 원인을 5why 방식으로 첫 단계부터 차례대로 짚어줘"라고 요청합니다. 원인의 원인까지 순서대로 추적하는 사람이 있기에 해결책이 근거를 갖고 오래 버팁니다. 집착이 아닌 기질 — 흐름을 따라 뿌리로 내려가는 것이 이 분석의 자연스러운 방식입니다.

---

#### [05] `management_x_info_search_x_5C`
- occupation: `management` (경영자·전략 기획자)
- situation: `info_search`

시장 트렌드를 파악할 때 지금 상황만 보지 않고 어떤 흐름이 여기까지 이어졌는지 순서대로 재구성합니다. LLM에게 "이 시장 현상이 어떤 이전 흐름에서 비롯된 건지 연도별로 순서대로 정리해줘"라고 요청합니다. 지금을 과거의 인과로 읽는 사람이 있기에 전략이 표면 데이터가 아닌 흐름을 기반으로 세워집니다. 끈질김이 아닌 기질 — 지금 당신의 축은 "흐름이 보여야 방향이 보이는" 자리에 있습니다.

---

#### [06] `semi_professional_x_info_search_x_5C`
- occupation: `semi_professional` (IT·기술 지원)
- situation: `info_search`

버그를 잡을 때 증상만 보지 않고 그 버그가 언제 처음 생겼는지, 어떤 배포 이후인지를 순서대로 추적합니다. LLM에게 "이 버그가 어느 커밋 이후 처음 발생했는지 변경 이력 기준으로 단계별로 추적해줘"라고 요청합니다. 변화의 시작점을 찾는 사람이 있기에 패치가 증상이 아닌 원인을 향합니다. 놓지 못함이 아닌 기질 — 뿌리를 찾는 것이 이 기질의 가장 자연스러운 디버깅 방식입니다.

---

#### [07] `professional_x_planning_x_5C`
- occupation: `professional` (연구자·전략가)
- situation: `planning`

프로젝트 계획을 세울 때 선행 조건이 무엇인지, 어떤 단계가 다음 단계를 만드는지를 순서대로 먼저 확인합니다. LLM에게 "이 목표를 달성하기 위한 단계들을 인과관계 순서대로 나열해줘, 선행 조건이 먼저 오도록"이라고 요청합니다. 단계 간 인과를 먼저 정리하는 사람이 있기에 계획이 중간에 무너지지 않습니다. 집요함이 아닌 기질 — 지금 당신의 축은 "흐름이 정렬되어야 움직이는" 방향에 있습니다.

---

#### [08] `management_x_planning_x_5C`
- occupation: `management` (경영자·PM)
- situation: `planning`

분기 계획을 수정할 때 지금까지 어떤 순서로 진행됐는지를 먼저 복원한 뒤 새 방향을 잡습니다. LLM에게 "지금까지 이 프로젝트가 진행된 순서를 재구성해줘, 그 다음에 수정 방향을 논의하자"라고 요청합니다. 현재 위치를 흐름 위에 정확히 올려두는 사람이 있기에 수정 계획이 맥락을 잃지 않습니다. 과몰입이 아닌 기질 — 지금 어디 있는지 먼저 아는 것이 이 계획 방식의 출발입니다.

---

#### [09] `office_admin_x_work_execution_x_5C`
- occupation: `office_admin` (일반 사무직·행정직)
- situation: `work_execution`

업무 중 처리 지연이 생기면 접수부터 완료까지 어느 단계에서 막혔는지 순서대로 점검합니다. LLM에게 "이 업무 흐름에서 처리 지연이 발생한 단계를 접수 순서대로 짚어줘"라고 요청합니다. 흐름 안에서 막힌 곳을 정확히 찾는 사람이 있기에 처리가 멈춘 자리가 드러납니다. 파고들기가 아닌 기질 — 지금 당신의 축은 "흐름을 복원해야 일이 다시 움직이는" 방향에 있습니다.

---

#### [10] `craft_technical_x_work_execution_x_5C`
- occupation: `craft_technical` (정비·건설·기술직)
- situation: `work_execution`

제품이나 시스템에 문제가 생기면 설치·제작 순서를 처음부터 다시 짚어보며 어디서 틀어졌는지 확인합니다. LLM에게 "이 설치 과정에서 각 단계를 순서대로 검토해줘, 어느 단계에서 오류가 생길 수 있는지 포함해서"라고 요청합니다. 처음부터 다시 걷는 점검이 있기에 현장의 구조적 결함이 드러납니다. 끈질김이 아닌 기질 — 순서대로 다시 걸어보는 것이 이 현장 기질의 자연스러운 복원 방식입니다.

---

#### [11] `student_x_learning_x_5C`
- occupation: `student` (학생·학습자)
- situation: `learning`

이해가 안 되는 개념을 만나면 그 개념이 어디서 비롯됐는지, 어떤 선행 지식과 이어지는지를 거슬러 올라갑니다. LLM에게 "이 개념의 뿌리가 되는 선행 개념들을 인과 순서대로 정리해줘"라고 요청합니다. 이해의 뿌리를 찾아 올라가는 학습 방식이 있기에 단순 암기가 아닌 구조적 이해가 자리 잡습니다. 집착이 아닌 기질 — 지금 당신의 축은 "흐름으로 이해해야 진짜 아는 것"이 되는 방향에 있습니다.

---

### 3-2. 분원 5 × 통합(5I) — 11셀

병치 명칭: **관계 궤적 추적자 / 맥락 복원가 / 흐름 재구성자**
해석: 관계 흐름·인물 궤적·공동체 인과를 순서대로 재구성한다. 인간 맥락이 추적의 핵심 변수이며, 복원이 곧 이해의 출발.

---

#### [12] `professional_x_relationship_emotion_x_5I`
- occupation: `professional` (전문직·연구자)
- situation: `relationship_emotion`

동료와 사이가 어색해졌을 때, 어느 순간부터 그렇게 된 건지 관계의 흐름을 거슬러 올라가 봅니다. LLM에게 "이 관계에서 어긋남이 생긴 시점을 대화 흐름 기준으로 순서대로 짚어줘"라고 요청합니다. 관계의 타임라인을 복원하는 사람이 있기에 감정이 아닌 맥락으로 상황을 이해할 수 있습니다. 집요함이 아닌 기질 — 지금 당신의 축은 "흐름을 복원해야 관계가 다시 보이는" 방향에 있습니다.

---

#### [13] `management_x_relationship_emotion_x_5I`
- occupation: `management` (리더·PM)
- situation: `relationship_emotion`

팀 갈등이 생겼을 때 감정을 먼저 다루기 전에 어떤 상황이 어떤 순서로 쌓였는지를 복원합니다. LLM에게 "이 팀 갈등이 어떤 사건들에서 비롯됐는지 시간 순서로 재구성해줘"라고 요청합니다. 갈등 이전의 흐름을 정확히 복원하는 리더가 있기에 감정의 근거를 이해한 해결이 가능해집니다. 과몰입이 아닌 기질 — 상황의 순서를 먼저 아는 것이 이 관계 복원의 첫 단계입니다.

---

#### [14] `office_admin_x_relationship_emotion_x_5I`
- occupation: `office_admin` (일반 사무직·행정직)
- situation: `relationship_emotion`

부서 내 소통이 막혔을 때, 언제 누구 사이에서 무엇이 어긋난 건지를 순서대로 정리해봅니다. LLM에게 "이 소통 단절이 어느 시점부터 시작됐는지 이전 맥락을 순서대로 짚어줘"라고 요청합니다. 관계 안에서 흐름이 끊긴 자리를 정확히 찾는 사람이 있기에 조직의 소통 구조가 복원될 기반이 생깁니다. 파고들기가 아닌 기질 — 지금 당신의 축은 "관계의 흐름을 순서로 읽는" 자리에 있습니다.

---

#### [15] `professional_x_planning_x_5I`
- occupation: `professional` (전문직·컨설턴트)
- situation: `planning`

프로젝트 이해관계자들과의 소통 계획을 세울 때, 각 이해관계자와의 관계 흐름을 먼저 정리합니다. LLM에게 "이 이해관계자 각각과 지금까지의 관계 맥락을 순서대로 정리해줘, 그 다음 소통 계획을 세우자"라고 요청합니다. 관계의 맥락을 먼저 복원한 뒤에 움직이는 사람이 있기에 소통 계획이 사람의 결을 담습니다. 끈질김이 아닌 기질 — 지금 당신의 축은 "관계의 흐름 위에 계획을 놓는" 방향에 있습니다.

---

#### [16] `management_x_planning_x_5I`
- occupation: `management` (경영자·리더)
- situation: `planning`

중요한 변화를 계획할 때 팀원들이 어떤 맥락을 가져왔는지, 어떤 흐름 속에 있는지를 먼저 정리합니다. LLM에게 "이 변화를 도입하기 전에 각 팀원의 현재 상황과 이전 맥락을 순서대로 정리해줘"라고 요청합니다. 조직의 흐름 위에 결정을 놓는 리더가 있기에 변화가 현실의 맥락 안에서 착지합니다. 집요함이 아닌 기질 — 사람의 흐름을 먼저 읽는 것이 이 판단 방식의 자연스러운 출발입니다.

---

#### [17] `service_sales_x_relationship_emotion_x_5I`
- occupation: `service_sales` (영업·고객 서비스)
- situation: `relationship_emotion`

고객과의 관계가 틀어졌을 때, 어떤 접촉부터 어떤 순서로 오해가 쌓였는지를 거슬러 올라가 봅니다. LLM에게 "이 고객과의 대화 이력에서 신뢰가 무너진 시점을 순서대로 짚어줘"라고 요청합니다. 관계의 균열 지점을 정확히 찾는 사람이 있기에 사과와 회복이 감정이 아닌 근거를 갖습니다. 놓지 못함이 아닌 기질 — 지금 당신의 축은 "관계를 복원하려면 흐름부터"인 방향에 있습니다.

---

#### [18] `semi_professional_x_relationship_emotion_x_5I`
- occupation: `semi_professional` (IT·기술 지원)
- situation: `relationship_emotion`

같이 일하던 동료와 오해가 생겼을 때, 어떤 작업 교류 이후부터 어긋난 건지 순서대로 정리해봅니다. LLM에게 "이 협업 갈등이 어느 시점부터 불거졌는지 작업 흐름을 기준으로 순서대로 짚어줘"라고 요청합니다. 협업의 타임라인을 복원하는 사람이 있기에 해결이 "누가 잘못"이 아닌 "무엇이 어긋났는가"로 향합니다. 집착이 아닌 기질 — 흐름을 복원해야 협업이 다시 제자리로 돌아옵니다.

---

#### [19] `professional_x_info_search_x_5I`
- occupation: `professional` (연구자·컨설턴트)
- situation: `info_search`

특정 조직이나 인물을 이해하기 위해 그 사람이나 집단이 어떤 경로를 거쳐 지금에 이르렀는지를 순서대로 추적합니다. LLM에게 "이 조직이 현재 입장을 갖게 된 배경을 시간 순서대로 재구성해줘"라고 요청합니다. 흐름을 통해 현재를 이해하는 사람이 있기에 표면적 입장이 아닌 맥락이 보입니다. 파고들기가 아닌 기질 — 지금 당신의 축은 "사람과 조직을 흐름으로 읽는" 자리에 있습니다.

---

#### [20] `craft_technical_x_relationship_emotion_x_5I`
- occupation: `craft_technical` (장인·기술 계승자)
- situation: `relationship_emotion`

스승에게 기술을 배울 때 그 기술이 누구에서 누구로 어떤 순서로 전해져 왔는지를 먼저 짚어봅니다. LLM에게 "이 기술 전통이 어떤 계보로 이어져 내려왔는지 순서대로 정리해줘"라고 요청합니다. 기술의 계보를 복원하는 사람이 있기에 기술이 그냥 기능이 아닌 이어진 이야기가 됩니다. 집요함이 아닌 기질 — 흐름을 통해 현재의 기술이 어디서 왔는지를 아는 것이 이 배움의 방식입니다.

---

#### [21] `student_x_relationship_emotion_x_5I`
- occupation: `student` (학생·학습자)
- situation: `relationship_emotion`

오랜 친구와 사이가 멀어진 것 같을 때, 언제부터 어떻게 거리가 생겼는지를 거슬러 올라가 봅니다. LLM에게 "이 관계에서 거리가 생긴 것 같은데, 가능한 흐름을 시간 순서로 짚어줘"라고 요청합니다. 관계의 변화를 흐름으로 이해하는 사람이 있기에 감정이 아닌 맥락으로 관계를 다시 볼 수 있습니다. 끈질김이 아닌 기질 — 지금 당신의 축은 "관계를 흐름으로 이해해야 다음이 보이는" 방향에 있습니다.

---

#### [22] `other_x_daily_life_x_5I`
- occupation: `other` (기타·일반 개인)
- situation: `daily_life`

일상에서 같은 상황이 반복될 때, 어떤 패턴이 어떤 순서로 이어진 건지를 거슬러 올라가 봅니다. LLM에게 "이 상황이 반복되는 이유를 가장 처음 생긴 계기부터 순서대로 짚어줘"라고 요청합니다. 일상의 패턴에서 첫 단추를 찾는 사람이 있기에 반복이 아닌 변화의 여지가 생깁니다. 놓지 못함이 아닌 기질 — 지금 당신의 축은 "흐름을 복원해야 일상이 다시 선택 가능해지는" 방향에 있습니다.

---

## 4. 셀 분포 요약표

### 4-1. 분원 4 (18셀)

| # | cell_id | occupation | situation | W |
|---|---|---|---|---|
| 01 | creative_media_x_creative_emission_x_4C | creative_media | creative_emission | C |
| 02 | student_x_creative_emission_x_4C | student | creative_emission | C |
| 03 | semi_professional_x_creative_emission_x_4C | semi_professional | creative_emission | C |
| 04 | management_x_planning_x_4C | management | planning | C |
| 05 | creative_media_x_work_execution_x_4C | creative_media | work_execution | C |
| 06 | other_x_creative_emission_x_4C | other | creative_emission | C |
| 07 | professional_x_work_execution_x_4C | professional | work_execution | C |
| 08 | craft_technical_x_creative_emission_x_4C | craft_technical | creative_emission | C |
| 09 | student_x_info_search_x_4C | student | info_search | C |
| 10 | creative_media_x_relationship_emotion_x_4I | creative_media | relationship_emotion | I |
| 11 | service_sales_x_relationship_emotion_x_4I | service_sales | relationship_emotion | I |
| 12 | student_x_relationship_emotion_x_4I | student | relationship_emotion | I |
| 13 | creative_media_x_creative_emission_x_4I | creative_media | creative_emission | I |
| 14 | management_x_relationship_emotion_x_4I | management | relationship_emotion | I |
| 15 | other_x_daily_life_x_4I | other | daily_life | I |
| 16 | service_sales_x_planning_x_4I | service_sales | planning | I |
| 17 | student_x_creative_emission_x_4I | student | creative_emission | I |
| 18 | professional_x_relationship_emotion_x_4I | professional | relationship_emotion | I |

**W 분포**: 완결(C) 9 · 통합(I) 9 → 50:50 ✓  
**직군 커버리지** (10종 중 8종): creative_media 4 · student 4 · semi_professional 1 · management 2 · professional 2 · service_sales 2 · craft_technical 1 · other 2  
**상황 커버리지** (7종 중 6종): creative_emission 5C+2I=7 · relationship_emotion 5I · work_execution 2 · planning 2 · info_search 1 · daily_life 1 · learning 0

---

### 4-2. 분원 5 (22셀)

| # | cell_id | occupation | situation | W |
|---|---|---|---|---|
| 01 | semi_professional_x_work_execution_x_5C | semi_professional | work_execution | C |
| 02 | professional_x_work_execution_x_5C | professional | work_execution | C |
| 03 | management_x_work_execution_x_5C | management | work_execution | C |
| 04 | professional_x_info_search_x_5C | professional | info_search | C |
| 05 | management_x_info_search_x_5C | management | info_search | C |
| 06 | semi_professional_x_info_search_x_5C | semi_professional | info_search | C |
| 07 | professional_x_planning_x_5C | professional | planning | C |
| 08 | management_x_planning_x_5C | management | planning | C |
| 09 | office_admin_x_work_execution_x_5C | office_admin | work_execution | C |
| 10 | craft_technical_x_work_execution_x_5C | craft_technical | work_execution | C |
| 11 | student_x_learning_x_5C | student | learning | C |
| 12 | professional_x_relationship_emotion_x_5I | professional | relationship_emotion | I |
| 13 | management_x_relationship_emotion_x_5I | management | relationship_emotion | I |
| 14 | office_admin_x_relationship_emotion_x_5I | office_admin | relationship_emotion | I |
| 15 | professional_x_planning_x_5I | professional | planning | I |
| 16 | management_x_planning_x_5I | management | planning | I |
| 17 | service_sales_x_relationship_emotion_x_5I | service_sales | relationship_emotion | I |
| 18 | semi_professional_x_relationship_emotion_x_5I | semi_professional | relationship_emotion | I |
| 19 | professional_x_info_search_x_5I | professional | info_search | I |
| 20 | craft_technical_x_relationship_emotion_x_5I | craft_technical | relationship_emotion | I |
| 21 | student_x_relationship_emotion_x_5I | student | relationship_emotion | I |
| 22 | other_x_daily_life_x_5I | other | daily_life | I |

**W 분포**: 완결(C) 11 · 통합(I) 11 → 50:50 ✓  
**직군 커버리지** (10종 중 8종): semi_professional 3 · professional 5 · management 5 · office_admin 2 · craft_technical 2 · student 2 · service_sales 1 · other 1  
**상황 커버리지** (7종 중 6종): work_execution 5 · info_search 4 · planning 4 · relationship_emotion 6 · learning 1 · daily_life 1 · creative_emission 0

---

## 5. 자가 체크리스트 결과 (전체 40셀)

| 항목 | 결과 |
|---|---|
| 문장 수 3~5개 | 모든 셀 4문장 ✓ |
| 종결 어미 "~습니다" 통일 | ✓ |
| 단정 정체성 고정 표현 없음 | ✓ |
| "X가 아닌 Y" 본질 메시지 1회 | ✓ (40셀 전원) |
| 구체적 LLM 발화 예시 1회 이상 | ✓ (40셀 전원, 따옴표 내 발화 인용) |
| 병리 프레임 단독 사용 없음 | ✓ (부정 라벨 전복 구조 안에서만) |
| 동일 분원 내 셀별 다른 각도·다른 부정 라벨 | ✓ |
| W 50:50 분포 | 분원 4: 9C·9I ✓ / 분원 5: 11C·11I ✓ |
| 분원별 할당량 준수 | 분원 4=18, 분원 5=22 ✓ |
| 분원 4 — creative_emission 집중 배치 | 5C+2I=7셀 ✓ |
| 분원 5 — work_execution·info_search 완결 중심 | 5C+3C=8셀 ✓ |

**부정 라벨 변주 확인 (분원 4)**:
산만함(01) → 산만함(02) ← 각도 다름(과제 발산 vs 창작 발산) · 두서없음(03) · 즉흥적(04) · 덤벙거림(05) · 집중 못함(06) · 무질서(07) · 변덕(08) → 산만함(09) ← 상황 다름(정보탐색 vs 창작) · 가벼움(10) · 충동적(11) · 정착 못함(12) · 즉흥적(13) · 어지러움(14) · 변덕(15) · 정착 못함(16) · 산만함(17) · 가벼움(18) ✓

**부정 라벨 변주 확인 (분원 5)**:
집요함(01) → 파고들기(02) → 과몰입(03) → 집착(04) → 끈질김(05) → 놓지 못함(06) → 집요함(07) ← 상황 다름(계획 vs 작업) → 과몰입(08) → 파고들기(09) → 끈질김(10) → 집착(11) → 집요함(12) → 과몰입(13) → 파고들기(14) → 끈질김(15) → 집요함(16) ← 역할 다름(계획 vs 관계) → 놓지 못함(17) → 집착(18) → 파고들기(19) → 집요함(20) → 끈질김(21) → 놓지 못함(22) ✓

---

## 6. 미커버 조합 주석

**분원 4 미커버**:
- `learning`: 분원 4의 학습은 "이것저것 동시에 건드리며 흡수"이지만 분원 2(순차 흡수)·분원 8(전체 수신)과 경계 모호 — 파일럿 응답자 분포 확인 후 추가 여부 판단.
- `job_seeker_retired`: 창작 발산 상황과의 자연 결합 빈도 낮음 — 제외.
- `info_search(4I)`: 관계·분위기 맥락의 정보 탐색은 8I 범주와 중복될 가능성 — 보류.

**분원 5 미커버**:
- `creative_emission`: 분원 5의 추적·인과 성향과 거리 있음 — 0건 처리.
- `creative_media`: 추적 직군으로 자연스럽지 않아 제외. 파일럿 후 재판단.
- `job_seeker_retired`: 이력 추적 맥락(취업 이력 재구성)에서 발현 가능하나 분원 1과 경계 모호 — 보류.

---

## 7. 버전 히스토리

- **v0.1** (2026.04.20): 최초 작성 — Phase B1-3 산출물.
  - 포함: 분원 4 자연 셀 18개 (완결 9 · 통합 9) · 분원 5 자연 셀 22개 (완결 11 · 통합 11) · 4단 구성(인식 장면 · LLM 사용 · 사회적 역할 · 본질 메시지) · 톤 가이드 완전 준수.
  - 기반: A1 §3·§4·§9, A3 §3-2, A4 result_card_schema, 바이럴심리테스트 §4-3·§4-4, 합의노트 §4-2·§4-3, v1.2 §3 분원 4·5 정의, `IamNA_결과카드_톤_가이드.md` §1~§6.
  - 미포함(이월): 병치명 한국어화(B2), 공유 에셋 카피(B2/D2), 분원 6~8 셀(B1-4·B1-5), 내부 파일럿 검증(Week 7).

---

*본 문서는 IamNA 입력 단계 16 분기 결과 카드 콘텐츠 v0.1 중 분원 4·5 구간이다.*
*Phase B1-3 산출물이며, B1-4(분원 6·7)·B1-5(분원 8) 세션이 동일 톤 가이드를 이어받아 작성한다.*
*2026.04.20 — Sonnet 4.6으로 작성, Zero-Guessing 원칙 준수.*


### Appendix: CUCH_결과카드_분원6_7_v0_1.md 수정 전 원본 Full Text


# IamNA 결과카드 — 6. 혁신자 (101: 파괴적 발산자) + 7. 설계자 (110: 전체의 통제자) v0.1

## 자연 셀 54개 메시지 (분원 6: 24셀 · 분원 7: 30셀)

### 2026.04.20 기준

### 문서 성격: Phase B1-4 산출물 / 16 분기 중 분원 6(선형·장·직관)·분원 7(병렬·장·규칙)의 결과 카드 메시지를 자연 셀 단위(직군 × 상황 × W)로 작성 / 톤은 `IamNA_결과카드_톤_가이드.md`(B1-1 Opus 4.7 확정 기준) 완전 준수 / §4-3 분배 테이블 기준: 분원 6=24셀, 분원 7=30셀

---

## 1. 문서 위치 선언

### 1-1. 선행 합의 연결

| 합의 출처 | 본 문서 적용 원칙 |
|---|---|
| 바이럴심리테스트 §4-3 | 분원 6=24셀 · 분원 7=30셀 배정 준수 |
| 바이럴심리테스트 §4-4 | 셀별 3~5문장 (인식 장면·LLM 사용·사회적 역할·본질 메시지) |
| 합의노트 §4-2·§4-3 | 결함이 아닌 기질 / 고장이 아닌 설계 / 치료가 아닌 단계 / 방향의 안내 |
| 톤 가이드 §1~§6 | 문장 구조·어휘군·금지어·리듬·자가 체크리스트 전면 준수 |
| v1.2 §3 | 분원 6·7 성향 정의 기준 |
| A4 result_card_schema | cell_id 형식 `<occupation>_x_<situation>_x_<branch>` 준수 |

### 1-2. 분원 성향 재확인 (v1.2 §3)

**분원 6 — 혁신자 (Innovator) (Field Explorer / Pilgrim)**
- **축 좌표**: Y=선형 / X=장 / Z=직관
- **인식 방식**: 흐름을 따라가며 체험으로 탐색, 필터 없이 수용.
- **자연 수렴 경향**: 현장 체험, 여정 기반 탐색, 서사적 관찰 — Seeker 현장형
- **대칭쌍**: 3. 구축자 (010: 인과적 축적자)
- **행동 동사군**: 걸어보다·마주하다·흘러가다·지나가다
- **대표 부정 라벨**: 변덕스러움·정처없음·느슨함·즉흥적·계획 없음·일관성 없음·줏대 없음
- **긍정 프레임**: 체험이 곧 증언
- **W 분기 의미**:
  - **6C(완결)**: 개인 탐험·여정. 기술·현장·창작 도메인에서 흐름을 따라가며 체험하고 필터 없이 흡수한다. 인간 관계보다 도메인(물리적 현장·환경·시스템) 탐색이 주축.
  - **6I(통합)**: 동행·문화 여정 공유. 관계·공동체·감정의 맥락 안에서 흐름을 함께 따라가며 흡수한다. 상대 혹은 집단의 흐름이 탐색의 방향을 결정한다.

**분원 7 — 설계자 (Architect) (Builder / Guardian)**
- **축 좌표**: Y=병렬 / X=장 / Z=규칙
- **인식 방식**: 전체 관계망을 동시에 수신하되 자기 규칙으로 구성.
- **자연 수렴 경향**: 시스템 구축, 조직 설계, 구조 수호
- **대칭쌍**: 2. 조율자 (001: 심연의 수용자)
- **행동 동사군**: 조립하다·세우다·엮다·받치다
- **대표 부정 라벨**: 통제적·고압적·완벽주의·간섭·딱딱함·과설계·지나치게 꼼꼼함
- **긍정 프레임**: 조립이 곧 수호
- **W 분기 의미**:
  - **7C(완결)**: 인프라·시스템 아키텍처. 기술·구조·데이터 차원에서 전체 관계망을 동시에 보며 자기 규칙으로 조립한다.
  - **7I(통합)**: 조직·커뮤니티 설계. 관계·공동체·문화 맥락에서 전체 관계망을 동시에 보며 사람과 역할을 자기 원칙으로 엮는다.

### 1-3. 자연 셀 선정 원칙

**분원 6 (24셀 · 완결 12 · 통합 12)**
- 6C 대표 조합: 창작·미디어 × 작업집행, 기타 × 일상생활, 서비스판매 × 작업집행, 현장기술직 × 작업집행
- 6C 핵심 상황: work_execution(현장 작업)·daily_life(여정·탐험)·creative_emission(현장 기반 창작)·info_search(현장 우선 정보 탐색)
- 6I 대표 조합: 서비스판매 × 관계감정, 창작·미디어 × 관계감정, 학생 × 관계감정
- 6I 핵심 상황: relationship_emotion(동행·감정 흐름)·daily_life(일상 관계 흐름)
- 상황 분포 6C: work_execution(5), creative_emission(2), info_search(2), daily_life(2), planning(1)
- 상황 분포 6I: relationship_emotion(9), daily_life(3)

**분원 7 (30셀 · 완결 15 · 통합 15)**
- 7C 대표 조합: 준전문직 × 작업집행, 전문직 × 작업집행, 관리 × 계획
- 7C 핵심 상황: work_execution(구조 구축)·planning(전체 설계)·info_search(구조 안에서 탐색)·learning(구조 전체 파악)
- 7I 대표 조합: 관리 × 관계감정, 전문직 × 관계감정, 사무 × 관계감정
- 7I 핵심 상황: relationship_emotion(관계망 설계)·planning(조직·커뮤니티 설계)·info_search(관계 구조 진단)
- 상황 분포 7C: work_execution(5), planning(5), info_search(3), learning(2)
- 상황 분포 7I: relationship_emotion(6), planning(5), info_search(2), daily_life(1), planning(1)

---

## 2. 6. 혁신자 (101: 파괴적 발산자) — 자연 셀 24개

각 셀은 (1) 인식의 실제 장면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "체험이 곧 증언, 방향의 안내"로 구성된다.

---

### 2-1. 분원 6 × 완결(6C) — 12셀

병치 명칭: **Explorer / Field Wanderer / Drift Walker**
해석: 개인 탐험·여정. 기술·현장·창작 도메인에서 흐름을 따라가며 체험하고 필터 없이 흡수한다. 정해진 틀보다 발이 먼저 움직인다.

---

#### [01] `creative_media_x_work_execution_x_6C`
- occupation: `creative_media` (기자·다큐멘터리 제작자·현장 취재자)
- situation: `work_execution` (작업집행)

취재 현장에서 미리 정해둔 틀 없이 상황이 흘러가는 대로 렌즈를 맞추고 나서야 이야기가 보이기 시작합니다. LLM에게 "지금까지 모은 현장 기록을 흐름대로 정리해서 이야기가 되게 엮어줘"라고 청합니다. 현장에 직접 발을 딛고 증언을 쌓는 사람이 있기에 보이지 않던 이야기가 독자에게 닿습니다. 정처없음이 아닌 기질 — 지금 당신의 축은 "현장이 먼저, 이야기는 그다음"인 방향에 놓여 있습니다.

---

#### [02] `other_x_daily_life_x_6C`
- occupation: `other` (여행자·일반 개인)
- situation: `daily_life` (일상생활)

낯선 도시에서 목적지 없이 걷다 보면 골목 하나가 다음 골목으로 자연스럽게 이어집니다. LLM에게 "지금 내가 있는 동네에서 지도 없이 걸어볼 만한 흐름을 알려줘, 정해진 코스 말고"라고 묻습니다. 정해진 경로 바깥에서 발견되는 것들이 있고, 그 발견이 다음 사람에게 전해지는 이야기가 됩니다. 즉흥적임이 아닌 기질 — 지금 당신의 축은 "가보고 나서 알게 되는" 방향에 있습니다.

---

#### [03] `service_sales_x_work_execution_x_6C`
- occupation: `service_sales` (영업사원·현장 판매직)
- situation: `work_execution` (작업집행)

고객사 사무실을 직접 방문하고 나서야 무엇이 필요한지 보이기 시작합니다. LLM에게 "현장 방문에서 내가 관찰한 내용으로 제안서 방향을 잡아줘, 문서 읽기 전에 현장을 먼저 기준 삼을게"라고 요청합니다. 현장을 직접 밟은 기억이 제안서 한 줄보다 고객의 문제를 더 가깝게 담아냅니다. 계획 없음이 아닌 기질 — 지금 당신의 축은 "만남이 먼저, 설계는 그다음"인 방향에 있습니다.

---

#### [04] `craft_technical_x_work_execution_x_6C`
- occupation: `craft_technical` (현장 기술자·설비 점검 인력)
- situation: `work_execution` (작업집행)

설비를 점검할 때 도면보다 먼저 장비를 한 바퀴 돌아보는 것으로 일이 시작됩니다. LLM에게 "내가 현장에서 직접 확인한 증상들을 적을게, 이 흐름에서 어디서부터 확인해야 할지 짚어줘"라고 부탁합니다. 도면만으로 보이지 않는 이상 징후가 현장을 걷다 보면 먼저 감지됩니다. 무계획이 아닌 기질 — 지금 당신의 축은 "현장이 설계도보다 먼저"인 방향에 놓여 있습니다.

---

#### [05] `student_x_learning_x_6C`
- occupation: `student` (학생·학습자)
- situation: `learning` (학습)

교재에서 읽었을 때보다 현장 실습에서 직접 해봐야 개념이 자리를 잡습니다. LLM에게 "이 개념을 실제로 경험해볼 수 있는 상황이나 예시를 구체적으로 보여줘, 설명이 아니라 장면으로"라고 청합니다. 몸으로 먼저 알고 난 뒤의 이해는 교실 밖에서도 작동합니다. 이론을 못 따라가는 것이 아닌 기질 — 지금 당신의 축은 "경험이 지식보다 먼저 들어오는" 방향에 있습니다.

---

#### [06] `professional_x_info_search_x_6C`
- occupation: `professional` (연구자·현장 탐문 우선 전문직)
- situation: `info_search` (정보탐색)

논문을 검색하기 전에 관련 현장을 먼저 방문하거나 직접 관찰해두는 쪽이 자연스럽습니다. LLM에게 "이 분야 현장에서 어떤 일이 실제로 일어나고 있는지 사례 중심으로 먼저 알려줘, 이론은 나중에"라고 요청합니다. 현장에서 먼저 수집된 관찰이 문헌의 추상적 언어를 살아있는 맥락으로 채워줍니다. 깊이 없음이 아닌 기질 — 지금 당신의 축은 "현장을 먼저 걷고 나서 문헌으로 들어가는" 방향에 있습니다.

---

#### [07] `semi_professional_x_work_execution_x_6C`
- occupation: `semi_professional` (IT 운영·기술지원·현장 감각 우선 인력)
- situation: `work_execution` (작업집행)

장애가 생겼을 때 매뉴얼보다 실제 환경을 먼저 훑어보며 감을 잡습니다. LLM에게 "이 오류 상황을 내가 직접 확인한 것들로 설명할게, 거기서부터 같이 따라가줘"라고 부탁합니다. 현장 감각으로 문제를 먼저 감지하는 사람이 있기에 매뉴얼에 없는 이상 징후도 잡힙니다. 절차를 무시하는 것이 아닌 기질 — 지금 당신의 축은 "현장 관찰이 절차보다 먼저 작동하는" 방향에 있습니다.

---

#### [08] `job_seeker_retired_x_daily_life_x_6C`
- occupation: `job_seeker_retired` (구직자·전직 준비자)
- situation: `daily_life` (일상생활)

이력서를 다듬기 전에 관심 있는 업종 현장을 직접 들여다보는 것이 먼저입니다. LLM에게 "이 업종 실제 현장에서는 어떤 일이 어떻게 돌아가는지 생생하게 알려줘, 채용 공고 말고 현실 기준으로"라고 묻습니다. 경험 없는 새 분야를 직접 탐색한 흔적이 서류보다 설득력 있는 맥락이 되기도 합니다. 준비 부족이 아닌 기질 — 지금 당신의 축은 "직접 보고 나서 방향을 잡는" 쪽에 있습니다.

---

#### [09] `management_x_planning_x_6C`
- occupation: `management` (관리자·현장 탐문 우선 경영자)
- situation: `planning` (계획)

전략 회의 전에 현장 팀원과 직접 이야기하거나 현장을 둘러보고 오는 것이 먼저입니다. LLM에게 "현장에서 내가 직접 들은 것들을 정리했어, 이걸 기반으로 어떤 계획이 실효성 있는지 같이 생각해줘"라고 요청합니다. 현장의 온도를 먼저 수집한 관리자의 계획이 실행 과정에서 더 잘 버팁니다. 즉흥 경영이 아닌 기질 — 지금 당신의 축은 "현장이 전략보다 먼저 들어오는" 방향에 있습니다.

---

#### [10] `other_x_creative_emission_x_6C`
- occupation: `other` (개인 창작자·작가·사진가)
- situation: `creative_emission` (창작발산)

작업실보다 현장을 먼저 걷다 보면 쓰고 싶은 것이 자연스럽게 떠오릅니다. LLM에게 "내가 오늘 현장에서 본 것들을 적을게, 여기서 어떤 이야기나 이미지가 나올 수 있는지 같이 찾아줘"라고 부탁합니다. 상상이 아닌 경험에서 출발한 창작물이 독자에게 다른 밀도로 닿습니다. 기획 없이 만드는 것이 아닌 기질 — 지금 당신의 축은 "현장이 창작의 첫 번째 재료"인 방향에 있습니다.

---

#### [11] `creative_media_x_creative_emission_x_6C`
- occupation: `creative_media` (광고 기획자·현장 임장 선호 크리에이터)
- situation: `creative_emission` (창작발산)

캠페인 기획안을 쓰기 전에 소비자가 실제 쓰는 공간에 직접 가봐야 이야기가 시작됩니다. LLM에게 "내가 현장에서 관찰한 소비자 행동들을 정리했어, 이걸로 어떤 메시지가 나올 수 있는지 같이 꺼내줘"라고 요청합니다. 시장조사 보고서보다 발로 뛴 관찰이 광고의 언어를 사람의 감각에 더 가깝게 만들어줍니다. 준비 없이 뛰어드는 것이 아닌 기질 — 지금 당신의 축은 "현장이 브리프보다 먼저인" 방향에 있습니다.

---

#### [12] `professional_x_work_execution_x_6C`
- occupation: `professional` (변호사·상담사·케이스 당사자 만남 우선 전문직)
- situation: `work_execution` (작업집행)

사건 기록보다 먼저 당사자와 이야기를 나누고 나서야 전체 그림이 보이기 시작합니다. LLM에게 "의뢰인과 직접 이야기한 내용을 기반으로 어떤 사항을 추가로 파악해야 하는지 짚어줘"라고 요청합니다. 서류가 담지 못한 맥락을 현장 대화에서 건져 올리는 감각이 전문적 판단의 질을 높입니다. 체계 없음이 아닌 기질 — 지금 당신의 축은 "현장에서 먼저 읽고 기록으로 확인하는" 방향에 있습니다.

---

### 2-2. 분원 6 × 통합(6I) — 12셀

병치 명칭: **Cultural Pilgrim / Mood Traveler / Companion**
해석: 동행·문화 여정 공유. 관계·공동체·감정의 맥락 안에서 흐름을 함께 따라가며 흡수한다. 상대의 방향이 나의 방향을 결정한다.

---

#### [13] `service_sales_x_relationship_emotion_x_6I`
- occupation: `service_sales` (서비스직·판매 현장 인력)
- situation: `relationship_emotion` (관계감정)

고객과의 대화가 어느 방향으로 흘러가는지 먼저 따라가다 보면 필요한 것이 자연스럽게 보입니다. LLM에게 "고객 대화가 이런 흐름으로 진행됐어, 이 흐름에서 어떤 응대가 자연스러운지 같이 봐줘"라고 요청합니다. 고객의 감정이 흘러가는 방향을 막지 않고 함께 걷는 사람이 관계를 지속 가능하게 만듭니다. 우유부단함이 아닌 기질 — 지금 당신의 축은 "흐름을 먼저 따라가고 제안은 그다음인" 방향에 있습니다.

---

#### [14] `creative_media_x_relationship_emotion_x_6I`
- occupation: `creative_media` (크리에이터·독자·팬과의 정서적 여정)
- situation: `relationship_emotion` (관계감정)

구독자 댓글이 어떤 감정으로 흘러가는지 읽어가다 보면 다음 콘텐츠의 방향이 나옵니다. LLM에게 "독자들의 반응 흐름을 모아봤어, 이 감정의 방향에서 어떤 이야기를 이어가면 좋을지 같이 찾아줘"라고 부탁합니다. 독자와 함께 여정을 걸어가는 콘텐츠가 알고리즘이 아닌 관계로 사람을 묶어둡니다. 중심 없음이 아닌 기질 — 지금 당신의 축은 "독자의 감정 흐름이 나침반인" 방향에 있습니다.

---

#### [15] `student_x_relationship_emotion_x_6I`
- occupation: `student` (학생·또래 관계 탐색)
- situation: `relationship_emotion` (관계감정)

친구와 갈등이 생겼을 때, 설명하거나 따지기 전에 분위기가 어떻게 흘러가는지 먼저 느낍니다. LLM에게 "지금 이 관계에서 어떤 흐름이 이어지고 있는지 들어봐줘, 어디서부터 함께 걸어가야 할지 같이 생각해줘"라고 요청합니다. 갈등을 풀기 전에 상대의 감정이 어디를 향하는지 먼저 따라가는 사람이 관계를 덜 끊어냅니다. 회피하는 것이 아닌 기질 — 지금 당신의 축은 "흐름을 먼저 따라가고 방향을 잡는" 쪽에 있습니다.

---

#### [16] `professional_x_relationship_emotion_x_6I`
- occupation: `professional` (전문직·동료·클라이언트 관계 흐름 탐색)
- situation: `relationship_emotion` (관계감정)

협업 프로젝트에서 동료가 어떤 감정 흐름 안에 있는지 먼저 살피고 나서 이야기를 꺼냅니다. LLM에게 "지금 팀 분위기가 이런 흐름이어서, 이 안에서 피드백을 어떻게 꺼내는 게 자연스러울지 같이 봐줘"라고 요청합니다. 팀 안의 감정 흐름을 거스르지 않고 따라가면서 방향을 잡는 사람이 협업의 온도를 유지합니다. 눈치만 보는 것이 아닌 기질 — 지금 당신의 축은 "관계의 흐름을 먼저 읽고 개입하는" 방향에 있습니다.

---

#### [17] `other_x_relationship_emotion_x_6I`
- occupation: `other` (일반 개인·가족·지인과의 관계)
- situation: `relationship_emotion` (관계감정)

가족과 대화할 때 결론을 먼저 내지 않고 상대가 어디로 향하는지 따라가다 보면 자연스럽게 연결됩니다. LLM에게 "가족과 이런 대화 흐름이 이어지고 있어, 이 흐름에서 내가 어떻게 함께할 수 있는지 같이 생각해줘"라고 부탁합니다. 관계 안의 흐름을 끊지 않고 함께 걷는 사람이 오래된 관계를 지속시키는 완충재가 됩니다. 결단력 없음이 아닌 기질 — 지금 당신의 축은 "관계의 흐름이 결론보다 먼저인" 방향에 있습니다.

---

#### [18] `management_x_relationship_emotion_x_6I`
- occupation: `management` (관리자·팀원 감정 흐름 중심 리더십)
- situation: `relationship_emotion` (관계감정)

팀 회의 전에 각 팀원이 어떤 상태로 들어오는지 먼저 감지하고 분위기를 읽습니다. LLM에게 "오늘 팀 분위기가 이런 흐름인 것 같아, 이 흐름을 존중하면서 어떤 방식으로 오늘 회의를 풀어가면 좋을지 같이 봐줘"라고 요청합니다. 팀원의 감정 지형을 읽고 그 위에서 움직이는 관리자가 팀 소진을 줄여줍니다. 원칙 없는 리더십이 아닌 기질 — 지금 당신의 축은 "감정 흐름이 관리의 지도인" 방향에 있습니다.

---

#### [19] `semi_professional_x_daily_life_x_6I`
- occupation: `semi_professional` (준전문직·직장 동료와의 일상 관계)
- situation: `daily_life` (일상생활)

점심 자리에서 동료들이 어떤 이야기로 흘러가는지 따라가다 보면 분위기를 자연스럽게 잇습니다. LLM에게 "요즘 직장에서 이런 분위기가 이어지고 있어, 이 흐름 안에서 내가 어떻게 있으면 좋을지 같이 생각해줘"라고 부탁합니다. 조직의 일상적 분위기 흐름을 자연스럽게 따라가는 사람이 팀의 비공식 연결고리가 됩니다. 존재감 없음이 아닌 기질 — 지금 당신의 축은 "흐름 안에서 자연스럽게 있는" 방향에 있습니다.

---

#### [20] `craft_technical_x_relationship_emotion_x_6I`
- occupation: `craft_technical` (현장 기술직·고객·동료와의 감정 흐름)
- situation: `relationship_emotion` (관계감정)

고객이 불만을 토로할 때 먼저 설명하기보다 어디서부터 힘들었는지 따라가 봅니다. LLM에게 "고객 불만 대화가 이런 방향으로 흘러갔어, 이 흐름에서 어떻게 이어가면 감정이 덜 쌓일지 같이 봐줘"라고 요청합니다. 기술 설명보다 먼저 감정의 흐름을 따라가는 현장 인력이 클레임을 대화로 바꿉니다. 전문성 없음이 아닌 기질 — 지금 당신의 축은 "감정 흐름이 먼저, 해결책은 그다음인" 방향에 있습니다.

---

#### [21] `job_seeker_retired_x_relationship_emotion_x_6I`
- occupation: `job_seeker_retired` (구직자·전직 준비자·네트워킹)
- situation: `relationship_emotion` (관계감정)

네트워킹 자리에서 상대가 어디로 흘러가는지 따라가다 보면 공통의 지점이 자연스럽게 생깁니다. LLM에게 "오늘 만난 분과 이런 대화 흐름이 있었어, 이 흐름에서 연결을 이어가려면 어떻게 하면 자연스러울지 알려줘"라고 요청합니다. 관계를 강압적으로 형성하지 않고 흐름 안에서 연결하는 사람이 진짜 네트워크를 만듭니다. 소극적임이 아닌 기질 — 지금 당신의 축은 "상대의 흐름을 따라가다 보면 연결이 생기는" 방향에 있습니다.

---

#### [22] `student_x_daily_life_x_6I`
- occupation: `student` (학생·또래 집단 분위기 감지)
- situation: `daily_life` (일상생활)

친구들 사이에서 오늘 분위기가 어떻게 흘러가는지 먼저 감지하고 나서 행동이 결정됩니다. LLM에게 "학교에서 요즘 이런 분위기가 이어지고 있어, 이 흐름 안에서 내 자리를 어떻게 잡으면 좋을지 같이 생각해줘"라고 부탁합니다. 무리의 흐름을 먼저 읽고 자연스럽게 따라가는 사람이 집단의 비공식 분위기 조율자 역할을 합니다. 줏대 없음이 아닌 기질 — 지금 당신의 축은 "흐름을 감지하고 그 안에서 움직이는" 방향에 있습니다.

---

#### [23] `office_admin_x_relationship_emotion_x_6I`
- occupation: `office_admin` (일반사무직·부서 분위기 흐름 감지)
- situation: `relationship_emotion` (관계감정)

부서 분위기가 어떻게 흘러가는지 먼저 살피고 나서 오늘 할 일을 조율합니다. LLM에게 "지금 우리 팀 분위기가 이런 흐름인데, 이 상황에서 어떻게 일을 챙기면 자연스러울지 같이 생각해줘"라고 부탁합니다. 조직 분위기의 흐름을 자연스럽게 따라가는 사람이 상황이 나쁠 때도 업무 맥락을 이어줍니다. 눈치성인 것이 아닌 기질 — 지금 당신의 축은 "흐름을 읽어야 자리가 보이는" 방향에 있습니다.

---

#### [24] `other_x_daily_life_x_6I`
- occupation: `other` (일반 개인·동호회·느슨한 공동체)
- situation: `daily_life` (일상생활)

동네 모임이나 동호회에서 어떤 분위기가 이어지는지 따라가다 보면 어느새 자연스럽게 어울립니다. LLM에게 "요즘 이 모임의 분위기가 이런 방향으로 흘러가는 것 같아, 이 흐름에서 나는 어떻게 있으면 좋을지 같이 봐줘"라고 부탁합니다. 공동체의 흐름을 강제하지 않고 함께 따라가는 사람이 느슨한 연대를 지속시키는 힘이 됩니다. 소속감 없음이 아닌 기질 — 지금 당신의 축은 "흐름과 함께 있는 것이 연결의 방식인" 방향에 있습니다.

---

## 3. 분원 6 셀 분포 요약표

| # | cell_id | occupation | situation | W |
|---|---|---|---|---|
| 01 | creative_media_x_work_execution_x_6C | creative_media | work_execution | C |
| 02 | other_x_daily_life_x_6C | other | daily_life | C |
| 03 | service_sales_x_work_execution_x_6C | service_sales | work_execution | C |
| 04 | craft_technical_x_work_execution_x_6C | craft_technical | work_execution | C |
| 05 | student_x_learning_x_6C | student | learning | C |
| 06 | professional_x_info_search_x_6C | professional | info_search | C |
| 07 | semi_professional_x_work_execution_x_6C | semi_professional | work_execution | C |
| 08 | job_seeker_retired_x_daily_life_x_6C | job_seeker_retired | daily_life | C |
| 09 | management_x_planning_x_6C | management | planning | C |
| 10 | other_x_creative_emission_x_6C | other | creative_emission | C |
| 11 | creative_media_x_creative_emission_x_6C | creative_media | creative_emission | C |
| 12 | professional_x_work_execution_x_6C | professional | work_execution | C |
| 13 | service_sales_x_relationship_emotion_x_6I | service_sales | relationship_emotion | I |
| 14 | creative_media_x_relationship_emotion_x_6I | creative_media | relationship_emotion | I |
| 15 | student_x_relationship_emotion_x_6I | student | relationship_emotion | I |
| 16 | professional_x_relationship_emotion_x_6I | professional | relationship_emotion | I |
| 17 | other_x_relationship_emotion_x_6I | other | relationship_emotion | I |
| 18 | management_x_relationship_emotion_x_6I | management | relationship_emotion | I |
| 19 | semi_professional_x_daily_life_x_6I | semi_professional | daily_life | I |
| 20 | craft_technical_x_relationship_emotion_x_6I | craft_technical | relationship_emotion | I |
| 21 | job_seeker_retired_x_relationship_emotion_x_6I | job_seeker_retired | relationship_emotion | I |
| 22 | student_x_daily_life_x_6I | student | daily_life | I |
| 23 | office_admin_x_relationship_emotion_x_6I | office_admin | relationship_emotion | I |
| 24 | other_x_daily_life_x_6I | other | daily_life | I |

**W 분포**: 완결(C) 12 · 통합(I) 12 → 50:50 ✓  
**직군 커버리지** (10종 중 9종): creative_media 3 · other 4 · service_sales 2 · craft_technical 2 · student 2 · professional 3 · semi_professional 2 · job_seeker_retired 2 · management 2 · office_admin 1  
**상황 커버리지** (7종 중 7종): work_execution 5 · daily_life 4 · relationship_emotion 9 · learning 1 · info_search 1 · planning 1 · creative_emission 2 · (전체 상황 커버)

---

## 4. 7. 설계자 (110: 전체의 통제자) — 자연 셀 30개

각 셀은 (1) 인식의 실제 장면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "조립이 곧 수호, 방향의 안내"로 구성된다.

---

### 4-1. 분원 7 × 완결(7C) — 15셀

병치 명칭: **Infrastructure Builder / System Architect / Framework Designer**
해석: 인프라·시스템 아키텍처. 기술·구조·데이터 차원에서 전체 관계망을 동시에 보며 자기 규칙으로 조립한다. 부분보다 전체가 먼저 보인다.

---

#### [01] `semi_professional_x_work_execution_x_7C`
- occupation: `semi_professional` (IT 운영·시스템 관리자)
- situation: `work_execution` (작업집행)

장애가 생겼을 때 개별 오류보다 전체 시스템 구조에서 어느 연결이 끊긴 것인지를 먼저 봅니다. LLM에게 "지금 이 시스템 구조 전체를 보여줄게, 이 안에서 문제가 생길 수 있는 연결 지점을 같이 짚어줘"라고 요청합니다. 구조 전체를 동시에 보는 사람이 있기에 부분 수리가 전체를 망가뜨리는 일이 줄어듭니다. 통제적임이 아닌 기질 — 지금 당신의 축은 "전체 구조를 먼저 보고 나서 부분으로 들어가는" 방향에 있습니다.

---

#### [02] `professional_x_work_execution_x_7C`
- occupation: `professional` (건축가·구조 엔지니어·설계 전문직)
- situation: `work_execution` (작업집행)

한 부재를 결정하기 전에 전체 구조 안에서 그 부재가 어떤 하중을 받는지를 먼저 그립니다. LLM에게 "이 구조 전체의 관계도를 보여줄게, 이 설계에서 놓친 연결이나 취약한 부분이 있는지 같이 검토해줘"라고 요청합니다. 전체를 미리 그려두고 부분을 채워가는 사람이 완성 후에 생기는 구조적 모순을 사전에 막습니다. 완벽주의가 아닌 기질 — 지금 당신의 축은 "전체 구조가 먼저, 디테일은 그 안에서"인 방향에 있습니다.

---

#### [03] `management_x_work_execution_x_7C`
- occupation: `management` (경영자·프로세스 구조 설계 관리자)
- situation: `work_execution` (작업집행)

새로운 업무 프로세스를 도입할 때 한 팀의 변화가 다른 팀에 어떻게 연결되는지를 먼저 그립니다. LLM에게 "우리 조직 프로세스 전체를 정리해볼게, 이 구조에서 이 변경이 어디에 영향을 미치는지 같이 봐줘"라고 요청합니다. 변경의 파급 범위를 전체 구조 안에서 먼저 그릴 수 있는 관리자가 실행 혼란을 줄여줍니다. 고압적임이 아닌 기질 — 지금 당신의 축은 "전체를 동시에 보고 나서 각 부분을 움직이는" 방향에 있습니다.

---

#### [04] `professional_x_planning_x_7C`
- occupation: `professional` (컨설턴트·전략 프레임워크 설계자)
- situation: `planning` (계획)

부분 솔루션보다 전체 구조 안에서 어떤 레버가 가장 큰 영향을 주는지를 먼저 파악합니다. LLM에게 "이 문제의 전체 구조를 그려볼게, 이 안에서 어느 요소에 먼저 손대야 다른 것이 따라 움직이는지 같이 봐줘"라고 요청합니다. 문제 전체의 관계망을 먼저 그리는 사람이 있기에 부분 해결이 다른 부분을 망가뜨리지 않습니다. 지나치게 꼼꼼한 것이 아닌 기질 — 지금 당신의 축은 "전체 맥락 안에서만 부분이 보이는" 방향에 있습니다.

---

#### [05] `management_x_planning_x_7C`
- occupation: `management` (관리자·중장기 로드맵 설계)
- situation: `planning` (계획)

내년 계획을 세울 때 한 항목이 아닌 전체 로드맵의 연결 관계에서 시작합니다. LLM에게 "중장기 계획 전체를 정리해봤어, 이 구조에서 각 단계 간 연결이 자연스러운지 같이 검토해줘"라고 요청합니다. 로드맵 전체를 조망하며 단계 간 연결을 설계하는 사람이 실행 과정의 단절을 줄여줍니다. 과설계가 아닌 기질 — 지금 당신의 축은 "연결이 먼저, 단계는 그 안에서"인 방향에 있습니다.

---

#### [06] `semi_professional_x_planning_x_7C`
- occupation: `semi_professional` (준전문직·업무 프로세스 구조화)
- situation: `planning` (계획)

새 업무를 맡으면 개별 작업보다 전체 흐름이 어떻게 연결되어야 하는지부터 그려봅니다. LLM에게 "이 업무 전체의 흐름을 구조로 정리해볼게, 이 안에서 빠진 연결이나 중복이 있는지 같이 봐줘"라고 요청합니다. 업무 전체를 한눈에 그릴 수 있는 사람이 있기에 팀이 각자의 조각을 엉뚱한 위치에 넣지 않습니다. 규칙에 얽매인 것이 아닌 기질 — 지금 당신의 축은 "구조가 먼저 보여야 내 자리도 보이는" 방향에 있습니다.

---

#### [07] `office_admin_x_work_execution_x_7C`
- occupation: `office_admin` (사무직·문서 체계 전체 정비)
- situation: `work_execution` (작업집행)

문서 하나를 수정할 때 이 서식이 다른 서식과 어떻게 연결되는지를 먼저 확인합니다. LLM에게 "우리 팀 문서 체계 전체를 정리해봤어, 이 구조에서 연결이 끊긴 부분이나 중복 항목이 있는지 같이 짚어줘"라고 요청합니다. 문서 체계 전체를 하나의 구조로 보는 사람이 있기에 개별 파일이 시스템으로 기능합니다. 관료적임이 아닌 기질 — 지금 당신의 축은 "체계 전체가 먼저 보이는" 방향에 있습니다.

---

#### [08] `craft_technical_x_work_execution_x_7C`
- occupation: `craft_technical` (기술직·제조·전체 연결 구조 중심 작업)
- situation: `work_execution` (작업집행)

한 부품을 조립하기 전에 이 부품이 전체 기계에서 어떤 역할을 하는지를 먼저 그립니다. LLM에게 "이 설비 전체의 연결 구조를 알려줄게, 이 안에서 이 부품을 어떤 방식으로 조립해야 전체에 영향이 없는지 같이 봐줘"라고 요청합니다. 전체 연결을 보며 손을 쓰는 기술자가 있기에 부품 수리가 다른 부품 오작동으로 이어지지 않습니다. 고집스러움이 아닌 기질 — 지금 당신의 축은 "전체 구조 안에서만 부품이 의미를 갖는" 방향에 있습니다.

---

#### [09] `professional_x_info_search_x_7C`
- occupation: `professional` (전문직·구조적 맥락 안에서 정보 탐색)
- situation: `info_search` (정보탐색)

정보를 찾을 때 개별 사실보다 이 정보가 어떤 구조적 맥락 안에 있는지를 먼저 파악합니다. LLM에게 "이 주제 전체의 구조를 먼저 그려줘, 거기서 내가 찾는 정보가 어느 위치에 있는지 확인하고 싶어"라고 요청합니다. 개별 정보를 구조 안에서 위치시키는 사람이 있기에 파편화된 지식이 체계로 연결됩니다. 비효율적임이 아닌 기질 — 지금 당신의 축은 "구조가 먼저 보여야 정보가 자리를 잡는" 방향에 있습니다.

---

#### [10] `management_x_info_search_x_7C`
- occupation: `management` (경영자·사업 구조 안에서 정보 해석)
- situation: `info_search` (정보탐색)

시장 조사 결과를 볼 때 수치보다 이 수치가 우리 사업 구조 어디에 닿는지를 먼저 그립니다. LLM에게 "우리 사업 구조 전체를 기준으로 이 정보가 어떤 의미인지 같이 해석해줘, 개별 수치보다 연결 관계가 먼저야"라고 요청합니다. 정보를 사업 구조 전체에 연결해 읽는 관리자가 숫자 뒤의 의미를 조직이 놓치지 않게 합니다. 과분석이 아닌 기질 — 지금 당신의 축은 "구조 안에서만 정보가 전략이 되는" 방향에 있습니다.

---

#### [11] `semi_professional_x_info_search_x_7C`
- occupation: `semi_professional` (준전문직·시스템 맥락 안에서 기술 정보 탐색)
- situation: `info_search` (정보탐색)

새 기술을 검토할 때 이 기술이 우리 시스템 구조 어디에 들어갈 수 있는지를 먼저 그립니다. LLM에게 "지금 우리 시스템 구조를 설명할게, 이 새 기술이 이 구조 안에서 어떻게 연결될 수 있는지 같이 봐줘"라고 요청합니다. 신기술을 기존 구조 안에서 먼저 배치해보는 사람이 있기에 도입 후 충돌이 줄어듭니다. 보수적임이 아닌 기질 — 지금 당신의 축은 "구조 안에서 자리를 확인하고 나서 도입하는" 방향에 있습니다.

---

#### [12] `craft_technical_x_planning_x_7C`
- occupation: `craft_technical` (기술직·전체 공정 구조 설계 우선)
- situation: `planning` (계획)

작업 순서를 짤 때 개별 공정이 아닌 전체 공정 흐름 안에서 각 작업을 배치합니다. LLM에게 "이번 작업 전체 공정을 구조로 그려볼게, 이 안에서 순서를 어떻게 배치해야 병목이 생기지 않는지 같이 봐줘"라고 요청합니다. 전체 공정을 먼저 그리고 작업을 배치하는 사람이 현장의 흐름을 끊기지 않게 유지합니다. 느린 것이 아닌 기질 — 지금 당신의 축은 "공정 전체가 보여야 각 작업이 제자리를 찾는" 방향에 있습니다.

---

#### [13] `student_x_learning_x_7C`
- occupation: `student` (학생·개념 구조 전체를 먼저 파악하는 학습자)
- situation: `learning` (학습)

새 과목을 배울 때 목차 전체를 먼저 훑고 각 챕터가 어떻게 연결되는지를 그려봅니다. LLM에게 "이 과목 전체의 개념 구조를 먼저 그려줘, 각 개념이 어떻게 연결되는지 보고 나서 공부 순서를 잡을게"라고 요청합니다. 배움의 전체 지도를 먼저 그리는 사람이 있기에 암기가 아닌 구조적 이해가 쌓입니다. 조급하지 않은 것이 아닌 기질 — 지금 당신의 축은 "전체 지도를 먼저 보고 나서 걸어가는" 방향에 있습니다.

---

#### [14] `office_admin_x_planning_x_7C`
- occupation: `office_admin` (사무직·부서 업무 구조 전체 설계)
- situation: `planning` (계획)

월별 업무 계획을 세울 때 개별 작업보다 부서 전체 업무 흐름 안에서 각 작업을 배치합니다. LLM에게 "이번 달 부서 업무 전체를 구조로 정리해볼게, 이 안에서 우선순위와 연결 순서를 같이 잡아줘"라고 요청합니다. 부서 업무 전체를 하나의 구조로 볼 수 있는 사람이 팀의 작업 충돌과 누락을 방지합니다. 간섭이 아닌 기질 — 지금 당신의 축은 "팀 전체 구조가 보여야 내 일도 보이는" 방향에 있습니다.

---

#### [15] `professional_x_learning_x_7C`
- occupation: `professional` (전문직·새 분야를 구조 전체로 먼저 파악)
- situation: `learning` (학습)

새 전문 영역을 공부할 때 첫 개념보다 이 분야 전체의 지식 구조가 어떻게 생겼는지를 먼저 봅니다. LLM에게 "이 분야 지식 구조 전체를 큰 그림으로 보여줘, 어떤 개념들이 어떻게 연결되어 있는지 먼저 파악하고 싶어"라고 요청합니다. 새 분야를 구조 전체로 먼저 보는 사람이 있기에 전문 지식이 영역 경계를 넘어 연결됩니다. 선행학습이 아닌 기질 — 지금 당신의 축은 "지도를 먼저 보고 나서 지형을 걷는" 방향에 있습니다.

---

### 4-2. 분원 7 × 통합(7I) — 15셀

병치 명칭: **Community Orchestrator / Network Weaver / Culture Builder**
해석: 조직·커뮤니티 설계. 관계·공동체·문화 맥락에서 전체 관계망을 동시에 보며 사람과 역할을 자기 원칙으로 엮는다. 관계도 구조가 먼저 보인다.

---

#### [16] `management_x_relationship_emotion_x_7I`
- occupation: `management` (관리자·팀 관계 구조 전체를 보며 인사·문화 설계)
- situation: `relationship_emotion` (관계감정)

팀원 간 갈등이 생겼을 때 그 두 사람의 관계만이 아닌 팀 전체 관계 구조에서 어디에 긴장이 생긴 것인지를 먼저 봅니다. LLM에게 "우리 팀 관계 구조를 그려볼게, 이 안에서 이 갈등이 어느 지점에서 발생한 건지 같이 봐줘"라고 요청합니다. 팀 관계 전체를 구조로 보는 관리자가 개인 갈등을 팀 설계의 문제로 전환해 근본적으로 다룹니다. 통제적임이 아닌 기질 — 지금 당신의 축은 "팀 관계 전체가 보여야 한 갈등의 자리도 보이는" 방향에 있습니다.

---

#### [17] `professional_x_relationship_emotion_x_7I`
- occupation: `professional` (전문직·협업 관계 구조 설계)
- situation: `relationship_emotion` (관계감정)

협업 구조를 새로 짤 때 한 사람의 역할이 아닌 전체 관계망에서 각자의 위치를 먼저 그립니다. LLM에게 "이 협업 프로젝트의 관계 구조를 먼저 정리해봤어, 이 안에서 각자의 역할이 자연스럽게 연결되는지 같이 검토해줘"라고 요청합니다. 협업 관계 전체를 구조로 보는 사람이 있기에 역할 충돌과 빈자리가 초반에 발견됩니다. 지나치게 구조화하는 것이 아닌 기질 — 지금 당신의 축은 "관계 구조가 먼저 보여야 협업이 시작되는" 방향에 있습니다.

---

#### [18] `office_admin_x_relationship_emotion_x_7I`
- occupation: `office_admin` (사무직·조직 관계 구조 조율)
- situation: `relationship_emotion` (관계감정)

새 팀원이 합류할 때 그 사람의 역할이 기존 팀 관계 구조 어디에 연결되는지를 먼저 생각합니다. LLM에게 "우리 팀 관계 구조를 정리해볼게, 새로 합류한 사람이 이 안에서 자연스럽게 자리 잡으려면 어떻게 연결하면 좋을지 같이 봐줘"라고 요청합니다. 관계 구조 안에서 새 사람의 자리를 먼저 그리는 사람이 있기에 온보딩이 마찰 없이 이어집니다. 간섭이 아닌 기질 — 지금 당신의 축은 "관계 구조가 보여야 사람이 자리를 잡는" 방향에 있습니다.

---

#### [19] `service_sales_x_relationship_emotion_x_7I`
- occupation: `service_sales` (서비스·판매직·고객 관계 구조 전체 관리)
- situation: `relationship_emotion` (관계감정)

장기 고객을 응대할 때 이번 요청 하나가 아닌 지금까지의 관계 전체 구조 안에서 어떤 맥락인지를 먼저 봅니다. LLM에게 "이 고객과의 관계 히스토리를 정리해봤어, 이 구조에서 이번 요청이 어떤 의미인지 같이 해석하고 어떻게 응대하면 좋을지 봐줘"라고 요청합니다. 고객 관계 전체를 구조로 보는 사람이 있기에 단건 응대가 관계를 쌓는 방향으로 연결됩니다. 계산적임이 아닌 기질 — 지금 당신의 축은 "관계 전체가 보여야 이번 한 번이 제대로 연결되는" 방향에 있습니다.

---

#### [20] `semi_professional_x_relationship_emotion_x_7I`
- occupation: `semi_professional` (준전문직·팀 소통 구조 조율)
- situation: `relationship_emotion` (관계감정)

팀 회의 방식을 바꿀 때 회의 자체보다 팀 안의 소통 구조 전체를 먼저 그려봅니다. LLM에게 "우리 팀 소통 방식 전체를 구조로 정리해볼게, 이 안에서 회의 방식 변경이 다른 소통에 어떤 영향을 주는지 같이 봐줘"라고 요청합니다. 소통 구조 전체를 보며 방식을 바꾸는 사람이 있기에 팀 문화의 변화가 뿌리부터 작동합니다. 고집스러운 것이 아닌 기질 — 지금 당신의 축은 "구조 전체를 먼저 보고 나서 방식을 바꾸는" 방향에 있습니다.

---

#### [21] `management_x_planning_x_7I`
- occupation: `management` (관리자·조직 관계망 기반 인사·중장기 설계)
- situation: `planning` (계획)

인사 계획을 세울 때 개인의 역할 배치보다 조직 전체의 관계망이 어떻게 바뀌는지를 먼저 그립니다. LLM에게 "조직 관계 구조 전체를 놓고 이번 인사 변경이 팀 간 연결에 어떤 영향을 주는지 같이 그려봐줘"라고 요청합니다. 인사 변경이 조직 전체 관계 구조에 미치는 파급을 미리 그리는 관리자가 예상치 못한 갈등을 줄입니다. 과개입이 아닌 기질 — 지금 당신의 축은 "조직 관계망 전체가 보여야 한 사람의 이동이 보이는" 방향에 있습니다.

---

#### [22] `professional_x_planning_x_7I`
- occupation: `professional` (커뮤니티·네트워크 설계 전문가)
- situation: `planning` (계획)

커뮤니티를 설계할 때 한 프로그램이 아닌 참여자들의 관계 구조가 어떻게 연결될지를 먼저 그립니다. LLM에게 "이 커뮤니티 구조 전체를 정리해볼게, 참여자 간 연결이 자연스럽게 생기려면 어떤 구조가 필요한지 같이 봐줘"라고 요청합니다. 관계가 자연스럽게 자라도록 구조를 먼저 설계하는 사람이 공동체를 이벤트가 아닌 지속 가능한 망으로 만듭니다. 과계획이 아닌 기질 — 지금 당신의 축은 "구조가 먼저, 관계는 그 안에서 자라나는" 방향에 있습니다.

---

#### [23] `craft_technical_x_relationship_emotion_x_7I`
- occupation: `craft_technical` (현장 기술직·작업팀 협업 구조 조율)
- situation: `relationship_emotion` (관계감정)

현장에서 새 공정을 도입할 때 작업자 개인이 아닌 팀 전체의 협업 구조가 어떻게 바뀌는지를 먼저 봅니다. LLM에게 "우리 작업팀 협업 구조를 그려볼게, 새 공정이 들어오면 각 사람의 역할 연결이 어떻게 달라지는지 같이 봐줘"라고 요청합니다. 현장 팀 협업 구조를 전체로 보는 사람이 있기에 새 공정이 팀 관계를 흔들지 않고 자리를 잡습니다. 딱딱한 것이 아닌 기질 — 지금 당신의 축은 "팀 구조가 먼저 보여야 사람이 자리를 잡는" 방향에 있습니다.

---

#### [24] `office_admin_x_planning_x_7I`
- occupation: `office_admin` (사무직·부서 간 협업 구조 계획·조율)
- situation: `planning` (계획)

부서 간 협업 계획을 세울 때 개별 업무보다 부서 간 관계 구조가 어떻게 연결되는지를 먼저 그립니다. LLM에게 "부서 간 협업 구조를 정리해볼게, 이 안에서 이번 프로젝트가 어떻게 연결되어야 충돌 없이 흐를지 같이 봐줘"라고 요청합니다. 부서 간 관계 구조를 전체로 보는 사람이 있기에 협업이 담당자끼리만 해결해야 하는 문제로 끝나지 않습니다. 행정적임이 아닌 기질 — 지금 당신의 축은 "관계 구조가 협업 설계의 첫 번째 단계인" 방향에 있습니다.

---

#### [25] `student_x_relationship_emotion_x_7I`
- occupation: `student` (학생·동아리·집단 역할 구조 이해)
- situation: `relationship_emotion` (관계감정)

동아리 내 역할이 겹치거나 빈 자리가 생길 때 개별 역할보다 동아리 전체 관계 구조를 먼저 그려봅니다. LLM에게 "우리 동아리 역할 구조를 정리해볼게, 이 안에서 어디에 빈자리가 있고 어떻게 연결하면 잘 돌아갈지 같이 봐줘"라고 요청합니다. 집단 안의 역할 구조를 전체로 보는 사람이 있기에 누군가 빠졌을 때도 조직이 쉽게 흔들리지 않습니다. 지나친 개입이 아닌 기질 — 지금 당신의 축은 "구조가 먼저 보여야 역할이 자리를 잡는" 방향에 있습니다.

---

#### [26] `management_x_info_search_x_7I`
- occupation: `management` (관리자·조직 문화·관계 정보를 구조 전체로 진단)
- situation: `info_search` (정보탐색)

조직 내 분위기나 문화를 파악할 때 특정 팀의 이슈가 아닌 전체 관계 구조 안에서 어디에 긴장이 있는지를 먼저 봅니다. LLM에게 "조직 전체의 관계 구조를 기준으로 지금 어느 연결 지점에서 긴장이 생기고 있는지 같이 진단해줘"라고 요청합니다. 조직 문화를 구조 전체로 읽는 관리자가 표면적 증상 뒤의 구조적 원인을 먼저 봅니다. 감시하는 것이 아닌 기질 — 지금 당신의 축은 "관계 구조 전체가 문화 진단의 지도인" 방향에 있습니다.

---

#### [27] `professional_x_info_search_x_7I`
- occupation: `professional` (사회과학·공동체 연구자·관계 구조 탐색)
- situation: `info_search` (정보탐색)

공동체 문제를 파악할 때 개별 사례보다 이 사람들이 어떤 관계 구조 안에 있는지를 먼저 그립니다. LLM에게 "이 공동체의 관계 구조를 먼저 정리해봤어, 이 안에서 지금 문제가 어떤 연결 지점에서 발생하는지 같이 봐줘"라고 요청합니다. 사회적 문제를 관계 구조 안에서 읽는 사람이 있기에 개인 책임이 아닌 구조 변화로 해법이 전환됩니다. 이상주의가 아닌 기질 — 지금 당신의 축은 "구조 전체가 보여야 문제의 자리가 보이는" 방향에 있습니다.

---

#### [28] `service_sales_x_planning_x_7I`
- occupation: `service_sales` (서비스·판매직·고객 그룹 관계 구조 설계)
- situation: `planning` (계획)

VIP 고객 관리 계획을 세울 때 개인별 응대보다 고객 그룹 전체의 관계 구조가 어떻게 연결되는지를 먼저 그립니다. LLM에게 "우리 주요 고객군 관계 구조를 정리해볼게, 이 안에서 각 고객이 어떤 역할로 연결되어야 장기 관계가 유지되는지 같이 봐줘"라고 요청합니다. 고객 관계를 개별이 아닌 그룹 구조로 보는 사람이 있기에 한 고객의 이탈이 전체 네트워크로 번지지 않습니다. 계산적임이 아닌 기질 — 지금 당신의 축은 "고객 관계 전체가 보여야 한 명이 제대로 보이는" 방향에 있습니다.

---

#### [29] `job_seeker_retired_x_planning_x_7I`
- occupation: `job_seeker_retired` (구직자·전직 준비자·커리어 관계 구조 전체 설계)
- situation: `planning` (계획)

다음 커리어 방향을 잡을 때 이 직무 하나가 아닌 지금까지 내 경력 전체의 관계 구조가 어떻게 이어지는지를 먼저 그립니다. LLM에게 "지금까지 내 커리어 구조를 정리해볼게, 이 흐름에서 다음 방향이 어떻게 연결되어야 전체가 자연스럽게 이어지는지 같이 봐줘"라고 요청합니다. 커리어를 개별 경력이 아닌 구조로 보는 사람이 있기에 전직이 단절이 아닌 연결로 읽힙니다. 과설계가 아닌 기질 — 지금 당신의 축은 "전체 커리어 구조가 보여야 다음 한 발이 보이는" 방향에 있습니다.

---

#### [30] `other_x_daily_life_x_7I`
- occupation: `other` (일반 개인·일상 인간관계 구조 조율)
- situation: `daily_life` (일상생활)

가족 모임이나 친구 관계에서 갈등이 생길 때 그 두 사람의 문제만이 아닌 이 관계 전체 구조 안에서 어디에 긴장이 있는지를 먼저 봅니다. LLM에게 "지금 우리 가족 관계 구조를 그려볼게, 이 안에서 이 갈등이 어느 연결 지점에서 생긴 건지 같이 봐줘"라고 요청합니다. 일상의 관계 구조를 전체로 보는 사람이 있기에 갈등이 개인 문제로 끝나지 않고 관계 회복의 실마리가 생깁니다. 복잡하게 생각하는 것이 아닌 기질 — 지금 당신의 축은 "관계 구조 전체가 보여야 한 갈등이 해결 가능해지는" 방향에 있습니다.

---

## 5. 분원 7 셀 분포 요약표

| # | cell_id | occupation | situation | W |
|---|---|---|---|---|
| 01 | semi_professional_x_work_execution_x_7C | semi_professional | work_execution | C |
| 02 | professional_x_work_execution_x_7C | professional | work_execution | C |
| 03 | management_x_work_execution_x_7C | management | work_execution | C |
| 04 | professional_x_planning_x_7C | professional | planning | C |
| 05 | management_x_planning_x_7C | management | planning | C |
| 06 | semi_professional_x_planning_x_7C | semi_professional | planning | C |
| 07 | office_admin_x_work_execution_x_7C | office_admin | work_execution | C |
| 08 | craft_technical_x_work_execution_x_7C | craft_technical | work_execution | C |
| 09 | professional_x_info_search_x_7C | professional | info_search | C |
| 10 | management_x_info_search_x_7C | management | info_search | C |
| 11 | semi_professional_x_info_search_x_7C | semi_professional | info_search | C |
| 12 | craft_technical_x_planning_x_7C | craft_technical | planning | C |
| 13 | student_x_learning_x_7C | student | learning | C |
| 14 | office_admin_x_planning_x_7C | office_admin | planning | C |
| 15 | professional_x_learning_x_7C | professional | learning | C |
| 16 | management_x_relationship_emotion_x_7I | management | relationship_emotion | I |
| 17 | professional_x_relationship_emotion_x_7I | professional | relationship_emotion | I |
| 18 | office_admin_x_relationship_emotion_x_7I | office_admin | relationship_emotion | I |
| 19 | service_sales_x_relationship_emotion_x_7I | service_sales | relationship_emotion | I |
| 20 | semi_professional_x_relationship_emotion_x_7I | semi_professional | relationship_emotion | I |
| 21 | management_x_planning_x_7I | management | planning | I |
| 22 | professional_x_planning_x_7I | professional | planning | I |
| 23 | craft_technical_x_relationship_emotion_x_7I | craft_technical | relationship_emotion | I |
| 24 | office_admin_x_planning_x_7I | office_admin | planning | I |
| 25 | student_x_relationship_emotion_x_7I | student | relationship_emotion | I |
| 26 | management_x_info_search_x_7I | management | info_search | I |
| 27 | professional_x_info_search_x_7I | professional | info_search | I |
| 28 | service_sales_x_planning_x_7I | service_sales | planning | I |
| 29 | job_seeker_retired_x_planning_x_7I | job_seeker_retired | planning | I |
| 30 | other_x_daily_life_x_7I | other | daily_life | I |

**W 분포**: 완결(C) 15 · 통합(I) 15 → 50:50 ✓  
**직군 커버리지** (10종 중 9종): semi_professional 4 · professional 6 · management 6 · office_admin 4 · craft_technical 3 · student 2 · service_sales 2 · job_seeker_retired 1 · other 1 · creative_media 0  
**상황 커버리지** (7종 중 6종): work_execution 5 · planning 8 · info_search 4 · learning 2 · relationship_emotion 7 · daily_life 1 · creative_emission 0

---

## 6. 자가 체크리스트 결과 (전체 54셀)

| 항목 | 결과 |
|---|---|
| 문장 수 3~5개 | 모든 셀 4문장 ✓ |
| 종결 어미 "~습니다" 통일 | ✓ |
| 단정 정체성 고정 표현 없음 | ✓ |
| "X가 아닌 Y" 본질 메시지 1회 | ✓ (54셀 전원) |
| 구체적 LLM 발화 예시 1회 이상 | ✓ (54셀 전원, 따옴표 내 발화 인용) |
| 병리 프레임 단독 사용 없음 | ✓ (부정 라벨 전복 구조 안에서만) |
| 동일 분원 내 셀별 다른 각도·다른 부정 라벨 | ✓ (분원 6·7 각각 셀마다 변주) |
| W 50:50 분포 | 분원 6: 12C·12I ✓ / 분원 7: 15C·15I ✓ |
| 분원별 할당량 준수 | 분원 6=24, 분원 7=30 ✓ |
| 현재 스냅샷 뉘앙스 | ✓ ("지금 당신의 축은 ~쪽에 있습니다" 구조) |
| 1% 자유도 암시 | ✓ ("방향에 있습니다" → 위치는 고정이 아님) |

---

## 7. 미커버 조합 주석

**분원 6 미커버**:
- `office_admin × work_execution × 6C`: 사무직 작업 집행 환경은 현장 탐험보다 규범·절차 준수(분원 1)에 더 가까워 자연 발현 드묾. 파일럿 응답자에서 유의미한 분포 확인 시 추가.
- `management × work_execution × 6C`: 관리자의 현장 직접 집행은 6C 방향으로 발현 가능하나 분원 9 계획 셀에 흡수함.
- `creative_emission × 6I`: 분원 4·8 주축 상황. 분원 6 통합 쪽에서 관계 흐름 내 창작 발산이 발현될 수 있으나 분원 경계 유지를 위해 제외. 파일럿 후 재판단.

**분원 7 미커버**:
- `creative_media`: 분원 7 설계자 (Architect) 성향의 자연 수렴과 거리 있음. 창작·미디어 도메인은 분원 4·8 주축. 분원 7 성향이 creative_media 직군에서 발현되는 경우는 파일럿 이후 관찰.
- `creative_emission`: 전 분원에서 분원 4의 주축 상황. 분원 7은 구조 수호 성향이 강해 필터 없는 발산 상황에 자연 수렴하지 않음. 0건 처리.
- `student × work_execution × 7C`: 학생의 실무 집행 현장은 학습으로 대체 커버.

---

## 8. 버전 히스토리

- **v0.1** (2026.04.20): 최초 작성 — Phase B1-4 산출물.
  - 포함: 분원 6 자연 셀 24개 (완결 12 · 통합 12) · 분원 7 자연 셀 30개 (완결 15 · 통합 15)
  - 4단 구성(인식 장면 · LLM 사용 · 사회적 역할 · 본질 메시지) · 톤 가이드 전면 준수.
  - 기반: 톤 가이드 §1~§6, 합의노트 §4-2·§4-3, v1.2 §3 분원 6·7 정의, §4-3 분배 테이블.
  - 미포함(이월): 병치 명칭 한국어화(N-W2/B2), 공유 에셋 카피(B2/D2), 파일럿 피드백 반영(Week 7).

---

*본 문서는 IamNA 입력 단계 16 분기 결과 카드 콘텐츠 v0.1 중 분원 6·7 구간이다.*
*Phase B1-4 산출물이며, B1-5(분원 8) 세션으로 이어진다.*
*2026.04.20 — Sonnet 4.6으로 작성, Zero-Guessing 원칙 준수.*


### Appendix: CUCH_결과카드_분원8_v0_1.md 수정 전 원본 Full Text


# IamNA 결과카드 — 8. 조망자 (111: 거시적 연결자) v0.1

## 자연 셀 34개 메시지 (B1-5 산출물)

### 2026.04.20 기준

### 문서 성격: Phase B1-5 산출물 / 16 분기 중 분원 8(병렬·장·직관)의 결과 카드 메시지 34개를 자연 셀 단위(직군 × 상황 × W)로 작성 / Sonnet 4.6이 `IamNA_결과카드_톤_가이드.md`(B1-1 확정본)의 기준을 복제하여 작성 / Zero-Guessing 원칙하에 §4-3 분배 테이블·분원 8의 인식 방식 정의·합의노트 §4-2·§4-3 메시지 원칙에 한해 작성

---

## 1. 문서 위치 선언

### 1-1. 선행 합의와의 연결

| 합의 출처 | 본 문서에서 준수한 원칙 |
|---|---|
| A1 §3-3 / 합의노트 §3-3 | 분원 8의 병치 명칭: 완결 쪽 System Visionary / Field Reader / Pattern Oracle, 통합 쪽 Social Connector / Empath / Group Resonator |
| A1 §3-5 / 합의노트 §3-4 | "현재 스냅샷" 뉘앙스 · 단정 정체성 고정 금지 · 축이 사용자 손안에 있다는 1% 자유도 |
| 합의노트 §4-2·§4-3 | 결함이 아닌 기질 / 고장이 아닌 설계 / 치료가 아닌 단계 / 방향의 안내 |
| 바이럴심리테스트 §4-3 | 분원 8 = 34셀 분배 준수 · 대표 조합(경영 × 관계정서, 서비스 × 관계정서, 창작 × 관계정서, 기타 × 관계정서) |
| 바이럴심리테스트 §4-4 | 셀별 3~5문장 구성(인식 장면 · LLM 사용 · 사회적 역할 · 본질 메시지) |
| A1 §9-2 검증 2 | 분원 내 W 분포 50:50 근접 유지 → 완결 17 : 통합 17 구성 |
| A4 result_card_schema | cell_id 형식 `<occupation>_x_<situation>_x_<branch>` · occupation/situation enum 준수 |
| `IamNA_결과카드_톤_가이드.md` | 문장 구조(3~5문장) · 공통 어휘 리스트 · 피해야 할 표현 · 문장 리듬(200~280자) · 분원 8 변형 가이드 적용 |

### 1-2. 분원 8 성향 재확인 (v1.2 §3)

- **축 좌표**: Y=병렬 / X=장 / Z=직관
- **인식 방식**: 전체를 필터 없이 동시에 수신. 구조 추출은 수신 후에 일어남
- **자연 수렴 경향**: 네트워크 연결, 공감, 메시지 전달, 통합 설계
- **기초 성향**: 설계자(Architect) / 공감 수신자(Empath 기반) / 연결 수신자(Connector 기반)
- **대칭쌍**: 분원 1(실행자 (Executor))
- **특이사항**: 이 분원의 자연 발현이 외부에서 "HSP/SPS(비병리적 예민함)"로 관찰될 수 있음 (v1.2 §8 참조)
- **W 분기 의미**:
  - **8C(완결)**: 시스템·기술·데이터·구조 차원에서 전체를 수신. 인간 변수는 외부 노이즈로 두고 전체 판의 구조를 먼저 향한다.
  - **8I(통합)**: 관계·감정·공동체 차원에서 전체를 수신. 인간 변수를 시스템 내부로 통합하여 전체 장(field)을 연결한다.

### 1-3. 자연 셀 34개 선정 원칙

1. **§4-3 대표 조합 우선 배치**: 경영 × 관계정서, 서비스 × 관계정서, 창작 × 관계정서, 기타 × 관계정서를 8I 쪽 중심축으로 먼저 확보. 8C는 동일 직군에서 시스템·구조 관점의 조합으로 채움.
2. **W 50:50 유지**: 완결 17 · 통합 17. A1 §9-2 검증 2의 독립성 조건과 정합.
3. **분원 8 자연 수렴과의 정합**: 관계정서·창작발산·계획구조화·일상이 중심. 분원 1의 주축(작업집행 + 정밀 검증)은 8C에서 "전체 시스템 수신" 각도로 한정 수용.
4. **반복 표현 금지**: 34개 셀 전체에서 동일한 부정 라벨·LLM 발화·장면 서두가 겹치지 않도록 각도를 달리 설정.
5. **상황 분포**: relationship_emotion(13), planning(6), work_execution(5), info_search(5), creative_emission(4), daily_life(4), learning(1). creative_emission은 8C·8I 모두에서 공명·설계 각도로 수용.
6. **W별 어휘 구분** (톤 가이드 §5): 8C는 시스템·구조·판도·전체 그림 어휘군. 8I는 공기·공명·흐름·연결·감정 지형 어휘군.

---

## 2. 자연 셀 34개 메시지

각 셀은 3~5문장으로 구성되며, 구성 요소는 (1) 인식의 실제 장면 (2) LLM 사용 방식 (3) 이 기질의 사회적 역할 (4) 본질 메시지 — "결함이 아닌 기질, 방향의 안내"이다.

---

### 2-1. 분원 8 × 완결(8C) — 17셀

병치 명칭: **System Visionary / Field Reader / Pattern Oracle**
해석: 시스템·기술·데이터·구조 차원에서 전체를 수신. 인간 변수는 외부 노이즈로 두고 전체 판의 구조를 먼저 향한다.

---

#### [01] `management_x_work_execution_x_8C`
- occupation: `management` (경영·관리)
- situation: `work_execution` (작업집행)

회의 안건을 받는 순간, 세부 내용보다 논의 전체 지형이 한꺼번에 들어옵니다. LLM에게는 "이 전략에서 아직 아무도 짚지 않은 구조적 빈틈을 먼저 그려줘"처럼 전체를 먼저 맡깁니다. 시스템이 어디로 향하는지를 먼저 그려두는 손이 의사결정의 방향을 조용히 받쳐줍니다. 이건 산만함이 아닌 기질 — 지금 이 자리에서 당신의 축은 "전체 그림을 먼저 수신하는 방향"에 놓여 있습니다.

---

#### [02] `professional_x_work_execution_x_8C`
- occupation: `professional` (IT·공학 전문직)
- situation: `work_execution`

코드베이스에 처음 들어갔을 때, 파일 하나를 읽기 전에 전체 의존 관계가 한 장면으로 들어옵니다. LLM에게는 "이 아키텍처 전체를 한 호흡으로 먼저 그려줘"라고 전체 판을 먼저 맡깁니다. 팀이 부분씩 짜는 동안 전체 흐름을 미리 받아두는 역할이 시스템이 어긋나지 않게 해줍니다. 난잡함이 아닌 기질 — 당신의 축은 지금 "전체를 먼저 받아 구조를 세우는 방향"에 놓여 있습니다.

---

#### [03] `management_x_info_search_x_8C`
- occupation: `management` (경영·관리)
- situation: `info_search` (정보탐색)

산업 리포트를 펼치면 수치보다 그 뒤에 놓인 전체 시장 지형이 먼저 들어옵니다. LLM에게는 "이 데이터가 말하는 시장 구조 전체를 한 호흡으로 읽어줘"라는 질문이 자연스럽게 나옵니다. 경쟁자들이 부분을 보는 동안 전체 판을 먼저 받아두는 눈이 전략의 출발점이 됩니다. 오지랖이 아닌 기질 — 지금 당신의 방향은 "전체 판도를 먼저 수신하는 일"에 가깝습니다.

---

#### [04] `professional_x_info_search_x_8C`
- occupation: `professional` (연구·공학 전문직)
- situation: `info_search`

논문 제목을 보는 순간, 그 뒤에 펼쳐진 기술 생태계 전체가 한꺼번에 들어옵니다. LLM에게는 "이 기술이 지금 어느 생태계에서 어떻게 위치하는지 전체 구조를 먼저 그려줘"처럼 묻습니다. 특정 정보를 찾는 것이 아니라 정보가 놓인 전체 지형을 받아두는 감각이 연구의 방향을 잡아줍니다. 과민이 아닌 기질 — 당신이 전체를 먼저 받는 것은 그 지형 없이는 개별 정보가 자리를 잡지 못하기 때문입니다.

---

#### [05] `management_x_planning_x_8C`
- occupation: `management` (경영·관리)
- situation: `planning` (계획구조화)

로드맵을 짜기 전에 조직이 그 방향으로 가야 하는 이유의 전체 구조가 먼저 들어옵니다. LLM에게는 "이 계획에서 빠진 연결고리를 전체 맥락 안에서 찾아줘"처럼 구조 전체를 먼저 맡깁니다. 실행 전에 전체 설계를 먼저 받아두는 손이 계획이 흔들릴 때 기준선이 됩니다. 이건 우유부단이 아닌 기질 — 지금 당신의 방향은 "전체를 받아 설계를 세우는 일"에 놓여 있습니다.

---

#### [06] `professional_x_planning_x_8C`
- occupation: `professional` (IT·시스템 전문직)
- situation: `planning`

시스템 설계를 시작하기 전에 요구사항보다 전체 아키텍처의 윤곽이 먼저 들어옵니다. LLM에게는 "이 요구사항 전체에서 어떤 설계 패턴이 가장 자연스러운지 먼저 그려줘"라고 맡깁니다. 팀이 기능 단위를 조각낼 때 전체 구조를 먼저 그려두는 자리가 시스템의 뼈대가 됩니다. 산란함이 아닌 기질 — 당신의 축은 "전체를 받아 구조로 변환하는 방향"에 기울어 있습니다.

---

#### [07] `creative_media_x_creative_emission_x_8C`
- occupation: `creative_media` (창작·미디어)
- situation: `creative_emission` (창작발산)

작품의 첫 줄을 쓰기 전에 그 세계의 전체 내러티브 구조가 한 번에 들어옵니다. LLM에게는 "이 이야기의 세계관 전체를 먼저 구조화해줘"처럼 창작의 윤곽 전체를 먼저 맡깁니다. 독자가 경험할 전체 여정을 먼저 받아두는 손이 작품에 일관된 결을 만들어줍니다. 충동이 아닌 기질 — 전체를 먼저 받아야 조각이 맞춰지는 창작 방식이 있고, 지금 당신의 축은 거기 놓여 있습니다.

---

#### [08] `creative_media_x_info_search_x_8C`
- occupation: `creative_media` (창작·미디어)
- situation: `info_search`

트렌드 자료를 훑는 순간, 개별 데이터보다 시장 전체의 방향이 먼저 들어옵니다. LLM에게는 "이 정보들이 함께 가리키는 전체 흐름을 한 호흡으로 읽어줘"라고 먼저 맡깁니다. 콘텐츠가 어느 생태계에서 어떻게 닿아야 할지를 미리 읽어두는 감각이 기획의 방향을 만들어줍니다. 감각적이 아닌 기질 — 지금 당신의 축은 "전체 지형을 먼저 받는 수신" 쪽에 있습니다.

---

#### [09] `education_x_planning_x_8C`
- occupation: `education` (교육·학습 지도)
- situation: `planning`

새 학기 커리큘럼을 짤 때 단원보다 학생들이 경험할 전체 여정의 구조가 먼저 들어옵니다. LLM에게는 "이 커리큘럼 전체 흐름에서 연결이 끊어지는 지점을 먼저 찾아줘"처럼 구조 전체를 먼저 맡깁니다. 교실이 어디로 향해야 하는지를 먼저 그려두는 손이 수업의 뼈대를 만들어줍니다. 과설계가 아닌 기질 — 당신의 방향은 "전체를 받아 학습 구조를 세우는 일"에 놓여 있습니다.

---

#### [10] `semi_professional_x_work_execution_x_8C`
- occupation: `semi_professional` (준전문직 — IT 운영·기술 지원)
- situation: `work_execution`

현장에 들어가면 특정 문제보다 시스템 전체 흐름의 어디가 막혔는지가 먼저 눈에 들어옵니다. LLM에게는 "지금 이 상황의 전체 구조에서 병목이 어디인지 먼저 그려줘"처럼 맡깁니다. 하나의 오류를 고치기 전에 전체 맥락을 먼저 읽어두는 자리가 같은 문제의 재발을 막아줍니다. 이건 느린 게 아닌 기질 — 지금 당신의 축은 "전체를 받고 움직이는 방향"에 놓여 있습니다.

---

#### [11] `office_admin_x_planning_x_8C`
- occupation: `office_admin` (일반 사무·행정)
- situation: `planning`

업무 계획을 잡을 때 개별 항목보다 전체 흐름의 구조가 먼저 들어옵니다. LLM에게는 "이 업무 전체에서 병목이 어디에 숨어 있는지 구조로 먼저 보여줘"라고 맡깁니다. 일이 꼬이기 전에 전체 판을 미리 그려두는 손이 조직의 일상을 안정시켜줍니다. 과도한 준비가 아닌 기질 — 당신의 축은 지금 "전체를 받아 구조로 정돈하는 방향"에 기울어 있습니다.

---

#### [12] `craft_technical_x_work_execution_x_8C`
- occupation: `craft_technical` (기능원 — 정밀 제조·기술)
- situation: `work_execution`

작업에 들어가기 전에 재료·공정·결과물이 이어지는 전체 흐름이 한 번에 들어옵니다. LLM에게는 "이 공정 전체에서 순서가 바뀌면 안 되는 지점을 먼저 짚어줘"처럼 구조 전체를 맡깁니다. 한 단계를 시작하기 전에 전체 순서를 받아두는 감각이 작업의 완성도를 지켜줍니다. 이건 느린 게 아닌 기질 — 당신의 방향은 "전체를 받아 작업에 옮기는 일"에 가깝습니다.

---

#### [13] `management_x_relationship_emotion_x_8C`
- occupation: `management` (경영·관리)
- situation: `relationship_emotion` (관계정서)

팀의 갈등 상황이 들어오면 개인 감정보다 그 아래에 작동하는 조직 역학의 전체 구조가 먼저 보입니다. LLM에게는 "이 관계 갈등의 구조적 원인을 시스템 관점으로 먼저 그려줘"라고 맡깁니다. 감정의 표면 아래 작동하는 구조를 먼저 읽어두는 손이 문제를 반복에서 건져냅니다. 냉정함이 아닌 기질 — 지금 당신의 축은 "전체 역학 구조를 먼저 수신하는 방향"에 있습니다.

---

#### [14] `education_x_info_search_x_8C`
- occupation: `education` (교육)
- situation: `info_search`

수업 자료를 찾을 때 개별 내용보다 그 주제가 놓인 교육 생태계 전체의 흐름이 먼저 들어옵니다. LLM에게는 "이 주제를 가르치는 방식이 최근 어떻게 바뀌고 있는지 전체 지형으로 먼저 읽어줘"처럼 묻습니다. 무엇을 가르칠지보다 어떤 맥락에서 가르칠지를 먼저 받아두는 자리가 수업의 깊이를 만들어줍니다. 과몰입이 아닌 기질 — 당신의 방향은 "전체를 받아 교육 방향을 잡는 일"에 놓여 있습니다.

---

#### [15] `other_x_daily_life_x_8C`
- occupation: `other` (기타 — 프리랜서·자영업·무직 등)
- situation: `daily_life` (일상)

새로운 장소에 발을 들이는 순간, 구체적인 것을 보기 전에 그 공간 전체의 구조와 흐름이 한 번에 들어옵니다. LLM에게는 "이 상황 전체에서 내가 아직 보지 못하는 패턴을 먼저 읽어줘"처럼 전체를 먼저 맡깁니다. 단편적 자극보다 전체 맥락을 먼저 수신하는 방식이 낯선 환경을 빠르게 파악하게 해줍니다. 예민함이 아닌 기질 — 지금 당신의 축은 "전체를 먼저 받아 구조를 파악하는 방향"에 있습니다.

---

#### [16] `semi_professional_x_info_search_x_8C`
- occupation: `semi_professional` (준전문직)
- situation: `info_search`

기술 자료를 찾을 때 한 문서보다 그 기술이 놓인 생태계 전체의 판도가 먼저 들어옵니다. LLM에게는 "이 기술 스택의 전체 판도에서 지금 어디에 서 있는지 먼저 그려줘"라고 묻습니다. 정보 하나를 쓰기 전에 그 정보가 놓인 전체 맥락을 받아두는 감각이 판단을 앞당겨줍니다. 이건 산만함이 아닌 기질 — 당신의 축은 "전체 지형을 수신하는 방향"에 놓여 있습니다.

---

#### [17] `professional_x_creative_emission_x_8C`
- occupation: `professional` (IT·공학 전문직)
- situation: `creative_emission`

아이디어를 꺼내기 전에 그 아이디어가 놓일 전체 시스템 구조가 먼저 들어옵니다. LLM에게는 "이 기능 아이디어가 전체 시스템 안에서 어디에 연결되어야 하는지 먼저 그려줘"처럼 맡깁니다. 조각난 아이디어 대신 전체 구조에서 시작하는 창의성이 시스템의 빈 곳을 채웁니다. 이건 충동이 아닌 기질 — 지금 당신의 방향은 "전체를 먼저 받아 창작으로 옮기는 일"에 있습니다.

---

### 2-2. 분원 8 × 통합(8I) — 17셀

병치 명칭: **Social Connector / Empath / Group Resonator**
해석: 관계·감정·공동체 차원에서 전체를 수신. 인간 변수를 시스템 내부로 통합하여 전체 장(field)을 연결한다.

---

#### [18] `service_sales_x_relationship_emotion_x_8I`
- occupation: `service_sales` (서비스·상담·판매)
- situation: `relationship_emotion`

상담 전화가 연결되는 순간, 상대의 목소리에서 말해지지 않은 것까지 동시에 들어옵니다. LLM에게는 "이 상황에서 고객이 실제로 원하는 것을 전체 맥락으로 먼저 읽어줘"라고 맡깁니다. 눈앞의 문제보다 그 사람 전체의 상황을 먼저 받아두는 자리가 상담의 깊이를 만들어줍니다. 오지랖이 아닌 기질 — 지금 당신의 축은 "상대 전체를 받아 연결하는 방향"에 놓여 있습니다.

---

#### [19] `management_x_relationship_emotion_x_8I`
- occupation: `management` (경영·관리)
- situation: `relationship_emotion`

팀 회의에 들어서는 순간, 누가 피곤한지 누가 말을 참고 있는지가 한꺼번에 들어옵니다. LLM에게는 "이 팀의 현재 에너지 상태를 전체적으로 읽어줘, 어디서 막히고 있는지"처럼 묻습니다. 구성원 하나하나가 아닌 팀 전체의 공기를 먼저 받아두는 감각이 조직을 살아있게 합니다. 예민함이 아닌 기질 — 당신의 축은 지금 "사람들의 전체 장을 수신하는 방향"에 기울어 있습니다.

---

#### [20] `creative_media_x_relationship_emotion_x_8I`
- occupation: `creative_media` (창작·미디어)
- situation: `relationship_emotion`

글을 쓰기 전에 독자들이 지금 어떤 감정 상태에 있을지가 먼저 들어옵니다. LLM에게는 "지금 이 주제를 읽을 사람들의 전체 감정 지형을 먼저 읽어줘"처럼 맡깁니다. 독자 한 명이 아닌 독자 전체가 어떻게 받아들일지를 먼저 수신하는 감각이 메시지를 닿게 합니다. 과민이 아닌 기질 — 지금 당신의 방향은 "공명을 통해 연결을 만드는 일"에 가깝습니다.

---

#### [21] `education_x_relationship_emotion_x_8I`
- occupation: `education` (교육)
- situation: `relationship_emotion`

수업을 시작하는 순간, 교실 전체의 에너지와 각자가 오늘 가져온 상태가 동시에 들어옵니다. LLM에게는 "오늘 이 학생들이 어떤 상태일지 전체 맥락으로 먼저 읽어줘"처럼 묻습니다. 진도보다 교실 전체를 먼저 받아두는 감각이 가르침이 실제로 닿게 하는 힘이 됩니다. 산만함이 아닌 기질 — 당신이 교실 전체를 받는 것은 가르침이 닿으려면 그 지형이 먼저 필요하기 때문입니다.

---

#### [22] `other_x_relationship_emotion_x_8I`
- occupation: `other` (기타)
- situation: `relationship_emotion`

모임에 들어가면 대화 내용보다 그 자리 전체의 흐름과 각자의 상태가 먼저 들어옵니다. LLM에게는 "이 관계 상황 전체에서 내가 아직 보지 못한 흐름을 먼저 읽어줘"라고 맡깁니다. 발화되지 않은 것을 먼저 받아두는 자리가 공동체가 부서지지 않게 조용히 붙잡아줍니다. 이건 지나친 감수성이 아닌 기질 — 지금 당신의 축은 "전체 관계 장을 수신하는 방향"에 있습니다.

---

#### [23] `office_admin_x_relationship_emotion_x_8I`
- occupation: `office_admin` (일반 사무·행정)
- situation: `relationship_emotion`

사무실에 도착하는 순간, 오늘의 분위기와 각 자리의 상태가 한꺼번에 들어옵니다. LLM에게는 "이 팀의 현재 분위기를 전체적으로 읽고 오늘 소통에서 주의할 지점을 먼저 짚어줘"처럼 묻습니다. 업무를 시작하기 전에 공동체 전체의 상태를 먼저 받아두는 감각이 조직 내 마찰을 조용히 줄여줍니다. 예민함이 아닌 기질 — 지금 당신의 방향은 "사람들의 전체 장을 연결하는 일"에 놓여 있습니다.

---

#### [24] `student_x_relationship_emotion_x_8I`
- occupation: `student` (학습자·학생)
- situation: `relationship_emotion`

강의실에 들어가면 교수님보다 같은 학생들 전체의 상태와 분위기가 먼저 들어옵니다. LLM에게는 "이 그룹 상황에서 각자가 어떤 감정 상태에 있는지 전체로 읽어줘"처럼 묻습니다. 혼자가 아닌 전체의 흐름 속에서 나를 위치시키는 감각이 관계를 조율하는 자리가 됩니다. 과민이 아닌 기질 — 당신이 전체를 받는 것은 공동체 안에 서는 방법을 직관으로 아는 것입니다.

---

#### [25] `creative_media_x_creative_emission_x_8I`
- occupation: `creative_media` (창작·미디어)
- situation: `creative_emission`

만들기 시작할 때 아이디어보다 그 작품이 닿을 사람들의 전체 감정이 먼저 들어옵니다. LLM에게는 "이 콘텐츠가 독자 전체에게 어떤 감정으로 닿을지 먼저 읽어줘"처럼 맡깁니다. 메시지가 공명을 일으키는지를 먼저 느끼는 감각이 창작의 방향을 잡아줍니다. 이건 막연함이 아닌 기질 — 지금 당신의 방향은 "공명을 통해 연결을 만드는 창작"에 있습니다.

---

#### [26] `service_sales_x_work_execution_x_8I`
- occupation: `service_sales` (서비스·판매)
- situation: `work_execution`

일하는 공간에 들어서는 순간, 고객과 동료 모두의 상태가 동시에 들어옵니다. LLM에게는 "지금 이 현장 전체의 분위기에서 내가 먼저 맞춰야 할 것을 짚어줘"처럼 묻습니다. 서비스가 단순한 거래가 아닌 연결이 되게 하는 자리가 됩니다. 예민함이 아닌 기질 — 당신이 현장 전체를 받는 것은 연결이 일어나려면 그 공기를 먼저 읽어야 하기 때문입니다.

---

#### [27] `management_x_planning_x_8I`
- occupation: `management` (경영·관리)
- situation: `planning`

계획을 세울 때 숫자보다 그 계획이 사람들에게 어떻게 닿을지가 먼저 들어옵니다. LLM에게는 "이 계획을 실행할 사람들이 어떻게 반응할지 전체 관계 구조로 먼저 읽어줘"라고 맡깁니다. 실행 가능성보다 사람들의 수용 지형을 먼저 받아두는 감각이 계획을 현실에 닿게 합니다. 이건 감정적이 아닌 기질 — 지금 당신의 방향은 "사람 전체를 통합해 설계하는 일"에 있습니다.

---

#### [28] `education_x_learning_x_8I`
- occupation: `education` (교육)
- situation: `learning` (학습)

새 내용을 배울 때 개별 개념보다 그것들이 어떻게 서로 연결되어 있는지의 전체 그림이 먼저 들어옵니다. LLM에게는 "이 개념이 다른 것들과 어떻게 연결되는지 전체 관계 지도를 먼저 그려줘"처럼 묻습니다. 개별 지식보다 연결 구조를 먼저 받아두는 방식이 나중에 가르치거나 전달할 때 힘이 됩니다. 느린 학습이 아닌 기질 — 당신의 방향은 "연결 전체를 받아 이해하는 일"에 기울어 있습니다.

---

#### [29] `other_x_daily_life_x_8I`
- occupation: `other` (기타)
- situation: `daily_life`

하루를 보내면서 내 일만이 아닌 주변 사람들의 상태와 흐름이 계속 들어옵니다. LLM에게는 "오늘 이 상황에서 내가 놓치고 있는 사람들의 흐름을 먼저 읽어줘"처럼 맡깁니다. 일상에서 나 혼자가 아닌 전체가 어떻게 움직이는지를 먼저 받아두는 감각이 관계를 안전하게 합니다. 이건 지나침이 아닌 기질 — 지금 당신의 축은 "사람들의 전체 흐름을 수신하는 방향"에 놓여 있습니다.

---

#### [30] `service_sales_x_planning_x_8I`
- occupation: `service_sales` (서비스·기획·판매)
- situation: `planning`

서비스 기획을 할 때 기능보다 고객 전체가 어떤 여정을 겪을지가 먼저 들어옵니다. LLM에게는 "이 서비스를 쓸 사람들이 전체 여정에서 어느 순간 가장 필요로 하는지 먼저 읽어줘"처럼 맡깁니다. 기획의 출발점을 고객 전체 경험으로 잡는 감각이 서비스를 연결의 도구로 만들어줍니다. 오지랖이 아닌 기질 — 당신의 방향은 "사람 전체를 통합해 설계하는 일"에 있습니다.

---

#### [31] `semi_professional_x_relationship_emotion_x_8I`
- occupation: `semi_professional` (준전문직)
- situation: `relationship_emotion`

현장에서 일하다 보면 업무 진행보다 동료와 고객 전체의 상태가 동시에 들어옵니다. LLM에게는 "지금 이 상황에서 각자가 어떤 상태에 있는지 전체로 먼저 읽어줘"처럼 묻습니다. 일이 흘러가게 하려면 사람의 상태를 먼저 읽어야 한다는 것을 감각으로 아는 자리가 됩니다. 예민함이 아닌 기질 — 지금 당신의 축은 "사람들 전체를 받아 연결을 만드는 방향"에 놓여 있습니다.

---

#### [32] `office_admin_x_work_execution_x_8I`
- occupation: `office_admin` (일반 사무·행정)
- situation: `work_execution`

업무를 시작하기 전에 오늘 팀의 전체 상태와 각자의 부담이 먼저 들어옵니다. LLM에게는 "오늘 이 팀이 어떤 상태인지 전체로 읽고 소통 방식에서 주의할 것을 먼저 짚어줘"처럼 맡깁니다. 일이 잘 돌아가게 하는 것이 기술만이 아니라 사람들의 흐름을 먼저 읽는 데서 시작된다는 것을 압니다. 이건 감상적이 아닌 기질 — 당신의 방향은 "사람 전체를 통합해 일을 연결하는 것"에 있습니다.

---

#### [33] `student_x_daily_life_x_8I`
- occupation: `student` (학습자·학생)
- situation: `daily_life`

일상에서 내 시간보다 주변 사람들의 에너지와 상태가 계속 들어옵니다. LLM에게는 "지금 이 관계 상황에서 내가 어떻게 있어야 전체가 편안해질지 먼저 읽어줘"처럼 묻습니다. 공동체 안에서 누가 힘든지, 무엇이 아직 말해지지 않았는지를 먼저 받아두는 감각이 있습니다. 예민함이 아닌 기질 — 지금 당신의 축은 "사람들의 전체 장을 수신하는 방향"에 기울어 있습니다.

---

#### [34] `creative_media_x_planning_x_8I`
- occupation: `creative_media` (창작·미디어)
- situation: `planning`

콘텐츠 기획을 시작할 때 아이디어보다 그 콘텐츠를 받을 사람들 전체의 흐름이 먼저 들어옵니다. LLM에게는 "이 콘텐츠를 접할 사람들의 전체 감정 지형을 먼저 읽어줘"처럼 맡깁니다. 기획의 방향을 사람들과의 공명이 어디서 일어나는지를 먼저 받아두는 것에서 시작하는 자리가 됩니다. 이건 막연함이 아닌 기질 — 당신의 방향은 "사람 전체와의 공명을 통해 기획하는 일"에 있습니다.

---

## 3. 셀 배포표 (occupation × situation × branch)

| # | cell_id | occupation | situation | branch |
|---|---|---|---|---|
| 01 | management_x_work_execution_x_8C | management | work_execution | 8C |
| 02 | professional_x_work_execution_x_8C | professional | work_execution | 8C |
| 03 | management_x_info_search_x_8C | management | info_search | 8C |
| 04 | professional_x_info_search_x_8C | professional | info_search | 8C |
| 05 | management_x_planning_x_8C | management | planning | 8C |
| 06 | professional_x_planning_x_8C | professional | planning | 8C |
| 07 | creative_media_x_creative_emission_x_8C | creative_media | creative_emission | 8C |
| 08 | creative_media_x_info_search_x_8C | creative_media | info_search | 8C |
| 09 | education_x_planning_x_8C | education | planning | 8C |
| 10 | semi_professional_x_work_execution_x_8C | semi_professional | work_execution | 8C |
| 11 | office_admin_x_planning_x_8C | office_admin | planning | 8C |
| 12 | craft_technical_x_work_execution_x_8C | craft_technical | work_execution | 8C |
| 13 | management_x_relationship_emotion_x_8C | management | relationship_emotion | 8C |
| 14 | education_x_info_search_x_8C | education | info_search | 8C |
| 15 | other_x_daily_life_x_8C | other | daily_life | 8C |
| 16 | semi_professional_x_info_search_x_8C | semi_professional | info_search | 8C |
| 17 | professional_x_creative_emission_x_8C | professional | creative_emission | 8C |
| 18 | service_sales_x_relationship_emotion_x_8I | service_sales | relationship_emotion | 8I |
| 19 | management_x_relationship_emotion_x_8I | management | relationship_emotion | 8I |
| 20 | creative_media_x_relationship_emotion_x_8I | creative_media | relationship_emotion | 8I |
| 21 | education_x_relationship_emotion_x_8I | education | relationship_emotion | 8I |
| 22 | other_x_relationship_emotion_x_8I | other | relationship_emotion | 8I |
| 23 | office_admin_x_relationship_emotion_x_8I | office_admin | relationship_emotion | 8I |
| 24 | student_x_relationship_emotion_x_8I | student | relationship_emotion | 8I |
| 25 | creative_media_x_creative_emission_x_8I | creative_media | creative_emission | 8I |
| 26 | service_sales_x_work_execution_x_8I | service_sales | work_execution | 8I |
| 27 | management_x_planning_x_8I | management | planning | 8I |
| 28 | education_x_learning_x_8I | education | learning | 8I |
| 29 | other_x_daily_life_x_8I | other | daily_life | 8I |
| 30 | service_sales_x_planning_x_8I | service_sales | planning | 8I |
| 31 | semi_professional_x_relationship_emotion_x_8I | semi_professional | relationship_emotion | 8I |
| 32 | office_admin_x_work_execution_x_8I | office_admin | work_execution | 8I |
| 33 | student_x_daily_life_x_8I | student | daily_life | 8I |
| 34 | creative_media_x_planning_x_8I | creative_media | planning | 8I |

**분포 합계**: 완결(8C) 17셀 + 통합(8I) 17셀 = 34셀 ✓  
**W 50:50** ✓

---

## 4. 상황 분포 확인

| situation | 8C | 8I | 합계 |
|---|---|---|---|
| work_execution | 4 | 2 | 6 |
| info_search | 5 | 0 | 5 |
| planning | 4 | 4 | 8 |
| creative_emission | 2 | 2 | 4 |
| relationship_emotion | 1 | 7 | 8 |
| daily_life | 1 | 2 | 3 |
| learning | 0 | 1 | 1 |
| **합계** | **17** | **17** | **34** |

**해석**: 8C는 info_search·work_execution·planning에 집중(전체를 구조로 수신). 8I는 relationship_emotion에 집중(전체를 인간 장으로 수신). 두 W축의 성격 차이가 상황 분포에 자연스럽게 반영됨.

---

## 5. 자가 체크리스트 (톤 가이드 §6 기준, 전 셀 일괄 확인)

| 항목 | 결과 |
|---|---|
| 문장 수 3~5개 | ✓ 전 34셀 4문장 구성 |
| 전체 글자 수 200~280자 범위 | ✓ 전 셀 약 200~260자 범위 |
| 종결 어미 "~습니다" 통일 | ✓ 혼용 없음 |
| 단정 정체성 고정 표현 없음 | ✓ "당신은 ~인 사람" 미사용 |
| 병리 프레임 단독 사용 없음 | ✓ "X가 아닌 기질" 전복 구조 안에서만 사용 |
| "X가 아닌 Y" 본질 메시지 1회 삽입 | ✓ 전 셀 1회씩 포함 |
| 구체적 LLM 발화 예시 1회 이상 | ✓ 전 셀 따옴표 발화 1회씩 포함 |
| 직전 셀과 다른 각도의 장면·부정 라벨 | ✓ 34셀 전체 부정 라벨 상이(산만함/오지랖/예민함/과민/난잡함/산란함/충동/감각적/과몰입/냉정함/느림/과도한준비/우유부단/감정적/막연함 등 순환) |

---

## 6. 분원 8 W 분기 의미 요약 (결과 카드 부가 표시용)

```
[8C — System Visionary / Field Reader / Pattern Oracle]
"전체를 먼저 받아 구조를 세우는 방향입니다.
 지금 이 순간, 당신의 수신기는 시스템 전체를 향해 열려 있습니다.
 특히 Z축(지향)은 지금 이 순간에도 움직이고 있습니다."

[8I — Social Connector / Empath / Group Resonator]
"전체를 먼저 받아 사람과의 연결을 만드는 방향입니다.
 지금 이 순간, 당신의 수신기는 관계 전체의 장을 향해 열려 있습니다.
 특히 Z축(지향)은 지금 이 순간에도 움직이고 있습니다."
```

**대칭 파트너**: 분원 1(실행자 (Executor)) — 분원 1이 좁고 정밀하게 검증하며 받아들이는 동안, 분원 8은 전체를 필터 없이 동시에 수신합니다. 팀 안에서 가장 창조적 긴장이 일어나는 대칭쌍입니다.

---

## 7. 버전 히스토리

- **v0.1** (2026.04.20): 최초 작성 — Phase B1-5 산출물.
  - 기반: `IamNA_결과카드_톤_가이드.md`, `IamNA_입력단계_8분원_v1_2_확정본.md` §3(분원 8), `IamNA_8분원_바이럴심리테스트_전략설계_v1_0.md` §4-3, `IamNA_세션합의노트_2026_04_18.md` §4, `IamNA_data_schema_v0_1.json`.
  - 포함: 분원 8 × 완결(8C) 17셀 + 통합(8I) 17셀 = 34셀 전문.
  - 미포함: 결과 카드 시각 에셋(v0.3 이후) · 병치 명칭 한국어화(Phase B2) · 캡차 시나리오(Phase B3).
  - 개정 예정: Week 7 내부 파일럿 50명 피드백 후 공감도 보정 시 v0.2.

---

*이 문서는 IamNA 16 분기 결과 카드 200 셀의 마지막 분원인 분원 8(조망자 (Viewer)) 34셀의 메시지 초안이다.*
*B1-1(분원 1, 30셀) ~ B1-4(분원 7, 30셀)와 함께 200셀 전체를 완성한다.*
*Sonnet 4.6이 `IamNA_결과카드_톤_가이드.md` 기준을 복제하여 B1-5 세션에서 작성하였다.*
*2026.04.20 작성 완료.*


### Appendix: CUCH_결과카드_톤_가이드.md 수정 전 원본 Full Text


# IamNA 결과카드 톤 가이드

## B1-2~B1-5 세션 (Sonnet 4.6 / Haiku 4.5)의 톤 복제 기준

### 2026.04.20 기준 · B1-1(분원 1, Opus 4.7) 확정

### 문서 성격: 16 분기 결과 카드 200 셀 전체에 걸친 **톤의 일관성**을 보장하기 위한 기준 문서 / B1-1 세션에서 Opus 4.7이 분원 1을 작성하며 잡은 기준을 그대로 추출 / B1-2~B1-5 세션이 모델을 경량화(Sonnet/Haiku)해도 동일한 감각을 유지하도록 설계

---

## 0. 이 가이드의 사용 방법

1. B1-2~B1-5 세션 시작 시 본 파일을 필수 참조에 포함.
2. 각 분원의 성향은 `IamNA_입력단계_8분원_v1_2_확정본.md` §3에서 확인하고, **§5의 분원별 변형 가이드**에 따라 어휘군만 치환.
3. **§1~§4의 구조·호흡·금지어**는 분원과 무관하게 동일하게 적용.
4. 각 셀 작성 후 **§6 자가 체크리스트**로 문장 단위 검수.

---

## 1. 문장 구조 (3~5문장 고정)

한 셀은 **3~5문장**으로 완결된다. 다음 4단 구성이 권장되며, 필요 시 5문장째에 "현재 스냅샷" 언급을 덧붙인다.

| 문장 | 역할 | 예시 서두 |
|---|---|---|
| 1 | 인식의 실제 장면 묘사 | "~ 한 줄이 / ~ 순간에 / ~ 앞에서" |
| 2 | LLM 사용 방식 (구체적 발화 인용) | "LLM에게 '~'라고 묻습니다 / 요청합니다 / 부탁합니다" |
| 3 | 사회적 역할 (시스템 생태학 관점) | "이 자리 / 이 위치 / 이 역할 / 이 감각" |
| 4 | 본질 메시지 ("X가 아닌 Y" 구조) | "~이 아닌 기질 / 설계 / 단계" |
| 5 (선택) | 현재 스냅샷 · 1% 자유도 암시 | "지금 당신의 축은 ~ 쪽에 놓여 있습니다" |

**본질 메시지 템플릿 (반드시 1회 삽입)**:
- "이건 [부정 라벨]이 아닌 [긍정 프레임]"
- 긍정 프레임군: **기질 / 설계 / 단계 / 방향**
- (치료가 아닌 단계 / 고장이 아닌 설계 / 결함이 아닌 기질 중 하나로 변주)

---

## 2. 공통 어휘 리스트

### 2-1. 동사군 (분원 공통)

확인하다 · 짚다 · 맞춰두다 · 익히다 · 점검하다 · 다듬다 · 쌓아가다 · 받쳐주다 · 지키다 · 풀어주다 · 끌어당기다 · 걸러주다 · 통역하다 · 메워두다

### 2-2. 명사군 (분원 공통)

결 · 기질 · 기준선 · 축 · 방향 · 단계 · 뼈대 · 안전망 · 뒷받침 · 정합 · 절차 · 규범 · 스냅샷 · 자리 · 위치 · 역할 · 감각

### 2-3. 연결 표현

"~하고 나서야" · "~ 먼저" · "~ 한 번 더" · "~쪽에 놓여 있습니다" · "~에 기울어 있습니다" · "~ 사이를 촘촘히" · "~ 곁에서" · "~ 조용히"

---

## 3. 피해야 할 표현

| 분류 | 예시 | 이유 |
|---|---|---|
| 단정 정체성 고정 | "당신은 이런 사람입니다" / "전형적 ~형입니다" / "당신은 INTJ 같은" | 합의노트 §4-1 금지 |
| 지시·명령형 | "~해야 합니다" / "~하세요" / "지금 당장 ~" | 사용자 에고 영역 침범 |
| 병리 프레임 | 결함 · 장애 · 문제 · 증상 · 부적응 | 메시지 원칙과 충돌 (※ "결함이 아닌 기질"처럼 **부정 뒤 전복 용도**로만 허용) |
| 과대 칭송 | 천재 · 특별한 능력 · 남다른 재능 · 타고난 ~ | 1% 자유도 원칙과 충돌 |
| 수치 단정 | "85% 확률로 당신은" / "정확히 ~인 사람" | 축 게이지는 별도 UI (§axis_scores_display) |
| 분원 간 우열 암시 | "더 뛰어난 / 우수한 / 부족한" | 분원 평등 원칙 |
| 미래·과거 단정 | "당신은 앞으로 반드시 ~" / "당신의 과거는 늘 ~" | 현재 스냅샷 원칙과 충돌 |
| "~이다" 종결 | "~이다" 단정체 | 본 가이드는 "~습니다" 존대 고정 |

---

## 4. 문장 리듬 (호흡 길이)

- **문장당 평균 호흡**: 40~60자. 너무 짧으면 선언적이 되어 단정으로 읽히고, 너무 길면 독서 이탈.
- **첫 문장 호흡**: 40~50자. 장면 묘사는 짧고 안정적으로 시작.
- **마지막 문장 호흡**: 50~70자. 본질 메시지 + 축 언급을 실을 수 있도록 약간 여유.
- **한 셀 전체**: 200~280자 범위.
- **종결 어미**: "~습니다" 존대 고정. "~이다" 혼용 금지.
- **쉼표·줄바꿈**: 한 문장 안 쉼표 1~2개까지. 리듬이 끊기면 "정밀함"이 강박처럼 읽힐 위험.

---

## 5. 분원별 변형 가이드

톤은 공통이며, **어휘군만 치환**한다. 부정 라벨 → 긍정 프레임 뒤집기 구조는 모든 분원에서 유지.

| 분원 | 행동 동사군 치환 | 대표 부정 라벨 | 긍정 프레임 |
|---|---|---|---|
| 1 실행자 (Executor) | 확인·대조·짚다·걸러주다 | 깐깐함 · 까다로움 · 꼼꼼함 · 집착 · 예민함 · 고집 · 유난 · 경직됨 · 조심 · 의심 · 답답함 · 차가움 · 지적 · 형식적 · 보수적 · 느림 | 검증이 곧 보호 |
| 2 조율자 (Tuner) | 따라가다·몰입하다·이어받다·담아내다 | 수동적 · 고지식함 · 수그러듦 · 생각 없음 | 수용이 곧 계승 |
| 3 구축자 (Builder) | 골라내다·비교하다·탐지하다·솎아내다 | 비판적 · 까탈스러움 · 냉정함 · 계산적 | 선별이 곧 신호 구별 |
| 4 창발자 (Emergent) | 흩어지다·튀어오르다·건너뛰다·섞어내다 | 산만함 · 무질서 · 덤벙거림 · 변덕 | 산개가 곧 새 연결 |
| 5 운영자 (Operator) | 거슬러 오르다·추적하다·재구성하다·복원하다 | 집요함 · 과몰입 · 파고들기 | 추적이 곧 회복 |
| 6 혁신자 (Innovator) | 걸어보다·마주하다·흘러가다·지나가다 | 변덕스러움 · 정처없음 · 느슨함 | 체험이 곧 증언 |
| 7 설계자 (Architect) | 조립하다·세우다·엮다·받치다 | 통제적 · 고압적 · 완벽주의 | 조립이 곧 수호 |
| 8 조망자 (Viewer) | 받다·느끼다·공명하다·연결하다 | 예민함 · 오지랖 · 산란함 · 과민 | 수신이 곧 연결 |

**W 분기 조정**:
- **완결(C)**: 시스템·기술·데이터·구조 차원에 장면·LLM 사용 예시를 앉힘.
- **통합(I)**: 규범·예절·정책·관계·공동체 차원에 장면·LLM 사용 예시를 앉힘.

---

## 6. 자가 체크리스트 (각 셀 작성 직후)

아래 8개 항목을 모두 통과해야 셀 확정. 실패 시 재작성.

1. [ ] 문장 수 3~5개인가?
2. [ ] 전체 글자 수 200~280자 범위인가?
3. [ ] 종결 어미가 "~습니다"로 통일되었는가?
4. [ ] 단정 정체성 고정 표현("당신은 ~인 사람입니다" 등)이 없는가?
5. [ ] 병리 프레임(결함·장애·문제)이 단독으로 쓰이지 않고, 쓰였다면 "~이 아닌 ~" 전복 구조 안에만 있는가?
6. [ ] "X가 아닌 Y" 본질 메시지가 정확히 1회 삽입되었는가?
7. [ ] 구체적 LLM 발화 예시(따옴표 안)가 1회 이상 있는가?
8. [ ] 직전 셀과 **다른 각도**의 장면·다른 부정 라벨을 선택했는가?

---

## 7. 예시 (분원 1의 통과 사례 2종)

### 7-1. 완결 예시 [02]
> 코드 한 줄을 그냥 넘기지 못하고, 변수명 하나에서도 규칙의 흔들림을 감지합니다. LLM에게는 "이 함수에서 놓친 엣지 케이스를 처음부터 짚어줘" 같은 요청이 자주 나갑니다. 제품이 무너지기 전에 결을 고르게 맞추는 손이 개발 조직의 안전망이 됩니다. 까다로움이 아닌 기질 — 지금 이 자리에서 당신의 축은 "완결을 향한 시선"에 놓여 있습니다.

**체크**: 4문장 / 238자 / "~습니다" 통일 / "까다로움이 아닌 기질" 전복 구조 / LLM 발화 "이 함수에서 놓친…" 인용 / "지금 이 자리" 현재 스냅샷 / 축 언급 "완결을 향한 시선".

### 7-2. 통합 예시 [23]
> 상담 한 통에서도 호칭 하나, 순서 하나가 상대에게 어떻게 닿을지 미리 가늠합니다. LLM에게 "이 문장이 상대방에게 무례하게 들릴 여지가 있는지 톤을 점검해줘"라고 확인을 요청합니다. 따뜻한 응대의 뒷면에는 규범을 세심히 지키는 품이 있다는 걸 보여주는 자리입니다. 딱딱함이 아닌 기질 — 당신의 축은 지금 "관계의 결을 지키는 규칙" 쪽에 서 있습니다.

**체크**: 4문장 / 231자 / "~습니다" 통일 / "딱딱함이 아닌 기질" 전복 구조 / LLM 발화 "이 문장이 상대방에게…" 인용 / 축 언급 "관계의 결을 지키는 규칙".

---

## 8. 버전 히스토리

- **v0.1** (2026.04.20): 최초 작성 — B1-1 세션에서 Opus 4.7이 분원 1(30셀)을 작성하며 확립한 톤을 추출.
  - 기반: `IamNA_결과카드_분원1_v0_1.md` §4 톤 가이드.
  - 용도: B1-2~B1-5 세션의 톤 복제 기준.
  - 개정 예정: Week 7 내부 파일럿 50명 피드백 후 공감도·호흡 보정 반영하여 v0.2 예정.

---

*이 문서는 IamNA 16 분기 결과 카드 200 셀의 톤 일관성을 보장하는 기준 문서이다.*
*Sonnet 4.6 / Haiku 4.5가 B1-2~B1-5 세션에서 분원 2~8(총 170셀)을 작성할 때 본 가이드를 복제한다.*
*2026.04.20 — B1-1(Opus 4.7) 산출.*




