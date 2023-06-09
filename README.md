# PYTN_Kampus Merdeka_Final-Project_Krisna-Winar-Setiawan

# PYTN_KampusMerdeka_fp1_Krisna-Winar-Setiawan
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

# PYTN_KampusMerdeka_fp2_Krisna-Winar-Setiawan
## Projects Overview
Database ini memiliki 23 atribut. Dengan data hujan harian selama 10 tahun di Australia,
kolom RainTomorrow adalah target variable yang mau kita prediksi. Jika “Yes” maka
besok harinya disana hujan 1mm atau lebih.
Attribute Information:
1. Date - tanggal hari itu
2. Location - lokasi, nama kota di Australia
3. MinTemp - temperatur terendah hari itu dalam celcius
4. MaxTemp - temperatur tertinggi hari itu dalam celcius
5. Rainfall - jumlah curah hujan hari itu dalam mm
6. Evaporation - jumlah evaporasi dalam mm dari Class A pan selama 24 jam
sebelum jam 9 pagi hari itu
7. Sunshine - jumlah jam hari itu cerah dengan cahaya matahari
8. WindGustDir - arah kecepatan angin yang paling tinggi selama 24 jam sebelum
jam 12 malam hari itu
9. WindGustSpeed - kecepatan angin yang paling tinggi dalam km/jam selama 24
jam sebelum jam 12 malam hari itu
10. WindDir9am - arah angin jam 9 pagi
11. WindDir3pm - arah angin jam 3 sore
12. WindSpeed9am - kecepatan angin jam 9 pagi dalam km/jam dihitung dari
rata-rata kecepatan angin 10 menit sebelum jam 3 sore
13. WindSpeed3pm - kecepatan angin jam 3 sore dalam km/jam dihitung dari
rata-rata kecepatan angin 10 menit sebelum jam 3 sore
14. Humidity9am - humiditas jam 9 pagi dalam persen
15. Humidity3pm - humiditas jam 3 sore dalam persen
16. Pressure9am - tekanan udara jam 9 pagi dalam hpa
17. Pressure3pm - tekanan udara jam 3 sore dalam hpa
18. Cloud9am - persentase langit yang tertutup awan jam 9 pagi. dihitung dalam
oktas, unit ⅛, menghitung berapa unit ⅛ dari langit yang tertutup awan. Jika 0,
langit cerah, jika 8, langit sepenuhnya tertutup awan.
19. Cloud3pm - persentase langit yang tertutup awan jam 3 sore
20. Temp9am - temperatur jam 9 pagi dalam celcius
21. Temp3pm - temperatur jam 3 sore dalam celcius
22. RainToday - apakah hari ini hujan: jika curah hujan 24 jam sebelum jam 9 pagi
melebihi 1mm, maka nilai ini adalah 1, jika tidak nilai nya 0
23. RainTomorrow - variable yang mau di prediksi

## KESIMPULAN
Untuk Hasil akhiir Classification algoritma Logistic Regression memiliki performa yang lebih baik dari yang algoritma yang lain seperti SVM, KNN, dan Random Forest. Hasil classification diatas dapat dilihat bahwa proses klasifikasi dengan dataset menghasilkan accuracy sebesar 0.84. 


# PYTN_KampusMerdeka_fp3_Krisna Winar Setiawan
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
