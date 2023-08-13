# TrashClassification_Project
## Waste Classification System using Deep Learning Models as Solutions for Organic and Non-Organic Waste Detection
### Mytha Shabira, Nadya Zahra Rahmadani, Windi Noviani, Fauziah Umri

Abstract- The increase in population and changes in consumption patterns have led to new problems, one of which is related to waste production. Basically, waste consists of two types of groups, organic and non organic waste. The lack of public awareness in managing and sorting waste leads to scattered waste piles. However, sorted waste can facilitate waste management for recycling purposes. Based on this issue, a classification system needs to be designed to educate the sorting of organic and non-organic waste. This paper explored performance of Tensorflow, Keras, Numpy, Pandas, CV2, Matplotlib) in classifying waste types of 22500 waste images from kaggle dataset. Waste type can be identified directly from waste-type classifiers. The highest waste-type classification accuracy was 94,30% from this model classifier.
Keywords: Waste, Organic, Non-Organic, Classification

Abstrak-- Peningkatan jumlah penduduk serta perubahan pola konsumsi masyarakat menyebabkan permasalahan baru, salah satunya dalam hal produksi sampah. Pada dasar nya sampah terdiri dari dua jenis kelompok, yaitu sampah organik dan non-organik. Kurangnya kesadaran masyarakat dalam mengelola dan memilah sampah membuat tumpukan sampah berserakan. Padahal sampah yang dipilah dapat memudahkan pengelolaan sampah untuk didaur ulang. Berdasarkan permasalahan tersebut maka perlu dirancang sistem klasifikasi untuk dapat mengedukasi pemilahan sampah organik dan anorganik. Paper ini mengeksplorasi performa Tensorflow, Keras, Numpy, Pandas, CV2, dan Matplotlib dalam mengklasifikasikan jenis sampah dari 22.500 gambar sampah dari dataset Kaggle. Jenis sampah dapat diidentifikasi secara langsung menggunakan klasifikasi jenis sampah. Akurasi klasifikasi jenis sampah tertinggi yang dicapai dalam model ini adalah 94,30%.
Kata kunci: Sampah, Organik, Non-Organik, Klasifikasi

## I. PENDAHULUAN
Sampah merupakan barang/bahan yang tidak memiliki nilai yang digunakan secara biasa maupun khusus dalam lingkup produksi, atau material yang sebagian besar berasal dari rumah tangga. Sampah tersebut dibuang sembarangan ke berbagai tempat atau dibakar di sekitar tempat tinggal warga yang efeknya akan merusak lingkungan sekitar. Di Indonesia, Sampah merupakan salah satu permasalahan yang sangat serius, hal ini dibuktikan dengan data yang diperoleh dari Badan Pusat Statistik (BPS) Tahun 2018 dimana masyarakat Indonesia masih sulit dalam melakukan pemilahan sampah dan tidak tahu manfaat dari sampah yang telah dibuang. Data yang diperoleh dari kementrian Lingkungan Hidup dan Kehutanan pada tahun 2019 sampah di Indonesia mencapai 66-67 juta ton, dimana jumlah ini lebih tinggi dibandingkan dengan tahun sebelumnya yang mencapai 64 juta ton, Persentase sampah organik sebesar 60% sedangkan sampah anorganik mencapai 15%. Hal ini dapat terjadi oleh beberapa faktor, salah satunya akibat banyaknya limbah sampah yang dihasilkan oleh masyarakat, kurangnya tempat pembuangan sampah sehingga sampah yang menumpuk menjadi tempat berkembang dan sarang dari serangga seperti tikus. hal ini juga tidak menutup kemungkinan terjadinya polusi dan pencemaran tanah, air, dan udara. Namun masalah sampah ini tidak terjadi di indonesia saja, negara-negara di dunia juga merasakan masalah sampah namun tergantung berapa tinggi nya sampah dan cara negara itu sendiri mengatasi permasalahan nya. Negara yang juga mengalami permasalahan serius mengenai sampah adalah Negara Thailand dimana Thailand hampir dikatakan sebagai “Tempat Sampah Dunia” karena di Thailand banyak nya sampah plastik yang menggunung dan menghasilkan 27,82 juta ton sampah kota (MSW) pada tahun 2018 dan lebih tinggi sekitar 1,64% dari tahun sebelumnya. Hal ini juga dibuktikan oleh Teluk yang terdapat di negara Thailand telah dipenuhi sampah hampir sepanjang 10 kilometer mengambang pada tahun 2017. Akibat sampah, seekor ikan paus ikut tewas setelah menelan 80 kantong plastik di perutnya. Hal ini cukup mengejutkan warga Thailand sehingga masalah ini dengan cepat diatasi oleh warga Thailand dengan mengingatkan ke publik untuk kesadaran dalam mengelola sampah atau limbah di negara Thailand.

