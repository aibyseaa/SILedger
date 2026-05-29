# SILedger
SILedger adalah solusi akuntansi modern berbasis R yang dirancang untuk mengotomatisasi pemindahan data dari Jurnal Umum ke Buku Besar. Melalui sistem pencatatan real-time, setiap transaksi yang masuk akan langsung memperbarui seluruh laporan keuangan secara otomatis, memastikan pengelolaan finansial yang sistematis, akurat, dan efisien.
# 🎯 Tujuan
Pengembangan SILedger didasarkan pada tiga tujuan utama. Pertama, kami ingin menyediakan software akuntansi gratis yang bisa dimanfaatkan oleh UMKM untuk merapikan pencatatan keuangan mereka tanpa harus terbebani biaya langganan aplikasi. Kedua, dari sisi teknis, kami mengembangkan program berbasis R ini agar proses pencatatan dan pengelolaan General Ledger bisa dilakukan dengan cepat, efisien, dan mudah digunakan oleh siapa saja. Terakhir, SILedger juga ditujukan sebagai fasilitas edukasi bagi mahasiswa yang ingin mempraktikkan pencatatan keuangan digital menggunakan sistem yang sistematis.
# ✨ Fitur Utama
Sistem SILedger didesain agar saling terintegrasi. Artinya, cukup dengan satu kali input, seluruh laporan akan otomatis terbarui. Berikut adalah fitur-fitur yang bisa kamu gunakan di aplikasi ini:

##Chart of Account untuk menyusun dan mengelola daftar akun perusahaan.
##Journal Voucher sebagai tempat input transaksi harian. Menariknya, fitur ini sudah mendukung pencatatan multi-mata uang (multi-currency) dan sub buku besar (sub-ledger).
##Account Budget untuk membantu kamu merencanakan sekaligus memantau batas anggaran di masing-masing akun.
##Account History dan Account Balance untuk melacak riwayat aktivitas transaksi sekaligus mengecek posisi saldo tiap akun secara *real-time*.
##Manajemen Jurnal Fleksibel, di mana jurnal yang sudah kamu buat tetap bisa diedit atau dihapus jika ada kesalahan, dan sistem akan mengalkulasi ulang secara otomatis.
# 🛠️ Teknologi
## R Shiny
## DT 
# 📂 Struktur
```text
└── app.R             # File tunggal utama yang berisi seluruh kode UI, Server, dan simulasi database reaktif aplikasi SILedger.

 # 👥 Pengembang
Kelompok 9 - R Programming, FEB Universitas Gadjah Mada
