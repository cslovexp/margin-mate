# App Store In-App Purchase Test

## Product

- Product ID: `margin_mate_pro_lifetime_v2`
- Type: 비소모성
- Display Name: Pro 평생 이용권
- Description: PDF 보고서, CSV 내보내기, 월 손익 분석 기능을 한 번의 결제로 사용할 수 있습니다.

## Simulator Test

Xcode에서 `Runner` scheme을 실행하면 `ios/Runner/MarginMate.storekit` 파일이 연결됩니다.

1. iOS Simulator에서 앱을 실행합니다.
2. Pro 화면으로 이동합니다.
3. 가격이 표시되고 구매 버튼이 활성화되는지 확인합니다.
4. StoreKit 테스트 결제를 완료합니다.
5. PDF 보고서, CSV 내보내기, 월 손익 기능이 열리는지 확인합니다.

## TestFlight Test

1. App Store Connect에서 앱 내 구입 상품 상태를 `제출 준비 완료`로 맞춥니다.
2. `App Store > iOS 앱 1.0.3`의 앱 내 구입 섹션에 상품을 연결합니다.
3. TestFlight 빌드 `1.0.3 (7)` 이상을 설치합니다.
4. Pro 화면에서 실제 상품 가격, 구매, 복원을 확인합니다.
