# MachineLearning-TimeSeries-01
Projek Machine Learning mengenai Time Series - Forecasting untuk tugas Submission 2 Kursus Pengembang Machine Learning Dicoding Academy

Projek dipublish pada github https://github.com/Abito21/MachineLearning-TimeSeries-01

Projek yang saya buat untuk memenuhi tugas submission kedua kursus Belajar Pengembang Machine Learning di Dicoding Academy, dijelaskan sebagai berikut

## •	Data Preparation

Data yang digunakan adalah dataset bbc-new-data yang diunduh melalui kaggle https://www.kaggle.com/mahirkukreja/delhi-weather-data kemudian agar lebih mudah mengaksesnya menyimpannya di google drive.Data memiliki 19 atribut atau kolom objek

Data memiliki 19 atribut atau kolom objek.

![image](https://user-images.githubusercontent.com/67644383/160245564-38dc2a0d-3ee2-4c8d-b674-6e321f55af25.png)

Data yang digunakan.

![image](https://user-images.githubusercontent.com/67644383/160245580-0dc5b7dc-a866-4a2d-b99f-2cd7b3bf7c6d.png)

Melakukan pengecekan nilai kosong (NaN)

![image](https://user-images.githubusercontent.com/67644383/160245583-162af568-23fc-4a52-96f5-cd8dc7b89c58.png)

Melakukan data cleaning nilai yang kosong dengan nilai rata – rata dari data dan mengubah tipe data pada kolom waktu tanggal yang awal mulanya string menjadi datetime untuk memudahkan melakukan forecasting berdasarkan time series.

![image](https://user-images.githubusercontent.com/67644383/160245593-2217ac00-efb9-40b3-ab10-839d0ab63079.png)

Visualisasi nilai dataset yang sudah di cleaning terlihat nampak data lebih relevan tidak terdapat nilai outlier dan kosong, sebagai berikut.

![image](https://user-images.githubusercontent.com/67644383/160245605-f2f1902e-13fd-4f66-a5c6-afd2d9095bd4.png)

## •	Data Modelling

Model yang digunakan untuk pelatihan.

![image](https://user-images.githubusercontent.com/67644383/160245619-6afa171e-d63b-485f-93db-4e5b14787e60.png)

Metrik Loss

![image](https://user-images.githubusercontent.com/67644383/160245628-d16529d5-c7c5-4022-bcf5-509a3a3931a2.png)

![image](https://user-images.githubusercontent.com/67644383/160245632-09bb7ef3-877e-4cc5-b84b-dac329fd7b0d.png)

Hasil pelatihan model mendapatkan metrik loss sebesar  19% dan val_loss sebesar 18%.
 
 
