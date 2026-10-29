# Jaga Laut

**Website Edukasi Konservasi Laut dan Pantai**  
Mata Kuliah: Pemrograman Web — Proyek UTS  
Tema SDGs: **SDG 13 (Penanganan Perubahan Iklim)** dan **SDG 14 (Ekosistem Laut)**

## Deskripsi Proyek

Jaga Laut adalah website edukasi yang menyampaikan informasi mengenai pentingnya menjaga laut dan wilayah pesisir. Website ini membahas persoalan seperti sampah laut, pencemaran pantai, perlindungan ekosistem pesisir, serta tindakan sederhana yang dapat dilakukan masyarakat untuk membantu menjaga kelestarian laut.

Website ditujukan bagi masyarakat umum, khususnya pelajar dan komunitas yang ingin mempelajari cara menjaga kebersihan pantai serta ekosistem laut. Konten disusun agar mudah dipahami dan mendorong kebiasaan yang lebih bertanggung jawab terhadap lingkungan.

## Tujuan dan Manfaat

- Memberikan edukasi dasar mengenai konservasi laut dan pantai.
- Mengajak masyarakat mengurangi sampah dan pencemaran di wilayah pesisir.
- Menyediakan panduan praktis yang bisa diterapkan dalam kehidupan sehari-hari.
- Memudahkan pengguna menemukan informasi melalui navigasi ant halaman yang konsisten.

## Anggota Kelompok dan Pembagian Tugas

> Lengkapi bagian **NIM** dan nama lengkap anggota selain Artha. Data tersebut belum tersedia pada informasi yang diberikan, jadi tidak dicantumkan dengan tebakan.

| No. | Nama Lengkap                              | NIM            | Tanggung Jawab                                                |
| --: | ----------------------------------------- | -------------- | ------------------------------------------------------------- |
|   1 | **Putu Artha Wiguna**                     | **2515091084** | Halaman Edukasi (`edukasi.html`) dan Tentang (`tentang.html`) |
|   2 | **I Gede Panji Adikara Rendytama**        | **2515091024** | Halaman Panduan (`panduan.html`)                              |
|   3 | **Naysheila Firyal Ramdani**              | **2515091066** | Halaman Beranda (`index.html`)                                |
|   4 | **I Made Andhika Cahya Putra Aran Bakan** | **2515091068** | Halaman Artikel (`artikel.html`)                              |

## Halaman Website

| Halaman | Berkas         | Isi Utama                                                                                       | Penanggung Jawab |
| ------- | -------------- | ----------------------------------------------------------------------------------------------- | ---------------- |
| Beranda | `index.html`   | Pengenalan website Jaga Laut, pengantar tema, dan tautan ke konten utama.                       | Nay              |
| Edukasi | `edukasi.html` | Informasi dan edukasi mengenai isu konservasi laut dan pantai.                                  | Artha            |
| Panduan | `panduan.html` | Langkah praktis untuk menjaga kebersihan pantai dan mengurangi dampak terhadap lingkungan laut. | Panji            |
| Artikel | `artikel.html` | Artikel edukatif dan informasi pendukung tentang laut serta wilayah pesisir.                    | Andhika Bakan    |
| Tentang | `tentang.html` | Penjelasan tujuan website, identitas pengembang, dan referensi informasi.                       | Artha            |

## Teknologi yang Digunakan

- **HTML5** untuk menyusun struktur dan konten setiap halaman.
- **CSS3** untuk mengatur tata letak, warna, tipografi, dan tampilan ant halaman.
- **Flexbox dan/atau CSS Grid** untuk membantu penyusunan layout jika diterapkan pada stylesheet.
- **CSS Media Queries** untuk menyesuaikan tampilan pada desktop, tablet, dan smartphone.
- **Git dan GitHub** untuk pengelolaan kode sumber.
- **GitHub Pages** untuk publikasi website secara daring.

