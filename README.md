# environment-test
깃허브 협업환경 조성 테스트

소스트리 사용

마스터브랜치에서 하위브랜치 develop과 4인1조 를 기준으로 각 멤버별 feature/member~브랜치를 생성하였으며,
member브랜치에서 develop브랜치로 커밋앤푸쉬를 해야합니다.

develop브랜치는 feature/member~ 브랜치들의 모든 커밋데이터를 검증하는 역할을 맡고있으며,
develop브랜치에서 검증이 끝나면 develop브랜치가 마스터브랜치인 live-distribution 브랜치로 커밋앤푸쉬 절차를 진행합니다.

결과적으로 검증과정을 거친 데이터가 live-distribution 에 기록이 남으며 아직 develop브랜치에서 하위브랜치로 롤백을 하는 것은 해보지 못하였습니다.

