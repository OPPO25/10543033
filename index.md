<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<body>
	<div id="nav"></div>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
	<script> 
		$("#nav").load("nav.html");
	</script>
	<p> this is page8.</p>
<form method="get" action="">
	<label for="phone">your name:</label><br><br>
    <input type="text" name="id"></<br><br>
    <label for="phone">your password:(8 digits)</label><br><br>
    <input type="password" pattern="[a-zA-Z0-9]{8,}"></<br><br>
    <label for="phone">your phone number</label><br><br>
<input type="tel" id="phone" name="phone" placeholder="0912-123123" pattern="[0-9]{4}-[0-9]{6}"><br><br>
<label for="phone">textarea:</label><br><br>
<textarea style="width:300px;height:100px;"></textarea>
<select name="YourLocation">
　<option value="aaa">科管系</option>
　<option value="bbb">醫管系</option>
　<option value="ccc">行管系</option>
　<option value="ddd">護理系</option>
 <option value="ddd">醫放系</option>
</select><br><br>
<input type="radio" name="location" value="Taipei"> 0-30<br>
<input type="radio" name="location" value="Taoyuan"> 31-60<br>
<input type="radio" name="location" value="Taoyuan">61-100<br>
<input type="checkbox" value="Travel" name="Interest"> I have a bike<br>
<input type="checkbox" value="Movie" name="Interest"> I have a car<br>
<input type="checkbox" value="Food" name="Interest"> I have boat
<input type="submit" value="送出表單">
</form>
	
</body>
</html>
