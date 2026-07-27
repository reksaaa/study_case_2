# Prediksi Konsentrasi Glukosa

Proyek ini menggunakan metode **Sliding Window** dan **Linear Regression** untuk memprediksi konsentrasi glukosa pada time-step berikutnya berdasarkan tiga data sebelumnya.

## Teknologi

* Python
* NumPy
* Pandas
* Scikit-learn

## Instalasi

```bash
pip install numpy pandas scikit-learn
```

## Cara Menjalankan

```bash
python glucose_prediction.py
```

## Metode

Data runtun waktu diubah menjadi fitur dan target dengan Sliding Window.

Contoh:

```text
Data: [5, 4, 3, 2, 1]

X = [[5, 4, 3],
     [4, 3, 2]]

y = [2, 1]
```

Model menggunakan tiga data glukosa sebelumnya untuk memprediksi satu nilai berikutnya.

## Hasil

Dengan `seed=42`, hasil prediksi:

```text
Prediksi Glukosa Selanjutnya: 0.9601052053763887
Nilai Aktual Glukosa: 0.9823152554004779
```

Model berhasil menghasilkan prediksi numerik bertipe `float` dan mendekati nilai aktual.

## Struktur File

```text
glucose-prediction/
├── glucose_prediction.py
├── requirements.txt
└── README.md
```

## Pengembang

**Neng Teni Yuliani**
