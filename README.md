# cssPractice

display:flex 정리

flexbox에서 무언가를 움직이고 싶다면
flexbox container를 만들어야 한다.
배치하려는 item의 부모는 flex container여야 하며
바로 붙어 있어야만 한다.

flex-direction 의 기본값은 row
row 일 경우 main axis는 가로 cross axis는 세로

부모 컨테이너에 높이를 설정하지 않을 경우
제대로 동작하지 않을 수 있다.

justify-content는 수평축에 있는 item의 위치를 변경
align-item은 수직축에 있는 item의 위치를 변경

flex-direction: column 일 경우
main axis는 세로 cross axis는 가로

align-self 와 order는 item에 직접 설정하여 위치 변경 가능

flex-wrap의 기본값은 nowrap
item들에 지정한 width를 무시하고 같은 줄에 일정한 크기로 정렬한다.
flex-wrap:wrap을 사용할 경우 width를 고려하여 줄을 바꿔 정렬한다.
align-content는 wrap으로 정렬시 사용 가능
nowrap이 강제로 한 줄에 정렬하여 flex line이 한 줄 뿐이기 때문이다.
