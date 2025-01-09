## upstream
다른 개발자가 생성한 원격 저장소에 있는 변경사항을 로컬 저장소로 가져오는 역할   
협업하고 있는 프로젝트의 최신 업데이트를 받아올 수 있음
---
#### 사용 방법
1. upstream 설정 방법
- 로컬 저장소의 터미널에서 `git remote add upstream [원격 저장소 url]` 명령어 실행
- upstream 원격 저장소를 추가했으며, 변경사항을 가져오기 위해 `git fetch upstream` 명령어를 실행할 수 있음
2. upstream 설정 후 사용 방법
- `git fetch upstream` 명령어를 실행하여 원격 저장소의 변경사항을 로컬 저장소로 가져옴
- 가져온 변경사항을 로컬 브랜치에 병합하기 위해 `git merge upstream/[branch name]` 명령어를 실행
---
#### 명령어
- `git remote add upstream [원격 저장소 url]` : 로컬 저장소에 upstream 원격 저장소를 추가
- `git remote -v` : 현재 설정된 원격 저장소 목록을 확인
- `git fetch upstream` : upstream 원격 저장소의 변경사항을 로컬 저장소로 가져옴
- `git merge upstream/[branch name]` : 가져온 upstream 변경사항을 로컬 브랜치에 병합
- `git remote remove upstream` : upstream 원격 저장소 설정을 제거
---
#### 주의사항
- 충돌이 발생할 수 있으므로 병합을 진행하기 전에 변경사항을 잘 확인
- 원격 저장소의 [url]이 변경되면 다시 설정