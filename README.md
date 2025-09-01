<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- UBAH: Judul Website -->
  <title>Profil Kelurahan Berkas</title>

  <!-- UBAH: Deskripsi singkat untuk SEO -->
  <meta name="description" content="Website profil Kelurahan Berkas: informasi layanan, struktur organisasi, berita, dan kontak." />

  <style>
    /* ===================== CSS UTAMA ===================== */
    :root {
      --brand: #136f63;   /* UBAH: warna utama */
      --accent: #f4b400;  /* UBAH: warna aksen */
      --light: #f9f9f9;
      --dark: #222;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: var(--dark);
      background: var(--light);
    }

    h1, h2, h3 {
      margin-top: 0;
      color: var(--brand);
    }

    a {
      color: var(--brand);
      text-decoration: none;
    }

    /* Layout umum */
    .container {
      width: 90%;
      max-width: 1100px;
      margin: auto;
      padding: 20px 0;
    }

    /* Navbar */
    header {
      background: var(--brand);
      color: white;
      padding: 10px 0;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav .brand {
      font-size: 1.3rem;
      font-weight: bold;
      color: white;
    }

    nav .menu a {
      margin: 0 10px;
      color: white;
    }

    nav .btn {
      background: var(--accent);
      padding: 5px 12px;
      border-radius: 5px;
      color: black;
      font-weight: bold;
    }

    /* Hero */
    .hero {
      background: url("https://via.placeholder.com/1200x400") center/cover no-repeat; 
      /* UBAH: ganti link gambar background */
      color: white;
      text-align: center;
      padding: 100px 20px;
    }

    .hero h1 {
      font-size: 2.5rem;
    }

    /* Grid */
    .grid-2 {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .grid-3 {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }

    /* Card */
    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    /* Table */
    .table {
      width: 100%;
      border-collapse: collapse;
    }

    .table td {
      border: 1px solid #ddd;
      padding: 8px;
    }

    /* Galeri */
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 10px;
    }

    .gallery img {
      width: 100%;
      border-radius: 10px;
    }

    /* Map */
    .map {
      width: 100%;
      height: 300px;
      border: 0;
      border-radius: 10px;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background: var(--brand);
      color: white;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <!-- ====================== NAVBAR ====================== -->
  <header>
    <div class="container">
      <nav>
        <!-- UBAH: Nama Kelurahan -->
        <a class="brand" href="#beranda">Kelurahan Berkas</a>

        <div class="menu">
          <!-- Menu bisa ditambah/kurangi -->
          <a href="#profil">Profil</a>
          <a href="#visi">Visi & Misi</a>
          <a href="#layanan">Layanan</a>
          <a href="#struktur">Struktur</a>
          <a href="#berita">Berita</a>
          <a href="#galeri">Galeri</a>
          <a href="#lokasi">Peta</a>
          <a href="#kontak" class="btn">Kontak</a>
        </div>
      </nav>
    </div>
  </header>

  <!-- ====================== HERO ====================== -->
  <section id="beranda" class="hero">
    <div class="container">
      <!-- UBAH: Judul sambutan -->
      <h1>Selamat Datang di Website Kelurahan Berkas</h1>
      <!-- UBAH: Deskripsi singkat -->
      <p>Pusat informasi layanan publik dan aktivitas masyarakat.</p>
    </div>
  </section>

  <!-- ====================== PROFIL ====================== -->
  <section id="profil">
    <div class="container grid-2">
      <div class="card">
        <h2>Profil Kelurahan</h2>
        <!-- UBAH: Isi deskripsi profil -->
        <p>Kelurahan Berkas berada di Kecamatan Teluk segara, Kota Bengkulu. 
           Wilayah ini memiliki potensi ekonomi, sosial, dan budaya yang berkembang.</p>
      </div>
      <div class="card">
        <h3>Data Singkat</h3>
        <table class="table">
          <tbody>
            <!-- UBAH: Data sesuai kelurahan -->
            <tr><td>Kecamatan</td><td>Teluk Segara</td></tr>
            <tr><td>Kota/Kabupaten</td><td>Bengkulu</td></tr>
            <tr><td>Provinsi</td><td>Bengkulu</td></tr>
            <tr><td>Luas Wilayah</td><td>3,7 km²</td></tr>
            <tr><td>Kode Pos</td><td>38114</td></tr>
            <tr><td>Telepon</td><td>(021) 123-456</td></tr>
          </tbody>
        </table>
      </div>
    </div>
  </section>

  <!-- ====================== VISI MISI ====================== -->
  <section id="visi">
    <div class="container grid-2">
      <div class="card">
        <h2>Visi</h2>
        <!-- UBAH: isi visi -->
        <p>“Menjadi kelurahan yang maju, transparan, dan berdaya saing.”</p>
      </div>
      <div class="card">
        <h2>Misi</h2>
        <!-- UBAH: isi misi -->
        <ul>
          <li>Meningkatkan kualitas pelayanan publik.</li>
          <li>Mendorong partisipasi aktif masyarakat.</li>
          <li>Mengembangkan potensi lokal.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- ====================== LAYANAN ====================== -->
  <section id="layanan">
    <div class="container">
      <h2>Layanan Kelurahan</h2>
      <div class="grid-3">
        <div class="card">
          <h3>Administrasi Kependudukan</h3>
          <p>KTP, KK, akta lahir, surat pindah.</p>
        </div>
        <div class="card">
          <h3>Surat Pengantar</h3>
          <p>SKTM, domisili, usaha, pernikahan.</p>
        </div>
        <div class="card">
          <h3>Pengaduan Warga</h3>
          <p>Layanan aduan terkait fasilitas umum dan sosial.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- ====================== STRUKTUR ORGANISASI ====================== -->
  <section id="struktur">
    <div class="container">
      <h2>Struktur Organisasi</h2>
      <div class="card">
        <ul>
          <!-- UBAH: Nama pejabat -->
          <li>Lurah: Luna Maswita S.E</li>
          <li>Sekretaris: Nama Sekretaris</li>
          <li>Kasi Pemerintahan: Nama Pegawai</li>
          <li>Kasi Pelayanan: Nama Pegawai</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- ====================== BERITA ====================== -->
  <section id="berita">
    <div class="container">
      <h2>Berita & Agenda</h2>
      <div class="grid-3">
        <article class="card">
          <h3>Gotong Royong Bersama</h3>
          <p>Kegiatan kerja bakti warga RW 05, Minggu pagi.</p>
        </article>
        <article class="card">
          <h3>Pembagian Sembako</h3>
          <p>Bantuan sosial untuk warga kurang mampu.</p>
        </article>
        <article class="card">
          <h3>Pelatihan UMKM</h3>
          <p>Workshop kewirausahaan untuk pelaku usaha kecil.</p>
        </article>
      </div>
    </div>
  </section>

  <!-- ====================== GALERI ====================== -->
  <section id="galeri">
    <div class="container">
      <h2>Galeri</h2>
      <div class="gallery">
        <!-- UBAH: Ganti link gambar -->
        <img src="https://via.placeholder.com/300" alt="Kegiatan 1">
        <img src="https://via.placeholder.com/300" alt="Kegiatan 2">
        <img src="https://via.placeholder.com/300" alt="Kegiatan 3">
      </div>
    </div>
  </section>

  <!-- ====================== PETA ====================== -->
  <section id="lokasi">
    <div class="container">
      <h2>Peta Lokasi</h2>
      <!-- UBAH: ganti link src maps -->
      <iframe class="map" src="https://www.google.com/maps/embed?pb=..." allowfullscreen></iframe>
    </div>
  </section>

  <!-- ====================== KONTAK ====================== -->
  <section id="kontak">
    <div class="container">
      <h2>Kontak</h2>
      <!-- UBAH: alamat, telepon, email -->
      <p>Alamat: Jl. Contoh Raya No. 1</p>
      <p>Telepon: (021) 123-456</p>
      <p>Email: kelurahan@example.go.id</p>
    </div>
  </section>

  <!-- ====================== FOOTER ====================== -->
  <footer>
    <div class="container">
      <!-- UBAH: Nama Kelurahan -->
      <p>© 2025 KKN 25 UNIVERSITAS MUHAMMADIYAH BENGKULU</p>
    </div>
  </footer>

</body>
</html>
