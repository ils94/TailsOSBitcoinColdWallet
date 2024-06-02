# TailsOS sürümünüzü güncel tutmak, Bitcoin'lerinizi çalabilecek her türlü kötü amaçlı saldırıdan kaçınmak için çok önemlidir! Eski bir TailsOS sürümü kullanıyorsanız, çevrimdışı cüzdanınıza erişirken ASLA internete bağlanmamayı unutmayın! Çevrimiçi cüzdanınızı oluşturmak için ikinci bir USB sürücü kullanın veya Android veya iOS'ta çevrimiçi cüzdanınızı oluşturmak ve işlemlerinizi QR Kodu ile imzalamak için diğer yöntemleri kullanın. Güvenlik kurallarını ihlal ederseniz, bu uyarıyı göz ardı ederseniz Bitcoin'lerinizin çalınmasıyla ilgili hiçbir sorumluluğum yoktur.

**Bu kılavuz, İngilizce'den Türkçe'ye ChatGPT kullanılarak çevrildi. Bazı çeviri hataları olabilir, ancak umarım Türkçe konuşan topluluk için hala anlamlı olur!**

**Türkçe Kılavuz: Tails OS ve Kalıcı Depolama Kullanarak Bitcoin Soğuk Cüzdan Oluşturma**

Bu eğitimde, Windows 10 kullanacağım. Ayrıca en az 8GB alanı olan bir USB bellek gerekecek.

1. https://tails.net/install/download/index.pt.html adresine gidin ve USB İmajını indirin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. USB imajını indirdikten sonra, indirme sayfasına giderek indirilen imajı doğrulamak için **Select your download to verify...** düğmesine tıklayın ve indirdiğiniz imajı yükleyin. Doğrulama başarılı olursa, devam edebilirsiniz; aksi takdirde imajı yeniden indirmeniz gerekir. Daha sonra, balenaEtcher'ı bu bağlantıdan indirin: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. USB belleğinizi takın ve **balenaEtcher**'ı başlatın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. **Flash from file** düğmesine tıklayarak USB imajını seçin. USB belleğiniz otomatik olarak algılanmalıdır. Değilse, doğru USB belleğini seçtiğinizden emin olun. Ardından, **Flash!** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Yanıp sönme işleminin tamamlanmasını bekleyin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. İşlem tamamlandıktan sonra **balenaEtcher**'ı kapatın ve USB bellekten önyükleyin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. **TailsOS**'te, **TailsOS**'i başlatmak için **Start** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. **Applications**'a gidin ve **Persistent Storage**'i arayın (**Favorites** sekmesinde olmalıdır).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. **Continue** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. **TailsOS** kurulumunuzu şifrelemek için güçlü bir şifre oluşturun. **Create Persistent Storage** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. **Persistent Storage** oluşturulmasının tamamlanmasını bekleyin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. Tamamlandıktan sonraki pencerede, varsayılan olarak **Persistent Folder** açık olmalıdır. Değilse, açın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Hem **Electrum Bitcoin Wallet** hem de **GnuPG** için kalıcılığı açın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. **TailsOS**'u yeniden başlatın ve şifrenizi girin. Ardından, **Unlock Encryption** düğmesine tıklayarak **Persistent Storage**'nızı açın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. **Persistent Storage** açıldıktan sonra, **Start Tails** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Şimdi Tor Ağına bağlanalım. Bilgisayarınızın bir Ethernet kablosuna veya Wi-Fi'ya bağlı olduğundan emin olun ve **Applications**'ta **Tor Connection**'ı arayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Seç **Connect to Tor automatically** ve **Connect to Tor** düğmesine tıkla.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Tor Ağına bağlanmasını bekleyin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Bağlandıktan sonra, **Start Tor Browser** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Veya **Applications**'ta **Tor Browser**'ı arayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. **Tor Browser** açıkken, bu bağlantıya gidin: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Sayfanın aşağısına inin ve **GPG My Public Key**'i görene kadar kaydırın. Bağlantıya sağ tıklayın ve **Save Link As...** seçeneğini seçin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Dosyayı **/home/amnesia/Persistent/Tor Browser** konumuna kaydedin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Şimdi, **Ian Coleman GitHub** sayfasına bu bağlantıdan gidin: https://github.com/iancoleman/bip39 ve Sürümler'e gidin. Sürümlere bu bağlantıdan erişebilirsiniz: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Hem **bip39-standalone.html** hem de **signature.txt.asc** dosyalarını indirin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. **bip39-standalone.html** dosyasını indirmek için, üzerine tıklayın ve **/home/amnesia/Persistent/Tor Browser** konumuna kaydedin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. **signature.txt.asc**'yi kaydetmek için, **GPG Public Key** ile aynısını yapın ve üzerine sağ tıklayıp **Save Link As...** seçeneğini seçin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Dosyayı **/home/amnesia/Persistent/Tor Browser** konumuna kaydedin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. İndirmelerinizi tarayıcı çubuğundaki **Downloads** simgesinde görebilirsiniz.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Şimdi **TailsOS**'i internetten ayırın. Şimdi cüzdanımızı oluşturacağız. Bu çok paranoyakça görünebilir, ama güvende olalım, tamam mı?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. **Applications**'a gidin ve **Terminal**'i arayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Şimdi anahtarları içe aktaracağız ve indirdiğimiz **bip39-standalone.html** dosyasının iyi olup olmadığını doğrulayacağız. Her komutu **Tab** tuşuna basarak otomatik olarak tamamlayabilirsiniz.

Şunu yazın:

