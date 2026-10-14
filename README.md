# PADwiki 인물 문서

Figma 데스크톱(1440px) 및 모바일(390px) 디자인을 기준으로 작성한 정적 HTML/CSS/Vanilla JavaScript 구현입니다.

## 실행
index.html을 브라우저에서 열면 됩니다. 별도 빌드나 패키지 설치는 필요하지 않습니다. 인터넷 연결 시 Noto Sans KR 웹폰트를 사용하고, 연결이 불가능하면 시스템 한글 글꼴로 대체합니다.

## 파일
- index.html: 문서 구조와 콘텐츠
- css/style.css: 데스크톱 스타일
- css/responsive.css: 태블릿·모바일 스타일
- js/main.js: 별도 프로필 데이터 객체, 표 렌더링 및 메뉴·접기 동작
- assets/images/pori-profile.png: Figma 원본 프로필 사진
- assets/icons/: Figma 원본 SVG 아이콘

검색과 문서 기능 메뉴는 백엔드가 연결되지 않은 UI이며, 모바일 패널과 목차 앵커, 문서 접기는 동작합니다.
