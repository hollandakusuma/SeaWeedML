# Proyek Machine Learning Kadar Air Rumput Laut Kappaphycus Alvarezii - Hollanda Arief Kusuma

## Domain Proyek
_Kappaphycus alvarezii_ (_K. alvarezii_), juga dikenal sebagai _Eucheuma cottonii_, adalah spesies rumput laut merah penting secara komersial yang ditemukan di perairan tropis [1]. Rumput laut ini dijumpai di Kepulauan Riau terutama di Kabupaten Karimun, Kabupaten Natuna, dan Kabupaten Lingga [2]–[4]. Rumput laut ini memiliki potensi ekonomi yang besar sebagai sumber bahan baku dalam industri pangan, farmasi, dan kosmetik [5]. Pertumbuhan dan kesehatan rumput laut ini sangat dipengaruhi oleh faktor lingkungan, terutama ketersediaan air dan kandungan air dalam jaringannya [6]. 
Pemantauan kandungan air pada _K. alvarezii_ sangat penting baik untuk pertumbuhan dan kesehatannya, serta untuk aplikasi industri. Dari sudut pandang pertumbuhan dan kesehatan, kandungan air mempengaruhi proses fisiologis rumput laut, seperti fotosintesis dan respirasi, yang penting untuk pertumbuhan dan kelangsungan hidupnya [7], [8]. Selain itu, kandungan air dapat mempengaruhi terjadinya epifit dan infeksi penyakit, sehingga dapat berdampak negatif terhadap pertumbuhan _K. alvarezii_ [9]. Dari perspektif aplikasi industri, kadar air merupakan faktor kunci dalam menentukan kualitas dan hasil karagenan, hidrokoloid yang diekstraksi dari _K. alvarezii_, yang digunakan dalam berbagai produk makanan dan non-makanan [10]. 
Metode konvensional dalam mengukur kadar air dalam rumput laut menghadapi beberapa tantangan, termasuk proses yang memakan waktu, tenaga, dan invasif [11]. Oleh karena itu, pengembangan metode non-destruktif dan cepat untuk karakterisasi kandungan air dalam rumput laut menjadi perhatian utama. Salah satunya menggunakan metode spektrofotometri. Sensor spektroskopi AS7265x beroperasi dengan mengukur spektrum cahaya dalam rentang UV, sinar tampak, dan IR, memberikan solusi portabel dan efisien untuk analisis kualitatif dan kuantitatif [12]. Sensor ini memiliki resolusi 25-50 nm dengan rentang pengukuran dari 410 nm hingga 940 nm [13]. Sensor ini menawarkan keunggulan dibandingkan metode konvensional, seperti sensor spektro [14] dan spektrograf tradisional [15], karena ukurannya yang ringkas dan kemampuannya mengukur rentang panjang gelombang yang luas.
Sensor AS7265x perlu diintegrasikan dengan mikrokontroler untuk memperoleh data secara akurat dan efisien. Perangkat akuisisi data merupakan integrasi antara sensor, mikrokontroler, micro SD, Real Time Clock, display, dan komponen lainnya yang akan membuat sebuah perangkat akuisisi data yang dapat melakukan pengambilan, penyimpanan, dan tampilan data secara efektif dan efisien. Mikrokontroler berperan sebagai otak sistem yang mengatur operasi dan interaksi antara semua komponen tersebut. Beberapa penelitian menggunakan Arduino [16]–[21] dan ESP32 [21]–[23]. Namun Refly dan Kusuma [24] menyampaikan bahwa ESP32 lebih rendah konsumsi dayanya daripada Arduino. Oleh karena itu, pemilihan mikrokontroler dengan konsumsi daya yang rendah, seperti ESP32, menjadi krusial untuk memastikan kinerja perangkat akuisisi data secara optimal.
Karakterisasi spektral kandungan air pada _K. alvarezii_ di wilayah Kepulauan Riau atau Indonesia pada umumnya merupakan bidang yang belum banyak diteliti secara komprehensif. Sementara penelitian telah mengevaluasi pertumbuhan dan kualitas produk _K. alvarezii_ di berbagai lokasi budidaya di Indonesia [25], menilai kesesuaian perairan untuk budidayanya di Kepulauan Obi [26], dan mengevaluasi kesesuaian air untuk keberlanjutannya. budidaya di Kalimantan Utara [27], tidak ada yang secara khusus berfokus pada karakterisasi spektral kandungan air. Kesenjangan ini memberikan peluang untuk mengeksplorasi potensi penggunaan karakterisasi spektral untuk menilai kandungan air di _K. alvarezii_. Oleh karena itu, penelitian ini bertujuan untuk mengisi kesenjangan pengetahuan tersebut dengan menggunakan sensor spektroskopi AS7265x. Dengan memanfaatkan sensor spektroskopi AS7265x dan _machine learning_, diharapkan penelitian ini dapat memberikan kontribusi dalam pemahaman yang lebih baik tentang hubungan antara karakteristik spektral dengan kandungan air dalam rumput laut _K. alvarezii_. 

