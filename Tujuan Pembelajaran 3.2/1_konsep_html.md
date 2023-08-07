# HTML

## Sejarah Singkat HTML

Pada tahun 1990, sebagai bagian dari visinya tentang Web, Tim Berners-Lee mendefinisikan konsep hypertext , yang diresmikan oleh Berners-Lee pada tahun berikutnya melalui markup yang sebagian besar didasarkan pada SGML . IETF mulai menetapkan HTML secara resmi pada tahun 1993, dan setelah beberapa draf merilis versi 2.0 pada tahun 1995. Pada tahun 1994 Berners-Lee mendirikan W3C untuk mengembangkan Web. Pada tahun 1996, W3C mengambil alih pekerjaan HTML dan menerbitkan rekomendasi HTML 3.2 setahun kemudian. HTML 4.0 dirilis pada tahun 1999 dan menjadi standar ISO pada tahun 2000.

Pada saat itu, W3C hampir meninggalkan HTML demi XHTML , mendorong pendirian grup independen yang disebut WHATWG pada tahun 2004. Berkat WHATWG, pengerjaan HTML berlanjut: kedua organisasi tersebut merilis draf pertama HTML5 pada tahun 2008 dan standar resmi pada tahun 2014. Istilah "HTML5" hanyalah kata kunci yang mengacu pada teknologi web modern yang merupakan bagian dari HTML Living Standard .
## Perkembangan dan versi HTML 

<div style="text-align: justify">
HTML punya beberapa versi, dari versi yang paling tua hingga yang terbaru. Berikut ini perkembangan versi HTML:

1. HTML 1.0 (Juni 1993)
2. HTML 2.0 (24 November 1995)
3. HTML 3.0 (28 Maret 1995)
4. HTML 3.2 (14 Januari 1997)
5. HTML 4.0 (24 April 1998)
6. XHTML 1.0 (26 Januari 2000)
7. HTML 5 (22 Januari 2008)
   Perkembangan HTML5:
   |Versi|Draft Awal|Kandidat Rilis|Rilis Resmi|
   |---|---|---|---|
   |HTML 5.0|2007|2012|2014|
   |HTML 5.1|2012|2012|2016|
   |HTML 5.2|2015|2017|2017|
   |HTML 5.3|2017|N/A|N/A|

</div>

## Fungsi HTML

<div style="text-align: justify">Setelah mengenal sejarah singkat dari bahasa markup HTML, selanjutnya kita juga harus mengetahui kegunaannya. Berikut ini beberapa fungsi dan tujuan dari penerapan HTML untuk pembuatan situs atau web app.

Fungsi utama penggunaan HTML sendiri adalah membangun tampilan website yang telah menerapkan metode semantik untuk memudahkan setiap pengembang dalam proses development dan maintenance. Kemudian, HTML juga dapat dikolaborasikan dengan penggunaan bahasa CSS (Cascade Style Sheet) serta JavaScript.
Dimana, peran dari HTML5 berfungsi untuk menyusun kerangka dan struktur halaman website. Kemudian, CSS membantu dalam memberikan tampilan desain meliputi warna, font, outline, dan lain sebagainya. Dan Tugas dari bahasa pemrograman JavaScript adalah memberikan sentuhan interaksi untuk memberikan pengalaman yang berbeda kepada user.
</div>

## Konsep dan sintaksis HTML

Dokumen HTML adalah dokumen teks biasa yang disusun dengan elemen. Elemen dikelilingi oleh tag pembuka dan penutup yang cocok. Setiap tag diawali dan diakhiri dengan tanda kurung sudut ( <>). Ada beberapa elemen kosong atau kosong yang tidak dapat menyertakan teks apa pun, misalnya ```<img>```.
File HTML biasanya disimpan dengan ekstensi .htm atau .html, dilayani oleh server web , dan dapat dirender oleh browser Web apa pun.
Anda dapat memperluas tag HTML dengan atribut , yang memberikan informasi tambahan yang memengaruhi cara browser menginterpretasikan elemen:

