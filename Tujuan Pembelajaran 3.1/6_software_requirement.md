# Perangkat lunak apa yang saya perlukan untuk membuat situs web?

Anda memerlukan alat untuk:

* Membuat dan mengedit halaman web
* Unggah file ke server web Anda
* Lihat situs web Anda
  
Hampir semua sistem operasi secara default menyertakan editor teks dan browser, yang dapat Anda gunakan untuk melihat situs web. Akibatnya, Anda biasanya hanya perlu memperoleh perangkat lunak untuk mentransfer file ke server web Anda

## Membuat dan mengedit halaman web

Untuk membuat dan mengedit situs web, Anda memerlukan editor teks. Editor teks membuat dan memodifikasi file teks yang tidak diformat. Format lain, seperti RTF , memungkinkan Anda menambahkan pemformatan, seperti huruf tebal atau garis bawah. Format tersebut tidak cocok untuk menulis halaman web. Anda harus memikirkan editor teks mana yang Anda gunakan, karena Anda akan bekerja dengannya secara ekstensif saat membangun situs web.

Semua sistem operasi desktop dilengkapi dengan editor teks dasar. Semua editor ini sangat mudah, tetapi tidak memiliki fitur khusus untuk pengkodean halaman web. Jika Anda menginginkan sesuatu yang lebih menarik, ada banyak alat pihak ketiga yang tersedia. Editor pihak ketiga sering dilengkapi dengan fitur tambahan, termasuk pewarnaan sintaksis, pelengkapan otomatis, bagian yang dapat dilipat, dan pencarian kode. Berikut adalah daftar singkat editor:

<table class="standard-table">
  <thead>
    <tr>
      <th scope="col">Operating system</th>
      <th scope="col">Built-in editor</th>
      <th scope="col">Third-party editor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Windows</td>
      <td>
        <ul>
          <li>
            <a
              href="https://en.wikipedia.org/wiki/Notepad_%28software%29"
              rel="external"
              >Notepad</a
            >
          </li>
        </ul>
      </td>
      <td>
        <ul>
          <li><a href="https://notepad-plus-plus.org/">Notepad++</a></li>
          <li>
            <a href="https://www.visualstudio.com/">Visual Studio Code</a>
          </li>
          <li><a href="https://www.jetbrains.com/webstorm/">Web Storm</a></li>
          <li><a href="http://brackets.io/">Brackets</a></li>
          <li><a href="https://shiftedit.net/">ShiftEdit</a></li>
          <li><a href="https://www.sublimetext.com/">Sublime Text</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Mac OS</td>
      <td>
        <ul>
          <li>
            <a href="https://en.wikipedia.org/wiki/TextEdit" rel="external"
              >TextEdit</a
            >
          </li>
        </ul>
      </td>
      <td>
        <ul>
          <li>
            <a href="https://www.barebones.com/products/textwrangler/"
              >TextWrangler</a
            >
          </li>
          <li>
            <a href="https://www.visualstudio.com/">Visual Studio Code</a>
          </li>
          <li><a href="http://brackets.io/">Brackets</a></li>
          <li><a href="https://shiftedit.net/">ShiftEdit</a></li>
          <li><a href="https://www.sublimetext.com/">Sublime Text</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Linux</td>
      <td>
        <ul>
          <li>
            <a href="https://en.wikipedia.org/wiki/Vi" rel="external">Vi</a>
            (All UNIX)
          </li>
          <li>
            <a href="https://en.wikipedia.org/wiki/Gedit" rel="external"
              >GEdit</a
            >
            (Gnome)
          </li>
          <li>
            <a
              href="https://en.wikipedia.org/wiki/Kate_%28text_editor%29"
              rel="external"
              >Kate</a
            >
            (KDE)
          </li>
          <li>
            <a href="https://en.wikipedia.org/wiki/Leafpad" rel="external"
              >LeafPad</a
            >
            (Xfce)
          </li>
        </ul>
      </td>
      <td>
        <ul>
          <li><a href="https://www.gnu.org/software/emacs/">Emacs</a></li>
          <li><a href="https://www.vim.org/" rel="external">Vim</a></li>
          <li>
            <a href="https://www.visualstudio.com/">Visual Studio Code</a>
          </li>
          <li><a href="http://brackets.io/">Brackets</a></li>
          <li><a href="https://shiftedit.net/">ShiftEdit</a></li>
          <li><a href="https://www.sublimetext.com/">Sublime Text</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Chrome OS</td>
      <td></td>
      <td>
        <ul>
          <li><a href="https://shiftedit.net/">ShiftEdit</a></li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

Berikut adalah tangkapan layar dari editor teks tingkat lanjut:

![ss notepad](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Tools_and_setup/What_software_do_I_need/notepadplusplus.png)


Berikut adalah screenshot dari editor teks online:
![ss notepad](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Tools_and_setup/What_software_do_I_need/shiftedit.png)

## Mengunggah file di Web
Saat situs web Anda siap untuk dilihat publik, Anda harus mengunggah halaman web Anda ke server web Anda. Anda dapat membeli ruang di server dari berbagai penyedia (lihat Berapa biaya untuk melakukan sesuatu di web? ). Setelah Anda menentukan penyedia mana yang akan digunakan, penyedia akan mengirimkan informasi akses melalui email kepada Anda, biasanya dalam bentuk URL SFTP, nama pengguna, kata sandi, dan informasi lain yang diperlukan untuk terhubung ke server mereka. Ingatlah bahwa (S)FTP sekarang agak kuno, dan sistem pengunggahan lainnya mulai menjadi populer, seperti RSync dan Git/GitHub .
> Catatan: FTP pada dasarnya tidak aman. Anda harus memastikan bahwa penyedia hosting Anda mengizinkan penggunaan koneksi yang aman, misalnya SFTP atau RSync melalui SSH.

Mengunggah file ke server web adalah langkah yang sangat penting saat membuat situs web. Untuk saat ini, berikut adalah daftar singkat klien dasar (S)FTP gratis:

<table class="standard-table">
  <thead>
    <tr>
      <th scope="col">Operating system</th>
      <th colspan="2" scope="col">FTP software</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Windows</td>
      <td>
        <ul>
          <li><a href="https://winscp.net">WinSCP</a></li>
          <li><a href="https://mobaxterm.mobatek.net/">Moba Xterm</a></li>
        </ul>
      </td>
      <td rowspan="3">
        <ul>
          <li>
            <a href="https://filezilla-project.org/">FileZilla</a> (All OS)
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Linux</td>
      <td>
        <ul>
          <li>
            <a
              href="https://wiki.gnome.org/action/show/Apps/Files?action=show&#x26;redirect=Apps%2FNautilus"
              rel="external"
              >Nautilus/Files</a
            >
            (Gnome)
          </li>
          <li>
            <a href="https://dolphin.com/" rel="external">Dolphin</a> (KDE)
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Mac OS</td>
      <td>
        <ul>
          <li><a href="https://cyberduck.de/">Cyberduck</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Chrome OS</td>
      <td>
        <ul>
          <li><a href="https://shiftedit.net/">ShiftEdit</a> (All OS)</li>
        </ul>
      </td>
      <td></td>
    </tr>
  </tbody>
</table>

*Source* : [mdn web docs_](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Tools_and_setup/What_software_do_I_need)

*Thanks To* : [roadmap.sh](https://roadmap.sh/)

[Home](README.md) | [Back](5_web_browser.md)