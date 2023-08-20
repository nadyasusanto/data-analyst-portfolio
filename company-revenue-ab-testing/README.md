# Data:
- Tabel hipotesis:
    - Hypotheses — deskripsi singkat tentang hipotesis
    - Reach — jangkauan pengguna, dalam skala satu hingga sepuluh
    - Impact — dampak terhadap pengguna, dalam skala satu hingga sepuluh
    - Confidence — keyakinan pada hipotesis, dalam skala satu sampai sepuluh
    - Effort — sumber daya yang diperlukan untuk menguji hipotesis, dalam skala satu sampai sepuluh. Semakin tinggi nilai Effort, semakin intensif sumber daya pengujiannya.\

Data yang digunakan pada bagian kedua proyek:
- Tabel orders:
    - transactionId — ID pesanan
    - visitorId — ID pengguna yang membuat pesanan
    - date — tanggal dibuatnya pesanan
    - revenue — pendapatan dari pesanan
    - group — kelompok uji (test group) A/B tempat pengguna berada
- Tabel visits:
    - date — tanggal
    - group — kelompok uji (test group) A/B
    - visits — jumlah kunjungan pada tanggal yang ditentukan untuk kelompok uji A/B yang ditentukan

# Tujuan:
Menentukan hipotesis dan mengambil keputusan berdasarkan data apakah hipotesis tersebut dapat dijalankan untuk membantu meningkatkan pendapatan perusahaan dengan melakukan analisa pengujian kelompok A/B.

# Library:
pandas\
scipy\
seaborn\
matplotlib.pyplot\
math\
numpy\