# Belajar Dengan Jenius Linux

## Penulis : Gun Gun Febrianza

# Computer

## Computer Program

Komputer memproses sebuah program yang terdiri dari serangkaian instruksi biner untuk melakukan suatu komputasi (**Computation**) secara spesifik. Kata spesifik mengacu pada suatu **problem domain** atau **programming domain**. 

Menurut **Robert W.Semesta** dalam bukunya yang berjudul **Concept of Programming Language** (2016) sebuah **programming domain** terdiri dari 4 hal yaitu untuk :

**1. Scientific Application**

 Program yang dibuat untuk keperluan sains dan penelitian.

**2. Business Application**

  Program yang dibuat untuk keperluan bisnis.

**3. Artificial Intelligence**

  Program yang dibuat memiliki kemampuan kecerdasan buatan.

**4. Web Software** 

  Program yang dibuat menggunakan teknologi web.

Namun kini kita sudah memasuki era teknologi blockchain sehingga menurut **Gun Gun Febrianza** dalam bukunya yang berjudul Belajar dengan **Jenius Smart Contract & Tokenomics** terdapat dua jenis Applications :

**1. Centralized Applications** 

  Program yang tertanam dalam sistem komputer tersentral, program tidak bersifat transparan dan tidak deterministik.

**2. Decentralized Applications** 

  Program yang tertanam dalam sistem komputer terdesentralisasi, program bersifat transparan dan deterministik.

## Computation

Terdapat dua jenis komputasi yaitu : 

1. Komputasi bisa berupa *numeric computation* seperti memecahkan sesuatu dengan model matematis seperti pada *system of equation* (sistem persamaan) 

2. Dan *symbolic computation* seperti melakukan pencarian pada sebuah teks, memanipulasi teks, gambar dan vidio.

## Computer System

Komputer terdiri dari sekumpulan **hardware** dan **software**, pada **hardware** terdapat beberapa **logical units** seperti :

### Input Unit

Terdiri dari sekumpulan **input device** untuk memproduksi informasi yaitu **keyboard**, **touchscreen**, **webcam**, **microphone**, **barcode scanner** dan **mouse devices.**

### Ouput Unit

Terdiri dari sekumpulan **output device** untuk menampilkan informasi yaitu **screen monitor**, **speaker**, **printer** hingga ke **oculus rift**. 

<img src="../assets/OculusRift.png" style="zoom:50%;" />

### Memory Unit

*Memory unit* seringkali disebut **memory**, **primary memory** atau **RAM (Random Access Memory)**. Informasi yang tersimpan dalam **memory unit** bersifat **volatile**, artinya informasi akan hilang jika komputer dimatikan. 

**Memory unit** menjadi tempat untuk mempertahankan informasi setelah melalui **input unit**, sehingga langsung tersedia untuk diproses oleh **processor** jika dibutuhkan untuk memproduksi hasil pada **Ouput Unit**.

#### Memory Hierarchy

Ada berbagai jenis **memory unit** yang disusun berdasarkan **memory hierarchy** yang disusun berdasarkan kapasitas penyimpanan dan waktu akses :

<img src="../assets/Memory-Hierarchy.png" style="zoom:90%;" />

Di bawah ini adalah waktu akses dan kapasitas tipikal untuk setiap memory dalam dalam hirarkinya :

<img src="../assets/Memory-Hierarchy2.png" style="zoom:90%;" />

#### Register

Urutan memory paling cepat tentu dipegang oleh register yang letaknya berada di dalam internal sebuah CPU. Di buat dengan material yang sama dengan CPU, didesain secepat CPU sehingga tidak ada delay sama sekali untuk waktu akses. 

Hanya saja kapasitasnya terbatas baik untuk 32-64 bit CPU terdapat kapasitas kurang dari 1KB.

#### Cache Memory

Cache memory di control secara penuh oleh hardware, main memory dibagi menjadi beberapa baris cache (Cache Lines) dengan ukuran typical 64 bytes. 

Dimulai dari address 0 sampai 63 pada baris cache 0, kemudian address 64-127 pada baris cache 1 dan seterusnya.