Pengelolaan sampah dapat dimulai dari manajemen sampah dengan baik. Pemilihan dan pengelompokan sampah menjadi tindakan penting, karena jika limbah yang masuk ke tempat yang salah dapat menggiring sampah lain juga ikut masuk ke tempat yang salah. Misalnya sampah yang akan didaur ulang terpaksa dikirim kembali ke
TPA di sebabkan oleh sampah yang tidak dapat di daur ulang berada di tempat yang sama dengan sampah yang dapat di daur ulang. Tindakan yang sebaiknya dilakukan adalah memisahkan sampah atau limbah sesuai dengan tempat nya dihasilkan. Saat ini tempat umum sudah menyediakan tempat sampah dengan baragam label mulai dari Organik, Anorganik, Daur ulang dan sebagainya. Hal ini juga sebagai aksi untuk memperbaiki tatanan sampah yang ada di indonesia maupun negara lain yang memiliki permasalahan yang sama. Berdasarkan permasalahan tersebut, pada penelitian ini dilakukan optimasi penggunaan metode Convolutional Neural Network (CNN) untuk mendapatkan hasil yang akurat dalam mengidentifikasi jenis sampah yaitu sampah organik dan anorganik.
Berikut terkait rangkaian kinerja yang kami lakukan dalam penelitian atau project ini: 
- I. PENDAHULUAN
- II. METODE PENELITIAN
- III. HASIL DAN PEMBAHASAN
- IV. KESIMPULAN DAN SARAN serta REFERENSI.

## II. METODE PENELITIAN
Dalam melaksanakan penelitian ini, digunakan pendekatan metodologi yang lazim digunakan. Metode penelitian dibagi menjadi 4 tahapan utama, yaitu (1) Studi literatur , (2) Pengumpulan Data, (3) Perancangan menggunakan Algoritma CNN, dan (4) Evaluasi. Berikut ini adalah deskripsi rinci dari masing-masing tahapan dalam metode penelitian:

### A. Studi literatur
Pada tahap Studi Literatur ini digunakan untuk melakukan pencarian serta mempelajari dasar-dasar secara teoritis yaitu seperti mempelajari Jurnal, e-book dan lainnya yang berhubungan dengan penelitian sebelumnya telah dilakukan. Seperti pada konsep pendeteksi sampah, pengolahan data sampah dan metode Deep Learning mengenai CNN dan arsitektur jaringan Tensorflow. Selanjutnya setelah melakukan studi literatur, sehingga didapatkan rumusan Langkah seperti apa yang akan dikerjakan, dan hal baru seperti apa yang akan dihasilkan sebagai halnya pada penelitian ini. Berdasarkan penjelasan yang sudah diuraikan sebelumnya maka dari itu pada penelitian ini menggunakan Teknik studi literatur ini guna untuk mencari dan memenuhi dari dasar-dasar secara teoritis yang digunakan dalam penelitian ini.

