# 📅 2025-06-26 TIL - Git 핵심 명령어 정리

## 🛠 Git 환경 설정
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --global core.editor "vim"
git config --list

---

## 📁 Git 저장소 시작
git init                      # 로컬 저장소 생성
git clone <repo-url>         # 원격 저장소 복제

---

## 📄 파일 작업 기본 흐름
git status                   # 변경된 파일 확인
git add <파일명>             # 스테이징
git commit -m "메시지"       # 커밋
git push origin main         # 원격 저장소로 푸시
git pull origin main         # 원격 저장소에서 풀

---

## 🌿 브랜치 작업
git branch                   # 브랜치 목록 보기
git branch <브랜치명>        # 새 브랜치 생성
git switch <브랜치명>        # 브랜치 전환
git merge <브랜치명>         # 병합
git branch -D <브랜치명>     # 브랜치 삭제
git diff main dev            # 브랜치 차이 비교

---

## 🔁 커밋 수정 / 되돌리기
git commit --amend           # 마지막 커밋 수정
git reset --soft HEAD~1      # 최근 커밋 취소 (내용 유지)
git revert HEAD              # 커밋 되돌리기 (기록 남김)

---

## ⚔️ 병합 충돌 해결
git merge <브랜치명>
vi <파일명>                  # <<<<, ==== 등 충돌 부분 수정
git add <파일명>
git commit

---

## 🧼 기타 명령어
git stash                    # 작업 임시 저장
git stash list               # 임시 저장 목록 확인
git stash pop                # 마지막 임시 작업 복원

git restore <파일명>         # 수정 취소
git reset HEAD <파일명>      # 스테이징 취소
git rm -f <파일명>           # 파일 삭제 및 스테이징 해제

---

## 🏷 커밋 메시지 Prefix 규칙

feat:     기능 추가
fix:      버그 수정
docs:     문서 변경
style:    코드 포맷 변경 (기능 X)
refactor: 리팩토링
test:     테스트 추가/수정
chore:    기타 변경
ci:       CI 설정
conf:     환경 설정 관련

---

## ✍️ 오늘의 한 줄 요약
Git은 **작업 흐름을 이해하고, 브랜치/커밋을 명확히 나누는 습관**이 가장 중요하다!

