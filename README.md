# 딜픽 (dealpicks)

쿠팡 골드박스에서 할인율이 큰 상품 30개를 골라 모아둔 모바일 특가 페이지입니다.

- 페이지: https://dealpicks.github.io
- 모든 상품 링크는 쿠팡 파트너스 링크입니다.

> 이 페이지는 쿠팡 파트너스 활동의 일환으로, 이에 따른 일정액의 수수료를 제공받습니다.

## 업데이트 방법

`index.html` 안의 `const DATA = [...]` 배열만 교체하면 됩니다. 각 항목 필드:

| 필드 | 설명 |
|---|---|
| `id` | 쿠팡 상품 ID |
| `code` | 파트너스 단축링크 코드 (`https://link.coupang.com/a/{code}`) |
| `cat` | 카테고리 (식품·생활·주방·뷰티·가전·패션·유아·반려·레저) |
| `name` | 상품명 |
| `sale` / `orig` | 할인가 / 정가 (할인율은 자동 계산) |
| `img` | 쿠팡 썸네일 경로 (`thumbnail.coupangcdn.com/thumbnails/remote/{size}/` 뒤) |
