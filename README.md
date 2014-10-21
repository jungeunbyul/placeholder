* placeholder 기능

placeholder의 섬세한 디자인 적용이 불가능한 단점을 보완하고자 label을 이용한 제이쿼리 구현


* 사용 방법

- 원리 : 

.placeHolder(input)박스에 포커스 또는 클릭했을 때
.placeHolder 이전에 위치하는 요소를 .hide()시킨다.

.placeHolder(input)박스에 포커스가 out 되었을 때
.placeHolder(input)의 value값이 없을 때 이전에 위치하는 요소를 .show()시키고,
.placeHolder(input)의 value값이 있을 때 이전에 위치하는 요소를 .hide()시킨다.


