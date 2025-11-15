Dalam konteks pengembangan aplikasi NotesApp menggunakan Android Studio oleh Kelompok-2, pembagian tugas (jobdesk) didasarkan pada operasi dasar manajemen data yang dikenal sebagai CRUD (Create, Read, Update, Delete).
Berikut adalah penjelasan mengenai tanggung jawab masing-masing anggota tim:
1. Ado Murtado (10222081) - Job: CREATE (Membuat)
Ado bertanggung jawab atas semua fungsionalitas yang memungkinkan pengguna untuk membuat catatan baru dalam aplikasi.
Jobdesk Spesifik:
Desain UI Input: Merancang dan mengimplementasikan tampilan layar (activity atau fragment) di Android Studio tempat pengguna memasukkan judul dan konten catatan.
Pengambilan Input: Memastikan aplikasi dapat menangkap data yang diketik oleh pengguna secara akurat.
Logika Penyimpanan Awal: Mengimplementasikan fungsi untuk menyimpan data catatan baru ke dalam database lokal (misalnya, SQLite atau Room Database di Android).
Penanganan Error Pembuatan: Memastikan aplikasi memberikan umpan balik yang tepat jika proses pembuatan catatan gagal (misalnya, jika judul kosong).
Abdul Halim (10222143) - Job: READ (Membaca/Menampilkan)
2. Halim bertanggung jawab untuk mengambil dan menampilkan data catatan yang sudah disimpan di database kepada pengguna.
Jobdesk Spesifik:
Integrasi Database Reading: Mengimplementasikan query database untuk mengambil daftar semua catatan atau catatan spesifik.
Desain Tampilan Daftar (RecyclerView): Merancang bagaimana daftar catatan akan ditampilkan secara efisien (misalnya, menggunakan RecyclerView dan Adapter di Android Studio).
Tampilan Detail Catatan: Membuat layar terpisah untuk menampilkan detail lengkap dari satu catatan ketika pengguna memilihnya dari daftar.
Fungsionalitas Pencarian/Filter: (Opsional, tetapi umum dalam READ) Mengimplementasikan fitur pencarian untuk menemukan catatan tertentu.
3. Faisal Fahmi N (10222137) - Job: UPDATE (Memperbarui)
Faisal bertanggung jawab atas fungsionalitas yang memungkinkan pengguna untuk memodifikasi catatan yang sudah ada.
Jobdesk Spesifik:
Navigasi ke Layar Edit: Menghubungkan tampilan baca ke tampilan edit, memastikan data catatan yang dipilih dimuat sebelumnya di layar edit.
Logika Pembaruan Data: Mengimplementasikan fungsi database yang memperbarui baris data yang ada dengan informasi baru yang dimasukkan pengguna.
Penyimpanan Perubahan: Memastikan perubahan disimpan secara permanen di database setelah pengguna menekan tombol "Simpan" atau "Perbarui".
Validasi Perubahan: Memastikan data yang diperbarui valid dan tidak merusak integritas data.
4. Rian Abdul Aziz (10222037) - Job: DELETE (Menghapus)
Rian bertanggung jawab atas fungsionalitas untuk menghapus catatan yang sudah tidak diperlukan lagi oleh pengguna.
Jobdesk Spesifik:
Implementasi Fungsi Hapus: Mengimplementasikan fungsi database yang menghapus catatan spesifik berdasarkan ID uniknya.
Mekanisme Penghapusan UI: Merancang cara pengguna dapat menghapus catatan, seperti swipe-to-delete pada daftar, tombol hapus di layar detail, atau opsi menu konteks.
Konfirmasi Pengguna (Confirmation Dialog): Memastikan ada dialog konfirmasi sebelum penghapusan permanen untuk mencegah penghapusan yang tidak disengaja.
Refresh Tampilan: Memastikan tampilan daftar catatan diperbarui secara otomatis setelah sebuah catatan berhasil dihapus.
Dengan pembagian tugas ini, setiap anggota tim memiliki fokus yang jelas pada satu aspek fundamental dari aplikasi, yang pada akhirnya akan digabungkan untuk membentuk aplikasi NotesApp yang berfungsi penuh.


