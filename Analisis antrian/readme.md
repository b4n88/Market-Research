<h1 align = 'center'> Analisis antrian</h1>

Analisa ini bisa digunakan dalam konteks apapun, rumah sakit, Pelayanan telephone, Bank dan lain lain.

Data yang Dibutuhkan untuk Analisis Antrian :
  
## Dataset yang Dibutuhkan untuk Analisis Antrian di Rumah Sakit

| **Kolom Data**           | **Deskripsi**                                                  | **Tipe Data** |
|---------------------------|---------------------------------------------------------------|--------------|
| **Tanggal**              | Tanggal kunjungan pasien                                      | Date         |
| **Waktu_Kedatangan**     | Waktu pasien datang di loket/resepsionis                      | Time         |
| **Waktu_Pelayanan_Mulai**| Waktu pelayanan dimulai                                       | Time         |
| **Waktu_Pelayanan_Selesai**| Waktu pelayanan selesai                                     | Time         |
| **Jenis_Layanan**        | Jenis pelayanan (Poli Umum, Poli Gigi, IGD, dsb.)             | Categorical  |
| **Durasi_Pelayanan**     | Lama waktu pelayanan (menit)                                  | Numeric      |
| **Jumlah_Atasan**        | Jumlah dokter di layanan tersebut                            | Numeric      |
| **Jumlah_Karyawan**       | Jumlah perawat di layanan tersebut                           | Numeric      |
| **Prioritas_Pasien**     | Tingkat prioritas pasien (Darurat, Umum, Lansia, Anak)        | Categorical  |
| **Status_Antrian**       | Selesai, Menunggu, Dibatalkan                                | Categorical  |
| **Waktu_Tunggu**         | Lama waktu pasien menunggu sebelum dilayani (menit)          | Numeric      |
| **Jumlah_Pasien_Harian** | Total pasien yang dilayani per hari                          | Numeric      |
| **Feedback_Pasien**      | Kepuasan pasien (Sangat Puas, Puas, Biasa, Tidak Puas)        | Categorical  |

# Analisis Antrian
## Teori Antrian

1. Single Server Model (M/M/1) : Satu loker / Satu pelayanan
2. Multi - Server Model (M/M/C) : Beberapa loket pelayanan yang melayani antrian bersama
3. Priority Queue : Antrian berdasarkan prioritas.

## Simulasi Antrian

- Simulasi Montecarlo atau simulasi diskrit
- Membuat simulasi untuk memprediksi dampak penambahan loket

## Analisis Bottleneck (Titik Macet)

Identifikasi di bagian mana waktu tunggu tertinggi dan pelayanan paling lambat.

# Insight yang Dibutuhkan
- Efisiensi Pelayanan:
  > Loket atau poli mana yang paling memiliki waktu tunggu lama
  > Identifikasi jam sibuk untuk menambah tenaga medis atau loket.

- Optimisasi Sumber daya
- Pelayanan ala CS BCA kliling
  Melakukan penawaran terhadap antrian yg tidak terlalu butuh CS atau yang bisa diselesaikan tanpa CS bisa dilakukan penawaran keliling.
- Analisis Prioritas
- Rekomendasi Strategis
  > Sitem antrian digital
  > Jadwal janji temu lebih efektif
  > Dashboard daftar antrian (masukan antrian baru dan total antrian yang akan mengantri)
  



