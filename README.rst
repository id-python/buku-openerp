Dasar-dasar OpenERP: sisi teknikal dan contoh kasus
============================================================

.. contents:: 


Target Pembaca
------------------------------------------------------------
- Pengguna OpenERP yang telah terbiasa, dan ingin melakukan
  kustomisasi ataupun menambah fungsionalitas tertentu. 

- Pengguna Python yang ingin mengembangkan solusi berbasis
  OpenERP.

  
Versi OpenERP
------------------------------------------------------------
- Versi OpenERP yang digunakan adalah versi 7.

- Kode lama (apabila ada) harus diuji terlebih dahulu.


Tim Buku (urut abjad)
------------------------------------------------------------

Penulis
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- Noprianto (https://github.com/nopri)
  (Bab: 5, 6, 7, 8, 9, 10) (+Editor)

- Whisnu Budhysantika (https://github.com/whisnu)
  (Bab: 1, 2, 3)

- Widoyo (https://github.com/widoyo)
  (Bab: 4)


Kesan Singkat
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- Ismail Sunni (http://github.com/ismailsunni)

- Owo Sugiana (https://github.com/sugiana)

- Steven Haryanto (https://github.com/sharyanto)

- Zaki Akhmad (https://github.com/za)


Layout
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- Syaeful Bahri (https://github.com/passionfactory)


Penerbit
------------------------------------------------------------
- Materi buku akan tersedia bebas.

- Buku akan dipublikasikan sendiri.


Model Kontribusi, Royalti, Referensi
------------------------------------------------------------
- Siapa saja bisa berkontribusi dalam buku ini selama 
  tujuannya adalah menulis buku, berbagi untuk sesama dan
  saling belajar. Dengan kata lain, tidak melakukan
  iklan berselubung ataupun jualan. 
  
- Royalti buku sebesar 30% akan didonasikan kepada komunitas
  Python ID. Selebihnya, 70% akan dibagi rata sesuai jumlah
  penulis. Ini dengan asumsi ada penghasilan dari buku.

- Batas waktu bergabung sebagai penulis adalah Hari Kamis,
  10 Juli 2014 20:00 WIB.
  
- Setiap penulis paling tidak harus menulis sebanyak 1 Bab
  atau +/- 15 halaman. 

- Untuk referensi, penulis diharapkan membaca 
  memento teknis OpenERP dan dokumentasi resmi OpenERP. 
  

Jadwal (UTC+7)
------------------------------------------------------------
Selengkapnya tentang jadwal bisa dibaca di:
https://github.com/id-python/buku-openerp/issues/milestones


Laporan
------------------------------------------------------------
- Laporan minggu pertama, dijadwalkan 24 Juli, dilaporkan
  terlambat 2 hari (26 Juli):
  
  - Secara umum, penulisan buku baru berjalan sekitar/kurang
    dari 10 persen. Dua dari tim penulis, yaitu Noprianto 
    dan Widoyo masih 0 persen. 
    
  - Dari dua penerbit yang didekati, satu menolak dan satu
    lagi belum ada keputusan. 
  
- Laporan minggu kedua, dijadwalkan 31 Juli, dilaporkan
  terlambat 5 hari (5 Agustus):
  
  - Secara umum, penulisan buku telah berjalan sekitar
    22,5 persen. 
    
  - Masih belum ada keputusan dari penerbit kedua.
  
- Laporan minggu ketiga, dijadwalkan 8 Agustus, dilaporkan
  terlambat 5 hari (13 Agustus):
  
  - Secara umum, penulisan buku telah berjalan sekitar
    28 persen. Ada kemungkinan buku akan terlambat 
    selesai 1 minggu.
    
  - Penerbit kedua tampaknya kurang antusias. Usaha akan
    terus dilakukan untuk pendekatan ke penerbit, sambil
    tim buku memikirkan cara publikasi lainnya. 

- Naskah buku telah selesai pada hari Kamis, 21 Agustus 2014. 

  - Karena salah satu penulis tidak dapat dihubungi selama
    hari-hari terakhir, dan belum pernah ada tulisan yang 
    dikirimkan, maka isi buku terpaksa disesuaikan sehingga 
    pembahasan tentang workflow dan contoh kasus 2 
    tidak disertakan. Susunan Bab juga ikut berubah.
    
  - Buku akan melalui proses penyuntingan, sebelum diserahkan
    ke penulis kesan singkat. 


Daftar Isi
------------------------------------------------------------

1. Memulai OpenERP
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   - Instalasi OpenERP
   
   - Konfigurasi Database dan OpenERP
   
   - Contoh modul dan data sample


2. Dasar-dasar Kustomisasi 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   
   - Developer Mode 
      
   - Technical Feature
   
   - Menambah field
   
   - Menampilkan field
   
   - Menyembunyikan field dan mengatur posisi

   - Kelebihan dan kekurangan


3. Dasar Pengembangan Modul OpenERP
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   
   - Lingkungan pengembangan OpenERP
   
   - Struktur modul
   
   - Komposisi modul OpenERP 
     
   - Contoh modul sederhana


4. Contoh kasus
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


5. Model pada OpenERP 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   - Hirarki class
    
   - orm.Model, osv.Model dan osv.osv
   
   - Atribut
   
   - Atribut: _columns
   
   - Atribut: _constraints
   
   - Model, tabel database dan field
   
   - Method
   
   - Mengakses OpenERP tanpa server dijalankan
   
   - Method: search
   
   - Method: read
   
   - Method: write
   
   - Method: create
   
   - Method: unlink
   
   - Program: menambah field
   
   - Program: readonly dan nilai default
   
   - Program: constraint
   
   - Program: field functional
   
   - Program: method create/write
   
   
6. Dasar-dasar view
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   - Kerangka
   
   - Field pada model
   
   - Inheritance pada view
   
   - Form: mengatur ulang posisi field
   
   - Form: menambah field
   
   - Form: notebook dan group
   
   - Form: attrs dan atribut lain
   
   - Form: on change
   
   - Form: on change (2)
   
   - Tree: tambah/hapus field
   
   - Menuitem dan editable tree
   
   
7. Dasar-dasar Report 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   - Definisi
   
   - Report dengan RML
   
   - Kerangka RML
   
   - Report pada model
   
   - Custom parser
   
   - Wizard


8.Tip dan Trik
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   - Pelajarilah source code OpenERP
   
   - Generate file konfigurasi
   
   - Lebih dari satu lokasi addons
   
   - Pustaka notation dan notasi prefix/postfix
   
   - Lisensi pada modul OpenERP
   
   - Perubahan pada file python dalam modul
   
   - Menampilkan pesan kesalahan
   
   - Format tanggal/waktu
      

9. Web Service dengan XML-RPC
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   - ERP dan sistem berjalan
   
   - Membangun frontend sendiri
   
   - XML-RPC dan Python
   
   - Pustaka oerpapi
   
   - Program: pilih dan login ke database
   
   - Program: buat, update, baca, hapus
   
   - Program: melakukan pencarian
   
   - Program: laporan
   
   - Program: buat, ganti nama, kopi, hapus database
   
   - Program: dump dan restore database
   
   - Menggunakan xmlrpclib


10. Dasar-dasar Python
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   
   - Penulisan source code
   
   - Sekilas tentang Python
   
   - Interpreter Python (interaktif)
   
   - Script Python
   
   - Tipe builtin, collection dan operator
   
   - Kondisi
   
   - Perulangan
   
   - Fungsi
   
   - Class
   
   - Modul-modul
   
   - Exception
   
   - File

