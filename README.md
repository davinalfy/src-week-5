# Flutter - Pemrograman Asynchronous

## Praktikum 1 - Mengunduh Data dari Web Service (API)
**Soal 1**
Tambahkan nama panggilan Anda pada title app sebagai identitas hasil pekerjaan Anda.  

  ![W5 Soal 1](images/W5-soal1.jpg)

**Soal 2**
Carilah judul buku favorit Anda di Google Books, lalu ganti ID buku pada variabel path di kode tersebut. Kemudian cobalah akses di browser URI tersebut dengan lengkap. Lakukan capture milik Anda dan tulis di README pada laporan praktikum.  

  ![W5 Soal 2](images/W5-soal2.jpg)

**Soal 3**
- Jelaskan maksud kode langkah 5 tersebut terkait substring dan catchError!  
> kode `substring(0, 450)` berfungsi untuk memotong teks agar hanya tampil 450 karakter pertama. Sedangkan, kode `catchError((_) { })` berfungsi untuk menangani error saat mengambil data agar aplikasi tetap berjalan.
- Capture hasil praktikum Anda berupa GIF dan lampirkan di README

  ![W5 Soal 3](images/W5-soal3.gif)  

## Praktikum 2: Menggunakan await/async untuk menghindari callbacks
**Soal 4**
- Jelaskan maksud kode langkah 1 dan 2 tersebut!  
> Kode tersebut mensimulasikan tiga proses asynchronous (`returnOneAsync`, `returnTwoAsync`, dan `returnThreeAsync`) yang masing-masing menunggu selama 3 detik sebelum mengembalikan angka 1, 2, dan 3. Ketiganya dipanggil secara berurutan dalam method `count()`, lalu hasilnya dijumlahkan menjadi 6 dan ditampilkan ke UI lewat `setState`. Jadi, kode ini melatih penggunaan `async/await` untuk proses berurutan dan update tampilan setelah semua proses selesai.
- Capture hasil praktikum Anda berupa GIF dan lampirkan di README.

  ![W5 Soal 4](images/W5-soal4.gif)

## Praktikum 3: Menggunakan Completer di Future
**Soal 5**
- Jelaskan maksud kode langkah 2 tersebut!  
> Langkah ini membuat sistem penundaan hasil menggunakan `Completer`, yaitu cara manual untuk menyelesaikan `Future`. Variabel `late Completer completer`; disiapkan untuk menyimpan proses yang akan diselesaikan nanti. Saat `getNumber()` dipanggil, `calculate()` dijalankan dan setelah 5 detik, `completer.complete(42)`; mengirim nilai 42 sebagai hasil.
- Capture hasil praktikum Anda berupa GIF dan lampirkan di README.

  ![W5 Soal 5](images/W5-soal5.gif)