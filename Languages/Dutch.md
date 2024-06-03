# Het is erg belangrijk om je TailsOS-versie up-to-date te houden om elke vorm van kwaadaardige aanval te voorkomen die je Bitcoins zou kunnen stelen! Als je een verouderde versie van TailsOS gebruikt, onthoud dan om NOOIT verbinding te maken met het internet wanneer je toegang hebt tot je offline wallet! Gebruik een tweede USB-stick om je online wallet te maken, of gebruik andere middelen om een online wallet op Android of iOS te hebben, en gebruik methoden om je transacties te ondertekenen met een QR-code. Ik ben niet verantwoordelijk voor enige diefstal van je Bitcoins als je enige veiligheidsregels overtreedt, inclusief het negeren van deze waarschuwing.

**Deze handleiding is vertaald van Engels naar Nederlands met behulp van ChatGPT. Er kunnen enkele vertaalfouten zijn, maar ik hoop dat het nog steeds begrijpelijk is voor de Nederlandstalige gemeenschap!**

**Nederlandse Handleiding: Een Bitcoin Cold Wallet Maken met TailsOS en Persistent Storage**

In deze tutorial zal ik Windows 10 gebruiken. Je hebt ook een USB-stick nodig met minstens 8GB aan ruimte.

1. Ga naar https://tails.net/install/download/index.en.html en download de **USB image**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Na het downloaden van de **USB image**, verifieer de download door naar de downloadpagina te gaan en je gedownloade afbeelding te uploaden door op de knop te klikken die zegt **Select your download to verify...**. Als de verificatie succesvol is, kun je doorgaan; anders moet je de afbeelding opnieuw downloaden. Download dan **balenaEtcher** van deze link: https://tails.net/etcher/balenaEtcher-portable.exe.

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Steek je USB-stick in en start **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Selecteer de **USB image** door op de knop **Flash from file** te klikken. Je USB-stick zou automatisch gedetecteerd moeten worden. Zo niet, zorg ervoor dat je de juiste USB-stick selecteert. Klik dan op de knop **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Wacht tot het flash-proces is voltooid.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Zodra het is voltooid, sluit **balenaEtcher** en start vanaf de USB-stick.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. In **TailsOS**, klik op de knop **Start Tails** om **TailsOS** te starten.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Ga naar **Applications** en zoek naar **Persistent Storage** (het zou in het tabblad **Favorites** moeten staan).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Klik op de knop **Continue**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Maak een sterk wachtwoord aan om je **TailsOS** installatie te versleutelen. Klik op de knop **Create Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Wacht tot de **Persistent Storage** is aangemaakt.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. In het volgende venster na voltooiing zou de **Persistent Folder** standaard ingeschakeld moeten zijn. Zo niet, schakel deze in.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Schakel persistentie in voor zowel de **Electrum Bitcoin Wallet** als **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Herstart **TailsOS** en voer je wachtwoord in. Klik dan op de knop **Unlock Encryption** om je **Persistent Storage** te ontgrendelen.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Zodra de **Persistent Storage** is ontgrendeld, klik op de knop **Start Tails**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Laten we nu verbinding maken met het Tor-netwerk. Zorg ervoor dat je computer is verbonden met een ethernetkabel of Wi-Fi, en zoek naar **Tor Connection** in **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Selecteer **Connect to Tor automatically** en klik op de knop **Connect to Tor**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Wacht tot het verbinding maakt met het Tor-netwerk.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Zodra de verbinding tot stand is gebracht, klik op de knop **Start Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Of zoek naar **Tor Browser** in de **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. Met **Tor Browser** geopend, ga naar deze link: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Scroll naar beneden op de pagina tot je **GPG My Public Key** ziet. Klik met de rechtermuisknop op de link en selecteer **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Sla het bestand op in **/home/amnesia/Persistent/Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Ga nu naar de **Ian Coleman GitHub** pagina via deze link: https://github.com/iancoleman/bip39 en ga naar Releases. Je kunt releases openen via deze link: https://github.com/iancoleman/bip39/releases.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Download zowel **bip39-standalone.html** als **signature.txt.asc**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. Om **bip39-standalone.html** te downloaden, klik erop en sla het op in **/home/amnesia/Persistent/Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. Om **signature.txt.asc** op te slaan, doe hetzelfde als voor de **GPG Public Key** en klik met de rechtermuisknop erop en selecteer **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Sla het op in **/home/amnesia/Persistent/Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Je kunt je downloads zien in het **Downloads** pictogram in de browserbalk.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Ontkoppel nu **TailsOS** van het internet. We gaan nu onze wallet maken. Het klinkt misschien te paranoïde, maar laten we veilig zijn, oké?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Ga naar **Applications** en zoek naar **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. We gaan nu sleutels importeren en controleren of alles goed is met het **bip39-standalone.html** bestand dat we hebben gedownload. Je kunt elke opdracht automatisch aanvullen door op **Tab** te drukken.

