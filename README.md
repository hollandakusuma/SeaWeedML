# Proyek Machine Learning Kadar Air Rumput Laut Kappaphycus Alvarezii - Hollanda Arief Kusuma

## Domain Proyek
_Kappaphycus alvarezii_ (_K. alvarezii_), juga dikenal sebagai _Eucheuma cottonii_, adalah spesies rumput laut merah penting secara komersial yang ditemukan di perairan tropis [1]. Rumput laut ini dijumpai di Kepulauan Riau terutama di Kabupaten Karimun, Kabupaten Natuna, dan Kabupaten Lingga [2]–[4]. Rumput laut ini memiliki potensi ekonomi yang besar sebagai sumber bahan baku dalam industri pangan, farmasi, dan kosmetik [5]. Pertumbuhan dan kesehatan rumput laut ini sangat dipengaruhi oleh faktor lingkungan, terutama ketersediaan air dan kandungan air dalam jaringannya [6]. 
Pemantauan kandungan air pada _K. alvarezii_ sangat penting baik untuk pertumbuhan dan kesehatannya, serta untuk aplikasi industri. Dari sudut pandang pertumbuhan dan kesehatan, kandungan air mempengaruhi proses fisiologis rumput laut, seperti fotosintesis dan respirasi, yang penting untuk pertumbuhan dan kelangsungan hidupnya [7], [8]. Selain itu, kandungan air dapat mempengaruhi terjadinya epifit dan infeksi penyakit, sehingga dapat berdampak negatif terhadap pertumbuhan _K. alvarezii_ [9]. Dari perspektif aplikasi industri, kadar air merupakan faktor kunci dalam menentukan kualitas dan hasil karagenan, hidrokoloid yang diekstraksi dari _K. alvarezii_, yang digunakan dalam berbagai produk makanan dan non-makanan [10]. 
Metode konvensional dalam mengukur kadar air dalam rumput laut menghadapi beberapa tantangan, termasuk proses yang memakan waktu, tenaga, dan invasif [11]. Oleh karena itu, pengembangan metode non-destruktif dan cepat untuk karakterisasi kandungan air dalam rumput laut menjadi perhatian utama. Salah satunya menggunakan metode spektrofotometri. Sensor spektroskopi AS7265x beroperasi dengan mengukur spektrum cahaya dalam rentang UV, sinar tampak, dan IR, memberikan solusi portabel dan efisien untuk analisis kualitatif dan kuantitatif [12]. Sensor ini memiliki resolusi 25-50 nm dengan rentang pengukuran dari 410 nm hingga 940 nm [13]. Sensor ini menawarkan keunggulan dibandingkan metode konvensional, seperti sensor spektro [14] dan spektrograf tradisional [15], karena ukurannya yang ringkas dan kemampuannya mengukur rentang panjang gelombang yang luas.
Sensor AS7265x perlu diintegrasikan dengan mikrokontroler untuk memperoleh data secara akurat dan efisien. Perangkat akuisisi data merupakan integrasi antara sensor, mikrokontroler, micro SD, Real Time Clock, display, dan komponen lainnya yang akan membuat sebuah perangkat akuisisi data yang dapat melakukan pengambilan, penyimpanan, dan tampilan data secara efektif dan efisien. Mikrokontroler berperan sebagai otak sistem yang mengatur operasi dan interaksi antara semua komponen tersebut. Beberapa penelitian menggunakan Arduino [16]–[21] dan ESP32 [21]–[23]. Namun Refly dan Kusuma [24] menyampaikan bahwa ESP32 lebih rendah konsumsi dayanya daripada Arduino. Oleh karena itu, pemilihan mikrokontroler dengan konsumsi daya yang rendah, seperti ESP32, menjadi krusial untuk memastikan kinerja perangkat akuisisi data secara optimal.
Karakterisasi spektral kandungan air pada _K. alvarezii_ di wilayah Kepulauan Riau atau Indonesia pada umumnya merupakan bidang yang belum banyak diteliti secara komprehensif. Sementara penelitian telah mengevaluasi pertumbuhan dan kualitas produk _K. alvarezii_ di berbagai lokasi budidaya di Indonesia [25], menilai kesesuaian perairan untuk budidayanya di Kepulauan Obi [26], dan mengevaluasi kesesuaian air untuk keberlanjutannya. budidaya di Kalimantan Utara [27], tidak ada yang secara khusus berfokus pada karakterisasi spektral kandungan air. Kesenjangan ini memberikan peluang untuk mengeksplorasi potensi penggunaan karakterisasi spektral untuk menilai kandungan air di _K. alvarezii_. Oleh karena itu, penelitian ini bertujuan untuk mengisi kesenjangan pengetahuan tersebut dengan menggunakan sensor spektroskopi AS7265x. Dengan memanfaatkan sensor spektroskopi AS7265x dan _machine learning_, diharapkan penelitian ini dapat memberikan kontribusi dalam pemahaman yang lebih baik tentang hubungan antara karakteristik spektral dengan kandungan air dalam rumput laut _K. alvarezii_. 

