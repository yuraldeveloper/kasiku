# Kebijakan Privasi

**Terakhir diperbarui: 18 Juli 2026**

## 1. Pendahuluan

Yural Dev ("kami", "milik kami", atau "kita") mengoperasikan Kasiku ("Aplikasi"), sebuah aplikasi pencatatan keuangan pribadi. Kebijakan Privasi ini menjelaskan bagaimana kami mengumpulkan, menggunakan, menyimpan, dan melindungi informasi Anda saat menggunakan Aplikasi ini.

Dengan menggunakan Kasiku, Anda menyetujui praktik yang dijelaskan dalam Kebijakan Privasi ini. Jika Anda tidak setuju, harap hentikan penggunaan Aplikasi.

## 2. Informasi yang Kami Kumpulkan

Kasiku dirancang sebagai **aplikasi yang sepenuhnya offline**. Semua data disimpan secara lokal di perangkat Anda. Kami **tidak** mengumpulkan, mentransmisikan, atau menyimpan data apa pun di server eksternal.

### 2.1 Informasi yang Anda Berikan

Aplikasi menyimpan informasi berikut secara lokal di perangkat Anda:

| Kategori Data           | Data Spesifik                                                                                                                           | Tujuan                                           |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| **Transaksi Keuangan**  | Catatan pemasukan, pengeluaran, dan transfer termasuk jumlah, tanggal, waktu, kategori, dan aset terkait                                | Fungsi inti aplikasi — mencatat keuangan pribadi |
| **Informasi Aset**      | Nama aset, tipe (kas, bank, e-wallet, tabungan, kartu kredit, investasi, kripto, properti, kendaraan, dana pensiun, piutang), dan saldo | Menampilkan dan mengelola akun keuangan          |
| **Catatan Transaksi**   | Teks catatan dan deskripsi opsional yang dilampirkan pada transaksi                                                                     | Referensi dan konteks pengguna                   |
| **Kategori**            | Nama kategori kustom, ikon, dan warna untuk mengklasifikasikan transaksi                                                                | Pengkategorian transaksi                         |
| **Pengingat**           | Jadwal notifikasi termasuk label, waktu, dan hari pengulangan                                                                           | Fitur notifikasi berulang                        |
| **Preferensi Aplikasi** | Pilihan bahasa, pilihan mata uang, dan preferensi tampilan lainnya                                                                      | Personalisasi pengalaman pengguna                |

### 2.2 Informasi yang Dikumpulkan Secara Otomatis

Kami **tidak** secara otomatis mengumpulkan analitik, laporan kerusakan, statistik penggunaan, pengidentifikasi perangkat, atau data telemetri lainnya. Aplikasi tidak membuat permintaan jaringan apa pun dan beroperasi sepenuhnya secara offline.

### 2.3 Informasi dari Pihak Ketiga

Kami **tidak** terintegrasi dengan layanan analitik, periklanan, media sosial, atau penyimpanan cloud pihak ketiga mana pun. Kasiku tidak menggunakan SDK apa pun yang mengumpulkan atau mentransmisikan data ke pihak ketiga.

## 3. Bagaimana Kami Menggunakan Informasi Anda

Semua informasi yang disimpan di Kasiku digunakan semata-mata untuk menyediakan fitur-fitur Aplikasi:

- Merekam dan menampilkan transaksi keuangan
- Menghitung dan menampilkan saldo aset
- Menghasilkan ringkasan keuangan, grafik, dan laporan
- Menyediakan ekspor data dalam format CSV, Excel, dan PDF
- Membuat dan memulihkan cadangan (backup) JSON data Anda
- Menjadwalkan notifikasi lokal untuk pengingat
- Menyimpan preferensi bahasa dan mata uang Anda

## 4. Penyimpanan dan Keamanan Data

### 4.1 Lokasi Penyimpanan

Semua data disimpan secara lokal di perangkat Anda dalam:

- **Database SQLite** yang terletak di direktori data privat aplikasi
- **Shared Preferences** untuk pengaturan key-value ringan
- **Sistem file lokal** untuk file backup JSON dan dokumen yang diekspor

### 4.2 Keamanan Data

- Data Anda **tidak dienkripsi** saat disimpan di penyimpanan perangkat.
- Aplikasi **tidak menerapkan autentikasi perangkat** (PIN, kata sandi, atau biometrik) untuk mengakses data.
- Siapa pun dengan akses fisik ke perangkat Anda yang tidak terkunci mungkin dapat melihat data keuangan Anda.
- File backup dan ekspor disimpan sebagai file teks biasa di sistem file perangkat Anda.

### 4.3 Penyimpanan Berdasarkan Platform

| Platform | Lokasi Penyimpanan            |
| -------- | ----------------------------- |
| Android  | Penyimpanan internal aplikasi |

> **Catatan:** Kasiku saat ini tersedia untuk Android. Dukungan untuk platform tambahan (iOS, Web, Windows, Linux, macOS) akan diberikan di pembaruan mendatang. Kebijakan ini akan diperbarui sesuai dengan platform baru yang didukung.

## 5. Berbagi dan Pengungkapan Data

### 5.1 Tidak Ada Berbagi dengan Pihak Ketiga

Kasiku **tidak membagikan, menjual, menyewakan, atau mengungkapkan data pribadi Anda kepada pihak ketiga mana pun**. Aplikasi tidak membuat koneksi jaringan dan tidak memiliki infrastruktur server.

### 5.2 Berbagi yang Diprakarsai Pengguna

