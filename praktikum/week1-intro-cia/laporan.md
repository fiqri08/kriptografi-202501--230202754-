# Laporan Minggu 1 - Intro CIA
Nama : Fiqri Nur Hidayanto
NIM  : 230202754
Kelas: 5IKKA

Konsep Dasar Confidentiality, Integrity, Availability (CIA)

Keamanan informasi adalah aspek krusial dalam dunia digital yang terus berkembang. Untuk menjaga keamanan data dan sistem informasi, terdapat tiga prinsip utama yang dikenal dengan istilah CIA Triad, yaitu Confidentiality (Kerahasiaan), Integrity (Integritas), dan Availability (Ketersediaan). Ketiga konsep ini membentuk dasar untuk melindungi informasi dari ancaman yang dapat merugikan individu maupun organisasi.

1. Confidentiality (Kerahasiaan)
Kerahasiaan memastikan bahwa informasi hanya dapat diakses oleh pihak-pihak yang berwenang. Informasi yang bersifat sensitif, seperti data pribadi, rahasia bisnis, atau informasi strategis organisasi, harus dilindungi agar tidak jatuh ke tangan yang salah. Jika kerahasiaan ini dilanggar, maka dapat terjadi kebocoran data yang mengakibatkan kerugian finansial, hilangnya kepercayaan, atau pelanggaran hukum.
Contoh penerapan kerahasiaan termasuk penggunaan enkripsi untuk data yang dikirim atau disimpan, sistem autentikasi yang ketat seperti password atau biometrik, serta pembatasan akses berbasis peran (role-based access control).

2. Integrity (Integritas)
Integritas berarti menjaga keutuhan dan kebenaran informasi dari perubahan yang tidak sah, baik secara sengaja maupun tidak sengaja. Data harus tetap akurat, lengkap, dan dapat dipercaya sepanjang siklus hidupnya. Jika integritas informasi terganggu, misalnya karena manipulasi data atau kesalahan teknis, maka keputusan yang diambil berdasarkan data tersebut bisa salah dan merugikan organisasi.
Untuk menjaga integritas, biasanya digunakan mekanisme seperti hashing, digital signature, audit trail, dan kontrol versi. Mekanisme ini membantu mendeteksi dan mencegah perubahan data tanpa izin serta memastikan bahwa setiap perubahan dapat dilacak.

3. Availability (Ketersediaan)
Ketersediaan memastikan bahwa informasi dan sistem dapat diakses oleh pengguna yang berwenang tepat pada saat dibutuhkan. Gangguan terhadap ketersediaan, seperti serangan denial-of-service (DoS), kegagalan perangkat keras, atau bencana alam, dapat menyebabkan layanan menjadi tidak berfungsi dan menimbulkan kerugian besar.
Untuk menjaga ketersediaan, organisasi biasanya menerapkan strategi backup data secara rutin, menggunakan sistem redundansi (misalnya server cadangan), dan melakukan pemeliharaan sistem secara berkala agar dapat segera pulih dari gangguan.

Peran Kriptografi dalam Kehidupan Sehari-hari

1. Komunikasi Digital (WhatsApp, Telegram, Signal, Email)
•	Aplikasi pesan instan seperti WhatsApp dan Signal menggunakan end-to-end encryption (E2EE).
•	Pesan dienkripsi di perangkat pengirim dan hanya dapat didekripsi di perangkat penerima menggunakan kunci kriptografi.
•	Bahkan penyedia layanan (WhatsApp, Meta, atau Signal Foundation) tidak bisa membaca isi pesan.
•	Contoh: ketika Anda mengirim pesan pribadi, hacker atau pihak ketiga tidak bisa menyadap isinya meskipun data lewat jaringan publik (misalnya Wi-Fi umum).
2. Keamanan Akses Internet (SSL/TLS pada Website)

•	Saat membuka website dengan https://, browser dan server menggunakan protokol SSL/TLS untuk mengamankan koneksi.
•	Proses dimulai dengan handshake kriptografi: browser memverifikasi sertifikat digital server, lalu bertukar kunci enkripsi.
•	Data selanjutnya (misalnya password, nomor kartu kredit, atau data pribadi) dienkripsi dengan algoritma simetris (misalnya AES).
•	Manfaat: mencegah pencurian data (sniffing) dan memastikan pengguna terhubung ke server asli, bukan server palsu (phishing).

3. Tanda Tangan Digital (Digital Signature)
•	Banyak dokumen resmi, kontrak kerja, hingga surat elektronik menggunakan tanda tangan digital.
•	Tanda tangan digital dibangun dengan kriptografi asimetris:
o	Private key digunakan untuk menandatangani dokumen.
o	Public key digunakan untuk memverifikasi keaslian tanda tangan.
•	Keunggulan tanda tangan digital:
o	Otentikasi: memastikan siapa pengirim dokumen.
o	Integritas: menjamin dokumen tidak diubah setelah ditandatangani.
o	Non-repudiation: pengirim tidak bisa menyangkal bahwa ia telah menandatangani dokumen tersebut.

4. Keamanan Data Pribadi di Perangkat
•	Banyak smartphone dan laptop kini dilengkapi dengan full-disk encryption.
•	Jika perangkat hilang atau dicuri, data di dalamnya tetap aman karena hanya bisa diakses dengan password atau sidik jari pemilik.
•	Contoh: sistem FileVault (MacOS) atau BitLocker (Windows) yang menggunakan algoritma AES untuk mengenkripsi isi hard drive.

5. Sistem Perbankan dan Transaksi Digital
•	Ketika melakukan transaksi online banking atau menggunakan e-wallet (Dana, OVO, GoPay), data transaksi dikirim dalam bentuk terenkripsi.
•	ATM dan kartu kredit juga menggunakan kriptografi untuk mengamankan PIN dan data kartu.
•	Protokol 3D Secure (seperti Verified by Visa, Mastercard SecureCode) menggunakan tanda tangan digital untuk mencegah transaksi palsu.
•	Dengan adanya enkripsi, pencurian data nasabah bisa diminimalisir meskipun transaksi dilakukan melalui jaringan publik.

6. Blockchain dan Cryptocurrency
•	Blockchain (misalnya Bitcoin, Ethereum) sangat bergantung pada kriptografi.
•	Setiap transaksi diamankan dengan fungsi hash (SHA-256, Keccak) dan tanda tangan digital (ECDSA).
•	Hash digunakan untuk menjaga integritas data, sementara tanda tangan digital memastikan transaksi sah dan benar-benar dikirim oleh pemilik dompet digital.
•	Tanpa kriptografi, cryptocurrency tidak mungkin aman dari pemalsuan atau manipulasi data.

7. Sistem Keamanan Lainnya dalam Kehidupan Modern
•	Wi-Fi Security (WPA2, WPA3): jaringan Wi-Fi menggunakan kriptografi (AES, PSK) agar data komunikasi antar perangkat tidak bisa disadap.
•	Aplikasi Cloud (Google Drive, Dropbox, iCloud): semua data pengguna dienkripsi sebelum disimpan di server.
•	E-KTP dan Paspor Digital: identitas digital menggunakan tanda tangan digital dan enkripsi agar sulit dipalsukan.
