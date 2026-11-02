# n8n 생활 자동화 팩

Self-hosted n8n automations for daily life — built and operated by myself.

n8n을 Docker로 셀프호스팅하고, 매일 실제로 쓰는 생활 자동화를 직접 만들어 운영하는 프로젝트입니다.

[English](README.md) · [Русский](README.ru.md) · [한국어](README.ko.md)

## 자동화 목록
- [ ] ① 아침 브리핑 — 날씨·환율을 모아 텔레그램으로 전송 (환경 구축 완료, 워크플로 제작 중)
- [ ] ② 관심 사이트 변경 감지
- [ ] ③ RSS·뉴스레터 LLM 요약
- [ ] ④ GitHub 릴리스·이슈 감시
- [ ] ⑤ 웹폼/메시지 응답 → 시트 기록·알림

## 실행 방법
docker compose up -d 후 http://localhost:5678 접속

## 스택
n8n · Docker · Telegram Bot API
