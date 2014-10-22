* placeholder 기능
placeholder의 섬세한 디자인 적용이 불가능한 단점을 보완하고자 label을 이용한 제이쿼리 구현

* 사용 방법

원리 : .placeHolder라는 클래스를 가진 input박스에 포커스가 되었을 경우, 포커스가 아웃 되었을 경우의 수를 만듦.

주의 : placeholder기능을 할 label 요소는 반드시 input박스 이전에 위치 시킨다. (input박스 다음에 위치 시켜도 되지만 마크업으로 보았을 때 이전에 위치 시키는게 더 논리적이라 생각됨.)
