Alat untuk menampilkan dan mengirim file melalui jaringan lokal.

### Bahan yang Diperlukan
Perangkat pengirim harus terinstal `nodejs`. Kedua perangkat harus terhubung melalui jaringan lokal yang sama.

### Cara Penggunaan
Pengirim file:
```bash
./send PATH_TO_FILE
```

Penerima file:
Akses `http://IP_PENGIRIM:3000` untuk mendownload file.

Bisa juga digunakan untuk menampilkan file dalam bentuk plaintext:
```bash
./serve PATH_TO_FILE
```
