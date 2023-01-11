                     Penulis:Hilmy syaddad ramzy nurfauzan
                                    312210162 | TI22A1
                                         FAKULTAS TEKNIK
                       PROGRAM STUDI TEKNIK INFORMATIKA
             Dosen pengampu: Agung Nugroho,S.kom.,M.kom.

-	Buat package dan modul dengan struktur
-	![py1](https://user-images.githubusercontent.com/115677769/211516416-c8057a50-6005-4e37-81c6-2c0951b07add.png)

Untuk membuat Package Modul kita buka aplikasi PyCharm
![Screenshot (131)](https://user-images.githubusercontent.com/115677769/211516685-82c30b18-97d9-4a1c-a07d-a50a07f25ece.png)

•	Kemudian Pilih New > python package

![py3](https://user-images.githubusercontent.com/115677769/211519347-64a65599-2018-4bc2-b801-43b0e78b7a51.png)

" -> Kita buat Nama Model dan View "
![py4](https://user-images.githubusercontent.com/115677769/211519923-4b78dd47-1393-40dd-9086-2ca4643c3c72.png)
Tampilan folder Package Model dan View yang terdapat file_init_.py
![py5](https://user-images.githubusercontent.com/115677769/211520109-a3773e6b-eb34-4e8d-81ee-462c66daa565.png)

•	Kemudian kita buat nama program Python dengan Klik Folder Model > pilih New >Python File dengan nama : daftar_nilai.py

![py6](https://user-images.githubusercontent.com/115677769/211520274-478ded48-131b-4169-937c-da87f449355f.png)

•	Lalu kita buat nama program Python dengan Klik Folder view > pilih New >Python File dengan nama : input_nilai.py dan view_nilai.py

![py7](https://user-images.githubusercontent.com/115677769/211520421-4fe15a2c-6915-4cf8-a5db-c0682dedc5cd.png)
Nama program python sudah kita buat 
![py8](https://user-images.githubusercontent.com/115677769/211520531-11198ed6-44b6-4f75-bc69-0207087ecd33.png)


Buat sintaks program python
**Membuat kode program : daftar_nilai.py **

![Screenshot (125)](https://user-images.githubusercontent.com/115677769/211520765-fa365d42-12e8-4470-9699-86413fb71c53.png)
![Screenshot (126)](https://user-images.githubusercontent.com/115677769/211520824-2299f792-3be6-41f7-a34c-c1380c8c2a93.png)

Penjelasan :
•	Disini kita menggunakan kamus ya untuk menyimpan inputan data mahasiswa
•	Def tambahkan : Dibagian ini kita gunakan print untuk penulisan bagian input data mahasiswa nanti agar terlihat rapih
•	Def hapus :
•	Disini kita buat inputan yang menginput nama

o	Gunanya untuk menghapus data mahasiswa dari nama mahasiswa itu sendiri
o	Kita gunakan del untuk fungsi menghapus datanya
o	(Jika)Jika mahasiswa tersebut ada maka data mahasiswa tersebut akan terhapus
o	(Else)Jika nama mahasiswa tersebut tidak ada maka datanya tidak akan ditemukan
•	Def ubah
Penjelasan:

o	Disini kita hampir sama dengan yang hapus, kita gunakan inputan nama untuk mengubah NIM, Nilai Tugas, Ujian Tengah Semester(UTS), ataupun Ujian Akhir Semester(UAS)
o	Lalu setelah kita memasukkan nama maka dictionary akan mengeksekusi program menggunakan keys untuk mencari data dari nama mahasiswa tersebut
o	(Jika)Jika nama mahasiswa tersebut ketemu atau ada didalam data maka program akan masuk ke inputan NIM, Nilai Tugas, Nilai UTS, dan Nilai UAS yang baru
o	(Else)Jika nama mahasiswa tersebut tidak ada didalam data maka program akan memunculkan tulisan atau perintah bahwa data mahasiswa tidak ada
•	Def cari
Penjelasan:

o	Fungsinya sama dengan tambahkan Def

**Membuat kode program input_nilai.py **

![Screenshot (127)](https://user-images.githubusercontent.com/115677769/211521535-9ae76824-7e11-4474-901f-38bd151f07e6.png)

Penjelasan:
•	Dari dan impor
Penjelasan:

o	From digunakan untuk memanggil package temporary import untuk tujuan yang kita pilih yaitu modul daftar_nilai
o	Lalu kita gunakan import data_mahasiswa itu gunanya agar saat kita menginputkan data atau setiap kali kita menambah data maka data mahasiswa secara otomatis akan masuk ke dalam dictionary meskipun berbeda atau paket terpisah dan juga modulnya
o	Def tambah data
Penjelasan:
	Disini kita buat inputan karena tadi kita sudah membuat kata - kata outputnya kali ini kita cukup membuat inputan data mahasiswanya saja
	Jangan lupa gunakan penambahan untuk menghitunghasil total atau rata- ratanya


**Membuat kode program view_nilai.py **

![Screenshot (128)](https://user-images.githubusercontent.com/115677769/211521763-bb36a94a-6fc0-4c13-8ee1-8f131b073a5a.png)
![Screenshot (129)](https://user-images.githubusercontent.com/115677769/211521790-7731e203-8d8e-40d9-81a7-91f9d5ba8ba3.png)

Penjelasan:
•	Dari dan impor
Penjelasan:

o	Fungsinya sama saja dengan yang ada dibagian Input_Nilai
o	Def tampil
Penjelasan:
	Disini kita buat sebuah tabel untuk menampilkan data - data dan nama - nama mahasiswa didalam kamus
	(Jika)Jika terdapat data maka data dan nama mahasiswa tersebut akan muncul
	Disini kita menggunakan for untuk melakukan perulangan nomor urut
	(Else)Jika kita belum menginputkan data sama sekali maka akan muncul tulisan "tidak ada data"
o	Def mencari data
Penjelasan:
	Tadi kita sudah buat print sama seperti dibagian Input_Nilai
	Kita akan langsung membuat inputan dengan format nama untuk mencari data dari mahasiswa yang sedang kita cari
	(If)Jika data mahasiswa yang dicari ada didalam kamus maka data baik Nama, NIM, Nilai Tugas, Nilai UTS, dan Nilai UAS akan muncul
	(Else)Jika data mahasiswa yang dicari tidak ada didalam kamus maka akan muncul tulisan "datanya tidak ada"

**Membuat kode program : main.py **

![Screenshot (130)](https://user-images.githubusercontent.com/115677769/211521996-03febead-8afa-49aa-88e1-a2539d9d53af.png)


•	Dari dan impor
Penjelasan:

o	Sama seperti sebelumnya hanya disini saja sedikit berbeda
o	Dari sini kita tulis package.modulnya lalu import fungsi(def) tadi
o	Karena dibagian utama ini kita akan menggunakan atau membuat menu pilihan sintaks
o	Sementara Benar
Penjelasan:
	Kita gunakan print untuk membuat pilihan menunya
	Lalu kita buat inputan untuk memilih menu nanti ketika program dijalankan
	(If dan Elif)Kita gunakan karena kita akan membuat cabang pilihan yang banyak
	Lalu dibawahnya kita tambahkan juga fungsi - fungsi yang sudah kita buat tadi
	Pada perintah ke 6 kita gunakan break untuk keluar dari program yang kita jalankan
	(Else)Jika kita tidak memilih salah satu menu tersebut maka akan muncul peringatan "pilih menu yang tersedia diatas"


Menjalankan program python
•	Untuk menjalankan program kita klik : Run > main.py
•	Pilih Menu Nomor : 1. Tambah

![hilmy1](https://user-images.githubusercontent.com/115677769/211719704-3a50a33e-4248-4c62-ab6e-6460627898c3.png)
![hilmy2](https://user-images.githubusercontent.com/115677769/211719715-fc2230a0-cf0a-45b6-8bd9-031209f59c17.png)
![hilmy3](https://user-images.githubusercontent.com/115677769/211719726-aff68870-8963-4a68-8041-43cda8c406c1.png)
![hilmy4](https://user-images.githubusercontent.com/115677769/211719740-6afc1270-720b-4800-8e97-82c8f89bcf3d.png)
![hilmy5](https://user-images.githubusercontent.com/115677769/211719753-faae4630-a8db-4daf-8cf7-b5f7bcbfd234.png)
![hilmy6](https://user-images.githubusercontent.com/115677769/211719781-6435f921-227d-45e5-bbdd-f63df4debeec.png)
![hilmy7](https://user-images.githubusercontent.com/115677769/211719802-57522b46-9819-4de1-9b69-4a7cb8a71ff2.png)
![hilmy8](https://user-images.githubusercontent.com/115677769/211719821-81340f07-b8f9-4f47-974a-a114dc32a448.png)
![hilmy9](https://user-images.githubusercontent.com/115677769/211719844-ce32390b-ac91-4c25-b2f7-afa49cd7d611.png)
![hilmy10](https://user-images.githubusercontent.com/115677769/211719856-0564325f-7c47-40da-816d-884aa63f4792.png)
untuk penjelasan lebih lanjut bisa klik link dibawah

https://youtu.be/7i3KAGyHAAo









