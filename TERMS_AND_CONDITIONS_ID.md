# Syarat dan Ketentuan

**Terakhir diperbarui: 13 November 2026**

## 1. Penerimaan Syarat

Dengan mengunduh, menginstal, atau menggunakan Kasiku ("Aplikasi"), Anda menyetujui untuk terikat oleh Syarat dan Ketentuan ("Syarat") ini. Jika Anda tidak menyetujui Syarat ini, jangan menginstal, menggunakan, atau mengakses Aplikasi.

Syarat ini merupakan perjanjian yang mengikat secara hukum antara Anda ("Pengguna" atau "Anda") dan Yural Dev ("Pengembang", "kami", "milik kami", atau "kita").

## 2. Deskripsi Layanan

Kasiku adalah aplikasi pencatatan keuangan pribadi yang memungkinkan pengguna untuk:

- Mencatat pemasukan, pengeluaran, dan transfer antar aset keuangan
- Mengelola akun keuangan di 11 tipe aset (kas, bank, e-wallet, tabungan, kartu kredit, investasi, kripto, properti, kendaraan, dana pensiun, piutang)
- Mengatur transaksi dengan kategori yang dapat disesuaikan
- Mencari dan memfilter transaksi berdasarkan catatan, kategori, aset, tipe, dan periode
- Melampirkan hingga 5 foto per transaksi dari kamera atau galeri (disimpan lokal)
- Melihat ringkasan keuangan, grafik, laporan, dan analitik lokal (skor keuangan, tren, proyeksi, deteksi kebiasaan)
- Mengekspor data ke format CSV, Excel, dan PDF, termasuk ringkasan analitik ke PDF
- Membuat dan memulihkan cadangan (backup) data JSON terenkripsi (opsional dilindungi PIN pilihan Anda)
- Mengatur notifikasi pengingat berulang
- Mengunci aplikasi dengan PIN 6 digit dan/atau biometrik secara opsional
- Menggunakan antarmuka dalam bahasa Indonesia atau Inggris dengan 6 pilihan mata uang

**Aplikasi** adalah pelacak keuangan yang mengutamakan penyimpanan lokal. Data keuangan Anda selalu tetap berada di perangkat Anda sendiri. Kasiku tidak menyinkronkan data pribadi Anda ke cloud dan tidak terhubung ke infrastruktur server Yural Dev. Namun, Aplikasi menampilkan iklan melalui **Google AdMob** (banner dan interstitial), yang hanya memerlukan koneksi internet untuk pengiriman iklan dan, bila diperlukan, formulir persetujuan UMP Google. Tidak ada data keuangan yang dikirim ke jaringan iklan.

## 3. Lisensi

### 3.1 Pemberian Lisensi

Dengan tunduk pada kepatuhan Anda terhadap Syarat ini, Pengembang memberikan Anda lisensi terbatas, dapat dibatalkan, non-eksklusif, tidak dapat dialihkan, dan tidak dapat disublisensikan untuk mengunduh, menginstal, dan menggunakan Aplikasi untuk tujuan pribadi dan non-komersial Anda.

### 3.2 Pembatasan

Anda tidak diperbolehkan untuk:

- Menyalin, memodifikasi, mengadaptasi, menerjemahkan, melakukan rekayasa balik, mendekompilasi, atau membongkar Aplikasi
- Membuat karya turunan berdasarkan Aplikasi
- Menghapus, mengubah, atau mengaburkan hak cipta, merek dagang, atau pemberitahuan kepemilikan lainnya
- Menyewakan, meminjamkan, menjual, mensublisensikan, menugaskan, atau mentransfer Aplikasi
- Menggunakan Aplikasi untuk tujuan ilegal atau tidak sah
- Menggunakan Aplikasi dengan cara yang melanggar hukum lokal, nasional, atau internasional yang berlaku
- Mendistribusikan, mempublikasikan, atau membuat Aplikasi tersedia melalui jaringan di mana Aplikasi dapat digunakan oleh beberapa perangkat secara bersamaan

## 4. Tanggung Jawab Pengguna

### 4.1 Keakuratan Data

Anda sepenuhnya bertanggung jawab atas keakuratan, kelengkapan, dan keandalan semua data yang Anda masukkan ke dalam Aplikasi, termasuk data transaksi, aset, kategori, catatan, dan foto. Pengembang tidak memverifikasi, memvalidasi, atau mendukung informasi keuangan apa pun yang Anda catat.

