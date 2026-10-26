**PENERAPAN MACHINE LEARNING UNTUK KLASIFIKASI KEGAGALAN MESIN FRAIS BERDASARKAN KONDISI OPERASIONAL**


**1. Deskripsi Proyek**

Proyek ini menerapkan Machine Learning untuk mengklasifikasikan kegagalan mesin (Machine Failure) berdasarkan data historis operasional. Penelitian ini membandingkan dua algoritma, yaitu Logistic Regression sebagai model baseline dan Random Forest sebagai model ensemble.
Tujuan proyek ini adalah mengetahui kemampuan kedua algoritma dalam membedakan kondisi mesin normal dan kondisi mesin yang mengalami kegagalan. Hasil klasifikasi diharapkan dapat mendukung analisis kondisi mesin dalam penerapan Predictive Maintenance di sektor manufaktur.

 **Anggota Kelompok :** 
    
    Mawar Putri Rabia (F1G125062)
    
    Agy Prawira Hutama S. (F1G125023)
    
    Siti Munawara (F1G125018)  

**2. Latar Belakang**

Mesin merupakan komponen penting dalam proses produksi industri manufaktur. Kegagalan mesin yang terjadi secara mendadak dapat mengganggu proses produksi, meningkatkan biaya perbaikan, dan menurunkan efisiensi operasional.
Data historis operasional mesin dapat digunakan untuk mempelajari pola kegagalan. Dengan memanfaatkan Machine Learning, data tersebut dapat diolah menjadi model klasifikasi yang membantu mengidentifikasi kemungkinan kegagalan mesin.
Proyek ini menggunakan Logistic Regression dan Random Forest untuk membandingkan performa model dalam mendeteksi kegagalan mesin berdasarkan parameter operasionalnya.

**3. Rumusan Masalah**

1. Apakah data historis operasional mampu digunakan untuk mengklasifikasikan machine failure?
2. Bagaimana perbandingan performa analitik antara Logistic Regression sebagai baseline dan Random Forest sebagai ensemble?

**4. Tujuan Riset**

1. Menerapkan Machine Learning untuk klasifikasi biner machine failure secara akurat.
2. Melakukan perbandingan objektif antara performa Logistic Regression dan Random Forest dalam klasifikasi kegagalan mesin.

**5. Dataset**

Dataset yang digunakan adalah AI4I 2020 Predictive Maintenance Dataset dari UCI Machine Learning Repository.
Dataset ini terdiri atas 10.000 observasi dan 14 kolom data yang memuat informasi mengenai jenis mesin, kondisi operasional, dan indikator kegagalan mesin.
  
  Fitur Dataset :
  
  - Type
  
  - Air Temperature
  
  - Process Temperature
  
  - Rotational Speed
  
  - Torque
  
  - Tool Wear

Machine Failure (target klasifikasi)

Target klasifikasi:
0 = Normal
1 = Failure

**6. Preprocessing Data**

• Pemeriksaan Data

• Penghapusan Identifier

• Encoding 

• Pembagian Data 

• Standardisasi 

**7. Algoritma Machine Learning**

• Logistic Regression

Logistic Regression digunakan sebagai model baseline untuk mengklasifikasikan kegagalan mesin berdasarkan hubungan antara fitur operasional dan target klasifikasi. Algoritma ini efisien, tetapi memiliki keterbatasan dalam menangkap hubungan yang kompleks.

• Random Forest

Random Forest merupakan algoritma ensemble yang menggabungkan banyak pohon keputusan untuk menghasilkan prediksi. Algoritma ini mampu mempelajari pola yang lebih kompleks dan hubungan nonlinier antarfitur operasional mesin.

**8. Hasil Perbandingan Model**



| model | Accuracy | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- | :--- |
| Logistic Regression | 0.97 | 0.64 | 0.10 | 0.18 |
| Random Forest | 0.98 | 0.88 | 0.53 | 0.66 |



**9. Hubungan dengan SDG 9 Target 9.5**

Proyek ini berkaitan dengan Sustainable Development Goal 9 (SDG 9): Industry, Innovation and Infrastructure, khususnya Target 9.5 yang menekankan penguatan penelitian ilmiah, kemampuan teknologi, dan inovasi industri.

Penerapan Machine Learning untuk klasifikasi kegagalan mesin merupakan bentuk pemanfaatan teknologi analitik untuk mendukung sektor manufaktur. Dengan menganalisis data historis, model dapat membantu mengidentifikasi pola kegagalan dan mendukung pengambilan keputusan terkait pemeliharaan mesin.

**10. Teknologi yang Digunakan**

- Python

- Pandas

- NumPy

- Scikit-learn

- Jupyter Notebook / Google Colab

- GitHub

**11. Struktur Repository**

klasifikasi-kegagalan-mesin/

│

├── Klasifikasi_Kegagalan_Mesin_Machine_Learning.ipynb

├── ai4i2020 (1).csv

├── app.py

└── README.md

Keterangan:

**Klasifikasi_Kegagalan_Mesin_Machine_Learning.ipynb :** Notebook analisis data, preprocessing, pelatihan, dan evaluasi model.

**ai4i2020 (1).csv :** Dataset operasional mesin.

**app.py :** Implementasi aplikasi prediksi.

**README.md :** Dokumentasi proyek.

**12. Kesimpulan**

Proyek ini menerapkan Machine Learning untuk mengklasifikasikan kegagalan mesin menggunakan Logistic Regression dan Random Forest. Berdasarkan hasil evaluasi, Random Forest menunjukkan performa lebih baik dengan Accuracy sebesar 98% dan F1-Score sebesar 66%.
Meskipun demikian, model masih perlu dikembangkan agar lebih mampu mendeteksi kegagalan mesin. Proyek ini diharapkan dapat menjadi dasar pengembangan sistem Predictive Maintenance untuk mendukung efisiensi operasional industri.
