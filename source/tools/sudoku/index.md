---
layout: false
---
{% raw %}

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width,user-scalable=no" />
	<title>Sudoku</title>
	<link rel="shortcut icon" href="https://cdn.jsdelivr.net/gh/novaELLIAS/CDN_for_ND/suduku/icon.png">
	<link rel="Stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/novaELLIAS/CDN_for_ND/sudoku/sudoku.css" />
</head>
<body>
	<div class = "btn-group">
		<button onclick = "sd.checkRes();">SUBMIT</button>
		<button onclick = "sd.reset();">RESET</button>
		<button onclick = "sd.again();">RETRY</button>
	</div>
	<script src="https://cdn.jsdelivr.net/gh/novaELLIAS/CDN_for_ND/js/jquery1.8.1.min.js"></script>
	<script src="https://cdn.jsdelivr.net/gh/novaELLIAS/CDN_for_ND/sudoku/sudoku.js"></script>
	<script>
		var sd = new SD;
		sd.init(30);
	</script>
</body>
</html>


{% endraw %}