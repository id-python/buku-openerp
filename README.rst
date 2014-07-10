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
kecuali untuk contoh kasus. 


Tim Buku (urut abjad)
------------------------------------------------------------

Penulis:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- Noprianto (https://github.com/nopri)
  (Dari draft daftar isi: 1, 2, 3, 4, 5 (sebagian), 8)

- Setiaji Kurniawan (https://github.com/setiaji)
  (Dari draft daftar isi: )

- Whisnu Budhysantika
  (Dari draft daftar isi: )

- Widoyo 
  (Dari draft daftar isi: )


Kesan Singkat:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- Ismail Sunni

- Owo Sugiana (https://github.com/sugiana)

- Steven Haryanto (https://github.com/sharyanto)

- Zaki Akhmad (https://github.com/za)


Perancang Cover:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
-

Layout:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- 


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
- [2014-07-04] Usulan penulisan buku disampaikan ke mailing list 
  id-python: https://groups.yahoo.com/neo/groups/id-python/conversations/topics/7544
  
- [2014-07-07] Daftar Isi (Draft) tersedia.

- [2014-07-10] Batas akhir pendaftaran tim penulis.

- [2014-07-17] Buku secara resmi mulai ditulis.

- [2014-07-24] Laporan minggu pertama.

- [2014-07-31] Laporan minggu kedua.

- [2014-08-08] Laporan minggu ketiga
  
- [2014-08-14] Buku selesai (konten buku dapat diserahkan 
  kepada penulis kesan singkat).

- [2014-08-17] Cover buku depan dan belakang selesai.

- [2014-08-18] Konten buku diserahkan kepada penerbit.


Daftar Isi (Draft) 
------------------------------------------------------------

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


4. ORM 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   Membahas komponen kunci OpenERP. Di sini, kita
   akan membahas detil atribut, tipe field, method
   dan lainnya. 
   
   Contoh pada Bab 3 akan dikembangkan lebih lanjut.
   
   Contoh-contoh yang dibahas di sini harus
   representatif sehingga pembaca dapat mengembangkan 
   lebih lanjut.

   - Atribut 
    
   - Tipe field
   
   - Method 
   
   - Tips: Override method
   
   
5. View
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   Membahas lebih lanjut tentang view pada OpenERP, 
   termasuk dynamic view.
   
   - Form
   
   - Tree
   
   - Dynamic view
   
   - ...
   

6. Migrasi data
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   Pembaca mungkin perlu melakukan migrasi data
   dari sistem sebelumnya. Kita bisa membahas strategi
   yang bisa dilakukan di sini (yang umum di dunia
   OpenERP).
   
   Kalau ada pengalaman dari penulis, maka mungkin
   bisa berguna untuk dikemukakan.

7. Workflow
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   Membahas workflow, aktifitas dan transisi. Seperti
   biasa, kita bahas juga beberapa contoh. 
   
8. Laporan 
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


9. Contoh kasus 1
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

10.Contoh kasus 2
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

