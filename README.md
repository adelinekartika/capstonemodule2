# capstonemodule2
Capstone Module 2: Data Analysis
Airbnb Listings Bangkok

Dibuat Oleh: Adeline Kartika Tiku Putri (JCDSOL-013 Kelas 02)

## Latar Belakang
Airbnb adalah platform penyewaan akomodasi jangka pendek yang populer, memungkinkan tuan rumah menyewakan properti mereka kepada tamu dari seluruh dunia. Sementara itu, para tamu dapat menemukan pilihan akomodasi yang lebih fleksibel, terjangkau, dan seringkali lebih personal daripada hotel tradisional. Dengan jutaan daftar di berbagai destinasi, Airbnb telah menjadi salah satu opsi populer bagi wisatawan yang mencari pengalaman menginap yang unik dan berbeda. Pada tahun 2023, Thailand menjadi destinasi paling banyak dikunjungi di Asia Tenggara di Airbnb, dengan jumlah malam menginap meningkat sebesar 60% dari tahun sebelumnya. Sumber: [bangkokpost](https://www.bangkokpost.com/business/general/2771814/airbnb-registers-focus-on-local-experiences). Di Bangkok, Airbnb saat ini sedang berkembang pesat dengan beragam properti seperti apartemen, vila, dan rumah tradisional. Harga bersaing dan keterlibatan lokal menjadi daya tariknya. Meski demikian, Airbnb dihadapkan pada tantangan regulasi.

Sebagai seorang *data analyst* yang sedang bekerja untuk sebuah perusahaan yang mengelola platform Airbnb di Bangkok, mereka ingin meningkatkan efektivitas dan kinerja platform Airbnb di Bangkok dengan memahami kondisi aktual platform serta menganalisis popularitas dan ketersediaan properti untuk mengoptimalkan strategi penyewaan dan meningkatkan pengalaman pengguna.

## Stakeholder
Ditujukan untuk perusahaan pemilik Platform Airbnb yang terdiri dari **tim data** dan **tim manajemen properti** dimana mereka tertarik untuk memahami kinerja platform Airbnb mereka saat ini guna meningkatkan pengalaman pengguna, mengoptimalkan fungsionalitas platform dan properti Airbnb di Bangkok.

## Pernyataan Masalah dan Jawaban Berdasarkan Hasil Analisis Data
**Tujuan utama adalah meningkatkan efektivitas dan kinerja platform Airbnb di Bangkok dengan memahami kondisi aktual platform serta menganalisis popularitas dan ketersediaan properti untuk mengoptimalkan startegi penyewaan dan meningkatkan pengalaman pengguna.**

Sebagai seorang *data analyst*, kita akan mencoba menjawab pertanyaan berikut:

1. Ketersediaan properti dan popularitas pengguna per daerah:
- Bagaimana pemetaan jumlah Airbnb berdasarkan daerah di Bangkok?
  - Vadhana, Khlong Toei, Ratchathewi, Huai Khwang, Bang Ra secara berurutan menjadi daerah dengan jumlah Airbnb terbanyak di Bangkok.
  - Terlihat adanya tren peningkatan jumlah Airbnb seiring semakin mendekatnya lokasi properti ke pusat kota.
- Apa daerah yang paling populer di kalangan penyewa Airbnb?
  - Khlong Toei, Vadhana, Sathon, Ratchathewi, Huai Khwang menjadi daerah paling populer berdasarkan jumlah review.
  - Terlihat adanya tren peningkatan popularitas Airbnb seiring semakin mendekatnya lokasi properti ke pusat kota. Tren peningkatan popularitas Airbnb seiring dengan mendekatnya lokasi properti ke pusat kota dapat dijelaskan dengan berbagai faktor. Salah satunya adalah preferensi banyak penyewa Airbnb yang lebih memilih tinggal di daerah yang lebih dekat dengan pusat kota. Selain itu, kemungkinan faktor aksesibilitas dan kenyamanan juga turut memengaruhi, di mana lokasi yang lebih dekat dengan pusat kota biasanya memiliki akses yang lebih mudah ke fasilitas umum dan tempat-tempat wisata. Di Bangkok, fasilitas transportasi seperti Bangkok Rail Transit (BRT) berada di pusat kota.
  - Jumlah ulasan dapat memberikan indikasi berapa banyak pengguna Airbnb yang menginap atau mengunjungi suatu tempat. Jika suatu daerah atau properti memiliki jumlah ulasan yang tinggi, ini dapat menunjukkan bahwa tempat tersebut cukup populer di kalangan pengguna Airbnb.
- Apakah ada korelasi antara harga Airbnb dengan kepopuleran dari lokasi Airbnb?
  Berdasarkan hasil korelasi sebesar 0.4, dapat dikatakan antara jumlah review dengan harga sewa memiliki *moderate positive correlation*. Artinya semakin tinggi jumlah review yang diterima, maka harga sewa properti tersebut juga akan meningkat meskipun tidak dalam tingkat yang sangat kuat. Dengan demikian, kita bisa mengamati bahwa popularitas properti Airbnb, yang tercermin dari jumlah review, berpengaruh sedang terhadap harga sewanya.
2. Ketersediaan dan permintaan berdasarkan tipe kamar:
- Apa jenis kamar yang paling banyak tersedia di Airbnb Bangkok?
  Tipe kamar yang paling banyak pada plaform Airbnb tersebut adalah *Entire home/apt*, dengan persentase sebesar 57%, diikuti oleh *private room*, *hotel room*, dan *shared room*.
- Apa tipe kamar yang paling populer di kalangan penyewa Airbnb?
  Tipe kamar yang paling populer berdasarkan jumlah review adalah *Entire home/apt* hampir 200 ribu ulasan. Angka ini hampir 4 kali lipat tipe kamar terpopuler kedua yaitu *Private room* dengan jumlah ulasan hampir 50 ribu ulasan.
- Apakah ketersediaan kamar sudah memenuhi permintaan/kepopuleran pasar?
  - Permintaan atau popularitas pasar direpresentasikan dengan jumlah ulasan, di mana tipe kamar yang paling populer adalah Entire home, diikuti oleh private room, hotel room, dan shared room. Namun, dalam hal ketersediaan kamar selama 365 hari ke depan, terlihat bahwa Entire home sudah banyak dipesan oleh pengguna Airbnb karena ketersediaannya yang lebih rendah dibandingkan dengan tipe kamar lainnya.
  - Secara keseluruhan, masih banyak kamar yang tersedia untuk disewa yang menandakan perlunya strategi untuk meningkatkan penjualan.
- Bagaimana pola harga Airbnb berdasarkan tipe kamar?
  Berdasarkan rata-rata harga, tipe kamar hotel room memiliki harga sewa yang paling mahal diikuti oleh entire home, private room, dan shared room. Hal ini mungkin disebabkan karena adanya pelayanan lebih yang diberikan oleh tipe kamar hotel.
3. Tentang Performa Host dan portfolio Host:
- Bagaimana efektivitas penggunaan platform Airbnb oleh host?
   Dari 10 host teratas, distribusi properti mereka tergolong merata, walaupun ada beberapa host yang memiliki jumlah properti yang lebih tinggi. Salah satu host teratas, Curry, telah memasukkan lebih dari 200 properti ke dalam platform Airbnb. Sementara itu, Noons memiliki hampir 100 properti, dan 8 host teratas lainnya mendaftarkan sekitar 75 properti. Fenomena ini menandakan tingkat kepercayaan yang tinggi terhadap platform Airbnb oleh para host, sehingga mereka merasa yakin dan nyaman untuk memasukkan sejumlah besar properti ke dalam platform Airbnb perusahaan. Berdasarkan plot, ternyata memiliki banyak properti yang disewakan tidak menjamin popularitas. Dapat dilihat dari sisi sebelah kiri bahwa untuk host dengan jumlah properti terbanyak, rata-rata ulasan per properti hanya sekitar 33 ulasan per properti. Sementara itu, pada rata-rata ulasan per properti tertinggi yang terlihat di visualisasi sebelah kanan, mencapai 1200 ulasan per properti. Hal ini menunjukkan perlunya tinjauan yang lebih mendalam. Salah satu langkah yang dapat dilakukan adalah dengan menambahkan kolom baru seperti fasilitas yang disediakan, komentar dari pengguna, dan penilaian dari 1 hingga 5 oleh pengguna sehingga tidak hanya mengetahui popularitas tetapi juga tingkat kepuasan pengguna. Dengan penambahan data tersebut memungkinkan untuk melakukan perbandingan antara pemilik Airbnb secara mendalam dan meningkatkan pendapatan mereka.
- Apa tren atau pola tertentu dalam penamaan Airbnb?
  Berdasarkan 25 kata yang sering digunakan oleh para Host untuk menamai Airbnb mereka, terlihat sebuah tren yang jelas yaitu Host menggunakan istilah yang spesifik untuk memudahkan pencarian oleh calon pengguna Airbnb. Kata-kata seperti bts (Bangkok Transit Station) untuk mempromosikan Airbnb mereka dekat dengan transportasi publik, kemudian room, near, bangkok, condo, hal ini sangat umum untuk digunakan. Secara sederhana Host menjelaskan kondisi/lokasi Airbnb yang mereka sewakan.

## Kesimpulan

Dari analisis yang telah dilakukan, kita bisa membuat kesimpulan sebagai berikut:
1. Ketersediaan properti dan popularitas pengguna per Daerah:
* Daerah-daerah seperti Vadhana dan Khlong Toei memiliki jumlah Airbnb terbanyak dan daerah populer berdasarkan jumlah review di Bangkok.
* Tren peningkatan popularitas, jumlah, dan harga sewa Airbnb terjadi di daerah yang semakin mendekat ke pusat kota. Dikarenakan merupakan lokasi yang strategis.

2. Analisis Tipe Kamar dan Harga:
* Entire home/apartment menjadi tipe kamar paling banyak (57%), terpopuler berdasarkan jumlah ulasan, dan paling sedikit ketersediaannya namun bukan yang termahal.
* Hotel room merupakan tipe kamar yang paling sering dibooking setelah entire room, meskipun jumlahnya tidak sebanyak entire room, memiliki ulasan yang tidak terlalu banyak, dan harganya paling tinggi.
* Shared room memiliki kinerja yang kurang optimal meskipun memiliki harga yang paling terjangkau.

3. Host dan portfolio Airbnb Host:
* Banyak host yang sudah mempercayakan properti untuk disewakan di platform airbnb milik perusahaan hingga 200 properti.
* Banyak properti yang disewakan tidak menjamin popularitas per properti.
* Kata-kata yang sering digunakan untuk menamai Airbnb seperti bts, room, near adalah jenis kata yang umum dan menjelaskan kondisi Airbnb host sehingga memudahkan pencarian oleh calon pengguna Airbnb.


## Rekomendasi

1. Strategi Pemasaran Berbasis Data:
* Menggunakan data popularitas dan harga, Airbnb dapat mengoptimalkan strategi pemasaran di daerah-daerah yang populer untuk meningkatkan pendapatan.
* Menyediakan informasi yang lebih detail tentang fasilitas, komentar pengguna, dan rating akan membantu pengguna membuat keputusan yang lebih baik dan meningkatkan kepuasan.

2. Peninjauan Strategi Harga:
* Daerah dengan harga sewa yang tinggi namun tidak terlalu populer dapat diperhatikan lebih lanjut untuk meninjau kembali strategi harga dan menarik lebih banyak penyewa.
* Pusatkan perhatian pada tipe kamar yang paling populer untuk meningkatkan ketersediaan dan kepuasan pelanggan.

3. Pengembangan Platform:
* Melakukan pembaruan platform Airbnb dengan informasi lebih detail tentang tipe kamar dan daerah, serta memfasilitasi pemilik properti untuk menambahkan informasi yang lebih komprehensif.
* Dapat memberikan contoh opsi penamaan Airbnb kepada Host baru saat melakukan pendaftaran.
* Memperbaiki sistem penambahan/pembaharuan data lebih baik lagi agar tidak terjadi data duplikat.
* Memperkuat analisis data untuk memberikan wawasan yang lebih dalam tentang preferensi dan kebutuhan pengguna Airbnb di Bangkok.
