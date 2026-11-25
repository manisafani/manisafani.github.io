# Portofolio Manisa Fani Rahmasari

Website portofolio statis menggunakan HTML, CSS, dan JavaScript.

## Isi folder
- `index.html` — halaman utama website.
- `assets/` — tempat menyimpan foto profesional.

## Cara mengganti placeholder foto
1. Siapkan foto profesional berbentuk JPG atau PNG.
2. Ubah nama file menjadi `foto-manisa.jpg`.
3. Simpan file tersebut ke folder `assets`.
4. Buka `index.html`, cari blok `div class="portrait"` di bagian Hero.
5. Ganti isi blok tersebut dengan:
   `<img src="assets/foto-manisa.jpg" alt="Foto profesional Manisa Fani Rahmasari" style="width:100%;height:100%;object-fit:cover;border-radius:inherit;">`
6. Simpan perubahan.

## Publikasi melalui GitHub Pages
1. Buat repository publik bernama `manisafani.github.io` (jika username GitHub memang `manisafani`).
2. Unggah `index.html` dan folder `assets` ke root repository.
3. Buka Settings > Pages.
4. Pada Build and deployment, pilih Deploy from a branch.
5. Pilih branch `main` dan folder `/ (root)`, lalu Save.
6. Tunggu proses publikasi, lalu buka `https://manisafani.github.io`.

## Catatan konten
Empat proyek di bagian Projects adalah simulasi konseptual dengan data fiktif, bukan dokumen resmi atau klaim hasil kerja dari perusahaan/instansi. Periksa kembali seluruh informasi dan tautan sebelum website dipublikasikan.