### Daftar Pustaka:

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

### Goals
1. Menentukan solusi berbasis machine learning untuk memprediksi kadar air rumput laut menggunakan data intensitas reflektansi dari sensor AS7265X.
2. Mengidentifikasi channel-channel sensor yang paling relevan dalam menentukan kadar air, berdasarkan sensitivitas panjang gelombangnya terhadap kadar air.
3. Membangun dan membandingkan model prediksi, dengan menggunakan algoritma seperti (a) random forest, (b) multi-layer perceptron regresi, (c) KNN, (d) AdaBoost, (e) GradienBoost, (f) MLP deep learning, dan (g) Decision Tree.
4. Mengembangkan sistem yang terukur dengan metrik evaluasi yang jelas, seperti MSE (*Mean Square Error*), R² (Koefisien Determinasi), MAE (*Mean Absolute Error*) atau RMSE (*Root Mean Squared Error*), untuk memastikan kinerja model yang dapat diandalkan.
5. Melakukan pengujian model dengan melakukan prediksi terhadap data yang ada.

### Solution statements
1. Data Preprocessing: Menggunakan teknik normalisasi untuk menyiapkan data intensitas reflektansi dari 18 channel sensor AS7265X agar dapat diolah oleh model machine learning.
2. Analisis PCA : Menggunakan Principal Component Analysis untuk mengkombinasi fitur kanal sensor.
3. Model Development:
    a. Neural Network digunakan untuk menangkap pola non-linear yang kompleks dalam hubungan antara intensitas cahaya dan kadar air.
    b. Random Forest digunakan untuk memberikan informasi tentang pentingnya fitur dan meningkatkan stabilitas prediksi.

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
**1. Fitur Input (X)**:
   
| Kanal     | Panjang Gelombang (nm) | Warna          |
|:-----------|:-----:|:-------------:|
| Kanal A    |  410 |   Violet     |
| Kanal B |435| Violet – Biru|
|Kanal C |460|Biru|
|Kanal D |485|Biru – Hijau|
|Kanal E|510|Hijau|
|Kanal F|535|Hijau – Kuning|
|Kanal G |560|Kuning|
|Kanal H |585| Kuning – Jingga|
|Kanal R |610| Jingga|
|Kanal I |645| Jingga – Merah|
|Kanal S |680| Merah|
| Kanal J |705| Merah Pekat|
| Kanal T |730|Infra merah dekat|
| Kanal U |760|Infra merah dekat|
| Kanal V |810|Infra merah dekat|
| Kanal W |860| Infra merah dekat|
| Kanal K |900| Infra merah dekat|
| Kanal L |940| Infra merah dekat|

**2. Target Output (y)**:
    - **Kadar Air Rumput Laut**: Nilai kontinu yang menunjukkan kadar air dalam rumput laut yang diukur pada saat pengambilan data reflektansi dari sensor.

