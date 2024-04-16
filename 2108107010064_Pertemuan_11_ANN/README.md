# Tugas- Pembelajaran Mesin

Artikel berikut menjadi referensi dalam mengerjakan Tugas - Pembelajaran Mesin:

[Support Vector Machines (SVM) Explanation - Mini Project](https://medium.com/@youness.habach/support-vector-machines-svm-explanation-mini-project-9d4b4962be52)

Nama: T.Rifal AUlia
NPM: 2108107010064

**Libary Python yang dipakai**

1. Numpy
2. Scikit-Learn
3. Matplotlib
4. Seaborn

Dataset yang digunakan berasal dari Kaggle: [Pumpkin Seeds Dataset](https://www.kaggle.com/datasets/muratkokludataset/pumpkin-seeds-dataset/data)

Biji labu sering dikonsumsi sebagai penganan di seluruh dunia karena kandungan protein, lemak, karbohidrat, dan mineralnya yang memadai. Penelitian ini dilakukan pada dua jenis biji labu yang paling penting dan berkualitas, 'Urgup_Sivrisi' dan 'Cercevelik', yang umumnya ditanam di daerah Urgup dan Karacaoren di Turki. Namun, pengukuran morfologi dari 2500 biji labu dari kedua varietas tersebut dapat dilakukan dengan menggunakan teknik ambang batas abu-abu dan biner. Dengan mempertimbangkan fitur morfologi, semua data dimodelkan dengan lima metode pembelajaran mesin yang berbeda: Regresi Logistik (LR), Multilayer Perceptron (MLP), Support Vector Machine (SVM) dan Random Forest (RF), dan k-Nearest Neighbor (k-NN), yang selanjutnya menentukan metode yang paling berhasil untuk mengklasifikasikan varietas biji labu. Namun, kinerja model-model tersebut ditentukan dengan bantuan metode validasi silang 10 kfold. SVM mencapai akurasi 88,64 persen.

## Artificial Neural Network (ANN) Model for Pumpkin Seed Classification
Repository ini berisi implementasi pembelajaran mesin untuk mengklasifikasikan varietas biji labu menggunakan data morfologis.

## Tujuan

Tujuan dari kode ini adalah:

1. Memuat dataset dan memeriksa informasinya.
2. Memisahkan dataset menjadi fitur dan label, lalu membaginya menjadi set pelatihan dan pengujian.
3. Melakukan preprocessing data dengan mengkodekan label dan melakukan penskalaan fitur.
4. Membangun model jaringan saraf tiruan (ANN) untuk klasifikasi.
5. Melatih model menggunakan set pelatihan dan mengukur akurasinya.
6. Mengevaluasi performa model dengan menggunakan set pengujian dan membuat visualisasi confusion matrix.

## Hasil

Setelah melatih model, akurasi prediksi yang dihasilkan adalah sebesar X%. Visualisasi confusion matrix juga disertakan untuk mengevaluasi performa model.

## Penggunaan

1. Instal semua library yang diperlukan dengan menjalankan perintah `pip install -r requirements.txt`.
2. Jalankan script Python `classification_of_pumpkin_seeds.py` untuk menjalankan kode.

Pastikan Anda telah menginstal Python dan semua library yang diperlukan sebelum menjalankan kode.
