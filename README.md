# 🛍️ Mall Customers Segmentation

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk melakukan segmentasi pelanggan di sebuah mall menggunakan algoritma **K-Means Clustering**. Dengan memahami kelompok pelanggan yang berbeda, pihak manajemen mall dapat merancang strategi pemasaran yang lebih personal dan efektif.

## 📊 Dataset
Dataset yang digunakan adalah `Mall_Customers.csv` yang berisi informasi dasar pelanggan:
- **CustomerID**: ID unik pelanggan.
- **Gender**: Jenis kelamin pelanggan.
- **Age**: Usia pelanggan.
- **Annual Income**: Pendapatan tahunan pelanggan.
- **Spending Score**: Skor yang diberikan mall berdasarkan perilaku belanja pelanggan.

## 🛠️ Metodologi & Tahapan
1. **Data Preprocessing**: Melakukan pengecekan nilai kosong (null values) dan mengubah nama kolom agar lebih mudah diakses.
2. **Exploratory Data Analysis (EDA)**: Visualisasi distribusi data untuk memahami karakteristik pelanggan.
3. **Elbow Method**: Menentukan jumlah cluster (k) yang optimal dengan melihat penurunan *Within-Cluster Sum of Square* (WCSS).
4. **Clustering**: Mengimplementasikan K-Means dengan k=4 untuk membagi pelanggan ke dalam beberapa kelompok.

## 📈 Hasil Segmentasi
Berdasarkan hasil analisis, pelanggan terbagi menjadi 4 kelompok utama:
- **Premium Loyal Customers**: Pendapatan tinggi & Pengeluaran tinggi.
- **Wealthy but Thrifty**: Pendapatan tinggi & Pengeluaran rendah.
- **Young Impulsive Buyers**: Pendapatan rendah & Pengeluaran tinggi.
- **Low Value Customers**: Pendapatan rendah & Pengeluaran rendah.

## 🎯 Rekomendasi Bisnis
- Memberikan program loyalitas eksklusif untuk kelompok **Premium Loyal Customers**.
- Menargetkan promosi gaya hidup dan diskon besar untuk kelompok **Young Impulsive Buyers**.
- Mengaktifkan kembali kelompok **Wealthy but Thrifty** melalui pemasaran yang dipersonalisasi.

## 💻 Teknologi yang Digunakan
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-Learn (K-Means)
