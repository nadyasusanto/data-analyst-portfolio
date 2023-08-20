# Data:
 - 'Churn' — churn aktual untuk bulan terkait\
 
Kolom dataset saat ini:
- Data pengguna untuk bulan sebelumnya
    - gender
    - Near_Location — apakah pengguna tinggal atau bekerja di dekat lokasi pusat kebugaran
    - Partner — apakah pengguna adalah karyawan perusahaan mitra (pusat kebugaran ini memiliki perusahaan mitra dan para karyawannya berhak untuk mendapatkan diskon; dalam hal ini, pusat kebugaran menyimpan informasi tentang perusahaan tempat kerja pelanggan mereka)
    - Promo_friends — apakah pengguna awalnya melakukan pendaftaran melalui penawaran "ajak teman" (mereka menggunakan kode promo teman saat membayar keanggotaan pertama mereka)
    - Phone — apakah pengguna memberikan nomor telepon mereka
    - Age
    - Lifetime — waktu (dalam bulan) sejak kunjungan pertama pelanggan ke pusat kebugaran
- Data dari log kunjungan dan pembelian, serta data terkait status keanggotaan saat ini
    - Contract_period — 1 bulan, 3 bulan, 6 bulan, atau 1 tahun
    - Month_to_end_contract — sisa bulan sebelum kontrak berakhir
    - Group_visits — apakah pengguna mengambil bagian dalam sesi kelompok
    - Avg_class_frequency_total —frekuensi rata-rata kunjungan per minggu selama masa hidup (lifetime) pelanggan
    - Avg_class_frequency_current_month — frekuensi rata-rata kunjungan per minggu sepanjang bulan yang sedang berjalan
    - Avg_additional_charges_total — jumlah total uang yang dikeluarkan untuk membayar layanan lain di pusat kebugaran: kafe, barang atletik, kosmetik, pijat, dll.

# Tujuan:
Menganalisis profil para pelanggan pusat kebugaran dan mengembangkan strategi retensi pelanggan (customer retention)

# Library:
pandas\
scipy.stats\
seaborn\
matplotlib.pyplot\
math\
numpy\
sklearn.preprocessing\
sklearn.linear_model\
sklearn.ensemble\
sklearn.cluster\
scipy.cluster\