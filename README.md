# Warung Pintar

## Tujuan Aplikasi
Aplikasi ini digunakan untuk membantu operasional harian toko grosir sembako,
meliputi pencatatan stok barang, pembelian dari supplier, penjualan ke pelanggan,
dan laporan sederhana.

Aplikasi digunakan oleh pemilik toko dan admin toko.

---

## Fitur Utama

1. Manajemen Barang
2. Manajemen Supplier
3. Manajemen Pelanggan
4. Pembelian Barang
5. Penjualan Barang
6. Laporan Stok & Penjualan

---

## User Role
- Admin Toko
  - Mengelola data barang
  - Mencatat pembelian
  - Mencatat penjualan
  - Melihat laporan

---

## Data & Input

### Data Barang
- Nama Barang
- Kategori (Beras, Gula, Minyak, dll)
- Satuan (Kg, Dus, Liter, Pcs)
- Harga Beli
- Harga Jual
- Stok Saat Ini
- Stok Minimum

### Data Supplier
- Nama Supplier
- Nomor Telepon
- Alamat

### Data Pelanggan
- Nama Pelanggan
- Tipe Pelanggan (Retail / Grosir)
- Nomor Telepon

---

## Alur Proses Aplikasi

### 1. Pembelian Barang
- Admin memilih supplier
- Admin memilih barang
- Admin memasukkan jumlah pembelian
- Sistem menambah stok barang
- Sistem menyimpan riwayat pembelian

### 2. Penjualan Barang
- Admin memilih pelanggan
- Admin memilih barang
- Admin memasukkan jumlah penjualan
- Sistem mengurangi stok barang
- Sistem menghitung total harga
- Sistem menyimpan riwayat penjualan

---

## Aturan Bisnis
- Stok tidak boleh minus
- Jika stok ≤ stok minimum, tampilkan peringatan
- Harga jual diambil dari master barang
- Total penjualan dihitung otomatis

---

## Output & Laporan

1. Laporan Stok Barang
   - Nama Barang
   - Stok Saat Ini
   - Status (Aman / Hampir Habis)

2. Laporan Penjualan
   - Per hari
   - Per periode (tanggal)

3. Laporan Pembelian
   - Per supplier
   - Per periode

---

## Tampilan Aplikasi
- Dashboard ringkas
- Menu sidebar
- Tabel data
- Form input sederhana

---

## Platform
- Aplikasi berbasis web
- Digunakan di laptop / tablet
