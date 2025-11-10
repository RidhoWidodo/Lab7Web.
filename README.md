# Lab7Web.
**Nama : Muhammad Ridho Hafiedz**

**Nim  : 312410195**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PHP Dasar</title>
</head>
<body>
    <h1>Belajar PHP Dasar</h1>
    <?php
      echo "Hello World";
  ?>
</body>
</html>
```
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/5125dcd2-5ca6-4ed7-b363-c3e02dfc450a" />

```php
<?php
$nim = "0411500400";
$nama = 'Abdullah';
echo "NIM : " . $nim . "<br>";
echo "Nama : $nama";
?>
```
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/d4801e11-bdf4-4ce4-8dcf-684eada2d6cb" />

```PHP
<?php
$nim = "0411500400";
$nama = 'Abdullah';
echo "NIM : " . $nim . "<br>";
echo "Nama : $nama";
?>
```
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/d630d44f-ce44-48c9-b80a-d996e48f57ab" />

```
<?php
echo 'Selamat Datang ' . $_GET['nama'];
?>
```
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/5f75761b-0639-4e73-a863-38a92c15d0e5" />

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PHP Dasar</title>
</head>
<body>
<h2>Form Input</h2>
<form method="post">
    <label>Nama: </label>
    <input type="text" name="nama">
    <input type="submit" value="Kirim">
</form>
<?php
echo 'Selamat Datang ' . $_POST['nama'];
?>
</body>
</html>
```

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/31e665ea-5fa5-435e-be9e-fe1ef1110ef3" />

```php
Operator
<?php
$gaji = 1000000;
$pajak = 0.1;
$thp = $gaji - ($gaji*$pajak);
echo "Gaji sebelum pajak = Rp. $gaji <br>";
echo "Gaji yang dibawa pulang = Rp. $thp";
?>
Kondisi IF
<?php
$nama_hari = date("l");
if ($nama_hari == "Sunday") {
    echo "Minggu";
} elseif ($nama_hari == "Monday") {
    echo "Senin";
} else {
echo "Selasa";
}
?>
Kondisi Switch
<?php
$nama_hari = date("l");
switch ($nama_hari) {
    case "Sunday":
      echo "Minggu";
      break;
    case "Monday":
      echo "Senin";
      break;

Modul Praktikum Pemrograman Web
    case "Tuesday":
      echo "Selasa";
      break;
    default:
      echo "Sabtu";
?>

Perulangan for
<?php
echo "Perulangan 1 sampai 10 <br />";
for ($i=1; $i<=10; $i++) {
    echo "Perulangan ke: " . $i . '<br />';
}
echo "Perulangan Menurun dari 10 ke 1 <br />";
for ($i=10; $i>=1; $i--) {
    echo "Perulangan ke: " . $i . '<br />';
}
?>


Perulangan while
<?php
    echo "Perulangan 1 sampai 10 <br />";
    $i=1;
while ($i<=10) {
echo "Perulangan ke: " . $i . '<br />';
$i++;
}
?>

Perulangan dowhile
<?php
echo "Perulangan 1 sampai 10 <br />";
$i=1;
do {
    echo "Perulangan ke: " . $i . '<br />';
    $i++;
} while ($i<=10);
?>
```
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/20b6afa2-2ce3-4b1c-9b8e-16f5eb0fe9de" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/0f364dc6-745f-40af-a8d2-8c5139d15136" />
