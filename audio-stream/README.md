Stream audio ke perangkat lain melalui jaringan lokal.

### Bahan yang Diperlukan
Perangkat penerima harus terinstal `nodejs`. Kedua perangkat harus terinstal `gstreamer`, `gstreamer-plugins-good`, `gstreamer-plugins-bad`, dan `gstreamer-plugins-ugly`. Kedua perangkat harus terhubung melalui jaringan lokal yang sama.

### Cara Penggunaan
Penerima audio:
```bash
./receive
```

Pengirim audio:
```bash
./send IP_PENERIMA
```
