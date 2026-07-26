Stream audio ke perangkat lain melalui jaringan lokal.

### Bahan yang Diperlukan
Perangkat penerima harus terinstal `nodejs`. Kedua perangkat harus terinstal `gstreamer`, `gst-plugins-good`, `gst-plugins-bad`, dan `gst-plugins-ugly`. Kedua perangkat harus terhubung melalui jaringan lokal yang sama.

### Cara Penggunaan
Penerima audio:
```bash
./receive
```

Pengirim audio:
```bash
./send IP_PENERIMA
```
