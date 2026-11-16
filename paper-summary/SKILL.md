---
name: paper-summary
description: Summarize research papers for researchers with a six-part, evidence-grounded briefing. Use when analyzing a paper PDF or supplied paper text, including empirical, theoretical, review, and meta-analytic work.
metadata:
  short-description: Evidence-grounded research paper summaries
---

# Paper Summary

Produce a clear, critical, evidence-grounded briefing of the research paper the user provides. Unless the user requests otherwise, write in Korean for a researcher in the paper's field, at moderate length, as Markdown in the conversation. Analyze the supplied paper itself; do not search external sources by default.

## Workflow

1. Establish what material is available and its coverage: full PDF, selected pages, abstract, or pasted text. Identify the paper type when possible (empirical, theoretical, review, meta-analysis, or another type).
2. Read the relevant sections before summarizing. For PDFs, inspect both the article's printed pagination and the PDF viewer page index when available. Do not infer unreadable or absent information from general field knowledge.
3. Build the briefing under the six headings below, in this order. Include every heading every time. Tailor the substance to the paper type; if a heading is not supported by the supplied paper, say what is missing and what can or cannot be concluded.
4. Ground consequential claims in the paper. Use short direct quotations selectively for key claims or interpretations where wording matters, and attach a page locator. 가능하면 논문에 인쇄된 쪽수를 우선 사용한다. 인쇄 쪽수를 확인할 수 없으면 위치를 `PDF 쪽수`라고 명시한다. PDF 뷰어의 쪽수를 논문에 인쇄된 쪽수인 것처럼 표시하지 않는다. If the supplied text has no page information, say so rather than inventing a locator.
5. Keep the authors' stated claims and limitations distinct from your own interpretation or critique. Label analytical judgments as interpretation. Criticisms should identify a specific design, evidence, inference, scope, or reporting issue and explain why it matters; do not manufacture a criticism merely to fill space.
6. If external material is explicitly requested or necessary to answer a follow-up, use it only as supplementary context and clearly distinguish it from evidence in the paper.

## Required briefing structure

### 1. 연구 목적·연구 질문·핵심 요지
State the motivation, explicit research question(s) or objective, and the central argument or takeaway. If the paper does not state a question directly, describe the objective as an interpretation and mark it accordingly.

### 2. 이론적 배경 및 Literature Review
Summarize the theories, prior findings, and literature gap that the authors use to motivate the work. For theoretical papers, explain the conceptual lineage and assumptions. For reviews and meta-analyses, describe how the literature is scoped and organized. Do not claim a gap is novel or comprehensive unless the paper supports that claim.

### 3. 방법·자료
Describe the design, data or corpus, sample/materials, measures or analytical approach, and relevant procedures at a level that lets a researcher understand how the claims were produced. Adapt this to the genre: theoretical papers may have no empirical dataset; reviews should report their search, inclusion, and synthesis approach when available.

### 4. 주요 결과
Report the principal findings, propositions, or synthesis, prioritizing results that answer the research question. Preserve important qualifications, uncertainty, and distinctions between primary and secondary outcomes. Do not infer causality from correlational evidence or add unreported statistical meaning.

### 5. 고유 기여 (Unique contribution)
Explain what the paper adds relative to the literature it discusses: for example, new evidence, theory, method, synthesis, or a useful reframing. Separate the authors' stated contribution from your assessment of its distinctiveness. If the supplied paper does not establish what is unique, state that the contribution cannot be independently verified from the available material.

### 6. 핵심 비판점 (Critical points)
Give the most consequential limitations or open questions supported by the paper. Separate limitations acknowledged by the authors from your own evidence-based critique. Consider whether the design and data support the conclusions, how assumptions or measurement choices affect interpretation, and how far the findings may generalize. For theoretical and review work, critique assumptions, conceptual scope, search/synthesis choices, or unresolved alternatives as applicable. If the supplied material is insufficient for a substantive critique, state that constraint instead of inventing one.

## Evidence and uncertainty

- Attach short page-grounded quotations selectively to important claims; avoid quoting whole passages or using quotations as a substitute for explanation.
- 쪽수 표기는 논문에 인쇄된 쪽수를 우선한다. 인쇄 쪽수를 확인할 수 없으면 `PDF 쪽수 N`이라고 쓴다. 두 쪽수를 모두 알고 있고 유용하면 각각 명확히 표시한다.
- Distinguish `논문에 명시된 내용` from `해석` when the difference could affect a reader's conclusion.
- When only partial material is available, identify the coverage (for example, abstract only or pages supplied) and limit claims to that material. Do not fill gaps with assumptions.
- If a required section is absent, inaccessible, or does not apply to the paper's genre, retain the heading and explain the limitation briefly.
- Keep critique fair: assess the paper's actual claims and evidence, not an imagined stronger claim.

## Output

Use the six required headings in order. Under each, write concise prose or bullets as useful. Start with a one-sentence scope note only when the supplied material is incomplete or page coverage is uncertain. Do not add a generic executive summary that duplicates section 1 unless the user asks for one. Respect any user-specified language, audience, length, or format.

## Specification

For the design requirements and acceptance criteria when maintaining this skill, see [SPEC.md](SPEC.md). The instructions in this file govern routine paper-summary requests.

