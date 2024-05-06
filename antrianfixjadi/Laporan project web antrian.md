**Laporan Project UTS           Mata Kuliah: Pemrograman Web** 



|**Nama Kelompok** |Kelompok 3 |
| - | - |
|**Nama Project** |Aplikasi Manajemen Antrian |

**Anggota TIM** 



|**No** |**NIM** |**Nama** |**Tugas** |**Keterangan** |
| - | - | - | - | - |
|1 |312210481 |Muhamad Jati Wasesa |Gambaran,kebutuhan sistem |Ketua |
|2 |312210489 |Dimas Aditya Putranto |Rancangan Sistem |Anggota |
|3 |312210478 |Tatia Deswita Anggraeni |Mockup |Anggota |
||||||
**Laporan terdiri dari:** 

1. Gambaran Umum Sistem 
1. Kebutuhan Sistem 
   1. Functional (Use Case) 
   1. Non-Functional 
1. Rancangan Sistem 
1. Rancangan Basis Data (Data Model/ERD) 
1. Prototype (Desain Mockup/Figma) 
1. Hasil Akhir (Demo program) 

Lampirkan link github kolaborasi tim. **A.Gambaran Umum Sistem** 

Program antrian adalah program komputer yang dirancang untuk mengelola antrian data. Antrian adalah struktur data yang mengikuti prinsip First In, First Out (FIFO), di mana elemen yang pertama masuk adalah yang pertama keluar. Di sisi lain, sistem memberikan alat kepada petugas untuk memanggil nomor antrian secara efisien menggunakan suara. Aplikasi Antrian ini dibangun menggunakan bahasa pemrograman PHP Versi 8 dan database MySQL/MariaDB. Untuk berkomunikasi dengan database menggunakan MySQLi Extension dengan antarmuka Procedural. Desain tampilan aplikasi ini menggunakan framework CSS Bootstrap 5.

Berikut adalah beberapa fungsi utama dari program antrian: 

- **Menambahkan elemen ke antrian:** Fungsi ini menambahkan elemen baru ke bagian belakang antrian. 
- **Menghapus elemen dari antrian:** Fungsi ini menghapus elemen pertama dari antrian. 
- **Memeriksa elemen depan antrian:** Fungsi ini mengembalikan elemen pertama dalam antrian tanpa menghapusnya. 
- **Memeriksa apakah antrian kosong:** Fungsi ini mengembalikan nilai true jika antrian kosong, dan false jika antrian berisi elemen 

**Kebutuhan Sistem:** 

1. **Data Antrian:** 
- Memungkinkan penambahan, penghapusan, dan modifikasi data antrian.  
2. **Data Pelayanan:** 
- Memungkinkan penambahan, penghapusan, dan modifikasi data layanan.  
- Menghubungkan data layanan dengan data antrian. 
3. **Data Loket:** 
- Menyimpan informasi tentang loket layanan, termasuk nomor loket, status loket (tersedia, sibuk, dll.), 
- Memungkinkan penambahan, penghapusan, dan modifikasi data loket. 
- Menghubungkan data loket dengan data antrian untuk mengarahkan pelanggan ke loket yang tersedia. 

**Fitur Sistem:** 

- **Pendaftaran Antrian:**  
- Sistem akan memberikan nomor antrian kepada pelanggan. 
- **Pemanggilan Antrian:**  
- Sistem akan memanggil nomor antrian secara berurutan. 
- Sistem akan menampilkan informasi tentang antrian saat ini di layar monitor.  
- **Manajemen Pelayanan:**  
- Petugas dapat menandai antrian. 
- Sistem akan memperbarui data antrian secara otomatis. 

**Manfaat Sistem:** 

- **Meningkatkan Efisiensi:** Sistem ini dapat membantu mengurangi waktu tunggu pelanggan dan meningkatkan efisiensi proses antrian.  
- **Meningkatkan Kualitas Layanan:** Sistem ini dapat membantu meningkatkan kualitas layanan dengan memberikan informasi yang jelas kepada pelanggan dan melacak kinerja petugas.  
- **Meningkatkan Kepuasan Pelanggan:** Sistem ini dapat membantu meningkatkan kepuasan pelanggan dengan mengurangi frustrasi dan meningkatkan pengalaman antrian.  

  **B. Kebutuhan Sistem** 

1. **functional sistem (use case)** 

![](Aspose.Words.381b3444-b514-42e7-8697-1e99c8db93ba.001.jpeg)

![](Aspose.Words.381b3444-b514-42e7-8697-1e99c8db93ba.002.jpeg)

![](Aspose.Words.381b3444-b514-42e7-8697-1e99c8db93ba.003.png)

2. **Non functional** 

Analisis kebutuhan non-fungsional terdiri dari dua kategori: kebutuhan perangkat keras dan perangkat lunak. Tujuan perangkat keras adalah untuk membuat proses perancangan dan implementasi sistem ini lebih mudah. 

• Perangkat Lunak yang Dibutuhkan  

Analisis ini diperlukan untuk mengetahui spesifikasi minimum yang dibutuhkan untuk membangun sebuah software.  

*Tabel 1 Tabel Spesifikasi Perangkat Lunak* 



|No. |Software Pendukung |
| - | - |
|1\. |Visual Studio Code |
|2\. |Bahasa Program PHP,HTML,CSS,SQL |
|3\. |phpMyAdmin |
|4\. |XAMPP |
|5\. |Google Chrome |

- Kebutuhan Perangkat Keras 

  Kebutuhan spesifikasi minimum perangkat keras yang dibutuhkan oleh pengguna untuk menjalankan aplikasi dapat dilihat pada Tabel dibawah ini : 

  *Tabel 2 Kebutuhan Perangkat Keras Pengguna* 



|No. |Perangkat |
| - | - |
|1 |Speaker* |
|2 |TV LED |
|3 |Personal Computer (PC) |

3. **Rancangan Sistem** 
- Activity Diagram** 

![](Aspose.Words.381b3444-b514-42e7-8697-1e99c8db93ba.004.jpeg)

- Sequence Diagram 
- Devloyment Diagram 

![](Aspose.Words.381b3444-b514-42e7-8697-1e99c8db93ba.005.png)

4. **Rancangan Basis Data (ERD)** 

![](Aspose.Words.381b3444-b514-42e7-8697-1e99c8db93ba.006.png)

**C.Prototype (Desain Mockup/Figma Data Loket** 

![](Aspose.Words.381b3444-b514-42e7-8697-1e99c8db93ba.007.jpeg)

**Data Pelayanan** 

![](Aspose.Words.381b3444-b514-42e7-8697-1e99c8db93ba.008.jpeg)

**F.Hasil Demo** 

![](Aspose.Words.381b3444-b514-42e7-8697-1e99c8db93ba.009.jpeg)

![](Aspose.Words.381b3444-b514-42e7-8697-1e99c8db93ba.010.jpeg)

![](Aspose.Words.381b3444-b514-42e7-8697-1e99c8db93ba.011.jpeg)
