# Napakahalaga na panatilihing updated ang iyong bersyon ng TailsOS upang maiwasan ang anumang uri ng malisyosong atake na maaaring magnakaw ng iyong mga Bitcoin! Kung gumagamit ka ng luma nang bersyon ng TailsOS, tandaan na HUWAG kailanman kumonekta sa internet kapag ina-access ang iyong offline na wallet! Gumamit ng pangalawang USB drive upang lumikha ng iyong online na wallet, o gumamit ng ibang paraan upang magkaroon ng online na wallet sa Android o iOS, at gumamit ng mga pamamaraan upang pirmahan ang iyong mga transaksyon gamit ang QR Code. Hindi ako responsable sa anumang pagnanakaw ng iyong mga Bitcoin kung lalabagin mo ang anumang patakaran sa seguridad, kabilang ang hindi pagsunod sa babalang ito.

**Ang tutorial na ito ay isinalin mula sa Ingles patungo sa Philipino gamit ang ChatGPT. Maaaring mayroong ilang mga error sa pagsasalin, ngunit umaasa akong may kahulugan pa rin ito sa komunidad ng mga nagsasalita ng Philipino!**

**Filipino Tutorial: Paggawa ng Bitcoin Cold Wallet Gamit ang TailsOS at Persistent Storage**

Sa tutorial na ito, gagamitin ko ang Windows 10. Kakailanganin mo rin ng USB stick na may hindi bababa sa 8GB na espasyo.

1. Pumunta sa https://tails.net/install/download/index.en.html at i-download ang **USB image**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Pagkatapos i-download ang **USB image**, i-verify ang download sa pamamagitan ng pagpunta sa download page at pag-upload ng iyong na-download na image sa pamamagitan ng pag-click sa button na nagsasabing **Select your download to verify...** Kung matagumpay ang pag-verify, maaari kang magpatuloy; kung hindi, kailangan mong i-download muli ang image. Pagkatapos, i-download ang **balenaEtcher** mula sa link na ito: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. I-plug ang iyong USB stick at simulan ang **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Piliin ang **USB image** sa pamamagitan ng pag-click sa **Flash from file** button. Ang iyong USB stick ay awtomatikong madi-detect. Kung hindi, siguraduhing pinipili mo ang tamang USB stick. Pagkatapos, i-click ang **Flash!** button.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Hintayin ang pagproseso ng flashing hanggang matapos.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Kapag tapos na, isara ang **balenaEtcher** at mag-boot mula sa USB stick.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. Sa **TailsOS**, i-click ang **Start Tails** button upang simulan ang **TailsOS**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Pumunta sa **Applications** at hanapin ang **Persistent Storage** (dapat ito ay nasa **Favorites** tab).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. I-click ang **Continue** button.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Gumawa ng malakas na password upang i-encrypt ang iyong **TailsOS** installation. I-click ang **Create Persistent Storage** button.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Hintayin ang paglikha ng **Persistent Storage** hanggang matapos.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. Sa susunod na window pagkatapos ng pag-complete, dapat ay naka-on na ang **Persistent Folder** bilang default. Kung hindi, i-on ito.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. I-on ang persistence para sa parehong **Electrum Bitcoin Wallet** at **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. I-restart ang **TailsOS** at ilagay ang iyong password. Pagkatapos, i-click ang **Unlock Encryption** button upang i-unlock ang iyong **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Kapag ang **Persistent Storage** ay naka-unlock, i-click ang **Start Tails** button.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Ngayon, mag-connect sa Tor Network. Siguraduhing ang iyong computer ay konektado sa isang Ethernet cable o Wi-Fi, at hanapin ang **Tor Connection** sa **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Piliin ang **Connect to Tor automatically** at i-click ang **Connect to Tor** button.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Hintayin ang pag-connect sa Tor Network.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Kapag naka-connect na, i-click ang **Start Tor Browser** button.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. O hanapin ang **Tor Browser** sa **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. Kapag bukas na ang **Tor Browser**, pumunta sa link na ito: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. I-scroll pababa ang pahina hanggang makita mo ang **GPG My Public Key**. I-right-click ang link at piliin ang **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. I-save ang file sa **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Ngayon, pumunta sa **Ian Coleman GitHub** page sa link na ito: https://github.com/iancoleman/bip39 at pumunta sa Releases. Maaari mong ma-access ang releases mula sa link na ito: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. I-download pareho ang **bip39-standalone.html** at **signature.txt.asc**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. Para i-download ang **bip39-standalone.html**, i-click lang ito at i-save sa **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. Para i-save ang **signature.txt.asc**, gawin ang pareho sa ginawa sa **GPG Public Key** at i-right-click ito at piliin ang **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. I-save ito sa **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Makikita mo ang iyong mga download sa **Downloads** icon sa browser bar.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Ngayon, i-disconnect ang **TailsOS** mula sa internet. Gagawa na tayo ngayon ng ating wallet. Mukhang masyadong paranoyd, pero maging ligtas tayo, okay?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Pumunta sa **Applications** at hanapin ang **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Ngayon, i-import natin ang mga keys at i-verify kung lahat ay maayos sa **bip39-standalone.html** file na na-download natin. Maaari mong i-autocomplete ang bawat command sa pamamagitan ng pag-pindot ng **Tab**.

Type:

