# Permainan Tebak Angka '123'

Permainan tebakan angka sederhana berbasis web yang menggunakan **Web Storage API** (localStorage dan sessionStorage) untuk menyimpan data permainan dan data pengguna secara lokal di browser.

---

## Demo

> Klik tombol **Bermain** untuk memulai permainan.  
> Tebak kombinasi angka unik dari "1", "2", dan "3" sebanyak 3 digit, seperti "123", "312", dll.  
> Jangan ulangi angka dalam kombinasi tebakanmu!

---

## Fitur

- **Permainan Tebak Angka**  
  Menebak kombinasi unik dari angka "1", "2", dan "3" (3 digit).
  
- **Statistik Lokal**  
  Menyimpan jumlah kemenangan dan jumlah tebakan salah terbanyak dalam satu sesi, menggunakan `localStorage`.
  
- **Statistik Sesi**  
  Menampilkan jumlah tebakan salah selama sesi permainan berlangsung menggunakan `sessionStorage`.
  
- **Manajemen Data User**  
  Form input untuk menambah data user (nama, umur, domisili) yang tersimpan di `localStorage`.  
  Menampilkan daftar user dengan opsi hapus data.

- **UI Responsif**  
  Tampilan yang menyesuaikan pada perangkat desktop maupun mobile.

- **Fitur Hapus Data**  
  Tombol untuk menghapus data permainan dan data user secara terpisah dari `localStorage`.

---

## Cara Main

1. Klik tombol **Bermain** untuk memulai sesi baru.
2. Klik tombol angka 1, 2, dan 3 untuk membentuk tebakan kombinasi angka 3 digit unik.
3. Jika tebakan benar, skor kemenangan bertambah dan permainan berakhir.
4. Jika tebakan salah, jumlah tebakan salah bertambah dan Anda dapat coba lagi.
5. Gunakan tombol **Main Lagi** untuk memulai ulang permainan.
6. Tambahkan data user baru melalui form yang tersedia.
7. Anda dapat menghapus semua data permainan atau user kapan saja.

---

## Teknologi yang Digunakan

- HTML5, CSS3 (desain responsif)
- Vanilla JavaScript
- Web Storage API (`localStorage` & `sessionStorage`)

---

## Cara Menjalankan

1. Clone repository ini  
   ```bash
   git clone https://github.com/Adityabeckham/Web-Storage-Game/
