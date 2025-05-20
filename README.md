# 🧾 Customer Segmentation Using RFM Analysis

Proyek ini bertujuan untuk mengelompokkan pelanggan berdasarkan perilaku pembelian mereka menggunakan metode **RFM Analysis** (Recency, Frequency, Monetary). Dengan pendekatan ini, bisnis dapat lebih memahami karakteristik pelanggannya dan menyusun strategi pemasaran yang lebih tepat sasaran.

## 📂 Dataset

Dataset yang digunakan berisi transaksi pembelian dengan kolom-kolom berikut:

- `No_Invoice` – Nomor faktur transaksi
- `Kode_Barang` – Kode unik barang
- `Deskripsi_Barang` – Nama atau deskripsi barang
- `Jmlah` – Jumlah barang yang dibeli
- `Tgl_invoice` – Tanggal transaksi
- `Harga_Satuan` – Harga satuan barang
- `ID_Costumer` – ID unik pelanggan
- `Negara` – Negara pelanggan

## 🧹 Data Preparation

Proses data cleaning meliputi:

- Menghapus karakter-karakter khusus atau tidak valid dalam kolom teks
- Menangani nilai kosong (null value)
- Menghapus data duplikat untuk menjaga integritas data

## 📊 Exploratory Data Analysis (EDA)

EDA dilakukan untuk memahami:

- Distribusi transaksi per pelanggan
- Frekuensi pembelian
- Nilai pembelian
- Perilaku pembelian berdasarkan waktu

## 📈 RFM Segmentation

Pelanggan dikelompokkan berdasarkan:

- **Recency (R):** Seberapa baru pelanggan melakukan pembelian terakhir
- **Frequency (F):** Seberapa sering pelanggan melakukan pembelian
- **Monetary (M):** Total nilai pembelian oleh pelanggan

## 👥 Customer Behavior Segments

Berdasarkan skor RFM, pelanggan dikelompokkan ke dalam beberapa kategori perilaku:

- **Casual Buyers** – Belanja jarang dengan nilai transaksi kecil
- **Regular Customers** – Konsisten melakukan pembelian dengan frekuensi sedang
- **High-Volume Buyers** – Sering belanja dalam jumlah besar
- **Wholesale Buyers** – Beli dalam jumlah besar tapi tidak sering
- **Premium Customers** – Pelanggan terbaik; belanja sering, baru-baru ini, dan dengan nilai besar

## 🛠 Tools

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

## 📁 Struktur Folder

