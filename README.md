<!DOCTYPE HTML>
<html>
	<head>
		<style type="text/css">
			div {
				color: red;
				    padding: 10px;
				    border: 2px solid blue;
				    margin: 25px;
			}
		</style>
	</head>
	<body>
		<a href="http://www.google.com" title="Google title">Link to Google website</a>
		
		<p>
			<label>Enter your name:</label>
			<input type="text" value="Your name here" />
		</p>

		<p>
			<label>Choose your sex:</label>
			<select>
				<option value="male">Male</option>
				<option value="female">Female</option>
			</select>
		</p>

		<p>
			<label>Choose your age-range:</label>
			<input type="radio" name="agee" value="18-25" />18-25
			<input type="radio" name="age" value="26-40" />26-40
			<input type="radio" name="age" value="41-60" />41-60
			<input type="radio" name="age" value="60-160" />60-160
		</p>

		<p>
			<label>Choose your contact preferences:</label>
			<input type="checkbox" name="preference" value="email" />email
			<input type="checkbox" name="preference" value="sms" />sms
			<input type="checkbox" name="preference" value="facebook message" /> facebook message
		</p>

		<div>
			Some text here - to show margins an paddings and borders
		</div>
		<span>some more text here</span>


	</body> 
</html>
