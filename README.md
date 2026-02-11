# 🚀 CI/CD Pipeline

Repositori ini menggunakan **GitHub Actions** untuk mengotomatisasi proses build dan testing setiap kali ada perubahan kode.

## ⚙️ Workflow Overview
Pipeline ini akan berjalan secara otomatis untuk memastikan integritas kode.

* **Build**: Memastikan project dapat di-compile tanpa error (Gradle Build).
* **Unit Test**: Menjalankan pengujian otomatis untuk memverifikasi logika aplikasi.
* **Lint Check**: Memeriksa gaya penulisan kode (Code Style) agar sesuai standar Kotlin/Android.

## trigger 🎯
Pipeline akan berjalan otomatis ketika:
1.  **Push** ke branch `main` atau `master`.
2.  **Pull Request** dibuka ke branch utama.
