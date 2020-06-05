2개의 컴포넌트(.banner와 .events)가 있다.
이때 아래 쪽 컴포넌트(.events)에 다음과 같은 상황을 가정해보자.

하나의 부모 요소에 여러 개의 자식 컴포넌트(.event_div)들이
들어있다.
이때 이 자식 요소들을 수직으로, 일정한 간격으로
정렬하는 방법에 대해 생각해보자.
(flex와 table 방식을 사용하지 않는 가정하에)

● index.html
자식 요소들에 position: relatve 값을 준 상태에서
위쪽(top)에 약간의 유동값을 주었다.

그 다음에 모든 자식 요소들 아래에 margin 값을 부여했다.
position으로 모든 요소들을 옮기지 않은 상태에서
margin값을 넣었다가는 
.banner와 .events 사이에 공간(marign값 만큼)이 생겨버린다.






