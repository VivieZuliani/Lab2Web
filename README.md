# Lab2Web

Tugas Modul 1

Nama : Vivie Zuliani Erikasari 

NIM : 312210475 

Kelas : TI.22.A5 

MataKuliah : Pemrograman Web 2 

Dosen Pengampu : Agung Nugroho, S.Kom., M.Kom. 

***
### Tugas
1. Buatlah repository baru dengan nama Lab2Web.
2. Kerjakan semua latihan yang diberikan sesuai urutannya.
3. Screenshot setiap perubahannya.
4. Buatlah file README.md dan tuliskan penjelasan dari setiap langkah praktikum beserta
screenshotnya.
5. Commit hasilnya pada repository masing-masing.
6. Kirim URL repository pada e-learning ecampus
***
#### 1. Membuat Dokumen HTML untuk PHP_Dasar.php
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PHP DASAR</title>
</head>
<body>
    <h1>Belajar PHP Dasar</h1>
    <?php
    echo "Hello World";
    ?>
</body>
<body>
    <h2>Menggunakan Variabel</h2>
    <?php
    $nim = "0411500400";
    $nama = 'Abdullah';
    echo "NIM : ". $nim . "<br>";
    echo "Nama : $nama";
    ?>
</body>
<body>
    <h2>Perdefine Variabel $_GET</h2>
    <h3>tambahin variabel ?nama=Abdullah di url localhost, nempel sama ../.. .php?nama=Abdullah</h3>
    <?php
    echo 'Selamat Datang ' . $_GET['nama'];
    ?>
</body>
</html>
```
**OUTPUTNYA :**

![Screenshot 2024-03-25 221652](https://github.com/VivieZuliani/Lab2Web/assets/130271255/6b9f814e-4bba-4c5e-b803-2fd501fc0ff0)

#### *Note :*

***
#### 2. Membuat Dokumen HTML KE-2 Untuk Form_Input.php
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PHP Dasar</title>
</head>
<body>
    <h2>Form Input</h2>
    <form method="post">
        <label>Nama : </label>
        <input type="text" name="nama">
        <input type="submit" value="Kirim">
    </form>
    <?php
    echo'Selamat Datang ' . $_POST['nama'];
    ?>
</body>
<body>
    <h2>Operator Gaji</h2>
    <?php
    $gaji = 1000000;
    $pajak = 0.1;
    $thp = $gaji - ($gaji*$pajak);
    echo "Gaji sebelum pajak = Rp. $gaji <br>";
    echo "Gaji yang dibawa pulang = Rp. $thp";
    ?>
</body>
<body>
    <h2>Kondisi IF</h2>
    <?php
    $nama_hari =date("1");
    if ($nama_hari == "Sunday"){
        echo "Minggu";
    } elseif ($nama_hari == "Monday"){
        echo "Senin";
    } else {
        echo "Selasa";
    }
    ?>
</body>
<body>
    <h2>Kondisi Switch</h2>
    <?php
    $nama_hari = date("1");
    switch ($nama_hari){ 
        case "Sunday":
            echo "Minggu";
            break;
        case "Monday":
            echo "Senin";
            break;
        case "Tuesday":
            echo "Selasa";
            break;
        default:
        echo "Sabtu";
    }
    ?>
</body>
<body>
    <h2>Perulangan For</h2>
    <?php
    echo "Perulangan 1 sampai 10 <br />";
    for ($i=1; $i<=10; $i++){
        echo "Perulangan ke : " . $i . '<br />';
    }

    echo '<br />';
    echo "Perulangan Menurun dari 10 ke 1 <br />";
    for ($i=10; $i>=1; $i--){
        echo "Perulangan ke : " . $i . '<br />';
    }
    ?>
</body>
<body>
    <h2>Perulangan While</h2>
    <?php
    echo "Perulangan 1 sampai 10 <br />";
    $i=1;
    while ($i<=10) {
        echo "Perulangan ke : " . $i . '<br />';
        $i++;
    }
    ?>
</body>
<body>
    <h2>Perulangan Dowhile</h2>
    <?php
    echo "Perulangan 1 sampai 10 <br />";
    $i=1;
    do {
        echo "Perulangan ke : " . $i . '<br />';
        $i++;
     } while ($i<=10);
    ?>
</body>
</html>
```
**OUTPUTNYA :**



#### *Note :*
***

# SELESAI, TERIMA KASIH


