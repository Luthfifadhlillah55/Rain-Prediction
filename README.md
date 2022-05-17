[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=7387052&assignment_repo_type=AssignmentRepo)
# Graded Challenge 2

_Graded Challenge ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Data Science Fulltime Program khususnya pada konsep Classification terutama Logistic Regression dan SVM._

---

## Dataset Description

Unduh dataset yang akan digunakan [disini](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package).

## Assignment Instructions

*Graded Challenge 2* dikerjakan dalam format ***notebook*** dengen beberapa **kriteria wajib** di bawah ini:

1. Machine learning framework yang digunakan adalah *Scikit-Learn*.

2. Ada penggunaan library visualisasi, seperti *matplotlib*, *seaborn*, atau yang lain.

3. Isi *notebook* harus mengikuti *outline* di bawah ini:
   1. Perkenalan
      > Bab pengenalan harus diisi dengan identitas, gambaran besar dataset yang digunakan, dan *objective* yang ingin dicapai.
   
   2. Import Libraries
      > *Cell* pertama pada *notebook* **harus berisi dan hanya berisi** semua *library* yang digunakan dalam *project*.
   
   3. Data Loading
      > Bagian ini berisi proses penyiapan data sebelum dilakukan eksplorasi data lebih lanjut. Proses Data Loading dapat berupa memberi nama baru untuk setiap kolom, mengecek ukuran dataset, dll.
   
   4. Exploratory Data Analysis (EDA)
      > Bagian ini berisi eksplorasi data pada dataset diatas dengan menggunakan query, grouping, visualisasi sederhana, dan lain sebagainya.

   5. Data Preprocessing
      > Bagian ini berisi proses penyiapan data untuk proses pelatihan model, seperti pembagian data menjadi train-dev-test, transformasi data (normalisasi, encoding, dll.), dan proses-proses lain yang dibutuhkan.
   
   6. Model Definition
      > Bagian ini berisi cell untuk mendefinisikan model. Jelaskan alasan menggunakan suatu algoritma/model, hyperparameter yang dipakai, jenis penggunaan metrics yang dipakai, dan hal lain yang terkait dengan model.

   7. Model Training
      > Cell pada bagian ini hanya berisi code untuk melatih model dan output yang dihasilkan. Lakukan beberapa kali proses training dengan hyperparameter yang berbeda untuk melihat hasil yang didapatkan. Analisis dan narasikan hasil ini pada bagian Model Evaluation.
   
   8. Model Evaluation
      > Pada bagian ini, dilakukan evaluasi model yang harus menunjukkan bagaimana performa model berdasarkan metrics yang dipilih. Hal ini harus dibuktikan dengan visualisasi tren performa dan/atau tingkat kesalahan model. **Lakukan analisis terkait dengan hasil pada model dan tuliskan hasil analisisnya**.

   9. Model Inference
      > Model yang sudah dilatih akan dicoba pada data yang bukan termasuk ke dalam train-set ataupun test-set. Data ini harus dalam format yang asli, bukan data yang sudah di-scaled.
   
   10. Pengambilan Kesimpulan
       > Pada bagian terakhir ini, **harus berisi** kesimpulan yang mencerminkan hasil yang didapat dengan *objective* yang sudah ditulis di bagian pengenalan.
    
5. *Notebook* harus diupload dalam akun GitHub masing-masing siswa untuk selanjutnya dinilai.

## Assignment Submission

- Simpan assignment pada sesi ini dengan nama `h8dsft_P1W1LGSVM_<nama-student>.ipynb` misal `h8dsft_P1W1LGSVM_raka_ardhi.ipynb`.
- Push Assigment yang telah kalian buat ke akun Github kalian masing-masing.

## Assignment Objectives

*Graded Challenge 2* ini dibuat guna mengevaluasi konsep Logistic Regression dan SVM sebagai berikut:

- Mampu memahami konsep Classification dengan Logistic Regression dan SVM
- Mampu mempersiapkan data untuk digunakan dalam model Logistic Regression dan SVM
- Mampu mengimplementasikan Logistic Regression dan SVM untuk membuat prediksi

---

## Assignment Rubrics

### Code Review

| Criteria | Meet Expectations | Points |
| --- | --- | --- |
| Preprocessing | Mampu melakukan preprocessing dataset sebelum melakukan proses modeling (split data, normalisasi, encoding, dll) | 10 pts |
| Logistic Regression | Mengimplementasikan Logistic Regression dan menentukan hyperparameter yang tepat dengan Scikit-Learn | 40 pts |
| SVM | Mengimplementasikan SVM dan menentukan hyperparameter yang tepat dengan dengan Scikit-Learn | 40 pts |
| Model Inference | Mencoba model yang telah dibuat dengan data baru | 20 pts |
| Apakah Kode Berjalan Tanpa Ada Error? | Kode berjalan tanpa ada error. Seluruh kode berfungsi dan dibuat dengan benar | 10 pts |

### Readability

| Criteria | Meet Expectations | Points |
| --- | --- | --- |
| Tertata Dengan Baik | Semua baris kode terdokumentasi dengan baik dengan Markdown untuk penjelasan kode | 10 pts |

### Analysis

| Criteria | Meet Expectations | Points|
| --- | --- | --- |
| Model Analysis | Menganalisa informasi dari model yang telah dibuat | 30 pts |
| Overall Analysis | Menarik informasi/kesimpulan dari keseluruhan kegiatan yang dilakukan | 20 pts |

---

```
Total Points : 180
```

---


## Notes

* **Deadline : P1W2D5 pukul 23:59 WIB.**

* **Keterlambatan pengumpulan tugas mengakibatkan skor GC 2 menjadi 0.**
