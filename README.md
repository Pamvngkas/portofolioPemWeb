# Portofolio Pamvngkas

## Deskripsi
Website portofolio ini dibuat sebagai tugas akhir praktikum Pemrograman Web.  
Menampilkan profil, daftar proyek, keahlian, dan kontak.

## Teknologi
- HTML5  
- CSS3  
- Git & GitHub  

## Cara Menjalankan
1. Clone repository:
   git clone https://github.com/username/portofolioPemWeb.git
2. Masuk ke folder proyek:
   cd portofolioPemWeb
3. Buka file index.html di browser.

## Struktur Folder
- index.html — halaman utama portofolio  
- style.css — file gaya tampilan  
- README.md — dokumentasi proyek  

## Kontribusi
Melakukan git commit -m "teks" untuk setiap section yang di edit atau di tambahkan
Buat branch baru untuk setiap fitur baru:
   git switch -c experimental-styiling
Setelah selesai, merge kembali ke main dengan git push origin main

## Error
Pada merging pertama dari branch experimental/styiling terjadi fast forward yang membuat branch tidak di anggap dan menghasilkan graph yang tidak bercabang (tidak tau kenapa)
Hal ini sudah di coba ulang dengan membuat cabang baru bernama feature/test-branch untuk menampilkan merging pada --graph

