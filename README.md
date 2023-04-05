# 깃 고급 특강

## 브랜치

### 정의
- 영어사전: 가지
- git에서의 정의: A brnach in Git is simply a lightweight movable pointer to one of these commit
- 실무에서: 새로운 작업(기능 개발, 버그 수정 등)을 시작할 때 만든다.

### 명령어
1. 브랜치 생성: `git branch 브랜치이름`
2. 생성되어있는 브랜치 보기
    - `git branch` 혹은 `git branch -r`
3. 다른 브랜치로 전환하기
    - `git checkout 브랜치명`
    - `git switch 브랜치명`
4. 브랜치 만들고, 전환까지 동시에 하기
    - `git checkout -b 브랜치명`

#### refernce

00. 브랜치 삭제하기
    - `git brnach -d 브랜치명`
01. 브랜치 병합하기
    - `git rebase 병합하고 싶은 브랜치명`
    - `git merge 병합하고 싶은 브랜치명`

## 로컬 저장소와 원격 저장소 동기화하기

### PUSH
    - git push 명령어를 사용하면 로컬 저장소의 브랜치에 있는 커밋들을 원격 저장소에 특정 브랜치로 push해서 동기화 할 수 있다.

## 커밋 되돌리기
### git reset
- `git reset`을 사용하면 현재 체크아웃한 브랜치의 원하는 과거 커밋으로 HEAD를 이동시키고, 그 이후의 커밋들은 모두 버릴 수 있습니다. 원치 않는 커밋을 되돌릴 때 유용한 명령어 입니다.
- [참고자료](https://violet-bora-lee.github.io/git-tutorial/#reset)


dvgevsevbsgbesv