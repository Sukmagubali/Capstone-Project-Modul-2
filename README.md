# Latar Belakang
Perusahaan taksi di New York City menghadapi sejumlah tantangan, termasuk peningkatan kepuasan pelanggan, optimasi operasional, dan pemahaman mendalam mengenai dinamika pembayaran penumpang. Dalam upaya mengatasi tantangan tersebut, perusahaan berencana melakukan analisis mendalam terhadap data set New York City TLC Trip Record. Fokus analisis melibatkan perbandingan kepuasan pelanggan antara dua vendor utama, eksplorasi pola perjalanan taksi, dan evaluasi hubungan antara jumlah total pembayaran dan tip. Dalam rangka mencapai tujuan tersebut, stakeholders utama seperti perusahaan taksi, pelanggan, pengemudi taksi, dan pemerintah Kota New York akan terlibat aktif. Langkah-langkah ini diambil dengan harapan meningkatkan kualitas layanan, efisiensi operasional, dan pemahaman mendalam terkait interaksi pembayaran penumpang.
# Rumusan Masalah
Berdasarkan latar belakang diatas, stekholder diatas ingin mengetahui beberapa informasi berikut :

1. Bagaimana perbandingan kepuasan pelanggan antara Vendor Creative Mobile Technologies, LLC (VendorID 1) dan Vendor VeriFone Inc. (VendorID 2), berdasarkan parameter total jarak perjalanan,total jumlah pendapatan, dan total jumlah tip yang penumpang?

2. Bagaimana pola perjalanan taksi mencerminkan tren permintaan penumpang di Bulan Januari 2023?

3. Apakah terdapat hubungan yang signifikan antara jumlah bayar (total_amount) dan jumlah tip (tip_amount) yang diberikan oleh penumpang kepada pengemudi taksi?
# Tujuan Analisis
Berdasarkan latar belakang dan rumusan masalah diatas, berikut adalah tujuan analisis yang tepat:

1. **Perbandingan Kepuasan Pelanggan antara Vendor:**
   - Mengidentifikasi perbedaan kepuasan pelanggan antara dua vendor utama (Creative Mobile Technologies, LLC dan VeriFone Inc.) berdasarkan parameter:
     - Total jarak perjalanan.
     - Total jumlah pendapatan.
     - Total jumlah tip yang diterima oleh pengemudi.

2. **Pemahaman Pola Perjalanan Taksi untuk Tren Permintaan Penumpang di Januari 2023:**
   - Menganalisis pola perjalanan taksi untuk memahami tren permintaan penumpang selama bulan Januari 2023. Fokus pada:
     - Distribusi waktu perjalanan.
     - Tren permintaan penumpang berdasarkan jumlah penumpang

3. **Evaluasi Hubungan antara Pembayaran Total dan Tips:**
   - Mengevaluasi apakah terdapat hubungan yang signifikan antara jumlah total pembayaran (total_amount) yang diterima oleh perusahaan taksi dan jumlah tip (tip_amount) yang diberikan oleh penumpang kepada pengemudi.
# **Kesimpulan**
#### 1. Perbandingan Kepuasan Pelanggan antara VendorID 1 dan VendorID 2

1. **Total Jarak Perjalanan:**
   - VendorID 2 memiliki total jarak perjalanan lebih tinggi dibandingkan dengan VendorID 1.
   - Hari paling aktif untuk keduanya adalah Selasa, sedangkan Sabtu memiliki jumlah perjalanan terendah untuk VendorID1 dan Minggu di VendorID 2.

2. **Total Pendapatan:**
   - VendorID 2 memiliki total pendapatan lebih tinggi dibandingkan dengan VendorID 1.
   - Hari dengan pendapatan tertinggi untuk keduanya adalah Selasa, sedangkan Sabtu memiliki jumlah pendapatan terendah untuk VendorID1 dan Minggu di VendorID 2.

3. **Total Tip:**
   - VendorID 2 mendapatkan total tip lebih tinggi dibandingkan dengan VendorID 1.
   - Hari dengan tip tertinggi untuk keduanya adalah Selasa, sedangkan  memiliki jumlah tip terendah untuk VendorID1 dan Minggu di VendorID 2.

#### 2. Pola Perjalanan Taksi dan Tren Permintaan Penumpang di Januari 2023

1. **Pola Perjalanan Berdasarkan Jumlah Penumpang:**
   - Puncak aktivitas terjadi pada rentang waktu 15.00 - 18.00, dengan Selasa memiliki jumlah penumpang tertinggi.
   - Aktivitas penumpang cenderung lebih rendah pada akhir pekan, terutama Sabtu dan Minggu.

