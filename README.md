# sky-gan

스키비디 토일렛 3D 팬게임 (Three.js 단일 HTML, 백엔드 없음).

## 실행
`index.html`을 브라우저에서 열면 바로 실행됩니다. (Three.js r152 인라인 포함)

## 구조
- `index.html` : 빌드가 끝난 최종 단일 파일 (게임 로직 + Three.js 인라인)

## 참고
- 원래는 모듈형 JS 조각(`w1.js`, `m1.js`, `g1.js` 등)을 이어붙여 `template.html`에 인라인하는 방식으로 빌드했으나, 소스 조각은 보존되지 않아 현재는 빌드된 `index.html`을 기준으로 관리합니다.
