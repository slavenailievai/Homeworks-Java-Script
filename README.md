Homeworks-Java-Script
=====================

JavaScript Beginners Course - Homeworks
<!DOCTYPE html>
<html>
	<head>
		<title>Hello world!</title>
		<meta http-equiv="content-type" content="text/html; charset=utf-8">
		
	</head>
	<body>
		<h1 id="myTitle"></h1>
		<script type="text/javascript">
			var greeting = "Hello " + prompt("Please, enter your title(Ms, Mr): ") + " " + prompt("Please, enter your first name: ") + " " + prompt("Please, enter your last name:") + "!";
			alert(greeting);
			document.documentElement.firstChild.firstChild.nextSibling.innerHTML=greeting;
			document.getElementById("myTitle").innerHTML=greeting;
		</script>
	</body>
</html>