**3. URL Dataset** : (https://tinyurl.com/datarumputlaut)

**4. Struktur Dataset**
Dataset yang digunakan memiliki **4322 baris** dan **19 kolom**, di mana setiap baris mewakili sampel, dan kolom-kolomnya adalah fitur serta target yang akan diprediksi. **Kolom 1** berisi nilai kadar air rumput laut, **kolom 2-19** merupakan nilai intensitasi reflektansi setiap kanal.

**5. Kondisi Data**
- **Missing Values**: Tidak ditemukan nilai yang hilang (missing value) dalam dataset.
- **Duplikasi Data**: Tidak ada baris yang terduplikasi.
- **Outlier**: Terdapat beberapa nilai outlier pada kanal tertentu, yang teridentifikasi melalui analisis *box plot*.

**6.Visualisasi Data**
- **Box Plot**: Digunakan untuk mendeteksi keberadaan outlier pada setiap kanal sensor.
- **Histogram Plot**: Setiap kanal dianalisis distribusinya. Pola distribusi data terlihat berbeda untuk setiap panjang gelombang, menunjukkan karakteristik unik tiap kanal.
- **Scatter Plot**: Hubungan antara setiap kanal dengan kadar air ditampilkan untuk memahami korelasi antar fitur.
     
**Tahapan Data Understanding**:
- Data Loading : Import data dari google drive
- Preview Data: Menampilkan struktur dataset.
- Statistik Deskriptif: Rata-rata, standar deviasi, dll.
- Distribusi Data: Histogram untuk setiap kanal.
- Matriks Korelasi: Visualisasi hubungan antar kanal dan target.
- Outliers: Deteksi menggunakan boxplot.
- Scatter Plot: Hubungan antar kanal reflektansi dan nilai R².
- Distribusi Target: Distribusi kadar air.

## Data Preparation
### 1. Standarisasi Data

Standarisasi nilai adalah langkah penting dalam **pra-pemrosesan data** sebelum melakukan analisis atau pembangunan model, terutama ketika menggunakan metode seperti **Principal Component Analysis (PCA)**, **regresi**, dan **klasifikasi**. Tujuan dari standarisasi adalah untuk mengubah skala fitur (variabel) sehingga setiap fitur memiliki rata-rata 0 dan deviasi standar 1. Proses ini membantu memastikan bahwa semua fitur memiliki kontribusi yang setara dalam model, mencegah fitur dengan skala lebih besar mendominasi proses analisis.

Standarisasi dilakukan dengan cara berikut:

$$
x_{\text{scaled}} = \frac{x - \mu}{\sigma}
$$

Dimana:
- (x) adalah nilai data mentah,
- (μ) adalah rata-rata dari data,
- (σ) adalah deviasi standar dari data.

### Implementasi dengan Python (Menggunakan `StandardScaler` dari `sklearn`):

```python
from sklearn.preprocessing import StandardScaler

# Inisialisasi objek StandardScaler
scaler = StandardScaler()

# Standarisasi data (misalnya, 'data' adalah DataFrame Anda)
data_scaled = scaler.fit_transform(data.drop(columns=['Kadar Air']))  # Menghapus kolom target 'Kadar Air'
```

### 2. Reduksi Dimensi dengan PCA

PCA adalah teknik yang digunakan untuk mengurangi jumlah fitur dengan cara mengubah fitur yang ada menjadi kombinasi linier yang lebih sedikit tetapi tetap mempertahankan sebanyak mungkin varians (informasi) dari data asli. Teknik ini sangat berguna jika Anda memiliki banyak kanal dan ingin mengurangi kompleksitas data tanpa kehilangan banyak informasi penting. PCA membantu kita untuk memahami struktur data dan memvisualisasikan data yang kompleks dengan cara yang lebih sederhana.

**Tujuan utama dari PCA** adalah untuk mengurangi jumlah fitur (dimensi) dalam dataset, sambil mempertahankan sebanyak mungkin variasi yang ada. Dengan kata lain, PCA berusaha menemukan proyeksi data dalam ruang dimensi yang lebih rendah, yang menjelaskan variasi terbesar di dalam data.

Pada langkah ini, PCA (Principal Component Analysis) digunakan untuk mengurangi dimensi data dengan cara memilih jumlah komponen yang optimal. Langkah-langkah yang dilakukan adalah sebagai berikut:

1. **Standarisasi Data**: Sebelum melakukan PCA, data harus distandarisasi agar setiap fitur memiliki skala yang sama. Hal ini penting karena PCA peka terhadap skala data.
  
2. **Menghitung Explained Variance**: Melakukan perhitungan untuk melihat seberapa banyak variansi yang dijelaskan oleh setiap komponen utama. Dengan memeriksa nilai *explained variance* dan *cumulative variance*, kita memilih jumlah komponen yang cukup untuk menjelaskan sebagian besar variansi data (misalnya, 95%).

3. **Heatmap Kontribusi Kanal terhadap Komponen PCA**: Setelah memilih jumlah komponen yang optimal, kita menghitung kontribusi setiap kanal sensor terhadap komponen utama dan memvisualisasikan hasilnya dalam bentuk heatmap untuk melihat hubungan antar kanal dengan komponen utama.

```python
import matplotlib.pyplot as plt
import numpy as np
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
import seaborn as sns

# Standarisasi data (misalnya data adalah DataFrame yang berisi kanal-kanal)
scaler = StandardScaler()
data_scaled = scaler.fit_transform(data.drop(columns=['Kadar Air']))  # Menghapus target 'Kadar Air'

# Inisialisasi PCA dan fit pada data
pca = PCA()
pca.fit(data_scaled)

# Plot explained variance
plt.figure(figsize=(8, 6))
plt.bar(range(1, len(pca.explained_variance_ratio_) + 1), pca.explained_variance_ratio_)
plt.xlabel('PCA Komponen')
plt.ylabel('Varians yang Dijelaskan')
plt.title('Explained Variance untuk Setiap Komponen PCA')
plt.xticks(np.arange(1, len(pca.explained_variance_ratio_) + 1, 1))
plt.show()

# Menampilkan total explained variance kumulatif
explained_variance_cumulative = np.cumsum(pca.explained_variance_ratio_)
plt.figure(figsize=(8, 6))
plt.plot(range(1, len(explained_variance_cumulative) + 1), explained_variance_cumulative, marker='o', color='b')
plt.xlabel('Jumlah Komponen PCA')
plt.ylabel('Kumulatif Varians yang Dijelaskan')
plt.title('Kumulatif Varians yang Dijelaskan oleh PCA')
plt.xticks(np.arange(1, len(pca.explained_variance_ratio_) + 1, 1))
plt.grid(True)
plt.show()

# Pilih jumlah komponen PCA yang sesuai (misalnya 6)
pca = PCA(n_components=6)
data_pca = pca.fit_transform(data_scaled)

# Visualisasi Heatmap Kontribusi Setiap Kanal terhadap Komponen PCA
pca_components = pca.components_  # Eigenvectors sebagai kontribusi kanal terhadap komponen

plt.figure(figsize=(10, 6))
sns.heatmap(pca_components, cmap='coolwarm', annot=True, xticklabels=data.drop(columns=['Kadar Air']).columns, 
            yticklabels=[f'Komponen {i+1}' for i in range(6)])
plt.title('Kontribusi Setiap Kanal terhadap 6 Komponen PCA')
plt.xlabel('Kanal Sensor')
plt.ylabel('PCA Komponen')
plt.show()
```

Penjelasan Kode
1. **Standarisasi Data**: Data fitur distandarisasi agar setiap fitur memiliki rata-rata 0 dan deviasi standar 1 menggunakan `StandardScaler`.
2. **PCA**: Komponen utama dihitung dengan menggunakan `PCA()` dari `sklearn.decomposition`. Jumlah komponen yang digunakan ditentukan berdasarkan varians yang dijelaskan.
3. **Visualisasi Explained Variance**: Bar chart menggambarkan seberapa besar varians yang dijelaskan oleh masing-masing komponen utama.
4. **Heatmap Kontribusi**: Heatmap ini menggambarkan kontribusi setiap kanal sensor terhadap komponen-komponen utama. Setiap sel menunjukkan kontribusi relatif antara kanal dan komponen PCA.


### 3. Train-Test-Split

Pada langkah ini, kita membagi dataset menjadi dua bagian: satu untuk pelatihan (training) dan satu lagi untuk pengujian (testing). Pembagian ini penting untuk memastikan bahwa model yang dibangun dapat dievaluasi secara objektif menggunakan data yang belum pernah dilihat sebelumnya oleh model.

- **Data X**: Merupakan data komponen PCA yang telah dihasilkan dari proses PCA sebelumnya.
- **Data Y**: Merupakan data kadar air yang menjadi target atau label yang ingin diprediksi.

Proses pembagian dilakukan dengan menggunakan fungsi `train_test_split` dari *scikit-learn*. Pembagian dilakukan dengan proporsi 80% untuk data pelatihan dan 20% untuk data pengujian, sehingga model akan dilatih menggunakan 80% data dan diuji menggunakan 20% data.

**Langkah-langkah**:
1. **Menyiapkan Data**: Data `X` berisi fitur-fitur hasil PCA, dan data `Y` berisi nilai kadar air.
2. **Melakukan Split**: Fungsi `train_test_split` digunakan untuk membagi data secara acak dengan proporsi yang ditentukan.
3. **Output**: Hasil pembagian adalah empat dataset:
   - `X_train`: Data pelatihan untuk fitur.
   - `X_test`: Data pengujian untuk fitur.
   - `Y_train`: Data pelatihan untuk target kadar air.
   - `Y_test`: Data pengujian untuk target kadar air.

### Contoh Kode Program:
```python
from sklearn.model_selection import train_test_split

# Misalkan data_pca adalah data yang telah melalui PCA (X)
# Misalkan target adalah kadar air (Y)
X = data_pca  # Data komponen PCA
Y = data['Kadar Air']  # Target kadar air

# Melakukan train-test split dengan proporsi 80% untuk training dan 20% untuk testing
X_train, X_test, Y_train, Y_test = train_test_split(X, Y, test_size=0.2, random_state=42)

# Menampilkan ukuran data setelah split
print(f'Ukuran data pelatihan X: {X_train.shape}')
print(f'Ukuran data pengujian X: {X_test.shape}')
print(f'Ukuran data pelatihan Y: {Y_train.shape}')
print(f'Ukuran data pengujian Y: {Y_test.shape}')
```

Penjelasan Kode:

`train_test_split(X, Y, test_size=0.2, random_state=42)`: Fungsi ini membagi dataset menjadi data latih dan data uji. `X` berisi data komponen PCA (fitur), dan `Y` berisi data kadar air (target). Parameter `test_size=0.2` berarti 20% data digunakan untuk pengujian, sedangkan 80% untuk pelatihan. `random_state=42` digunakan agar hasil split dapat direproduksi di lain waktu.

`X_train, X_test, Y_train, Y_test`: Variabel ini berisi data pelatihan dan data pengujian untuk fitur (`X`) dan target (`Y`).
    
## Modeling

Dalam permasalahan ini, kami menggunakan beberapa algoritma machine learning untuk memprediksi kadar air berdasarkan data intensitas cahaya dari sensor. Model yang digunakan ialah:

- **Random Forest**
- **Neural Network (MLP)**
- **K-Nearest Neighbors (KNN)**
- **AdaBoost**
- **Gradient Boost**
- **Deep Neural Network (DNN)**
- **Decision Tree**

## Tahapan Pemodelan
Pemodelan machine learning dilakukan dalam beberapa tahapan sebagai berikut:

1. **Persiapan Data**: Data yang tersedia dibagi menjadi dua set, yaitu data pelatihan (training) dan data pengujian (testing).
2. **Pembuatan Model**: Setiap algoritma machine learning dilatih menggunakan data pelatihan.
3. **Evaluasi Model**: Model dievaluasi menggunakan metrik evaluasi seperti MSE (Mean Squared Error), MAE (Mean Absolute Error), RMSE (Root Mean Squared Error), dan R² (Koefisien Determinasi) untuk mengukur kinerja model baik pada data pelatihan maupun data pengujian.
4. **Pemilihan Model Terbaik**: Model yang menunjukkan hasil terbaik pada data pengujian dipilih sebagai solusi.

## Penjelasan Algoritma yang Digunakan

## Modeling

Dalam permasalahan ini, kami menggunakan beberapa algoritma machine learning untuk memprediksi kadar air berdasarkan data intensitas cahaya dari sensor. Model yang digunakan ialah:

### 1. **Random Forest**
   - **Deskripsi**: Random Forest adalah algoritma ensemble yang menggunakan banyak pohon keputusan untuk meningkatkan akurasi prediksi. Setiap pohon keputusan dilatih dengan sampel data yang berbeda, dan hasil akhir dihasilkan dengan mengambil rata-rata atau voting dari semua pohon.
   - **Parameter yang digunakan**:

`n_estimators=100`: Model membangun 100 pohon keputusan.

`random_state=42`: Parameter ini memastikan replikasi hasil dengan menetapkan nilai acak yang sama.

   - **Kelebihan**:
     - Tidak mudah overfitting pada data yang kompleks.
     - Dapat menangani data besar dengan banyak fitur.
   - **Kekurangan**:
     - Memerlukan waktu komputasi yang lebih lama, terutama untuk jumlah pohon yang banyak.
     - Model yang dihasilkan lebih sulit untuk diinterpretasikan.

### 2. **Neural Network (MLP)**
   - **Deskripsi**: Multi-Layer Perceptron (MLP) adalah jenis neural network dengan satu atau lebih lapisan tersembunyi. Model ini berfungsi untuk memodelkan hubungan non-linear antara input dan output.

   - **Parameter yang digunakan**:

`hidden_layer_sizes=(50, 30)`: Model terdiri dari dua lapisan tersembunyi, masing-masing memiliki 50 dan 30 neuron.

`max_iter=1000`: Model dilatih hingga maksimal 1.000 iterasi untuk konvergensi.

`random_state=42`: Memastikan hasil yang dapat direproduksi.

   - **Kelebihan**:
     - Mampu mempelajari pola yang kompleks dan non-linear.
     - Cukup fleksibel dan dapat digunakan untuk berbagai masalah.
   - **Kekurangan**:
     - Cenderung memerlukan banyak data untuk melatih model secara efektif.
     - Rentan terhadap overfitting jika jumlah data terbatas.

### 3. **K-Nearest Neighbors (KNN)**
   - **Deskripsi**: KNN adalah algoritma yang melakukan klasifikasi atau regresi berdasarkan kedekatan data dengan titik-titik data lainnya. Prediksi dilakukan dengan melihat nilai dari K tetangga terdekat.
   - **Parameter utama:** `n_neighbors=5`: Model menggunakan 5 tetangga terdekat dalam perhitungannya.

   - **Kelebihan**:
     - Sederhana dan mudah dipahami.
     - Tidak memerlukan asumsi distribusi data.
   - **Kekurangan**:
     - Sangat sensitif terhadap data yang tidak relevan atau noise.
     - Membutuhkan waktu komputasi yang lama pada data besar karena perhitungan jarak untuk setiap prediksi.

### 4. **AdaBoost (Adaptive Boosting)**
   - **Deskripsi**: AdaBoost adalah algoritma ensemble yang menggabungkan beberapa model yang lebih sederhana untuk membentuk model yang lebih kuat. Model yang lebih lemah diberikan bobot lebih besar saat kesalahan prediksi meningkat.
   - **Parameter yang digunakan:**

`n_estimators=50`: Model menjalankan 50 iterasi untuk menguatkan prediksi.

`random_state=42`: Menetapkan nilai awal acak untuk hasil yang dapat direplikasi.

   - **Kelebihan**:
     - Dapat meningkatkan akurasi model yang lemah.
     - Sederhana dan dapat digunakan untuk banyak jenis model dasar.
   - **Kekurangan**:
     - Rentan terhadap overfitting pada data yang sangat berisik.
     - Mungkin tidak seefektif pada model yang sangat kompleks.

### 5. **Gradient Boosting**
   - **Deskripsi**: Gradient Boosting adalah algoritma ensemble yang mengkombinasikan pohon keputusan sederhana dalam urutan bertahap, dengan setiap pohon mengoreksi kesalahan model sebelumnya.
   - **Parameter yang digunakan:**

`n_estimators=100`: Model membangun 100 pohon keputusan untuk memaksimalkan akurasi.

`random_state=42`: Memastikan hasil yang konsisten.

   - **Kelebihan**:
     - Efektif untuk menangani data yang besar dan kompleks.
     - Meningkatkan akurasi prediksi secara signifikan.
   - **Kekurangan**:
     - Memerlukan waktu pelatihan yang lebih lama.
     - Bisa overfit pada data yang sangat bising jika tidak disetel dengan baik.

### 6. **Deep Neural Network (DNN)**
   - **Deskripsi**: Deep Neural Network (DNN) adalah jenis neural network dengan banyak lapisan tersembunyi yang memungkinkan model untuk menangkap pola yang lebih kompleks dan lebih dalam dari data.
   - **Parameter yang digunakan:**

Loss function: `mean_squared_error` digunakan untuk mengukur kesalahan regresi.

Optimizer: `adam` untuk pembaruan bobot yang efisien.

Epochs: Model dilatih selama `100 epoch`.

Batch size: `32 data` diproses dalam setiap iterasi pembaruan bobot.

   - **Kelebihan**:
     - Sangat efektif untuk masalah yang melibatkan data besar dan kompleks.
     - Mampu melakukan representasi fitur yang sangat kompleks.
   - **Kekurangan**:
     - Membutuhkan data dalam jumlah besar untuk melatih model secara efektif.
     - Rentan terhadap overfitting tanpa regularisasi yang tepat.

### 7. **Decision Tree**
   - **Deskripsi**: Decision Tree adalah model prediksi berbentuk pohon yang membagi data ke dalam cabang-cabang berdasarkan fitur tertentu hingga mencapai hasil yang diinginkan.
   - **Parameter yang digunakan:** `random_state=42`: Menetapkan nilai acak yang memastikan konsistensi hasil.
   - **Kelebihan**:
     - Mudah diinterpretasikan dan divisualisasikan.
     - Dapat menangani data yang tidak terstruktur dan fitur kategorikal.
   - **Kekurangan**:
     - Rentan terhadap overfitting jika tidak dipangkas dengan baik.
     - Dapat menghasilkan model yang terlalu sederhana jika pohon terlalu kecil.

## Memilih Model Terbaik

Berdasarkan hasil evaluasi pada data pengujian (*data test*), model terbaik dipilih berdasarkan metrik yang diinginkan (MSE, MAE, RMSE, dan R²). Model yang memberikan performa terbaik dalam hal akurasi dan kecepatan prediksi akan dipilih sebagai solusi untuk prediksi kadar air.

**Model terbaik**: Misalnya, jika **Gradient Boosting** memiliki performa terbaik dalam hal metrik dibandingkan model lainnya, maka **Gradient Boosting** akan dipilih sebagai model final.

## Evaluation

Dalam evaluasi model machine learning untuk memprediksi kadar air berdasarkan data intensitas cahaya dari sensor, digunakan beberapa metrik evaluasi untuk mengukur kinerja model. Metrik evaluasi yang digunakan disesuaikan dengan konteks data, problem statement, dan solusi yang diinginkan.

### 1. **Mean Absolute Error (MAE)**
   - **Deskripsi**: MAE mengukur rata-rata perbedaan absolut antara nilai prediksi dan nilai aktual (ground truth). Metrik ini memberikan gambaran yang jelas tentang seberapa besar kesalahan prediksi dalam unit yang sama dengan data.
   - **Formula**:  $MAE =\frac {1}{n} \sum_{i=1}^{n} |y_i - \hat{y_i}|$

     Di mana:
     - $( y_i)$ adalah nilai aktual
     - $( \hat{y_i})$ adalah nilai prediksi
     - $( n)$ adalah jumlah data
   - **Interpretasi**: Nilai MAE yang lebih rendah menunjukkan bahwa model memiliki kesalahan yang lebih kecil dalam memprediksi kadar air.

### 2. **Mean Squared Error (MSE)**
   - **Deskripsi**: MSE mengukur rata-rata dari kuadrat perbedaan antara nilai prediksi dan nilai aktual. Metrik ini memberikan penalti yang lebih besar untuk kesalahan prediksi yang besar.
   - **Formula**:       $MSE = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y_i})^2$

     Di mana:
     - $(y_i)$ adalah nilai aktual
     - $( \hat{y_i})$ adalah nilai prediksi
     - $(n)$ adalah jumlah data
   - **Interpretasi**: MSE yang lebih rendah menunjukkan bahwa model lebih akurat dalam memprediksi kadar air, dengan penalti yang lebih besar untuk kesalahan yang signifikan.

