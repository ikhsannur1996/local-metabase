# Menginstal Metabase Lokal

## Instalasi Java JRE

Sebelum memulai, pastikan Java JRE 11 sudah terinstal di komputer Anda. Anda dapat memeriksa versi Java dengan menjalankan perintah berikut di terminal/CMD:

```bash
java -version
```

Jika Java belum terinstal, Anda harus menginstalnya terlebih dahulu. Kami merekomendasikan versi 11 dari [JRE Eclipse Temurin](https://adoptium.net/) dengan JVM HotSpot. Metabase dapat dijalankan di mana saja yang mendukung Java 11, termasuk arsitektur prosesor x86 dan ARM.

Download Java:
https://adoptium.net/

## Unduh Metabase

Unduh file JAR Metabase dari situs resmi.
[https://www.metabase.com/start/oss/jar](https://www.metabase.com/start/oss/jar)

## Buat Direktori Baru dan Pindahkan File JAR Metabase ke Dalamnya

Buat direktori baru dan pindahkan file JAR Metabase ke dalamnya. Ini penting agar Metabase tidak menciptakan file baru di direktori unduhan Anda.

## Ke Direktori Baru dan Jalankan File JAR

Ke direktori yang Anda buat di langkah sebelumnya:
Jalankan file JAR Metabase dari terminal:

```bash
java -jar metabase.jar
```

Metabase akan mulai berjalan menggunakan pengaturan default. Anda akan melihat entri log mulai berjalan di jendela terminal Anda, menunjukkan kemajuan aplikasi. Setelah Metabase selesai diinisialisasi, Anda akan melihat konfirmasi seperti ini:

```
06-19 10:29:34 INFO metabase.task :: Initializing task CheckForNewVersions
06-19 10:29:34 INFO metabase.task :: Initializing task SendAnonymousUsageStats
06-19 10:29:34 INFO metabase.task :: Initializing task SendAbandomentEmails
06-19 10:29:34 INFO metabase.task :: Initializing task SendPulses
06-19 10:29:34 INFO metabase.task :: Initializing task SendFollowUpEmails
06-19 10:29:34 INFO metabase.task :: Initializing task TaskHistoryCleanup
06-19 10:29:34 INFO metabase.core :: Metabase Initialization COMPLETE
```
Sekarang Anda siap untuk menggunakan Metabase Anda di port 3000, biasanya di http://localhost:3000.
