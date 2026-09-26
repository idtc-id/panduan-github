# M2 — Membuat Akun dan Mengamankannya

**Tingkat:** T0 — Pengamat &nbsp;·&nbsp; **Durasi:** 20 menit &nbsp;·&nbsp; **Prasyarat:** M1

## Tujuan

Setelah modul ini, Anda dapat:

- Memiliki akun GitHub yang aktif dan terverifikasi.
- Mengaktifkan autentikasi dua faktor pada akun tersebut.
- Bergabung ke organisasi `idtc-id`.

## Kenapa dua faktor diwajibkan

IDTC mewajibkan **autentikasi dua faktor** (kode tambahan selain kata sandi) bagi setiap anggota organisasi. Ini bukan formalitas: banyak anggota IDTC berasal dari kementerian dan BUMN yang membawa data pekerjaan yang sensitif. Bila kata sandi seorang anggota bocor, autentikasi dua faktor adalah lapisan terakhir yang mencegah orang lain masuk ke akunnya dan mengubah dokumen komunitas atas namanya.

Ini adalah **kebijakan wajib IDTC**, bukan sekadar imbauan — pengurus dapat meninjau ulang keanggotaan akun yang tidak mengaktifkannya. Lakukan langkah ini sebelum meminta undangan bergabung ke organisasi, supaya prosesnya tidak perlu diulang.

## Langkah

### 1. Mendaftar akun

1. Buka `github.com/signup` di peramban.
2. Isi surel, kata sandi, dan nama pengguna (username) yang diminta. Pilih nama pengguna yang mudah dikenali rekan Pokja Anda — sebaiknya memuat nama asli Anda.
3. Selesaikan verifikasi yang diminta di layar.
4. Buka kotak masuk surel Anda, cari surel dari GitHub, dan klik tautan verifikasi di dalamnya.

   ![Halaman pendaftaran GitHub](gambar/M2-01-halaman-pendaftaran.png)

Sesudah langkah ini, Anda sudah bisa masuk (login) ke `github.com` dengan surel dan kata sandi tadi.

Bila surel verifikasi tidak kunjung muncul dalam beberapa menit, periksa folder **Spam** atau **Promosi** pada kotak masuk Anda sebelum mencoba mendaftar ulang — mendaftar dua kali dengan surel yang sama akan ditolak oleh sistem.

### 2. Mengaktifkan autentikasi dua faktor

1. Setelah masuk, klik foto profil Anda di kanan atas, lalu pilih **Settings**.
2. Di menu kiri, klik **Password and authentication**.
3. Pada bagian **Two-factor authentication**, klik **Enable two-factor authentication**.

   ![Setelan Password and authentication](gambar/M2-02-setelan-2fa.png)

4. Pilih metode **aplikasi autentikator** (disarankan) — misalnya Google Authenticator atau Microsoft Authenticator, dipasang lebih dulu di ponsel Anda dari toko aplikasi.
5. Pindai (scan) kode QR yang tampil di layar memakai aplikasi autentikator tersebut, lalu masukkan enam digit kode yang muncul di aplikasi ke kotak konfirmasi GitHub.
6. GitHub akan menampilkan **kode cadangan (recovery codes)** — sederet kode sekali pakai.

   ![Layar kode cadangan](gambar/M2-03-kode-cadangan.png)

7. **Simpan kode cadangan ini di tempat aman di luar ponsel Anda** — misalnya dicetak atau disimpan di pengelola kata sandi. Kode ini satu-satunya jalan masuk bila ponsel Anda hilang atau berganti.

### 3. Bergabung ke organisasi idtc-id

1. Kirim nama pengguna GitHub Anda kepada pengurus Pokja melalui kanal yang sudah disepakati (WhatsApp atau surel Sekretariat). Periksa ulang ejaannya sebelum mengirim.
2. Tunggu surel undangan dari GitHub dengan judul mengenai organisasi `idtc-id`.

   ![Surel undangan organisasi](gambar/M2-04-surel-undangan.png)

3. Buka surel tersebut dan klik **View invitation**, lalu klik **Join idtc-id**.
4. Setelah diterima, buka `github.com/idtc-id` — nama Anda kini terdaftar sebagai anggota organisasi.

## Latihan

Aktifkan autentikasi dua faktor di akun Anda, simpan kode cadangannya di tempat yang bukan ponsel yang sama, lalu kirim nama pengguna Anda kepada pengurus Pokja untuk diundang.

## Kesalahan umum yang harus diantisipasi

- **Kode cadangan tidak disimpan, lalu ponsel hilang atau diganti.** Tanpa kode cadangan, akun tidak bisa dipulihkan sendiri dan harus melalui proses pemulihan GitHub yang memakan waktu. Ingatkan peserta menyimpannya *sebelum* menutup layar.
- **Nama pengguna dikirim dengan salah ketik**, sehingga pengurus mengundang akun yang salah dan undangan tidak pernah sampai. Minta peserta menyalin-tempel nama pengguna, bukan mengetik ulang dari ingatan.
- **Peserta menutup layar kode QR sebelum sempat memindainya**, lalu harus mengulang proses pengaktifan dari awal. Ingatkan agar aplikasi autentikator sudah terpasang di ponsel *sebelum* memulai langkah ini.

## Ringkasan

Akun GitHub yang aman adalah syarat masuk untuk semua modul berikutnya. Dua faktor wajib karena melindungi dokumen sensitif komunitas, dan kode cadangan adalah jaring pengaman satu-satunya bila ponsel bermasalah. Setelah akun aktif dan bergabung ke `idtc-id`, Anda siap menjelajah repositori secara lebih mendalam pada M3.