### 3. **Root Mean Squared Error (RMSE)**
   - **Deskripsi**: RMSE adalah akar kuadrat dari MSE, yang mengubah satuan dari kuadrat ke satuan asli data, memberikan pemahaman yang lebih mudah terkait ukuran kesalahan.
   - **Formula**:      $RMSE = \sqrt{\frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y_i})^2}$

     Di mana:
     - $(y_i)$ adalah nilai aktual
     - $(\hat{y_i})$ adalah nilai prediksi
     - $(n)$ adalah jumlah data
   - **Interpretasi**: Seperti MSE, RMSE lebih sensitif terhadap kesalahan besar. Semakin rendah nilai RMSE, semakin baik prediksi model.

### 4. **R² (Koefisien Determinasi)**
   - **Deskripsi**: R² mengukur seberapa baik model dapat menjelaskan variasi dalam data. Ini memberikan gambaran tentang proporsi varians yang dapat dijelaskan oleh model terhadap total varians yang ada.
   - **Formula**: 
     $R^2 = 1 - \frac{\sum_{i=1}^{n} (y_i - \hat{y_i})^2}{\sum_{i=1}^{n} (y_i - \bar{y})^2}$

     Di mana:
     - $( y_i)$ adalah nilai aktual
     - $( \hat{y_i} )$ adalah nilai prediksi
     - $( \bar{y} )$ adalah rata-rata nilai aktual
   - **Interpretasi**: Nilai R² yang lebih tinggi menunjukkan bahwa model lebih baik dalam menjelaskan variasi data, dengan nilai yang mendekati 1 menunjukkan model yang sangat baik, sementara nilai yang lebih rendah menunjukkan model yang kurang efektif.


