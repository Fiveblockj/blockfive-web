# Block Five 회사 소개 웹사이트

일상을 더 즐겁게 만드는 앱을 만드는 **Block Five(블록 파이브)**의 공식 회사 소개 사이트입니다.

- 순수 HTML + 인라인 CSS 단일 파일 (`index.html`)
- 프레임워크·빌드 도구 없음, 반응형(모바일 우선), 한국어
- GitHub Pages 배포 · 커스텀 도메인 [blockfive.kr](https://blockfive.kr)

## 로컬 미리보기

```bash
# 그냥 파일을 열거나
open index.html
# 또는 간단한 로컬 서버
python3 -m http.server 8000   # http://localhost:8000
```

## 구조

```
index.html      # 전체 사이트 (인라인 CSS)
favicon.svg     # "B" 이니셜 파비콘
CNAME           # blockfive.kr
assets/         # 앱 아이콘 이미지 (haengte.png, gomin.png)
```

## 배포

`main` 브랜치에 push하면 GitHub Pages(root)가 자동 배포합니다.
