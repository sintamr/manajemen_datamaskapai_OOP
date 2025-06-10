# 🛫 **Object Oriented Programming (OOP) dalam Manajemen Data Maskapai Penerbangan**
*Sebuah Simulasi Sistem Manajemen Data Maskapai Penerbangan Berbasis OOP*

Oleh : **Sinta Miftakhul Rohmah**

<p align="center">
  <img src="Images1.jpg" width="849"><br>
  <sub>
    Photo by <a href="[https://unsplash.com/@jack19992011?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Markus Spiske</a> on <a href="https://unsplash.com/photos/a-grocery-store-aisle-filled-with-lots-of-food-IH65r4HEQWQ?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash](https://unsplash.com/photos/text-jG8nlwLRZTM)">Unsplash</a>
  </sub>
</p>

# 🧾 Deskripsi Singkat
Manajemen Data Maskapai di sini adalah sebuah program simulasi sederhana yang dirancang menggunakan konsep **Object Oriented  Programming (OOP)** 
untuk mengelola informasi penerbangan. Sistem ini dapat menyimpan dan menampilkan detail penerbangan seperti maskapai, jadwal keberangkatan, durasi, jumlah transit, serta informasi tambahan.
Program ini juga menerapkan *inheritance* (pewarisan) dan *encapsulation* (enkapsulasi) untuk menunjukkan praktik desain perangkat lunak yang baik.

# 🧱 Konsep Pemrograman yang Digunakan
1.   **Class dan Object**

     Program dibangun menggunakan kelas `Penerbangan` yang berfungsi sebagai cetakan untuk setiap data penerbangan. Setiap objek mewakili satu penerbangan.
2.   **Inheritance (Pewarisan)**

     Subclass `Detail_Info` mewarisi atribut dan metode dari Penerbangan, serta menambahkan fitur tambahan seperti jenis penerbangan (domestik atau internasional).
3.   **Encapsulation (Enkapsulasi)**

      Atribut `__Price` disembunyikan (private) agar tidak diakses langsung dari luar kelas. Untuk mengaksesnya, digunakan metode getter dan setter yang aman.
     
# 🎯 Tujuan Program

1. Menerapkan konsep Object Oriented Programming (OOP) dalam studi kasus penerbangan.
2. Mensimulasikan sistem informasi penerbangan yang terdiri atas beberapa komponen dan mudah dikembangkan.
3. Melatih penggunaan `inheriritance` (pewarisan) dan `encapsulation` (enkapsulasi) dalam Python.
4. Menyediakan struktur data penerbangan yang rapi dan terorganisir untuk analisis atau pengembangan selanjutnya (misalnya integrasi ke Database).

# 🧩 Komponen Isi
Sebelum membuat program, komponen yang akan digunakan sebagai variabel dalam program adalah sebagai berikut :

| Komponen          | Keterangan                           |
| ----------------- | ------------------------------------ |
| `index`           | Indeks baris                         |
| `Airline`         | Nama maskapai                        |
| `Date_of_Journey` | Tanggal keberangkatan (objek string) |
| `Source`          | Kota asal                            |
| `Destination`     | Kota tujuan                          |
| `Dep_Time`        | Waktu berangkat (string)             |
| `Duration`        | Durasi penerbangan (string)          |
| `Total_Stops`     | Jumlah transit                       |
| `Additional_Info` | Info tambahan (makanan, dll)         |
| `CrewInfo`        | Informasi Crew yang bertugas         |

## 🧱 Object Oriented Programming (OOP) ~ Class : `Penerbangan`

Dalam dunia pemrograman berorientasi objek atau OOP, kita dapat merepresentasikan entitas nyata dalam bentuk class yang berisi atribut dan metode. 
Misalnya, sebuah `penerbangan` yang biasanya memiliki data seperti nomor penerbangan, asal, tujuan, jadwal keberangkatan, dan lain-lain. 
Data-data tersebut akan dikelola secara terstruktur dengan memanfaatkan kelas `penerbangan` yang akan dibuat. Lebih lengkapnya sebagai berikut :

**SuperClass**
<p align="center">
  <img src="Informasi Penerbangan.PNG" width="400"><br>
</p>

**SubClass**

Pada subclass ini, penerapan konsep pewarisan atau Inheritance dilakukan yang bersumber pada SuperClass. Diperoleh hasil sebagai berikut :
<p align="center">
  <img src="Informasi Penerbangan dengan Inheritance.PNG" width="400"><br>
</p>

Selanjutnya adalah pengecekan terhadap konsep encapsulated. Konsep ini digunakan untuk menyimpan data yang bersifat privat atau rahasia.
Pada konteks kasus penerbangan ini adalah informasi data diri petugas (CrewInfo).
<p align="center">
  <img src="Encapsulated Output.PNG" width="400"><br>
</p>
Berdasarkan hasil di atas, terbukti bahwa informasi petugas berhasil disembunyikan. Terlihat ketika informasi tersebut diminta, program menampilkan pesan error yang membuat
spekulasi bahwa data mengenai petugas tidak ada atau tidak dimuat dalam program.

## 🛠️ Dibuat dengan

- **Python**

## 📑 Data
Data yang diinputkan hanyalah data rekayasa untuk mencoba apakah program dapat berjalan seperti yang diinginkan.

## 👩‍💻 Penulis

**Sinta Miftakhul Rohmah**  
Mahasiswa Matematika Terapan  
Universitas Islam Negeri Sunan Kalijaga, Yogyakarta  
📫 [LinkedIn](https://www.linkedin.com/in/sintamiftakhulr/)

