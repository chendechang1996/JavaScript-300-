# JavaScript-300-
练习
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>修改鼠标形状为手形</title>
</head>
<body style="text-align:center" onload="initMouse()">

<p style="margin:5px auto; width:200px; height:200px; background:gray;">把鼠标移动到该区域</p>

<script type="text/javascript">
	function initMouse() {
		var pDom = document.getElementsByTagName("p")[0];
		// pDom.style.cursor = 'pointer';
		console.log(pDom);
	}


</script>
	
</body>
</html>
