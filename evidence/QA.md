# 검증 기록

기준일: 2026-09-13 | 자동검사 34개 PASS

Excel은 artifact_tool로 생성했으며 모든 수량/포장/금액 계산을 셀 수식으로 기록했다. 기본 구성 121행의 계산값을 독립 JSON 계산과 전수 대조했고, 조향 옵션을 켰을 때 퓨즈/홀더가 각각11개가 되는지 확인한 뒤 기본값OFF로 복구했다.

PDF는 A3 가로20페이지, 구매/출처 클릭 링크58개다. 전체 페이지를 이미지로 렌더링해 검토했고 주요 표는 확대 확인했다. 모든 텍스트가 페이지 안전 여백 안에 있으며 전121개 BOM ID가 문서에 존재한다.

쇼핑몰 페이지 표시 재고는 실시간 예약이 아니다. 국내 배송/재고 근거와 별도로 실제 주문 가능·당일출고·판매자 동봉품 확인은 수행하지 않았다. 15행의 실제 수량/길이 미정은 해소되지 않았다. 판매 링크의 유무는 전장/기구 승인과 별개다.

원본 46개 Ref의 GitHub 스냅샷과 대응 정보는 data/source-reference-audit.csv, 원본 바이트의 Git blob SHA-1은 evidence/repository-manifest.json에서 확인한다.

## 자동 검사

- PASS: Unique master IDs
- PASS: 46 source references mapped once
- PASS: Every source mapping refers to master
- PASS: Unknown quantities remain null
- PASS: No missing linked product records
- PASS: No overseas procurement domains
- PASS: Only product URLs, no search/category links
- PASS: Valid nonnegative quantity inputs
- PASS: No shortage for all active numerically defined rows
- PASS: ToF integrated2 spare1 delivery3
- PASS: UWB bases2 usertag1
- PASS: Full fuse count11
- PASS: Full holder count11
- PASS: Base fuse count8
- PASS: Base holder count8
- PASS: Logic internal/external wires
- PASS: Original breadboard equation84
- PASS: 1k resistor10pack
- PASS: M-F80 from two40packs
- PASS: Zero installation with40spares retained
- PASS: Partial quoted sum
- PASS: Workbook8 sheets
- PASS: No exported formula error cells
- PASS: No unsupported HYPERLINK output
- PASS: Procurement calculations exported as formulas
- PASS: Cached summary price334530
- PASS: Steering defaultOFF
- PASS: PDF20pages
- PASS: All master IDs present in PDF
- PASS: PDF clickable source/purchase links
- PASS: PDF text within page safety margins
- PASS: All master IDs in Markdown
- PASS: All16 purchase URLs in MD
- PASS: No font files distributed
