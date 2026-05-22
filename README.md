# cowork-assets

코웍(Claude Cowork) 자산 통합 레포지토리. 모국어 alias 카탈로그와 행동 보강 강화 스킬을 한 자리에서 무료 배포한다. 코웍 입문서 4권 "기계어 장벽의 파괴"의 동적 부록이다 — 책이 정적 문맥을 제공하고, 이 레포가 실시간 갱신본을 둔다.

## 자산

### ko-aliases.plugin (v0.4.0)
영어 원본 코웍 스킬을 한국어 트리거로 호출하는 alias 113개 묶음. 모든 alias는 한국어 풀번역 매뉴얼 컨텍스트를 함께 제공한다. 영어 키워드를 외우지 않아도 한국어 자연어로 코웍 스킬을 발동할 수 있다.

### enhance-skills.plugin (v0.1.0)
코웍 행동 보강 강화 스킬 넷.
- session-logger - 세션 간 기억 회복. 작업 내용을 공통 메모리에 기록하고 새 세션에서 복원한다.
- try-alternatives - 불능 선언 전 대안 탐색 강제. "못 합니다" 즉답을 막고 네 체크리스트를 짚는다.
- parallel-research - 서브에이전트 병렬 위임 조사. 한 주제를 여러 각도로 쪼개 병렬 조사 후 취합한다.
- fuzzy-file-finder - 오타 허용 퍼지 파일 검색. 부정확한 키워드로도 유사도 상위 후보를 반환한다.

## 설치

1. 위 .plugin 파일을 내려받는다.
2. 코웍 플러그인 설치 폴더에 떨어뜨린다.
   - Windows: C:\Users\<사용자명>\AppData\Roaming\Claude\plugins\
   - macOS: ~/Library/Application Support/Claude/plugins/
   - Linux: ~/.config/Claude/plugins/
3. 코웍을 재시작한다. 스킬이 등록 목록에 추가된다.

## 다른 모국어로 옮기기

두 plugin의 스킬 본문은 모국어 독립적이다. 각 skills/<스킬>/SKILL.md의 frontmatter description 트리거 키워드만 자기 모국어로 바꾸면, 같은 동작이 어느 모국어에서나 작동한다. 코웍 입문서 4권 7장의 다섯 단계가 그 절차다. 한국어가 첫 카탈로그이며, 다른 모국어 화자가 자기 카탈로그를 한 자리씩 추가해 가는 것이 이 레포의 설계다.

## 라이선스

수록 스킬은 모두 저자 자작이며 외부 라이선스 종속이 없다. 누구든 그대로 받아 쓸 수 있다.

## 저자

박병진 (Vibe Toolsmith)
