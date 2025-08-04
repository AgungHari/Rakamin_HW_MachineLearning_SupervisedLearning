[![banner1](rakaminacademy_cover.jpg)](https://www.rakamin.com/)

# Rakamin Homework : Supervised Learning

## Deskripsi

Repositori ini berisi rangkaian materi dan homework selama mengikuti Bootcamp di Rakamin Academy. Setiap minggu dilengkapi modul pembelajaran (PDF) dan tugas untuk memperkuat pemahaman konsep.

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

## Ringkasan Minggu ini (Week 12)
- Pengambilan keputusan drop fitur dilakukan berdasarkan gabungan statistical analysis, domain knowledge (ilmu peryoutuban).
- Feature engineering pada kolom waktu, dengan mengubah publish_time menjadi kategori waktu (pagi, siang, sore, malam) dan publish_date menjadi weekday/weekend menggunakan datetime. 
- Transformasi log (log1p) dan expm1
- Feature selection tidak menggunakan SelectKBest, melainkan dilakukan manual berdasarkan EDA, visualisasi korelasi (heatmap), dan logika bisnis. Fokusnya adalah memilih fitur yang memang tersedia saat prediksi dilakukan.
- Mencoba regresi.


## 🗂️ Struktur Repository

```
/Rakamin-SupervisedLearning
│
├── .gitignore
├── HandsOn
│   └── Regression.ipynb
├── Homework
│   └── Part1_EDA_Mentah.ipynb
│   └── Part2_DataCleansing.ipynb
│   └── Part3_Modelling.ipynb
│   └── Part4_Randomforest.ipynb
│   └── Part5_Ridgelasso.ipynb
│   └── X_test_views.csv
│   └── X_train_views.csv
│   └── y_test_views.csv
│   └── y_train_views.csv
├── Homework_LatexPDF
│   └── Gambar/
│   └── bab1.tex
│   └── bab2.tex
│   └── bab3.tex
│   └── bab4.tex
│   └── bab5.tex
│   └── main.pdf
│   └── main.tex
├── 
├── 
├── 
└── README.md


```
## ⚠️ Disclaimer

Materi dan tugas dalam repositori ini adalah milik resmi Rakamin Academy. Semua konten digunakan hanya untuk tujuan referensi dan pembelajaran pribadi, bukan untuk klaim kepemilikan.

## Acknowledgements

```
Mantap
```