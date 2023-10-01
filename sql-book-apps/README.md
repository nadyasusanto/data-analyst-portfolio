# Data:
- Tabel books: Berisi data tentang buku:

    - book_id — ID buku
    - author_id — ID penulis
    - title — judul buku
    - num_pages — jumlah halaman
    - publication_date — tanggal penerbitan
    - publisher_id — ID penerbit
- Tabel authors: Berisi data tentang penulis:

    - author_id — ID penulis
    - author — nama penulis
- Tabel publishers: Berisi data tentang penerbit:

    - publisher_id — ID penerbit
    - publisher — nama penerbit
- Tabel ratings: Berisi data tentang ulasan pengguna:

    - rating_id — ID rating
    - book_id — ID buku
    - username — nama pengguna yang memberi rating buku
    - rating
- Tabel reviews: Berisi data tentang ulasan pelanggan:

    - review_id — ID ulasan
    - book_id — ID buku
    - username — nama pengguna yang mengulas buku
    - text — teks ulasan

# Tujuan:
Menganalisis data tentang buku, penerbit, penulis, serta rating dan ulasan pelanggan atas buku terkait untuk mengetahui faktor-faktor apa saja yang dapat berpengaruh dalam industri atau pasar buku, sehingga kita dapat memberikan usulan harga yang kompetitif untuk produk baru yang ditujukan kepada para pecinta buku.

# Library:
pandas\
sqlalchemy
