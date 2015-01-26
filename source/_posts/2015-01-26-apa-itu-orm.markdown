---
layout: post
title: "Apa itu ORM ?"
date: 2015-01-26 22:20:14 +0700
comments: true
categories: 
---

**Pemetaan objek-relasional**(object-relational mapping atau O/RM) merupakan sebuah teknik yang digunakan dalam pemrograman untuk menggunakan basisdata relasional sebagai penyimpanan data dengan bentuk obyek. Teknik ini biasa digunakan dalam bahasa pemrograman berorientasi objek saat harus menggunakan basisdata relasional dalam penyimpanannya.

### Masalah
Pemrograman berorientasi obyek menggunakan cara pandang obyek dalam dunia nyata untuk melihat sistem. Contoh: seorang Manusia mempunyai atribut yang melekat pada dirinya berupa nama, alamat, tanggal lahir, dan sebagainya. Mahasiswa merupakan manusia, maka Mahasiswa mewarisi semua sifat manusia.

Dalam penyimpanannya ke dalam basisdata, penurunan sifat maupun hubungan antar objek daat menjadi masalah tersendiri. Apalagi sebuah objek mendukung aksi(method) akan tetapi tidak dengan basis data.

### Pemecahan
Bahasa pemrograman menggunakan O/RM untuk memetakan objek ke dalam database. Objek yang kita masukkan akan dibaca oleh O/RM tersebut kemudian diubah ke dalam Sintaks SQL. Selanjutnya baru kemudian dijalankan di basisdata relasional dan hasilnya kembali ke O/RM.
<br>
Sumber : [wikipedia](http://id.wikipedia.org/wiki/Pemetaan_objek-relasional)