**Daftar Pustaka**:

[1]	R. Rama, L. Ode Muhammad Aslan, W. Iba, A. R. Nurdin, A. Armin, and Y. Yusnaeni, “Seaweed Cultivation of Micropropagated Seaweed (Kappaphycus alvarezii) in Bungin Permai Coastal Waters, Tinanggea Sub-District, South Konawe Regency, South East Sulawesi.,” IOP Conf. Ser. Earth Environ. Sci., vol. 175, p. 012219, Jul. 2018, doi: 10.1088/1755-1315/175/1/012219.

[2]	A. F. Ilhamdy, Jumsurizal, W. K. Shabilla, and G. Pratama, “Sifat Fisiko-Kimia Semi Refined Carrageenan (SRC) Kappaphycus Alvarezii Dari Perairan Karimun, Kepulauan Riau, Indonesia,” J. Perikan. dan Kelaut., vol. 9, no. 1, pp. 125–136, 2019, [Online]. Available: https://jurnal.untirta.ac.id/index.php/jpk/article/view/7079

[3]	Astika, A. F. Ilhamdy, and R. M. S. Putri, “Karakterisasi Beberapa Rumput Laut Dari Perairan Natuna Sebagai Sediaan Kosmetik,” Marinade, vol. 05, no. 02, pp. 77–84, 2022, [Online]. Available: https://ojs.umrah.ac.id/index.php/marinade/article/view/4667/1852

[4]	Herianto, “Evaluasi Pertumbuhan Rumput Laut Kappaphycus Alvarezii Dengan Jarak Peletakan Wadah Berbeda Ketinggian Dari Dasar Perairan,” [Bachelor Thesis] Universitas Maritim Raja Ali Haji, 2024. [Online]. Available: http://repositori.umrah.ac.id/6906/

[5]	J. Necas and L. Bartosikova, “Carrageenan: A review,” Vet. Med. (Praha)., vol. 58, no. 4, pp. 187–205, 2013, doi: 10.17221/6758-VETMED.

[6]	A. R. Sunny, “A review on effect of global climate change on seaweed and seagrass,” Int. J. Fish. Aquat. Stud., vol. 5, no. 6, pp. 19–22, 2017, [Online]. Available: https://www.fisheriesjournal.com/archives/2017/vol5issue6/PartA/5-5-49-118.pdf

[7]	P. G. Araújo, A. E. Nardelli, V. C. Gelli, M. T. Fujii, and F. Chow, “Monitoring environmental risk of the exotic species Kappaphycus alvarezii (Rhodophyta), after two decades of introduction in southeastern Brazil,” Bot. Mar., vol. 63, no. 6, pp. 551–558, Dec. 2020, doi: 10.1515/bot-2020-0052.

