# git-study

Git 학습 및 실습을 위한 저장소입니다.

## 개요

이 레포지토리는 Git의 기본 명령어와 버전 관리 시스템을 학습하기 위해 생성되었습니다.

## 학습 목표

- Git 기본 명령어 이해 및 실습
- 버전 관리 개념 학습
- GitHub 원격 저장소 사용법 습득
- 커밋, 푸시, 풀 등 기본 작업 흐름 이해

## Git 기본 명령어

### 저장소 초기화
```bash
git init
```

### 파일 추가 및 커밋
```bash
git add .
git commit -m "커밋 메시지"
```

### 원격 저장소 연결
```bash
git remote add origin <repository-url>
git push -u origin main
```

### 변경사항 확인
```bash
git status
git log
git diff
```

### 브랜치 관리
```bash
git branch              # 브랜치 목록 확인
git branch <name>       # 새 브랜치 생성
git checkout <name>     # 브랜치 전환
git merge <name>        # 브랜치 병합
```

## 학습 자료

- [Git 공식 문서](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
- [Git 입문 가이드](https://backlog.com/git-tutorial/kr/)

## 프로젝트 구조

```
git-study/
├── test              # 테스트 파일
└── README.md
```

## 실습 내용

이 저장소를 통해 다음과 같은 Git 작업을 실습할 수 있습니다:

1. **파일 생성 및 수정**
   - 새 파일 생성
   - 기존 파일 수정
   - 변경사항 추적

2. **커밋 관리**
   - 의미 있는 커밋 메시지 작성
   - 커밋 히스토리 관리
   - 커밋 취소 및 수정

3. **원격 저장소 작업**
   - Push/Pull 실습
   - 충돌 해결
   - 협업 워크플로우

## 참고 명령어 모음

```bash
# 설정
git config --global user.name "이름"
git config --global user.email "이메일"

# 클론
git clone <repository-url>

# 변경사항 확인
git status
git log --oneline

# 되돌리기
git reset HEAD^        # 최근 커밋 취소
git checkout -- <file> # 파일 변경사항 취소

# 원격 저장소
git remote -v          # 원격 저장소 확인
git pull origin main   # 원격 변경사항 가져오기
git push origin main   # 로컬 변경사항 업로드
```

## 다음 단계

- 브랜치 전략 학습 (Git Flow, GitHub Flow)
- Pull Request 작성법
- 이슈 트래킹
- 협업 시나리오 실습

## 라이선스

학습 목적으로 작성된 저장소입니다.
