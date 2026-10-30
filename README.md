# Klasifikasi untuk penyaringan prioritas verifikasi lapangan melalui prediksi tingkat kepercayaan (confidence level) titik panas berdasarkan karakteristik termal dan waktu kejadian di Indonesia (Januari–Oktober 2026)

## Nomor Kelompok  : 6
## Nama Kelompok   : Prediksi Cuaca Cerah Tapi Berasap

## Anggota Kelompok
| NIM | Nama | Kelas Teori | Kelas Praktikum |
|----|------|-----|-------|
| 123240195  | Indra Naufal Firdaus | IF-A | IF-D |
| 123240206  | Rio Adhi Permana | IF-A | IF-E |
| 123240209  | Achmad Daud Ashshidieqiya | IF-A | IF-F |
| 123240250  | Candra Aji Ramadhan | IF-A | IF-G |

## Latar Belakang / Permasalahan
Kebakaran hutan dan lahan merupakan permasalahan lingkungan yang membutuhkan pemantauan dan penanganan secara tepat waktu. Salah satu sumber informasi yang digunakan untuk mendeteksi potensi kebakaran adalah data titik panas (hotspot) dari penginderaan jauh satelit. Namun, tidak semua hotspot yang terdeteksi menunjukkan adanya kebakaran karena titik panas juga dapat berasal dari aktivitas industri, pembakaran lahan, maupun sumber panas lainnya. Banyaknya hotspot yang tersebar di berbagai wilayah, ditambah keterbatasan petugas, waktu, dan biaya operasional, menjadi kendala dalam menentukan titik yang perlu diprioritaskan untuk verifikasi lapangan.

## Solusi
Mengembangkan model klasifikasi confidence level hotspot menggunakan algoritma machine learning berdasarkan karakteristik termal, seperti brightness, bright_t31, Fire Radiative Power (FRP), serta waktu kejadian. Model ini bertujuan mengelompokkan hotspot ke dalam kategori rendah (Low), sedang (Nominal), dan tinggi (High) untuk membantu proses penyaringan awal dan penentuan prioritas pemeriksaan. Dengan demikian, hasil klasifikasi diharapkan dapat memberikan informasi yang lebih terstruktur bagi petugas dan instansi terkait dalam mendukung kegiatan pemantauan serta pengambilan keputusan. Hasil prediksi tetap menjadi informasi pendukung dan tidak menggantikan verifikasi langsung di lapangan.
