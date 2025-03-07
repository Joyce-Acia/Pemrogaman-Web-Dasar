# Apa Itu CSS?
CSS adalah bahasa Cascading Style Sheet dan biasanya digunakan untuk mengatur tampilan elemen yang tertulis dalam bahasa markup, seperti HTML. CSS berfungsi untuk memisahkan konten dari tampilan visualnya di situs.

# Fungsi CSS
CSS berfungsi untuk membantu para web designer agar dapat mengubah dan menambahkan, baik teks, gambar, hingga latar belakang sebuah halaman HTML. Biasanya, keberadaan CSS dapat langsung terlihat dengan adanya perbedaan pada warna teks. Berikut beberapa fungsi CSS lainnya yang baik untuk website, antara lain:

1. Proses loading halaman web lebih cepat
Satu rangkaian kode CSS dapat diaplikasikan untuk beberapa halaman website sekaligus sehingga jumlah kode dapat diminimalkan. Hal ini tentunya akan membuat beban loading website menjadi lebih kecil. Alhasil, kecepatan saat loading website pun akan menjadi lebih cepat.

2. Beragam variasi
Seperti yang kita ketahui, HTML memang dapat digunakan untuk mengatur tampilan website. Sayangnya, terbatas. Namun hal ini tidak berlaku bagi CSS yang menawarkan lebih banyak style tampilan pada halaman website.

3. Tampilan website akan lebih rapi
Dengan menggunakan CSS, tampilan halaman website pun akan rapi dan optimal di berbagai ukuran layar pengguna, baik itu desktop maupun smartphone. Sehingga pemilik website tidak perlu repot mengatur dan pusing memikirkan website tidak maksimal dibuka dari perangkat-perangkat pengunjung.

# Penggunaan CSS untuk HTML
CSS didesain untuk digunakan dengan HTML. Ada tiga cara berbeda di dalam menggunakan CSS dengan HTML yaitu inline CSS, internal CSS dan external CSS. Tergantung keperluan, bisa saja ketiga cara menggunakan CSS tersebut dipakai semua dalam membuat laman web. Berikut ini adalah penjelasan singkat untuk masing-masing cara menggunakan CSS dengan HTML:
## 1. Inline CSS
Inline CSS digunakan untuk memberi style (gaya) pada tag atau elemen HTML tertentu. Anda dapat menggunakan atribut style untuk memberi style pada tag HTML. Style hanya berlaku untuk tag HTML tersebut. Style di inline CSS memiliki prioritas utama dan yang akan digunakan (rendering) meskipun tag HTML tersebut juga sudah diberi style melalui internal CSS atau external CSS.
Berikut ini adalah contoh kode sederhana:

```
<!DOCTYPE html>
<html>
<head>
</head>
<body style="background-color:yellow;">

<h2 style="color:red;">Menggunakan CSS Dengan HTML</h2>

<p style="color:blue;">Ada dua teknologi utama dalam pembuatan web modern yaitu CSS dan HTML. Keduanya mempunyai peran berbeda namun tidak terpisahkan. Secara umum, ada tiga cara menggunakan CSS dengan HTML yaitu inline CSS, internal CSS dan external CSS.</p>

</body>
</html>

```


## 2. Internal CSS
Internal CSS digunakan untuk memberi style yang hanya berlaku pada satu laman web. Style yang diberikan diapit oleh tag <style> </style> dan diletakkan di bagian elemen head atau tag <head> dari laman web. Anda dapat menggunakan internal CSS bila pemberian style dimaksudkan hanya untuk satu laman web saja dan tidak untuk digunakan di laman web yang lain. Anda dapat menggunakan internal CSS bila kode untuk style tidak terlalu besar atau kompleks.

Berikut ini adalah contoh kode sederhana:

