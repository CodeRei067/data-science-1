# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview
Project ini bertujuan untuk menganalisis faktor-faktor yang mempengaruhi tingkat keselamatan penumpang pada kapal Titanic. Analisis dilakukan menggunakan Exploratory Data Analysis (EDA) untuk menemukan pola dari data penumpang.

---

## 📊 Dataset Information
Dataset yang digunakan berisi informasi penumpang Titanic seperti:
- Gender (Sex)
- Umur (Age)
- Kelas tiket (Pclass)
- Pelabuhan keberangkatan (Embarked)
- Status keselamatan (Survived)

---

## 🧹 Data Cleaning Summary
Sebelum analisis dilakukan, data telah dibersihkan dengan langkah berikut:
- Menghapus kolom yang tidak relevan (Cabin)
- Mengisi missing value pada Age menggunakan median
- Mengisi missing value pada Embarked menggunakan nilai yang paling sering muncul (mode)

Hasil akhir dataset:
- Tidak ada missing value
- Total data: 891 penumpang

---

## 📈 Key Findings (Hasil Analisis)

### 1. Survival Overview
- Sekitar 342 penumpang selamat
- Sekitar 549 penumpang tidak selamat
- Tingkat keselamatan secara keseluruhan sekitar 38%

---

### 2. Gender Influence
- Perempuan memiliki tingkat keselamatan sekitar *74%*
- Laki-laki memiliki tingkat keselamatan sekitar *19%*

👉 Kesimpulan: Gender memiliki pengaruh besar terhadap peluang keselamatan.

---

### 3. Passenger Class (Pclass)
- Penumpang kelas 1 memiliki tingkat keselamatan paling tinggi
- Penumpang kelas 3 memiliki tingkat keselamatan paling rendah

👉 Kesimpulan: Status sosial-ekonomi mempengaruhi peluang bertahan hidup.

---

### 4. Age Distribution
- Kelompok usia dewasa (sekitar 20–40 tahun) memiliki jumlah korban paling banyak
- Anak-anak memiliki peluang selamat yang lebih tinggi dibanding sebagian dewasa

---

## 🧠 Conclusion
Dari hasil analisis, dapat disimpulkan bahwa faktor utama yang mempengaruhi keselamatan penumpang Titanic adalah:
- Gender (perempuan lebih diprioritaskan)
- Kelas sosial (kelas 1 lebih diutamakan)
- Usia (anak-anak lebih diprioritaskan)

Data ini menunjukkan adanya pengaruh struktur sosial dalam proses evakuasi.

---

## 🚀 Next Step
Tahap selanjutnya adalah membangun model Machine Learning untuk memprediksi kemungkinan keselamatan penumpang menggunakan algoritma seperti Logistic Regression atau Random Forest.