### 4.2 Cadangan Data

Anda sangat dianjurkan untuk secara teratur membuat cadangan data menggunakan fitur backup bawaan Aplikasi. File backup dienkripsi, dan Anda dapat memilih PIN 4–6 digit untuk perlindungan tambahan. Pengembang tidak bertanggung jawab atas kehilangan data akibat kegagalan perangkat, penghapusan tidak sengaja, kerusakan Aplikasi, PIN yang lupa, atau penyebab lainnya. Jika Anda lupa PIN backup, file tersebut tidak dapat dipulihkan.

### 4.3 Keamanan Perangkat dan Data

- Anda bertanggung jawab untuk menjaga keamanan perangkat Anda dan data apa pun yang disimpan di dalam Aplikasi.
- Database internal Aplikasi **tidak dienkripsi**. Aplikasi menyediakan **kunci aplikasi opsional** berupa PIN 6 digit dan/atau biometrik. PIN disimpan sebagai hash SHA-256, bukan teks biasa, dan sesi verifikasi berlaku selama 2 jam setelah berhasil.
- Kunci aplikasi adalah kontrol akses, **bukan enkripsi database**. Kunci ini tidak melindungi data dari akses langsung ke penyimpanan perangkat, perangkat yang di-root, malware, atau sistem operasi yang disusupi.
- Data biometrik tidak pernah disimpan oleh Aplikasi; verifikasi biometrik ditangani oleh sistem operasi perangkat Anda.
- PIN kunci aplikasi tidak dapat dipulihkan jika lupa. Anda bertanggung jawab untuk mengingat PIN tersebut; menghapus data Aplikasi akan menghapus data lokal, dan backup menyertakan pengaturan kunci aplikasi.
- File backup dienkripsi secara default (AES-256-GCM). Backup tanpa PIN menggunakan kunci yang diturunkan dari rahasia bawaan Aplikasi; backup dengan PIN memberikan perlindungan yang lebih kuat. Anda sepenuhnya bertanggung jawab untuk menjaga PIN backup Anda.
- Foto transaksi disimpan secara lokal di penyimpanan privat Aplikasi, tidak diunggah, tidak diekspor, dan tidak disertakan dalam backup. Anda bertanggung jawab atas isi foto serta izin dari orang yang mungkin muncul di dalamnya.
- Dokumen hasil ekspor (CSV, Excel, PDF) tidak dienkripsi dan dapat dibaca oleh aplikasi lain jika Anda membagikannya. Berhati-hatilah saat menyimpan atau membagikan file tersebut.

### 4.4 Kepatuhan terhadap Hukum

Anda setuju untuk menggunakan Aplikasi sesuai dengan semua hukum dan peraturan yang berlaku di yurisdiksi Anda.

## 5. Kekayaan Intelektual

Aplikasi, termasuk namun tidak terbatas pada kode, desain, tata letak, grafik, logo, dan antarmuka penggunanya, adalah kekayaan intelektual Yural Dev dan dilindungi oleh hak cipta, merek dagang, dan hukum kekayaan intelektual lainnya yang berlaku.

Nama, logo, dan identitas merek Kasiku adalah aset kepemilikan. Anda tidak boleh menggunakannya tanpa izin tertulis sebelumnya dari Pengembang.

## 6. Privasi

Penggunaan Aplikasi Anda diatur oleh Kebijakan Privasi kami, yang tergabung dalam Syarat ini sebagai referensi. Harap tinjau Kebijakan Privasi untuk memahami praktik kami terkait data Anda.

## 7. Layanan Pihak Ketiga

Kasiku terintegrasi dengan layanan pihak ketiga berikut semata-mata untuk menampilkan iklan:

- **Google AdMob** — Layanan periklanan pihak ketiga oleh Google yang menyediakan iklan banner dan interstitial yang ditampilkan di Aplikasi. Pengiriman iklan dapat mengirimkan informasi perangkat dan penggunaan standar (seperti ID iklan Anda, alamat IP, dan model perangkat) kepada Google untuk tujuan penyajian dan pengukuran iklan, sesuai dengan Kebijakan Privasi Google dan, jika diperlukan (misalnya di EEA, Inggris, dan Swiss), setelah memperoleh persetujuan Anda melalui User Messaging Platform Google. Data keuangan Anda **tidak pernah** dibagikan kepada Google atau jaringan iklan mana pun.

