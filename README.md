# Jarkom-Modul-1-ITB04-2022

Pengerjaan Soal Shift Komunikasi Data dan Jaringan Komputer Modul 1 oleh ITB04

# Anggota

| Nama                           | NRP          | 
| -------------------------------| -------------| 
| Nadine Haninta                 | `5027201014` | 
| Maulanal Fatihil A. M          | `5027201031` | 
| Dzaki Indra Cahya              | `5027201053` |

# Konten
* [Sumber Soal dan Resource Praktikum Komunikasi Data dan Jaringan Komputer Modul 1 Tahun 2022](#sumber-soal-dan-resource-praktikum-komunikasi-data-dan-jaringan-komputer-modul-1-tahun-2022)
    * [Sumber Soal](#symber-soal)
    * [Resource Soal Praktikum]()
* [Soal 1](#soal-1)
    * [Jawaban Soal 1](#jawaban-soal-1)
    * [Penyelesaian dan Dokumentasi Soal 1](#penyelesaian-dan-dokumentasi-soal-1)
    * [Kendala Soal 1](#kendala-soal-1)
* [Soal 2](#soal-1)
    * [Jawaban Soal 2](#jawaban-soal-2)
    * [Penyelesaian dan Dokumentasi Soal 2](#penyelesaian-dan-dokumentasi-soal-2)
    * [Kendala Soal 2](#kendala-soal-2)
* [Soal 3](#soal-3)
    * [Jawaban Soal 3](#jawaban-soal-3)
    * [Penyelesaian dan Dokumentasi Soal 3](#penyelesaian-dan-dokumentasi-soal-3)
    * [Kendala Soal 3](#kendala-soal-3)
* [Soal 4](#soal-4)
    * [Jawaban Soal 4](#jawaban-soal-4)
    * [Penyelesaian dan Dokumentasi Soal 4](#penyelesaian-dan-dokumentasi-soal-4)
    * [Kendala Soal 4](#kendala-soal-4)
* [Soal 5](#soal-5)
    * [Jawaban Soal 5](#jawaban-soal-5)
    * [Penyelesaian dan Dokumentasi Soal 5](#penyelesaian-dan-dokumentasi-soal-5)
    * [Kendala Soal 5](#kendala-soal-5)
* [Soal 6](#soal-6)
    * [Jawaban Soal 6](#jawaban-soal-6)
    * [Penyelesaian dan Dokumentasi Soal 6](#penyelesaian-dan-dokumentasi-soal-6)
    * [Kendala Soal 6](#kendala-soal-6)
* [Soal 7](#soal-7)
    * [Jawaban Soal 7](#jawaban-soal-7)
    * [Penyelesaian dan Dokumentasi Soal 7](#penyelesaian-dan-dokumentasi-soal-7)
    * [Kendala Soal 7](#kendala-soal-7)
* [Soal 8](#soal-8)
    * [Jawaban Soal 8](#jawaban-soal-8)
    * [Penyelesaian dan Dokumentasi Soal 8](#penyelesaian-dan-dokumentasi-soal-8)
    * [Kendala Soal 8](#kendala-soal-8)
* [Soal 9](#soal-9)
    * [Jawaban Soal 9](#jawaban-soal-9)
    * [Penyelesaian dan Dokumentasi Soal 9](#penyelesaian-dan-dokumentasi-soal-9)
    * [Kendala Soal 9](#kendala-soal-9)
* [Soal 10](#soal-10)
    * [Jawaban Soal 10](#jawaban-soal-10)
    * [Penyelesaian dan Dokumentasi Soal 10](#penyelesaian-dan-dokumentasi-soal-10)
    * [Kendala Soal 10](#kendala-soal-10)

## Sumber Soal dan Resource Praktikum Komunikasi Data dan Jaringan Komputer Modul 1 Tahun 2022
Adapun untuk soal dan _resource_ yang digunakan dalam praktikum 1
### Symber Soal
Sebagai berikut adalah soal yang digunakan dalam praktikum,
[Sumber Soal](https://docs.google.com/document/d/1e5fXdleV59vFthVeK0O5WfmuOYV6xi6WkpHsZEiBofE/edit?usp=sharing)
### Resource Soal
Sebagai berikut adalah resource yang digunakan dalam praktikum 1,
[Resource Praktikum](https://drive.google.com/drive/folders/1mj1IKV1_NPWtz7AcIytw4DK8vC9fZ1Ox)

## Soal 1
Sebutkan web server yang digunakan pada "monta.if.its.ac.id"! 

### Jawaban Soal 1
Nginx

### Penyelesaian dan Dokumentasi Soal 1
1) Mengunduh _file_ `soal1-2.pcapng` dari tautan resource <br>
2) Membuka program Wireshark untuk menganalisis _file_ yang didapatkan <br>
3) Dilakukan filter `http` pada Wireshark. <br>
![ProsesFilter](/image/Soal1-a.PNG) <br>
4) Menelusuri paket yang didapatkan dengan melakukan klik kanan pada salah satu dan memilih "Follow HTTP"
![FollowHTTP](/image/Soal1-b.PNG) <br>
5) Melakukan pelacakan terhadap hasil pada nomor sebelumnya, di mana pada kasus ini dicari "Server" untuk mengetahui server yang digunakan oleh monta.
![WebServer](/image/Soal1-c.PNG)<br>

### Kendala Soal 1
Tidak ada

## Soal 2
Ishaq sedang bingung mencari topik ta untuk semester ini , lalu ia datang ke website monta dan menemukan detail topik pada website “monta.if.its.ac.id” , judul TA apa yang dibuka oleh ishaq ?

### Jawaban Soal 2
Topik Tugas Akhir: Evaluasi Unjuk Kerja User Space Filesystem

### Penyelesaian dan Dokumentasi Soal 2
1) Dengan cara yang sama dengan nomor sebelumnya, Follow dilakukan dari paket
`576	43.664770386	192.168.0.27	103.94.189.5	HTTP	1393	GET /index.php/topik/detailTopik/194 HTTP/1.1` <br>
2) Dapat diketahui bahwa alamat yang dikunjungi adalah [http://monta.if.its.ac.id/index.php/topik/detailTopik/194](http://monta.if.its.ac.id/index.php/topik/detailTopik/194) <br>
3) Tampilan dari ss-nya adalah <br>
   ![image/soal2-a.png](/image/soal2-a.PNG)<br>
4) Karena title yang ada di bagian atas sepertinya bukan merupakan judul, kemungkinan besar judulnya adalah <br> “Topik Tugas Akhir: Evaluasi Unjuk Kerja User Space Filesystem”. Ditambah dengan deskripsi yang mengarah pada FUSE. <br>
  ![image/soal2-b.png](/image/soal2-b.PNG)<br> 



### Kendala Soal 2
Tidak ada

## Soal 3
Filter sehingga wireshark hanya menampilkan paket yang menuju port 80! 

### Jawaban Soal 3
wireshark filter expression( tcp.dstport == 80 || udp.dstport == 80)

### Penyelesaian dan Dokumentasi Soal 3
![image.png](/image/soal3.PNG)<br>
Penjelasan : <br>
disini kita disuruh untuk memfilter whileshark  sehingga hanya menampilkan paket yang menuju port 80, <br>
Disini kita menggunakan filter expression yaitu tcp.dstport == 80 || udp.dstport == 80 agar hanya menampilkan paket yang menuju port 80. <br>
Disini juga ada yang mana untuk tcp/udp merupakan detail dari protokol dimana paket ingin diambil atau ditangkap lalu dst yang diartikan sebagai menuju ke port yang ditulis di soal yaitu port 80.


### Kendala Soal 3
Tidak ada
## Soal 4
Filter sehingga wireshark hanya mengambil paket yang berasal dari port 21! 

### Jawaban Soal 4
Wireshark filter expression ( tcp.srcport == 21 || udp.srcport == 21 )

### Penyelesaian dan Dokumentasi Soal 4
![image.png](/image/soal4.PNG)<br>
Penjelasan : <br>
Soal memerintahkan untuk mem-filter wireshark sehingga hanya mengambil paket yang berasal dari port 21. Sesuai dengan yang tertera pada modul 1, maka kita dapat menggunakan perintah src untuk menangkap semua paket yang berasal dari tempat yang diinginkan. <br>
Pada soal nomer 4, digunakan perintah tcp.srcport == 21 || udp.srcport == 21 yang mana untuk tcp/udp merupakan detail dari protokol dimana paket ingin diambil atau ditangkap, <br>
dilanjutkan dengan src seperti penjelasan sebelumnya, baru kemudian memasukkan detail tempat dimana paket ingin diambil, disini diperintahkan mengambil paket yang berasal dari port 21, maka digunakan perintah port == 21
### Kendala Soal 4
Tidak ada
## Soal 5
Filter sehingga wireshark hanya mengambil paket yang berasal dari port 443!

### Jawaban Soal 5


### Penyelesaian dan Dokumentasi Soal 5


### Kendala Soal 5

## Soal 6
Filter sehingga wireshark hanya menampilkan paket yang menuju ke lipi.go.id !

### Jawaban Soal 6


### Penyelesaian dan Dokumentasi Soal 6


### Kendala Soal 6

## Soal 7
Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!

### Jawaban Soal 7


### Penyelesaian dan Dokumentasi Soal 7


### Kendala Soal 7

## Soal 8
Telusuri aliran paket dalam file .pcap yang diberikan, cari informasi berguna berupa percakapan antara dua mahasiswa terkait tindakan kecurangan pada kegiatan praktikum. Percakapan tersebut dilaporkan menggunakan protokol jaringan dengan tingkat keandalan yang tinggi dalam pertukaran datanya sehingga kalian perlu menerapkan filter dengan protokol yang tersebut.

### Jawaban Soal 8


### Penyelesaian dan Dokumentasi Soal 8


### Kendala Soal 8

## Soal 9
Terdapat laporan adanya pertukaran file yang dilakukan oleh kedua mahasiswa dalam percakapan yang diperoleh, carilah file yang dimaksud! Untuk memudahkan laporan kepada atasan, beri nama file yang ditemukan dengan format `[nama_kelompok].des3` dan simpan output file dengan nama `flag.txt`.

### Jawaban Soal 9


### Penyelesaian dan Dokumentasi Soal 9


### Kendala Soal 9

## Soal 10
Temukan password rahasia (flag) dari organisasi bawah tanah yang disebutkan di atas!

### Jawaban Soal 10


### Penyelesaian dan Dokumentasi Soal 10


### Kendala Soal 10
