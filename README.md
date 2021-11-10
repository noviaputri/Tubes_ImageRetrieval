# Image Retrieval

## OpenCV Basic

<p align=justify>OpenCV adalah library open-source yang mencakup ratusan algoritma computer vision. OpenCV memiliki struktur modular.</p>

* Image Arithmetic OpenCV

  <p align=justify>Dengan library openCV, kita dapat melakukan suatu operasi aritmatika pada gambar. Contoh yang sederhana yaitu penjumlahan dan pengurangan. Operasi aritmatika ini memiliki banyak fungsi, salah satu contohnya yaitu menyesuaikan kecerahan dan kontras dengan operasi penjumlahan atau pengurangan.</p>

* Image Cropping OpenCV

  <p align=justify>Cropping image adalah proses memotong gambar menjadi ukuran yang diinginkan. Cropping bekerja dengan cara slicing image array dengan pertama-tama menyediakan koordinat startY dan endY, lalu diikuti oleh koordinat startX dan endX ke irisan.</p>
  
* Image Drawing OpenCV

  <p align=justify>Metode ini dilakukan untuk menggambar berbagai bentuk pada gambar yang ada. Gambar yang dibuat bisa beragam, beberapa contoh yang paling umum digunakan yaitu garis, lingkaran, dan persegi panjang.</p>
  
* Image Flipping OpenCV

  <p align=justify>OpenCV juga menyediakan metode untuk membalikkan gambar melintasi sumbu x atau y atau pun keduanya. Proses flipping ini biasanya digunakan untuk augmentasi dataset.</p>

* Image Masking OpenCV

  <p align=justify>Masking biasanya digunakan untuk meng-highlight objek tertentu di dalam gambar.</p>

* Setting Image Pixel OpenCV

  <p align=justify>Pixel adalah blok bangunan dari sebuah gambar. Setiap gambar terdiri dari sekumpulan pixel. Dengan openCV kita bisa mengakses dan memanipulasi pixel.</p>

* Read Write Image OpenCV

  <p align=justify>Fungsi read digunakan untuk memuat gambar input dari disk sedangkan fungsi write digunakan untuk menyimpan gambar pada perangkat penyimpanan.</p> 

* Resize Image OpenCV

  <p align=justify>Resizing image dilakukan dengan menggunakan metode interpolasi. Pengubahan ukuran gambar biasanya dilakukan untuk mengurangi atau menambah jumlah ukuran pixel pada gambar.</p>

* Rotate Image OpenCV

  <p align=justify>Memutar gambar adalah salah satu metode yang dapat dilakukan dalam image processing. Pada openCV, rotate image dapat dilakukan dengan menggunakan 2 fungsi yaitu getRotationMatrix2D() dan warpAffine(). Fungsi getRotationMatrix2D() digunakan untuk menghitung rotasi matriks.</p>
  
* Split Merge Image OpenCV

  <p align=justify>Teknik split dan merge biasanya digunakan untuk mengelompokkan gambar.</p> 
  
* Translate Image OpenCV

  <p align=justify>Translasi adalah pergeseran bayangan sepanjang sumbu x dan y atau lebih sederhananya pergeseran gambar dari satu lokasi ke lokasi lain.</p> 
  
## Image Processing

* Adaptive Thresholding

  <p align=justify>Adaptive thresholding adalah metode di mana nilai thresholding dihitung untuk wilayah yang lebih kecil sehingga akan ada nilai thresholding yang berbeda untuk wilayah yang berbeda.</p>

* Canny

  <p align=justify>Metode ini digunakan untuk mendeteksi tepi pada gambar. Canny merupakan edge detector yang paling terkenal dan paling sering digunakan dalam computer vision. Canny adalah algoritma multi-langkah yang diperkenalkan oleh John F. Canny dalam makalahnya tahun 1986, A Computational Approach to Edge Detection.</p>

* Color Space

  <p align=justify>Color space adalah cara untuk mewakili saluran warna yang ada dalam gambar yang memberikan warna tertentu pada gambar. Ada beberapa ruang warna yang berbeda dan masing-masing memiliki maknanya sendiri.</p>

* Convolution

  <p align=justify>Konvolusi adalah salah satu blok bangunan paling penting dan mendasar dalam visi komputer dan pemrosesan gambar. Konvolusi (gambar) hanyalah perkalian elemen dari dua matriks yang diikuti dengan jumlah.</p>

* Gradien

  <p align=justify>Gradien gambar adalah blok bangunan mendasar dari banyak visi komputer dan rutinitas pemrosesan gambar. Gradien digunakan untuk mendeteksi tepi dalam gambar, yang memungkinkan untuk menemukan kontur dan garis besar objek dalam gambar, lalu juga digunakan sebagai masukan untuk mengukur gambar melalui ekstraksi fitur, dan juga digunakan untuk membuat peta saliency yang menyoroti subjek gambar.</p>
  
* Morphology

  <p align=justify>Operasi morfologi meliputi erosion, dilation, opening, closing, morphological gradient, black hat, top hat (also called “White hat”). Operasi pemrosesan gambar ini diterapkan pada gambar skala abu-abu atau biner dan digunakan untuk preprocessing untuk algoritma OCR, mendeteksi kode batang, mendeteksi pelat nomor, dan banyak lagi. Dan terkadang penggunaan operasi morfologis yang cerdas dapat memungkinkan untuk menghindari pembelajaran mesin yang lebih rumit (dan mahal secara komputasi) dan algoritma pembelajaran mendalam.</p>

* Smoothing blurring

  <p align=justify>Smoothing dan blurring adalah salah satu langkah preprocessing yang paling penting dalam semua visi komputer dan pemrosesan gambar. Dengan menghaluskan gambar sebelum menerapkan teknik seperti deteksi tepi atau ambang batas, kita dapat mengurangi jumlah konten frekuensi tinggi, seperti noise dan tepi (yaitu, "detail" gambar). Dengan mengurangi detail pada gambar, kita dapat lebih mudah menemukan objek yang kita minati. Selanjutnya, teknik ini memungkinkan kita untuk fokus pada objek struktural yang lebih besar dalam gambar. Operasi blurring meliputi Simple blurring (cv2.blur), Weighted Gaussian blurring (cv2.GaussianBlur), Median filtering (cv2.medianBlur), dan Bilateral blurring (cv2.bilateralFilter).</p>

* Thresholding

  <p align=justify>Thresholding adalah salah satu teknik segmentasi yang paling umum dan dasar dalam computer vision dan memungkinkan kita untuk memisahkan latar depan (yaitu, objek yang kita minati) dari latar belakang gambar. Thresholding adalah binarisasi dari sebuah gambar yang mana berusaha untuk mengonversi gambar skala abu-abu ke gambar biner, di mana pikselnya 0 atau 255. Thresholding ada 3 macam yaitu simple thresholding, otsu’s thresholding, dan adaptive thresholding.</p>

Referensi dokumentasi OpenCV diambil dari [OpenCV Docs](https://docs.opencv.org/4.5.4/d1/dfb/intro.html), [Website PyImageSearch](https://www.pyimagesearch.com/), dan [Website GeeksforGeeks](https://www.geeksforgeeks.org/opencv-python-tutorial/?ref=lbp).

