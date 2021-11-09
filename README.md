# Image Retrieval

## OpenCV Basic

OpenCV adalah library open-source yang mencakup ratusan algoritma computer vision. OpenCV memiliki struktur modular.

* Image Arithmetic OpenCV

  Dengan library openCV, kita dapat melakukan suatu operasi aritmatika pada gambar. Contoh yang sederhana yaitu penjumlahan dan pengurangan. Operasi aritmatika ini memiliki banyak fungsi, salah satu contohnya yaitu menyesuaikan kecerahan dan kontras dengan operasi penjumlahan atau pengurangan.

* Image Cropping OpenCV

  Cropping image adalah proses memotong gambar menjadi ukuran yang diinginkan. Cropping bekerja dengan cara slicing image array dengan pertama-tama menyediakan koordinat startY dan endY, lalu diikuti oleh koordinat startX dan endX ke irisan.

* Image Drawing OpenCV

  Metode ini dilakukan untuk menggambar berbagai bentuk pada gambar yang ada. Gambar yang dibuat bisa beragam, beberapa contoh yang paling umum digunakan yaitu garis, lingkaran, dan persegi panjang.
  
* Image Flipping OpenCV

  OpenCV juga menyediakan metode untuk membalikkan gambar melintasi sumbu x atau y atau pun keduanya. Proses flipping ini biasanya digunakan untuk augmentasi dataset.

* Image Masking OpenCV

  Masking biasanya digunakan untuk meng-highlight objek tertentu di dalam gambar.

* Setting Image Pixel OpenCV

  Pixel adalah blok bangunan dari sebuah gambar. Setiap gambar terdiri dari sekumpulan pixel. Dengan openCV kita bisa mengakses dan memanipulasi pixel.

* Read Write Image OpenCV

  Fungsi read digunakan untuk memuat gambar input dari disk sedangkan fungsi write digunakan untuk menyimpan gambar pada perangkat penyimpanan. 

* Resize Image OpenCV

  Resizing image dilakukan dengan menggunakan metode interpolasi. Pengubahan ukuran gambar biasanya dilakukan untuk mengurangi atau menambah jumlah ukuran pixel pada gambar.

* Rotate Image OpenCV

  Memutar gambar adalah salah satu metode yang dapat dilakukan dalam image processing. Pada openCV, rotate image dapat dilakukan dengan menggunakan 2 fungsi yaitu getRotationMatrix2D() dan warpAffine(). Fungsi getRotationMatrix2D() digunakan untuk menghitung rotasi matriks.
  
* Split Merge Image OpenCV

  Teknik split dan merge biasanya digunakan untuk mengelompokkan gambar. 
  
* Translate Image OpenCV

  Translasi adalah pergeseran bayangan sepanjang sumbu x dan y atau lebih sederhananya pergeseran gambar dari satu lokasi ke lokasi lain. 

Referensi OpenCV diambil dari [OpenCV Docs](https://docs.opencv.org/4.5.4/d1/dfb/intro.html) dan [Website PyImageSearch](https://www.pyimagesearch.com/)

