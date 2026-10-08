# Project Bulanan — GitHub Pages

Paket aplikasi siap untuk GitHub Pages. Belum diterbitkan.

## Publikasi dari browser
1. Buat repository baru bernama `project-bulanan`. Untuk GitHub Free, gunakan repository Public.
2. Ekstrak ZIP ini. Pilih Add file → Upload files di repository. Upload seluruh isi folder hasil ekstraksi, termasuk `index.html`, `sw.js`, `manifest.webmanifest`, kedua ikon dan `.nojekyll`, langsung di akar repository, bukan di subfolder.
3. Commit ke branch `main`.
4. Buka Settings → Pages → Source: Deploy from a branch → Branch: main → Folder: /(root) → Save.
5. Tunggu GitHub menampilkan alamat situs. Aktifkan Enforce HTTPS bila tersedia.
6. Buka alamat yang ditampilkan GitHub lewat Safari. Bagikan → Tambahkan ke Layar Utama. Buka lagi dari ikon tersebut saat online sebelum mencoba mode pesawat.

## Memindahkan data
Di aplikasi lama pilih Unduh cadangan. Di aplikasi baru pilih Pulihkan cadangan lalu pilih file JSON tadi. Gambar dan note ikut dalam cadangan. Alamat baru memiliki penyimpanan browser sendiri; data tidak pindah otomatis dan tidak disinkronkan antar HP.

## Akses dan penyimpanan
Situs dan source code di GitHub Pages ini dapat dibuka publik dan tidak memiliki login ChatGPT. Isi catatan project dan gambar disimpan lokal oleh aplikasi, bukan dikirim ke GitHub. Jangan upload file cadangan JSON atau foto project ke repository. Data lokal belum dienkripsi oleh aplikasi. Menghapus data situs dapat menghapus catatan; unduh cadangan rutin.

File `.nojekyll` mungkin disembunyikan pengelola file; paket ini hanya berisi aset statis, sehingga situs tetap dapat berjalan jika file tersebut terlewat.

Dokumentasi: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