### B. Pengumpulan Data
Kami mendapatkan dataset kami menggunakan dataset publik yang tersedia di dalam Platform Kaggle. Kaggle adalah situs untuk berbagi ide, mendapatkan inspirasi, bersaing dengan ilmuwan data lainnya, mempelajari informasi baru dan trik pengkodean, dan melihat contoh penerapan ilmu data. Ada banyak kumpulan data seperti data polusi udara yang dapat digunakan untuk hal-hal sederhana, data lainnya seperti menjual video game hingga sesuatu yang lebih kompleks dan penting. Data ini sebenarnya direferensikan sehingga kami dapat melatih dan menguji model kami dalam proyek yang pada akhirnya dapat membantu orang lain.
Disini kami menggunakan dataset yang terdapat data dari sampah organik dan anorganik, yang merupakan data yang kami butuhkan dalam merancang sistem pendeteksi sampah ini. Langkah berikutnya yaitu melakukan klasifikasi dataset tersebut ke dalam training data dan setdata. Pada penelitian ini dataset tersebut akan diinputkan pada proses sistem, setelah itu menyiapkan data training dengan menggunakan CNN, pada saat melakukan proses training metode CNN yang nanti akan dilakukan tahap uji seberapa besar tingkat akurat dan seberapa besar performa dari yang sudah dihasilkan.

### C. Model Klasifikasi CNN
Kami menggunakan enam algoritma CNN yang terkenal yaitu, Tensorflow, Keras, Numpy, Pandas, Cv2, dan Matplotlib.
TensorFlow : Tensorflow adalah pustaka sumber terbuka yang menggunakan bahasa Python untuk membuat komputasi numerik yang membuat pembelajaran mesin dan mengembangkan jaringan saraf lebih cepat dan lebih mudah. Aplikasi TensorFlow dapat dijalankan di hampir semua target yang nyaman: mesin lokal, kluster di cloud, iOS, dan Perangkat Android, CPU, atau GPU. Model hasil yang dibuat oleh TensorFlow dapat diterapkan di hampir semua perangkat yang akan digunakan untuk menyajikan prediksi.
Keras : Keras adalah API pembelajaran mendalam yang ditulis dengan Python, berjalan di atas platform pembelajaran mesin TensorFlow. Ini dikembangkan dengan fokus untuk memungkinkan eksperimen cepat. Mampu beralih dari ide ke hasil secepat mungkin adalah kunci untuk melakukan penelitian yang baik.
Numpy : Numpy adalah paket fundamental untuk komputasi ilmiah dengan Python. Ini adalah  pustaka Python yang menyediakan objek array multidimensi, berbagai objek turunan (seperti array dan matriks bertopeng), dan bermacam-macam rutin untuk operasi cepat pada array, termasuk manipulasi bentuk matematis, logis, bentuk, menyortir, memilih, I/O, transformasi Fourier diskrit, aljabar linier dasar, operasi statistik dasar, simulasi acak, dan banyak lagi.
Pandas : Pandas adalah paket Python open source yang paling banyak digunakan untuk ilmu data/analisis data dan tugas pembelajaran mesin. Itu dibangun di atas paket lain bernama Numpy, yang menyediakan dukungan untuk array multidimensi. Sebagai salah satu paket perselisihan data yang paling populer, Pandas bekerja dengan baik dengan banyak modul ilmu data lainnya di dalam ekosistem Python, dan biasanya disertakan  dalam setiap distribusi Python, dari yang datang dengan sistem operasi hingga distribusi vendor komersial seperti ActivePython dari ActiveState.
Cv2 : cv2 adalah nama impor modul untuk opencv-python, "Paket OpenCV khusus CPU pra-bangun tidak resmi untuk Python". OpenCV tradisional memiliki banyak langkah rumit yang melibatkan pembuatan modul dari awal, yang tidak diperlukan. Kami akan merekomendasikan untuk tetap menggunakan pustaka opencv-python.
Matplotlib : Matplotlib adalah pustaka komprehensif untuk membuat visualisasi statis, animasi, dan interaktif dengan Python. Matplotlib membuat hal-hal yang mudah menjadi mudah dan hal-hal yang sulit menjadi mungkin.

### D. Evaluasi
Sebelum melakukan evaluasi coba terlebih dahulu harus melakukan proses pengkodean (coding). Pengkodean (coding) yaitu bahasa pemrograman yang menerjemahkan design kedalam bahasa yang dapat dipahami oleh komputer. Pada tahap evaluasi ini yaitu tahapan secara nyata (real) dalam melakukan pengerjaan sistem yaitu dapat melakukan proses pendeteksian sampah pada data. Maksudnya dalam penggunaan komputer akan dioptimalkan dalam tahap ini. Setelah selesai melakukan proses pengkodean (coding), selanjutnya membuat proses evaluasi dengan menggunakan set testing.
