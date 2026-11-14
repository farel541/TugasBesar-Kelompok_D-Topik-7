# TugasBesar-Kelompok_D-Topik-7

Aplikasi pengelolaan komunitas kampus (**ukm.telu**) mencatat mahasiswa dan komunitas yang diikuti. Seorang mahasiswa dapat bergabung dengan beberapa komunitas, dan setiap komunitas dapat memiliki banyak anggota. Setiap anggota dapat mengikuti berbagai kegiatan komunitas serta memperoleh poin keaktifan.

Data keanggotaan dikelola menggunakan **Multi Linked List (MLL)**, sedangkan aktivitas mahasiswa dicatat dalam **Binary Search Tree (BST)**.

---

## Struktur Data

1. **Parent — Mahasiswa**
   - Atribut: `NIM`, `nama`, `prodi`, `angkatan`
2. **Child — Komunitas**
   - Atribut: `kode komunitas`, `nama`, `kategori`
3. **Relasi — Keanggotaan (Multi Linked List)**
   - Atribut: `tanggal bergabung`, `jabatan`, `status anggota`
4. **Binary Search Tree — Aktivitas Mahasiswa**
   - Key: `id aktivitas` (unik dan acak)
   - Atribut: `NIM`, `kode komunitas`, `nama kegiatan`, `poin keaktifan`

---

## Fitur & Fungsionalitas

### Fungsional Khusus
- Membatasi satu mahasiswa maksimal bergabung dengan **3 komunitas**.
- Mencatat dan menyimpan aktivitas mahasiswa ke dalam **BST** berdasarkan nomor `id aktivitas` (unik dan acak).
- Menampilkan **5 mahasiswa paling aktif** berdasarkan total poin keaktifan.
- Menampilkan **seluruh aktivitas** yang pernah diselenggarakan.

### Fungsional Tambahan (Bonus)
- Menampilkan informasi **komunitas dengan jumlah aktivitas terbanyak**.
- Menampilkan informasi **mahasiswa yang tidak pernah mengikuti aktivitas apapun**.
- Merekap **keaktifan mahasiswa berdasarkan angkatan**.
