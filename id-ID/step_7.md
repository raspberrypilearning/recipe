## Warna!

Mari tambahkan beberapa warna ke halaman web resep Anda.

+ Anda sudah belajar cara menambahkan teks berwarna ke halaman web. Tambahkan kode ini di dalam file `style.css` , untuk membuat semua teks di biru badan situs web:

    badan {
        warna: biru;
    }
    

![tangkapan layar](images/recipe-blue.png)

+ Browser Anda tahu warna seperti `biru`, `kuning` dan bahkan `lightgreen`, tetapi apakah Anda tahu bahwa peramban Anda benar-benar mengetahui **nama** dari 140 lebih warna yang berbeda?

Ada daftar semua nama warna yang bisa Anda gunakan: [jumpto.cc/colours](http://jumpto.cc/colours), yang mencakup nama warna seperti `tomat`, `firebrick` dan `peachpuff`.

Ubah warna teks dari `biru` menjadi `tomat`.

![screenshot](images/recipe-tomato.png)

+ Browser Anda tahu nama-nama 140 warna, tetapi sebenarnya tahu nilai-nilai **warna** lebih dari 16 juta warna!

Untuk memberi tahu browser mana warna yang akan ditampilkan, Anda hanya perlu membiarkannya mengetahui seberapa banyak warna merah, hijau, dan biru yang digunakan.

Jumlah warna merah, hijau dan biru ditulis sebagai angka antara `0` dan `255`.

![screenshot](images/recipe-rgb-img.png)

Tambahkan kode ini ke CSS untuk badan halaman web, untuk menampilkan latar belakang kuning muda:

    latar belakang: rgb (250,250,210);
    

![screenshot](images/recipe-rgb.png)

+ Jika Anda suka, Anda dapat memberi tahu browser mana warna yang akan ditampilkan dengan menggunakan kode heksadesimal (atau **kode hex**). Ini bekerja dengan cara yang mirip dengan `rgb ()` kode di atas, kecuali bahwa kode hex selalu dimulai dengan `#`, dan menggunakan 'angka' heksadesimal antara `00` dan `ff` untuk jumlah merah, hijau dan biru.

![screenshot](images/recipe-hex-img.png)

Ganti kode `rgb ()` di CSS Anda dengan kode hex ini:

    latar belakang: # fafad2;
    

![screenshot](images/recipe-hex.png)

Anda seharusnya melihat warna kuning yang sama seperti sebelumnya!