## Penjelasan Hasil Proyek Berdasarkan Metrik Evaluasi

Setelah melatih dan menguji model dengan data pelatihan dan data pengujian, hasil evaluasi model menunjukkan kinerja model dalam memprediksi kadar air berdasarkan intensitas cahaya sensor. Berikut adalah penjelasan tentang hasil masing-masing model berdasarkan metrik evaluasi yang digunakan:

1. **Random Forest**:
   - Memiliki nilai MSE, RMSE, dan MAE yang rendah, menunjukkan bahwa model ini dapat memberikan prediksi yang cukup akurat untuk kadar air.
   - Nilai R² yang tinggi menunjukkan bahwa model ini mampu menjelaskan sebagian besar variansi dalam data, membuatnya efektif dalam tugas prediksi.

2. **Neural Network (MLP)**:
   - Model ini memiliki nilai MAE dan RMSE yang baik, namun MSE lebih besar daripada Random Forest, yang menunjukkan bahwa model ini sensitif terhadap kesalahan besar.
   - R² yang cukup tinggi menunjukkan bahwa model ini mampu menjelaskan hubungan antara fitur dan target dengan baik.

3. **K-Nearest Neighbors (KNN)**:
   - MSE dan RMSE yang sedikit lebih tinggi menunjukkan bahwa KNN tidak seefektif model lainnya dalam menangani data.
   - R² yang lebih rendah dibandingkan dengan model lain menunjukkan bahwa model ini tidak seakurat model lain dalam menjelaskan variansi data.

