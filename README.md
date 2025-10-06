# Langkah 1: Membuat File lab3_list.HTML
Langkah pertama adalah membuat struktur dasar HTML dengan nama file `lab3_list.HTML`. File ini akan digunakan untuk mempelajari berbagai jenis list dalam HTML. Saya membuat dokumen HTML5 dengan struktur dasar yang mencakup deklarasi DOCTYPE, meta charset UTF-8 untuk mendukung karakter Indonesia, dan viewport untuk responsivitas. Di dalam body, saya menambahkan header dengan judul "Membuat List" yang akan menjadi judul utama halaman.

**Kode:**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

## Penjelasan
Struktur HTML ini menggunakan tag `<!DOCTYPE html>` yang menandakan bahwa dokumen menggunakan HTML5. Tag `<html lang="en">` mendefinisikan bahasa dokumen. Di bagian `<head>`, terdapat meta charset yang mengatur encoding karakter dan meta viewport untuk responsivitas tampilan di berbagai perangkat. Tag `<body>` berisi konten utama halaman dengan header yang menampilkan judul "Membuat List".

# Langkah 2: Membuat Ordered List
Setelah struktur dasar selesai, saya menambahkan Ordered List ke dalam dokumen. Ordered List adalah daftar yang terurut dengan nomor. Saya membuat section dengan id "order-list" yang berisi judul "Ordered List" dan daftar mata kuliah. Tag `<ol>` digunakan untuk membuat ordered list, dan setiap item daftar menggunakan tag `<li>` (list item). Daftar ini akan menampilkan tiga mata kuliah: Pemrograman Web, Sistem Informasi, dan Basis Data 2, yang secara otomatis diberi nomor 1, 2, dan 3.

**Kode:**
```
<section id="order-list">
    <h2>Ordered List</h2>
    <ol>
        <li>Pemrograman Web</li>
        <li>Sistem Informasi</li>
        <li>Basis Data 2</li>
    </ol>
</section>
```
## Penjelasan
Ordered List menggunakan tag `<ol>` sebagai pembungkus dan tag `<li>` untuk setiap item. Secara default, browser akan menampilkan nomor urut 1, 2, 3 di depan setiap item. Ordered List cocok digunakan ketika urutan item memiliki makna penting, seperti langkah-langkah instruksi atau peringkat.

**Hasil Tampilan:**
<img width="1920" height="1080" alt="Screenshot (50)" src="https://github.com/user-attachments/assets/70e0e0d3-cd6b-4a17-bafb-c0d3a777bc07" />

# Langkah 3: Membuat Unordered List
Langkah selanjutnya adalah membuat Unordered List, yaitu daftar yang tidak memiliki urutan khusus. Saya menambahkan section baru dengan id "unorder-list" yang berisi judul "Unordered List". Berbeda dengan ordered list, unordered list menggunakan tag `<ul>` dan saya menambahkan atribut `type="square"` untuk mengubah simbol bullet dari default (lingkaran) menjadi persegi. Daftar ini menampilkan tiga mata kuliah: Jaringan Komputer, Struktur Data, dan Algoritma & Pemrograman.

**Kode:**
```
<section id="unorder-list">
    <h2>Unordered List</h2>
    <ul type="square">
        <li>Jaringan Komputer</li>
        <li>Struktur Data</li>
        <li>Algoritma &amp; Pemrograman</li>
    </ul>
</section>
```
## Penjelasan 
Unordered List menggunakan tag `<ul>` untuk membuat daftar tidak berurutan. Atribut `type="square"` mengubah bullet point menjadi bentuk persegi. Pilihan type lainnya adalah "disc" (lingkaran penuh/default), "circle" (lingkaran kosong), atau "none" (tanpa simbol). Perhatikan penggunaan `&amp;` untuk menampilkan karakter ampersand (&) dengan benar di HTML.

**Hasil Tampilan:**
<img width="1920" height="1080" alt="Screenshot (51)" src="https://github.com/user-attachments/assets/59ad4e90-6b63-4d4d-944b-f3682980dc5c" />

# Langkah 4: Membuat Description List
Description List adalah jenis list yang berbeda, digunakan untuk membuat daftar dengan deskripsi atau penjelasan. Saya membuat section baru yang berisi struktur description list dengan tag `<dl>` sebagai pembungkus utama. Di dalamnya terdapat tag `<dt>` (description term) untuk istilah atau judul, dan tag `<dd>` (description description) untuk penjelasan atau sub-item. Dalam contoh ini, saya membuat dua fakultas (Fakultas Teknik dan Fakultas Ekonomi dan Bisnis) dengan masing-masing program studinya.

