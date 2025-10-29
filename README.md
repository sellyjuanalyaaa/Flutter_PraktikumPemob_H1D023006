# Aplikasi Manajemen Daftar Belanja Sederhana

Aplikasi mobile lintas platform (cross-platform) sederhana yang dikembangkan menggunakan Flutter (Dart) untuk mengelola daftar belanja. Aplikasi ini memungkinkan pengguna untuk menambah dan menghapus item secara langsung di antarmuka.

# Sellyjuan Alya Rosalina H1D023006 SHIFT A/C

# Fitur Aplikasi
Aplikasi ini berfokus pada fungsionalitas inti:

Tambah Item: Memungkinkan pengguna memasukkan dan menambahkan item baru ke daftar.

Hapus Item: Menyediakan tombol hapus (Icons.delete) di samping setiap item.

Tampilan Daftar Dinamis: Daftar diperbarui secara real-time (seketika) saat item ditambahkan atau dihapus.

Notifikasi Kosong: Menampilkan pesan saat daftar belanja kosong.

# Cara Kerja Pengembangan Kode
Pengembangan aplikasi ini mengikuti prinsip dasar widget-based dari Flutter dan menggunakan manajemen status lokal:
Komponen Utama (Widget Hierarchy)

ShoppingListApp	StatelessWidget	Merupakan akar aplikasi. Mendefinisikan tema dan struktur dasar (MaterialApp).
     
ShoppingListPage	StatefulWidget	Widget utama yang menampung tampilan layar. Dibuat sebagai StatefulWidget karena konten (daftar belanja) akan berubah.
     
ShoppingListPageState	State Class	Kelas ini menyimpan data yang dapat berubah (_items) dan logika yang memanipulasi data tersebut (_addItem, _removeItem).

# Contoh Tampilan
(https://github.com/sellyjuanalyaaa/Flutter_PraktikumPemob_H1D023006/blob/main/Screenshot%202025-10-29%20103348.png)
   
