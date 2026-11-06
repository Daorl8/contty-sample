# STRUCTURE · contty-sample

```
contty-sample/
├─ index.html                 단일 파일 (CSS·JS 인라인)
├─ wrangler.toml              name = contty-sample → contty-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ cn-diphylleia.woff2        한글 제목 (디필레아 400, 쓰는 글자만)
├─ cn-dmserif-italic.woff2    영문 라벨 (DM Serif Display Italic, 라틴 + Latin-1)
├─ cn-pretendard.woff2        본문 (Pretendard 400–700, 쓰는 글자만)
├─ cn-logo.webp / cn-logo-c.webp   로고 빨강(헤더) · 크림(푸터)
├─ cn-window.webp             히어로 창가
├─ cn-brunch / soup / pasta / risotto / cheesecake / croissant .webp   브런치
├─ cn-bottles / counter .webp                                         커피와 술
├─ cn-bar / sofa / audio / plants / room .webp                        공간
├─ cn-sign.webp               오시는 길 입간판
├─ favicon.png · og-contty.jpg
├─ img/                       다올 제공 원본 34장 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → 체크 띠 → `#brunch` → `#drinks`(띠색) → `#space` → 체크 띠 → `#visit`(띠색) → 푸터(어두움) + 모바일 `.quick`.

## 색 규칙
로고 빨강은 로고 · 채움 버튼만. 조명 호박색은 어두운 바탕(푸터)에서만. 체크무늬는 `.check` 띠 2곳만.

## 링크
- 길찾기 `map.naver.com/p/entry/place/2011364242` · 전화 `0507-1311-8124` · 인스타 `@contty.ch.2f`(네이버엔 @contty_changwon · 확인 필요)

## 그리드
모든 그리드 칸 `minmax(0, …)`(LESSONS §27).

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 세 서브셋 모두 다시.
