# Data:
- Tabel visits (log/catatan server yang memuat data kunjungan ke situs web):
- Uid — ID pengguna
- Device —perangkat pengguna
- Start Ts — tanggal dan waktu dimulainya sesi
- End Ts — tanggal dan waktu berakhirnya sesi
- Source Id — ID sumber iklan, sumber yang digunakan pengguna untuk datang ke situs web
- Semua tanggal dalam tabel ini menggunakan format YYYY-MM-DD.
- Tabel orders (data terkait pesanan):
- Uid — ID pengguna yang membuat pesanan
- Buy Ts — tanggal dan waktu pesanan dibuat
- Revenue — pendapatan Y.Afisha dari pesanan tersebut
- Tabel costs (data terkait pengeluaran pemasaran):
source_id — ID sumber iklan
- dt — tanggal
- costs — pengeluaran untuk sumber iklan pada tanggal tersebut

# Tujuan:
Menganalisis data mengenai sesi pengguna, pemasaran dan penjualan produk perusahaan online, supaya kita dapat mengetahui sumber/platform mana saja yang efektif sehingga perusahaan ini dapat mengoptimalkan biaya pemasaran.

# Library:
pandas\
scipy\
seaborn\
matplotlib.pyplot\
math\
numpy\