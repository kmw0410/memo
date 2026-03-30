# 메모
셀프호스트 기반 간단한 메모 애플리케이션
<img width="2551" height="1276" alt="image" src="https://github.com/user-attachments/assets/dbb685e0-371f-4b5b-8c5d-5ef376a41bee" />

[ 한국어 | [ENGLISH](https://github.com/kmw0410/memo/README_EN.md) ]

# 어떻게 쓰나요?
1. 레포지토리를 복사후 디렉토리 이동
2. `docker compose up -d --build` 명령어 실행
3. `localhost:8080` 혹은 `공인_혹은_내부망_IP:8080`으로 접속

# 기술 스택
- 백엔드: PHP 8.4 (PHP-FPM)
- 웹서버: Nginx
- 데이터베이스: SQLite
- 도커 (Alpine 기반)
