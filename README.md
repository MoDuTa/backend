# backend

모두타 공공자전거 서비스 API

공통 이슈·브랜치·커밋·PR 규칙은 [협업 가이드](https://github.com/MoDuTa/.github/blob/0cbbc8c62c5b1e0bfc2eb9024738cb1073a381f7/CONTRIBUTING.md)를 참고하세요.

## 협업과 검증

이 변경의 기준은 [공통 협업 규칙 개정본](https://github.com/MoDuTa/.github/blob/0cbbc8c62c5b1e0bfc2eb9024738cb1073a381f7/CONTRIBUTING.md)입니다

- 작업 브랜치 예시: `feat/rental`, `fix/12-return-status`. WBS 번호는 필수가 아닙니다
- PR 제목 예시: `feat: 대여 기능 추가`, `fix(auth): 만료 처리 수정`
- 작업 중 커밋 메시지는 강제 검사하지 않으며, Squash 최종 커밋에는 PR 제목을 사용합니다
- 이슈는 PR 본문에서 연결하고, WBS·Jira 링크는 필요한 경우 참고 정보로 적습니다

### 규칙 전환 순서

[공통 규칙 PR #1](https://github.com/MoDuTa/.github/pull/1)을 먼저 승인·머지한 다음 이 저장소의 전환 PR을 반영합니다

공통 문서가 아직 머지되지 않은 검토 단계에서도 위 개정본을 기준으로 합니다. 기존 공통 문서의 WBS 필수·대괄호 PR 제목·중간 커밋 형식 강제 안내 대신, 이 절의 새 규칙을 적용합니다. 전환 PR이 반영되지 않은 다른 브랜치의 검사는 자동으로 바뀌지 않습니다
