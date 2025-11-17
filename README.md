Nama : Fitri Malinda
NIM : 24183207002
Kelas : 3A
1. Kelas Mahasiswa (Struktur Data)
Kelas Mahasiswa berfungsi sebagai template atau tipe data khusus yang menggambarkan satu objek mahasiswa.
- Atribut (Fields)
Atribut adalah variabel yang menyimpan informasi atau kondisi dari sebuah objek Mahasiswa:
*private String nim; → Menyimpan Nomor Induk Mahasiswa.
*private String nama; → Menyimpan nama lengkap mahasiswa.
- Metode Utama (Methods)
*Konstruktor (Mahasiswa(), Mahasiswa(String nim, String nama))
Konstruktor digunakan untuk membuat objek baru. Konstruktor tanpa parameter memberikan nilai awal default, sedangkan konstruktor dengan parameter memungkinkan pengisian data langsung saat objek dibuat.
*Getter (getNim(), getNama())
Digunakan untuk mengambil nilai atribut dari luar kelas.
*Setter (setNim(), setNama())
Berfungsi untuk mengubah nilai atribut dari luar kelas.
- tampilkanData()
Method khusus yang digunakan untuk menampilkan informasi NIM dan Nama mahasiswa ke layar.

2. MainClass (Program Utama)
Kelas MainClass merupakan bagian program tempat eksekusi dimulai melalui method main().
- Variabel Penting
*Scanner input → Untuk menerima input dari pengguna melalui keyboard.
*ArrayList<Mahasiswa> daftarMahasiswa → Struktur data dinamis untuk menyimpan banyak objek Mahasiswa.
*int pilihan → Menyimpan angka pilihan menu dari pengguna.
- Struktur Kontrol Utama
*do-while
Digunakan untuk menampilkan menu secara berulang hingga pengguna memilih opsi 3 (keluar program).
*switch
Memilih dan menjalankan bagian kode tertentu berdasarkan nilai variabel pilihan.
