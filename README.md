Html
<!DOCTYPE html>
<html>
<head>
	<title>Search Results</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<header>
		<h1>Search Results</h1>
	</header>
	<main>
		<form>
			<label for="search">Search:</label>
			<input type="text" id="search" name="search">
			<button type="submit">Submit</button>
		</form>
		<table>
			<thead>
				<tr>
					<th>Title</th>
					<th>Description</th>
					<th>Link</th>
				</tr>
			</thead>
			<tbody>
				<!-- Results will go here -->
			</tbody>
		</table>
	</main>
</body>
</html>



Css 
/* Reset default styles */
* {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
}

/* Style the header */
header {
	background-color: #333;
	color: #fff;
	padding: 20px;
}

/* Style the form */
form {
	margin-top: 20px;
}

label {
	display: block;
	margin-bottom: 5px;
}

