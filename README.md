# Lab1Web
# 1. membuat paragraf
```
<!-- Ini adalah paragraf pertama --> 
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi 
Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat 
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar 
HTML.</p> 
<!-- Ini adalah paragraf kedua --> 
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling 
mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan 
tag dasar html.</p>
```
![Screenshot (207)](https://github.com/user-attachments/assets/f0d25448-d4b6-40b0-a443-e79727422009)
![Screenshot (208)](https://github.com/user-attachments/assets/26d80d4d-1fe0-4e42-b7ca-87c7ff0dafaa)


# 2. Menambahkan Judul
```
Seperti sudah dijelaskan pada materi bahwa judul memiliki 6 level yaitu mulai h1 sampai h6. 
Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum 
paragraf kedua.
<!-- judul paragraf pertama --> 
<h1>Belajar Dasar HTML</h1> 
<!-- judul paragraf kedua --> 
<h2>Paragraf pada HTML</h2> 
```

![Screenshot (210)](https://github.com/user-attachments/assets/4a3060a7-ae76-45ee-a74b-e6f7d7b179e7)


# 3. Memformat teks
```
untuk membuat warna dengan menambahkan <font color=yellow>html dasar</font>
dan untuk mempertebal dengan menggunakan tag <b></b>
dan untuk membuat garis dibawah mengunaka tag<U></U>
```

![Screenshot (211)](https://github.com/user-attachments/assets/16f02820-90b5-4b69-b028-40b2e362357a)

# 4. Menyisipkan Gambar 
```
 <img src="logo_perguruanTinggi_1.png" width="200" title="Logo Univeritas Pelita Bangsa">
untuk ngelink ke gambar dan untuk mengatur lebar
```

![Screenshot (212)](https://github.com/user-attachments/assets/9b6cdb1c-d2ac-4db4-9ef5-19e09cf360f7)

# 5. Menambahkan Hyperlink
```
 <nav>
        <a href="lab1_tag_dasar.html">Dasar HTML</a>
        <a href="lab1_halaman2.html">Halaman 2</a>
        <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
untuk membuat navigasi
```
![Screenshot (213)](https://github.com/user-attachments/assets/bc20f1a5-815c-46a4-bbd7-d99fbf8661af)

# 1.Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
```
Ya, jika terjadi kesalahan penulisan tag HTML, kemungkinan besar akan terjadi error yang menyebabkan tampilan tidak sesuai harapan. Browser umumnya tetap mencoba menampilkan halaman meskipun terdapat kesalahan, namun hasilnya bisa berbeda dari yang diinginkan. Misalnya, jika kita menulis <dvi> alih-alih <div>, browser mungkin akan mengabaikan tag tersebut atau menampilkan elemen secara tidak semestinya.
```
# 2.Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!
```
<p> untuk membuat paragraf dan untuk tag <b> untuk pindah baris
```
# 3.Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya! 
```
Perbedaan utama: alt digunakan untuk menjelaskan gambar bagi pengguna yang tidak dapat melihatnya (misalnya, pengguna dengan disabilitas atau ketika gambar gagal dimuat), sementara title memberikan informasi tambahan yang muncul saat gambar disorot.
```
# 4.Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya! 
```
Sebaiknya hanya satu atribut yang diisi (biasanya width), agar gambar tetap proporsional. Jika Anda menetapkan kedua atribut (width dan height), gambar dapat terlihat terdistorsi jika perbandingan aspek gambar tidak sesuai. Jika hanya salah satu yang diisi, browser akan secara otomatis menyesuaikan atribut lainnya untuk menjaga proporsi gambar.
```
# 5.Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
```
_blank: Membuka link di tab atau jendela baru.

Contoh:
html
<a href="https://example.com" target="_blank">Klik di sini</a>
Saat diklik, tautan akan terbuka di tab/jendela baru.

_self: Membuka link di tab atau jendela yang sama (default).
Contoh:
html
<a href="https://example.com" target="_self">Klik di sini</a>
Tautan akan terbuka di tab atau jendela yang sama.

_top: Membuka link di seluruh jendela browser, menghapus frame (jika ada frame).
Contoh:
html
<a href="https://example.com" target="_top">Klik di sini</a>
Berguna jika halaman tersebut ada dalam frame, dan Anda ingin membuka link di seluruh jendela browser, mengabaikan frame.

_parent: Membuka link di frame induk, jika halaman berada di dalam frame.
Contoh:
html
<a href="https://example.com" target="_parent">Klik di sini</a>
Jika halaman berada dalam frame, tautan akan terbuka di frame induk, bukan di frame yang saat ini aktif.
```