```
<!DOCTYPE html>
<html>
<head>
   <style type="text/css">
      body {background-color:yellow;}
      h2 {color:red;}
      p {color:blue;}
   </style>
</head>
<body>

<h2>Menggunakan CSS Dengan HTML</h2>

<p>Ada dua teknologi utama dalam pembuatan web modern yaitu CSS dan HTML. Keduanya mempunyai peran berbeda namun tidak terpisahkan. Secara umum, ada tiga cara menggunakan CSS dengan HTML yaitu inline CSS, internal CSS dan external CSS.</p>

</body>
</html>
```


## 3. External CSS.
External CSS adalah file berekstensi .css yang hanya berisi kode-kode style. Tujuan menggunakan external CSS adalah untuk memisahkan kode style dengan struktur dan tipe konten laman web. External CSS dapat diaplikasikan pada lebih dari satu laman web sehingga semua laman web akan memiliki tampilan atau desain yang seragam.

Sebagai contoh, buat file CSS bernama csseksternal.css menggunakan plain text editor seperti Notepad atau Notepad++. Tuliskan kode CSS di bawah ini sebagai style yang akan diberlakukan di laman web. Simpan file CSS di folder yang sama tempat menyimpan file HTML.

```
body {background-color:yellow;}
h2 {color:red;}
p {color:blue;}
```

Buat file HTML dan di bagian tag <head> tambahkan elemen link atau tag <link>. Tag <link> ini akan digunakan untuk mengacu ke file CSS yang dibuat sebelumnya. Perhatikan penulisan <link> beserta atributnya untuk mengacu ke file CSS.

Berikut ini adalah contoh kode sederhana:
```
<!DOCTYPE html>
<html>
<head>
<link href="csseksternal.css" rel="stylesheet" type="text/css">
</head>
<body>

<h2>Menggunakan CSS Dengan HTML</h2>

<p>Ada dua teknologi utama dalam pembuatan web modern yaitu CSS dan HTML. Keduanya mempunyai peran berbeda namun tidak terpisahkan. Secara umum, ada tiga cara menggunakan CSS dengan HTML yaitu inline CSS, internal CSS dan external CSS.</p>

</body>
</html>
```
Tiga cara menggunakan CSS dengan HTML di atas menghasilkan tampilan laman web yang sama persis seperti gambar di bawah ini.

