---
description: >-
  Jenis pembayaran yang menggunakan metode payment gateway (Virtual Account,
  E-wallet, Convenience Store, dan lainnya)
---

# Xendit

Disclaimer: Sebelum melakukan setting pembayaran, di sarankan untuk setting terlebih dahulu produk, asset-asset web anda, whatsapp service (notifikasi pesanan otomatis)\
\
Langkah-langkah yang harus di lakukan untuk setting xendit:\
\
1\. Daftar akun xendit Anda melalui [tautan berikut ini](https://dashboard.xendit.co/register/1) dan isi semua informasi yang dibutuhkan, jangan lupa memasukan referal/promo code 84095BE1\
Setelah terdaftar, Anda akan diarahkan menuju sebuah laman di mana kami akan menanyakan beberapa pertanyaan tambahan untuk menentukan produk apa yang bisa Anda gunakan\*\
\
catatan: pilih akun individu jika belum memiliki perizinan badan, agar dapat aktivasi instan.\


<figure><img src="../../.gitbook/assets/daftar xendit.png" alt=""><figcaption></figcaption></figure>

2\. Setelah semua pertanyaan terjawab, Anda akan diarahkan ke dasbor Anda dalam mode tes\
3\. Verifikasi alamat email Anda dan Anda sudah siap untuk merasakan dasbor Xendit dalam mode tes

<figure><img src="../../.gitbook/assets/akun test xendit (3).png" alt=""><figcaption></figcaption></figure>

Untuk bisa mulai melakukan transaksi riil, Anda harus melakukan aktivasi akun terlebih dahulu.&#x20;

Ikuti 3 langkah sederhana berikut ini untuk mengaktivasi akun Anda:

1. Pergi menuju bagan Mulai Langsung di halaman utama dasbor Xendit Anda
2. Selesaikan semua langkah yang dibutuhkan satu persatu dari Jelajahi Xendit hingga Dokumen
3. Tunggu 1-3 hari kerja ke depan dan kami akan mengirimkan email kepada Anda ketika akun Anda berhasil diaktivasi\*

Catatan:

*   Jika Anda merupakan individu yang bergerak pada bidang industri dengan resiko rendah dari Indonesia, Anda dapat melakukan aktivasi instan dengan beberapa [batasan](https://docs.xendit.co/id/getting-started/activate-account#ketersediaan-produk-dan-fitur).\


    <figure><img src="../../.gitbook/assets/Account+Activation+OW (1).gif" alt=""><figcaption><p>Keterangan:<br>Contoh pengisian aktivasi akun xendit</p></figcaption></figure>



4\. Integrasi API Xendit ke website Anda\
Setelah akun anda berhasil terverifikasi/live dan dapat melakukan transaksi rill maka Anda dapat melanjutkan proses integrasi API Xendit Anda, dan mengatur callback transaksinya pada website Xendit > setelah melakukan login akun\
\
Langkah-langkah yang harus di lakukan:\
a. Masuk akun xendit anda, lalu masuk menu > pengaturan\


<figure><img src="../../.gitbook/assets/laman dashboard xendit.png" alt=""><figcaption><p>Keterangan: <br>a. Masuk menu pengaturan untuk mulai mengatur API Key dan Callback<br>b. Untuk rubah bahasa pada akun xendit Anda</p></figcaption></figure>

b. setelah anda masuk pada menu tersebut, maka silahkan masuk pada menu Developer > API keys

<figure><img src="../../.gitbook/assets/xendit setup api (1).png" alt=""><figcaption></figcaption></figure>

c.  Lalu setelah itu pilih Buat secret key baru&#x20;

<figure><img src="../../.gitbook/assets/api keys xendit - Copy.png" alt=""><figcaption></figcaption></figure>

d. Maka akan tampil beberapa pilihan sebagai berikut, kemudian silahkan isi nama toko anda, lalu pilih beberapa pilihan yang sesuai:\


<figure><img src="../../.gitbook/assets/api keys xendit 1.png" alt=""><figcaption><p>Keterangan:<br>a. Silahkan isi nama API Key, sesuai nama toko Anda<br>b. Pilih beberapa pilihan sesuai petunjuk<br>c. silahkan mulai buat API key Anda</p></figcaption></figure>

catatan: Setelah selesai anda akan di minta untuk verifikasi dengan memasukan password akun xendit anda, dan setelah itu akan tampil detail API key Anda.\
\
Silahkan di simpan/copy API key Anda di tempat yang aman, nantinya akan di masukan di dashboard panel website kakak. Tampilan pop-up tersebut hanya muncul satu kali setelah pilih buat key, jika terpaksa hilang, boleh di ulangi proses point c dan d dari awal.\


e. Selanjutnya kita akan setting untuk API Signature/Callback, caranya masuk > pengaturan API > silahkan scroll untuk mencari menu Callback:

<figure><img src="../../.gitbook/assets/api xendit 3 (1).png" alt=""><figcaption></figcaption></figure>

Silahkan pilih lihat token verifikasi callback, masukan password xendit untuk verifikasi, simpan dengan aman nantinya akan di masukan di dashboard panel website kakak

f. Setelah dapat semua data API Key dan API Signature silahkan kakak, login kembali panel dashboard member kakak, dan masukan semua data data tersebut pada menu Setting > API KEY > Xendit Secret Key dan Xendit Signature, lalu pilih save untuk menyimpan \
dan setelah tersimpan jangan lupa refresh web broswernya

<figure><img src="../../.gitbook/assets/xen 1.png" alt=""><figcaption><p><br></p></figcaption></figure>

g. Lalu setelahnya silahkan setting untuk URL Callbacknya, silahkan kembali masuk ke akun xendit anda, lalu pilih menu > URL Callback > lalu isikan seperti format di bawah ini, pilih tes dan simpan

<figure><img src="../../.gitbook/assets/api keys 4.png" alt=""><figcaption><p>Keterangan: <br>a. <a href="https://api.domainkamu.com/v1/public/callback/xendit/va">https://api.domainkamu.com/v1/public/callback/xendit/va</a><br>b. <a href="https://api.domainkamu.com/v1/public/callback/xendit/cstore">https://api.domainkamu.com/v1/public/callback/xendit/cstore</a></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/api keys 5.png" alt=""><figcaption><p>Keterangan:<br>c. <a href="https://api.domainkamu.com/v1/public/callback/xendit/ewallet">https://api.domainkamu.com/v1/public/callback/xendit/ewallet</a></p></figcaption></figure>

h. Lalu setelahnya silahkan aktifkan merchant/channel pembayaran yang akan di gunakan pada menu metode pembayaran

<figure><img src="../../.gitbook/assets/metode pembayaran chanel xendit.png" alt=""><figcaption><p>Keterangan:<br>a. Silahkan klik tombol aktifkan kepada semua merchant/channel pembayaran yang ingin di aktifkan, ada beberapa merchant yang membutuhkan verifikasi dokumen/isian sedikit, namun mudah untuk melakukannya contoh: merchant alfamart/indomart, shopeepay, link aja dll<br>b. Jika sudah selesai klik aktifkan silahkan klik details lalu pilih klik fixed dan klik click here untuk mengaktifkan merchant, namun hanya beberapa merchant yang perlu lakukan itu<br>c. Estimasi pengaktifan merchant tersebut<br>d. merchant anda telah aktif sejak tanggal tersebut<br>e. beberapa pilihan merchant/channel pembayaran yang dapat di aktifkan</p></figcaption></figure>

i. Lalu setelahnya kita akan setting untuk tarik uang/witdrawal dari wallet xendit, silahkan masuk xendit > Pengaturan, langkahnya sebagai berikut:

<figure><img src="../../.gitbook/assets/menu wd xendit.png" alt=""><figcaption><p>Keterangan:<br>a. Pilih akun bank, untuk memasukan akun bank mana yang akan di pilih untuk menampung penarikan/withdrawal anda<br>b. Pilih email notifikasi, untuk memasukan email mana yang akan di pilih untuk mengirimkan info penarikan/withdrawal anda<br>c. Pilih penjadwalan otomatis penarikan/withdrawal anda<br>d. menu saldo, untuk memonitor uang masuk dan keluar dari wallet xendit anda, dan untuk memproses witdrawal atau penarikan dana anda > pilih tarik dana > anda akan di arahkan untuk memilih penarikan dana di lakukan di nomor rekening yang sudah sesuai anda atur pada menu ini</p></figcaption></figure>
