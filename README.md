# GitStudy

## git과 github 차이

### git
- local repository의 버전 관리 도구 
  
### github
- 협업을 위한 원격 저장소 

### 저장소
  - Working Directory 
     - 내 PC에서 git을 사용하는 작업공간
  - Local Repository 
    -  임시 버전들이 올라가는 공간 
    -  git
  - Remote Repository 
    -  최종 확정본이 올라가는 공간 
    -  github

## Git 명령어
### Working directory -> Local Repository
- $ git init
  - 이 폴더에서 깃 시작  
- $ git add
  - 파일을 스테이지로 올릴 때 사용
  - (사용) $ git add <파일명>
  - (모든 파일) $ git add .
- $ git commit
  - (사용) git commit -m "메세지"
  - 메세지 필수


### Local Repository -> Remote Repository
- $ git push
  - 로컬 저장소에 있는 내용을 원격 저장소에 저장
  - (사용) $ git push origin <브랜치명>

### Remote Repository -> Local Repository
- $ git pull
  - 원격 저장소에 있는 내용은 로컬 저장소(Local Repository)에 반영
  - (사용) $ git pull origin <브랜치명>

### 기타
- $ git status
  - 깃의 상태 출력

- $ git restore
  - 수정한 파일 되돌리기
  - 파일이 수정되었고, 스테이지에 올라가 있지 않는 상태에서 사용
  - (사용) $ git restore <파일명>
  - (모든 파일) $ git restore .

- $ git restore --stage
  - 스테이지에 올라간 경우(add 사용 후) 되돌리기
  - $ git restore --stage <파일명>



## 사용 방법

### 깃 허브에 저장하기
- $ git status
- $ git add .
- $ git commit -m "0518"
- $ git push origin jiyoung
