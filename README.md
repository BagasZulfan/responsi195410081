# Melalui Github
### Tutorial Menginstall
Jalankan perintah ini untuk dapat mendownload data dari repository github :

```sh
$ git clone https://github.com/BagasZulfan/responsi195410081.git
$ cd responsi195410081
```

### Tutorial Menjalankan
Jalankan perintah berikut ini untuk dapat membuat image, serta menjalankan container dengan image `responsi195410081` :

```sh
$ docker build -t responsi195410081 ./
$ docker run -dit --name bagasresponsi -p 5000:80 responsi195410081
```

Kemudian buka browser Anda dengan url `http://locahost:5000` agar dapat melihat hasil.
# Melalui Docker Hub
### Tutorial Menjalankan
Jalankan perintah ini agar dapat mengambil image dari dockerhub, serta menjalankan container dengan image `responsi195410081` :
```sh
$ docker run -dit --name bagasresponsi -p 5000:80 195410081bagaszulfananugerah/responsi195410081:latest
```
Selanjutnya buka browser Anda dengan url `http://locahost:5000` agar dapat melihat hasil.