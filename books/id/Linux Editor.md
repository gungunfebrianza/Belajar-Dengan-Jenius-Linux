# Belajar Dengan Jenius Linux

## Penulis : Gun Gun Febrianza

# Linux Text Editor

**Linux** memiliki filosopi, segala sesuatu dalam **linux** adalah direpresentasikan dalam sebuah **file**. **Hardisk**, **Keyboard**, **Mouse**, dan **Printer** direpresentasikan dalam sebuah **file**. Proses yang sedang berjalan juga direpresentasikan dalam sebuah **file**.

Sehingga seorang **System Administrator** dalam **Linux** waktunya dihabiskan dengan memodifikasi dan observasi **file**. Sehingga mereka sangat cekatan dalam menggunakan **text editor**.

Jika anda menggunakan **Linux Dekstop** yang mendukung tampilan **user interface** berbasis **GUI**, anda bisa menggunakan **GNOME** atau **KDE**. Pada **GNOME** sudah tersedia program bernama **gedit** dan pada **KDE** terdapat **kate**.

Untuk membuka sebuah **file text** menggunakan **gedit** eksekusi perintah di bawah ini :

```
~$ gedit suratcinta.txt
```

Begitu juga dengan **kate** untuk membuka **file text** eksekusi perintah dibawah ini :

```bash
~$ kate suratcinta.txt
```

Semuanya tergantung **linux distribution** yang anda gunakan.

Namun jika anda menggunakan **Ubuntu Linux** pada layanan **cloud** seperti **Amazon EC2**, kita harus terbiasa dengan **command-line editor** seperti **nano** dan **vi**.

## Nano Editor

**Nano editor** adalah **editor** yang sangat cocok untuk pemula.

### Create Text

Untuk menggunakan **nano editor** eksekusi perintah di bawah ini :

```bash
~$ nano
```

<img src="../assets/Editor-Nano.png" style="zoom:90%;" />

Selanjutnya silahkan ketik beberapa kalimat :

<img src="../assets/Editor-Nano2.png" style="zoom:90%;" />

Disinilah tempat kita akan membuat sebuah teks berbasis **command-line editor** menggunakan **nano**.

### Save Text

Jika anda lihat terdapat beberapa informasi short cut yang dapat anda gunakan untuk memproses teks di atas.

| Nano Shortcut | Penjelasan                                        |
| ------------- | ------------------------------------------------- |
| CTRL + O      | Simpan teks yang telah kita tulis (**Write Out**) |

Untuk menyimpan **file** tekan **CTRL+O**, selanjutnya anda akan dihadapkan untuk memberi nama **file** yang akan anda simpan seperti pada gambar di bawah ini :

<img src="../assets/Editor-Nano3.png" style="zoom:90%;" />

Untuk keluar dari **editor** tekan tombol **CTRL+X**.

| Nano Shortcut | Penjelasan              |
| ------------- | ----------------------- |
| CTRL + X      | Keluar dari kode editor |

Selanjutnya kita dapat melihat **file** yang sudah kita buat dengan mengeksekusi perintah di bawah ini :

```bash
~$ ls -l
…
-rw-rw-r-- 1 ubuntu ubuntu  105 Mar 26 15:20 maudy.txt
…
```

Terdapat **file** yang telah kita buat yaitu **maudy.txt**.

### Open Text

Untuk membuka sebuah **file** menggunakan **nano** eksekusi perintah di bawah ini :

```bash
~$ nano maudy.txt
```

Maka **nano editor** akan membuka **file maudy.txt**.

### Replace Text

Jika kita ingin mengganti (**replace**) sebuah kata menggunakan **nano** tekan CTRL + \.

| Nano Shortcut | Penjelasan                           |
| ------------- | ------------------------------------ |
| CTRL + \      | Mengganti (**Replace**) sebuah kata. |

Selanjutnya **nano editor** akan meminta anda mengisi kata apa yang ingin kita ganti (**replace**), pada gambar di bawah ini penulis ingin mengganti kata **world** dengan gun.

<img src="../assets/Editor-Nano4.png" style="zoom:90%;" />

Tekan enter, kemudian masukan gun.