**Kode:**
```
<section id="description-list">
    <h2>Description List</h2>
    <dl>
        <dt>Fakultas Teknik</dt>
        <dd>Teknik Industri</dd>
        <dd>Teknik Informatika</dd>
        <dd>Teknik Lingkungan</dd>
        <dt>Fakultas Ekonomi dan Bisnis</dt>
        <dd>Akuntansi</dd>
        <dd>Manajemen</dd>
        <dd>Bisnis Digital</dd>
    </dl>
</section>
```
## Penjelasan:
Description List sangat berguna untuk membuat glossary, daftar istilah, atau struktur data yang memiliki judul dan sub-item. Tag `<dl>` adalah container utama, `<dt>` mendefinisikan term/istilah yang akan dijelaskan, dan `<dd>` berisi deskripsi atau penjelasan dari term tersebut. Satu `<dt>` bisa memiliki beberapa `<dd>` sebagai penjelasannya.

**Hasil Tampilan:**
<img width="1920" height="1080" alt="Screenshot (52)" src="https://github.com/user-attachments/assets/196cc55d-c8f5-4a79-a13d-23d707d522a3" />

# Langkah 5: Membuat File Lab3_Table.HTML
Setelah selesai dengan list, saya membuat file baru bernama `lab3_Table.html` untuk mempelajari pembuatan tabel. Struktur dasar HTML-nya sama dengan file sebelumnya, namun dengan judul header "Membuat Table". File ini akan digunakan untuk memahami cara membuat dan memanipulasi tabel dalam HTML.

**Kode:**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat Table</h1>
    </header>
</body>
</html>
```
## Penjelasan:

File baru ini menggunakan struktur HTML5 yang sama dengan file list sebelumnya. Pemisahan file ini bertujuan untuk memudahkan pemahaman dan organisasi kode, dimana setiap file fokus pada satu topik tertentu.

# Langkah 6: Membuat Tabel Sederhana
Saya membuat tabel sederhana dengan struktur yang terdiri dari header dan body. Tag `<table>` digunakan sebagai container utama dengan atribut `border="1"` untuk membuat garis border, `cellpadding="4"` untuk memberikan jarak antara konten dan border sel, dan `cellspacing="0"` untuk menghilangkan jarak antar sel. Bagian `<thead>` berisi header tabel dengan tag `<th>` untuk judul kolom (No, Fakultas, Program Studi). Bagian `<tbody>` berisi data tabel dengan tag `<tr>` untuk baris dan `<td>` untuk sel data.

**Kode:**
```
<table border="1" cellpadding="4" cellspacing="0">
    <thead>
        <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1.</td>
            <td>Teknik</td>
            <td>Teknik Informatika</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>Teknik</td>
            <td>Teknik Industri</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>Teknik</td>
            <td>Teknik Lingkungan</td>
        </tr>
    </tbody>
</table>
```
## Penjelasan:
Tabel HTML memiliki struktur hierarki. Tag `<table>` adalah container utama. `<thead>` dan `<tbody>` memisahkan bagian header dan body untuk semantic HTML yang lebih baik. `<tr>` (table row) mendefinisikan baris, `<th>` (table header) untuk header kolom yang biasanya tampil tebal dan center, sedangkan `<td>` (table data) untuk sel data biasa. Atribut cellpadding mengatur ruang di dalam sel, cellspacing mengatur jarak antar sel, dan border mengatur ketebalan garis tabel.

**Hasil Tampilan:**
<img width="1920" height="1080" alt="Screenshot (53)" src="https://github.com/user-attachments/assets/a134d7cc-b2c2-456b-bbba-ed28f8276e82" />

# Langkah 7: Menggabungkan Sel dengan Rowspan
Untuk membuat tabel lebih efisien, saya menggunakan atribut `rowspan` untuk menggabungkan sel secara vertikal. Pada contoh ini, kata "Teknik" di kolom Fakultas muncul tiga kali untuk tiga program studi yang berbeda. Dengan `rowspan="3"` pada sel "Teknik" di baris pertama, sel tersebut akan membentang menutupi tiga baris sekaligus. Ini membuat tabel lebih rapi dan mudah dibaca karena tidak ada pengulangan data yang tidak perlu.

**Kode:**
```
<table border="1" cellpadding="6" cellspacing="0">
    <thead>
        <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1.</td>
            <td rowspan="3">Teknik</td>
            <td>Teknik Informatika</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>Teknik Industri</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>Teknik Lingkungan</td>
        </tr>
    </tbody>
</table>
```
##  Penjelasan:
Atribut `rowspan` menggabungkan sel secara vertikal (ke bawah). `Nilai rowspan="3"` berarti sel tersebut akan membentang menutupi 3 baris. Perhatikan bahwa pada baris ke-2 dan ke-3, tidak ada tag `<td>` untuk kolom Fakultas karena sudah digantikan oleh sel yang menggunakan rowspan di baris pertama. Ini membuat struktur data lebih jelas dan menghindari redundansi.

**Hasil Tampilan:**
<img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/8a4d66c5-66cc-4234-922e-bca60956f4d1" />

# Langkah 8: Membuat File lab3_form.html
Langkah selanjutnya adalah membuat file baru bernama `lab3_form.html` untuk mempelajari pembuatan form HTML. Form adalah elemen penting dalam web development karena digunakan untuk mengumpulkan input dari pengguna. Saya membuat struktur dasar HTML dengan judul "Membuat Form" di header.

**Kode:**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat Form</h1>
    </header>
</body>
</html>
```
## Penjelasan:
File ini memiliki struktur yang sama dengan file-file sebelumnya. Form HTML adalah komponen interaktif yang memungkinkan pengguna memasukkan data yang kemudian dapat dikirim ke server untuk diproses.

