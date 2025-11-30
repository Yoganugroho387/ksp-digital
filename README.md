# 🌟 Fitur Unggulan KSP Digital

Aplikasi manajemen Koperasi Simpan Pinjam berbasis web yang dirancang untuk efisiensi, transparansi, dan kemudahan penggunaan.

## 🌍 1. Halaman Publik (Landing Page)
Halaman depan modern sebagai wajah digital koperasi.
* **Profil Dinamis:** Menampilkan identitas, alamat, dan kontak koperasi yang bisa diubah sewaktu-waktu oleh Admin.
* **Statistik Real-time:** Menampilkan jumlah anggota aktif dan total penyaluran dana secara otomatis dari database.
* **Navigasi Responsif:** Tampilan optimal di Desktop maupun HP.
* **Direct Login:** Akses cepat untuk masuk ke area anggota/admin.

## 🔐 2. Panel Administrator
Pusat kendali penuh untuk pengelola koperasi.

### 📊 Dashboard Utama
* Ringkasan Saldo Kas Tunai (Real-time).
* Total Aset Piutang (Uang yang beredar di anggota).
* Grafik & Statistik Anggota.
* **Pengingat Jatuh Tempo:** Tabel otomatis yang menampilkan siapa saja yang harus ditagih bulan ini.
* **Aksi Cepat (Quick Action):** Tombol pintas untuk Teller (Setor, Cairkan Pinjaman, Tambah Anggota).

### 👥 Manajemen Anggota
* Pendaftaran Anggota Baru (Generate No Anggota Otomatis).
* Edit Profil & Data Anggota.
* Non-aktifkan Anggota (Soft Delete).

### 💰 Transaksi Simpanan
* **Setor Tunai:** Mendukung Simpanan Pokok, Wajib, dan Sukarela.
* **Tarik Tunai:** Penarikan saldo Simpanan Sukarela.
* **Bukti Transaksi:** Pencatatan riwayat setor/tarik yang rapi.

### 💸 Transaksi Pinjaman (Kredit)
* **Pengajuan Pinjaman:** Input plafon, bunga (%), dan tenor (bulan).
* **Kalkulator Otomatis:** Sistem langsung menghitung angsuran per bulan (Pokok + Bunga) menggunakan metode Bunga Tetap (*Flat Rate*).
* **Pencairan Dana:** Otomatis memotong saldo kas koperasi saat pinjaman disetujui.

### 📝 Pembayaran & Kartu Piutang
* **Kartu Piutang Digital:** Halaman detail per anggota untuk melihat sisa hutang.
* **Input Angsuran:** Pembayaran cicilan yang otomatis mengurangi pokok hutang.
* **Denda Keterlambatan:** Fitur input denda manual jika anggota telat bayar.
* **Pelunasan Otomatis:** Status pinjaman berubah menjadi "LUNAS" jika saldo hutang mencapai 0.
* **Validasi Sistem:** Mencegah pembayaran melebihi sisa hutang (Anti-Minus).

## 📈 3. Laporan & Akuntansi (Financial Report)
Fitur unggulan untuk transparansi keuangan.

* **Laporan Piutang:** Rekapitulasi siapa yang meminjam, berapa yang sudah dibayar, dan sisa hutang.
* **Laporan Arus Kas (Cashflow):** Mutasi detail uang masuk (Debet) dan uang keluar (Kredit).
* **Laporan Neraca (Balance Sheet):** Menampilkan posisi keuangan (Aset vs Pasiva) secara seimbang (*Balance*).
* **Laporan Rugi Laba (Income Statement):** Menghitung pendapatan bunga dikurangi biaya operasional untuk menghasilkan SHU (Sisa Hasil Usaha).
* **Export Data:** Semua laporan bisa diunduh ke format **Excel (.xlsx)** dan **PDF**.

## ⚙️ 4. Manajemen Keuangan Internal
* **Modal Koperasi:** Input modal awal pendiri, hibah, atau penyertaan modal luar.
* **Biaya Operasional:** Input pengeluaran rutin kantor (Listrik, Air, Gaji, ATK, dll) untuk perhitungan laba bersih yang akurat.

## 📱 5. Panel Anggota (Member Area)
Dashboard khusus yang bisa diakses oleh nasabah/anggota lewat HP.
* **Cek Saldo:** Melihat total tabungan (Pokok, Wajib, Sukarela).
* **Info Pinjaman:** Melihat status pinjaman aktif, sisa angsuran, dan tanggal jatuh tempo.
* **Riwayat Transaksi:** Memantau 5 aktivitas keuangan terakhir.

## 🛡️ 6. Keamanan & Sistem
* **Multi-Level User:** Login terpisah antara Admin dan Anggota.
* **Enkripsi Password:** Menggunakan algoritma Bcrypt (Aman dari peretasan standar).
* **Pengaturan Identitas:** Admin bisa mengubah Nama Koperasi, Logo, dan Kontak tanpa menyentuh kodingan.
* **Responsive UI:** Tampilan tabel dan menu yang bisa digeser (scrollable) dan rapi di layar HP.