- cd Persistent/
- Pindutin ang Enter
- cd Tor\ Browser/
- Pindutin ang Enter
- ls (ang command na ito ay para ilista ang mga files sa directory, tingnan kung ang lahat ng 3 files na na-download natin ay nandiyan)
- Pindutin ang Enter
- gpg --import pubkey.asc
- Pindutin ang Enter
- gpg --verify signature.txt.asc
- Pindutin ang Enter

33. Tingnan kung sinasabi na **Good signature from Ian Coleman <ian@iancoleman.io>**. Kung sinasabi na maayos, ibig sabihin lahat ng files na na-download natin ay lehitimo.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Ngayon, tingnan natin kung ang hash ng **bip39-standalone.html** ay tumutugma sa hash sa Ian's GitHub.

Type:

- sha256sum bip39-standalone.html
- Pindutin ang Enter

35. I-verify ang hash sa Terminal at ang hash sa **Ian Coleman GitHub**. Kung tumutugma, ibig sabihin lehitimo rin ang **bip39-standalone.html** file.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Pumunta sa **Places** at piliin ang **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Buksan ang **bip39-standalone.html** file.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Narito ang ating Bitcoin wallet offline generator.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Gumawa tayo ng 24-word wallet (pumili ng 12 o 24 upang maging compatible sa kahit anong wallet).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. I-click ang **GENERATE** button at isulat ang iyong mga salita. Mag-ingat nang husto at itago nang ligtas ang mga salitang ito. Kung mawawala mo ito o kung may magnanakaw nito, tapos na ang laro.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Ngayon, pumunta sa **Applications** at hanapin ang **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Pangalanan natin ang ating wallet ng **Offline** upang ipaalala sa iyo na dapat mo lamang itong i-access nang walang koneksyon sa internet. Pindutin ang **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Piliin ang **Standard wallet**. Pindutin ang **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Piliin ang **I already have a seed**. Pindutin ang **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. I-type ang iyong mga salita sa text box, at i-click ang **Options**, may lilitaw na maliit na window, at dapat mong piliin ang **BIP39 seed** at i-click ang **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Tingnan kung ang **BIP39 (checksum: ok)**. Pindutin ang **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Piliin ang **native segwit (p2wpkh)**. Pindutin ang **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Piliin ang isang malakas na password upang i-encrypt ang iyong **Offline** wallet. Pindutin ang **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Ang iyong wallet ay nalikha na. Ngayon, pumunta sa **View** at **Show Addresses** at **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Tingnan ang iyong mga address.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Bumalik sa **bip39-standalone** page, at i-scroll pababa sa **Derivation Path** at i-click ang **BIP84** tab.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Tingnan kung ang unang address sa webpage ay tumutugma sa unang address na ipinapakita sa **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Kung parehong tumutugma ang unang address (at ang pangalawa, at ang pangatlo, at iba pa) ibig sabihin ang iyong wallet ay tamang na-import sa **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**Ito ang bahagi kung saan lumikha tayo ng ating Online Wallet, at mayroon kang dalawang opsyon:**

- **1- Maaari mong likhain ang Online Wallet sa loob ng parehong pag-install ng TailsOS na naglalaman ng iyong Offline Wallet. Sa kasong ito, HINDI KA DAPAT KUMONEKTA SA INTERNET kapag ina-access ang Offline Wallet upang maiwasan ang anumang attack vectors sa iyong Bitcoins.**

- **2- Maaari mong gamitin ang isa pang USB stick, sundin ang parehong proseso tulad ng nasa itaas, at pagkatapos ay sundin ang mga susunod na hakbang upang lumikha ng iyong Online Wallet sa bagong USB stick. Nakakatulong ito upang maiwasan ang pagkakamali ng tao ng pag-access sa iyong Offline Wallet habang nakakonekta sa internet.**

54. Ngayon pumunta sa **Electrum Bitcoin Wallet** at pumunta sa **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Kopyahin ang iyong **Master Public Key** (huwag ibahagi ang key na ito kaninuman. Kung may makakakuha ng access sa iyong **Master Public Key**, makikita nila ang iyong mga address at kung magkano ang Bitcoin mo).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Ngayon, gumawa tayo ng isa pang wallet. Sa pagkakataong ito, ito ang ating **Online** wallet (o watching-only).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Piliin ang **Standard wallet**. Pindutin ang **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Piliin ang **Use a master key**. Pindutin ang **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. I-paste ang iyong **Master Public Key** na kinopya mula sa iyong **Offline** wallet. Pindutin ang **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Hindi mo kailangang maglagay ng password sa iyong watching-only wallet, dahil ang watching-only wallets ay hindi makakapagpadala ng Coins, ngunit nasa iyo na ito. Pindutin ang **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Ang iyong watching-only wallet ay nalikha na, at ipapakita sa iyo ang isang babala na nagsasabing **This wallet is watching-only. This means you will

 not be able to spend Bitcoins with it. Make sure you own the seed phrase or private keys, before you request Bitcoins to be sent to this wallet.**

Ang isang watching-only wallet ay para lamang magpakita ng mga address at Bitcoin balance, maaari kang magpadala ng Bitcoins mula rito ngunit kailangan mo munang i-sign ang transaction gamit ang iyong **Offline** wallet.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Ngayon, ang huling hakbang, tingnan kung ang mga address ng **Online** wallet ay tumutugma sa **Offline** wallet. Kung gayon, handa ka na. Good luck.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
