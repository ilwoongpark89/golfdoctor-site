# golfdoctor-site

App Store Connect 가 요구하는 **개인정보 처리방침 URL · 지원 URL** 을 위한 정적 페이지.
앱 소스는 별도 비공개 저장소에 있고, 여기에는 법적 페이지 두 장과 업데이트 설정 파일을 둔다.

- `app-version.json` 은 앱이 읽는 업데이트 설정이다. 정본은 앱 저장소의 `web/data/app-version.json` 이다.
- `vercel.json` 도 생성물이다. 설정 파일의 캐시 상한이 여기에 있다.

내용 SoT = 앱 저장소의 `web/data/ui-strings.json` · `ios/StoreListing/metadata.json` · `web/data/app-version.json`.
손으로 고치지 말고 `web/scripts/gen-site.mjs` 로 다시 생성해 배포한다.
