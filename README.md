# Time Series Plotting with Python

Proyek ini berisi contoh plotting data time series menggunakan Python dan Matplotlib. Terdapat dua notebook utama:
1. **`contohplot.ipynb`**: Contoh dasar plotting dengan data manual.
2. **`datasetplot.ipynb`**: Plotting data time series dari file CSV (`DATA_Historical_Data.csv`).

## Struktur Proyek

time-series-plotting 
- contohplot.ipynb # Contoh plotting dasar
- datasetplot.ipynb # Plotting dataset time series
- DATA_Historical_Data.csv # Dataset time series
- README.md # Penjelasan proyek
- requirements.txt # Daftar dependensi
- .gitignore # File untuk mengabaikan folder/file tertentu

## Dataset

Dataset yang digunakan (DATA_Historical_Data.csv) berisi data historis dengan kolom:
- `Date`: Tanggal
- `Open`: Harga pembukaan
- `High`: Harga tertinggi
- `Low`: Harga terendah
- `Close`: Harga penutupan
- `Volume`: Volume transaksi
-  `Price`: Harga pada tanggal tersebut.
-  `Change %`: Persentase perubahan harga.

## Dependensi

Library yang digunakan 

- `pandas`
- `matplotlib`
- `numpy`
- `datetime`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.