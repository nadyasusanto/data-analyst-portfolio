# Data:
- Tabel neighborhoods: data terkait wilayah di kota Chicago
    - name: nama wilayah
    - neighborhood_id: kode wilayah
- Tabel cabs: data terkait taksi
    - cab_id: kode kendaraan
    - vehicle_id: ID teknis kendaraan
    - company_name: nama perusahaan yang memiliki kendaraan
- Tabel trips: data terkait perjalanan
    - trip_id: kode perjalanan
    - cab_id: kode kendaraan yang beroperasi
    - start_ts: tanggal dan waktu perjalanan dimulai (waktu dibulatkan dalam satuan jam)
    - end_ts: tanggal dan waktu perjalanan berakhir (waktu dibulatkan dalam satuan jam)
    - duration_seconds: durasi perjalanan dalam satuan detik
    - distance_miles: jarak perjalanan dalam satuan mil
    - pickup_location_id: kode wilayah penjemputan
    - dropoff_location_id: kode wilayah pengantaran
- Tabel weather_records: data terkait cuaca
    - record_id: kode pencatatan cuaca
    - ts: tanggal dan waktu saat pencatatan cuaca dilakukan (waktu dibulatkan dalam satuan jam)
    - temperature: suhu saat pencatatan cuaca dilakukan
    - description: deskripsi singkat tentang kondisi cuaca, seperti "light rain" (hujan ringan) atau "scattered clouds" (berawan).

Hasil dari proyek SQL disimpan di file csv dengan data sebagai berikut:
- company_name: nama perusahaan taksi
- trips_amount: jumlah perjalanan untuk setiap perusahaan taksi pada tanggal 15-16 November 2017.
- project_sql_result_04.csv. File ini memuat data berikut:
- dropoff_location_name: nama wilayah di Chicago tempat perjalanan berakhir
- average_trips: jumlah rata-rata perjalanan yang berakhir di setiap wilayah pada bulan November 2017.

# Tujuan:
Mempelajari basis data, menganalisis data dari kompetitor menggunakan SQL dan menguji hipotesis menggunakan Python tentang pengaruh cuaca terhadap frekuensi perjalanan, pada sebuah perusahaan berbagi tumpangan (ride-sharing) baru yang diluncurkan di Chicago.

# Library:
pandas\
scipy\
seaborn\
matplotlib.pyplot\
math\
numpy\