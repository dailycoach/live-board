# Live Board Basic

강의·코칭·워크숍용 기본형 라이브보드입니다.

## 구조

```text
참여자
→ GitHub Pages / docs/index.html
→ Google Apps Script doPost()
→ Google Spreadsheet / Responses
→ Google Apps Script doGet(action=public)
→ GitHub Pages / docs/live.html
```

## 운영 링크

참여자 입력:

```text
https://dailycoach.github.io/live-board/
```

라이브보드:

```text
https://dailycoach.github.io/live-board/live.html
```

## GitHub Pages 세팅

```text
Settings
→ Pages
→ Deploy from a branch
→ main
→ /docs
```

## 공개 원칙

라이브보드에는 `PublicConsent = 공개 가능`인 응답만 표시합니다.

절대 표시하지 않는 값:

```text
PrivateMemo
UserAgent
```
