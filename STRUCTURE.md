# STRUCTURE · contty-sample (v0.2 · 영어 위주 · 깔끔한 뉴욕 빈티지)

```
contty-sample/
├─ index.html                 단일 파일 (CSS·JS 인라인) · lang="en", 한글은 lang="ko" 보조 줄
├─ wrangler.toml              name = contty-sample → contty-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ cn-dmserif.woff2           영문 제목 (DM Serif Display Regular, 라틴 + Latin-1)
├─ cn-dmserif-italic.woff2    영문 이탤릭 포인트 (히어로 time. · 푸터 문장)
├─ cn-franklin.woff2          대문자 라벨 · 내비 · 버튼 · 정보 항목 (Libre Franklin 600 고정)
├─ cn-pretendard.woff2        본문 · 한글 (Pretendard 400–700, 쓰는 글자만)
├─ cn-logo.webp / cn-logo-c.webp   로고 빨강(헤더) · 크림(푸터)
├─ cn-window.webp             히어로 창가
├─ cn-brunch / soup / pasta / risotto / cheesecake / croissant .webp   Brunch
├─ cn-bottles / counter .webp                                         Coffee & Bar
├─ cn-bar / sofa / audio / plants / room .webp                        The Room
├─ cn-sign.webp               Visit 입간판
├─ favicon.png · og-contty.jpg
├─ img/                       다올 제공 원본 34장 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → 체크 띠 → `#brunch` → `#drinks`(띠색) → `#space` → 체크 띠 → `#visit`(띠색) → 푸터(먹) + 모바일 `.quick`.

## 색 규칙
오프화이트 #F7F6F3 · 먹 #1C1B1A. 빨강은 로고 · 채움 버튼 · 대문자 라벨만. 호박색은 어두운 푸터 문장만. 체크무늬(먹 · 밝은 회색)는 `.check` 띠 2곳만.

## 타이포 규칙
영문 제목 = DM Serif(400 고정). 라벨 · 버튼 = Franklin 600 대문자(라틴 전용 → 한글 넣지 말 것). 한글은 `.ko` 줄 · 캡션 span · 안내 small에서 Pretendard.

## 링크
- 길찾기 `map.naver.com/p/entry/place/2011364242` · 전화 `0507-1311-8124` · 인스타 `@contty.ch.2f`(확정 · 네이버의 @contty_changwon은 미사용)

## 그리드
모든 그리드 칸 `minmax(0, …)`(LESSONS §27).

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 서브셋 4종 모두 다시(라틴 3종은 U+0020-007E, U+00A0-00FF, U+2013, U+2018-201D, U+2026, U+2192).
