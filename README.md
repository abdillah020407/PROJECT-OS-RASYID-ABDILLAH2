# PROJECT-OS-RASYID-ABDILLAH2
#TUGAA PROYEK
#LANGKAH IMPLEMENTASI

LANGKAH 2 STRUKTUR PROYEK
[Deskripsi Gambar]
https://drive.google.com/file/d/1ueaMfqmx83hh3ZUNDxSF4I9vvJpiq7nc/view?usp=drivesdk

#Penjelasan Perintah

1.pwd

● Perintah ini digunakan untuk   menampilkan direktori kerja saat ini (Print Working Directory).

● Output:
```
/home/rasyidabdillahalhasni yang menandakan user sedang berada di direktori home bernama "rasyidabdillahalhasni".
```
2.ls

● Perintah untuk menampilkan daftar file dan folder di dalam direktori saat ini.

● Output menampilkan beberapa direktori seperti Desktop, Documents, Downloads, Music, Pictures, Public, snap, Templates, Videos.

3.sudo apt-get update

● Perintah ini digunakan untuk memperbarui daftar paket dari repository yang sudah dikonfigurasi pada sistem Ubuntu.

● sudo digunakan agar perintah dijalankan dengan hak akses administrator (root).

● Setelah memasukkan password, sistem mulai mencari dan mengunduh file daftar paket baru dari server Ubuntu.
Proses ini mengambil metadata dan informasi terbaru dari berbagai sumber software repository Ubuntu.

● Terdapat beberapa output Get, Hit, dan beberapa error seperti "No such file or directory" yang menandakan ada sumber repo dari CD-ROM yang tidak ditemukan.

● Walaupun ada error, proses tetap berjalan dan berhasil mengakses repository online Ubuntu.

Fungsi Umum Perintah di Atas:

○ pwd: Fungsinya yaitu memastikan di direktori mana user berada.

○ ls: Fungsinya yaitu melihat isi  folder saat ini.

○ sudo apt-get update: Fungsinya yaitu mengupdate daftar paket supaya sistem tahu versi terbaru perangkat lunak yang tersedia untuk diinstall/upgrade.

[Deskripsi Gambar]
https://drive.google.com/file/d/1gx-h7Mf68w2XVeQGTNbe-dauLWyntiq7/view?usp=drivesdk

Detail Perintah dan Output
1.Perintah
```
sudo apt instal tree
```
Fungsi

●sudo
Berarti “superuser do”. Digunakan untuk menjalankan perintah dengan hak akses administrator (root).

●apt
Merupakan manajer paket pada sistem berbasis Debian/Ubuntu. Digunakan untuk menginstal, memperbarui, atau menghapus paket perangkat lunak.

●install tree
Memberitahu apt untuk menginstal program bernama tree.
tree adalah utilitas command-line yang menampilkan struktur direktori dalam bentuk hierarki pohon.

```
tree
```
Fungsi
Menampilkan daftar isi direktori secara hierarki dalam bentuk pohon (tree view).

Output yang Dihasilkan
```
Abdillah
├── Abdillah_05301425018
├── Desktop
│   ├── computer.desktop
│   ├── lubuntu-manual.desktop
│   ├── network.desktop
│   ├── trash-can.desktop
│   └── user-home.desktop
├── Documents
├── Downloads
├── Music
├── Pictures
└── Project_Based_Learning
    ├── archives
    ├── documents
    ├── file10.txt
    ├── file11.jpg
    ├── file12.jpg
    ├── file13.jpg
    ├── file14.jpg
    ├── file15.jpg
    ├── file16.pdf
    ├── file17.pdf
    ├── file18.pdf
    ├── file19.log
    ├── file1.txt
    ├── file20.log
    ├── file2.txt
    ├── file3.txt
    ├── file4.txt
    ├── file5.txt
    └── file6.txt
```
https://drive.google.com/file/d/1N0E77s1No2sCBZqEb9I-wCpM-5bDCR-J/view?usp=drivesdk

Detail Perintah dan Output
Perintah
```
mkdir project_sistem_operasi_b
```
Fungsi:
Masuk ke direktori project_sistem_operasi_b yang baru dibuat.

mkdir src doc data

Fungsi:
Membuat tiga folder sekaligus bernama:
```
src → tempat menyimpan file program atau script
```
```
doc → tempat menyimpan dokumentasi
```
```
data → tempat menyimpan data proyek
```

tree
Fungsi:
Menampilkan struktur direktori dan file dalam bentuk pohon (tree view).

Output yang Dihasilkan
```
project_sistem_operasi_b
├── data
├── doc
├── readem.md
└── src
    └── main.sh
```
Melihat Ukuran Folder (du -h --max-depth=1)
Perintah
```
du -h --max-depth=1
```
Fungsi: 
Menampilkan ukuran masing-masing subdirektori langsung di dalam folder saat ini (maksimal kedalaman 1).

Output yang Dihasilkan
```
4.0K    ./src
4.0K    ./doc
4.0K    ./data
16K     .
```
Interpretasi:
°Setiap subfolder berukuran sekitar 4KB.
°Total keseluruhan folder (.) berukuran 16KB.
