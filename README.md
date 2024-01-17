# Submission Dicoding "Belajar Data Analytics dengan Python"

## Project Data Analytics

Repositori berisi projek analisis data yang dibuat dengan menggunakan **Streamlit** sebagai dashboard framework.

## Deskripsi

Proyek ini berupa analis data terhadap **Brazilian E-Commerce** dengan tujuan untuk memberikan insight dan pemahaman mengenai informasi data berdasarkan pertanyaan bisnis. Selain itu dilakukan juga Analisis RFM (Recency, Frequency, Monetary). Analisis RFM adalah metode yang digunakan untuk mengidentifikasi segmen pelanggan berdasarkan kegiatan mereka. Analisis ini membantu perusahaan untuk mengoptimalkan strategi marketing dan penjualan.

## Sumber Data

Kaggle Dataset brazilian-ecommerce [(Link Download)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data)

## Pertanyaan Bisnis

- Bagaimana performa penjualan dan revenue perusahaan dalam beberapa bulan terakhir?
- Produk apa yang paling banyak dan paling sedikit terjual?
- Bagaimana demografi pelanggan yang kita miliki?

## Struktur Direktori

- **/data**: Merupakan Direktori Projek yang terdiri atas dataset yang berformat .csv
- **/dashboard**: Terdiri atas file dashboard.py yang merupakan kode utama dalam pembuatan visualisasi website
- **notebook.ipynb**: File yang digunakan untuk melakukan analisis data.

## Instalasi

1. Clone repository ke komputer lokal anda menggunakan perintah berikut:

   ```shell
   git clone IrvandyIN/Brazilian-E-Commerce-Analysis
   ```
2. Buat Virtual Environtment:

    ```shell
    python -m venv venv

    ```
3. Aktifkan Virtual Environment:

    ```shell
    .\venv\Scripts\activate

    ```

4. Lakukan Instalasi Dependecies atau Library Dengan Perintah Berikut:

    ```shell
    pip install -r requirements.txt
    
    ```

## Penggunaan
Menjalankan Dashboard Streamlit:

    ```shell
    cd dashboard
    streamlit run dashboard.py

    ```





   
