# 엑셀 모아보기 — 체험판

흩어진 엑셀(월별 탭·연도별 파일)을 끌어다 놓으면 하나로 모아 조건으로 바로 걸러 보고,
폴더를 한 번 연결해 두면 키워드 하나로 그 안의 모든 엑셀에서 그 줄을 최신순으로 찾는 화면입니다.

- **써 보기**: https://kery27.github.io/excel-jsgg/
- 설치·서버 없이 브라우저 안에서만 동작합니다. 넣은 엑셀은 이 PC 밖으로 나가지 않아요(서버 전송·외부 CDN 없음).
- 파일이 없으면 [가짜 데이터로 체험]을 눌러 보세요.
- 폴더 찾아보기는 크롬·엣지에서만 됩니다(폴더 고르기 기능).

## 내 PC에서 열기

이 저장소를 내려받아(Code → Download ZIP) 압축을 풀고 `index.html`을 크롬으로 열면 인터넷 없이도 동작합니다.
`vendor/` 폴더가 옆에 있어야 해요.

## 쓰는 라이브러리

`vendor/` 안에 그대로 넣어 둠 — [sql.js](https://github.com/sql-js/sql.js)(MIT), [SheetJS Community Edition](https://sheetjs.com)(Apache-2.0). 각 폴더의 `LICENSE` 참고.

문의: [존슨거라지](https://johnsongarage.github.io/#contact)
