# backend 리뷰 규칙

백엔드 팀이 정한 backend 저장소의 리뷰 규칙입니다. 브랜치·커밋·PR 형식과 머지 흐름은 [MoDuTa/.github CONTRIBUTING.md](https://github.com/MoDuTa/.github/blob/main/CONTRIBUTING.md)를 따릅니다.

## 리뷰어 지정과 승인

1. PR을 열면 **Reviewers**에 백엔드 팀원 중 리뷰받을 사람을 지정합니다. 작성자 본인은 지정할 수 없습니다.
2. Discord에 리뷰 요청을 직접 남깁니다.

   ```text
   [리뷰 요청] [0.0.3] 협업 규칙 정비
   @리뷰어 PR 링크
   요약: 한두 줄로 무엇을 바꿨는지
   ```

3. 리뷰어는 고칠 점이 있으면 Approve하지 않고 리뷰를 남깁니다. 리뷰를 제출할 때 **Request changes**를 고르면 PR에 "변경 요청" 상태가 표시됩니다.
4. 작성자는 리뷰 코멘트를 반영하거나, 반영하지 않는 이유를 답글로 남긴 뒤 push하고, 리뷰어에게 다시 리뷰를 요청합니다(Reviewers의 재요청 버튼).
5. 리뷰어는 요구한 사항이 모두 해결됐는지 확인하고, 해결된 코멘트를 **Resolve conversation**으로 닫습니다. 모두 해결되면 Approve합니다.
6. 지정한 리뷰어 **전원**이 Approve해야 머지할 수 있습니다. "리뷰 승인 규칙" 검사가 이를 확인합니다. 필요한 사람만 지정하고, 잘못 지정했다면 Reviewers에서 빼면 됩니다.
7. **리뷰어가 직접 Squash merge합니다.** 리뷰어가 여러 명이면 마지막으로 Approve한 리뷰어가 머지합니다. 작성자는 머지하지 않습니다.

Approve 뒤에 작성자가 커밋을 더 push하면 승인이 풀립니다. 리뷰어에게 다시 요청하고 Approve를 받습니다.

CodeRabbit 코멘트도 같은 방식으로 반영하거나 이유를 답글로 남기고 Resolve합니다. 해결되지 않은 코멘트가 남아 있으면 머지할 수 없습니다.

CodeRabbit은 PR을 열면 자동으로 리뷰하므로 Reviewers에 지정하지 않습니다. 지정하면 CodeRabbit은 Approve를 하지 않아 검사가 통과하지 않습니다.
