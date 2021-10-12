# HTML-Table

<!DOCTYPE html>
<html>

<body>

	<table>
		<tr>
			<th>Candidate Name</th>
			<th>Designation</th>
			<th>Skill</th>
		</tr>
		<tr>
			<td>Sanjay Singh Rawat</td>
			<td>Senior Software Engineer</td>
			<td>Bigdata</td>
		</tr>
		<tr>
			<td>Sreeram Gorpoade</td>
			<td>Technical Lead</td>
			<td>Golang</td>
		</tr>
		<tr>
			<td>Rashi Agarwal</td>
			<td>Senior Tester</td>
			<td>Selenium</td>
		</tr>
	</table>

</body>
</html>

## Defining Tables in HTML ##

<!DOCTYPE html>
<html>

<body>

<tr>
	<th>Firstname</th>
	<th>Lastname</th>
	<th>Role</th>
</tr>
<tr>
	<td>Priya</td>
	<td>Sharma</td>
	<td>Java Developer</td>
</tr>
<tr>
	<td>Arun</td>
	<td>Singh</td>
	<td>UI designer</td>
</tr>
<tr>
	<td>Sam</td>
	<td>Watson</td>
	<td>FullStack Developer</td>
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
	<th>Role</th>
	</tr>
	<tr>
	<td>Priya</td>
	<td>Sharma</td>
	<td>Java Developer</td>
	</tr>
	<tr>
	<td>Arun</td>
	<td>Singh</td>
	<td>UI Designer</td>
	</tr>
	<tr>
	<td>Sam</td>
	<td>Watson</td>
	<td>FullStack Developer</td>
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
	<th>Role</th>
	</tr>
	<tr>
	<td>Priyanka</td>
	<td>Chaturvedi</td>
	<td>Cloud Engineer</td>
	</tr>
	<tr>
	<td>Arun</td>
	<td>Mondal</td>
	<td>DevOps Engineer</td>
	</tr>
	<tr>
	<td>Samuel</td>
	<td>Watson</td>
	<td>Site Reliability Engineer</td>
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
	<th>Role</th>
	</tr>
	<tr>
	<td>Radhika</td>
	<td>Sharma</td>
	<td>Data Scientist</td>
	</tr>
	<tr>
	<td>Arunachalam</td>
	<td>Parthasarthy</td>
	<td>Data Analyst</td>
	</tr>
	<tr>
	<td>Sameer</td>
	<td>Malhotra</td>
	<td>Data Engineer</td>
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
	<th>Role</th>
	</tr>
	<tr>
	<td>Prabhu</td>
	<td>Sachdeva</td>
	<td>SDET</td>
	</tr>
	<tr>
	<td>Ashish</td>
	<td>Monge</td>
	<td>SDE</td>
	</tr>
	<tr>
	<td>Sanyukta</td>
	<td>Panigrahi</td>
	<td>SDM</td>
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
	<th>Location</th>
	</tr>
	<tr>
	<td>Meenu</td>
	<td>Sharma</td>
	<td>India</td>
	</tr>
	<tr>
	<td>Mark</td>
	<td>Samuel</td>
	<td>Italy</td>
	</tr>
	<tr>
	<td>Sam</td>
	<td>Ahlawat</td>
	<td>Canada</td>
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
	<td>Inderjeet Rawat</td>
	<td>9125408567</td>
	<td>8565000000</td>
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
	<td>Surjeet Singh</td>
	</tr>
	<tr>
	<th rowspan="2">Telephone:</th>
	<td>912557805000</td>
	</tr>
	<tr>
	<td>85655000000</td>
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
	<th>Location</th>
	</tr>
	<tr>
	<td>Hema</td>
	<td>Sharma</td>
	<td>US</td>
	</tr>
	<tr>
	<td>Pradeep</td>
	<td>Bhandari</td>
	<td>Germany</td>
	</tr>
	<tr>
	<td>Thomas</td>
	<td>Falcon</td>
	<td>Israel</td>
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
	<th>Profession</th>
	</tr>
	<tr>
	<td>Thomas</td>
	<td>Lawrence</td>
	<td>Dance Istructor</td>
	</tr>
	<tr>
	<td>Lewis</td>
	<td>Terrance</td>
	<td>Doctor</td>
	</tr>
	<tr>
	<td>Bradley</td>
	<td>Watson</td>
	<td>Scientist</td>
	</tr>
</table>

<br />
<br />

<table id="t01">
	<tr>
	<th>Firstname</th>
	<th>Lastname</th>
	<th>Profession</th>
	</tr>
	<tr>
	<td>Thomas</td>
	<td>Lawrence</td>
	<td>Dance Istructor</td>
	</tr>
	<tr>
	<td>Lewis</td>
	<td>Terrance</td>
	<td>Doctor</td>
	</tr>
	<tr>
	<td>Bradley</td>
	<td>Watson</td>
	<td>Scientist</td>

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


</html>

