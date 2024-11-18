# **Demand Forecasting Report: PacRide**  
## **Sales Analysis and Strategic Recommendations**  

### **Introduction**  
PacRide adalah perusahaan yang bergerak di industri penjualan sepeda dan aksesorisnya. Dalam upaya meningkatkan performa penjualan, khususnya untuk produk-produk tertentu dengan tingkat penjualan rendah, perusahaan berfokus pada analisis mendalam untuk mengidentifikasi peluang dan tantangan pasar. Laporan ini bertujuan memberikan wawasan berbasis data tentang pola permintaan, wilayah strategis untuk distribusi, dan rekomendasi operasional guna mendorong pertumbuhan penjualan secara keseluruhan.  

### **Objectives**  
1. **Wilayah Prioritas Penjualan**  
   Mengidentifikasi wilayah atau negara dengan performa penjualan terbaik untuk subkategori produk tertentu. Informasi ini akan menjadi dasar untuk menetapkan fokus pemasaran, distribusi, dan alokasi sumber daya secara optimal.  

2. **Strategi Berbasis Data**  
   Memberikan rekomendasi strategis yang dapat mendukung pertumbuhan penjualan dan efisiensi operasional melalui:  
   - **Optimalisasi Stok**: Memastikan produk tersedia di wilayah dengan permintaan tinggi untuk meminimalkan kekurangan stok.  
   - **Kampanye Promosi yang Efektif**: Menargetkan kampanye pemasaran pada wilayah dengan potensi pasar tinggi, terutama untuk produk dengan penjualan rendah.  
   - **Strategi Penetapan Harga**: Menyesuaikan harga berdasarkan pola permintaan di berbagai wilayah untuk meningkatkan daya saing.  

3. **Demand Forecasting untuk Efisiensi Operasional**  
   Mengembangkan model Machine Learning untuk melakukan peramalan permintaan (demand forecasting). Fokus diberikan pada wilayah dan subkategori produk dengan tingkat permintaan tinggi terhadap produk yang saat ini memiliki penjualan yang belum optimal. Dengan ini, PacRide dapat merancang strategi produksi dan distribusi yang lebih efisien.  

### **Goals**  
1. **Analisis Penjualan Wilayah**  
   Mengidentifikasi wilayah dengan tingkat penjualan tertinggi dan tren pertumbuhan untuk masing-masing subkategori produk.  
   - Wilayah atau negara dengan kontribusi penjualan terbesar.  
   - Perbandingan performa penjualan berdasarkan parameter geografis seperti sub-region atau kota.  

2. **Peningkatan Kinerja Subkategori Produk**  
   Melakukan analisis mendalam pada subkategori produk yang menjadi prioritas, termasuk identifikasi pola penjualan bulanan, tren musiman, serta faktor yang memengaruhi kinerja produk.  

### **Methodology**  

#### **Data Preparation**  
- **Data Penjualan**:  
  Menggunakan data historis penjualan yang mencakup tanggal order, lokasi penjualan, jumlah unit terjual, dan kategori produk.  

#### **Analisis dan Modeling**  
1. **Exploratory Data Analysis (EDA)**:  
   - Mengidentifikasi pola distribusi penjualan per wilayah dan per subkategori produk.  
   - Visualisasi tren musiman dan fluktuasi penjualan berdasarkan waktu.  

2. **Demand Forecasting**:    
   - **Machine Learning**: XGBoost atau Prophet untuk pola permintaan yang kompleks dan tidak linier.  

### **Kesimpulan**  
1. **Subkategori yang Tidak Terjual**:  
   Berdasarkan data, terdapat subkategori produk seperti 'Mountain Frames', 'Road Frames', 'Touring Frames', 'Wheels', 'Jerseys', 'Shorts', 'Handlebars', 'Forks', 'Saddles', 'Bottom Brackets', 'Pumps', 'Bottles and Cages', 'Tires and Tubes' yang belum terjual sama sekali.  

2. **Region dengan Demand Tertinggi**:  
   - **Southwest, United States** adalah wilayah dengan demand tertinggi, khususnya untuk subkategori seperti *Road Frames* dan *Mountain Frames*.  
   - **Canada** memiliki performa penjualan tinggi pada subkategori seperti *Jerseys* dan *Shorts*.  

3. **Indikator Demand**:  
   Wilayah dengan performa tinggi pada produk terjual dapat dijadikan fokus untuk mengidentifikasi peluang penjualan pada subkategori yang belum terjual.  

---

### **Rekomendasi**  
1. **Fokus Pemasaran pada Wilayah dengan Demand Tinggi**:  
   - Lakukan kampanye promosi subkategori `Pedals`, `Gloves`, dan `Helmets` di **Southwest, United States** dan **Canada**.  
   - Pastikan stok tersedia di wilayah tersebut untuk mendukung potensi penjualan.  

2. **Penelitian Pasar Tambahan**:  
   - Lakukan survei pelanggan di wilayah dengan demand tinggi untuk memahami mengapa produk seperti `Pedals`, `Gloves`, dan `Helmets` belum diminati.  
   - Analisis kompetitor di wilayah tersebut untuk menentukan strategi harga dan fitur produk.  

3. **Uji Coba Promosi**:  
   - Berikan diskon atau penawaran bundling untuk subkategori yang belum terjual guna meningkatkan minat pelanggan.  
   - Gunakan saluran pemasaran lokal untuk meningkatkan kesadaran produk di wilayah yang ditargetkan.  

4. **Evaluasi dan Optimasi Stok**:  
   - Gunakan demand forecasting untuk mengelola stok secara efisien, terutama untuk wilayah dengan permintaan tinggi.  

---

Pendekatan ini akan membantu PacRide meningkatkan peluang penjualan pada subkategori produk yang saat ini belum optimal sambil memanfaatkan wilayah dengan demand tertinggi sebagai prioritas distribusi.
