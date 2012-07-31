cloudzoomgesture
================

A hack of cloudzoom (http://www.professorcloud.com/mainsite/cloud-zoom.htm) to allow gesture controls.

IMPORTANT!
Only works through server - not through file:///

Desktop:
Hover to zoom.

Mobile:
Double tap to zoom.

HTML Structure:
<div>
	<a href='product-template/7804610_904_OB_FNT_LG.jpg' class='cloud-zoom' id='zoom1'
		rel="position: 'inside', showTitle: false">
		<img src="product-template/7804610_904_OB_FNT_MD.jpg" alt='' title="Optional title display" />
	</a>

	<a href='product-template/7804610_904_OB_BCK_LG.jpg' class='cloud-zoom-gallery' title='Thumbnail 1'
		rel="useZoom: 'zoom1', smallImage: 'product-template/7804610_904_OB_BCK_MD.jpg' ">
	<img src="product-template/7804610_904_OB_BCK.jpg" alt = "Thumbnail 1"/></a>
	
	<a href='product-template/7804610_904_OB_FNT_LG.jpg' class='cloud-zoom-gallery' title='Thumbnail 1'
		rel="useZoom: 'zoom1', smallImage: 'product-template/7804610_904_OB_FNT_MD.jpg' ">
	<img src="product-template/7804610_904_OB_FNT.jpg" alt = "Thumbnail 1"/></a>
</div>

CSS dependancy: cloud-zoom.css
<link rel="stylesheet" type="text/css" href="../assets/cloud-zoom.css" >

JavaScript dependancy: jquery, hammer.js, jquery.hammer.js, cloudzoom.js
<script src="../assets/jquery-1.7.2.min.js" type="text/javascript"></script>
<script src="../assets/hammer.js" type="text/javascript"></script>
<script src="../assets/jquery.hammer.js" type="text/javascript"></script>
<script src="../assets/cloudzoom.js" type="text/javascript"></script>