# flex_practice2

패스트 캠퍼스 front-end 강의 중 flex 속성에 대한 공부

## flex-wrap?

flex items 묶음(줄 바꿈) 여부, 기본 값 nowrap, wrap, wrap-reverse

❗️ 묶음 처리 하지 않으면 줄 바꿈이 되지 않음으로 width 100px height 100px을 준 정사각형을 만들어 브라우저 창을 줄일 시 정사각형이 아닌 찌그러진 사각형을 볼 수 있다.

### nowarp

![스크린샷 2021-10-27 오후 3 57 38](https://user-images.githubusercontent.com/88579497/139021239-0fe5d41f-efc1-4523-a534-46c623e4ef82.png)


### wrap 사용

![스크린샷 2021-10-27 오후 3 59 58](https://user-images.githubusercontent.com/88579497/139021256-f65e084d-85da-4cd4-80a3-32ce97d16493.png)
![스크린샷 2021-10-27 오후 4 00 19](https://user-images.githubusercontent.com/88579497/139021327-bf695745-1a32-4934-87ba-78da6afc4093.png)


## justify-content

주 축의 정렬 방법, 기본값 flex-start, flex-end, center, space-between, space-around

수평 정렬을 할시 수평 축이 주축

![스크린샷 2021-10-27 오후 4 08 17](https://user-images.githubusercontent.com/88579497/139021372-0343e26e-ef7c-4fc0-9aa1-62f8766934a1.png)


## align-content

교차 축의 여러 줄 정렬 방법, 기본값 stretch, flex-start, flex-end, center, space-between, space-around

align-content라는 속성은 items 가 2줄 이상 그리고 flex wrap, 정렬이 가능한 여백이 있어야 하는 조건이 있다. align-content 보다는 align-items가 더 많이 사용 된다.

### stretch(기본값)

![스크린샷 2021-10-27 오후 4 15 50](https://user-images.githubusercontent.com/88579497/139021402-0e74b1dc-c727-46d1-9d07-e7b458fcc13d.png)

### flex-start

![스크린샷 2021-10-27 오후 4 16 18](https://user-images.githubusercontent.com/88579497/139021436-6ee6fe20-8c3e-47ed-a93c-9f19e90d1b2b.png)


### center

![스크린샷 2021-10-27 오후 4 16 33](https://user-images.githubusercontent.com/88579497/139021448-709703c6-502f-446c-9336-c7d7ca3e7275.png)

### flex-end

![스크린샷 2021-10-27 오후 4 16 45](https://user-images.githubusercontent.com/88579497/139021470-fd790825-332f-4ced-961e-4f9c2e011486.png)


## align-items

교차 축의 한 줄 정렬 방법, 기본값 stretch, flex-start, flex-end, center, baseline

### flex-start

![스크린샷 2021-10-27 오후 4 25 32](https://user-images.githubusercontent.com/88579497/139021489-f0db5339-3f94-45a7-ae9a-b30a42364521.png)


### flex-end
![스크린샷 2021-10-27 오후 4 25 47](https://user-images.githubusercontent.com/88579497/139021534-47fb398e-d2fc-47e9-9fc9-e3d55cdee1d1.png)


### center
![스크린샷 2021-10-27 오후 4 26 19](https://user-images.githubusercontent.com/88579497/139021555-4e8b3562-623e-43d3-9674-214ac76fd43f.png)