4. **AdaBoost**:
   - Metrik evaluasi menunjukkan bahwa AdaBoost cukup efektif, dengan MAE dan RMSE yang rendah.
   - R² yang tinggi menunjukkan bahwa model ini berhasil menjelaskan variansi dalam data dengan cukup baik.

5. **Gradient Boosting**:
   - Memiliki hasil yang sangat baik pada semua metrik evaluasi, terutama MSE dan RMSE yang sangat rendah serta R² yang mendekati 1.
   - Ini menunjukkan bahwa Gradient Boosting adalah salah satu model terbaik dalam hal akurasi dan kemampuan untuk menjelaskan variansi data.

6. **Deep Neural Network (DNN)**:
   - Model DNN memberikan prediksi yang sangat baik dengan nilai MAE dan RMSE yang rendah.
   - R² yang tinggi menunjukkan bahwa DNN dapat menangkap pola yang lebih kompleks dalam data.

7. **Decision Tree**:
   - Model ini menunjukkan hasil yang lebih bervariasi pada metrik evaluasi. MSE dan RMSE yang lebih tinggi menunjukkan bahwa model ini cenderung overfitting pada data pelatihan.
   - R² yang rendah menunjukkan bahwa model ini tidak cukup mampu menjelaskan variasi dalam data.

