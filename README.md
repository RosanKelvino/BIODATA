<h1>LAPORAN CSS</h1>
<h4>Rosan Kelvino Andre</h4>
<h4>42430025</h4>
<br>
<h2>PENDAHULUAN</h2>
<p>Cascading Style Sheets (CSS) adalah bahasa yang digunakan untuk mengatur tampilan dan desain halaman web. CSS memungkinkan pengembang web memisahkan konten dari tampilan, sehingga kode menjadi lebih rapi, mudah dikelola, dan efisien. Dengan CSS, kita dapat mengatur warna, ukuran font, tata letak, spasi, hingga animasi pada elemen HTML. Penggunaan CSS sangat penting karena memberikan pengalaman visual yang menarik bagi pengguna serta membuat halaman web lebih profesional dan konsisten. Laporan ini akan membahas konsep dasar CSS, manfaatnya, serta penerapan sederhana dalam membangun tampilan web.</p><br>

<h2>PEMBAHASAN</h2>
<h3>Profil.html dan profil.css</h3>
<p>Halaman ini menampilkan biodata dengan desain yang bersih dan modern. Struktur halaman diatur dengan elemen HTML seperti header, nav, section, dan div. Sedangkan CSS digunakan untuk mengatur warna, ukuran font, tata letak, serta memberikan efek desain seperti posisi header tetap, gambar profil berbentuk lingkaran, dan teks yang rata.</p>
<p>Fungsi Kode Profil.html:</p>
<ul>
     <li>Header -> menyediakan h1 untuk menampilkan judul dan nav untuk                menyedaiakn navigasi dengan link home dan profil</li>
    <li>Section -> berisi halaman utama dengan menampilkan dua elemen div yaitu foto dan konten</li>                                                                       
</ul>
<p>Fungsi Kode profil.css</p>
<ul>
   <li>margin untuk memberi jarak diluar elemen</li>
   <li>padding untuk memberi jarak didalam elemen</li>
   <li>font-size mengatur ukuran font </li>
   <li>background-color untuk mengatur warna latar belakang</li>
   <li>position: fixed  diperlukan untuk membuat bagian header selalu berada diatas layar meskipun halaman discroll</li>
   <li>color untuk mengatur warna pada font</li>
   <li>display: flex,gap,text-align:justify untuk mengatur tata letak konten menggunakan flexbox sehingga foto dan teks berada sejajar</li>
   <li>border-radius:50% untuk membentuk foto berbentuk lingkaran</li>
   <li>cursor:pointer untuk mengubah bentuk cursor saat berada diobjek home dan profil</li>
   <li>box-sizing:border-box membuat ukuran elemen tetap sesuai yang diatur</li>
</ul><br>

<h3>Biodata.html dan Biodata.css</h3>
<p>Halaman Profil adalah lanjutan dari halaman home. Halaman ini berisi informasi detail seperti nama lengkap, email, nomor telepon, akun media sosial, riwayat pendidikan, dan daftar kemampuan (skill). Tampilan diatur menggunakan biodata.css agar terlihat rapi, dengan posisi foto di sisi kiri dan konten biodata di sisi kanan</p>
<p>Fungsi kode Biodata.html</p>
<ul>
     <li>div class="foto" berisi foto profil dan informasi kontak</li>
     <li>hr style="border: 2px solid white; height: 100vh;" untuk membuat garis vertikal</li>
     <li>hr style="border: 1px solid white; untuk membuat garis horizontal</li>
     <li>div class="nama" berisi informasi biodata profil,pendidikan, dan skill</li>
     <li>table digunakan untuk menampilkan riwayat pendidikan dalam bentuk tabel</li>
     <li>ul dan li digunakan untuk menampilkan daftar skill dalam bentuk bullet list</li>
</ul>

<p>Fungsi Kode Biodata.css</p>
<ul>
     <li>Body{padding-left/rigt/top untuk memberi jarak agar konten tidak menempel pada tepi layar</li>
     <li>section { margin-top: 100px; display: flex; gap: 50px; } membantu agar mengatur bagian foto dan biodata ditampilkan sejajar</li>
     <li> justify-content: space-between untuk mengatur posisi item seperti item pertama dikiri dan item kedua dikanan</li>
     <li>text-decoration:none untuk menghapus dekorasi bawaan pada teks, seperti garis bawah</li>
     
</ul><br>

<h2>KESIMPULAN</h2>
<p>Dari pembahasan yang telah dilakukan, dapat disimpulkan bahwa CSS memiliki peran penting dalam pengembangan web karena mampu memisahkan desain dari struktur konten. Hal ini membuat halaman web menjadi lebih teratur, cepat diakses, dan enak dipandang. Selain itu, penggunaan CSS mempermudah pengembang dalam mengelola tampilan ketika terjadi perubahan desain, karena cukup mengedit file CSS tanpa harus mengubah seluruh file HTML.</p>



