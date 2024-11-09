# Semantik
HTML :
Dokumen HTML ini dimulai dengan deklarasi DOCTYPE untuk HTML5. Di dalam tag <head>, terdapat metadata seperti pengaturan karakter dan tampilan untuk responsivitas, serta penghubung ke file CSS eksternal (meskipun ada kesalahan pada URL file CSS). Pada bagian <body>, terdapat elemen-elemen struktural seperti header, navigasi dengan daftar link, section untuk konten, dan footer untuk informasi hak cipta.
Selain itu, ada beberapa kesalahan pada sintaks:
•	Tag <link> untuk file CSS memiliki tanda kurung yang tidak sesuai (nav {.css seharusnya nav.css).
•	Tag <section> seharusnya menggunakan huruf kecil (<section>) sesuai dengan standar HTML5.


CSS :
Kode CSS di atas mendesain tata letak halaman menggunakan grid. Elemen-elemen seperti header, navigasi, bagian utama (section), dan footer ditempatkan dalam struktur grid dengan penataan kolom dan baris tertentu. body menggunakan grid untuk mengatur area masing-masing elemen dengan menetapkan tinggi dan lebar yang sesuai. Warna latar belakang juga diterapkan pada setiap elemen, dan jarak antar elemen diatur dengan grid-gap. Dengan pengaturan ini, halaman akan mengisi seluruh tinggi layar dan elemen-elemen di dalamnya ditempatkan dengan terstruktur.

BEFORE AFTER :
Pada coding sebelumnya,style dari css tidak tampil pada html karena codingan html belum terhubung dengan style dari css.Agar style css dapat tampil dan mengubah style pada html maka diperlukan tambahan link rel yang menuju pada folder coding css seperti sintax berikut :
        <link rel="stylesheet" href="./Asset/Style/nav {.css">
Setelah sintax diatas diletakkan pada line head paling akhir maka barulah style pada html berubah tampilan karena sintax diatas berfungsi untuk menghubungkan antara coding awal html dengan css (style)
