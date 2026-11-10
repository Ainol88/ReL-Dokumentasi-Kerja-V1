# ReL Dokumentasi Kerja V1.0 — Starter

Proyek Android WebView untuk dokumentasi kegiatan:
- Judul kegiatan
- Pilih hingga 4 foto
- Geser dan ubah ukuran foto pada editor
- Reset tata letak
- Ekspor PDF lokal

## Status
Ini adalah fondasi/prototipe tahap pertama. Tombol Google Drive belum aktif. Integrasi Drive memerlukan konfigurasi OAuth resmi (Google Cloud project, OAuth Android client/package + SHA-1, dan izin Drive yang sesuai). Jangan memasukkan password Gmail ke aplikasi.

## Build APK
Build menggunakan GitHub Actions atau Android Gradle Plugin 8.7.3, JDK 17, Gradle 8.9+.
Aplikasi ini belum menyertakan Gradle Wrapper. Workflow CI dapat memasang Gradle 8.9.

## Catatan
Ekspor PDF menggunakan jsPDF dari CDN, sehingga koneksi internet diperlukan saat membuka fitur ekspor pada prototipe ini.
