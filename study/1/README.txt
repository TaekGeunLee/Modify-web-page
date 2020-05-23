1.
list-style-image 프로퍼티를 이용해
<li> 아이콘으로 image를 넣어줬다.

다만, image의 크기가 <li>의 크기와
딱 맞지 않으면 모양새가 이쁘게 안나온다.
이에 대해선 image의 크기를 resize할 필요가 있다.
(이 소스에서는 font-size를 기준으로 했다.)

2.
더 쉬운  방법으로
<li>에 background-image 값을 주어
margin 값으로 위치를 조정하는 것이 있다.

3.
display : list-item이 적용된 요소에만
list-style 프로퍼티를 적용할 수 있다.

<div> 태그에 해당 속성을 줘서
list-item을 적용할 수 있다는 뜻일지도.
