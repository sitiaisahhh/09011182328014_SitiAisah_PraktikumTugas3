# 09011182328014_SitiAisah_PraktikumTugas3
Nama : Siti Aisah<BR/>
Nim : 09011182328014<BR/>
Kelas : SK3B
<h1>Laporan Praktikum Sistem File</h1>
<h2>Latar Belakang</h2>
<p>Sistem file (file system) atau sistem berkas merupakan struktur logika yang digunakan untuk mengendalikan akses terhadap data yang ada pada disk. Dengan kata lain, sistem file merupakan database khusus untuk penyimpanan, pengelolaan, manipulasi dan pengambilan data, agar mudah ditemukan dan diakses.

Hubungan antara sistem operasi dengan sistem file adalah sistem file merupakan interface yang menghubungkan sistem operasi dengan disk. Ketika program menginginkan pembacaan dari hard disk atau media penyimpanan lainnya, sistem operasi akan meminta sistem file untuk mencari lokasi dari file yang diinginkan. Setelah file ditemukan, sistem file akan membuka dan membaca file tersebut, kemudian mengirimkan informasinya kepada sistem operasi dan akhirnya bisa dibaca oleh pengguna.</p>
<h2>Tujuan</h2>
1.  Mengenal organisasi File di Linux. <br/>
2.  Menciptakan dan manipulasi direktori. <br/>
3.  Mempelajari ijin akses (permission) dari file dan direktori. <br/>
4.  Mengenal konsep Owner dan Group. <br/>
5.  Mengerti konsep Link dan symbolic link. <br/>
<h2>Alat dan Bahan</h2>
1.  Laptop <br/>
2.  Sistem Operasi Linux <br/>
3.  Command Line Linux <br/>
<h2>Dasar Teori</h2>
Sistem file pada Linux menyerupai pepohonan (tree), yaitu dimulai dari root, kemudian 
direktori dan sub direktori. Sistem file pada Linux diatur secara hirarkhikal, yaitu dimulai dari 
root dengan symbol “/”.<br/>
<h2>Pembahasan</h2>
<p>1. Lihat peralatan I/O, character device, yang ada pada system komputer.</p>
<img src="https://github.com/user-attachments/assets/8eb95572-82e2-4551-925c-506e089b95e5" width=400/> <br/>
<img src="https://github.com/user-attachments/assets/6549501d-412f-4aa9-8148-9842be3ddb48" width=400/> <br/>
<p>2. Buatlah sub direktori januari, februari dan maret sekaligus pada direktori latihan5.</p>
<img src="https://github.com/user-attachments/assets/6275fca9-71c6-4b33-b08c-1e3ccdfc969e" width=400/> <br/>
<p>3. Buatlah file dataku yang berisi nama, nim dan alamat anda pada sub direktori januari dan copy-kan file tersebut ke sub direktori februari dan maret.</p>
<img src="https://github.com/user-attachments/assets/5d66b28c-c7dd-4e82-a78b-64c7b9957871" width=400/> <br/>
<img src="https://github.com/user-attachments/assets/a106d4f3-09c3-4d5a-a85d-0d95fe7c9ebf" width=400/> <br/>
<p>4. Ubahlah ijin akses file dataku pada sub direktori januari sehingga group dan others dapat melakukan write.</p>
<img src="https://github.com/user-attachments/assets/f614b843-f7f4-46e5-a8af-4bd30c6dc361" width=400/> <br/>
<p>5. Ubahlah ijin akses file dataku pada sub direktori pebruari sehingga user dapat melakukan baik write, read maupun execute, tetapi group dan others hanya bisa read 
dan execute.</p>
<img src="https://github.com/user-attachments/assets/9d56eb9e-0f45-4b34-8a99-2524a99a1af9" width=400/> <br/>
<p>6. Ubahlah ijin akses file dataku pada sub direktori maret sehingga semua dapat melakukan write, read dan execute.</p>
<img src="https://github.com/user-attachments/assets/79f939bf-cf96-4d4a-a0b3-f1f0d62221b8" width=400/> <br/>
<p>7. Hapuslah direktori maret.</p>
<img src="https://github.com/user-attachments/assets/af6f0010-4ff4-4d95-b14b-784472e361d2" width=400/> <br/>
<p>8. Ubahkan kepemilikan sub direktori februari sehingga user dan group hanya dapat melakukan read, dan cobalah untuk membuat direktori baru haha pada sub direktori 
februari.</p>
<img src="https://github.com/user-attachments/assets/fa261b6d-c42b-45b5-bb47-4ff9808c2a64" width=400/> <br/>
<p>9. Modifikasi umask dari file dataku pada sub direktori januari menjadi 027 dan berapakah nilai default-nya ?</p>
<img src="https://github.com/user-attachments/assets/2d4f42f4-4f1e-4eca-ae83-b5229b597246" width=400/> <br/>
<p>10. Buatlah link dari file dataku ke file dataku.ini dan file dataku.juga dan dengan perintah list perhatikan berapa link yang terjadi ?</p>
<img src="https://github.com/user-attachments/assets/f0cf46f6-f870-4197-8cb4-fd86ac68c77a" width=400/> <br/>
<h2>Kesimpulan</h2>
<p>Sistem file Linux adalah cara penyimpanan dan pengaturan data di dalam sistem operasi Linux, yang diorganisir dalam bentuk hirarki direktori dan file, dimulai dari root (/). Linux mendukung berbagai jenis sistem file seperti ext4, XFS, dan Btrfs, dengan ext4 sebagai yang paling umum. Setiap file memiliki izin akses (read, write, execute) untuk pengguna, grup, dan lainnya, serta diwakili oleh inode yang menyimpan informasi metadata. Sistem file Linux juga menggunakan konsep mounting untuk mengakses partisi disk melalui direktori tertentu. Beberapa sistem file mendukung journaling untuk meningkatkan keandalan dan pemulihan pasca crash. Dengan fitur izin, journaling, serta fleksibilitas dalam mendukung berbagai tipe file, sistem file Linux dirancang untuk stabilitas, keamanan, dan keandalan, baik untuk penggunaan server maupun desktop.</p>
