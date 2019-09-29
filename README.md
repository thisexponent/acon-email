# ACON3D 이메일 템플릿

### 설치
Foundation 도큐먼트 참고
<https://foundation.zurb.com/emails/docs/sass-guide.html>

### src 설명

`src/pages` 페이지 별로 만드는 곳

`src/partials` 중복적으로 사용되는 블록 (footer, header 등) 만드는 곳

`src/layouts` 위 두가지를 여기에서 가져와 씀

`src/helper` 사용하지 않았습니다

`src/data` json, yml로 passing 가능 사용하지 않았습니다

### 사용법
클론 후에 npm install 해주세요

dist 생성: `npm start`

dist 생성 + 스타일 인라인으로: `npm run build`