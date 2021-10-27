# flex_practice2

패스트 캠퍼스 font-end 강의 중 flex 속성에 대한 공부

## flex-wrap?

flex items 묶음(줄 바꿈) 여부, 기본 값 nowrap, wrap, wrap-reverse

❗️ 묶음 처리 하지 않으면 줄 바꿈이 되지 않음으로 width 100px height 100px을 준 정사각형을 만들어 브라우저 창을 줄일 시 정사각형이 아닌 찌그러진 사각형을 볼 수 있다.

### nowarp

스크린샷

### wrap 사용

스크린샷

## justify-content

주 축의 정렬 방법, 기본값 flex-start, flex-end, center, space-between, space-around

수평 정렬을 할시 수평 축이 주축

## align-content

교차 축의 여러 줄 정렬 방법, 기본값 stretch, flex-start, flex-end, center, space-between, space-around

align-content라는 속성은 items 가 2줄 이상 그리고 flex wrap, 정렬이 가능한 여백이 있어야 하는 조건이 있다. align-content 보다는 align-items가 더 많이 사용 된다.

### stretch(기본값)

스크린샷

### flex-start

스크린샷

### center

스크린샷

### flex-end

스크린샷

## align-items

교차 축의 한 줄 정렬 방법, 기본값 stretch, flex-start, flex-end, center, baseline

### flex-start

스크린샷

### flex-end

스크린샷

### center

스크린샷
