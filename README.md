# HTML-Table

<!DOCTYPE html>
<html>

<body>

	<table>
		<tr>
			<th>Book Name</th>
			<th>Author Name</th>
			<th>Genre</th>
		</tr>
		<tr>
			<td>The Book Thief</td>
			<td>Markus Zusak</td>
			<td>Historical Fiction</td>
		</tr>
		<tr>
			<td>The Cruel Prince</td>
			<td>Holly Black</td>
			<td>Fantasy</td>
		</tr>
		<tr>
			<td>The Silent Patient</td>
			<td> Alex Michaelides</td>
			<td>Psychological Fiction</td>
		</tr>
	</table>

</body>

</html>

Defining Tables in HTML

<!DOCTYPE html>
<html>

<body>

<tr>
	<th>Firstname</th>
	<th>Lastname</th>
	<th>Age</th>
</tr>
<tr>
	<td>Priya</td>
	<td>Sharma</td>
	<td>24</td>
</tr>
<tr>
	<td>Arun</td>
	<td>Singh</td>
	<td>32</td>
</tr>
<tr>
	<td>Sam</td>
	<td>Watson</td>
	<td>41</td>
</tr>
</table>

</body>

</html>

## Adding a border to a HTML Table: ##
<!DOCTYPE html>
<html>

<head>
<style>
	table,
	th,
	td {
	border: 1px solid black;
	}
</style>
</head>

<body>
<table style="width:100%">
	<tr>
	<th>Firstname</th>
	<th>Lastname</th>
	<th>Age</th>
	</tr>
	<tr>
	<td>Priya</td>
	<td>Sharma</td>
	<td>24</td>
	</tr>
	<tr>
	<td>Arun</td>
	<td>Singh</td>
	<td>32</td>
	</tr>
	<tr>
	<td>Sam</td>
	<td>Watson</td>
	<td>41</td>
	</tr>
</table>
</body>

</html>

## Adding Collapsed Borders in a HTML Table: ##

<!DOCTYPE html>
<html>

<head>
<style>
	table,
	th,
	td {
	border: 1px solid black;
	border-collapse: collapse;
	}
</style>
</head>

<body>

<table style="width:100%">
	<tr>
	<th>Firstname</th>
	<th>Lastname</th>
	<th>Age</th>
	</tr>
	<tr>
	<td>Priya</td>
	<td>Sharma</td>
	<td>24</td>
	</tr>
	<tr>
	<td>Arun</td>
	<td>Singh</td>
	<td>32</td>
	</tr>
	<tr>
	<td>Sam</td>
	<td>Watson</td>
	<td>41</td>
	</tr>
</table>
</body>

</html>

## Adding Cell Padding in a HTML Table: ##
<!DOCTYPE html>
<html>

<head>
<style>
	table,
	th,
	td {
	border: 1px solid black;
	border-collapse: collapse;
	}

	th,
	td {
	padding: 20px;
	}
</style>
</head>

<body>

<table style="width:100%">
	<tr>
	<th>Firstname</th>
	<th>Lastname</th>
	<th>Age</th>
	</tr>
	<tr>
	<td>Priya</td>
	<td>Sharma</td>
	<td>24</td>
	</tr>
	<tr>
	<td>Arun</td>
	<td>Singh</td>
	<td>32</td>
	</tr>
	<tr>
	<td>Sam</td>
	<td>Watson</td>
	<td>41</td>
	</tr>
</table>
</body>

</html>

## Adding Left Align Headings in a HTML Table : ##
<html>

<head>
<style>
	table,
	th,
	td {
	border: 1px solid black;
	border-collapse: collapse;
	}

	th,
	td {
	padding: 20px;
	}

	th {
	text-align: left;
	}
</style>
</head>

<body>

<table style="width:100%">
	<tr>
	<th>Firstname</th>
	<th>Lastname</th>
	<th>Age</th>
	</tr>
	<tr>
	<td>Priya</td>
	<td>Sharma</td>
	<td>24</td>
	</tr>
	<tr>
	<td>Arun</td>
	<td>Singh</td>
	<td>32</td>
	</tr>
	<tr>
	<td>Sam</td>
	<td>Watson</td>
	<td>41</td>
	</tr>
</table>
</body>

</html>

## Adding Border Spacing in a HTML Table: ##
<html>

<head>
<style>
	table,
	th,
	td {
	border: 1px solid black;
	}

	table {
	border-spacing: 5px;
	}
</style>
</head>

<body>

