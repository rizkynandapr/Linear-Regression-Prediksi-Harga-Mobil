## 📈 Linear Regression — Prediksi Harga Mobil

Proyek ini merupakan implementasi algoritma Linear Regression untuk memprediksi harga mobil berdasarkan variabel horsepower. Model dibangun menggunakan scikit-learn dengan preprocessing, training, evaluasi, dan visualisasi.

---

## 📂 Struktur File

| File                                             | Deskripsi                                                                                |
| ------------------------------------------------ | ---------------------------------------------------------------------------------------- |
| `Regresi_Rizky_Nanda_Praditia_20210140057.ipynb` | Notebook utama berisi preprocessing, training, evaluasi, dan visualisasi regresi linear. |

---

## ⚙️ Alur Model

| Tahap                 | Deskripsi                                                           |
| --------------------- | ------------------------------------------------------------------- |
| **Data Loading**      | Membaca dataset `CarPrice_Assignment.csv`.                          |
| **Visualisasi Awal**  | Scatterplot hubungan antara `horsepower` dan `price`.               |
| **Training Model**    | Menggunakan **LinearRegression** dari scikit-learn.                 |
| **Prediksi**          | Mengestimasi harga berdasarkan input horsepower.                    |
| **Evaluasi**          | Menghitung **Mean Squared Error (MSE)** untuk mengukur error model. |
| **Visualisasi Hasil** | Menampilkan garis regresi pada scatterplot data aktual.             |

---

## ✨ Fitur Utama

📊 Implementasi regresi linear sederhana.

🔍 Evaluasi dengan MSE.

🎨 Visualisasi data dan garis regresi.

⚡ Notebook interaktif, mudah dimodifikasi untuk eksperimen variabel lain.

---

## 🚀 Cara Menjalankan

Clone repo:

git clone https://github.com/rizkynandapr/LinearRegression-CarPrice.git
cd LinearRegression-CarPrice

Install dependencies:

pip install -r requirements.txt

Jalankan notebook:

jupyter notebook Regresi_Rizky_Nanda_Praditia_20210140057.ipynb

---

## 🛠️ Teknologi yang Digunakan

Python 3.x

scikit-learn

NumPy, Pandas

Matplotlib

## 📊 Hasil

✅ Model mampu memprediksi harga mobil berdasarkan horsepower.

📉 Error dievaluasi menggunakan Mean Squared Error (MSE).

📈 Visualisasi menunjukkan garis regresi linear terhadap data aktual.