[8]	B. Castelar, R. P. Reis, and M. Bastos, “Contribuição ao protocolo de monitoramento ambiental da maricultura de Kappaphycus alvarezii (Doty) Doty ex P.C. Silva (Areschougiaceae - Rhodophyta) na baía de Sepetiba, RJ, Brasil,” Acta Bot. Brasilica, vol. 23, no. 3, pp. 613–617, Sep. 2009, doi: 10.1590/S0102-33062009000300001.

[9]	M. Ateweberhan, A. Rougier, and C. Rakotomahazo, “Influence of environmental factors and farming technique on growth and health of farmed Kappaphycus alvarezii (cottonii) in south-west Madagascar,” J. Appl. Phycol., vol. 27, no. 2, pp. 923–934, Apr. 2015, doi: 10.1007/s10811-014-0378-3.

[10]	L. O. M. Aslan et al., “Field cultivation of Kappaphycus alvarezii (DOTY) doty ex silva using tissue-cultured seedlings at bungin permai costal waters, south konawe, Southeast (SE) Sulawesi: the third year of seaweed growth monitoring,” IOP Conf. Ser. Earth Environ. Sci., vol. 473, no. 1, p. 012007, Mar. 2020, doi: 10.1088/1755-1315/473/1/012007.

[11]	L. Zhang, E. Gionfriddo, V. Acquaro, and J. Pawliszyn, “Direct immersion solid-phase microextraction analysis of multi-class contaminants in edible seaweeds by gas chromatography-mass spectrometry,” Anal. Chim. Acta, vol. 1031, pp. 83–97, Nov. 2018, doi: 10.1016/j.aca.2018.05.066.

[12]	B. Daurai, S. S. Ramchiary, and M. Gogoi, “Comparison of Sparkfun TRIAD AS7265x spectroscopy sensor device with a Spectrophotometer for qualitative and quantitative analysis,” in 2023 4th International Conference on Computing and Communication Systems (I3CS), IEEE, Mar. 2023, pp. 1–3. doi: 10.1109/I3CS58314.2023.10127282.

[13]	ams AG, “AS7265x Datasheet,” Premstaetten, 2018. [Online]. Available: https://ams.com/documents/20143/36005/AS7265x_DS000612_1-00.pdf

[14]	R. Stanziola, B. Momiroff, and H. Hemmendinger, “The spectro sensor—A new generation spectrophotometer,” Color Res. Appl., vol. 4, no. 3, pp. 157–163, 1979, doi: 10.1002/col.5080040308.

[15]	J. Allington-Smith and J. Bland-Hawthorn, “Astrophotonic spectroscopy: defining the potential advantage,” Mon. Not. R. Astron. Soc., Mar. 2010, doi: 10.1111/j.1365-2966.2009.16173.x.

[16]	H. A. Kusuma, R. Anjasmara, T. Suhendra, A. H. Yunianto, and S. Nugraha, “An IoT Based Coastal Weather and Air Quality Monitoring Using GSM Technology,” J. Phys. Conf. Ser., vol. 1501, no. 012004, 2020, doi: 10.1088/1742-6596/1501/1/012004.

[17]	R. Anjasmara, T. Suhendra, and A. H. Yunianto, “Implementasi Sistem Monitoring Kecepatan Angin, Suhu, dan Kelembaban Berbasis Web di Daerah Kepulauan,” J. Appl. Electr. Eng., vol. 3, no. 2, pp. 29–35, Dec. 2019, doi: 10.30871/jaee.v3i2.1485.

[18]	H. A. Kusuma, R. Purbakawaca, I. R. Pamungkas, L. N. Fikry, and S. S. Maulizar, “Design and Implementation of IoT-Based Water Pipe Pressure Monitoring Instrument,” J. Elektron. dan Telekomun., vol. 21, no. 1, pp. 41–47, 2021, doi: 10.14203/jet.v21.41-44.

[19]	H. A. Kusuma, M. I. Wahyuni, and S. Nugraha, “Pengembangan Instrumen Pengukuran Aliran Air Berbasis Internet of Things (IoT),” J. Elektro dan Mesin Terap., vol. 7, no. 1, pp. 47–56, May 2021, doi: 10.35143/elementer.v7i1.4627.

