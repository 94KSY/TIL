# 250626 Git 기본 작업 순서

📅 2025-06-26

## 📌 Git 작업 순서 요약

1. 작업하기
2. `git status` – 변경 사항 확인
3. `git add` – 스테이징
4. `git commit` – 커밋 (스냅샷 저장)
5. `git push` – 원격 저장소에 업로드

## 💡 기억할 것

- 커밋 메시지는 명확하게 (예: `feat: Add login logic`)
- **커밋 메시지에 prefix 꼭 달기**  
  | prefix | 의미 |
  |--------|------|
  | `feat:` | 기능 개발 관련 |
  | `fix:` | 오류 개선 혹은 버그 패치 |
  | `docs:` | 문서화 작업 |
  | `test:` | 테스트 관련 |
  | `conf:` | 환경 설정 관련 |
  | `build:` | 빌드 작업 관련 |
  | `ci:` | Continuous Integration 관련 |
  | `chore:` | 패키지 매니저, 스크립트 등 기타 작업 |
  | `style:` | 코드 포매팅 관련 (기능 변경 없음) |