Anda dapat memilih untuk membagikan data Anda melalui fitur-fitur berikut, yang memerlukan tindakan eksplisit Anda:

- **Backup**: Anda dapat membuat file backup JSON dan memilih untuk menyimpan atau membagikannya melalui dialog berbagi sistem.
- **Ekspor**: Anda dapat mengekspor transaksi sebagai file CSV, Excel, atau PDF dan membagikannya melalui dialog berbagi sistem.
- **Berbagi File**: Saat berbagi, file ditangani oleh lembar berbagi asli perangkat Anda dan tunduk pada praktik privasi aplikasi penerima.

### 5.3 Persyaratan Hukum

Jika kami diwajibkan oleh hukum (seperti perintah pengadilan atau panggilan pengadilan yang sah) untuk mengungkapkan informasi Anda, kami akan melakukan upaya yang wajar untuk memberi tahu Anda, kecuali dilarang oleh hukum.

## 6. Retensi dan Penghapusan Data

### 6.1 Retensi

Data Anda tetap berada di perangkat Anda selama Anda tetap menginstal Aplikasi dan memilih untuk menyimpan data. Aplikasi tidak memberlakukan batasan retensi data apa pun.

### 6.2 Penghapusan

Anda dapat menghapus data Anda dengan cara berikut:

- **Catatan individu**: Hapus transaksi, aset, kategori, atau pengingat individual melalui antarmuka Aplikasi.
- **Hapus semua data**: Copot pemasangan Aplikasi untuk menghapus semua data lokal yang terkait. Perhatikan bahwa file backup yang dibuat sebelum pencopotan pemasangan mungkin tetap ada di sistem file perangkat Anda kecuali dihapus secara manual.
- **File backup**: Hapus file backup secara manual melalui layar Backup & Restore Aplikasi atau melalui pengelola file perangkat Anda.

### 6.3 Data Backup

File backup yang dibuat melalui Aplikasi tetap berada di perangkat Anda hingga Anda menghapusnya secara manual. Aplikasi menyimpan riwayat backup yang dapat dibersihkan kapan saja.

## 7. Hak Anda

Tergantung pada yurisdiksi Anda, Anda mungkin memiliki hak-hak berikut terkait data pribadi Anda:

| Hak                          | Deskripsi                                                                                          |
| ---------------------------- | -------------------------------------------------------------------------------------------------- |
| **Hak Akses**                | Anda dapat melihat semua data Anda di dalam Aplikasi kapan saja                                    |
| **Hak Koreksi**              | Anda dapat mengedit atau memperbaiki data apa pun melalui Aplikasi                                 |
| **Hak Penghapusan**          | Anda dapat menghapus catatan individu atau mencopot pemasangan Aplikasi untuk menghapus semua data |
| **Hak Portabilitas Data**    | Anda dapat mengekspor data Anda sebagai JSON (backup), CSV, Excel, atau PDF                        |
| **Hak Keberatan**            | Anda dapat berhenti menggunakan Aplikasi kapan saja                                                |
| **Hak Mencabut Persetujuan** | Anda dapat mencabut persetujuan dengan mencopot pemasangan Aplikasi                                |

Untuk menggunakan hak-hak ini, Anda dapat menggunakan fitur yang tersedia di dalam Aplikasi atau menghubungi kami menggunakan informasi di bawah.

## 8. Privasi Anak

Kasiku tidak ditujukan untuk anak-anak di bawah usia 13 tahun (atau usia persetujuan yang berlaku di yurisdiksi Anda). Kami tidak dengan sengaja mengumpulkan informasi pribadi dari anak-anak. Jika Anda yakin seorang anak telah memberikan data pribadi melalui Aplikasi, silakan hubungi kami agar kami dapat mengambil tindakan yang tepat.

## 9. Pengguna Internasional

Data Anda disimpan secara eksklusif di perangkat Anda dan tidak ditransfer lintas batas oleh kami. Namun, jika Anda memilih untuk membagikan atau mengekspor data, tindakan tersebut diprakarsai dan dikendalikan oleh Anda. Aplikasi tersedia di seluruh dunia dan mematuhi hukum privasi yang berlaku di yurisdiksi tempat penggunaannya, termasuk:

- **GDPR** (Wilayah Ekonomi Eropa)
- **CCPA/CPRA** (California, Amerika Serikat)
- **LGPD** (Brasil)
- **UU ITE** (Indonesia)
- **UU PDP** (Undang-Undang No. 27 Tahun 2022 tentang Perlindungan Data Pribadi)

## 10. Perubahan pada Kebijakan Privasi Ini

Kami dapat memperbarui Kebijakan Privasi ini dari waktu ke waktu. Perubahan akan diposting di Aplikasi dan/atau di repositori Aplikasi. Tanggal "Terakhir diperbarui" di bagian atas kebijakan ini mencerminkan perubahan terbaru.

Perubahan material akan dikomunikasikan melalui Aplikasi. Penggunaan Aplikasi yang berkelanjutan setelah perubahan merupakan penerimaan kebijakan yang diperbarui.

## 11. Hubungi Kami

Jika Anda memiliki pertanyaan, kekhawatiran, atau permintaan terkait Kebijakan Privasi ini, silakan hubungi kami:

- **Pengembang**: Yural Dev
- **Email**: yuraldeveloper@gmail.com

---

_Kebijakan Privasi ini disusun dengan mengacu pada standar privasi global termasuk General Data Protection Regulation (GDPR), California Consumer Privacy Act (CCPA), dan Undang-Undang Perlindungan Data Pribadi (UU PDP) Indonesia._
