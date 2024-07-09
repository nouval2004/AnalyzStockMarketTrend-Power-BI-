# Analysis of Indonesian Stock Market Trends (PowerBI)
### about dataset
Dataset ini berisi informasi mengenai perusahaan yang terdaftar di pasar saham Indonesia. Kolom-kolom yang terdapat dalam dataset ini meliputi:

- Code: Kode saham perusahaan.
- Name: Nama perusahaan.
- ListingDate: Tanggal pencatatan saham di bursa.
- Shares: Jumlah saham yang beredar.
- ListingBoard: Papan pencatatan.
- Sector: Sektor industri perusahaan.
- LastPrice: Harga saham terakhir.
- MarketCap: Kapitalisasi pasar.
- MinutesFirstAdded: Waktu pertama kali data ditambahkan (dalam menit).
- MinutesLastUpdated: Waktu terakhir data diperbarui (dalam menit).
- HourlyFirstAdded: Waktu pertama kali data ditambahkan (dalam jam).
- HourlyLastUpdated: Waktu terakhir data diperbarui (dalam jam).
- DailyFirstAdded: Waktu pertama kali data ditambahkan (dalam hari).
- DailyLastUpdated: Waktu terakhir data diperbarui (dalam hari).

### Data Cleaning

Pembersihan data dilakukan menggunakan Excel dengan langkah-langkah berikut:

  - Mengecek dan memperbaiki ejaan yang benar:
        Memastikan semua kode saham dan nama perusahaan dieja dengan benar.
        Memastikan konsistensi dalam penulisan sektor dan papan pencatatan.

  - Mengatasi data yang kosong:
        Mengisi nilai yang hilang dengan rata-rata atau nilai median yang relevan.
        Menghapus entri yang tidak lengkap jika tidak memungkinkan untuk mengisi data yang hilang.

  - Mengatasi data yang duplikat:
        Mengidentifikasi dan menghapus entri duplikat untuk memastikan keunikan setiap perusahaan dalam dataset.

  - Validasi data:
        Memastikan bahwa nilai dalam kolom seperti Shares, LastPrice, dan MarketCap adalah angka positif dan masuk akal.
        Memeriksa tanggal pencatatan (ListingDate) untuk memastikan format yang benar dan konsistensi kronologis.

### Pertanyaan/Pemrmasalahan

Beberapa pertanyaan yang relevan yang dapat dijawab dengan melihat dashboard adalah:

  1. Berapa jumlah sektor dan perusahaan yang tercatat di pasar saham Indonesia?
  2. Bagaimana tren harga saham rata-rata dan kapitalisasi pasar rata-rata dari tahun ke tahun?
  3. Sektor mana yang memiliki kapitalisasi pasar rata-rata tertinggi?
  4. Perusahaan mana yang memiliki kapitalisasi pasar rata-rata tertinggi?
  5. Bagaimana distribusi kapitalisasi pasar berdasarkan sektor?
  6. Apakah ada korelasi antara jumlah saham yang beredar dan kapitalisasi pasar?
  7. Bagaimana performa sektor-sektor tertentu selama periode waktu tertentu?
  8. Perusahaan mana yang menunjukkan lonjakan signifikan dalam harga saham dan kapitalisasi pasar?
  9. Bagaimana fluktuasi harga saham dan kapitalisasi pasar dipengaruhi oleh peristiwa ekonomi besar?

### Insight

  1. Jumlah Sektor dan Perusahaan
        Terdapat 11 sektor dan 829 perusahaan yang tercatat di pasar saham Indonesia.

  2. Tren Harga Saham dan Kapitalisasi Pasar
        Dari grafik "Average of LastPrice and Average of MarketCap by Year", terlihat bahwa ada beberapa lonjakan signifikan dalam harga saham rata-rata dan kapitalisasi pasar rata-rata pada tahun-tahun tertentu, seperti pada tahun 1980, 2000, dan 2010.

  3. Kapitalisasi Pasar Berdasarkan Sektor
        Sektor keuangan memiliki kapitalisasi pasar rata-rata tertinggi dibandingkan dengan sektor lainnya.

  4. Perusahaan dengan Kapitalisasi Pasar Tertinggi
        Bank Central Asia memiliki kapitalisasi pasar rata-rata tertinggi diikuti oleh Bank Rakyat Indonesia dan Bank Mandiri.

  5. Distribusi Kapitalisasi Pasar
        Grafik "Average of MarketCap by Sector" menunjukkan bahwa sektor keuangan mendominasi kapitalisasi pasar, diikuti oleh sektor infrastruktur dan teknologi.

  6. Korelasi Jumlah Saham dan Kapitalisasi Pasar
        Terdapat korelasi positif antara jumlah saham yang beredar dan kapitalisasi pasar, menunjukkan bahwa perusahaan dengan lebih banyak saham cenderung memiliki kapitalisasi pasar yang lebih tinggi.

  7. Performa Sektor Selama Periode Waktu Tertentu
        Sektor keuangan dan teknologi menunjukkan performa yang kuat selama beberapa dekade terakhir, sementara sektor lain seperti energi dan bahan dasar mengalami fluktuasi yang lebih besar.

  8. Lonjakan Signifikan dalam Harga Saham dan Kapitalisasi Pasar
        Beberapa perusahaan, seperti Bank Central Asia, menunjukkan lonjakan signifikan dalam harga saham dan kapitalisasi pasar pada periode tertentu, kemungkinan besar terkait dengan peristiwa ekonomi besar atau perubahan kebijakan pemerintah.

  9. Fluktuasi Harga Saham dan Kapitalisasi Pasar dipengaruhi oleh Peristiwa Ekonomi Besar
        Grafik "Average of LastPrice and Average of MarketCap by Year" menunjukkan bahwa fluktuasi signifikan dalam harga saham dan kapitalisasi pasar sering kali bertepatan dengan peristiwa ekonomi besar seperti krisis ekonomi, perubahan kebijakan pemerintah, dan peristiwa global yang berdampak pada pasar saham secara keseluruhan. Contoh yang menonjol termasuk lonjakan pada tahun 1997-1998 selama krisis keuangan Asia dan peningkatan pada tahun 2008-2009 selama krisis keuangan global.

### Kesimpulan

Analisis ini memberikan gambaran yang jelas mengenai tren pasar saham Indonesia. Beberapa poin penting yang dapat disimpulkan adalah:

  1. Pasar saham Indonesia didominasi oleh sektor keuangan dalam hal kapitalisasi pasar.
  2. Terdapat fluktuasi yang signifikan dalam harga saham rata-rata dan kapitalisasi pasar rata-rata selama beberapa dekade terakhir.
  3. Perusahaan besar seperti Bank Central Asia dan Bank Rakyat Indonesia memainkan peran utama dalam kapitalisasi pasar.
  4. Sektor keuangan dan teknologi menunjukkan performa yang kuat, sementara sektor lain mengalami fluktuasi yang lebih besar.
  5. Korelasi positif antara jumlah saham yang beredar dan kapitalisasi pasar menunjukkan pentingnya skala perusahaan dalam pasar saham.
  7. Lonjakan signifikan dalam harga saham dan kapitalisasi pasar seringkali terkait dengan peristiwa ekonomi besar atau perubahan kebijakan.
  8. Distribusi kapitalisasi pasar menunjukkan bahwa beberapa sektor dan perusahaan mendominasi pasar, sementara yang lain memiliki kontribusi yang lebih kecil.

Laporan ini memberikan wawasan tentang struktur dan dinamika pasar saham Indonesia, serta mengidentifikasi sektor dan perusahaan kunci yang mendominasi pasar.
