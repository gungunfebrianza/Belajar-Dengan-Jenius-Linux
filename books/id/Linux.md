# Belajar Dengan Jenius Linux

## Penulis : Gun Gun Febrianza

# Apa itu Linux ?

Pada tahun 1991 seorang mahasiswa lulusan dari **Universitas Helsinki** dari Finlandia mulai menulis sistem operasi gratis (**free operating system**) sebagai hobi. Sebuah hobi yang kelak akan menjadi sejarah besar kemajuan peradaban teknologi.

**Linus Torvald** mengawali pembangunan **UNIX like kernel** untuk **IBM PC (Intel 80386) Architecture** [1]. Sebuah **personal computer** zaman dulu :

<img src="../assets/IBM-PC.jpg" style="zoom:80%;" />

Pengembangan awal dilakukan pada tahun 1991, di tahun itu **linux** pertama kali di posting melalui internet, pembangunan **linux kernel** melalui proses yang panjang dan rumit.

Pengembangan linux kernel bisa terwujud berkat kolaborasi para ahli yang dikendalikan secara terpusat oleh Linus Torvald. Kontribusi kode dari para ahli di atasi menggunakan sebuah mailing list yaitu **LKML (Linux Kernel Mailing List)**.

**Linus** berkontribusi besar dalam meningkatkan kualitas **linux** agar bisa **up-to-date** dengan berbagai pengembangan **hardware device** dan berkoordinasi dengan ribuan para ahli lainnya untuk mengembangkan **linux** dari seluruh dunia.

Selama bertahun-tahun para pengembang berhasil membuat **linux** tersedia di beberapa arsitektur seperti **Hewlett-packard Alpha**, **Intel’s Itanium**, **AMD’s AMD64**, **PowerPC** dan **IBM’s zSeries**. 

Sistem operasi yang dibuat bersifat **open source** dan menjadi proyek **open source** terbesar dalam sejarah dunia **software engineering**. **Project open source** tersebut kini dikenal dengan sebutan **linux**.

## Apa itu Open Source?

<img src="../assets/SourceCode.png" style="zoom:90%;" />

**Open Source** artinya kode pemrogramannya tersedia untuk publik, sehingga kita dapat melihat kode pemrogrammannya dan memodifikasinya sesuai kebutuhan kita. Kita juga bisa ikut mengembangkan kode pemrograman tersebut agar bisa menjadi lebih baik dan dapat digunakan oleh orang lain dalam satu **codebase**. 

## Apa itu Closed Source?

Closed Source adalah sebuah project yang kode pemrogramannya bersifat privat, tidak tersedia untuk publik karena memiliki nilai komersil.

OS Linux bersifat open source dan OS Windows bersifat closed source.

## Apa itu Kernel?

Kernel adalah inti dari sebuah sistem operasi, yang menjadi layer perantara antara software dan hardware. Kernel melayani permintaan (request) dari sebuah aplikasi (arbitrary application) agar bisa berinteraksi dengan hardware.

<img src="../assets/Kernel.png" style="zoom:80%;" />

Pada gambar di atas, pada user level seorang pengguna akan berinteraksi dengan sebuah application, sebuah application dapat memberikan perintah pada kernel. 

Misal, kernel harus berinteraksi dengan hardisk, maka harus ditentukan path mana yang akan digunakan untuk menyalin data dari disk ke memory. Kernel juga bisa dikatakan sebagai sebuah library yang menyediakan berbagai perintah untuk mengelola sistem. 

Kernel akan dimuat kedalam RAM saat system boots dan memiliki banyak sekali procedure yang digunakan untuk membuat sistem dapat beroperasi. Setelah kernel dimuat kedalam RAM, service bisa disediakan untuk sistem dan user. Beberapa servis berjalan diluar lingkup kernel space.

### Kernel Architecture

Ada 2 arsitektur pengembangan kernel yang dominan yaitu kernel secara :

1. Monolithic dan 
2. Microkernel. 

Sebagian besar UNIX-kernel menggunakan arsitektur monolithic, begitu juga Linux Kernel yang dibangun Linus Torvald juga di desain secara **monolithic**. 

### Monolithic Kernel

Monolithic kernel artinya seluruh fungsionalitas sebuah sistem operasi secara virtual direpresentasikan dalam sebuah block of code tunggal dan berjalan sebagai process tunggal dengan address space tunggal.

Monolithic kernel adalah konsep tradisional yang sudah lama digunakan, pada monolithic kernel seluruh subsystem seperti memory management, file management dan device driver tersimpan dalam satu codebase tunggal.

Sebagai process tunggal monolithic kernel memiliki internal data structure dan routines yang dapat digunakan untuk memberikan berbagai fungsionalitas.

#### Dynamic Linking

Monolithic kernel memiliki keunggulan secara performance dibandingkan dengan microkernel. Linux Kernel didesain menggunakan arsitektur monolithic kernel dan telah mendukung konsep **Dynamic Linking**. 

Dengan Dynamic Linking sekumpulan modules dengan kernel code dapat dimuat dan dicabut kedalam kernel kapan saja dalam keadaan runtime. Pemasangan modules untuk memberikan tambahan fungsionalitas.



**Linux** adalah sebuah **kernel**, bukan sebuah sistem operasi yang siap digunakan. 

Untuk menyempurnakan **linux** agar menjadi sebuah sistem operasi yang dapat digunakan, kita memerlukan sekumpulan program (***bundling program***) yang kita kenal sebagai **distribution**\.

| Purpose                                   | Distribution           |
| ----------------------------------------- | ---------------------- |
| Umum                                      | Ubuntu                 |
| Keamanan Komputer (**Computer Security**) | Kali Linux             |
| Perusahaan (**Enterprise**)               | CentOS                 |
| Komputasi Awan (**Cloud Computing**)      | Amazon Linux (AWS AMI) |

**Distribution** **linux** di atas bisa didapatkan dengan gratis. 

Di dalamnya terdapat ribuan ***program*** dan **software** yang bisa digunakan secara gratis. Sebagian besar program tersebut bersifat **open source**, kita dapat melihat kode sumber dari program tersebut, mempelajarinya dan memodifikasinya sesuai dengan kebutuhan kita. 

---------------------