2. **Tren Permintaan Penumpang per Jam:**
   - Puncak permintaan terjadi pada jam 17.00-18.00, mencapai 5530 penumpang.
   - Jam-jam sibuk lainnya adalah 07.00-08.00, 08.00-09.00, dan 15.00-16.00.
   - Permintaan menurun pada dini hari dan meningkat pada pagi hingga sore hari.
   - Pentingnya perencanaan dan penugasan armada pada jam puncak, terutama pada pukul 17.00-18.00.
   
3. **Tren Permintaan Penumpang per Jam di Hari Kerja dan Akhir Pekan:**
   **Weekdays:**
   - Puncak permintaan pada jam 17.00-18.00 dengan 4322 penumpang.
   - Jam-jam puncak lainnya (08.00-09.00, 09.00-10.00, 16.00-17.00) juga tinggi.
   - Permintaan pagi (06.00-09.00) relatif tinggi.

   **Weekend:**
   - Puncak permintaan pada jam 15.00-16.00 dengan 1299 penumpang.
   - Jam-jam sibuk lainnya (10.00-11.00, 11.00-12.00, 14.00-15.00) juga tinggi.
   - Peningkatan signifikan pada pagi hari (06.00-09.00) dibanding weekdays. 

4. **Tren Permintaan Penumpang per Hari:**
   - Perbedaan pola antara weekdays dan weekend menunjukkan potensi waktu sibuk yang berbeda pada setiap periode.
   **Tren Permintaan Penumpang per Hari:**
   1. **Tren Harian:**
   - Jumlah penumpang tertinggi terjadi pada hari Selasa dengan 11484 penumpang.
   - Pada hari Sabtu dan Minggu, jumlah penumpang cenderung lebih rendah dibandingkan dengan hari-hari kerja.

   2. **Perbedaan Antara Hari Kerja dan Akhir Pekan:**
   - Jumlah penumpang pada hari Senin hingga Jumat (hari kerja) cenderung lebih tinggi dibandingkan dengan Sabtu dan Minggu (akhir pekan).

   3. **Tren Mingguan:**
   - Grafik menunjukkan tren mingguan yang konsisten, dengan fluktuasi tertentu di sepanjang minggu. 

#### 3. Hubungan antara Jumlah Bayar(total_amount) dan Jumlah Tip (total_tip)
   - Rata-rata total bayar per perjalanan adalah sekitar 23.88 USD, dengan variasi yang signifikan, memiliki standar deviasi sekitar 14.36 USD.
   - Mayoritas perjalanan memiliki total bayar di kisaran 15.00 USD hingga 28.02 USD.
   - Rata-rata jumlah tip yang diberikan adalah sekitar 2.43 USD, dengan variasi yang cukup besar, ditunjukkan oleh standar deviasi sekitar 2.97 USD.
   - Jumlah tip berkisar dari 0.00 USD hingga 80.88 USD.
   - Scatter plot antara total bayar dan tip menunjukkan tren positif yang kuat, mengindikasikan bahwa semakin besar total bayar, semakin besar juga tip yang diberikan.
   - Korelasi sebesar 0.56 menegaskan adanya hubungan positif yang kuat antara total bayar dan tip.
   - P-value yang sangat rendah (0.00) memberikan bukti statistik yang kuat untuk menolak hipotesis nol, sehingga kita dapat menyimpulkan bahwa korelasi antara total bayar dan tip adalah signifikan secara statistik.
   - Kesimpulan akhir: Semakin besar total bayar, semakin besar juga tip yang diberikan oleh penumpang kepada pengemudi taksi.
# **Rekomendasi**
### Rekomendasi untuk Meningkatkan Kepuasan Pelanggan dan Optimalisasi Layanan Taksi:

#### VendorID 1:

1. **Peningkatan Pelayanan pada Jam Puncak:**
   - *Saran:* Tingkatkan pelayanan pada jam-jam puncak, terutama di hari Selasa.
   - *Langkah Aksi:* Sesuaikan penempatan armada dan jadwal pengemudi untuk memaksimalkan ketersediaan selama jam-jam dengan jumlah perjalanan dan pendapatan tertinggi.

