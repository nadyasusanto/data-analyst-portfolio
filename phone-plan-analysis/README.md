# Data:
- Tabel users (data pengguna):
    - user_id — ID pengguna
    - first_name — nama depan pengguna
    - last_name — nama belakang pengguna
    - age — usia pengguna (tahun)
    - reg_date — tanggal mulai berlangganan (dd, mm, yy)
    - churn_date — tanggal pengguna berhenti menggunakan layanan (jika nilainya hilang atau tidak ada, berarti paket layanan sedang digunakan saat data ini dibuat)
    - city — kota tempat tinggal pengguna
    - plan — nama paket telepon
- Tabel calls (data panggilan):
    - id — ID sesi web unik
    - call_date — tanggal panggilan
    - duration — durasi panggilan (dalam menit)
    - user_id — ID pengguna yang melakukan panggilan
- Tabel messages (data SMS):
    - id — ID SMS unik
    - message_date — tanggal SMS dikirim
    - user_id — ID pengguna yang mengirim SMS
- Tabel internet (data sesi web):
    - id — ID sesi web unik
    - mb_used — volume data yang dihabiskan selama sesi 
(dalam megabita)
    - session_date — tanggal sesi web
    - user_id — ID pengguna
-Tabel plans (data paket telepon):
    - plan_name — nama paket telepon
    - usd_monthly_fee — biaya bulanan dalam dolar AS
    -minutes_included — alokasi menit panggilan bulanan
    - messages_included — alokasi SMS bulanan
    - mb_per_month_included — alokasi volume data bulanan (dalam megabita)
    - usd_per_minute — harga per menit jika telah melebihi batas alokasi paket (misalnya, jika paket memiliki alokasi 100 menit, maka penggunaan mulai dari menit ke-101 akan dikenakan biaya)
    - usd_per_message — harga per SMS jika telah melebihi batas alokasi paket
    - usd_per_gb — harga per ekstra gigabita data jika telah melebihi batas alokasi paket (1 GB = 1024 megabita)

# Tujuan:
Menganalisis perilaku para pengguna atau klien perusahaan operator telekomunikasi, lalu melakukan pengujian hipotesis statistik untuk menentukan paket prabayar manakah yang menghasilkan lebih banyak pendapatan.

# Library:
pandas\
scipy\
seaborn\
matplotlib.pyplot\
math\
numpy\