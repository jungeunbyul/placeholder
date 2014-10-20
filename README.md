* placeholder 기능



placeholder 자체 기능 단점 - 폰트에 섬세한 디자인 적용 불가

placeholder 단점을 보완하여 input과 label을 이용한 placeholder 기능 구현.



<span><label for="" class="placeTxt">검색어를 입력하세요</label><input type="text" name="" id="" class="placeHolder" /></span>

<script type="text/javascript">
jQuery(function($){
	$(".placeHolder").bind("focusin click",function(){
		$(this).prev().hide();
	});
	$(".placeHolder").bind("focusout",function(){
		if($(this).val()==0){ //val값이 없을 때
			$(this).prev().show();
		}else{
			$(this).prev().hide();
		};
	});
});
</script>


placeTxt와 placeHolder 클래스를 적용 시키고
label다음에 input을 위치 시킨다.


