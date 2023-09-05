# Data

- Tabel events_calendar:
    - name — nama event pemasaran
    - regions — kawasan tempat kampanye iklan akan berlangsung
    - start_dt — tanggal awal kampanye
    - finish_dt — tanggal akhir kampanye
- Tabel users:
    - user_id
    - first_date — tanggal pendaftaran (sign up)
    - region
    - device — perangkat yang digunakan untuk mendaftar
- Tabel ab_events:
    - user_id
    - event_dt — tanggal dan waktu peristiwa
    - event_name — nama jenis peristiwa
    - details — data tambahan terkait peristiwa tersebut (misalnya, jumlah total pesanan dalam USD untuk peristiwa purchase)
- Tabel ab_participants:
    - user_id
    - ab_test — nama eksperimen
    - group — kelompok eksperimen pengguna berasal

# Tujuan
Melihat apakah perubahan terkait pengenalan sistem rekomendasi yang telah ditingkatkan dapat memberikan hasil adanya peningkatan dalam hal konversi setiap tahapan corong peristiwa sebanyak 10% dalam kurun waktu 14 hari setelah pengguna mendaftar.

# Library
pandas\
numpy\
scipy.stats\
seaborn\
matplotlib.pyplot\
calendar\
plotly\
proportions_ztest