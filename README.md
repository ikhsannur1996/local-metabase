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

![Screenshot (407)](https://github.com/user-attachments/assets/89474a21-4240-48c9-9205-8e4c9c9df738)
Klik kanan dan klik Open in Terminal

Jalankan file JAR Metabase dari terminal:

```bash
java -jar metabase.jar
```
![Screenshot (408)](https://github.com/user-attachments/assets/505f0ac4-71cc-4a63-9654-4a7d6f537a7c)
Tekan tombol enter di Keyboard untuk menjalankan Metabase

![Screenshot (409)](https://github.com/user-attachments/assets/70d3d556-0926-457e-bfa3-02fccebd9837)
Jika muncul pop up klik Allow

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

![Screenshot (412)](https://github.com/user-attachments/assets/f572bfc3-ddbc-4a52-9330-7001679cab88)
Inisialisasi Metabase Selesai

Sekarang Anda siap untuk menggunakan Metabase Anda di port 3000, biasanya di http://localhost:3000.

## Konfigurasi Metabase
Buka browser dan ketik http://localhost:3000 kemudian enter. Akan muncul tampilan Metabase sebagai berikut.
![Screenshot (413)](https://github.com/user-attachments/assets/079a9b3d-a720-4b2c-a743-5d7a64d231fd)
Klik Let's get started.

![Screenshot (414)](https://github.com/user-attachments/assets/39ee9711-c52b-4383-9dfc-f15bb363d492)
Pilih bahasa Inggris dan klik Next

![Screenshot (415)](https://github.com/user-attachments/assets/d59ef678-988e-4182-97df-4c43602e36d0)
Isikan Nama, Email dan Password kemudian Klik Next

![Screenshot (416)](https://github.com/user-attachments/assets/cf077ebf-d4cf-4e5f-ad65-96ba1077529e)
Biarkan default dan klik Next

![Screenshot (417)](https://github.com/user-attachments/assets/34ec0706-2e90-4ee7-917d-960bc1b1c6a5)
Klik I'll add my data later

![Screenshot (418)](https://github.com/user-attachments/assets/515cbe65-2069-4275-871b-f9b84a524d41)
Klik Finish

![Screenshot (419)](https://github.com/user-attachments/assets/7bb16f8c-de3c-4478-b121-96b0ca5f2cab)
Klik Take me to Metabase

![Screenshot (420)](https://github.com/user-attachments/assets/725747fa-9dca-41fa-b3ed-b17a8478ecb8)
Tampilan antar muka Metabase akan terbuka

