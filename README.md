<html>
<head>
	<title></title>
</head>
<body onload="draw()">
<canvas id="sketch" width="300" height="300">
</canvas>
<script>
function draw() {
	var sketch = document.getElementById('sketch');
	var context = sketch.getContext("2d");
	context.fillRect (30, 30, 50, 50)
}
</script>
</body>
</html>