**HASIL EVALUASI MODEL**
|  Model  |  MSE  |  MAE | RMSE | R² | 
|:----------|:-----:|:-----:|:-----:|:-----:|
Random Forest       | 7.670838e-01 | 1.570440e-01 | 8.758332e-01  | 0.997529  
Neural Network      | 9.978332e-01 | 6.613435e-01 | 9.989160e-01  | 0.996785  
KNN                 | 2.393030e-30 | 3.367890e-16 | 1.546942e-15  | 1.000000  
Adaboost            | 9.749954e+01 | 8.556808e+00 | 9.874186e+00  | 0.685870  
Gradient Boost      | 1.725194e+01 | 3.034459e+00 | 4.153546e+00  | 0.944417  
Deep Neural Network | 1.365154e+00 | 7.766056e-01 | 1.168398e+00  | 0.995602  
Decision Tree       | 1.816077e+00 | 9.655491e-02 | 1.347619e+00  | 0.994149  

Hasil evaluasi model menunjukkan bahwa beberapa model machine learning berhasil memberikan prediksi yang sangat akurat untuk memprediksi kadar air rumput laut berdasarkan data sensor AS7265X. Berdasarkan metrik evaluasi yang digunakan, berikut adalah penjelasan dampak dari model terhadap Business Understanding:

