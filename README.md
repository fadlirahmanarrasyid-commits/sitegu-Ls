# SimpleEdu - Admin Guru Masa Kini 🎓✨

**SimpleEdu** adalah platform manajemen administrasi sekolah yang dirancang khusus untuk memudahkan guru dalam mengelola data harian secara efisien, aman, dan profesional. Dengan tampilan modern berbasis *Glassmorphism* dan efek *Aurora Ambient*, aplikasi ini memberikan pengalaman kerja yang mewah namun tetap ringan.

---

## 🚀 Fitur Utama

### 📊 Dashboard & Analisis
- **Statistik Cepat**: Ringkasan jumlah siswa, mapel, dan aktivitas terbaru.
- **Visualisasi Data**: Grafik tren kehadiran siswa (7 sesi terakhir) menggunakan Recharts.
- **Developer Banner**: Akses cepat ke profil pengembang.

### 👥 Manajemen Data Master
- **Data Siswa & Mapel**: Pengelolaan lengkap (Tambah, Edit, Hapus).
- **Pencarian Real-time**: Cari data siswa berdasarkan Nama, NIPD, atau Kelas secara instan.
- **Pagination**: Navigasi halaman yang rapi (10 data per halaman).
- **Impor CSV**: Unggah data siswa secara massal menggunakan file Excel/CSV dengan panduan tooltip interaktif.

### 📅 Modul PTM & Absensi
- **Jurnal Mengajar**: Catat materi harian, jam pelajaran, dan kendala kelas.
- **Sistem Absensi**: Input kehadiran siswa (Hadir, Izin, Sakit, Alpa) yang terintegrasi dengan rekapitulasi.

### 📈 Rekapitulasi & Penilaian
- **Rekap Kehadiran**: Pantau persentase kehadiran per kelas secara mendalam.
- **Pantau Siswa**: Lihat riwayat absensi individu siswa secara spesifik.
- **Rekap Nilai**: Manajemen nilai siswa per mata pelajaran dengan tampilan yang bersih.

### 🖨️ Cetak Laporan (Professional Output)
- Cetak Jurnal Mengajar, Absensi, dan Nilai ke format yang siap diprint (PDF-ready).
- Header laporan otomatis menggunakan identitas sekolah dari pengaturan.

### 🔐 Keamanan & Autentikasi
- **Sistem Login & Daftar**: Akses terkunci dengan akun lokal (Instansi, Nama, Username, Password).
- **Ganti Password**: Fitur keamanan untuk memperbarui kata sandi di halaman pengaturan.
- **Standalone Storage**: Data disimpan secara aman di memori lokal browser (`localStorage`).

### 📱 PWA (Progressive Web App)
- **Instalasi Desktop/HP**: Bisa diinstal sebagai aplikasi mandiri tanpa browser.
- **Offline Ready**: Tetap bisa diakses meskipun tanpa koneksi internet.
- **Auto-update Notice**: Notifikasi otomatis saat ada pembaruan versi baru.

### 💬 Feedback & Support
- **Dual Channel**: Kirim saran via Email Otomatis atau WhatsApp.
- **WhatsApp Community**: Link langsung untuk bergabung ke grup koordinasi guru.

---

## 🛠️ Teknologi yang Digunakan
- **Core**: React.js (Vite)
- **Styling**: Vanilla CSS (Premium Glassmorphism & Aurora Effect)
- **Icons**: Lucide React
- **Charts**: Recharts
- **API**: Web3Forms (Automated Email)
- **PWA**: Vite PWA Plugin

---

## 📜 Riwayat Versi (Change Log)

### **v1.3.6 (Juli 2026) - Clean Storage & Production Release**
- **Mengosongkan Data Dummy**: Mengosongkan data siswa (`INITIAL_STUDENTS`) dan mapel (`INITIAL_MAPELS`) agar aplikasi dalam keadaan bersih saat pertama kali dibuka.
- **Penghapusan Tombol Reset**: Menghapus tombol "Reset ke Data Dummy" di Dashboard untuk menghindari ketidaksengajaan terhapusnya data sekolah asli milik guru.
- **Dokumentasi Baru**: Penambahan berkas interaktif `readme.html` di dalam folder build untuk panduan yang menarik langsung dari browser.
- **Re-build Produksi**: Seluruh modul statis diperbarui untuk optimasi pemuatan pada hosting Vercel.

### **v1.3.5 (Juni 2026) - Deployment Optimization Update**
- Penghapusan file server lokal (`server.js` & `database.json`) yang tidak terpakai.
- Pembersihan *dependencies* backend untuk meringankan ukuran aplikasi.
- Konfigurasi *project* 100% menggunakan *LocalStorage* agar siap di-hosting ke Vercel dan GitHub.

### **v1.3.0 (Mei 2025) - Major Security & UI Update**
- Implementasi Sistem Autentikasi (Login/Registrasi).
- Fitur Ganti Password di halaman Pengaturan.
- Efek Latar Belakang Aurora Ambient Premium (Pastel Theme).
- Fitur Pencarian (Search) & Halaman (Pagination) di Data Master.
- Integrasi Link Grup WhatsApp Community.
- Perbaikan layout "Extra Rounded" (24px) di seluruh komponen.

### **v1.2.5 (Mei 2025)**
- Optimalisasi PWA & Standalone Mode.
- Penambahan Profil Pengembang di Dashboard dan Halaman About.

### **v1.2.0 (Mei 2025)**
- Implementasi PWA & Local File Storage.
- Modul Feedback via Email Otomatis.

### **v1.1.5 (Mei 2025)**
- Penyempurnaan desain cetak Jurnal (Portrait).
- Integrasi absensi otomatis ke rekap harian.

---

## 👨‍💻 Pengembang
**Fadli Rahman, S.Pd**  
*SMK Negeri 2 Sebulu*  
Website: [www.fadlirahman.my.id](http://www.fadlirahman.my.id)

---
*© 2025 SimpleEdu - Membantu Guru, Memajukan Pendidikan Indonesia.*
