# Proyek pembuatan website sederhana untuk kegiatan PKM-PI di SMK Bina Informatika

Proyek website yang kami ciptakan sangatlah mudah dimengerti dan mudah dipahami oleh berbagai kalangan. 
Disini kami akan secara menyeluruh menjelaskan tata cara penginstalan text editor sampai tahap melakukan pengkodingan dalam bahasa HTML dan CSS serta penambahan library khusus yaitu Bootstrap.

## Instalasi

Sebelum kita membuat website sederhana nya, kita perlu menyiapkan tools pendukung agar proses pengkodingan berjalan dengan lancar. 
Nah sama halnya dalam menggambar, kita perlu menyiapkan kanvas atau kertas sebagai media menggambarnya. 
Namun, di dunia pemrograman, kanvas yang kita pakai biasa disebut Text Editor. 
Apa itu Text Editor? Text Editor adalah sebuah software aplikasi yang memungkinkan kita "manusia" melakukan perubahan-perubahan pada file teks yang kita miliki menjadi teks yang kita inginkan.

Nah, dari banyaknya Text Editor yang ada di dunia, beberapa sudah mungkin kita dengar atau kenal, seperti 2 Contoh dibawah ini:
1. Visual Studio Code

- note : untuk instalasi visual studio code, bisa kalian klik link dibawah ini .

khusus OS Windows: 
https://code.visualstudio.com/sha/download?build=stable&os=win32-x64-user

khusus OS linux Debian & Ubuntu:
https://code.visualstudio.com/sha/download?build=stable&os=linux-deb-x64

khusus OS linux Red Hat, Fedora, SUSE:
https://code.visualstudio.com/sha/download?build=stable&os=linux-rpm-x64

khusus OS Mac:
https://code.visualstudio.com/sha/download?build=stable&os=darwin-universal


2. Sublime Text

- note : untuk instalasi sublime text, bisa kalian klik link dibawah ini.

khusus OS windows:
https://download.sublimetext.com/Sublime%20Text%20Build%203211%20Setup.exe

khusus OS linux Debian, Ubuntu:
https://download.sublimetext.com/sublime-text_build-3211_amd64.deb

khusus OS linux Red Hat, Fedora:
https://download.sublimetext.com/sublime-text-3211-1.x86_64.rpm

- note : untuk pengguna OS linux, disarankan membaca dokumentasi langsung dari situs sublime nya, karena mereka sudah menyediakan langkah-langkah apa saja yang diperlukan.
link dokumentasi sublime: https://www.sublimetext.com/docs/3/linux_repositories.html

khusus OS Mac:
https://download.sublimetext.com/Sublime%20Text%20Build%203211.dmg

Apabila Text Editor sudah kita install, maka langkah selanjutnya, kita perlu yang namanya Web Server. 
Nah, untungnya, ada 1 software yang memungkinkan kita menjalankan program HTML, CSS, dan PHP secara bersamaan. 
Software itu adalah XAMPP.

XAMPP adalah sebuah software berbasis web server yang sifatnya open source. 
Kalau kita mendengar kata open source, artinya, aplikasi ini gratis, yang mana dapat dipakai oleh berbagai kalangan.

Lalu, bagaimana sih cara instalasi XAMPP?

- note : klik link dibawah ini untuk menginstall XAMPP.

khusus OS Windows:
https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/8.1.10/xampp-windows-x64-8.1.10-0-VS16-installer.exe

khusus OS Linux:
https://sourceforge.net/projects/xampp/files/XAMPP%20Linux/8.1.10/xampp-linux-x64-8.1.10-0-installer.run

khusus OS Mac:
https://sourceforge.net/projects/xampp/files/XAMPP%20Mac%20OS%20X/8.1.6/xampp-osx-8.1.6-0-installer.dmg

Untuk proses konfigurasi dan setup aplikasinya, kalian bisa baca halaman FAQ (Frequently Asked Questions) milik XAMPP.

FAQ khusus OS Windows:
https://www.apachefriends.org/faq_windows.html