# Langkah 9: Membuat Form Dasar
Saya membuat form sederhana untuk data pelanggan. Form dimulai dengan tag `<form>` yang memiliki atribut `action="proses.php"` (menentukan file yang akan memproses data) dan `method="post"` (metode pengiriman data). Di dalam form, saya menggunakan `<fieldset>` untuk mengelompokkan elemen-elemen terkait dan `<legend>` untuk memberikan judul grup. Form ini berisi field untuk Nama (input text), Alamat (textarea), dan Jenis Kelamin (radio button). Setiap field memiliki `<label>` yang terhubung dengan input melalui atribut for dan id.

**Kode:**
```
<form action="proses.php" method="post">
    <fieldset>
        <legend>Data Pelanggan</legend>
        <p>
            <label for="nama">Nama</label>
            <input type="text" id="nama" name="nama">
        </p>
        <p>
            <label for="alamat">Alamat</label>
            <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
        </p>
        <p>
            <label>Jenis Kelamin</label>
            <input id="jk_l" type="radio" name="kelamin" value="L" /><label for="jk_l">Laki-laki</label>
            <input id="jk_p" type="radio" name="kelamin" value="P" /><label for="jk_p">Perempuan</label>
        </p>
        <p><input type="submit" value="Login"></p>
    </fieldset>
</form>
```
## Penjelasan:
Form HTML menggunakan tag `<form>` dengan atribut penting: `action` menentukan URL tujuan pengiriman data, dan `method` menentukan cara pengiriman (POST atau GET). POST lebih aman karena data tidak terlihat di URL. Tag `<fieldset>` mengelompokkan field terkait, dan `<legend>` memberi judul grup tersebut. Setiap input memiliki atribut `name` yang menjadi kunci data saat dikirim ke server. Tag `<label>` meningkatkan accessibility dengan menghubungkan teks label ke input melalui atribut `for` yang merujuk ke `id` input. Radio button dengan `name` yang sama membentuk grup pilihan tunggal.

**Hasil Tampilan:**
<img width="1920" height="1080" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/f196ee6b-ce1b-4091-b99e-976cac2e2357" />

# Langkah 10: Menambahkan CSS pada Form
Untuk membuat form lebih menarik, saya menambahkan CSS di dalam tag `<style>` pada bagian `<head>`. CSS ini mengatur lebar label agar seragam dengan `display: inline-block` dan `width: 100px`, memberikan border hijau pada input text dan textarea, serta mendesain tombol submit dengan background hijau, teks putih tebal, dan padding yang nyaman. Styling ini membuat form terlihat lebih profesional dan user-friendly.

**Kode:**
```
<style>
    form p > label {
        display: inline-block;
        width: 100px;
    }
    form input[type="text"], form textarea {
        border: 1px solid #197a43;
    }
    form input[type="submit"] {
        border: 1px solid #197a43;
        background-color: #197a43;
        color: #ffffff;
        font-weight: bold;
        padding: 5px 15px;
    }
</style>
```
## Penjelasan:
CSS (Cascading Style Sheets) digunakan untuk mengatur tampilan visual elemen HTML. Selector form `p > label` menargetkan semua label yang merupakan child langsung dari tag `<p>` dalam form. Property `display: inline-block` membuat label bisa diatur lebarnya dengan `width: 100px`, sehingga semua label sejajar rapi. Selector form `input[type="text"]` menargetkan input dengan type tertentu. Border color `#197a43` adalah kode hex untuk warna hijau. Tombol submit diberi styling khusus dengan background hijau, text putih, dan padding untuk membuatnya lebih menonjol dan mudah diklik.

**Hasil Tampilan:**
<img width="1920" height="1080" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/0574689b-2f24-499f-b5b0-865e97b69be1" />

# Kesimpulan
Melalui praktikum ini, saya telah berhasil mempelajari dan mengimplementasikan:

### 1. List HTML:
Ordered List (daftar berurutan), Unordered List (daftar tidak berurutan), dan Description List (daftar dengan deskripsi). Setiap jenis list memiliki kegunaan spesifik sesuai dengan struktur data yang ingin ditampilkan.
### 2. Tabel HTML: 
Membuat struktur tabel dengan header dan body, mengatur padding dan spacing sel, serta menggabungkan sel menggunakan rowspan untuk membuat tabel yang lebih efisien dan mudah dibaca.
### 3. Form HTML: 
Membuat form interaktif dengan berbagai jenis input (text, textarea, radio button, dropdown, dan multiple selection), memberikan styling dengan CSS untuk tampilan yang lebih menarik, serta memahami atribut-atribut penting seperti action, method, name, dan id.
### 4. Implementasi CSS: 
Menggunakan CSS untuk mempercantik tampilan dengan teknik modern seperti gradient background, border-radius, box-shadow, dan transition effects.
