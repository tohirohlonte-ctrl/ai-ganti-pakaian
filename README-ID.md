# AI Ganti Pakaian — Android APK via cloud build

Project Android ini bisa dibuild menjadi APK melalui GitHub Actions tanpa memasang Android Studio di HP/komputer.

## Cara mendapatkan APK
1. Buat akun / masuk ke GitHub.
2. Buat repository baru, misalnya `ai-ganti-pakaian`.
3. Upload seluruh isi folder ZIP ini ke repository (jangan upload ZIP-nya saja).
4. Buka tab **Actions** → workflow **Build Android APK** → **Run workflow**.
5. Setelah selesai, buka hasil run dan unduh artifact **AI-Ganti-Pakaian-APK**. Di dalam ZIP artifact terdapat `app-debug.apk`.
6. Pindahkan APK ke HP Android dan buka untuk memasang. Android mungkin meminta izin memasang aplikasi dari sumber ini.

## Batasan penting
- Ini adalah APK Android yang menampilkan antarmuka aplikasi dan dapat memilih foto.
- Fitur AI untuk mengubah pakaian belum tersambung ke layanan image-edit. Agar benar-benar mengganti pakaian, backend AI dan endpoint perlu dikonfigurasi.
- Jangan memasukkan API key rahasia ke aplikasi Android.