### Central Processing Unit (CPU)

*CPU* (**Central Processing Unit**) adalah istilah yang diberikan jika hanya terdapat 1 processor yang dimiliki oleh suatu komputer. 

#### Processor

Industri komputer menggunakan istilah terminologi **Central Processing Unit** pada awal tahun 1960, namun secara tradisional terminologi **CPU** mengacu pada sebutan untuk **processor**. 

Seluruh **modern CPU** adalah **Microprocessor** yang berarti mereka tersimpan di dalam sebuah chip tunggal **Integrated Circuit.** 

**Processor** adalah sebuah otak dari komputer yang mengendalikan operasi berbagai komponen dalam sistem komputer. Sebuah **CPU** membutuhkan dua hal yaitu program atau aplikasi dan data. 

#### Arithmetic & Logic Unit (ALU)

Fungsi dari **ALU** adalah untuk melakukan kalkulasi seperti penjumlahan, pengurangan, perkalian dan pembagian. 

**ALU** memiliki mekanisme untuk membuat keputusan yang dapat membuat komputer misal, membandingkan dua buah data dalam **memori unit** apakah data tersebut setara (**equal**) atau tidak. 

Kini ALU (**Arithmetic and Logic Unit**) dikembangkan sebagai **next logical unit** untuk **CPU**.

#### Von Neumann Architecture

Desain operasional dasar sebuah sistem komputer disebut dengan **architecture**. Seluruh arsitektur komputer yang ada saat ini tidak lepas dari seorang pioner komputer bernama **John von Neumann**. 

Dalam sebuah sistem *Von Neumann* terdapat tiga komponen utama yaitu **Central Processing Unit** (**CPU**), **physical memory**, dan **input** atau **output** (IO). **Central Processing Unit** (**CPU**) akan menerima data dari **memory** dan **input**. 

Elemen kunci dari **Von Neumann Architecture (VNA)** adalah :

1. Data & Instruksi disimpan dalam bilangan biner (**binary**).
2. Data & Instruksi disimpan dalam main **memory**.
3. Instruksi diambil (**fetched**) dari **memory** satu persatu dalam satu waktu secara berurutan.
4. **Processor** melakukan **decode** pada instruksi dan mengeksekusinya sebelum mengambil instruksi selanjutnya.
5. Aktivitas ini terus dilakukan sampai tidak ada lagi instruksi yang tersedia.

Dalam **Von Neumann Architecture (VNA)** dalam sebuah **processor** terdapat 5 spesial **register** :

**1.**  **Program Counter (PC)**

Menyimpan **memory address** dari instruksi selanjutnya yang akan diambil dari **main memory**.

**2.**  **Memory Address Register (MAR)**

Menyimpan **memory address** dari instruksi saat ini yang sedang dieksekusi. 

**3.**  **Memory Buffer Register (MBR)**

Menyimpan data yang akan ditransfer menuju **main memory**.

**4.**  **Current Instruction Register (CIR)**

Menyimpan instruksi yang saat ini telah di **decode** dan di eksekusi.

**5.**  **Accumulator (ACC)**

Menyimpan data yang telah diproses, hasil dari sebuah komputasi. 

#### CPU Register

Fungsi dasar **CPU** adalah melakukan **fetch**, **decode**, dan **execute** setiap instruksi bahasa mesin yang berada di dalam **Read-only Memory (ROM)** ataupun **Random Access Memory (RAM)**.

**CPU** akan melakukan **fetch data** dari sebuah memori eksternal dan mengirimkanya kedalam **internal memory** yang disebut dengan **register**.

**Register** adalah sebuah **high-speed memory** yang ada di dalam internal **CPU**. **Register** digunakan **processor** untuk menyimpan sebuah hasil komputasi sementara yang ukurannya terbatas. Data yang tersimpan dapat berupa : 

1. Alamat dari instruksi bahasa mesin selanjutnya yang akan dieksekusi.
2. Instruksi bahasa mesin saat ini yang sedang di **decode**.
3. Hasil komputasi.
