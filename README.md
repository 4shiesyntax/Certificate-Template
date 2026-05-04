# 🏅 Certificate Portfolio Template

Template HTML untuk menampilkan sertifikat secara elegan dengan tampilan dark gold luxury. Cocok untuk portofolio pribadi, CV online, atau halaman showcase sertifikat kamu.

---

## ✨ Fitur

- Desain dark & gold premium
- Animasi scroll yang smooth
- Nav dots untuk navigasi antar sertifikat
- Responsive (desktop & mobile)
- Grain texture subtle untuk kesan elegan
- Bisa memuat gambar sertifikat dari URL manapun (Cloudinary, ImgBB, Google Drive, dll)

---

## 🚀 Cara Pakai

### 1. Buka file `template_sertifikat.html` di teks editor (VS Code, Notepad++, dll)

### 2. Ganti semua teks `[placeholder]` dengan data kamu:

| Placeholder | Isi dengan |
|---|---|
| `[Nama Kamu]` | Nama lengkap kamu |
| `[Nama Lembaga]` | Penyelenggara sertifikat (cth: Karirnex, Coursera) |
| `[Tipe Program]` | Jenis program (cth: Exclusive Short Class, Bootcamp) |
| `[Nama Program]` | Nama program (cth: Digital Marketing) |
| `[Topik / Spesialisasi]` | Spesialisasi (cth: Copywriting) |
| `[Kota]` | Kota penyelenggaraan |
| `[Tanggal]` | Tanggal pelaksanaan |
| `[Mode Pelaksanaan]` | Online Zoom / Offline / Hybrid |
| `[URL_GAMBAR_SERTIFIKAT_1]` | Link gambar sertifikat kamu |
| `[Nomor Sertifikat Kamu]` | Nomor sertifikat resmi |
| `[Bulan Tahun]` | Bulan dan tahun sertifikat |
| `[Tahun]` | Tahun copyright |

### 3. Upload gambar sertifikat

Kamu bisa upload gambar sertifikat ke layanan gratis seperti:
- [Cloudinary](https://cloudinary.com) 
- [ImgBB](https://imgbb.com)
- [Postimages](https://postimages.org)

Lalu paste URL-nya di bagian `src="[URL_GAMBAR_SERTIFIKAT_X]"`.

### 4. Menambah / mengurangi slide sertifikat

Untuk **menambah** slide: duplikat blok `<!-- ══ SLIDE X ══ -->` dan ubah `id="sX"` serta nomor dot-nya.

Untuk **mengurangi** slide: hapus blok slide dan tombol dot yang tidak dipakai.

### 5. Buka di browser

Cukup buka file `.html` di browser kamu, atau host di GitHub Pages / Netlify secara gratis.

---

## 🌐 Deploy Gratis

| Platform | Cara |
|---|---|
| **GitHub Pages** | Upload ke repo → Settings → Pages → pilih branch |
| **Netlify** | Drag & drop folder ke [netlify.com/drop](https://app.netlify.com/drop) |
| **Vercel** | Import repo GitHub di [vercel.com](https://vercel.com) |

---

## 🎨 Kustomisasi Warna

Semua warna diatur lewat CSS variables di bagian `:root`. Kamu bisa ganti sesuai selera:

```css
:root {
  --bg:         #0D0C0A;   /* warna background utama */
  --gold:       #C9A84C;   /* warna aksen gold */
  --gold-light: #DFC07A;   /* gold lebih terang */
  --cream:      #F0EBE1;   /* warna teks utama */
}
```

---

## 📄 Lisensi

Template ini dirilis di bawah lisensi **MIT**, bebas dipakai, dimodifikasi, dan didistribusikan, dengan tetap mencantumkan atribusi. Lihat file `LICENSE` untuk detail lengkapnya.

---

> Dibuat dengan sama [@devxpxnyctrl](https://www.instagram.com/devxpxnyctrl_/) jangan lupa follow ig nya | feel free to use and share! 
