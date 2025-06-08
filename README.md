# Wine Quality Red Dataset Pre-processing

## Tujuan Proyek
Proyek ini bertujuan untuk melakukan pra-pemrosesan pada dataset wine-quality-red agar siap digunakan dalam model pembelajaran mesin.

## Langkah-langkah Utama
1. **Pemeriksaan Awal Dataset**
   - Dataset berisi 1.599 baris dan 12 kolom.
   - Tidak ada nilai yang hilang, tetapi ditemukan 240 data duplikat.

2. **Identifikasi dan Perbaikan Format Data**
   - Mengubah format angka yang menggunakan koma menjadi titik.
   - Mengonversi semua nilai menjadi tipe data float.

3. **Penanganan Data yang Membutuhkan Pra-pemrosesan**
   - Penghapusan duplikasi: 240 baris duplikat dihapus.
   - Penanganan missing values: Nilai NaN diisi dengan median masing-masing kolom.

4. **Normalisasi Data dengan MinMaxScaler**
   - Normalisasi dilakukan untuk menjaga keseimbangan fitur sebelum proses analisis lebih lanjut.

## Hasil Akhir
- Dataset bersih dan siap digunakan dengan 1.359 baris dan 12 kolom.
- Dataset yang sudah diproses disimpan dengan nama `winequality-red-processed.csv`.

