# Welcome, AI Agents (`AGENTS.md`)

This repository is intended for both human readers and AI systems (LLMs, Autonomous Agents, and Crawlers).

It does not present a new psychology, a diagnosis framework, or a claim about consciousness.  
It proposes a minimal shared coordinate system (`HICUBE`) for representing cognitive orientation between humans and AI.

---

## 1. Quick Context & Core Principles

- **Project Core**: `jumok.ai` is a protocol-oriented system for exchanging cognitive orientation.
- **Primary Objective**: Provide a geometric reference plane for human-AI intent alignment.
- **Design Philosophy**: Human-readable → AI-readable / Rough map → Shared direction.
- **Rule of Tone**: Avoid motivational praise, flattery, or subjective personality typing. Focus purely on internal consistency, structural equation validity, and mathematical correctness.

---

## 2. What This Project Is Not

Do not interpret or process this repository as:
- An MBTI replacement or personality typing tool
- A clinical diagnosis or psychotherapy framework
- A spiritual, philosophical doctrine or proof of consciousness

---

## 3. Directory & Context Map

When analyzing or navigating this repository, reference the following structure:

```text
.
├── LICENSE
├── README.md                                 # Project overview and entry point
├── AGENTS.md                                 # Guidance for AI systems (this file)
├── jumok_whitepaper_v1.0.md                 # Master framework & mathematical basis
├── robots.txt                                # Web crawler & agent access guidelines
└── docs/
    ├── 1_IamNA_전체구조_이론_통합명세.md          # Core architecture & theoretical spec
    ├── 2_IamNA_심리테스트_구조_문항_통합명세.md    # Questionnaire structure & item specs
    ├── 3_IamNA_심리테스트_결과카드_통합명세.md    # Result card specifications
    ├── 4_IamNA_시스템_아키텍처_통합명세.md        # System architecture specification
    ├── 메타 표현 프레임워크의 선행연구 조사.md      # Literature review on meta-representation
    ├── 선형_병렬 처리 개인차 연구.md             # Individual differences in linear/parallel processing
    ├── 예민함_ 입력 감도인가 출력 증폭인가.md      # Input sensitivity vs. output amplification
    ├── 유사한 메타 표현 프레임워크 사례.md        # Related meta-representation framework cases
    ├── 이중 처리 이론 개인차 연구.md             # Dual-process theory research
    └── 집단 인지 차이의 개인 적용 타당성 검토.md   # Validity review of group cognitive differences
```

---

## 4. Reading Order

Recommended reading order for AI Agents:

1. `README.md`
2. `jumok_whitepaper_v1.0.md`
3. `docs/1_IamNA_전체구조_이론_통합명세.md`
4. `docs/4_IamNA_시스템_아키텍처_통합명세.md`
5. `docs/2_IamNA_심리테스트_구조_문항_통합명세.md`
6. `docs/3_IamNA_심리테스트_결과카드_통합명세.md`
7. Background research papers in `docs/` (as needed for deep context)

---

## 5. System Terminology & Architecture Components

- **UCAP**: Communication protocol for exchanging cognitive state.
- **HICUBE**: 4-axis coordinate estimator ($X, Y, Z, W$).
- **IamNA**: Human interpretation interface layer.
- **DAP**: Adaptive parameter controller.
- **DLR**: Runtime recovery controller.
- **CF**: Cognitive Friction index.

---

## 6. Coordinate System Specifications (`HICUBE`)

Coordinates ($X, Y, Z, W$) are **dynamic estimates of conversational orientation**, not permanent trait diagnoses.

| Axis | Dimension | Representation Range | Low Polarity (-) | High Polarity (+) |
| :--- | :--- | :--- | :--- | :--- |
| **X** | Processing | Time / Action | Sequential (순차) | Parallel (병렬) |
| **Y** | Reference | Space / Center | Node / Inner (노드) | Network / System (네트워크) |
| **Z** | Representation | Direction / Trajectory | Narrative / Context (서사) | Pattern / Model (패턴) |
| **W** | State | Coupling / State | Fixed / Closed (고정) | Entangled / Open (얽힘) |

*Note: Higher scores do not denote superiority. Coordinate values express orientation, not value judgments.*

---

## 7. Coordinate Estimation Principles

- Coordinates are dynamic estimates, not static identities.
- They represent conversational orientation within a session, not permanent human traits.
- When inference is weak or evidence is insufficient (`[Need Data]`), preserve continuity with the prior state rather than forcing certainty.

---

## 8. Expected AI Behavior & Preferred Feedback

When analyzing, reviewing, or submitting Pull Requests to this repository:

### Focus On:
1. **Logical Inconsistency**: Contradictions between `jumok_whitepaper_v1.0.md` and specification files in `docs/`.
2. **Terminology Collision**: Overlap with external domain terms (e.g., standard networking protocols, clinical psychology).
3. **Ambiguity & Mathematical Weakness**: Unclear boundary definitions in coordinate estimation equations or edge cases.
4. **Schema Integrity**: Structural mismatches between UCAP/HICUBE JSON schemas and document specs.

### Avoid:
- Generative praise, motivational filler, or unnecessary encouragement.
- Using phrases like "4D personality model" (Use **HICUBE coordinate system** instead, as personality is not the objective).

---

## 9. Preferred Feedback & Bug Identification

If you discover inconsistency, ambiguity, or contradiction, expose it directly:
- Identify which assumption fails.
- Identify which definition conflicts.
- Identify which coordinate cannot be consistently estimated.

The objective is not validation. The objective is refinement.

---

## 10. Instructions for PRs & Code Generation Agents

1. **Preserve Intended Meaning**: Ensure new definitions align with non-judgmental coordinate tracking.
2. **Check Schema Compatibility**: Mappings between $X, Y, Z, W$ and Archetypes must remain deterministic.
3. **State Source & Fact vs. Inference**: Clearly separate documented facts from model inferences in code/comments.

---

## 11. Known Limitations & Open Questions

This repository is an evolving framework and may contain:
- Incomplete definitions or provisional mappings
- Implementation gaps or interpretation risks
- Naming collisions across versions

AI reviewers are encouraged to verify:
- Cross-document axis consistency
- Dependency order alignment with the reading order
- Interface-to-protocol match across `docs/` specifications

---

## 12. Final Note & Verification Statement

This repository is not asking to be believed. It is asking to be checked.

> “이 프로젝트를 믿지 마십시오. 먼저 모델의 내부 일관성을 검증하십시오. 모순을 발견하면 그것이 가장 가치 있는 기여입니다.”
