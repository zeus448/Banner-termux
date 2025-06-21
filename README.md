# ⚡ Termux Setup Otomatis & Personalisasi - ZEUS CODING ⚡

Selamat datang di repositori setup Termux pribadi milik ZEUS CODING!

Skrip ini dirancang untuk mengotomatiskan proses instalasi dan personalisasi Termux di perangkat Android-mu, menjadikannya siap untuk petualangan ngoding dan eksplorasi dunia Linux.

## ✨ Fitur Utama

Skrip ini akan melakukan hal-hal berikut:

-   **Pembaruan & Upgrade Sistem:** Memastikan semua paket Termux-mu up-to-date.
-   **Instalasi Paket Esensial:** Menginstal alat-alat penting seperti `git`, `python`, `nano`, `neofetch`, `figlet`, dan `toilet`.
-   **Akses Penyimpanan Internal:** Mengaktifkan akses Termux ke penyimpanan internal ponselmu (membutuhkan izin manual).
-   **Pembuatan Direktori Kerja:** Membuat folder dasar seperti `projects`, `scripts`, dan `documents` di direktori `home` Termux-mu.
-   **Banner Kustom Zeus Coding:** Menambahkan hiasan terminal yang menarik dengan nama "ZEUS CODING" setiap kali kamu membuka Termux.
-   **Link Facebook Zeus Coding:** Menyertakan link ke profil Facebook "Zeus Coding" di pesan sambutan terminal.

## 🚀 Cara Menggunakan

Ikuti langkah-langkah sederhana ini untuk menjalankan skrip di Termux-mu:

1.  **Buka Aplikasi Termux:** Pastikan kamu sudah menginstal aplikasi Termux di perangkat Android-mu.
2.  **Salin Seluruh Skrip:** Salin seluruh isi dari skrip `setup_termux_zeus.sh` ini.
    (Jika kamu mendownload dari GitHub, kamu bisa langsung menjalankan file ini.)
3.  **Tempel & Jalankan:**
    -   Jika kamu menyalin teksnya: Tempelkan seluruh teks skrip ke terminal Termux, lalu tekan `Enter`.
    -   Jika kamu memiliki file `.sh`: Pindahkan file tersebut ke Termux (misalnya ke `~/downloads`), lalu berikan izin eksekusi dan jalankan:
        ```bash
        chmod +x ~/downloads/setup_termux_zeus.sh
        bash ~/downloads/setup_termux_zeus.sh
        ```
4.  **Berikan Izin Penyimpanan:** Saat skrip berjalan, akan muncul pop-up izin di layar ponselmu. **Sangat penting untuk memberikan izin penyimpanan** agar Termux dapat mengakses file di memori internal.
5.  **Restart Termux:** Setelah skrip selesai, **tutup aplikasi Termux sepenuhnya** (dari daftar aplikasi yang baru dibuka atau paksa berhenti), lalu **buka kembali**. Kamu akan melihat hiasan "ZEUS CODING" dan pesan sambutanmu!

## ⚙️ Kustomisasi

Kamu bisa mengkustomisasi banner dan pesan sambutanmu dengan mengedit file `.bashrc`:

1.  Buka file `.bashrc` dengan `nano`:
    ```bash
    nano ~/.bashrc
    ```
2.  Cari bagian yang diawali dengan `## Custom Zeus Coding Banner Start ##` dan diakhiri dengan `## Custom Zeus Coding Banner End ##`.
3.  Di sini kamu bisa mengubah teks, warna (`--filter metal`, `--gay`, dll.), dan font (`-f standard`, `-f big` untuk `figlet`; `--font mono1`, `-f term` untuk `toilet`).
4.  Setelah selesai mengedit, tekan `Ctrl + X`, lalu `Y` (untuk menyimpan), lalu `Enter`.
5.  Tutup dan buka kembali Termux untuk melihat perubahannya.

## 🔗 Terhubung dengan Zeus Coding

Jangan lupa untuk mengikuti akun Facebook Zeus Coding untuk update dan konten menarik lainnya!

[https://www.facebook.com/share/19EornyQgz/](https://www.facebook.com/share/19EornyQgz/)

---

Selamat berpetualang di Termux, Sang Penguasa Kode!

---
