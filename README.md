# 코덱스로 업무 자동화 편리하게 만들기

2026 찾아가는 학교컨설팅 오남중학교 맞춤형 연수(모듈4) 자료입니다.

- 사이트: <https://agent20261106.web.app>
- Firebase 프로젝트 `lecture-c5f9b`, Hosting 사이트 `agent20261106`

## 들어 있는 것

| 경로 | 내용 |
|---|---|
| `public/index.html` | 첫 화면. 자료와 내려받기 목록 |
| `public/slides.pdf` | 사례 슬라이드 22쪽 |
| `public/guide/` | Codex 실습 안내서(실습 A~F, 90분) |
| `public/downloads/oname-codex-practice.zip` | 폴더 정리 연습용 가상 파일 27개 |
| `public/vibe/` | 바이브코딩 학습지(2026.6.19. 연수) |

## 배포

```
firebase deploy --only hosting
```

안내서의 실습 폴더 `AI연수실습.zip`은 아직 들어 있지 않습니다. `public/downloads/`에 넣고 첫 화면에 한 줄을 더하면 됩니다.
