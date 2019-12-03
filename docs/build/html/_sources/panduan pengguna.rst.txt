.. SIDADU documentation master file, created by
   sphinx-quickstart on Mon Dec  2 13:21:45 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. _Panduan_Pengguna:

Panduan Pengguna
=================================================

Berikut panduan penggunanaan SIDADU berdasarlan peran masing-masing


Admin
=================================================
  
Secara default, SIDADU mempunyai satu akun pengguna yang perannya sebagai Admin. Selanjutnya Admin dapat membuat akun untuk pengguna-pengguna lainnya sesuai dengan peran yang diinginkan.

**1. Pembuatan akun pengguna**

Pembuatan akun pengguna hanya dapat dilakukan oleh pengguna dengan peran atau hak akses sebagai Admin. Berikut langkah-langkah pembuatan akun pengguna. 

 1. Admin melakukan proses otentikasi melalui halaman Login.

  
  .. figure:: images/login.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Jika kombinasi nama pengguna dan kata sandi sesuai, Admin akan secara otomatis diarahkan ke halaman Dashboard.
 3. Pilih menu :code:`Kelola Pengguna`.


  .. figure:: images/kelola-user.png
     :width: 600
     :alt: gambar 2. Tambah pengguna


 4. Lalu pada pojok kanan atas, pilih atau tekan tombol :code:`Tambah Pengguna`. Selanjutnya secara otomatis Admin akan diarahkan ke halaman tambah pengguna.


  .. figure:: images/tambah-pengguna.png
     :width: 600
     :alt: gambar 2. Tambah pengguna


 5. Pada halaman tambah pengguna, isikan semua detail pengguna sesuai dengan kolom isian yang ada.
 6. Pada kolom peran pengguna terdapat dua peran pengguna yang bisa dipilih yaitu Admin dan RT. Pilih peran pengguna sesuai dengan peran yang diinginkan yaitu .
 7. Tekan :code:`Simpan`.
 8.  Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa data berhasil disimpan, dan Admin akan secara otomatis diarahkan ke halaman daftar pengguna yang sudah dibuat. Sistem juga secara otomatis akan mengirimkan detail nama pengguna dan kata sandi ke alamat email dari pengguna yang baru saja dibuat. Detail nama pengguna dan kata sandi ini diperlukan oleh pengguna untuk proses otentikasi di halaman login ketika akan mengakses layanan SIDADU.


  .. figure:: images/pesan-berhasil.png
     :width: 600
     :alt: gambar 2. Tambah pengguna


 9.  Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

   
  .. figure:: images/pesan-error.png
     :width: 600
     :alt: gambar 2. Tambah pengguna


**2.  Melihat detail akun pengguna**

 1. Pada halaman daftar pengguna, klik tanda :code:`...` pada kolom opsi pada akun pengguna yang ingin dilihat detailnya.


  .. figure:: images/detail-pengguna.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pilih :code:`Detail`. Sistem akan otomatis mengarahkan ke halaman detail pengguna sesuai dengan pengguna yang dipilih


  .. figure:: images/detail-pengguna2.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


**2.  Memperbarui detail akun pengguna**

 1. Pada halaman daftar pengguna, klik tanda :code:`...` pada kolom opsi pada akun pengguna yang ingin diperbarui detailnya.


  .. figure:: images/detail-pengguna.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pilih :code:`Edit`. Sistem akan otomatis mengarahkan ke halaman edit pengguna sesuai dengan pengguna yang dipilih


  .. figure:: images/edit-pengguna.png
     :width: 600
     :alt: gambar 4. Edit Pengguna

 3. Isikan data sesuai dengan kolom yang ingin diperbarui. Lalu tekan :code:`Simpan` untuk menyimpan data.
 5. Jika data yang dimasukkan valid, maka akan muncul pemberitahuan bahwa data berhasil diperbarui. Jika data yang dimasukkan tidak valid, maka akan muncul pemberitahuan  pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.


**3.  Menghapus akun pengguna**

 1. Pada halaman daftar pengguna, klik tanda :code:`...` pada kolom opsi pada akun pengguna yang ingin diperbarui detailnya.


  .. figure:: images/detail-pengguna.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pilih :code:`Hapus`. Sistem akan menampilkan jendela konfirmasi, apakah proses penghapusan akun akan diteruskan atau tidak. Pilih Batal untuk membatalkan proses penghapusan. Pilih OK untuk mengkonfirmasi penghapusan akun. 


  .. figure:: images/hapus-pengguna.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna


**4.  Melihat visualisasi data kependudukan**

 1. Pilih menu :code:`Dashboard` untuk melihat visualisasi data kependudukan.


  .. figure:: images/dashboard.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Halaman dashboard berisi visualisasi data kependudukan berdasarkan jenis kelamin, pendidikan, pekerjaan dan status keluarga.


