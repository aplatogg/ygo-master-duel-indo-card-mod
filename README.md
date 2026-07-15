[README.md](https://github.com/user-attachments/files/30062966/README.md)
# 🎮 Yu-Gi-Oh! Master Duel - Mod Bahasa Indonesia (v1.1)

Mod praktis untuk menerjemahkan deskripsi dan efek kartu Yu-Gi-Oh! Master Duel ke dalam **Bahasa Indonesia** secara aman, otomatis, dan sinkron 100%.

---

## 🌟 Fitur Utama Mod
*   **Efek Kartu Bahasa Indonesia:** Memudahkan pemahaman efek kartu yang panjang dan kompleks.
*   **Nama Kartu Tetap Bahasa Inggris:** Memudahkan pencarian kartu di Deck Builder sesuai nama kartu internasional (tidak membingungkan).
*   **Indeks Sinkron (Anti-Bug):** Penyelarasan biner otomatis untuk mencegah teks tergeser/scrambled atau game crash saat duel.
*   **Aman dari Anti-Cheat (EAC):** Mod ini bekerja secara *client-side* hanya pada file aset teks (`TextAsset`). Tidak memodifikasi file sistem (`.exe`/`.dll`), sehingga **100% AMAN dari banned**.
*   **Fitur Restore Sekali Klik:** Kembalikan game ke bahasa asli (Inggris) kapan saja dengan mudah.

---

## 📦 Cara Pemasangan (Sangat Mudah!)

> ⚠️ **PENTING:** Pastikan game **Yu-Gi-Oh! Master Duel dalam keadaan TUTUP (TIDAK SEDANG BERMAIN)** sebelum melakukan instalasi mod.

### 1. Langkah Pemasangan Mod:
1.  Unduh berkas **`gui_installer.exe`** dari tab **Releases** repositori ini (atau gunakan yang ada di folder portabel).
2.  Jalankan **`gui_installer.exe`**.
3.  Program akan otomatis mencari folder game Master Duel Anda. Jika tidak ditemukan, klik **CARI FOLDER** dan arahkan ke direktori instalasi Steam Anda (contoh: `C:\Program Files (x86)\Steam\steamapps\common\Yu-Gi-Oh!  Master Duel`).
4.  Klik tombol emas **PASANG MOD INDONESIA**.
5.  Tunggu hingga muncul notifikasi sukses **"Mod Bahasa Indonesia berhasil dipasang!"**.
6.  Tutup installer, buka Steam, dan jalankan gamenya! 🎉

### 2. Cara Mengembalikan ke Bahasa Inggris Asli:
Jika Anda ingin menghapus mod dan mengembalikan file game ke kondisi original:
1.  Buka kembali **`gui_installer.exe`**.
2.  Klik tombol merah **PULIHKAN GAME ASLI (RESTORE)**.
3.  Game Anda akan kembali bersih 100% ke versi Inggris bawaan Steam.

---

## 💡 Catatan & Solusi Masalah (FAQ)

*   **T: Apakah saya harus membuka Installer setiap kali ingin bermain?**
    *   **J:** Tidak. Anda cukup menjalankan installer **sekali saja**. Mod akan terpasang permanen di game Anda.
*   **T: Apa yang terjadi jika game Master Duel melakukan update di Steam?**
    *   **J:** Steam akan otomatis mengembalikan file game ke versi bahasa Inggris asli. Jika ini terjadi, Anda cukup membuka kembali **`gui_installer.exe`** dan klik **PASANG MOD INDONESIA** lagi.
*   **T: Bagaimana jika ada kartu baru yang dirilis setelah update?**
    *   **J:** Kartu baru tersebut akan tetap tampil dalam Bahasa Inggris, sedangkan kartu lama tetap dalam Bahasa Indonesia. Game tidak akan crash karena mod ini dirancang toleran terhadap pembaruan kartu.

---

## 🛠️ Panduan Developer (Menjalankan via Source Code)

Jika Anda ingin memodifikasi atau menjalankan installer ini langsung menggunakan Python:

### Prasyarat:
*   Windows 10/11
*   Python **3.8 atau versi lebih baru**

### Cara Menjalankan:
1.  Clone repositori ini:
    ```bash
    git clone https://github.com/aplatogg/ygo-master-duel-indo-card-mod
    cd REPO-NAME
    ```
2.  Buat virtual environment dan aktifkan:
    ```bash
    python -m venv .venv
    .venv\Scripts\activate
    ```
3.  Instal pustaka yang dibutuhkan:
    ```bash
    pip install UnityPy
    ```
4.  Jalankan skrip GUI:
    ```bash
    python gui_installer.py
    ```