![anatomy html](https://github.com/mdn/content/raw/main/files/en-us/learn/html/introduction_to_html/getting_started/grumpy-cat-small.png)

Anatomi elemen diatas adalah:

1. ***Opening Tag / Tag Pembuka***: Ini terdiri dari nama elemen (dalam contoh ini, p untuk paragraf), dibungkus dengan tanda kurung siku buka dan tutup. Tag pembuka ini menandai di mana elemen mulai atau mulai berlaku. Dalam contoh ini, itu mendahului awal teks paragraf.
2. ***Content / Konten***: Ini adalah konten elemen. Dalam contoh ini, itu adalah teks paragraf.
3. ***Close tag / Tag Penutup***: Ini sama dengan tag pembuka, kecuali ada garis miring sebelum nama elemen. Ini menandai di mana elemen berakhir. Gagal memasukkan tag penutup adalah kesalahan pemula yang umum yang dapat menghasilkan hasil yang aneh.

### Nesting Elements / Elemen Bersarang

Elemen dapat ditempatkan di dalam elemen lain. Ini disebut bersarang . Jika kita ingin menyatakan bahwa kucing kita **sangat** pemarah , kita dapat membungkus kata sangat dalam elemen ```<strong>```, yang berarti kata tersebut memiliki pemformatan teks strong(er):

```html
<p>Kucing saya <strong>sangat</strong> pemarah.</p>
```

Ada cara yang benar dan salah dalam melakukan nesting. Pada contoh di atas, kita buka ```p``` dulu elemennya, baru buka ```strong``` elemennya. Untuk nesting yang tepat, kita harus menutup ```strong``` elemen terlebih dahulu, sebelum menutup ```p```.

Berikut adalah contoh cara melakukan nesting yang *salah* :

```html
<p>Kucing saya <strong>sangat pemarah.</p></strong>
```

Tag **harus membuka dan menutup sedemikian rupa sehingga berada di dalam atau di luar satu sama lain**. Dengan jenis tumpang tindih pada contoh di atas, browser harus menebak maksud Anda. Tebakan semacam ini dapat menghasilkan hasil yang tidak terduga.

### Void Elements / Elemen Kosong

Tidak semua elemen mengikuti pola tag pembuka, konten, dan tag penutup. Beberapa elemen terdiri dari satu tag, yang biasanya digunakan untuk menyisipkan/menyematkan sesuatu ke dalam dokumen. Elemen seperti itu disebut void element. Misalnya, elemen ```<img>``` menyematkan file gambar ke halaman:

```html
<img
  src="https://raw.githubusercontent.com/mdn/beginner-html-site/gh-pages/images/firefox-icon.png"
  alt="Firefox icon" />
```

Ini akan menampilkan yang berikut:

![output img](https://raw.githubusercontent.com/mdn/beginner-html-site/gh-pages/images/firefox-icon.png)



## Attributes

Elemen juga dapat memiliki atribut. Atribut terlihat seperti ini:
![attribut](https://github.com/mdn/content/raw/main/files/en-us/learn/html/introduction_to_html/getting_started/grumpy-cat-attribute-small.png)

Atribut berisi informasi tambahan tentang elemen yang tidak akan muncul di konten. Dalam contoh ini, classatribut adalah nama pengenal yang digunakan untuk menargetkan elemen dengan informasi gaya.

Atribut harus memiliki:

* Spasi antara itu dan nama elemen. (Untuk elemen dengan lebih dari satu atribut, atribut juga harus dipisahkan oleh spasi.)
* Nama atribut, diikuti dengan tanda sama dengan.
* Nilai atribut, dibungkus dengan tanda kutip pembuka dan penutup.

## Anatomi dokumen HTML

Elemen HTML individu tidak terlalu berguna dengan sendirinya. Selanjutnya, mari kita periksa bagaimana masing-masing elemen digabungkan untuk membentuk seluruh halaman HTML:

```html
<!doctype html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <title>My test page</title>
  </head>
  <body>
    <p>This is my page</p>
  </body>
</html>
```

Di sini kita memiliki:
1. ```<!DOCTYPE html>```: Jenis dok. Ketika HTML masih muda (1991-1992), doctype dimaksudkan untuk bertindak sebagai tautan ke seperangkat aturan yang harus diikuti halaman HTML agar dianggap sebagai HTML yang baik. Doctypes biasanya terlihat seperti ini:

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
```

Baru-baru ini, doctype adalah artefak sejarah yang perlu disertakan agar yang lainnya berfungsi dengan benar. ```<!DOCTYPE html>``` adalah rangkaian karakter terpendek yang dianggap sebagai tipe dokumen yang valid. Hanya itu yang perlu Anda ketahui!
2. ```<html></html>```: Elemen . Elemen ini membungkus semua konten di halaman. Kadang-kadang dikenal sebagai elemen root.
3. ```<head></head>```: Elemen ```<head>```. Elemen ini bertindak sebagai wadah untuk semua yang ingin Anda sertakan di halaman HTML, bukan konten yang akan ditampilkan halaman tersebut kepada pemirsa. Ini termasuk kata kunci dan deskripsi halaman yang akan muncul di hasil pencarian, CSS untuk menata konten, deklarasi kumpulan karakter, dan banyak lagi. Anda akan mempelajari lebih lanjut tentang ini di artikel seri berikutnya.
4. ```<meta charset="utf-8">```: Elemen ```<meta>```. Elemen ini mewakili metadata yang tidak dapat diwakili oleh elemen terkait meta HTML lainnya, ```<base>```, ```<link>```, ```<script>```, ```<style>``` atau ```<title></title>```. Atribut charsetmenentukan pengkodean karakter untuk dokumen Anda sebagai UTF-8, yang menyertakan sebagian besar karakter dari sebagian besar bahasa tulisan manusia. Dengan pengaturan ini, halaman sekarang dapat menangani konten tekstual apa pun yang mungkin ada di dalamnya. Tidak ada alasan untuk tidak menyetel ini, dan ini dapat membantu menghindari beberapa masalah di kemudian hari.
5. ```<title></title>```: Elemen ```<title>```. Ini menetapkan judul halaman, yang merupakan judul yang muncul di tab browser tempat halaman dimuat. Judul halaman juga digunakan untuk mendeskripsikan halaman saat di-bookmark.
6. ```<body></body>```: Elemen ```<body>```. Ini berisi semua konten yang ditampilkan di halaman, termasuk teks, gambar, video, game, trek audio yang dapat diputar, atau apa pun.

## Menyertakan karakter khusus dalam HTML

Dalam HTML, karakter ```<```,```>```,```"```,```'```, dan ``` &``` merupakan karakter khusus. Mereka adalah bagian dari sintaks HTML itu sendiri. Jadi, bagaimana Anda memasukkan salah satu karakter khusus ini ke dalam teks Anda? Misalnya, jika Anda ingin menggunakan ampersand atau tanda kurang dari, dan tidak menafsirkannya sebagai kode.

Anda melakukan ini dengan referensi karakter. Ini adalah kode khusus yang mewakili karakter, untuk digunakan dalam keadaan yang tepat ini. Setiap referensi karakter dimulai dengan ampersand (```&```), dan diakhiri dengan titik koma (```;```).

|Karakter|literal	Persamaan referensi karakter|
|---|---|
|```<```|```&lt;```|
|```>```|```&gt;```|
|```"```|```&quot;```|
|```'```|```&apos;```|
|```&```|```&amp;```|

Padanan referensi karakter dapat dengan mudah diingat karena teks yang digunakannya dapat dilihat sebagai kurang dari '<', kutipan untuk ' " ' dan juga untuk orang lain. Untuk mengetahui lebih lanjut tentang referensi entitas, [lihat Daftar referensi entitas karakter XML dan HTML](https://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references) (Wikipedia).

Dalam contoh di bawah ini, ada dua paragraf:
```html
<p>In HTML, you define a paragraph using the <p> element.</p>

<p>In HTML, you define a paragraph using the &lt;p&gt; element.</p>
```


```html
<p>I'm not inside a comment</p>

<!-- <p>I am!</p> -->
```


## komentar HTML

HTML memiliki mekanisme untuk menulis komentar dalam kode. Browser mengabaikan komentar, secara efektif membuat komentar tidak terlihat oleh pengguna. Tujuan komentar adalah untuk memungkinkan Anda menyertakan catatan dalam kode untuk menjelaskan logika atau pengkodean Anda. Ini sangat berguna jika Anda kembali ke basis kode setelah pergi cukup lama sehingga Anda tidak sepenuhnya mengingatnya. Demikian pula, komentar sangat berharga karena orang yang berbeda membuat perubahan dan pembaruan.

Untuk menulis komentar HTML, bungkus dengan penanda khusus ```<!--``` dan ```-->```. Misalnya:

## Jenis – Jenis Tag HTML

 Untuk saat ini, terdapat dua jenis tag yang sering digunakan, yaitu sebagai berikut:

1. Block Level
Untuk elemen yang menggunakan block level menggunakan ruang (space) tersedia dan membuat line atau baris baru untuk mendeklarasikan elemen berikutnya. Contoh dari penggunaan block level adalah struktur heading dan paragraf.

2. Inline Tags
Inline tags berarti menggunakan ruang yang lebih sedikit dan sempit. Sehingga kebutuhannya lebih ke arah memformat isi konten pada block level.

### Referensi : 
1. [mdn web docs_](https://developer.mozilla.org/en-US/docs/Glossary/HTML)
2. [petanikode.com](https://www.petanikode.com/sejarah-html/)
3. [sekawanmedia.co.id](https://www.sekawanmedia.co.id/blog/pengertian-html/#:~:text=Sejarah%20HTML%20pertama%20kali%20dibuat,dalamnya%20terdalam%20sekitar%2018%20tag.)