## Penjelasan Implementasi

### 1. Struktur HTML

Setiap halaman menggunakan struktur HTML dan metadata dokumen. Elemen semantik seperti `header`, `nav`, `main`, `section`, `article`, dan `footer` dapat digunakan sesuai kebutuhan agar struktur halaman lebih jelas.

Contoh struktur dasar:

```html
<header>
  <nav aria-label="Navigasi utama">
    <a href="index.html">Beranda</a>
    <a href="edukasi.html">Edukasi</a>
    <a href="panduan.html">Panduan</a>
    <a href="artikel.html">Artikel</a>
    <a href="tentang.html">Tentang</a>
  </nav>
</header>

<main>
  <section>
    <h1>Jaga Laut</h1>
    <p>Edukasi untuk menjaga laut dan wilayah pesisir.</p>
  </section>
</main>
```

### 2. CSS Eksternal

Gaya halaman diletakkan dalam file CSS eksternal agar tampilan dapat dikelola secara konsisten. Jika berkas stylesheet berada pada folder `css`, halaman HTML menghubungkannya menggunakan jalur berikut:

```html
<link rel="stylesheet" href="css/style.css" />
```

### 3. Layout dan Desain Responsif

Flexbox atau CSS Grid dapat digunakan untuk mengatur posisi navigasi, kartu informasi, serta kolom konten. Media queries membantu menyesuaikan layout pada ukuran layar yang berbeda.

Contoh pola media query:

```css
@media (max-width: 768px) {
  .container {
    padding: 1rem;
  }

  .content-grid {
    grid-template-columns: 1fr;
  }
}
```

Potongan kode di atas merupakan **contoh pola implementasi**. Sesuaikan penjelasan dan potongan kode dengan isi aktual `css/style.css` sebelum laporan dikumpulkan.

### 4. Navigasi Antarahalaman

Navigasi menghubungkan halaman Beranda, Edukasi, Panduan, Artikel, dan Tentang menggunakan tautan HTML. Periksa kembali setiap nilai `href` agar mengarah ke nama berkas yang benar.

## Struktur Folder

Struktur utama proyek yang ditargetkan:

```text
UTS_PEMWEB_JAGA-LAUT/
├── index.html
├── edukasi.html
├── panduan.html
├── artikel.html
├── tentang.html
├── css/
│   └── style.css
├── images/              # Jika digunakan untuk menyimpan gambar
└── README.md
```

Pastikan nama dan lokasi file di repository sesuai dengan struktur aktual proyek. Jika folder gambar atau file lainnya memiliki nama berbeda, perbarui bagian ini.

## Website dan Repository

- **Repository GitHub:** https://github.com/Thaaa7/UTS_PEMWEB_JAGA-LAUT
- **Website GitHub Pages:** https://thaaa7.github.io/UTS_PEMWEB_JAGA-LAUT/

Periksa URL GitHub Pages setelah publikasi untuk memastikan website dapat diakses dan semua halaman, CSS, serta gambar tampil dengan benar.

## Referensi

- United Nations, **Goal 13: Climate Action** — https://sdgs.un.org/goals/goal13
- United Nations, **Goal 14: Life Below Water** — https://sdgs.un.org/goals/goal14
- Kementerian Kelautan dan Perikanan Republik Indonesia — https://kkp.go.id/
- United Nations Environment Programme, **Oceans and Seas** — https://www.unep.org/topics/ocean-seas-and-coasts

Cantumkan juga tautan sumber yang benar-benar digunakan untuk fakta, artikel, foto, ikon, atau aset visual pada halaman website. Pastikan atribusi dan lisensi aset sesuai ketentuannya.

---

**Catatan sebelum pengumpulan:** isi seluruh NIM dan nama lengkap yang masih berupa placeholder, pastikan penjelasan teknis sesuai dengan kode aktual, dan uji semua halaman melalui URL GitHub Pages.
