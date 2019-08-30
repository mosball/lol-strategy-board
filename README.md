# lol-strategy-board
Online service for League of Legends strategy meeting
## branch 전략
- master : 배포 전용 브랜치
- dev : 이번 출시버전을 준비하는 브랜치
- feature : 기능을 개발하는 브랜치
- hotfix : 출시 버전에서 발생한 버그를 수정하는 브랜치

### branch 규칙

#### 기능 개발 규칙 - feature
- 브랜치 네이밍은 다음과 같이 한다. feature-xxx
    - xxx는 최소 단위 기능으로 한다. ex)featrue-login, feature-join
- 기능 개발은 feature 브랜치에서 브랜치를 생성하여 개발한다.
- 개발이 완료되면 해당 브랜치를 삭제한다.
- feature에서 일정 수준 이상으로 개발을 완료하면 dev로 merge한다.
