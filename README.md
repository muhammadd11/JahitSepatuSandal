<?php
$warga = [
	["Mochammad doni", "23 Juli 1994", 
	"Mochammad111@gmail.com"],
	["andre oktaviansah", "12 Juni 1992", 
	"andreokta@gmail.com"],
	["vellin cleriza", "21 februari 2010", "vellinC@gmail.com"],
	["dimas dwi", "10 maret 2001", "dimasdw@gmail.com"],
	["sahudi", "01 januari 1983", "sahudi@gmail.com"]
];
if ($datapenduduk = true){
echo "mengisikan secara otomatis";
$datapenduduk = true;
}

?>

<!DOCTYPE html>
<html>
<head>
	<title>datapenduduk</title>
</head>
<body>
	<h1> data penduduk </h1>
	<form action="" method="POST">
		
	</form>
<?php foreach ($warga as $x) : ?>
	<ul>
	
	<li> Nama: <?= $x[0]; ?></li>
	<li> Tanggal,lhr: <?= $x[1]; ?></li>
	<li>E-mail <?= $x[2] ?></li>

</ul>
<?php endforeach; ?>
</body>
</html>
