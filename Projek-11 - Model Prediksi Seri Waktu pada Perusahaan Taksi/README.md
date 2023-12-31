### Model Prediksi Seri Waktu untuk Mengetahui Jumlah Pesanan Perusahaan Taksi

Sebuah perusahaan taksi bernama `Sweet Lift` telah mengumpulkan data historis (`time series`) tentang pesanan taksi di bandara. Untuk menarik lebih banyak pengemudi pada jam sibuk, perlu memprediksi jumlah pesanan taksi untuk `satu jam` berikutnya. Perusahaan hanya mempunyai data historis dari bulan `maret` hingga bulan `agustus` tahun 2018. Kita akan membuat beberapa model `machine learning` untuk memprediksi jumlah pesanan beserta pengujian model-model tersebut, dimana `metrik RMSE` pada *test set* `tidak boleh lebih dari 48`. Berikut ini beberapa langkah untuk menyelesaikan masalah pada projek ini:
1. Melakukan *resampling* data dalam satu jam.
2. Menganalisis dataset untuk mendapatkan `insights` berupa fitur-fitur `time series` seperti analisis `tren`, `seasonality` dan `residu`.
3.  Melatih `model` yang `berbeda` dengan `hiperparameter` yang `berbeda`. Disini kita akan menentukan bahwa sampel `test` sebesar `10%` dari dataset.
4. Menguji `metrik RMSE` pada `semua model` menggunakan data `test`.
5. Membuat prediksi untuk bulan `september` tahun 2018 menggunakan `best model`.

| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Model Prediksi Seri Waktu pada Perusahaan Taksi](https://github.com/fuadraharjo/TripleTen_IND/blob/main/Projek-11%20-%20Model%20Prediksi%20Seri%20Waktu%20pada%20Perusahaan%20Taksi/Model%20prediksi%20seri%20waktu%20untuk%20mengetahui%20jumlah%20pesanan%20perusahaan%20taksi.ipynb) | Perbandingan `model machine learning` untuk memprediksi `jumlah pesanan` pada perusahaan taksi menggunakan `dataset seri waktu` untuk mendapatkan skor `RMSE` yang `tidak lebih besar dari 48` | *pandas*, *numpy*, *sklearn*, *matplotlib*, *seaborn*, *XGBoost*, *time*, *LightGBM*, *statsmodels* |