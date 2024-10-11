# Request Sender Web
Request Sender Web adalah aplikasi web sederhana yang memungkinkan pengguna mengirim permintaan API POST secara otomatis dalam interval yang diatur. Dengan fitur pengiriman request yang dinamis, pengguna dapat memantau keberhasilan atau kegagalan permintaan dengan notifikasi berbasis alert yang intuitif.

Fitur Utama
Pengiriman Request API Dinamis:

Aplikasi memungkinkan pengguna untuk mengirim permintaan POST ke URL API yang diinginkan dengan payload yang dapat dikustomisasi.
Interval waktu pengiriman request bisa diatur, sehingga pengguna dapat menentukan seberapa cepat atau lambat permintaan dikirim.
Payload Generator:

Payload untuk setiap request dihasilkan secara acak berdasarkan pola yang ditentukan (misalnya, username acak, email acak, dan password acak).
Pengguna dapat menyesuaikan template payload dengan format JSON langsung di halaman web.
Pengaturan Interval Request:

Pengguna dapat mengatur waktu interval (dalam milidetik) antara setiap pengiriman request, memberikan fleksibilitas dalam pengujian API dengan berbagai skenario beban.
Tombol Mulai dan Hentikan Request:

Web menyediakan tombol interaktif yang memungkinkan pengguna untuk memulai dan menghentikan proses pengiriman request secara dinamis tanpa perlu memuat ulang halaman.
Saat request sedang berjalan, tombol berubah menjadi "Hentikan Request", dan jika diklik, request akan berhenti.
Notifikasi Sukses dan Gagal:

Sistem notifikasi yang menampilkan alert jika request berhasil atau gagal. Alert berwarna hijau untuk request sukses dan merah untuk request yang gagal.
Notifikasi akan menghilang setelah beberapa detik untuk tidak mengganggu pengguna.
Cara Kerja
Memulai Pengiriman Request:

Pengguna memasukkan URL API tujuan, interval waktu dalam milidetik, dan template payload dalam format JSON.
Setelah menekan tombol "Mulai Request", aplikasi akan mulai mengirim permintaan POST secara berkala sesuai interval yang ditentukan.
Menghentikan Pengiriman Request:

Pengguna dapat menghentikan pengiriman request kapan saja dengan menekan tombol "Hentikan Request". Tombol tersebut juga bisa diklik lagi untuk memulai kembali request.
Respon:

Setiap request akan menampilkan hasil sukses atau gagal. Pengguna dapat memonitor keberhasilan pengiriman request dengan mudah melalui alert yang ditampilkan di panel kanan.
Tujuan
Tujuan dari aplikasi ini adalah untuk memfasilitasi pengujian API dengan cara yang dinamis dan otomatis. Aplikasi ini berguna untuk developer yang ingin menguji endpoint API secara terus-menerus atau melakukan pengujian beban dengan pengiriman request berkala. Dengan aplikasi ini, developer dapat:

Mengotomatiskan pengujian API dengan data acak.
Melakukan pengujian performa atau stress testing terhadap server API.
Menghemat waktu dalam pengujian manual API dengan bantuan pengiriman request otomatis.
Dampak
Implementasi aplikasi ini memberikan dampak sebagai berikut:

Pengujian API yang lebih efisien: Aplikasi ini memudahkan developer untuk mengirim request secara berulang dalam waktu yang singkat, mengurangi kebutuhan untuk mengirim request secara manual.
Simulasi Beban: Dengan fitur interval yang dapat diatur, aplikasi ini membantu dalam simulasi beban (load testing) pada server API untuk melihat bagaimana performa server ketika menerima banyak request dalam waktu singkat.
Notifikasi yang Transparan: Dengan notifikasi berbasis alert, pengguna dapat dengan cepat mengetahui apakah request berhasil atau gagal, memberikan transparansi terhadap hasil pengujian.
