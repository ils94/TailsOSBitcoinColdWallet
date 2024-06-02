# Sangat penting untuk selalu memperbarui versi TailsOS Anda untuk menghindari segala jenis serangan jahat yang dapat mencuri Bitcoin Anda! Jika Anda menggunakan versi TailsOS yang sudah ketinggalan zaman, ingatlah untuk TIDAK PERNAH terhubung ke internet saat mengakses dompet offline Anda! Gunakan USB drive kedua untuk membuat dompet online Anda, atau gunakan cara lain untuk memiliki dompet online di Android atau iOS, dan gunakan metode untuk menandatangani transaksi Anda melalui QR Code. Saya tidak bertanggung jawab atas pencurian Bitcoin Anda jika Anda melanggar aturan keamanan apa pun, termasuk mengabaikan peringatan ini.

**Tutorial ini diterjemahkan dari bahasa Inggris ke bahasa Indonesia menggunakan ChatGPT. Mungkin ada beberapa kesalahan terjemahan, tapi saya harap masih bisa dimengerti oleh komunitas penutur bahasa Indonesia!**

**Tutorial dalam Bahasa Indonesia: Membuat Dompet Dingin Bitcoin Menggunakan Tails OS dan Penyimpanan Persisten**

Dalam tutorial ini, saya akan menggunakan Windows 10. Anda juga memerlukan USB stick dengan kapasitas minimal 8GB.

1. Buka https://tails.net/install/download/index.en.html dan unduh **USB image**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Setelah mengunduh gambar USB, verifikasi unduhan dengan membuka halaman unduhan dan mengunggah gambar yang telah Anda unduh dengan mengklik tombol yang bertuliskan **Select your download to verify...** Jika verifikasi berhasil, Anda dapat melanjutkan; jika tidak, Anda harus mengunduh ulang gambar tersebut. Kemudian, unduh **balenaEtcher** dari tautan ini: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Colokkan USB stick Anda dan jalankan **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Pilih gambar USB dengan mengklik tombol **Flash from file**. USB stick Anda harus terdeteksi secara otomatis. Jika tidak, pastikan Anda memilih USB stick yang benar. Kemudian, klik tombol **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Tunggu hingga proses flashing selesai.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Setelah selesai, tutup **balenaEtcher** dan boot dari USB stick.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. Di **TailsOS**, klik tombol **Start Tails** untuk memulai **TailsOS**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Buka **Applications** dan cari **Persistent Storage** (seharusnya ada di tab **Favorites**).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Klik tombol **Continue**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Buatlah kata sandi yang kuat untuk mengenkripsi instalasi **TailsOS** Anda. Klik tombol **Create Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Tunggu hingga pembuatan **Persistent Storage** selesai.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. Di jendela berikutnya setelah selesai, Anda harus memiliki **Persistent Folder** yang dinyalakan secara default. Jika tidak, nyalakan.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Nyalakan persistensi untuk **Electrum Bitcoin Wallet** dan **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Restart **TailsOS** dan masukkan kata sandi Anda. Kemudian, klik tombol **Unlock Encryption** untuk membuka **Persistent Storage** Anda.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Setelah **Persistent Storage** terbuka, klik tombol **Start Tails**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Sekarang, mari kita sambungkan ke Jaringan Tor. Pastikan komputer Anda terhubung ke kabel Ethernet atau Wi-Fi, dan cari **Tor Connection** di **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Pilih **Connect to Tor automatically** dan klik tombol **Connect to Tor**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Tunggu hingga terhubung ke Jaringan Tor.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Setelah terhubung, klik tombol **Start Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Atau cari **Tor Browser** di **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. Dengan **Tor Browser** terbuka, buka tautan ini: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Gulir ke bawah halaman sampai Anda melihat **GPG My Public Key**. Klik kanan tautannya dan pilih **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Simpan file di **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Sekarang, buka halaman **Ian Coleman GitHub** di tautan ini: https://github.com/iancoleman/bip39 dan buka Releases. Anda dapat mengakses rilis dari tautan ini: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Unduh **bip39-standalone.html** dan **signature.txt.asc**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. Untuk mengunduh **bip39-standalone.html**, cukup klik dan simpan di **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. Untuk menyimpan **signature.txt.asc**, lakukan hal yang sama seperti untuk **GPG Public Key** dan klik kanan padanya lalu pilih **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Simpan di **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Anda dapat melihat unduhan Anda di ikon **Downloads** di bilah peramban.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Sekarang, putuskan koneksi **TailsOS** dari internet. Kita akan membuat dompet kita sekarang. Kedengarannya terlalu paranoid, tetapi mari kita aman, oke?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Buka **Applications** dan cari **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Sekarang, kita akan mengimpor kunci dan memverifikasi apakah semuanya baik-baik saja dengan file **bip39-standalone.html** yang kita unduh. Anda dapat menyelesaikan setiap perintah dengan menekan **Tab**.

Ketik:

