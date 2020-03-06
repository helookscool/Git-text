# 깃플로우
지금까지 커밋, 브랜치, 병합, 태그 등 깃의 기본 동작들에 대해 학습하였습니다. 이번 장에서는 깃을 이용한 개발 방법론에 대해서 알아봅니다.

## 브랜치 전략
여러 개발자들과 하나의 프로젝트를 진행하는 것은 쉬운 일이 아닙니다. 서로 각자의 스타일로 개발할 경우, 협업에 많은 혼동이 발생할 수 있습니다. 원활한 작업을 위해서 공동 작업 규칙을 설정하는 것이 중요합니다.

* [브랜치](gitflow)
* [깃 플로우](gitflow)
* [깃허브 플로우](gitflow)
* [깃랩 플로우](gitflow)
* [진입장벽](gitflow)

## 실습준비
깃 플로우는 로컬 저장소와 원격 저장소를 동기화하면서 실습을 같이 하도록 합니다. 

* [실습폴더](practice)
* [원격저장소](practice)
* [도구](practice)
* [내장기능](practice)

## 초기화
실습 환경은 단순히 저장소를 생성하고 원격 저장소와 연동만 되어 있습니다. 깃 플로우를 실습하기 위해서는 추가로 플로우 초기화를 해주어야 합니다.

* [명령어](init)
* [초기화](init)
* [확인](init)
* [동기화](init)
* [소스트리](init)

## master 브랜치
Master 브랜치는 처음으로 생성되는 기본 브랜치입니다. 깃 저장소를 초기화한 후, 처음 커밋할 때 자동으로 생성되는 브랜치입니다. 

* [브랜치](master)
* [테그](master)

## develop 브랜치
깃 플로우를 초기화하면 자동으로 develop 브랜치를 생성합니다. develop 브랜치는 깃 플로우의 첫 번째 전략입니다. 

* [Develop 의미](develop)
* [Develop 생성](develop)
* [Develop 병합](develop)

## Featuer 브랜치
Feature 브랜치는 새로운 기능을 추가하기 위한 작업 브랜치입니다. 실제의 코드 작업들은 Feature 브랜치에서 이루어집니다. 코드를 수정하고 커밋합니다.
* [Feature 의미](feature)
* [Feature 생성](feature)
* [Feature 배포](feature)
* [Feature 닫기](feature)

## Release
Release 브랜치는 개발 완료된 코드 버전을 배포하기 위한 전략입니다. 현재의 코드 상태가 최신으로 최종 사용자에게 배포할 수 있는 상태라면 release 브랜치를 생성합니다.

* [브랜치 의미](release)
* [브랜치 생성](release)
* [테스트](release)
* [원격 배포](release)
* [브랜치 종료](release)
* [직접 배포](release)

## Hotfix
Hotfix는 배포된 버전에 문제가 생기면 해결하기 위한 전략입니다. 별도로 브랜치를 생성하고 버그를 수정합니다. Hotfix는 짧은 호흡의 브랜치로 한 가지 작업만을 위해서 생성되고 삭제됩니다.

* [브랜치 의미](hotfix)
* [브랜치 생성](hotfix)
* [버그 수정](hotfix)
* [핫픽스 완료](hotfix)
* [핫픽스 배포](hotfix)


## 정리
플로우 브랜치 전략은 프로젝트를 안정적으로 진행하는 데 도움이 되는 브랜치 전략입니다. 이 브랜치 전략은 새롭게 등장한 것이 아니라 여러 프로젝트를 진행하면서 경험에서 나온 전략들입니다.

깃 플로우 전략을 기본으로 수많은 파생 전략들이 나오고 있습니다. 이는 개발 프로세스별로 적합한 모델들이 다양하게 존재하기 때문입니다.

플로우는 또한 여러 사람들과 협업을 통하여 작업을 할 때 좀 더 가치를 발휘하게 됩니다. 하지만 팀 구성원 모두 플로우 동작을 이해하고 익숙해지기 위한 연습이 필요합니다.