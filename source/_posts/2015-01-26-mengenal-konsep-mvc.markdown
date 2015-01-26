---
layout: post
title: "Mengenal Konsep MVC"
date: 2015-01-26 22:19:46 +0700
comments: true
categories: pemrograman
---

**Model-View-Controller** atau **MVC** adalah sebuah metode untuk membuat sebuah aplikasi dengan memisahkan data (Model) dari tampilan (View) dan cara bagaimana memprosesnya (Controller). 

Dalam implementasinya kebanyakan framework dalam aplikasi website adalah berbasis arsitektur MVC. MVC memisahkan pengembangan aplikasi berdasarkan komponen utama yang membangun sebuah aplikasi seperti manipulasi data, antarmuka pengguna, dan bagian yang menjadi kontrol dalam sebuah aplikasi web.

{% img http://upload.wikimedia.org/wikipedia/commons/b/b5/ModelViewControllerDiagram2.svg %}

### Sejarah
Model View Controller pertama sekali dipublikasikan oleh peneliti XEROX PARC yang bekerja dalam pembuatan bahasa pemrograman Smalltalk sekitar tahun 1970-1980.

### Bagian dari MVC

- Model, Model mewakili struktur data. Biasanya model berisi fungsi-fungsi yang membantu seseorang dalam pengelolaan basis data seperti memasukkan data ke basis data, pembaruan data dan lain-lain.
- View, View adalah bagian yang mengatur tampilan ke pengguna. Bisa di katakan berupa halaman web.
- Controller, Controller merupakan bagian yang menjembatani model dan view. Controller berisi perintah-perintah yang berfungsi untuk memproses suatu data dan mengirimkannya ke halaman web.

Dengan menggunakan metode MVC maka aplikasi akan lebih mudah untuk dirawat dan dikembangkan. Untuk memahami metode pengembangan aplikasi menggunakan MVC diperlukan pengetahuan tentang pemrograman berorientasi objek (Object Oriented Programming).

### Jenis MVC pada website

- Server Side MVC, Server Side MVC biasa terjadi pada aplikasi web tradisional, yang tidak melibatkan client side seperti Javascript, Java applet, Flash, dan lain-lain. Server Side MVC menyerahkan keseluruhan proses bisnis pada server, aplikasi pada sisi pengguna hanya dapat menerima. MVC jenis ini kadang-kadang disebut juga dengan nama Thin Client.
- Mixed Client Side and Server Side MVC, Pada Mixed Client Side and Server Side MVC 1 client tidak menggunakan model sebagai jembatan untuk melakukan komunikasi pada server, dibandingkan dengan Server Side MVC, arsitektur ini memiliki tingkat kompleksitas yang lebih tinggi karena lebih banyak komponen yang terlibat. Untuk selanjutnya arsitektur ini disebut, dengan Mixed MVC 1. Pada Mixed Client Side and Server Side MVC 2, client menggunakan model sebagai jembatan untuk melakukan komunikasi pada server, dibandingkan dengan arsitektur MVC yang lain, arsitektur ini memiliki tingkat kompleksitas yang paling tinggi karena lebih banyak komponen yang terlibat, sehingga membutuhkan sumber daya yang lebih besar pula. Untuk selanjutnya arsitektur ini disebut dengan Mixed MVC 2.
- Rich Internet Application MVC, Application MVC Rich Internet Application (RIA) disebut juga dengan nama Fat Client, merupakan aplikasi web yang memiliki kemampuan dan fungsi hampir seperti aplikasi desktop. RIA pada sisi client, memiliki mesin untuk mengambil data yang berada pada server, sehingga pada client terdapat bagian MVC sendiri dan hanya membutuhkan bagian model pada sisi server.
<br>
Sumber : [wikipedia](http://id.wikipedia.org/wiki/MVC)