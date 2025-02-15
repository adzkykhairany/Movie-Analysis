# Movie Analysis
Selamat datang di repositori **Movie Analysis!** Proyek ini bertujuan untuk menganalisis data film, menggali wawasan dari berbagai atribut film, dan menyajikan hasil analisis dalam bentuk visualisasi.

## Pendahuluan
Proyek ini berfokus pada analisis data film untuk memahami tren, pola, dan faktor-faktor yang mungkin mempengaruhi kesuksesan sebuah film.

## Sumber Data
Data yang digunakan dalam proyek ini berasal dari Kaggle dengan judul ["IMDB Movie Dataset"](https://www.kaggle.com/datasets/danielgrijalvas/movies). Detail lebih lanjut mengenai sumber data dapat ditemukan dalam direktori [data](assets\movies.csv).

## Deskripsi Dataset
- `name`: Judul film
- `rating`: Peringkat film berdasarkan kesesuaian dengan segmen penonton tertentu (R, PG, NC-17, dsb)
- `genre`: Genre utama film
- `year`: Tahun film dirilis
- `released`: Tanggal film dirilis (YYYY-MM-DD)
- `score`: Rata-rata nilai film yang diberikan oleh user IMDB
- `votes`: Banyak user IMDB yang memberi nilai terhadap film
- `director`: Sutradara film
- `writer`: Penulis naskah film
- `star`: Pemeran utama film
- `country`: Negara produksi film
- `budget`: Biaya yang dikeluarkan untuk produksi film
- `gross`: Pendapatan kotor dari penayangan film
- `company`: Perusahaan rumah produksi film
- `runtime`: Durasi film (dalam menit)

## Proses Analisis Data
### Pengumpulan Data
Data film dikumpulkan dari Kaggle. Proses pengumpulan data melibatkan scraping data dari situs web dan mengunduh dataset dari web.

### Preprocessing
Proses preprocessing mencakup penghapusan nilai null dan baris duplikasi.
![Persebaran](assets/hubunganvar.png)
**Keterangan :** Setelah dilakukan pembersihan data dengan menghapus baris yang mengandung nilai null, visualisasi distribusi dan hubungan antar variabel tidak menunjukkan perubahan drastis. Hal ini mengindikasikan bahwa pembersihan data tidak mempengaruhi pola atau tren yang ada dalam data.


### Analisis Data
Setelah data dipreproses, langkah selanjutnya adalah melakukan analisis data untuk menggali wawasan yang berguna.

### Visualisasi Hasil Analisis
Hasil analisis data kemudian disajikan dalam bentuk visualisasi untuk memudahkan pemahaman.

## Analisis dan Hasil
Bagian ini menjelaskan hasil utama dari analisis data film:

1. **Analisis Genre dan Pendapatan**:
    ![Analisis Genre dan Pendapatan](assets/1_genregross.png)
    **Deskripsi**: Rata-rata pendapatan kotor (gross) untuk setiap genre utama film. Genre paling menguntungkan adalah Animasi, diikuti oleh Keluarga dan Aksi.

2. **Analisis Rating dan Pendapatan**:
    ![Analisis Rating dan Pendapatan](assets/2_ratingpendapatan.png)
    **Deskripsi**: Menampilkan distribusi pendapatan kotor berdasarkan rating film (R, PG, NC-17, dsb). Film dengan rating G cenderung memiliki pendapatan yang lebih tinggi dibandingkan dengan rating lainnya.
