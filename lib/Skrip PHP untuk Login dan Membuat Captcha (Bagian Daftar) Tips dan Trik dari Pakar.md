
 
# Skrip PHP untuk Login dan Membuat Captcha (Bagian: Daftar)
 
Captcha adalah sebuah teknik untuk membedakan antara manusia dan robot yang mengisi form pada website. Captcha biasanya berupa gambar atau tulisan yang harus dimasukkan oleh pengguna untuk memvalidasi form. Captcha berguna untuk mencegah spam, serangan brute force, dan aktivitas tidak bertanggung jawab lainnya.
 
Pada tutorial ini, kita akan belajar cara membuat skrip PHP untuk login dan membuat captcha pada bagian daftar. Kita akan menggunakan Bootstrap 4 sebagai framework CSS untuk membuat tampilan form yang responsif dan menarik. Kita juga akan menggunakan session PHP untuk menyimpan dan memeriksa captcha yang dihasilkan secara otomatis.
 
**Download File → [https://kneedacexbrew.blogspot.com/?d=2uJz18](https://kneedacexbrew.blogspot.com/?d=2uJz18)**


 
## Langkah-langkah Membuat Skrip PHP untuk Login dan Membuat Captcha
 
Berikut adalah langkah-langkah yang perlu kita lakukan untuk membuat skrip PHP untuk login dan membuat captcha:
 
1. Buat sebuah folder di localhost dengan nama php-login-captcha.
2. Buat sebuah file dengan nama index.php di dalam folder tersebut. File ini akan berisi form untuk login dan link ke halaman daftar.
3. Buat sebuah file dengan nama daftar.php di dalam folder tersebut. File ini akan berisi form untuk daftar dan captcha yang dihasilkan secara otomatis.
4. Buat sebuah file dengan nama proses\_daftar.php di dalam folder tersebut. File ini akan berisi skrip PHP untuk memproses data dari form daftar dan memeriksa captcha yang dimasukkan oleh pengguna.
5. Buat sebuah file dengan nama koneksi.php di dalam folder tersebut. File ini akan berisi skrip PHP untuk menghubungkan ke database MySQL yang akan kita gunakan untuk menyimpan data pengguna.
6. Buat sebuah database MySQL dengan nama php\_login\_captcha dan buat sebuah tabel dengan nama users yang memiliki kolom id, username, password, dan email.

## Kode Skrip PHP untuk Login dan Membuat Captcha
 
Berikut adalah kode skrip PHP untuk login dan membuat captcha yang bisa kita gunakan:

    <?php
    // file index.php
    session_start(); // mulai session
    if(isset($_SESSION['username'])) // cek apakah sudah login
      header('Location: home.php'); // jika ya, alihkan ke halaman home
      exit;
    
    ?>
    <!DOCTYPE html>
    <html lang="id">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <meta http-equiv="X-UA-Compatible" content="ie=edge">
      <title>Skrip PHP untuk Login dan Membuat Captcha (Bagian: Login)</title>
      <!-- sertakan bootstrap 4 -->
      <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    </head>
    <body>
      <div >
        <div >
          <div >
            <div >
              <div >
                <h3>Login</h3>
              </div>
              <div >
                <form action="proses_login.php" method="post">
                  <div >
                    <label for="username">Username</label>
                    <input type="text"  id="username" name="username" placeholder="Masukkan username" required>
                  </div>
                  <div >
                    <label for="password">Password</label>
                    <input type="password" class=" 8cf37b1e13

    