2. **Program Insentif pada Jam-Jam Rendah:**
   - *Saran:* Fokus pada jam-jam dengan potensi pertumbuhan, terapkan program insentif atau promosi.
   - *Langkah Aksi:* Implementasikan insentif khusus untuk merangsang penggunaan taksi VendorID 1 pada jam-jam tertentu.

3. **Analisis Kualitas Layanan pada Hari Sabtu:**
   - *Saran:* Evaluasi kualitas layanan pada hari Sabtu yang memiliki performa rendah.
   - *Langkah Aksi:* Lakukan survei kepuasan pelanggan khusus pada hari Sabtu untuk mengidentifikasi masalah dan tingkatkan layanan.

#### VendorID 2:

1. **Optimasi Ketersediaan Armada pada Hari Selasa:**
   - *Saran:* Pertahankan kualitas pelayanan optimal meskipun ketersediaan tinggi pada hari Selasa.
   - *Langkah Aksi:* Perbaiki sistem penjadwalan untuk menjaga kualitas layanan. Evaluasi performa pengemudi dan tambahan layanan jika diperlukan.

2. **Maksimalkan Pendapatan pada Jam-Jam Puncak:**
   - *Saran:* Fokus pada peningkatan pendapatan dan tip, terutama pada pukul 17.00 di hari Selasa.
   - *Langkah Aksi:* Rancang program promosi atau insentif untuk menarik lebih banyak penumpang selama jam-jam puncak.

3. **Pengoptimalan Jam Kerja Pengemudi:**
   - *Saran:* Maksimalkan potensi pendapatan dengan mengelola jam kerja pengemudi berdasarkan pola pendapatan harian dan jam-jam puncak.
   - *Langkah Aksi:* Sesuaikan jadwal kerja pengemudi dengan pola pendapatan dan pastikan insentif tambahan untuk pengemudi yang bekerja pada jam-jam puncak.

### Stakeholder Berdasarkan Pola Perjalanan dan Permintaan Penumpang:

1. **Optimasi Armada dan Pengemudi:**
   - *Saran:* Tingkatkan jumlah armada dan pengemudi selama jam-jam puncak pada rentang waktu 15.00 - 18.00.
   - *Langkah Aksi:* Pastikan ketersediaan maksimal armada dan pengemudi untuk memenuhi tingginya permintaan penumpang.

2. **Promosi dan Insentif pada Jam Sibuk:**
   - *Saran:* Terapkan program promosi atau insentif pada jam-jam potensial, seperti pada rentang waktu 08.00 - 10.00.
   - *Langkah Aksi:* Rancang insentif atau diskon khusus untuk meningkatkan penggunaan taksi selama jam-jam sibuk.

3. **Penyesuaian Tarif dan Diskon pada Jam Tertentu:**
   - *Saran:* Implementasikan tarif dinamis atau diskon pada jam-jam lengang untuk memicu permintaan.
   - *Langkah Aksi:* Evaluasi dan terapkan kebijakan tarif yang lebih fleksibel atau diskon pada rentang waktu yang kurang diminati.

4. **Pelatihan Pengemudi pada Pola Tren Harian:**
   - *Saran:* Berikan pelatihan kepada pengemudi tentang pola tren harian, terutama pada jam-jam sibuk.
   - *Langkah Aksi:* Lakukan pelatihan mengenai strategi optimal dalam menghadapi tingginya permintaan pada jam-jam tertentu.

5. **Promo Menarik pada Hari-Hari yang Kurang Aktif:**
   - *Saran:* Rancang promo menarik untuk meningkatkan penggunaan taksi pada hari Sabtu dan Minggu.
   - *Langkah Aksi:* Implementasikan promosi khusus untuk merangsang penggunaan taksi pada akhir pekan, seperti diskon akhir pekan.

### Stakeholder Berdasarkan Analisis Hubungan Jumlah Total Bayar dan Tip:

1. **Promosi Kesadaran Tip:**
   - *Saran:* Promosikan kebijakan memberikan tip secara positif kepada penumpang.
   - *Langkah Aksi:* Gunakan pesan promosi di kendaraan atau aplikasi untuk meningkatkan kesadaran penumpang tentang pentingnya memberikan tip kepada pengemudi yang memberikan pelayanan baik.

2. **Edukasi Pengemudi tentang Kualitas Pelayanan:**
   - *Saran:* Berikan pelatihan kepada pengemudi tentang pentingnya pelayanan yang baik untuk mendorong penumpang memberikan tip.
   - *Langkah Aksi:* Adakan sesi pelatihan reguler yang fokus pada aspek-aspek kualitas pelayanan
