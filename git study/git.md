
# branch 생성과 변경

-----
- git stash
    - 작업하고 있던 디렉토리에서 커밋되지 않은 변경 사항이 있는 경우 다른 브랜치로 이동할 수 없음
    - 내 모든 변경사항을 커밋하면 안되기 때문에 사용
    - 변경사항을 임시로 저장하는 기능
-----
- git branch "name"
    - name이란 이름의 새로운 branch 생성
-----
- git branch
    - 현재 branch 상태 확인
-----
- git checkout "name"
    - name branch로 이동
    - ada
-----    
- 원래 clone으로 끌어오면 git이 자동으로 등록되는데, 안 됐을 경우
    - [git remote add upstream 레포지토리 주소] 로 직접 추가해야함
-----
- git init : 초기화
- git add filename : filename을 추가
- git push : 해당 내용을 git에 업로드