Typ:

- cd Persistent/
- Druk op Enter
- cd Tor\ Browser/
- Druk op Enter
- ls (dit commando is om de bestanden in de directory weer te geven, zie of alle 3 de bestanden die we hebben gedownload erin staan)
- Druk op Enter
- gpg --import pubkey.asc
- Druk op Enter
- gpg --verify signature.txt.asc
- Druk op Enter

33. Controleer of er staat **Good signature from Ian Coleman <ian@iancoleman.io>**. Als het zegt dat het goed is, betekent dat dat alle bestanden die we hebben gedownload legitiem zijn.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. We zullen nu controleren of de hash van **bip39-standalone.html** overeenkomt met de hash op Ian's GitHub.

Typ:

- sha256sum bip39-standalone.html
- Druk op Enter

35. Vergelijk de hash in de Terminal met de hash op **Ian Coleman GitHub**. Als ze overeenkomen, is het **bip39-standalone.html** bestand ook legitiem.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Ga naar **Places** en selecteer **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Open het **bip39-standalone.html** bestand.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Hier is onze offline Bitcoin wallet generator.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Laten we een 24-woorden wallet genereren (kies 12 of 24 om het compatibel te maken met elke andere wallet).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Klik op de knop **GENERATE** en schrijf je woorden op. Besteed VEEL aandacht en bewaar deze woorden veilig. Als je ze kwijtraakt of als iemand ze steelt, is het game over.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Ga nu naar **Applications** en zoek naar **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Laten we onze wallet **Offline** noemen om je eraan te herinneren dat je er alleen zonder internetverbinding toegang toe moet hebben. Klik op **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Selecteer **Standard wallet**. Klik op **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Selecteer **I already have a seed**. Klik op **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Typ je woorden in het tekstvak en klik op **Options**, een klein venster zal verschijnen en je moet **BIP39 seed** selecteren en klik op **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Controleer of de **BIP39 (checksum: ok)**. Klik op **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Selecteer **native segwit (p2wpkh)**. Klik op **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Kies een sterk wachtwoord om je **Offline** wallet te versleutelen. Klik op **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Je wallet is aangemaakt. Ga nu naar **View** en **Show Addresses** en **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Bekijk je adressen.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Ga terug naar de **bip39-standalone** pagina en scroll naar beneden naar **Derivation Path** en klik op het **BIP84** tabblad.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Controleer of het eerste adres op de webpagina overeenkomt met het eerste adres dat wordt weergegeven in de **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Als beide eerste adressen overeenkomen (en de tweede, en de derde enzovoort), betekent dit dat je wallet correct is geïmporteerd naar de **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**Dit is het deel waar we onze Online Wallet maken, en je hebt twee opties:**

- **1- Je kunt de Online Wallet maken binnen dezelfde installatie van TailsOS die je Offline Wallet bevat. In dit geval mag je NIET VERBINDEN MET HET INTERNET wanneer je toegang hebt tot de Offline Wallet om eventuele aanvalspunten op je Bitcoins te voorkomen.**

- **2- Je kunt een andere USB-stick gebruiken, volg hetzelfde proces als hierboven, en volg dan de volgende stappen om je Online Wallet op de nieuwe USB-stick te maken. Dit helpt om menselijke fouten te voorkomen bij het toegang krijgen tot je Offline Wallet terwijl je verbonden bent met het internet.**

54. Ga nu naar **Electrum Bitcoin Wallet** en ga naar **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Kopieer je **Master Public Key** (deel deze sleutel niet met iemand. Als iemand toegang krijgt tot je **Master Public Key**, kunnen ze je adressen zien en hoeveel Bitcoin je bezit).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Laten we nu een andere wallet aanmaken. Deze keer wordt het onze **Online** wallet (of alleen-lezen).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Selecteer **Standard wallet**. Klik op **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Selecteer **Use a master key**. Klik op **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Plak je **Master Public Key** die je hebt gekopieerd van je **Offline** wallet. Klik op **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Je hoeft geen wachtwoord toe te voegen aan je alleen-lezen wallet, omdat alleen-lezen wallets geen munten kunnen verzenden, maar het is aan jou. Klik op **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Je alleen-lezen wallet is aangemaakt en je krijgt een waarschuwing te zien die zegt **This wallet is watching-only. This means you will not be able to spend Bitcoins with it. Make sure you own the seed phrase or private keys, before you request Bitcoins to be sent to this wallet.**

Een alleen-lezen wallet is alleen bedoeld om adressen en Bitcoin-saldo te tonen, je kunt Bitcoins ervan verzenden, maar alleen als je de transactie eerst ondertekent met je **Offline** wallet.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Nu, de laatste stap, controleer of de adressen van de **Online** wallet overeenkomen met de **Offline** wallet. Als dat zo is, dan ben je klaar. Veel succes.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
