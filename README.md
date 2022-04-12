# Lab 5 Web
<hr>
Nama    : Maulana Muhamad <br>

NIM     : 312010188 <br>

Kelas   : TI.20. A.1 <br>
<hr>

## Langkah-langkah Praktikum
### 1.Persiapan membuat dokumen HTML dengan nama file lab5_javascript.html seperti berikut.

![Menambahkan_Paragraf](pict/ss1.png) 
Gambar di atas adalah hasil codingan yang dibawah.

### Dibawah ini Adalah Codingan Dari Gambar Diatas:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mengenal Javascript</title>
</head>
<body>
    <h1>Pengenalan Javascript</h1>
    <h3>Contoh documen.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```
<hr>

### 2.Pemakaian alert sebagai operasi window
![Menambahkan_Paragraf](pict/ss2.png) 
Gambar di atas adalah hasil codingan yang dibawah yang telah ditambahkan Pemakaian alert sebagai property window dan akan muncul di atas halaman.

### Dibawah ini Adalah Codingan Dari Gambar Diatas:

```html
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>alert box</title>
</head>
<body>
   <script lang="javascript">
       window.alert("ini merupakan pesan untuk anda");
   </script>
</body>
</html>
```
<hr>

### 3.Pemakaian Method Dalam Objek
![Menambahkan_Paragraf](pict/ss3.png) 
Gambar di atas adalah hasil codingan yang dibawah yang Menggunakan Method dalam objek dengan javascript.

### Dibawah ini Adalah Codingan Dari Gambar Diatas:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>skrip javascript</title>
</head>
<body>
    percobaan memakai javascript:<br>
    <script lang="javascript">
        document.write("Selamat mencoba javascript<br>");
        document.write("Semoga sukses!");
    </script>
</body>
</html>
```
<hr>

### 4.Pemakaian Prompt
![Menambahkan_Paragraf](pict/ss4.png) 
![Menambahkan_Paragraf](pict/ss4-.png) 
Gambar di atas adalah hasil codingan yang dibawah yang Menggunakan Prompt pada script.

### Dibawah ini Adalah Codingan Dari Gambar Diatas:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pemasukan data</title>
</head>
<body>
    <script lang="javascript">
        var nama = prompt("siapa nama anda?","masukkan nama anda");
        document.write("hai, "+ nama);
    </script>
</body>
</html>
```
<hr>

### 5.Pembuatan Fungsi Dan Cara Pemanggilannya
![Menambahkan_Paragraf](pict/ss5.png) 
Gambar di atas adalah hasil codingan yang dibawah.

### Dibawah ini Adalah Codingan Dari Gambar Diatas:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program javascript</title>
    <script lang="javascript">
        function pesan(){
            alert ("Memanggil javascript lewat body onload")
        }
    </script>
</head>
<body onload=pesan()>
    
</body>
</html>
```
<hr>

## Dasar Pemrograman di Javascript

### 6.Operasi Dasar Aritmatika
![Menambahkan_Paragraf](pict/ss6.png) 
Gambar di atas adalah hasil codingan yang dibawah Operasi Dasar Artimatika dalam javascript.

