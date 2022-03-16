# JavaScript is one of the programming languages I am most comfortable with! Here is an example of a JavaScript project I created that displays the infamous "FizzBuzz" challenge 

```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 1; i < 101; i++) {
	if (i % 15 == 0) displayHTML += "<p>" + "FizzBuzz" + "</p>";
	else if (i % 5 == 0)  displayHTML += "<p>" + "Buzz" + "</p>";
	else if (i % 3 == 0)  displayHTML += "<p>" + "Fizz" + "</p>";
		else displayHTML += "<p>" + i + "</p>";
	}
	display.innerHTML = displayHTML
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```

### [Back to homepage](README.md)
