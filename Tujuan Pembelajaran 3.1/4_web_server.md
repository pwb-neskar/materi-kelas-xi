# Web Server / Server Web

Istilah server web dapat merujuk pada perangkat keras atau perangkat lunak, atau keduanya bekerja bersama.

1. Di sisi perangkat keras, server web adalah komputer yang menyimpan perangkat lunak server web dan file komponen situs web (misalnya, dokumen HTML, gambar, lembar gaya CSS, dan file JavaScript). Server web terhubung ke Internet dan mendukung pertukaran data fisik dengan perangkat lain yang terhubung ke web.
2. Di sisi perangkat lunak, server web menyertakan beberapa bagian yang mengontrol cara pengguna web mengakses file yang dihosting. Minimal, ini adalah server HTTP . Server HTTP adalah perangkat lunak yang memahami URL (alamat web) dan HTTP (protokol yang digunakan browser Anda untuk melihat halaman web). Server HTTP dapat diakses melalui nama domain dari situs web yang disimpannya, dan mengirimkan konten dari situs web yang dihosting ini ke perangkat pengguna akhir.

Pada tingkat paling dasar, setiap kali browser membutuhkan file yang dihosting di server web, browser meminta file tersebut melalui HTTP. Ketika permintaan mencapai server web (perangkat keras) yang benar, server HTTP (perangkat lunak) menerima permintaan, menemukan dokumen yang diminta, dan mengirimkannya kembali ke browser, juga melalui HTTP. (Jika server tidak menemukan dokumen yang diminta, server akan mengembalikan respons 404. )

![webserver&browser](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_web_server/web-server.svg)

Representasi dasar dari koneksi klien/server melalui HTTP
Untuk menerbitkan situs web, Anda memerlukan server web statis atau dinamis.

**Server web statis** , atau tumpukan, terdiri dari komputer (perangkat keras) dengan server HTTP (perangkat lunak). Kami menyebutnya "statis" karena server mengirimkan file yang dihosting apa adanya ke browser Anda.

**Server web dinamis** terdiri dari server web statis ditambah perangkat lunak tambahan, paling sering adalah server aplikasi dan database . Kami menyebutnya "dinamis" karena server aplikasi memperbarui file yang dihosting sebelum mengirim konten ke browser Anda melalui server HTTP.

Misalnya, untuk menghasilkan halaman web akhir yang Anda lihat di browser, server aplikasi mungkin mengisi template HTML dengan konten dari database. Situs seperti MDN atau Wikipedia memiliki ribuan halaman web. Biasanya, situs semacam ini hanya terdiri dari beberapa template HTML dan database raksasa, bukan ribuan dokumen HTML statis. Penyiapan ini mempermudah pemeliharaan dan pengiriman konten.




*Thanks To* : [roadmap.sh](https://roadmap.sh/)

[Home](README.md)
[Back](3_website_dan_halaman_web.md)
[Next](5_web_browser.md)