### Dibawah ini Adalah Codingan Dari Gambar Diatas:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program Javascript</title>
    <script lang="javascript">
        function test (val1,val2)
        {
            document.write("<br>"+"perkalian : val1*val2 "+"<br>")
            document.write(val1*val2)
            document.write("<br>"+"pembagian : val1/val2 "+"<br>")
            document.write(val1/val2)
            document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
            document.write(val1+val2)
            document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
            document.write(val1-val2)
            document.write("<br>"+"modulus : val1%val2 "+"<br>")
            document.write(val1%val2)
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
</body>
</html>
```

<hr>

### 7.Seleksi Kondisi (If/else)
![Menambahkan_Paragraf](pict/ss7.png) 
![Menambahkan_Paragraf](pict/ss7-.png) 
Gambar di atas adalah hasil codingan yang dibawah yang menggunakan program seleksi bersyarat dari if else dimana jika nilainya lebih dari 60 berarti lulus dan jika dibawah 60 berarti tidak lulus, sedangkan saya memberikan nilai 98 yang berarti hasilnya adalah lulus.

### Dibawah ini Adalah Codingan Dari Gambar Diatas:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh if-else</title>
</head>
<body>
    <script lang="javascript">
        var nilai = prompt("nilai (0-100): ", 0);
        var hasil = "";
        if (nilai >=60)
        hasil = "lulus";
        else
        hasil = "tidak lulus";
        document.write("hasil: " + hasil);
    </script>
</body>
</html>
```

<hr>

### 8.Penggunaan Operator switch untuk seleksi kondisi
![Menambahkan_Paragraf](pict/ss8.png) 
![Menambahkan_Paragraf](pict/ss8-.png) 
Gambar di atas adalah hasil codingan yang dibawah, Membuat form input dengan function javascript dan pengondisian if/else seperti gambar di atas saya memilih angka 3 maka akan menjadi bilangan ganjil. Kegunaan operator switch untuk pemilihan kondisi, disini saya menulis program switch case sebagai pemilihan kondisi dengan memasukkan angka 3 sebagai angka pilihan maka outputnya akan keluar argumen bilanagan lainya.

### Dibawah ini Adalah Codingan Dari Gambar Diatas:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program Javascript</title>
    <script lang="javascript">
        function test ()
        {
            val1=window.prompt("input nilai (1-5):")
            switch (val1)
            {
                case "1" :
                    document.write("bilangan satu")
                    break
                case "2" :
                    document.write("bilangan dua")
                    break
                case "3" :
                    document.write("bilangan tiga")
                    break
                case "4" :
                    document.write("bilangan empat")
                    break
                case "5" :
                    document.write("bilangan lima")
                    break 
                default  :
                    document.write("bilangan lainnya")
            }
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick=test()>
</body>
</html>
```

<hr>

### 9.Form Input
![Menambahkan_Paragraf](pict/ss9.png) 
Gambar di atas adalah hasil codingan yang dibawah, Membuat form input dengan function javascript dan pengondisian if/else saya memilih angka 23 maka akan menjadi bilangan ganjil.

### Dibawah ini Adalah Codingan Dari Gambar Diatas:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form input</title>
    <script lang="javascript">
        function test () {
            var val1=document.kirim.T1.value
            if (val1%2==0)
                document.kirim.T2.value="bilangan genap"
            else
                document.kirim.T2.value="bilangan ganjil"
        }
    </script>
</head>
<body>
    <form action="" method="post" name="kirim">
        <p>BIL <input type="text" name="T1" id="T1" size="20"> MERUPAKAN BIL <input type="text" name="T2" id="T2" size="20"></p>
        <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
    </form>
</body>
</html>
```

<hr>

### 10.Form Button
![Menambahkan_Paragraf](pict/ss10.png) 
Gambar di atas adalah hasil codingan yang dibawah yang telah menggunakan form button dengan function javascript dan html form button hasil nya adalah seperti contoh gambar di atas, saya memilih Latar Belakang Hijau dan teks kuning.

### Dibawah ini Adalah Codingan Dari Gambar Diatas:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Objek Document</title>
</head>
<body>
    <script lang="javascript">
        function ubahWarnaLB(warna) {
            document.bgColor = warna;
        }
        function ubahWarnaLD(warna) {
            document.fgColor = warna;
        }
    </script>
    <h1>Tes</h1>
    <form action="">
        <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('GREEN')">
        <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('WHITE')">
        <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('YELLOW')">
        <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')">
    </form>
    <script lang="javascript">
        document.write("Dimodifikasi terakhir pada " + document.lastModified);
    </script>
</body>
</html>
```

<hr>

## HTML DOM
### 11.Pilihan menggunakan checkBox dengan perhitungan otomatis
![Menambahkan_Paragraf](pict/ss11.png) 
Gambar di atas adalah hasil codingan yang dibawah yang menggunakan HTML DOM dengan input type checkbox sebagai contoh codingan di atas menghitung secara otomatis.

### Dibawah ini Adalah Codingan Dari Gambar Diatas:

```html
<!DOCTYPE html>
<!-- file daftar menu.html -->
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Daftar Menu</title>
  <script lang="javascript">
      function hitung(ele) {
          var total = document.getElementById('total').value;
              total = (total ? parseInt(total) : 0);
          var harga = 0;
          if (ele.checked) {
              harga = ele.value;
              total += parseInt(harga);
          } else {
              harga = ele.value;
              if (total > 0)
                  total -= parseInt(harga);
          }
          document.getElementById('total').value = total;
      }
  </script>
</head>
<body>
  <h1>Daftar Menu Makanan</h1>
  <label><input type="checkbox" value="5000" name="menu1" id="menu1" onclick="hitung(this);">Ayam Goreng Rp. 5.000</label><br>
  <label><input type="checkbox" value="500" name="menu2" id="menu2" onclick="hitung(this);">Tempe Goreng Rp. 500</label><br>
  <label><input type="checkbox" value="2500" name="menu3" id="menu3" onclick="hitung(this);">Telur Dadar Rp. 2.500</label><br>
  <label><input type="checkbox" value="4000" name="menu4" id="menu4" onclick="hitung(this);">Es Teh Manis Rp. 4.000</label><hr>
  <strong>Total Bayar: Rp. <input type="text" name="total" id="total"></strong>
</body>
</html>
```

<hr>

## PERTANYAAN DAN TUGAS
### 1.Buat script untuk melakukan validasi pada isian form.
![Menambahkan_Paragraf](pict/ss12.png) 
Gambar di atas adalah hasil codingan yang dibawah, Ini adalah contoh pembuatan form validasi menggunakan script atau javascript, ada beberapa syarat, jika data tidak diisi dengan lengkap maka akan ada prompt isikan alamat lengkap anda karena harus diisi dengan lengkap seperti contoh gambar di atas. 

### Dibawah ini Adalah Codingan Dari Gambar Diatas:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Form Validasi</title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <script type="text/javascript">
        function validasiForm() {
            var nama = document.getElementById("nama").value;
            var email = document.getElementById("email").value;
            var alamat = document.getElementById("alamat").value;
            if (nama != "" && email != "" && alamat != "") {
                return true;
            } else {
                alert('Isi Alamat Anda dengan lengkap !');
                return false;
            }
        }
    </script>
</head>
<body>
     <div class="login">
        <h2>VALIDASI DATA ANDA</h2>
        <form action="#" method="POST" onSubmit="return validasiForm()">
            <div>
                <label>Nama Lengkap:</label>
                <input type="text" name="nama" id="nama" />
            </div>
            <div>
                <label>Email:</label>
                <input type="email" name="email" id="email" />
            </div>
            <div>
                <label>Alamat:</label>
                <textarea cols="40" rows="5" name="alamat" id="alamat"></textarea>
            </div>
            <div>
                <input type="submit" value="Daftar" class="tombol">
            </div>
        </form>
    </div>
</body>
</html>
```

style css <br>

```CSS
body {
    background: #AEE2E0;
    font-family: sans-serif;
    padding: 100px;
  }
  
  h2{
      text-align: center;
      font-size: 35px;
      color: #555;
  }
  .login {
    padding: 1em;
    margin: 2em auto;
    width: 30em;
    background: #fff;
    border-radius: 3px;
  }
  
  label {
    font-size: 10pt;
    color: #555;
  } 
  
  input[type="text"],
  input[type="email"],
  textarea {
    padding: 8px;
    width: 95%;
    background: #efefef;
    border: 0;
    font-size: 10pt;
    margin: 6px 0px; 
  }
   
  .tombol {
    background: #2cb82c;
    color: #fff;
    border: 0;
    padding: 5px 8px;
  } 
   .tombol:hover{
      background-color: #555;
  }
```

## Selesai