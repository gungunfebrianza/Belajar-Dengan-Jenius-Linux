# Belajar Dengan Jenius Linux

## Penulis : Gun Gun Febrianza

## Bash Scripting

### Shebang

```bash
$ #!/bin/bash
```



### Comment

```bash
$ #!/bin/bash

# This is Comment
```



### Hello World

```bash
$ #!/bin/bash

# This is Comment
echo "Hello World"
```



### Read Script

```bash
$ cat hello.sh
```



### Set Permission (CHMOD)

```bash
$ chmod 755 hello.sh
```



### Execute Script

```bash
$ ./hello.sh
```

Dot merepresentasikan **current directory**.



### Built-in Shell 

echo adalah salah satu built-in shell command yang sudah tersedia pada bash. 

```bash
$ echo 'Hello World'
```

Untuk memeriksa apakah echo memang bagian dari built-in shell pada bash eksekusi perintah di bawah ini :

```bash
$ type echo
```

#### Help Command

Ada saatnya kita membutuhkan dokumentasi untuk mempelajari setiap perintah (Command), untuk mendapatkannya eksekusi perintah di bawah ini :

```bash
$ help echo
```



---------------------

