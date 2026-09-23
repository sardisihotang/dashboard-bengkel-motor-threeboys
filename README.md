# 🛒 Decision Support System: Product Bundling Recommendation

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
</p>

## 📌 Tentang Proyek / About the Project

**[ID]** Aplikasi web berbasis dasbor interaktif ini dibangun untuk membantu manajemen Bengkel Motor Threeboys dalam menggali pola pembelian pelanggan (*Market Basket Analysis*) menggunakan **Algoritma Apriori**. Sistem pendukung keputusan ini memproses data transaksi riil untuk menghasilkan rekomendasi paket *bundling* barang dan jasa perbaikan secara cerdas dan otomatis.

**[EN]** *This interactive dashboard-based web application is built to assist the management of Threeboys Motor Workshop in discovering customer purchasing patterns (Market Basket Analysis) using the **Apriori Algorithm**. This decision support system processes real transaction data to generate smart and automated bundling recommendations for spare parts and repair services.*

---

## 🚀 Fitur Utama / Key Features

**[ID]**
* **Fleksibilitas Data:** Mendukung integrasi dan pemrosesan data transaksi barang serta jasa perbaikan secara bersamaan.
* **Data Preprocessing (NLP):** Dilengkapi modul pembersihan teks teks dan kamus standardisasi otomatis untuk meminimalkan anomali data.
* **Automasi Machine Learning:** Ekstraksi *Frequent Itemset* dan *Association Rules* secara otomatis berdasarkan algoritma Apriori.
* **Parameter Dinamis:** Antarmuka (UI) yang memungkinkan pengguna awam untuk mengatur nilai batas *Minimum Support* dan *Confidence* secara langsung.

**[EN]**
* **Data Flexibility:** Supports the integration and simultaneous processing of both goods and service transaction data.
* **Data Preprocessing (NLP):** Equipped with text cleaning modules and automated standardization dictionaries to minimize data anomalies.
* **Machine Learning Automation:** Automated extraction of Frequent Itemsets and Association Rules based on the Apriori algorithm.
* **Dynamic Parameters:** A user-friendly UI allowing non-technical users to directly adjust the threshold values for Minimum Support and Confidence.

---

## 🛠️ Teknologi yang Digunakan / Tech Stack

* **Bahasa Pemrograman:** Python 3.12
* **Data Science & ML:** Pandas, MLxtend (Machine Learning Extensions)
* **Web Framework:** Streamlit

---

## 📝 Cara Penggunaan
1. Ekspor data transaksi barang dan jasa dari sistem POS bengkel (format CSV).
2. Unggah file CSV ke dalam sistem dasbor.
3. Atur parameter pendukung, lalu klik "Cari Paket Rekomendasi".
4. Unduh hasil rekomendasi dalam bentuk CSV untuk laporan strategi pemasaran.

---

## 💻 Panduan Instalasi (Lokal) / Local Installation

**[ID]** Pastikan Anda sudah menginstal Python di sistem Anda.
**[EN]** *Ensure you have Python installed on your system.*

1. Clone repositori ini / *Clone this repository*:
   ```bash
   git clone [https://github.com/sardisihotang/dashboard-bengkel-motor-threeboys.git](https://github.com/sardisihotang/dashboard-bengkel-motor-threeboys.git)
   cd dashboard-bengkel-motor-threeboys

