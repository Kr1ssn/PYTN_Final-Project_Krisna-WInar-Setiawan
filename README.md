# PYTN_Kampus Merdeka_Final-Project_Krisna-WInar-Setiawan

# PYTN_KampusMerdeka_fp1_Krisna-WInar-Setiawan
## Project Overview
Database ini memiliki 57 atribut, tetapi yang paling relevan ada 10 atribut dari semuanya.
Final Project 1 ini dibuat guna mengevaluasi konsep Regression sebagai berikut:

● Mampu memahami konsep regression dengan Linear Regression 

● Mampu mempersiapkan data untuk digunakan dalam model Linear Regression

● Mampu mengimplementasikan Linear Regression untuk membuat prediksi

Attribute Information:
1. id
2. timestamp
3. hour
4. day
5. month
6. datetime
7. timezone
8. source: destinasi awal
9. destination: destinasi akhir
10. cab_type: tipe transportasi (uber / lyft)
11. … dan lainnya

## KESIMPULAN
Setelah melakukan proses visualisai data dan analisis maka dapat ditarik kesimpulan bahwa jumlah order ataui pesananUber lebih uggul dibandingakan Lyft dari segalaa aspek periode waktu.

“PYTN_KampusMerdeka_fp2_Krisna Winar Setiawan"

“PYTN_KampusMerdeka_fp3_Krisna Winar Setiawan".
## Projects Overview
Data ini memiliki 13 atribut. Prediksi keselamatan pasien dari penyakit jantung.
## Attribute Information:
1. age - umur pasien
2. anaemia - apakah ada pengurangan haemoglobin
3. creatinine_phosphokinase - level enzim CPK dalam mcg/L
4. diabetes - apakah pasien punya riwayat diabetes
5. ejection_fraction - persentase darah yang meninggalkan jantung dalam persentasi
di setiap kontraksi jantung
6. high_blood_pressure - apakah pasien punya darah tinggi
7. platelets - jumlah platelet di darah dalam kiloplatelets/mL
8. serum_creatinine - level serum creatinine di darah dalam mg/dL
9. serum_sodium - level serum sodium di darah dalam mEq/L
10. sex - apakah pasien pria atau wanita
11. smoking - apakah pasien merokok
12. time - waktu dalam hari untuk follow-up
13. DEATH_EVENT - apakah pasien sudah meninggal saat waktu follow-up

## Random Forest
Random Forest secara teknis adalah ensemble method (berdasarkan pendekatan divide-and-conquer) dari decision trees yang dihasilkan pada dataset yang dipisahkan secara acak. Kumpulan decision tree classifiers ini juga dikenal sebagai forest. Decision trees individu dihasilkan menggunakan indikator pemilihan atribut seperti information gain, gain ratio, dan Gini index untuk setiap atribut. Setiap pohon bergantung pada sampel acak yang independen. Dalam masalah klasifikasi, setiap pohon memilih dan kelas paling populer dipilih sebagai hasil akhir. Dalam kasus regresi, rata-rata dari semua keluaran pohon dianggap sebagai hasil akhir. Ini lebih sederhana dan lebih kuat dibandingkan dengan algoritma klasifikasi non-linier lainnya.

### Random forest bekerja dalam 4 tahap:

1. Pilih sampel acak dari kumpulan data yang diberikan.
2. Buat decision tree untuk setiap sampel dan dapatkan hasil prediksi dari setiap decision tree.
3. Lakukan voting untuk setiap hasil prediksi.
4. Pilih hasil prediksi dengan suara terbanyak sebagai prediksi akhir.