FAQ khusus OS Linux:
https://www.apachefriends.org/faq_linux.html

FAQ khusus OS Mac:
https://www.apachefriends.org/faq_osx.html

## Setup

Setelah proses instalasi selesai, maka kita perlu melakukan setup terlebih dahulu untuk salah satu dari 2 Text Editor yang telah kita install.
Untuk Dokumentasinya, akan kami berikan kepada kalian.

1. Visual Studio Code

khusus OS windows:
Dokumentasi: https://code.visualstudio.com/docs/setup/windows

khusus OS linux:
Dokumentasi: https://code.visualstudio.com/docs/setup/linux

khusus OS Mac:
Dokumentasi: https://code.visualstudio.com/docs/setup/mac

2. Sublime Text

khusus OS windows:
Dokumentasi: https://www.sublimetext.com/docs/command_line.html#windows

khusus OS linux:
Dokumentasi: https://www.sublimetext.com/docs/command_line.html#linux

khusus OS Mac:
Dokumentasi: https://www.sublimetext.com/docs/command_line.html#mac

## Penggunaan (Koding)

Nah, disini kami akan memberikan 2 Contoh saja, bagaimana cara mengimplementasikan bahasa HTML dan CSS

1. Silahkan kalian buka salah satu dari 2 Text Editor diatas.
2. Sekarang, kita perlu membuat file baru. Untuk caranya, akan kami berikan dibawah ini.

khusus Visual Studio Code:
klik **file > new file > inputkan nama file nya**

khusus Sublime Text:
klik **file > new file**

- note : untuk nama file bebas.

3. Apabila file baru sudah terbentuk, kita bisa langsung save file nya. Lalu, setelah itu kita ganti nama filenya dan jenis file nya. Untuk caranya akan kami jelaskan dibawah ini.

khusus Visual Studio Code:
- save file = klik **file > save**

khusus Sublime Text:
- save file = klik **file > save > masukkan nama file nya**

kalau sudah, kita buka File Explorer (Windows) atau Repository apapun yang sesuai dengan OS masing-masing. Kita cari file yang kita buat sebelumnya. jika sudah ketemu maka, kita perlu mengganti jenis filenya menjadi **.html**.

caranya: klik pada file, ketuk 2 kali, lalu tambahkan dibelakang nama file dengan **.html**.

4. Apabila sudah, maka kita kembali ke Text Editor yang kita pakai. Lalu ketikkan kode yang ada dibawah ini.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Page</title>
</head>
<body>
    <h1>Hello World!</h1>
    <p>Ini adalah tampilan Website pertamaku</p>
</body>
</html>
```

5. Kalau sudah, kita perlu menyalakan web server XAMPP untuk bisa melihat secara jelas website yang telah kita buat.

khusus Windows dan Mac OS:
**pertama**, kita perlu membuka software XAMPP nya terlebih dahulu.
**kedua**, kita klik **start** pada Module Apache dan MySql.
**ketiga**, kita klik kanan pada file html kita.

- note : lakukan klik kanan pada filenya, di file explorer, lalu pilih **open with atau open** ke browser yang kalian miliki.

khusus Linux:

ketikkan command seperti dibawah ini.

```console
your-name@bar:~$ /opt/lampp/lampp start
Starting XAMPP for Linux 8.1.10-0...
XAMPP: Starting Apache...ok.
XAMPP: Starting MySQL...ok.
```

6. Website yang kita buat sudah muncul di depan layar laptop/pc. Namun, apabila sudah dirasa cukup, jangan lupa untuk menonaktifkan kembali Apache dan MySql nya, dengan cara, klik **stop** pada Module Apache dan MySql. 

khusus Linux:

ketikkan command seperti dibawah ini.

```console
your-name@bar:~$ /opt/lampp/lampp stop
Stopping XAMPP for Linux 8.1.10-0...
XAMPP: Stopping Apache...ok.
XAMPP: Stopping MySQL...ok.
```
