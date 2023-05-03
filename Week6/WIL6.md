# 6주차 과제 (B811186)

6주차 정리

1. Box model

- 박스의 테두리 -> border
ex) border: 3px solid red

블록 레벨 요소 -> 한줄을 차지하는 박스 (부모 요소 전체 공간 차지)
인라인 레벨 요소 -> 자신만을 감싸는 박스 (부모 요소 전체 공간 차지 X)

- margin/border/padding/content

content <> "여기 부분" </>

padding 충전제 쿠션 content와 border 사이의 간격들
ex) padding: 20px;

border '박스 테두리'

margin 여백(어떤 요소와 어떤 요소 사이의 여백)
ex) margin : 20px; 


- top -> right -> bottom -> left
margin을 적용할 박스와 박스 사이에서 다르게 멀어지고 싶을때
ex) margin: 10px 30px 0px 20px 일 경우
top -> right -> bottom -> left로 적용됨

ex) margin: 10px 30px;
top, bottom -> 10px, right, left -> 30px

여러종류의 border들도 있음
주요 border: none(테두리 없음), solid(일자 테두리)

//개발자 도구 사용법

2. Flex Box Layout = flexible layout
//greed box layout

- 어떤 아이템들의 배열될 방향들을 지정할 수 있다.
ex) flex-box{
    display: flex;  (여기부터 하위 요소는 flex의 적용을 받음)
    flex-direction: row;    (가로로 적용을 받음)
}
main axis : row, cross axis : column

- 주축들의 위치를 설정해주는 법
justify-content: main axis
align-item : cross axis
ex) align-item: center;
// 암기 : 저주콘서트 크로스라인

flexbox 안에 flexbox를 넣어서 활용

---------------------------------------
// 더 공부하면 좋은거
1. css grid layout
2. can i use?

grid layout의 좋은점
위치들을 flexbox layout에 비해서 더욱 더 쉽게 사용할 수 있다.
좀 더 복잡한 웹페이지 위치들을 설정할 때

can i use
css는 브라우저 마다 사용가능한게 다르다.
can i use에서 지원하는 버전들이랑 api들을 확인할 수 있다.

6주차 과제
개구리들이 flex 스타일대로 움직인다
게임으로 해보자