<table style="width:100%">
	<tr>
	<th>Firstname</th>
	<th>Lastname</th>
	<th>Age</th>
	</tr>
	<tr>
	<td>Priya</td>
	<td>Sharma</td>
	<td>24</td>
	</tr>
	<tr>
	<td>Arun</td>
	<td>Singh</td>
	<td>32</td>
	</tr>
	<tr>
	<td>Sam</td>
	<td>Watson</td>
	<td>41</td>
	</tr>
</table>
</body>

</html>

## Adding Cells that Span Many Columns in HTMl Tables : ## 

<!DOCTYPE html>
<html>

<head>
<style>
	table,
	th,
	td {
	border: 1px solid black;
	border-collapse: collapse;
	}

	th,
	td {
	padding: 5px;
	text-align: left;
	}
</style>
</head>

<body>

<h2>Cell that spans two columns:</h2>
<table style="width:100%">
	<tr>
	<th>Name</th>
	<th colspan="2">Telephone</th>
	</tr>
	<tr>
	<td>Vikas Rawat</td>
	<td>9125577854</td>
	<td>8565557785</td>
	</tr>
</table>
</body>

</html>
## Adding Cells that Span Many Rows in HTML Tables: ##
<!DOCTYPE html>
<html>

<head>
<style>
	table,
	th,
	td {
	border: 1px solid black;
	border-collapse: collapse;
	}

	th,
	td {
	padding: 5px;
	text-align: left;
	}
</style>
</head>

<body>

<h2>Cell that spans two rows:</h2>
<table style="width:100%">
	<tr>
	<th>Name:</th>
	<td>Vikas Rawat</td>
	</tr>
	<tr>
	<th rowspan="2">Telephone:</th>
	<td>9125577854</td>
	</tr>
	<tr>
	<td>8565557785</td>
	</tr>
</table>
</body>

</html>

## Adding a Caption in a HTML Table: ##
<html>

<head>
<style>
	table,
	th,
	td {
	border: 1px solid black;
	border-collapse: collapse;
	}

	th,
	td {
	padding: 20px;
	}

	th {
	text-align: left;
	}
</style>
</head>

<body>

<table style="width:100%">
	<caption>DETAILS</caption>
	<tr>
	<th>Firstname</th>
	<th>Lastname</th>
	<th>Age</th>
	</tr>
	<tr>
	<td>Priya</td>
	<td>Sharma</td>
	<td>24</td>
	</tr>
	<tr>
	<td>Arun</td>
	<td>Singh</td>
	<td>32</td>
	</tr>
	<tr>
	<td>Sam</td>
	<td>Watson</td>
	<td>41</td>
	</tr>
</table>
</body>

</html>

## Adding a Background Colour To a Table in HTML: ##
<!DOCTYPE html>
<html>

<head>
<style>
	table,
	th,
	td {
	border: 1px solid black;
	border-collapse: collapse;
	}

	th,
	td {
	padding: 5px;
	text-align: left;
	}

	table#t01 {
	width: 100%;
	background-color: #f2f2d1;
	}
</style>
</head>

<body>

<table style="width:100%">
	<tr>
	<th>Firstname</th>
	<th>Lastname</th>
	<th>Age</th>
	</tr>
	<tr>
	<td>Priya</td>
	<td>Sharma</td>
	<td>24</td>
	</tr>
	<tr>
	<td>Arun</td>
	<td>Singh</td>
	<td>32</td>
	</tr>
	<tr>
	<td>Sam</td>
	<td>Watson</td>
	<td>41</td>
	</tr>
</table>

<br />
<br />

<table id="t01">
	<tr>
	<th>Firstname</th>
	<th>Lastname</th>
	<th>Age</th>
	</tr>
	<tr>
	<td>Priya</td>
	<td>Sharma</td>
	<td>24</td>
	</tr>
	<tr>
	<td>Arun</td>
	<td>Singh</td>
	<td>32</td>
	</tr>
	<tr>
	<td>Sam</td>
	<td>Watson</td>
	<td>41</td>

	</tr>
</table>
</body>

</html>

## Creating Nested Tables in HTML: ##
<!DOCTYPE html>
<html>

<body>
<table border=5 bordercolor=black>
	<tr>
	<td>
		Fisrt Column of Outer Table
	</td>

	<td>
		<table border=5 bordercolor=grey>
		<tr>
			<td>
			First row of Inner Table
			</td>
		</tr>
		<tr>
			<td>
			Second row of Inner Table
			</td>
		</tr>
		</table>
	</td>
	</tr>
</table>
</body>

</html>

