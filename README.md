# Store Submission Assets

Play Store와 App Store 제출에 필요한 공개 문서와 메타데이터를 관리하는 디렉토리입니다.

## Files

- `privacy-policy.html`: 스토어에 제출할 수 있는 공개 개인정보처리방침 HTML
- `privacy-policy.md`: 같은 내용의 Markdown 원본
- `privacy-policy-en.html`, `privacy-policy-en.md`: English privacy policy
- `privacy-policy-zh-Hans.html`, `privacy-policy-zh-Hans.md`: 简体中文 privacy policy
- `privacy-policy-ja.html`, `privacy-policy-ja.md`: 日本語 privacy policy

## Publishing

GitHub Pages를 사용할 경우 이 디렉토리의 `privacy-policy.html`을 공개 페이지로 배포하고,
Play Console 및 App Store Connect의 개인정보처리방침 URL에 배포된 HTTPS 주소를 입력합니다.

예상 URL 형식:

```text
https://<github-username>.github.io/<repository-name>/store/privacy-policy.html
```

현재 루트 경로 호환용 리다이렉트 파일도 함께 제공합니다.

```text
https://cslovexp.github.io/margin-mate/privacy-policy.html
https://cslovexp.github.io/margin-mate/privacy-policy-en.html
https://cslovexp.github.io/margin-mate/privacy-policy-zh-Hans.html
https://cslovexp.github.io/margin-mate/privacy-policy-ja.html
```

## Before Release

- 개인정보 문의 이메일은 `cslovexp@gmail.com`으로 설정되어 있습니다.
- 앱에 광고, 분석, 로그인, 클라우드 동기화, 결제 기능을 추가하면 개인정보처리방침도 함께 업데이트하세요.
