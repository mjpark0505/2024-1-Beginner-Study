## What-I-Learned

# 브랜치 종류

Main Branches
- main(master)
- develop

Supporting branches
- feature
- release
- hotfix

# main
프로젝트 생성 시 기본으로 생성되는 브랜치
영원히 존재하는 첫 번째 브랜치
병합될 때마다 제품의 새로운 버전이 탄생
main이라는 이름 대신 master를 사용하기도 함

# develop
영원히 존재하는 두 번째 브랜치
feature 브랜치의 기반이 됨

# feature
develop 브랜치에서 분기하여 작업
기능 개발 완료 후 다시 develop으로 병합
대부분의 이름 가능
(단, main, master, develop, release, hotfix 제외)

# release
배포 준비를 위한 브랜치
자잘한 버그를 수정하고 QA 작업을 함
develop 브랜치에서 분기하여 main 브랜치로 병합

# hotfix
배포 환경에서 즉각적인 수정이 필요할 경우 사용
main 브랜치에서 분기
main, develop 모두에 병합 필요