[20]	S. Nugraha, R. T. Putra, R. Pramana, H.A. Kusuma, T. Suhendra, E. Prayetno, and D. Nusyirwan, “Monitoring Keasaman dan Kekeruhan Air menggunakan Mikrokontroler Berbasis Internet of Things,” J. Sustain. J. Has. Penelit. dan Ind. Terap., vol. 9, no. 2, pp. 60–66, Oct. 2020, doi: 10.31629/sustainable.v9i2.2765.

[21]	H. Kusuma, M. A. Akbar, T. Suhendra, A. Zuchriadi, and A. K. A. Cintra, “IoT Sea Level Monitoring Development and Field Testing Study,” ELECTRON J. Ilm. Tek. Elektro, vol. 4, no. 2, pp. 70–77, Nov. 2023, doi: 10.33019/electron.v4i2.50.

[22]	T. Akbar, H. Fakhrurroja, and H. Kusuma, “Development of Temperature Control and Monitoring System for Precision Aquaculture Based on the Internet of Things,” in Proceedings of the 1st International Conference on Sustainable Engineering Development and Technological Innovation, ICSEDTI 2022, 11-13 October 2022, Tanjungpinang, Indonesia, EAI, 2023. doi: 10.4108/eai.11-10-2022.2326275.

[23]	H. A. Kusuma, D. Oktavia, S. Nugraha, T. Suhendra, and S. Refly, “Sensor BMP280 Statistical Analysis for Barometric Pressure Acquisition,” IOP Conf. Ser. Earth Environ. Sci., vol. 1148, no. 1, pp. 0–9, 2023, doi: 10.1088/1755-1315/1148/1/012008.

[24]	S. Refly and H. A. Kusuma, “Analisis Konsumsi dan Fluktuasi Arus dan Daya pada Mikrokontroler Menggunakan Sensor INA219,” J. Sustain. J. Has. Penelit. dan Ind. Terap., vol. 11, no. 1, pp. 44–48, 2022.

[25]	N. F. Simatupang, P. R. Pong-Masak, P. Ratnawati, Agusman, N. A. Paul, and M. A. Rimmer, “Growth and product quality of the seaweed Kappaphycus alvarezii from different farming locations in Indonesia,” Aquac. Reports, vol. 20, p. 100685, Jul. 2021, doi: 10.1016/j.aqrep.2021.100685.

[26]	R. Labenua and M. Aris, “Suitability Of Kappaphycus alvarezi Cultivation In Obi Island, North Maluku,” J. Ilm. PLATAX, vol. 9, no. 2, p. 217, Aug. 2021, doi: 10.35800/jip.9.2.2021.33048.