**5.  Melihat data kepala keluarga**

 1. Pilih menu :code:`Kepala Keluarga` untuk melihat daftar kepala keluarga yang sudah didaftarkan di SIDADU.


  .. figure:: images/detail-pengguna.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pilih atau tekan tombol :code:`Ekspor ke Excel` untuk mengunduh data daftar kepala keluarga dalam format Excel.


**6.  Melihat data warga**

 1. Pilih menu :code:`Data Warga` untuk melihat daftar data warga yang sudah didaftarkan di SIDADU.


  .. figure:: images/detail-pengguna.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pilih atau tekan tombol :code:`Ekspor ke Excel` untuk mengunduh data daftar warga dalam format Excel.


  .. figure:: images/hapus-pengguna.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna


Rukun Tetangga (RT)
=================================================
  
Peran utama RT dalam SIDADU adalah untuk memasukkan data kependudukan dalam lingkup Rukun tetangga dimana ia menjabat.

**1. Memperbarui akun**

 1. RT melakukan proses otentikasi melalui halaman Login.

  
  .. figure:: images/login.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Jika kombinasi nama pengguna dan kata sandi sesuai, RT akan secara otomatis diarahkan ke halaman Dashboard.
 3. Pilih menu :code:`Kelola Akun Saya`. Sistem akan mengarahkan ke halaman detail akun pengguna.

  
  .. figure:: images/kelola-akun.png
     :width: 600
     :alt: gambar 1. halaman login


 4. Isikan data pada kolom isian yang ingin diperbarui.
 5. Tekan tombol Simpan.
 6.  Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa data berhasil disimpan. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

   
**2.  Melihat visualisasi data kependudukan**

 1. Pilih menu :code:`Dashboard` untuk melihat visualisasi data kependudukan.


  .. figure:: images/dashboard-rt.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Halaman dashboard berisi visualisasi data kependudukan berdasarkan jenis kelamin, pendidikan, pekerjaan dan status keluarga.


**3.  Memasukkan data warga**

 1. Pilih menu :code:`Data Warga`. Sistem akan mengarahkan ke halaman daftar data warga.


  .. figure:: images/data-warga.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pilih atau tekan tombol :code:`Tambah Data Baru` untuk menambahkan data baru`. Sistem akan mengarahkan ke halaman untuk memasukkan data baru.


  .. figure:: images/form-warga.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna

 4. Isikan data pada kolom isian yang ingin ada.
 5. Pada salah satu kolom isian, terdapat kolom status dalam keluarga. Jika warga yang datanya akan dimasukkan bersatatus Kepala Keluarga, maka RT diwajibkan untuk memasukkan Nomor Induk KK. Warga yang berstatus sebagai Kepala Keluarga, datanya bisa dilihat terpisah dalam menu Data Kepala Keluarga.
 6. Tekan tombol :code:`Simpan`.
 7. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa data berhasil disimpan. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.
 

**3.  Melihat detail data warga**

 1. Pilih menu :code:`Data Warga` untuk melihat daftar data warga yang sudah didaftarkan di SIDADU.


  .. figure:: images/data-warga-opsi.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pada halaman daftar warga, klik tanda :code:`**...**` pada kolom opsi pada baris warga yang ingin dilihat detailnya.
 3. Pilih :code:`Detail`
 4. Sistem akan mengarahkan ke halaman detail warga sesuai data warga yang dipilih. Tekan tombol kembali untuk kembali ke daftar warga. Tekan tombol edit untuk memperbarui data warga.

  .. figure:: images/detail-warga.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna


**3.  Memperbarui detail data warga**

 1. Pilih menu :code:`Data Warga` untuk melihat daftar data warga yang sudah didaftarkan di SIDADU.


  .. figure:: images/data-warga-opsi.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pada halaman daftar warga, klik tanda :code:`**...**` pada kolom opsi pada baris warga yang ingin dilihat detailnya.
 3. Pilih :code:`Edit`
 4. Sistem akan mengarahkan ke halaman edit warga sesuai data warga yang dipilih.
 5. Isikan data pada kolom isian yang ingin diperbarui datanya.
 6. Tekan tombol Simpan.
 7. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa data berhasil diperbarui. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui. 


**3.  Menghapus data warga**

 1. Pilih menu :code:`Data Warga` untuk melihat daftar data warga yang sudah didaftarkan di SIDADU.


  .. figure:: images/data-warga-opsi.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pada halaman daftar warga, klik tanda :code:`**...**` pada kolom opsi pada baris warga yang ingin dihapus datanya.
 3. Pilih :code:`Hapus`
 4. Sistem akan menampilkan jendela konfirmasi, apakah proses penghapusan akun akan diteruskan atau tidak. Pilih OK untuk mengkonfirmasi penghapusan akun. 


  .. figure:: images/hapus-warga.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna