# CV Dhea Kurniawan

Proyek ini adalah halaman CV pribadi milik **Dhea Kurniawan** yang dibuat menggunakan HTML semantik murni tanpa CSS framework maupun styling eksternal.

---

## Tujuan Proyek

Membuat halaman CV berbasis web yang memenuhi standar:

- **Semantic HTML** — menggunakan tag HTML yang sesuai makna kontennya
- **SEO Meta Tags** — membantu halaman ditemukan oleh mesin pencari
- **Open Graph (OG) Tags** — mengoptimalkan tampilan saat dibagikan di media sosial
- **Favicon** — ikon kecil yang muncul di tab browser

---

## Struktur File

```
cv-dhea-kurniawan/
├── index.html        # File utama halaman CV
└── README.md         # Dokumentasi proyek ini
```

---

## Penjelasan Teknis

### Semantic HTML

Tag HTML dipilih berdasarkan **makna konten**, bukan tampilan. Struktur yang digunakan:

| Tag                      | Fungsi                                               |
| ------------------------ | ---------------------------------------------------- |
| `<header>`               | Identitas halaman: nama, tagline, kontak             |
| `<main>`                 | Konten utama CV                                      |
| `<section>`              | Pengelompokan per tema (Pengalaman, Pendidikan, dll) |
| `<article>`              | Satu entri mandiri dalam section                     |
| `<address>`              | Informasi kontak                                     |
| `<footer>`               | Penutup halaman                                      |
| `<time datetime="">`     | Tanggal yang bisa dibaca mesin                       |
| `<dl>` / `<dt>` / `<dd>` | Pasangan label–nilai untuk Skills                    |

Hierarki heading yang digunakan:

```
h1 → Nama (hanya sekali di seluruh halaman)
h2 → Judul setiap section
h3 → Nama perusahaan / institusi / proyek
h4 → Posisi / jurusan / subtitle
```

---

### SEO Meta Tags

Meta tag yang disertakan di `<head>`:

```html
<meta name="description" content="..." />
<meta name="keywords" content="..." />
<meta name="author" content="Dhea Kurniawan" />
<meta name="robots" content="index, follow" />
<link rel="canonical" href="https://dheakurniawan.dev/cv" />
```

- `description` — ringkasan halaman yang muncul di hasil pencarian Google
- `keywords` — kata kunci relevan untuk mesin pencari
- `author` — nama pemilik konten
- `robots` — memberi izin mesin pencari untuk mengindeks halaman
- `canonical` — mencegah duplikasi konten jika halaman diakses dari beberapa URL

---

### Open Graph (OG) Tags

OG tags mengontrol tampilan ketika link CV dibagikan di media sosial (WhatsApp, LinkedIn, Twitter, dll):

```html
<meta property="og:title" content="..." />
<meta property="og:description" content="..." />
<meta property="og:image" content="..." />
<meta property="og:url" content="..." />
<meta property="og:type" content="profile" />
```

Ukuran gambar OG yang direkomendasikan: **1200 x 630 px**.

Twitter Card juga disertakan agar tampilan di Twitter/X optimal:

```html
<meta name="twitter:card" content="summary_large_image" />
```

---

### Favicon

Favicon adalah ikon kecil yang muncul di tab browser. Disertakan dalam beberapa format untuk kompatibilitas lintas perangkat:

```html
<!-- SVG (modern browsers) -->
<link rel="icon" type="image/svg+xml" href="..." />

<!-- PNG fallback -->
<link rel="icon" type="image/png" sizes="32x32" href="favicon-32x32.png" />
<link rel="icon" type="image/png" sizes="16x16" href="favicon-16x16.png" />

<!-- Apple devices -->
<link rel="apple-touch-icon" sizes="180x180" href="apple-touch-icon.png" />
```

---

## Cara Menjalankan

1. Clone atau download repository ini
2. Buka file `index.html` langsung di browser
3. Tidak membutuhkan server atau instalasi apapun

---

## Author

**Dhea Kurniawan**
Fresh Graduate S1 Sistem Informasi — UNIKOM
📧 dheakurniawan1941@gmail.com
📍 Subang, Indonesia
