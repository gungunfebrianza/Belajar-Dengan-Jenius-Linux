# Belajar Dengan Jenius Linux

## Penulis : Gun Gun Febrianza

# Apa itu Linux Virtual Machine ?

Virtual Machine adalah sebuah komputer virtual yang berjalan di dalam sebuah komputer.

<img src="../assets/VirtualMachine.png" style="zoom:90%;" />

Contoh Linux Virtual Machine adalah kita membuat sistem operasi *linux* berjalan di dalam sistem operasi *windows* yang kita gunakan, maka sistem operasi *linux* disebut sebagai **virtual machine**. 

## Virtual Machine

Sistem operasi windows di sebut sebagai **host** dan sistem operasi linux yang menjadi virtual machine disebut sebagai **Guest**.

<img src="../assets/VirtualMachine1.png" style="zoom:90%;" />

Virtual Machine memiliki representasi binary file biasanya dalam format ISO yang dapat kita salin atau pindahkan ke dalam physical computer sehingga menjadi portable.

**Virtual Machine (VM)** dapat berbasis **Full Virtualization** untuk meniru sebuah OS secara keseluruhan. VM diimplementasikan dengan membangun sebuah software layer pada physical machine untuk mendukung sebuah arsitektur mesin secara virtual[11]. 

<img src="../assets/VirtualMachine2.png" style="zoom:90%;" />

Gambar di atas adalah ilustrasi kita dapat memiliki 3 Virtual Machine CentOS dalam dekstop PC Ubuntu Linux.

Dalam beberapa literatur Full Virtualization sering juga disebut sebagai *System Virtual* Machine atau Hardware Virtual Machine. Sehingga dalam satu physical server atau physical computer kita dapat membangun Multiple OS Environment sekaligus. 

Untuk mewujudkanya kita memerlukan sebuah **Hypervisor**.

------



# Apa itu Hypervisor ? 

<img src="../assets/Hypervisor.png" style="zoom:90%;" />

Software untuk membuat virtual machine di antaranya adalah Virtualbox dan VMware Workstation. Saat kita membuat virtual machine kita dapat membuat virtual CPU, virtual disk dan memory yang ingin kita alokasikan. 

Oleh karena itu teknologi virtualization sangat membantu untuk membangun infrastructure yang scalable. 

Virtualbox dan VMware Workstation adalah sebuah hypervisor yang dapat kita gunakan untuk membangun guest operating system di dalam host operating system. Hypervisor adalah software yang bertanggung jawab untuk membangun system virtualization[12].

Semua ini dapat diwujudkan karena terdapat teknologi Virtualization.

----

# Apa itu Virtualization?

Terminologi Virtualization memiliki makna membuat sesuatu secara virtual atau artifisial. 

Dalam buku Virtualization Security yang diterbitkan EC-Council, dikatakan bahwa Virtualization adalah kerangka (framework) atau metodologi bagaimana membagi sumber daya (resources) sebuah komputer agar bisa menjadi sebuah multiple execution environment[10]**.**

### Multiple Execution Environment

Apa sih yang dimaksud Multiple Execution Environment?

Sebelum Virtualization muncul dahulu kita menggunakan satu sistem operasi untuk setiap mesin. Perhatikan gambar di bawah ini :

<img src="../assets/VirtualMachine3.png" style="zoom:40%;" />

Kemudian muncul virtualization layer yang dapat kita gunakan, misal untuk memasang sistem operasi lebih dari satu dalam satu mesin komputer. 

Inilah yang dimaksud dengan Multiple Execution Environment. Semuanya di isolasi agar masing-masing bisa berjalan dengan baik.

<img src="../assets/VirtualMachine4.png" style="zoom:40%;" />

Terminologi virtualization mengacu pada pembuatan suatu resource(s) secara virtual. Sehingga dapat menghemat biaya untuk memaksimalkan pemanfaatan sumber daya suatu komputer. 

Virtualization dapat melakukan emulation suatu hardware menggunakan software yang selanjutnya beberapa tehnik dikembangkan agar bisa membangun : 

1. Server Virtualization, 
2. Dekstop Virtualization, 
3. Network Virtualization, 
4. Storage Virtualization dan masih banyak lagi.
