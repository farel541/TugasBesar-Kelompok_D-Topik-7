# TugasBesar-Kelompok_D-Topik-7
Aplikasi pengelolaan komunitas kampus (ukm.telu) mencatat mahasiswa dan komunitas yang diikuti. Seorang
mahasiswa dapat bergabung dengan beberapa komunitas dan setiap komunitas dapat memiliki banyak
anggota. Setiap anggota dapat mengikuti berbagai kegiatan komunitas dan memperoleh poin keaktifan. Data
keanggotaan dikelola melalui Multi Linked List, sedangkan aktivitas mahasiswa dicatat dalam Binary Search
Tree
Struktur Data
Parent : Mahasiswa (NIM, nama, prodi, angkatan)
Child : Komunitas (kode komunitas, nama, kategori)
Relasi : Keanggotaan (tanggal bergabung, jabatan, status anggota)
Binary Search Tree : Aktivitas mahasiswa dengan key id aktivitas (NIM, kode komunitas, nama kegiatan, poin keaktifan)

Fungsional khusus
• Membatasi satu mahasiswa maksimal bergabung dengan tiga komunitas.
• Mencatat dan menyimpan aktivitas mahasiswa ke BST berdasarkan
nomor ide aktivitas (Unik dan acak).
• Menampilkan lima mahasiswa paling aktif berdasarkan total poin
keaktifan.
• Menampilkan seluruh aktivitas yang pernah diselenggarakan.

Fungsional tambahan (Bonus)
• Menampilkan informasi komunitas dengan jumlah aktivitas terbanyak.
• Menampilkan informasi mahasiswa yang tidak pernah mengikuti aktivitas
apapun.
• Merekap keaktifan mahasiswa berdasarkan angkatan.
