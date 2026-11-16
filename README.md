# paper-summary

연구논문을 연구자 관점에서 근거 중심으로 요약하는 Codex 스킬입니다. 실증 연구, 이론 논문, 리뷰와 메타분석을 지원합니다.

기본 요약은 한국어 Markdown 브리핑으로 제공하며, 연구 목적·질문·핵심 요지, 이론적 배경 및 Literature Review, 방법·자료, 주요 결과, 고유 기여, 핵심 비판점을 다룹니다. 논문에 인쇄된 쪽수를 우선해 짧은 직접 인용과 위치를 표시하며, 근거가 부족한 내용은 임의로 채우지 않고 확인 범위와 한계를 밝힙니다.

## Codex에 설치

Codex에서 `skill-installer`를 사용하고 아래 경로를 지정하세요.

`https://github.com/KwonSuwan/paper-summary/tree/main/paper-summary`

설치 후 다음 대화부터 `$paper-summary`로 호출하거나 논문 PDF 또는 본문을 제공해 요약을 요청할 수 있습니다.

## ZIP으로 수동 설치

1. 저장소에서 **Code → Download ZIP**을 선택합니다.
2. 압축을 풀고 `paper-summary` 폴더를 `$CODEX_HOME/skills/`에 복사합니다. `CODEX_HOME`이 설정되지 않았다면 `~/.codex/skills/`를 사용합니다.
3. Codex에서 `$paper-summary`를 호출합니다. 스킬이 표시되지 않으면 Codex를 다시 시작하세요.

## 패키지 파일

- `paper-summary/SKILL.md`: 스킬 지침
- `paper-summary/SPEC.md`: 설계 명세와 수용 기준
