# Automatidata

**Ringkasan Data Awal Proyek TLC Kota New York**

Proyek ini melakukan inspeksi awal terhadap data Komisi Taksi dan Limousine NYC untuk memberi informasi tentang deskripsi variabel data utama, dan memastikan informasi yang diberikan sesuai untuk menghasilkan wawasan yang jelas dan bermakna.

* Dataset dieksplorasi untuk menemukan nilai-nilai yang tidak biasa.
* Mempertimbangkan variabel mana yang paling berguna untuk membangun model prediktif (dalam hal ini: total_amount dan trip_distance).
* Mempertimbangkan potensi interaksi antara dua variabel yang dipilih.
* Menganalisis komponen mana dari data yang diberikan yang akan memberikan wawasan yang relevan.
* Membangun landasan untuk analisis data eksplorasi, visualisasi, dan model di masa mendatang.

**Next Step**
* Lakukan analisis data eksplorasi secara menyeluruh.
* Lakukan langkah-langkah pembersihan data dan analisis data untuk memahami variabel yang tidak biasa (misalnya, outlier).
* Gunakan statistik deskriptif untuk mempelajari lebih lanjut tentang data tersebut.
* Buat dan jalankan model regresi.

**Analisis Data Eksploratif dari Data TLC Kota New York**

Komisi Taksi & Limousine NYC telah menjalin kontrak dengan Automatidata untuk membangun model regresi yang memprediksi tarif perjalanan taksi. Pada bagian proyek ini, data perlu dianalisis, dieksplorasi, dibersihkan, dan distrukturkan sebelum pemodelan apa pun dilakukan.

**Next Step**
* Identifikasi setiap titik data yang tidak biasa yang dapat menimbulkan masalah untuk analisis selanjutnya dalam memprediksi tarif perjalanan.
  Sebagai contoh, lokasi yang memiliki durasi lebih lama.
* Tentukan variabel-variabel yang memiliki dampak terbesar pada tarif perjalanan.
* Saring untuk mempertimbangkan variabel yang paling relevan untuk menjalankan regresi, analisis statistik, dan penyetelan parameter.


**Tinjauan Statistik dan Pengujian A/B untuk Proyek TLC Kota New York**

**Tujuan** proyek ini adalah untuk memprediksi tarif taksi sebelum setiap perjalanan. Pada tahap ini, fokus proyek ini adalah untuk menemukan cara menghasilkan lebih banyak pendapatan bagi pengemudi taksi di New York City. Bagian proyek ini meneliti hubungan antara jumlah total tarif dan jenis pembayaran.


**Problem** Pengemudi taksi menerima jumlah tip yang bervariasi. Sambil meneliti hubungan antara jumlah total ongkos dan jenis pembayaran, proyek ini bertujuan untuk mengetahui apakah pelanggan yang membayar dengan kartu kredit cenderung membayar jumlah total ongkos yang lebih besar daripada pelanggan yang membayar tunai.

**Solution**
Tim Automatidata menjalankan uji A/B untuk menganalisis hubungan antara pembayaran kartu kredit dan total biaya perjalanan. Wawasan bisnis utamanya adalah bahwa mendorong pelanggan untuk membayar dengan kartu kredit kemungkinan akan menghasilkan lebih banyak pendapatan bagi pengemudi taksi.

**Langkah-langkah yang dilakukan dalam uji A/B**
* Data sampel yang dikumpulkan dari sebuah eksperimen di mana pelanggan dipilih secara acak dan dibagi menjadi dua kelompok:

  a. Pelanggan yang diharuskan membayar dengan kartu kredit.
  
  b. Pelanggan yang diharuskan membayar dengan uang tunai. Hal ini memungkinkan kami untuk menarik kesimpulan kausal tentang bagaimana metode pembayaran memengaruhi jumlah tarif.
* Menghitung statistik deskriptif untuk lebih memahami rata-rata total biaya perjalanan untuk setiap metode pembayaran yang tersedia bagi pelanggan.
* Melakukan uji t dua sampel untuk menentukan apakah terdapat perbedaan yang signifikan secara statistik dalam rata-rata total tarif antara pelanggan yang menggunakan kartu kredit dan pelanggan yang menggunakan uang tunai.

**Next Step**

Tim data Automatidata merekomendasikan agar TLC Kota New York mendorong pelanggan untuk membayar dengan kartu kredit, dan membuat strategi untuk mempromosikan pembayaran kartu kredit. Misalnya, TLC Kota New York dapat memasang tanda yang bertuliskan “Pembayaran kartu kredit lebih disukai” di dalam taksi mereka, dan menerapkan protokol yang mengharuskan pengemudi taksi untuk secara verbal memberi tahu pelanggan bahwa pembayaran kartu kredit lebih disukai

**Asumsi Regresi Setelah Pemodelan**

**Problem**
Komisi Taksi & Limousine Kota New York mengontrak Automatidata untuk memprediksi tarif taksi. Pada bagian proyek ini, tim data Automatidata membuat hasil akhir sesuai permintaan awal dari klien mereka: sebuah model regresi.

**Response**
Tim data Automatidata memilih untuk membuat model regresi linier berganda (MLR) berdasarkan jenis dan distribusi data yang diberikan. Model MLR menunjukkan keberhasilan dalam memperkirakan tarif taksi sebelum perjalanan dimulai.

Performa model tinggi baik pada set pelatihan maupun set pengujian, menunjukkan bahwa model tidak terlalu bias dan tidak mengalami overfitting. Model berkinerja lebih baik pada data pengujian.







