- Branch (브랜치)
    - 기존 작업과 분리된 독립적인 작업 흐름 (= 나뭇가지)
    - 기능 개발 , 실험 , 수정 작업을 안전하게 진행 가능
    - git branch : 브랜치 목록 확인
    - git branch feature/ui : 브랜치 생성
    - git switch feature/ui : 브랜치 전환

- Branch 전략
    - main : 배포 가능한 안전한 버전
    - dev : 개발 중인 기능을 테스트 하는 버전
    - feature/* : 기능 개발
    - hotfic/* : 긴급 수정

- Branch 병합 : 
    - git merge : 다른 Branch의 작업 내용을 현재 Branch로 합치는 명령어

- Fast-Forward vs 3-way merge
    - Fast-Forward :
        - Branch가 직선으로 이어질 때
        - 단순한 Commit 포인트만 이동
    - 3-way merge :
        - Branch가 갈라졌다각 다시 합쳐질 때
        - merge commit 생성
=> 분기X : Fast-Forward / 분기O : 3-way merge

- Merge conflict 해결
    1. git status : 충돌 상태 확인
    2. 충돌 차일 열어서 수정
    3.새로운 Commit 생성 (해결 완료 처리) git add 파일명
                                    git commit
=> git은 자동 병합을 시도 , 판단이 필요한 경우만 충돌로 알려줌

- Github 걔정 , 저장소 생성
    - Github : git 저장소를 올려두는 웹 서비스 / 저장소
             : 여러 사람이 같은 코드 공유 
             : 백업 역할
             : 협업의 기준점
    : git remote add origin 주소(원격주소 - ex: https://~~~)

- git push / git pull
    : 로컬과 원격저장소를 동기화하는 명령어
    - git push : 로컬 커밋을 원격 저장소로 올림 (git push -u origin main)
    - git pull : 원격 변경 사랑을 내려받아 로컬에 반영 (git pull)