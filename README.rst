Buku OpenERP (pengembangan)
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


Cara Baca 
------------------------------------------------------------
Buku ini diharapkan untuk dapat dibaca secara berurutan, 
kecuali untuk contoh kasus 1, contoh kasus 2, tip dan trik, 
web service dengan XML-RPC dan dasar-dasar Python
(5 bab terakhir).


Tim Buku (urut abjad)
------------------------------------------------------------

Penulis
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Catatan: Satu bab bisa ditulis oleh lebih dari satu penulis. 
Seiring proses penulisan buku, daftar kontribusi ini mungkin
bisa berubah. 

- Noprianto (https://github.com/nopri)
  (Dari draft daftar isi: 3, 4, 5, 7, 10, 11, 12)

- Setiaji Kurniawan (https://github.com/setiaji)
  (Dari draft daftar isi: 5, 6, 8, 9, 10)

- Whisnu Budhysantika (https://github.com/whisnu)
  (Dari draft daftar isi: 1, 2, 3, 7, 10)

- Widoyo (https://github.com/widoyo)
  (Dari draft daftar isi: 8)


Kesan Singkat
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- Ismail Sunni (http://github.com/ismailsunni)

- Owo Sugiana (https://github.com/sugiana)

- Steven Haryanto (https://github.com/sharyanto)

- Zaki Akhmad (https://github.com/za)


Pendukung Penerbitan
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Tim pendukung penerbitan, apabila ada, akan dicantumkan 
dalam buku. Buku ini membutuhkan bantuan layout, perancang
cover dan ilustrasi. 

- Syaeful Bahri (https://github.com/passionfactory)


Penerbit
------------------------------------------------------------
- Saat ini, buku ini masih belum memiliki penerbit. 

- Pendekatan kepada penerbit akan dilakukan satu demi satu,
  dalam waktu tertentu. Pindah ke calon penerbit lain 
  apabila calon penerbit yang didekati telah menolak.
  
- Bantuan akan sangat diperlukan di sini. 


Model Kontribusi, Royalti, Referensi
------------------------------------------------------------
- Siapa saja bisa berkontribusi dalam buku ini selama 
  tujuannya adalah menulis buku, berbagi untuk sesama dan
  saling belajar. Dengan kata lain, tidak melakukan
  iklan berselubung ataupun jualan. 
  
- Royalti buku sebesar 30% akan didonasikan kepada komunitas
  Python ID. Selebihnya, 70% akan dibagi rata sesuai jumlah
  penulis. 

- Batas waktu bergabung sebagai penulis adalah Hari Kamis,
  10 Juli 2014 20:00 WIB.
  
- Setiap penulis paling tidak harus menulis sebanyak 1 Bab
  atau +/- 15 halaman. 

- Untuk referensi, penulis diharapkan membaca 
  memento teknis OpenERP dan dokumentasi resmi OpenERP. 
  
- Silahkan merevisi Daftar Isi (Draft) di bawah.


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


Daftar Isi (Draft) 
------------------------------------------------------------
Catatan: hanya menampilkan satu level dalam bab. Juga dapat
dianggap sebagai indikasi seberapa jauh sebuah bab telah 
ditulis. 


1. Memulai OpenERP
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   Tujuan Bab ini adalah membahas proses instalasi sampai
   OpenERP siap digunakan dan dikustomisasi. Bagi yang telah
   terbiasa, bab ini bisa dilewatkan. 

   - Instalasi OpenERP
     ::

         Instalasi OpenERP dan paket sistem yang dibutuhkan 
         untuk menjalankan OpenERP. Apabila dirasa penting,
         mungkin kita bisa bahas untuk beberapa sistem operasi
         populer (tidak hanya GNU/Linux).
   
   - Konfigurasi Database dan OpenERP
     ::

         Konfigurasi database server, termasuk pembuatan
         user database. Membahas pula sekilas file konfigurasi
         OpenERP. 
   
   - Modul Sales Management dan data sample
     ::
     
         OpenERP siap digunakan dengan modul sales management dan 
         data sample. Kita gunakan Sales Management karena ini
         cenderung lebih mudah dimengerti.


2. Dasar-dasar Kustomisasi 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   Tujuan Bab ini adalah membahas dasar-dasar kustomisasi 
   OpenERP, dengan fokus kustomisasi TANPA pembuatan module
   (hanya menurunkan lewat UI). Kita bahas juga apa 
   kelebihan dan kekurangannya. 
   
   - Developer Mode 
     ::

         Memanfaatkan developer mode untuk lebih memudahkan 
         mengerti/mengembangkan.
      
   - Technical Feature
     ::

         Kita perlu aktifkan fitur ini kepada user yang ingin
         melakukan kustomisasi.
   
   - Menambah field
     ::

         Menambah field baru ke model.
   
   - Menampilkan field
     ::
     
         Menampilkan field yang ada.
   
   - Menyembunyikan field dan mengatur posisi

   - Kelebihan dan kekurangan


3. Dasar Pengembangan Modul OpenERP
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   Sampai di sini, pembaca telah mengetahui bahwa mereka
   memiliki kebutuhan untuk melakukan kustomisasi lewat
   pengembangan modul. Dasar-dasar pengembangan modul
   akan dibahas dan dijelaskan pada bab ini. 
   
   Apa yang telah dilakukan pada Bab 2 akan ditulis
   ulang menggunakan modul pada Bab ini. 
   
   Pembaca diharapkan memiliki gambaran apa yang 
   dilakukan. Detil akan dibahas pada bab lain. 
   
   Pembaca tahu bahwa hal tersebut bisa dilakukan, 
   dan kita ingin membuatnya sesederhana mungkin. 
   
   - Sekilas Paket Python 
   
   - Lingkungan pengembangan OpenERP
   
   - Struktur modul
   
   - Komposisi modul OpenERP 
     ::

         Sekilas tentang business object, data, wizard, 
         laporan, dll.
     
   - Contoh modul sederhana
     ::
     
         Apa yang dilakukan pada Bab 2 dalam bentuk
         modul.


4. Model pada OpenERP 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   - Hirarki class
    
   - osv.Model dan osv.osv
   
   - Atribut
   
   - Atribut: _columns
   
   - Atribut: _constraints
   
   - Model, tabel database dan field
   
   - Method
   
   - Mengakses OpenERP dari prompt Python
   
   - Method: search
   
   - Method: read
   
   - Method: write
   
   - Method: create
   
   - Method: unlink
   
   - Program 4-1: menambah field
   
   - Program 4-2: readonly dan nilai default
   
   - Program 4-3: constraint
   
   - Program 4-4: field functional
   
   - Program 4-5: method create/write
   
   
5. View
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   Membahas lebih lanjut tentang view pada OpenERP, 
   termasuk dynamic view.
   
   - Form
   
   - Tree
   
   - Dynamic view
   
   - ...
   

6. Workflow
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   Membahas workflow, aktifitas dan transisi. Seperti
   biasa, kita bahas juga beberapa contoh. 
   
7. Laporan 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   Bab ini membahas contoh pembuatan laporan, mulai dari
   yang sangat sederhana, melekat pada model, sampai
   pada yang lebih kompleks dan melibatkan wizard. 
   
   Kita akan membahas sebanyak mungkin contoh. 
   
   - Konsep
   
   - Laporan sederhana
   
   - Pengaturan header
   
   - Wizard
   
   - Output lain


8. Contoh kasus 1
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

9. Contoh kasus 2
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

10.Tip dan Trik
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   Berisikan koleksi tip dan trik dalam pengembangan solusi 
   berbasis OpenERP. 
   
   Migrasi data, yang sebelumnya direncanakan sebagai bab
   tersendiri, akan menjadi bagian dari bab ini. 
      
   Kalau ada pengalaman dari penulis, maka mungkin
   bisa berguna untuk dikemukakan.

11. Web Service dengan XML-RPC
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


12. Dasar-dasar Python
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