- cd Persistent/
- Tekan Enter
- cd Tor\ Browser/
- Tekan Enter
- ls (perintah ini untuk melihat file-file di direktori, lihat apakah semua 3 file yang kita unduh ada di dalamnya)
- Tekan Enter
- gpg --import pubkey.asc
- Tekan Enter
- gpg --verify signature.txt.asc
- Tekan Enter

33. Periksa apakah tertulis **Good signature from Ian Coleman <ian@iancoleman.io>**. Jika tertulis seperti itu, berarti semua file yang kita unduh adalah asli.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Sekarang kita akan melihat apakah hash dari **bip39-standalone.html** cocok dengan hash di GitHub Ian.

Ketik:

- sha256sum bip39-standalone.html
- Tekan Enter

35. Periksa kedua hash di Terminal dan hash di **Ian Coleman Github**. Jika cocok, maka file **bip39-standalone.html** juga sah.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Buka **Places** dan pilih **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Buka file **bip39-standalone.html**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Ini adalah generator dompet Bitcoin offline kita.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Mari kita buat dompet 24-kata (pilih 12 atau 24 untuk membuatnya kompatibel dengan dompet lain).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Klik tombol **GENERATE** dan catat kata-kata Anda. Perhatikan dengan BAIK dan simpan kata-kata ini dengan aman. Jika Anda kehilangan atau jika seseorang mencurinya, itu akan menjadi akhir.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Sekarang, buka **Applications** dan cari **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Mari beri nama dompet kita **Offline** untuk mengingatkan Anda bahwa Anda hanya boleh mengaksesnya tanpa koneksi internet. Tekan **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Pilih **Standard wallet**. Tekan **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Pilih **I already have a seed**. Tekan **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Ketik kata-kata Anda di kotak teks, dan klik **Options**, sebuah jendela kecil akan muncul, dan Anda harus memilih **BIP39 seed** dan klik **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Lihat apakah **BIP39 (checksum: ok)**. Tekan **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Pilih **native segwit (p2wpkh)**. Tekan **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Pilih kata sandi yang kuat untuk mengenkripsi dompet **Offline** Anda. Tekan **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Dompet Anda dibuat. Sekarang buka **View** dan **Show Addresses** dan **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Lihat alamat-alamat Anda.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Kembali ke halaman **bip39-standalone**, dan gulir ke bawah ke **Derivation Path** dan klik tab **BIP84**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Lihat apakah alamat pertama di halaman web cocok dengan alamat pertama yang ditampilkan di **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Jika kedua alamat pertama cocok (dan yang kedua, dan yang ketiga, dan seterusnya), itu berarti dompet Anda berhasil diimpor ke **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**Ini adalah bagian di mana kita membuat Dompet Online kita, dan Anda memiliki dua opsi:**

- **1- Anda dapat membuat Dompet Online dalam instalasi TailsOS yang sama yang berisi Dompet Offline Anda. Dalam hal ini, Anda sebaiknya TIDAK MENGHUBUNGKAN KE INTERNET saat mengakses Dompet Offline untuk mencegah vektor serangan pada Bitcoin Anda.**

- **2- Anda dapat menggunakan USB stick lain, ikuti proses yang sama seperti di atas, dan kemudian ikuti langkah-langkah berikutnya untuk membuat Dompet Online pada USB stick yang baru. Ini membantu mencegah kesalahan manusia saat mengakses Dompet Offline Anda saat terhubung ke internet.**

54. Sekarang buka **Electrum Bitcoin Wallet** dan buka **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Salin **Master Public Key** Anda (jangan bagikan kunci ini dengan siapa pun. Jika seseorang mendapatkan akses ke **Master Public Key** Anda, mereka akan dapat melihat alamat Anda dan berapa banyak Bitcoin yang Anda miliki).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Sekarang mari kita buat dompet lain. Kali ini, akan menjadi dompet **Online** kita (atau watching-only).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Pilih **Standard wallet**. Tekan **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Pilih **Use a master key**. Tekan **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Tempel **Master Public Key** Anda yang telah Anda salin dari dompet **Offline** Anda. Tekan **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Anda tidak perlu menambahkan kata sandi di dompet watching-only Anda, karena dompet watching-only tidak dapat mengirim Koin, tetapi terserah Anda. Tekan **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Dompet watching-only Anda dibuat, dan Anda akan diberi peringatan yang mengatakan **Dompet ini hanya dapat digunakan untuk melihat saja. Ini berarti Anda tidak akan bisa menghabiskan Bitcoin menggunakan dompet ini. Pastikan Anda memiliki frasa benih atau kunci privat, sebelum Anda meminta Bitcoin dikirimkan ke dompet ini.**

Dompet watching-only hanya untuk menampilkan alamat dan saldo Bitcoin, Anda dapat mengirim Bitcoin dari situ tetapi hanya jika Anda menandatangani transaksi dengan dompet **Offline** Anda terlebih dahulu.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Sekarang, langkah terakhir, lihat apakah alamat-alamat dari dompet **Online** cocok dengan dompet **Offline**. Jika ya, maka Anda sudah siap. Semoga sukses.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
