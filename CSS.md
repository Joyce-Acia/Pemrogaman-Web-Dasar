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




**Kelebihan Kekurangan**

**Perkembangan CSS hingga 2025 (summary)**

**Contoh Perusahaan** 
Meta

**//cantumkan sumber data
Source**
https://www.w3schools.com/css/css_intro.asp
https://www.geeksforgeeks.org/types-of-css-cascading-style-sheet/

https://www.termasmedia.com/kode-web/css/871-cara-menggunakan-css-dengan-html.html

https://www.bing.com/search?q=apa+fungsi+css&qs=n&form=QBRE&sp=-1&lq=0&pq=apa+fungsi+css&sc=12-14&sk=&cvid=7AD4231740064938B0558AE92621E7B7&ghsh=0&ghacc=0&ghpl=

https://www.hostinger.com/id/tutorial/apa-itu-css