![cara-menggunakan-css-dengan-html](https://github.com/user-attachments/assets/9ce075b5-6dfd-449e-91be-22e3412a8b4d)


# Kelebihan CSS
## 1. Pemisahan Konten dan Presentasi:
- Kelebihan terbesar CSS adalah pemisahan antara konten (HTML) dan presentasi (CSS). Ini memungkinkan perubahan tata letak dan gaya tanpa harus menyentuh struktur HTML.
  
## 2. Fleksibilitas:
- CSS memberikan tingkat fleksibilitas yang tinggi dalam menentukan tata letak dan gaya halaman web. Desainer dapat dengan mudah mengubah tampilan situs web secara keseluruhan dengan hanya mengedit file CSS.
  
## 3. Efisiensi:
- Penggunaan CSS eksternal (dalam file terpisah) memungkinkan penggunaan ulang kode gaya di berbagai halaman, menghemat waktu dan sumber daya.
  
## 4. Responsif:
- CSS memungkinkan desainer untuk membuat desain responsif yang dapat menyesuaikan diri dengan berbagai ukuran layar, seperti pada perangkat seluler atau tablet.
  
## 5. Mendukung Animasi:
- CSS menyediakan dukungan untuk animasi dan transisi tanpa memerlukan penggunaan JavaScript atau plugin tambahan.

# Kekurangan CSS
## 1. Kompatibilitas Browser:
- Tidak semua fitur CSS didukung dengan konsisten di semua browser. Kadang-kadang, diperlukan hack atau penyesuaian khusus untuk memastikan tampilan yang konsisten di berbagai platform.
## 2. Kurangnya Fitur Pengelolaan Variabel:
- CSS memiliki dukungan terbatas untuk variabel, dan hal ini dapat membuat manajemen gaya yang kompleks kurang efisien.
## 3. Kompleksitas Terkadang Terlalu Tinggi:
- Beberapa desainer atau pengembang mungkin merasa bahwa CSS, terutama dalam proyek yang besar, dapat menjadi kompleks dan sulit untuk dipelajari dan dikelola.
## 4. Keterbatasan Pengelolaan Dependensi:
- Pada proyek yang besar, manajemen dependensi dan warisan kode dapat menjadi tantangan, terutama ketika melakukan perubahan besar dalam desain.
## 5. Kurangnya Penanganan Logika:
- CSS dirancang untuk mengelola tata letak dan gaya visual, tetapi tidak dirancang untuk menangani logika bisnis. Ini memerlukan penggunaan JavaScript atau bahasa pemrograman lainnya untuk mengatasi masalah ini.


# Perkembangan CSS
## CSS 1
Pada tanggal 17 Agustus 1996 World Wide Web Consortium (W3C) menetapkan CSS sebagai bahasa pemrograman standard dalam pembuatan web. Tujuannya adalah untuk mengurangi pembuatan tag-tag baru oleh Netscape dan Internet Explorer, karena kedua browser tersebut sedang bersaing mengembangkan tag sendiri untuk mengatur tampilan web.
CSS 1 mendukung pengaturan tampilan dalam hal :
1. Font (Jenis ketebalan).
2. Warna, teks, background dan elemen lainnya.
3. Text attributes, misalnya spasi antar baris, kata dan  huruf.
4. Posisi teks, gambar, table dan elemen lainnya.
5. Margin, border dan padiing.

## CSS2
Pada tahun 1998, W3C menyempurnakan CSS tahap awal dengan menciptakan standard CSS 2 yang menjadi standard hingga saat ini. Pada level CSS 2 ini, dimasukkan semua atribut dari CSS 1 dan diperluas dengan penekanan pada International Accessibiality and Capacibilty kususnya media-specific CSS. CSS 2 dikembangkan untuk memenuhi kebutuhan terhadap format dokumen agar bisa ditampilkan di printer. 

## CSS3
CSS 3adalah versi terbaru dari CSS yang mampu melakukan banyak hal dalam mendesain website. CSS 3 dapat melakukan animasi pada halaman website, diantaranya animasi warna dan animasi 3D. Dengan CSS 3 desaigner dimudahkan dalam hal kompatibilitas websitenya pada smartphone dengan dukungan fitur baru yakni media query. Selain itu, banyak fitur baru pada CSS 3 yaitu : Multiple background, border-radius, drop-shadow, border-image, CSS-Math dan CSS Object Model.
Fitur terbaru CSS 3 :
1. Animasi, sehingga pembuatan animasi tidak memerlukan program sejenis Adobe Flash dan Microsoft Silverlight.
2. Beberapa efek teks, seperti teks berbayang, kolom koran dan "Word-Wrap".
3. Beberapa efek pada kotak, seperti kotak yang ukurannya dapat diubah-ubah, transformasi 2 dimensi dan 2 dimensi, sudut-sudut yang tumpul dan bayangan.

**Contoh Perusahaan** 
Meta

**//cantumkan sumber data
Source**
https://widyamulya98.blogspot.com/2015/04/sejarah-dan-perkembangan-css.html
https://www.w3schools.com/css/css_intro.asp
https://www.geeksforgeeks.org/types-of-css-cascading-style-sheet/

https://www.termasmedia.com/kode-web/css/871-cara-menggunakan-css-dengan-html.html

https://www.bing.com/search?q=apa+fungsi+css&qs=n&form=QBRE&sp=-1&lq=0&pq=apa+fungsi+css&sc=12-14&sk=&cvid=7AD4231740064938B0558AE92621E7B7&ghsh=0&ghacc=0&ghpl=

https://www.hostinger.com/id/tutorial/apa-itu-css
