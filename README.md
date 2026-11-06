# 코덱스로 업무 자동화 편리하게 만들기

2026 찾아가는 학교컨설팅 오남중학교 맞춤형 연수(모듈4) 자료입니다.

- 사이트: <https://agent20261106.web.app>
- Firebase 프로젝트 `lecture-c5f9b`, Hosting 사이트 `agent20261106`

## 들어 있는 것

| 경로 | 내용 |
|---|---|
| `public/index.html` | 연수 웹앱. 준비 체크, 사례 화면(누르면 크게), 실습에서 할 말 복사, 주의할 점 |
| `public/img/` | 사례 화면 캡처 |
| `public/slides.pdf` | 사례 슬라이드 22쪽 |
| `public/guide/` | Codex 실습 안내서(누를 곳 그림) |
| `public/downloads/oname-handout.zip` | 실습 파일 `배부용_오남중학교`(설치 파일 제외, 27개) |
| `public/downloads/oname-codex-practice.zip` | 폴더 정리 연습용 가상 파일 27개 |
| `public/vibe/` | 바이브코딩 학습지(2026.6.19. 연수) |

## 배포

```
firebase deploy --only hosting
```
