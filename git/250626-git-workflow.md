# 2025-06-26 TIL - Git 기본 명령어 정리

## Git 환경 설정
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --global core.editor "vim"
git config --list

## 저장소 초기화 및 클론
git init
git clone <repo-url>

## 파일 작업 흐름
git status
git add <파일명>
git commit -m "커밋 메시지"
git push origin main
git pull origin main

## 브랜치 작업
git branch
git branch <브랜치명>
git switch <브랜치명>
git merge <브랜치명>
git branch -D <브랜치명>
git diff main dev

## 커밋 수정 및 되돌리기
git commit --amend
git reset --soft HEAD~1
git revert HEAD

## 병합 충돌 해결
git merge <브랜치명>
vi <충돌된 파일>
# <<<< ==== >>>> 등 충돌표시 수정
git add <파일명>
git commit

## 커밋 메시지 Prefix 예시
feat:     새로운 기능 추가
fix:      버그 수정
docs:     문서 관련 변경
style:    코드 스타일 변경 (기능 변경 없음)
refactor: 리팩토링
test:     테스트 코드 추가/수정
chore:    기타 작업 (빌드, 설정 등)
ci:       CI 관련 설정
conf:     환경 설정 관련

## 기타 유용한 명령어
git stash
git stash list
git stash pop
git rm -f <파일명>
git restore <파일명>
git reset HEAD <파일명>

## 오늘의 한 줄 요약
Git은 작업 흐름과 브랜치 전략을 익히고, 커밋 메시지를 명확하게 쓰는 것이 핵심!
