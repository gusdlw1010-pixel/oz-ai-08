Git & Github

- 바이브 코딩 (Vibe Coding)
    - C , C++ , JAVA , Python 등 컴퓨터가 이해할 수 있는 언어로 코딩한 것
    - 자연어 코딩 , AI 코딩

- Version Control (버전 관리)
    - 파일 , 코드의 변경 이력을 체계적으로 기록 , 관리
    - 언제 , 누가, 무엇을 바꿨는지 알 수 있음
    - 과거 상태로 되돌리기 가능
    => 변경 이력을 추적 , 실수 복구 , 충돌 없이 협업 가능

- Git vs 파일 복사
    - 파일복사
        - 파일이 늘어남 / 어떤 파일이 최신인지 알 수 없음 / 변경 이유와 내용이 남지 않음
    - Git
        - 변경 내용이 Commit 단위로 남음 / 언제든지 특정 시점으로 되돌릴 수 있음

- Git vs Github
    - Git : 버전 관리를 위한 도구 (프로그램)
          : 자신의 컴퓨터에서 동작
    - Github : Git 저장소를 올려두는 웹 서비스
             : 코드 공유 및 협업 플랫폼
=> Git 은 버전 관리 엔진 / Github 는 협업과 공유를 위한 서비스

- Repository (레포지토리)
    - 파일과 그 변경 이력을 함께 관리하는 저장소
    - 프로젝트 전체와 모든 버전 기록이 들어있음
        - 로컬 저장소 : 자신의 컴퓨터 저장소
        - 원격 저장소 : 서버 (Guthub)에 있는 저장소

- Commit (커밋)
    - 변경사항을 하나의 기록으로 저장하는 단위 

- Branch (브랜치)
    - 독립적인 작업 공간
    - 새로운 기능 개발 , 버그 수정 등 작업을 다른 브랜치에서 진행 가능
    - 기본 브랜치 : main (또는 master)
    - 브랜치를 합치는 것 : Merge

- Head (헤드)
    - 현재 작업 중인 위치를 가리키는 포인터
    - 현재 Branch의 최신 Commit을 가리킴
    - Head가 움직임 -> 작업 기준 변경

- Working Directory (작업 디렉토리)
    - 현재 작업 중인 파일들이 있는 디렉토리
    - Git이 관리하는 파일과 Git이 관리하지 않는 파일이 섞여 있음

- Staging Area (스테이징 영역)
    - Commit을 준비하는 영역

- git config
    - git 기본 동작 설정 명령어

- git init
    - 새로운 Git 저장소를 생성하는 명령어
    - 현재 폴더를 git Repository로 초기화

- git status
    - 현재 상태 확인 명령어
    - 변경된 파일 , Staging Area에 올라간 파일 , Commit 여부 확인 가능

- git add
    - Staging Area에 파일을 올리는 명령어

- git commit
    - Staging Area에 올라간 파일을 Commit하는 명령어