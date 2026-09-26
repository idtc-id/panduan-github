# M9 — Aturan Main: Data, Lisensi, Keamanan

**Tingkat:** Semua tingkat &nbsp;·&nbsp; **Durasi:** 20 menit &nbsp;·&nbsp; **Prasyarat:** Modul sebelumnya

> Modul ini wajib disampaikan di akhir Sesi 1 maupun Sesi 2, kepada seluruh peserta tanpa kecuali — termasuk yang hanya mengikuti Sesi 1 (T0-T1). Aturan di sini menyangkut kepatuhan, bukan sekadar keterampilan teknis.

## Tujuan

Setelah modul ini, Anda dapat:

- Memilah data yang termasuk terbuka, terbatas, atau rahasia.
- Menyebutkan apa yang tidak boleh diunggah ke repo mana pun di `idtc-id`.
- Mengetahui langkah yang harus diambil bila data sensitif terlanjur terunggah.

## Tiga kelas data

| Kelas | Contoh | Boleh diunggah ke repo publik? |
|---|---|---|
| **Terbuka** | Dokumen kebijakan yang sudah disetujui, materi pelatihan, standar yang dipublikasikan | Ya |
| **Terbatas** | Draf yang belum disetujui, data teknis mitra dengan izin terbatas | Hanya dengan izin tertulis dan mengikuti kebijakan data Pokja |
| **Rahasia** | Data pribadi, kredensial, data mitra tanpa izin tertulis | Tidak, dalam bentuk apa pun |

## Larangan mutlak

Tidak boleh diunggah ke repo mana pun di `idtc-id` — baik publik maupun privat:

- **Data pribadi**: NIK, nomor telepon, alamat perorangan, dan sejenisnya.
- **Kredensial**: kata sandi, API key, token akses, connection string database.
- **Data mitra tanpa izin tertulis** untuk dibagikan, sekalipun repo tempat mengunggahnya bersifat privat.

> **Repo privat bukan tempat aman untuk data rahasia.** Privat hanya berarti tidak terlihat publik di GitHub — data tersebut tetap keluar dari sistem penyimpanan resmi mitra atau instansi Anda, dan itu sendiri sudah melanggar kesepakatan kerahasiaan pada banyak kasus.

## Batas ukuran berkas

Berkas yang diunggah ke repo maksimal **50 MB**. Dataset yang lebih besar disimpan di tempat penyimpanan terpisah (storage), dan repo cukup mencatat tautannya di katalog data.

## Lisensi

Kecuali dinyatakan lain secara eksplisit di repo tertentu:

- **Dokumen** berlisensi **CC BY 4.0** — boleh dipakai ulang siapa saja dengan menyebutkan sumbernya.
- **Kode** berlisensi **MIT** — boleh dipakai ulang termasuk untuk keperluan komersial.
- **Data** mengikuti lisensi pemiliknya masing-masing, dicatat di katalog data.

## Langkah darurat bila terlanjur mengunggah data sensitif

Ini bagian paling penting dari modul ini: **menghapus berkas saja tidak cukup**, karena versi lama berkas tersebut tetap tersimpan di riwayat git dan masih bisa diakses siapa pun yang menelusurinya.

1. **Segera hubungi pengurus** — jangan menunggu atau mencoba memperbaikinya sendirian dulu.
2. Sebutkan repo, nama berkas, dan Pull Request atau commit tempat data tersebut terunggah.
3. Pengurus akan mengoordinasikan penghapusan dari riwayat git sepenuhnya (bukan sekadar menghapus berkas pada commit terbaru) dan, bila kredensial yang bocor, memastikan kredensial tersebut dicabut (revoke) di sistem aslinya.

Semakin cepat dilaporkan, semakin kecil jendela waktu data tersebut bisa terlihat orang lain.

## Latihan

Pertimbangkan lima skenario berikut. Untuk masing-masing, putuskan boleh atau tidak diunggah ke repo publik IDTC, dan jelaskan alasannya:

1. Draf notulen rapat pengurus yang menyebut nama lengkap dan nomor HP peserta.
2. Data sebaran aset infrastruktur milik pemerintah daerah yang sudah dipublikasikan di situs resmi daerah tersebut.
3. Token API layanan peta yang dipakai tim teknis untuk pengujian.
4. Rancangan standar Digital Twin yang sudah disetujui Pokja 1 dan siap diterbitkan.
5. Dataset LiDAR mitra seberat 300 MB tanpa surat izin berbagi tertulis.

## Kesalahan umum yang harus diantisipasi

- **Peserta mengira repo privat aman untuk data rahasia.** Tegaskan kembali bahwa privasi repo tidak menghapus kewajiban menjaga data mitra dan data pribadi.
- **Peserta menganggap menghapus berkas sudah menyelesaikan masalah** ketika data sensitif terlanjur terunggah. Tekankan bahwa riwayat git menyimpan segalanya, dan pelaporan cepat ke pengurus adalah langkah yang benar, bukan mencoba memperbaikinya sendiri.

## Ringkasan

Tiga kelas data — terbuka, terbatas, rahasia — menentukan apa yang boleh diunggah ke mana; data pribadi, kredensial, dan data mitra tanpa izin tertulis tidak boleh diunggah dalam bentuk apa pun, ke repo publik maupun privat. Bila terlanjur, langkah yang benar adalah segera melapor ke pengurus, bukan menghapus berkas sendiri. Aturan ini berlaku untuk seluruh modul sebelumnya — dari mengedit dokumen di M6 hingga mengunggah data di repo mana pun.