- cd Persistent/
- Enter tuşuna basın
- cd Tor\ Browser/
- Enter tuşuna basın
- ls (bu komut dizindeki dosyaları listelemek için, indirdiğimiz 3 dosyanın orada olup olmadığını görmek için)
- Enter tuşuna basın
- gpg --import pubkey.asc
- Enter tuşuna basın
- gpg --verify signature.txt.asc
- Enter tuşuna basın

33. Kontrol et, eğer **Good signature from Ian Coleman <ian@iancoleman.io>** yazıyorsa. Eğer iyi olduğunu söylüyorsa, o zaman indirdiğimiz tüm dosyaların gerçek olduğu anlamına gelir.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Şimdi **bip39-standalone.html** dosyasının hash'inin Ian'ın GitHub'daki hash ile eşleşip eşleşmediğini göreceğiz.

Şunu yazın:

- sha256sum bip39-standalone.html
- Enter tuşuna basın

35. Terminal'de ve **Ian Coleman GitHub** üzerindeki hash'i kontrol edin. Eğer eşleşiyorlarsa, o zaman **bip39-standalone.html** dosyası da doğruludur.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. **Places**'e gidin ve **Tor Browser (persistent)**'i seçin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. **bip39-standalone.html** dosyasını açın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. İşte Bitcoin cüzdanımızın çevrimdışı jeneratörü.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. 24 kelimelik bir cüzdan oluşturacağız (diğer cüzdanlarla uyumlu hale getirmek için 12 veya 24 arasından seçim yapın).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. **GENERATE** düğmesine tıklayın ve kelimelerinizi yazın. ÇOK dikkatli olun ve bu kelimeleri güvenli bir şekilde saklayın. Eğer kaybederseniz veya birisi onları çalarsa, oyun biter.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Şimdi **Applications**'a gidin ve **Electrum Bitcoin Wallet**'i arayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Cüzdanımıza **Offline** adını verelim, bu size sadece internet bağlantısı olmadan erişmeniz gerektiğini hatırlatacaktır. **Next** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. **Standard wallet**'ı seçin. **Next** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. **I already have a seed**'i seçin. **Next** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Kelimelerinizi metin kutusuna yazın ve **Options**'a tıklayın, küçük bir pencere açılacak ve **BIP39 seed**'i seçip **OK**'e tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. **BIP39 (checksum: ok)** olup olmadığını kontrol edin. **Next** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. **native segwit (p2wpkh)**'yi seçin. **Next** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Şifreleme için güçlü bir şifre seçin **Offline** cüzdanınızı. **Next** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Cüzdanınız oluşturuldu. Şimdi **View**'e gidin ve **Show Addresses** ve **Show Coins**'i seçin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Adreslerinizi görün.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. **bip39-standalone** sayfasına geri dönün ve **Derivation Path**'e kaydırın ve **BIP84** sekmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Web sayfasındaki ilk adresin **Electrum Bitcoin Wallet**'te gösterilen ilk adresle eşleşip eşleşmediğini kontrol edin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Eğer her iki ilk adres eşleşiyorsa (ve ikinci, üçüncü ve devamı), cüzdanınızın **Electrum Bitcoin Wallet**'e doğru bir şekilde aktarıldığı anlamına gelir.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**Bu, Online Cüzdanımızı oluşturduğumuz bölümdür ve iki seçeneğiniz var:**

- **1- Çevrimdışı Cüzdanınızı içeren aynı TailsOS kurulumu içinde Online Cüzdanı oluşturabilirsiniz. Bu durumda, Bitcoins'inize yönelik herhangi bir saldırı vektörünü önlemek için ÇEVRİMİÇİ OLMADAN Çevrimdışı Cüzdana erişirken İNTERNETE BAĞLANMAMALISINIZ.**

- **2- Başka bir USB sürücü kullanabilir, yukarıdaki süreci aynen takip edebilir ve ardından yeni USB sürücüdeki Online Cüzdanınızı oluşturmak için bir sonraki adımları izleyebilirsiniz. Bu, Çevrimdışı Cüzdana internet bağlantısı olanken erişme hatalarını önlemeye yardımcı olur.**

54. Şimdi **Electrum Bitcoin Wallet**'e gidin ve **Information**'a gidin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. **Master Public Key**'inizi kopyalayın (bu anahtarı kimseyle paylaşmayın. Birisi **Master Public Key**'inize erişirse, adreslerinizi ve ne kadar Bitcoin'iniz olduğunu görebilir).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Şimdi başka bir cüzdan oluşturalım. Bu sefer, **Online** cüzdanımız (veya sadece izleme).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. **Standard wallet**'ı seçin. **Next** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. **Use a master key**'i seçin. **Next** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. **Offline** cüzdanınızdan kopyaladığınız **Master Public Key**'inizi yapıştırın. **Next** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. İzleme modundaki cüzdanınıza şifre eklemenize gerek yok, çünkü izleme modundaki cüzdanlar Coin gönderemez, ancak bu size bağlı. **Next** düğmesine tıklayın.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. İzleme modundaki cüzdanınız oluşturuldu ve size **Bu cüzdan sadece izleme modundadır. Bu, Bitcoin harcayamayacağınız anlamına gelir. Bu cüzdana Bitcoin gönderilmesini istemeden önce seed kelimelerine veya özel anahtarlara sahip olduğunuzdan emin olun.** şeklinde bir uyarı gösterilecektir.

İzleme modundaki bir cüzdan sadece adresleri ve Bitcoin bakiyesini göstermek içindir, bu cüzdandan Bitcoin gönderebilirsiniz, ancak sadece işlemi önce **Offline** cüzdanınızla imzalarsanız.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Şimdi, son adım, **Online** cüzdanın adreslerinin **Offline** cüzdanla eşleşip eşleşmediğini kontrol edin. Eğer öyleyse, her şey hazır. İyi şanslar.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
