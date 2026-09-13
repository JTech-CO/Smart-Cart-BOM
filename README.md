# Smart Cart Procurement BOM C1

[구매용 Excel](Smart-Cart-Procurement-BOM.xlsx) | [PDF](Smart-Cart-Procurement-BOM.pdf) | [Markdown](Smart-Cart-Procurement-BOM.md)

Smart-Cart / Smart-Cart-Wiring의 한 대 기준 통합 구매 BOM입니다. 121개 관리 행, 배선도 원본46개 참조번호, 국내 상품 링크16개를 포함합니다. 121행을 실제 부품121개로 읽지 마세요.

기본값은 차동구동, 조향옵션OFF, ToF2개용 멀티플렉서 보완안ON, 준비재료ON, 예비ON, 공구OFF입니다. 보완안은 아직 회로 승인 전입니다. 저장소에 근거가 없는15행의 전선 길이·접속재·체결물 등은 미정으로 남겼으며 0이 아닙니다.

보유/키트동봉 수량은 Excel에서 입력해 중복 구매를 차감하세요. 표시가 소계334,530원은 초기 설정 중 가격이 있는12행만 합친 값이고 완성 카트의 제작비나 결제 견적이 아닙니다. 배송비·미견적·가공비를 포함하지 않습니다.

국내재고/국내배송 근거는 링크 시트에 구분했으며 실제 주문 직전 국내 확보 수량과 출고일을 확인해야 합니다. 해외배송·주문수입·구매자 통관 경로는 구매 링크에 넣지 않았습니다.

- `data/master-bom.json`: 단일 원본 데이터
- `data/bom.csv`: 통합 부품표
- `data/domestic-products.csv`: 국내 구매 링크와 배송 근거
- `data/source-reference-audit.csv`: 원본46개 참조 대응
- `evidence/`: 계산/문서 검증과 스냅샷 해시

저장소 수정, 상품 주문, 판매자 재고 예약 또는 완제품 안전 승인을 수행하지 않았습니다.