Layanan sistem operasi berikut digunakan semata-mata untuk menyediakan fungsi inti:

- **Notifikasi lokal**: Untuk menjadwalkan pengingat (tidak ada data yang dikirim secara eksternal)
- **Biometrik**: Untuk membuka kunci Aplikasi melalui autentikasi sistem operasi (data biometrik tidak pernah disimpan oleh Aplikasi)
- **Kamera dan galeri**: Untuk melampirkan foto transaksi atas tindakan Anda
- **Berbagi file (lembar berbagi sistem)**: Untuk berbagi file backup dan ekspor yang diprakarsai pengguna
- **Pemilih file**: Untuk pemilihan file yang diprakarsai pengguna selama operasi pemulihan

Layanan-layanan sistem operasi ini beroperasi sepenuhnya di perangkat Anda. Satu-satunya komunikasi jaringan yang terjadi adalah pengiriman iklan yang dijelaskan di atas; data keuangan Anda tidak pernah dikirimkan ke Pengembang atau pihak ketiga mana pun.

## 8. Penyangkalan Jaminan

**APLIKASI INI DISEDIAKAN "SEBAGAIMANA ADANYA" DAN "SESUAI KETERSEDIAAN" TANPA JAMINAN DALAM BENTUK APA PUN, BAIK TERSURAT MAUPUN TERSIRAT, TERMASUK NAMUN TIDAK TERBATAS PADA:**

- **JAMINAN TERSIRAT TENTANG DAPAT DIPERDAGANGKAN, KESESUAIAN UNTUK TUJUAN TERTENTU, DAN TIDAK MELANGGAR HAK PIHAK KETIGA**
- **JAMINAN BAHWA APLIKASI AKAN BERJALAN TANPA GANGGUAN, BEBAS DARI KESALAHAN, AMAN, ATAU BEBAS DARI CACAT**
- **JAMINAN MENGENAI KEAKURATAN, KEANDALAN, ATAU KELENGKAPAN PERHITUNGAN KEUANGAN ATAU LAPORAN YANG DIHASILKAN OLEH APLIKASI**

**ANALITIK, SKOR KEUANGAN, PROYEKSI, DAN INSIGHT ADALAH ESTIMASI INFORMATIF YANG DIHITUNG DARI DATA YANG ANDA MASUKKAN. HASILNYA DAPAT TIDAK AKURAT, TIDAK LENGKAP, ATAU BERUBAH SEIRING WAKTU, DAN BUKAN MERUPAKAN JAMINAN ATAS KONDISI KEUANGAN ANDA DI MASA DEPAN.**

PENGEMBANG TIDAK MEMBERIKAN NASIHAT KEUANGAN. APLIKASI INI ADALAH ALAT UNTUK MENCATAT DAN MENGORGANISASI INFORMASI KEUANGAN DAN TIDAK BOLEH DIANDALKAN UNTUK MEMBUAT KEPUTUSAN KEUANGAN. ANDA HARUS BERKONSULTASI DENGAN PROFESIONAL KEUANGAN YANG BERKUALIFIKASI UNTUK MENDAPATKAN NASIHAT KEUANGAN.

## 9. Batasan Tanggung Jawab

**SAMPAI BATAS MAKSIMUM YANG DIIZINKAN OLEH HUKUM YANG BERLAKU, DALAM KEADAAN APA PUN PENGEMBANG TIDAK BERTANGGUNG JAWAB ATAS:**

- **KERUGIAN LANGSUNG, TIDAK LANGSUNG, INSIDENTAL, KHUSUS, KONSEKUENSIAL, ATAU HUKUMAN**
- **KEHILANGAN DATA, KEHILANGAN KEUNTUNGAN, KEHILANGAN BISNIS, ATAU KEHILANGAN GOODWILL**
- **KERUGIAN AKIBAT PENGGUNAAN ATAU KETIDAKMAMPUAN ANDA MENGGUNAKAN APLIKASI**
- **KERUGIAN AKIBAT AKSES TIDAK SAH KE PERANGKAT ATAU DATA ANDA**
- **KLAIM BERDASARKAN KEAKURATAN ATAU KEANDALAN DATA KEUANGAN YANG DIMASUKKAN ATAU DIHITUNG OLEH APLIKASI, TERMASUK ANALITIK, SKOR, PROYEKSI, DAN INSIGHT**

