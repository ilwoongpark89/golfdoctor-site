# golfdoctor-site

App Store Connect 가 요구하는 **개인정보 처리방침 URL · 지원 URL** 을 위한 정적 페이지.
앱 소스는 별도 비공개 저장소에 있고, 여기에는 법적 페이지 두 장만 둔다.

내용 SoT = 앱 저장소의 `web/data/ui-strings.json` · `ios/StoreListing/metadata.json`.
손으로 고치지 말고 `web/scripts/gen-site.mjs` 로 다시 생성해 배포한다.
