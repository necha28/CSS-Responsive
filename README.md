# CSS-Responsive

# Pengertian CSS Responsive
Salah satu prinsip halaman website adalah dapat dijalankan pada browser dari berbagai tipe device pengguna. Kategori device pengguna dapat dibedakan menjadi kategori perangkat mobile, dektop, dan tablet. Kategori perangkat tersebut berbeda dalam ukuran layarnya. Halaman website yang baik harus dapat menyesuaiakan ukuran layer dari device pengguna. Untuk mengatasi hal tersebut, dibutuhkan sebuah style yang responsive yang biasa disebut dengan CSS Responsive. 

Hal yang pertama kali untuk membuat halaman web yang responsive adalah dengan mengatur viewport pada halaman web tersebut. Pengarturan tersebut dituliskan pada tag <meta> yang terdapat di dalam tag <head>. Berikut ini adalah sintak untuk mengatur viewport pada halaman web. 
<head>
<meta name=”viewport” content=”width=device-width, initialscale=1.0” >
.. 
</head> 
Dari sintak di atas, dapat diartikan bahwa nilai width diambil dari ukuran lebar layar pengguna dan inisiasi zoom pada halaman tersebut adalah 1. 

Selain mengatur viewport pada halaman web, ada beberapa hal yang harus diperhatikan terutama ketika styling elemen HTML pada CSS. Agar halaman web menjadi responsive, pengaturan dimensi (width dan height) harus dinamis. Dengan arti lain, pengarturan width menggunakan satuan pesen (%) dan height harus auto. 

# Penggunaan Media Query
Fitur media query adalah fitur untuk yang digunakan sebagai filter terhadap lebar layar pengguna. Berikut ini contoh sintak penggunaan media query. 
@media only screen and (min-width: 780px) {
  body {   
       background:yellow;
  }
} 
Dari sintak di atas dapat diartikan bahwa background dari body akan berwarna kuning ketika lebar layar minimal 768 pixel (background berwarna kuning ketika lebar layar berukuran > 780 pixel).

# Konsep Grid pada Halaman Web
Konsep grid merupakan sebuah trik untuk membagi lebar layar menjadi 12 bagian. Konsep ini sangat membantu untuk membuat tampilan web menjadi lebih mudah. Berikut ini contoh sintak pembagian grid.

# Latihan Media Query
