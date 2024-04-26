

1. tentang css
	> extension google chrom (tools pendukung)
  - color zila (pick color hexa/rgb/cmyk)
  - font ninja (deteksi font)
2. git (cloud storage)
	- install git scm
	- registrasi/login github > https://github.com/
langkah github:
  1. install git (selesai proses instalasi)
  2. buat akun github/login akun github
  3. buat repository
  4. settings token classic
  5. management data koding > push

----------------
external css: style.css
/* artikel */
.artikel {
  padding: 10px;
  border-radius: 10px;
}

file belajar.html
<!-- internal css -->
<style>
  .warna {
    background-color: aqua !important;
    padding: 20px;
    font-size: larger;
    color: brown;
    margin-left: 50px;
    font-size: 24px;
  }

  h1 {
    background-color: blue;
    color: red;
    font-size: 20px;
  }
</style>

<!-- external -->
<link rel="stylesheet" type="text/css" href="style.css" />


body:
<p id="warna">Belajar CSS (Casecading Style Sheet)</p>
<p class="warna">Belajar HTML</p>
<h1 class="artikel">
  Hey Brow (Browser) Cari tag h1 yang terdapat di dalam class artikel, jika
  ditemukan/ada, ubah warnanya menjadi merah, warna background menjadi biru
  dan ukuran huruf menjadi 20 pixel.
</h1>
<!-- inline css -->
<h1 class="warna" style="background-color: bisque; color: blue">
  Hello Brow (Browser)
</h1>


---------------------------