[27]	E. Maradhy, R. S. Nazriel, S. H. Sutjahjo, M. S. Rusli, W. Widiatmaka, and M. F. A. Sondita, “Evaluation of Water Suitability for Sustainable Seaweed (Kappaphycus Alvarezii) Cultivation to Support Science Technopark in North Kalimantan,” J. Pengelolaan Sumberd. Alam dan Lingkung. (Journal Nat. Resour. Environ. Manag., vol. 11, no. 3, pp. 490–503, Jan. 2022, doi: 10.29244/jpsl.11.3.490-503.


## Business Understanding

### Problem Statements
Rumusan Masalah dalam penelitian ini ialah:
1. Bagaimana cara mengelola data intensitas reflektansi cahaya yang berasal dari berbagai panjang gelombang untuk menghasilkan prediksi kadar air yang akurat?
2. Algoritma machine learning mana yang paling cocok untuk memodelkan hubungan antara data sensor dan kadar air rumput laut?
3. Apa fitur-fitur penting yang harus diperhatikan dalam pengolahan data, mengingat adanya pengaruh dominan dari channel tertentu pada sensor?

### Goals
1. Menentukan solusi berbasis machine learning untuk memprediksi kadar air rumput laut menggunakan data intensitas reflektansi dari sensor AS7265X.
2. Mengidentifikasi channel-channel sensor yang paling relevan dalam menentukan kadar air, berdasarkan sensitivitas panjang gelombangnya terhadap kadar air.
3. Membangun dan mengoptimalkan model prediksi, dengan menggunakan algoritma seperti neural network dan random forest, serta melakukan hyperparameter tuning untuk meningkatkan akurasi model.
4. Mengembangkan sistem yang terukur dengan metrik evaluasi yang jelas, seperti MAE (Mean Absolute Error) atau RMSE (Root Mean Squared Error), untuk memastikan kinerja model yang dapat diandalkan.

### Solution statements
1. Data Preprocessing: Menggunakan teknik normalisasi untuk menyiapkan data intensitas reflektansi dari 18 channel sensor AS7265X agar dapat diolah oleh model machine learning.
2. Model Development:
    a. Neural Network digunakan untuk menangkap pola non-linear yang kompleks dalam hubungan antara intensitas cahaya dan kadar air.
    b. Random Forest digunakan untuk memberikan informasi tentang pentingnya fitur dan meningkatkan stabilitas prediksi.
3. Hyperparameter Tuning: Menerapkan teknik seperti Grid Search atau Random Search untuk mengoptimalkan parameter model dan mencapai hasil terbaik.
4. Feature Selection: Mengidentifikasi channel-channel yang paling relevan dengan kadar air rumput laut menggunakan Random Forest dan teknik lainnya.
5. Model Evaluation: Metrik seperti Mean Absolute Error (MAE) dan Root Mean Squared Error (RMSE) akan digunakan untuk mengevaluasi performa model, memastikan prediksi yang lebih akurat dan dapat diandalkan.

## Data Understanding
Proyek ini menggunakan data yang dihasilkan oleh sensor AS7265X, yang merupakan sensor multi-channel yang mengukur reflektansi cahaya dalam 18 channel, mencakup cahaya tampak dan infrared. Setiap channel sensor ini sensitif terhadap panjang gelombang cahaya tertentu, yang mencakup berbagai spektrum mulai dari cahaya tampak (400-700 nm) hingga infrared. Data yang diperoleh dari sensor ini berfungsi untuk memprediksi kadar air rumput laut berdasarkan intensitas cahaya yang dipantulkan oleh rumput laut pada panjang gelombang tertentu.
![SeaSpec](https://github.com/user-attachments/assets/85303a0e-11bb-4aa5-968d-6c1e6e0aa59d)


Data yang digunakan dalam proyek ini terdiri dari dua komponen utama:
1. **Fitur Input (X)**: Intensitas reflektansi cahaya yang diukur pada 18 channel sensor AS7265X. Setiap channel mengukur tingkat reflektansi pada panjang gelombang tertentu, yang memberikan gambaran tentang karakteristik optik rumput laut pada spektrum yang berbeda.
2. **Target Output (y)**: Nilai kadar air rumput laut yang diukur pada saat yang sama dengan pengambilan data reflektansi. Nilai ini adalah target yang ingin diprediksi oleh model machine learning.

Setiap pengukuran dilakukan dalam satu set data yang mencakup 18 nilai intensitas reflektansi yang berbeda, yang kemudian akan dipetakan dengan nilai kadar air rumput laut pada waktu yang bersamaan. Data ini berfungsi sebagai dasar untuk membangun model prediksi kadar air rumput laut, yang memungkinkan analisis dan pemahaman lebih mendalam tentang bagaimana berbagai channel reflektansi berkontribusi terhadap estimasi kadar air.

Dalam tahap pemahaman data ini, penting untuk mengidentifikasi pola dalam hubungan antara intensitas reflektansi pada setiap channel dengan kadar air rumput laut. Analisis ini juga melibatkan penanganan data yang hilang atau noise yang mungkin ada dalam data sensor, serta normalisasi data agar model machine learning dapat mengolah data secara efektif.

### Variabel-variabel pada dataset Intensitas Reflektansi Rumput Laut adalah sebagai berikut:
1. Fitur Input (X):
| Nama       | Umur | Kota          |
|:-----------|-----:|:-------------:|
| Andi       |   25 |   Jakarta     |
| Budi       |   30 |   Surabaya    |
| Citra      |   22 |   Bandung     |


    - Kanal A (410nm, Violet): Intensitas reflektansi cahaya pada panjang gelombang 410nm
    - Kanal B (435nm, Violet – Biru): Intensitas reflektansi cahaya pada panjang gelombang 435nm
    - Kanal C (460nm, Biru): Intensitas reflektansi cahaya pada panjang gelombang 460nm
    - Kanal D (485nm, Biru – Hijau): Intensitas reflektansi cahaya pada panjang gelombang 485nm
    - Kanal E (510nm, Hijau): Intensitas reflektansi cahaya pada panjang gelombang 510nm
    - Kanal F (535nm, Hijau – Kuning): Intensitas reflektansi cahaya pada panjang gelombang 535nm
    - Kanal G (560nm, Kuning): Intensitas reflektansi cahaya pada panjang gelombang 560nm
    - Kanal H (585nm, Kuning – Jingga): Intensitas reflektansi cahaya pada panjang gelombang 585nm
    - Kanal R (610nm, Jingga): Intensitas reflektansi cahaya pada panjang gelombang 610nm
    - Kanal I (645nm, Jingga – Merah): Intensitas reflektansi cahaya pada panjang gelombang 645nm
    - Kanal S (680nm, Merah): Intensitas reflektansi cahaya pada panjang gelombang 680nm
    - Kanal J (705nm, Merah Pekat): Intensitas reflektansi cahaya pada panjang gelombang 705nm
    - Kanal T (730nm, Infra merah dekat): Intensitas reflektansi cahaya pada panjang gelombang 730nm
    - Kanal U (760nm, Infra merah dekat): Intensitas reflektansi cahaya pada panjang gelombang 760nm
    - Kanal V (810nm, Infra merah dekat): Intensitas reflektansi cahaya pada panjang gelombang 810nm
    - Kanal W (860nm, Infra merah dekat): Intensitas reflektansi cahaya pada panjang gelombang 860nm
    - Kanal K (900nm, Infra merah dekat): Intensitas reflektansi cahaya pada panjang gelombang 900nm
    - Kanal L (940nm, Infra merah dekat): Intensitas reflektansi cahaya pada panjang gelombang 940nm

3. Target Output (y):
    - Kadar Air Rumput Laut: Nilai kontinu yang menunjukkan kadar air dalam rumput laut yang diukur pada saat pengambilan data reflektansi dari sensor.

**Rubrik/Kriteria Tambahan (Opsional)**:
- Melakukan beberapa tahapan yang diperlukan untuk memahami data, contohnya teknik visualisasi data atau exploratory data analysis.

## Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan proses data preparation yang dilakukan
- Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.

## Modeling
Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan. Anda perlu menjelaskan tahapan dan parameter yang digunakan pada proses pemodelan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan kelebihan dan kekurangan dari setiap algoritma yang digunakan.
- Jika menggunakan satu algoritma pada solution statement, lakukan proses improvement terhadap model dengan hyperparameter tuning. **Jelaskan proses improvement yang dilakukan**.
- Jika menggunakan dua atau lebih algoritma pada solution statement, maka pilih model terbaik sebagai solusi. **Jelaskan mengapa memilih model tersebut sebagai model terbaik**.

## Evaluation
Pada bagian ini anda perlu menyebutkan metrik evaluasi yang digunakan. Lalu anda perlu menjelaskan hasil proyek berdasarkan metrik evaluasi yang digunakan.

Sebagai contoh, Anda memiih kasus klasifikasi dan menggunakan metrik **akurasi, precision, recall, dan F1 score**. Jelaskan mengenai beberapa hal berikut:
- Penjelasan mengenai metrik yang digunakan
- Menjelaskan hasil proyek berdasarkan metrik evaluasi

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
- _Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_
- Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin dijelaskan saja.

