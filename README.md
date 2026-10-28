<p align="center">
  <img src="banner.png" alt="Dwipa: Dynamic Island untuk Windows" width="100%">
</p>

<p align="center">
  <a href="../../releases/latest"><b>⬇ Unduh Dwipa untuk Windows</b></a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  Windows 10 & 11 (64-bit)
  &nbsp;&nbsp;|&nbsp;&nbsp;
  Gratis
</p>

---

**Dwipa** menaruh pil hitam kecil di tengah atas layar, seperti poni di iPhone dan MacBook. Saat diam ia hanya menampilkan jam atau lagu yang sedang diputar. Arahkan kursor ke atasnya, dan pil melebar menjadi panel berisi musik, lirik, kalender, timer, dan kontrol laptop. Klik di sekitar pil tetap tembus ke aplikasi di belakangnya, jadi tidak mengganggu kerja.

<p align="center">
  <img src="screenshots/ringkas-lirik.png" alt="Pil ringkas menampilkan lirik yang sedang dinyanyikan" width="420">
</p>

## Isinya

<table>
  <tr>
    <td width="50%"><img src="screenshots/musik.png" alt="Halaman musik"></td>
    <td width="50%"><img src="screenshots/beranda.png" alt="Halaman beranda dengan kalender"></td>
  </tr>
  <tr>
    <td><b>Musik.</b> Spotify, YouTube, VLC, dan pemutar lain. Ganti lagu, jeda, dan klik progres untuk loncat.</td>
    <td><b>Beranda.</b> Cuaca, agenda dari Google Calendar, kalender bulan ini, dan tombol cepat.</td>
  </tr>
  <tr>
    <td><img src="screenshots/sistem.png" alt="Halaman sistem"></td>
    <td><img src="screenshots/pintasan.png" alt="Halaman pintasan"></td>
  </tr>
  <tr>
    <td><b>Sistem.</b> CPU, RAM, dan kecepatan internet secara langsung.</td>
    <td><b>Pintasan.</b> Aplikasi, folder, dan situs favorit sekali klik.</td>
  </tr>
</table>

<p align="center">
  <img src="screenshots/lirik.png" alt="Mode lirik: pemutar di kiri, lirik bergulir di kanan" width="80%">
  <br><sub>Mode lirik: lirik bergulir mengikuti lagu, latar berwarna dari cover album.</sub>
</p>

**Juga ada:**

- Lirik berjalan di pil, sinkron dengan lagu
- Notifikasi WhatsApp, Telegram, dan email muncul di pil; klik untuk membuka aplikasinya
- Titik hijau/oranye saat kamera atau mikrofon sedang dipakai
- Pop-up volume dan kecerahan yang beranimasi
- TWS tersambung lengkap dengan baterainya
- Timer dan pomodoro
- Rak file (seret masuk, seret keluar) dan riwayat clipboard
- Shortcut `Win + Alt + Spasi` untuk membuka panel
- Sembunyi otomatis saat main game atau nonton layar penuh
- Update otomatis

<p align="center">
  <img src="screenshots/notifikasi.png" alt="Notifikasi WhatsApp di pil" width="460">
</p>

## Cara memasang

1. Buka halaman [**Releases**](../../releases/latest), unduh file `Dwipa_x.y.z_x64-setup.exe`.
2. Jalankan file itu. Kalau muncul layar biru **"Windows protected your PC"**, klik **More info → Run anyway**. Peringatan ini muncul karena Dwipa belum memakai sertifikat berbayar, bukan karena berbahaya.
3. Pil muncul di tengah atas layar. Klik kanan ikon Dwipa di system tray (pojok kanan bawah) → **Pengaturan…** untuk:
   - mengisi kota untuk cuaca,
   - menempelkan link kalender (Google Calendar → Setelan → *Alamat rahasia dalam format iCal*),
   - menyalakan **Jalankan saat Windows menyala**.
4. Saat Windows bertanya izin membaca notifikasi, pilih **Izinkan** supaya chat bisa muncul di pil.

Versi baru akan dipasang otomatis. Dwipa memberi tahu lewat pil saat ada pembaruan.

## Pertanyaan

**Apakah berat?**
Tidak. Dwipa memakai WebView2 bawaan Windows, dan animasi berhenti saat tidak terlihat. Data sistem hanya dihitung saat halamannya dibuka.

**Data saya dikirim ke mana?**
Tidak ke mana-mana. Notifikasi, clipboard, dan aktivitas kamera/mikrofon hanya dibaca di laptop sendiri. Yang mengakses internet hanya pencarian lirik ([LRCLIB](https://lrclib.net)), cuaca ([Open-Meteo](https://open-meteo.com)), link kalender yang kamu isi sendiri, dan pemeriksaan update.

**Liriknya tidak muncul?**
Tidak semua lagu ada di database lirik, terutama lagu yang kurang populer. Kalau liriknya terasa telat atau kecepatan, geser dengan tombol **− Timing +** di mode lirik.

**Bagaimana cara keluar atau menghapus?**
Klik kanan ikon Dwipa di tray → **Keluar**. Untuk menghapus: Pengaturan Windows → Aplikasi → Dwipa → Uninstall.