BATASAN INI BERLAKU BAIK KLAIM DIDASARKAN PADA KONTRAK, PERBUATAN MELAWAN HUKUM (TERMASUK KELALAIAN), TANGGUNG JAWAB MUTLAK, ATAU TEORI HUKUM LAINNYA, BAHKAN JIKA PENGEMBANG TELAH DIBERITAHU MENGENAI KEMUNGKINAN KERUGIAN TERSEBUT.

## 10. Ganti Rugi

Anda setuju untuk mengganti rugi, membela, dan membebaskan Yural Dev dari dan terhadap semua klaim, kewajiban, kerusakan, kerugian, biaya, dan pengeluaran (termasuk biaya hukum yang wajar) yang timbul dari atau terkait dengan:

- Penggunaan Aplikasi oleh Anda
- Pelanggaran Anda terhadap Syarat ini
- Pelanggaran Anda terhadap hukum atau peraturan yang berlaku
- Data apa pun yang Anda masukkan, simpan, atau bagikan melalui Aplikasi, termasuk foto transaksi

## 11. Penghentian

### 11.1 Penghentian oleh Pengguna

Anda dapat mengakhiri Syarat ini kapan saja dengan mencopot pemasangan Aplikasi dan menghapus semua data terkait serta file backup dari perangkat Anda.

### 11.2 Penghentian oleh Pengembang

Pengembang berhak untuk menghentikan atau menangguhkan akses Anda ke Aplikasi kapan saja, tanpa pemberitahuan atau kewajiban sebelumnya, jika Anda melanggar ketentuan apa pun dalam Syarat ini.

### 11.3 Efek Penghentian

Setelah penghentian:

- Lisensi Anda untuk menggunakan Aplikasi segera berakhir
- Anda harus mencopot pemasangan Aplikasi dan menghapus semua salinan yang Anda miliki
- Ketentuan dalam Syarat ini yang secara alami harus tetap berlaku setelah penghentian akan tetap berlaku, termasuk namun tidak terbatas pada Bagian 5 (Kekayaan Intelektual), 8 (Penyangkalan Jaminan), 9 (Batasan Tanggung Jawab), dan 10 (Ganti Rugi)

## 12. Hukum yang Berlaku dan Penyelesaian Sengketa

### 12.1 Hukum yang Berlaku

Syarat ini harus diatur dan ditafsirkan sesuai dengan hukum Negara Republik Indonesia, tanpa memperhatikan ketentuan konflik hukumnya.

### 12.2 Penyelesaian Sengketa

Setiap sengketa yang timbul dari atau terkait dengan Syarat ini atau Aplikasi pertama-tama akan diupayakan untuk diselesaikan melalui negosiasi informal. Jika sengketa tidak dapat diselesaikan dalam waktu 30 hari, sengketa akan diajukan ke mediasi sesuai dengan Badan Arbitrase Nasional Indonesia (BANI). Tindakan hukum apa pun harus diajukan secara eksklusif di pengadilan Indonesia.

## 13. Perubahan Syarat

Pengembang berhak untuk mengubah Syarat ini kapan saja. Perubahan akan diposting di dalam Aplikasi dan/atau di repositori Aplikasi. Penggunaan Aplikasi Anda yang berkelanjutan setelah perubahan merupakan penerimaan terhadap Syarat yang dimodifikasi.

Jika Anda tidak menyetujui perubahan apa pun, Anda harus berhenti menggunakan Aplikasi dan mencopot pemasangannya.

## 14. Keterpisahan

Jika ketentuan apa pun dalam Syarat ini dinyatakan tidak sah, ilegal, atau tidak dapat diberlakukan oleh pengadilan yang berwenang, ketentuan yang tersisa akan tetap berlaku penuh.

## 15. Keseluruhan Perjanjian

Syarat ini, bersama dengan Kebijakan Privasi, merupakan seluruh perjanjian antara Anda dan Yural Dev mengenai Aplikasi dan menggantikan semua perjanjian dan pemahaman sebelumnya, baik tertulis maupun lisan.

## 16. Informasi Kontak

Untuk pertanyaan, kekhawatiran, atau pemberitahuan mengenai Syarat ini, silakan hubungi:

- **Pengembang**: Yural Dev
- **Email**: yuraldeveloper@gmail.com

---

_Syarat dan Ketentuan ini disusun dengan mengacu pada praktik standar industri dan hukum yang berlaku, termasuk Undang-Undang Informasi dan Transaksi Elektronik (UU ITE) Indonesia._