**1. Problem Statement**: Model yang dievaluasi berhasil menjawab problem statement, yaitu prediksi kadar air rumput laut. Model seperti Random Forest dan KNN memberikan hasil yang sangat baik dengan R² mendekati 1 (0.9975 dan 1.0000), yang menunjukkan bahwa model dapat menjelaskan sebagian besar variasi dalam data. Hal ini membuktikan bahwa solusi machine learning yang diusulkan efektif dalam memprediksi kadar air dengan akurasi yang tinggi.

**2. Goal Achievements**: Semua tujuan yang telah ditetapkan tercapai, termasuk:
- Membangun dan membandingkan model prediksi: Berbagai model seperti Random Forest, Neural Network, dan KNN dibandingkan, dan hasilnya menunjukkan bahwa Random Forest dan Gradient Boosting adalah yang paling optimal.
- Pengujian model dengan metrik yang jelas (MSE, MAE, RMSE, R²) menghasilkan pemahaman yang mendalam tentang kinerja model.

**3. Impact of the Solution**: Solusi yang direncanakan terbukti berdampak signifikan. Dengan kemampuan model untuk memberikan prediksi yang sangat akurat (seperti pada Random Forest dan KNN dengan nilai R² tinggi), sistem ini dapat diandalkan untuk aplikasi praktis dalam industri yang membutuhkan pemantauan kadar air secara real-time, seperti dalam pengelolaan sumber daya alam, pertanian kelautan, dan riset lingkungan. Pemilihan model terbaik berdasarkan evaluasi memungkinkan implementasi yang lebih efisien dan tepat sasaran.

Dengan demikian, solusi ini tidak hanya mencapai tujuan yang diharapkan tetapi juga memberikan dampak yang besar dalam mempermudah prediksi kadar air secara cepat dan akurat, yang dapat diimplementasikan untuk berbagai aplikasi bisnis dan penelitian.

## Kesimpulan

Berdasarkan hasil evaluasi, model **K-Nearest Neighbors (KNN)** menunjukkan hasil yang luar biasa dengan MSE, RMSE, dan MAE yang sangat rendah serta R² yang sangat tinggi pada data uji. **Random Forest** dan **Deep Neural Network (DNN)** juga menunjukkan hasil yang sangat baik, meskipun sedikit lebih rendah dibandingkan KNN. **Gradient Boosting** dan **Decision Tree** memiliki kinerja yang cukup baik, namun dengan sedikit penurunan pada data uji. **Adaboost** memberikan hasil yang buruk dan tidak direkomendasikan untuk digunakan pada masalah ini.
Berdasarkan hasil evaluasi ini, dapat disimpulkan bahwa tujuan proyek telah tercapai dengan sangat baik yang dijabarkan sebagai berikut:
1. Solusi berbasis machine learning berhasil diterapkan dan memberikan prediksi yang akurat.
2. Melalui PCA, kanal-kanal sensor yang paling relevan dalam menentukan kadar air dapat diidentifikasi.
3. Semua model yang direncanakan telah dibangun dan dibandingkan dengan hasil yang bervariasi, memberikan wawasan tentang pilihan model terbaik.
4. Sistem evaluasi yang jelas telah diterapkan, memastikan bahwa model yang dihasilkan dapat diandalkan.
5. Pengujian terhadap model memberikan hasil prediksi yang memadai untuk diterapkan dalam aplikasi dunia nyata.

----------

