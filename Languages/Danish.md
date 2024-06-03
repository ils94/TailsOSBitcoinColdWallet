# Det er meget vigtigt at holde din TailsOS-version opdateret for at undgå enhver form for ondsindet angreb, der kan stjæle dine Bitcoins! Hvis du bruger en forældet version af TailsOS, skal du huske ALDRIG at oprette forbindelse til internettet, når du får adgang til din offline wallet! Brug en anden USB-drev til at oprette din online wallet, eller brug andre metoder til at have en online wallet på Android eller iOS, og brug metoder til at signere dine transaktioner ved QR-kode. Jeg er ikke ansvarlig for eventuel tyveri af dine Bitcoins, hvis du bryder nogen sikkerhedsregler, herunder at ignorere denne advarsel.

**Denne vejledning blev oversat fra engelsk til dansk ved hjælp af ChatGPT. Der kan forekomme nogle oversættelsesfejl, men jeg håber stadig, at den giver mening for det danske publikum!**

**Dansk vejledning: Oprettelse af en Bitcoin Cold Wallet ved hjælp af TailsOS og Persistent Storage**

I denne tutorial vil jeg bruge Windows 10. Du skal også bruge en USB-stick med mindst 8GB plads.

1. Gå til https://tails.net/install/download/index.en.html og download **USB image**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Efter du har downloadet **USB image**, verificer downloadet ved at gå til download-siden og uploade dit downloadede billede ved at klikke på knappen, der siger **Select your download to verify...** Hvis verifikationen er vellykket, kan du fortsætte; ellers skal du downloade billedet igen. Derefter, download **balenaEtcher** fra dette link: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Tilslut din USB-stick og start **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Vælg **USB image** ved at klikke på knappen **Flash from file**. Din USB-stick burde blive automatisk detekteret. Hvis ikke, sørg for at du vælger den rigtige USB-stick. Klik derefter på knappen **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Vent på at flashing-processen bliver færdig.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Når den er færdig, luk **balenaEtcher** og boot fra USB-sticken.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. I **TailsOS**, klik på **Start Tails** knappen for at starte **TailsOS**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Gå til **Applications** og se efter **Persistent Storage** (det burde være i **Favorites** fanen).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Klik på **Continue** knappen.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Opret en stærk adgangskode for at kryptere din **TailsOS** installation. Klik på knappen **Create Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Vent på at **Persistent Storage** bliver oprettet.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. I det næste vindue efter afslutningen, burde **Persistent Folder** være tændt som standard. Hvis ikke, tænd den.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Tænd for persistens for både **Electrum Bitcoin Wallet** og **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Genstart **TailsOS** og indtast din adgangskode. Klik derefter på knappen **Unlock Encryption** for at låse din **Persistent Storage** op.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Når **Persistent Storage** er låst op, klik på **Start Tails** knappen.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Lad os nu forbinde til Tor-netværket. Sørg for at din computer er forbundet til et Ethernet-kabel eller Wi-Fi, og søg efter **Tor Connection** i **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Vælg **Connect to Tor automatically** og klik på **Connect to Tor** knappen.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Vent på at den forbinder til Tor-netværket.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Når den er forbundet, klik på **Start Tor Browser** knappen.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Eller søg efter **Tor Browser** i **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. Med **Tor Browser** åben, gå til dette link: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Rul ned på siden indtil du ser **GPG My Public Key**. Højreklik på linket og vælg **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Gem filen i **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Gå nu til **Ian Coleman GitHub** siden på dette link: https://github.com/iancoleman/bip39 og gå til Releases. Du kan få adgang til releases fra dette link: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Download både **bip39-standalone.html** og **signature.txt.asc**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. For at downloade **bip39-standalone.html**, klik bare på den og gem den i **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. For at gemme **signature.txt.asc**, gør det samme som for **GPG Public Key** og højreklik på den og vælg **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Gem den i **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Du kan se dine downloads i **Downloads** ikonet i browserbaren.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Afbryd nu **TailsOS** fra internettet. Vi skal til at oprette vores wallet nu. Det lyder måske for paranoid, men lad os være sikre, okay?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Gå til **Applications** og søg efter **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Nu skal vi importere nøgler og verificere om alt er godt med **bip39-standalone.html** filen, vi downloadede. Du kan autoudfylde hver kommando ved at trykke på **Tab**.

Skriv:

- cd Persistent/
- Tryk Enter
- cd Tor\ Browser/
- Tryk Enter
- ls (denne kommando er for at liste filerne i mappen, se om alle 3 filer vi downloadede er i den)
- Tryk Enter
- gpg --import pubkey.asc
- Tryk Enter
- gpg --verify signature.txt.asc
- Tryk Enter

33. Tjek om der står **Good signature from Ian Coleman <ian@iancoleman.io>**. Hvis der står det, betyder det, at alle filer vi downloadede er legitime.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Nu skal vi se om hashen af **bip39-standalone.html** matcher hashen på Ians GitHub.

Skriv:

- sha256sum bip39-standalone.html
- Tryk Enter

35. Tjek både hashen i Terminalen og hashen på **Ian Coleman GitHub**. Hvis de matcher, er **bip39-standalone.html** filen også legitim.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Gå til **Places** og vælg **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Åbn **bip39-standalone.html** filen.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Her er vores Bitcoin wallet offline generator.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Lad os generere en 24-ords wallet (vælg enten 12 eller 24 for at gøre den kompatibel med enhver anden wallet).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Klik på **GENERATE** knappen og skriv dine ord ned. Vær MEGET opmærksom og gem disse ord sikkert. Hvis du mister dem eller hvis nogen stjæler dem, er det game over.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Gå nu til **Applications** og søg efter **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Lad os navngive vores wallet **Offline** for at minde dig om, at du kun bør få adgang til den uden internetforbindelse. Tryk på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Vælg **Standard wallet**. Tryk på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Vælg **I already have a seed**. Tryk på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Indtast dine ord i tekstboksen, og klik på **Options**, et lille vindue vil dukke op, og du bør vælge **BIP39 seed** og klik på **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Se om det står **BIP39 (checksum: ok)**. Tryk på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Vælg **native segwit (p2wpkh)**. Tryk på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Vælg en stærk adgangskode for at kryptere din **Offline** wallet. Tryk på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Din wallet er oprettet. Lad os nu gå til **View** og **Show Addresses** og **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Se dine adresser.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Gå tilbage til **bip39-standalone** siden, og rul ned til **Derivation Path** og klik på **BIP84** fanen.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Se om den første adresse på websiden matcher den første adresse vist i **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Hvis begge første adresser matcher (og den anden, og den tredje osv.) betyder det, at din wallet blev korrekt importeret til **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**Dette er det afsnit, hvor vi opretter vores Online Wallet, og du har to muligheder:**

- **1- Du kan oprette Online Wallet'en inden for den samme installation af TailsOS, som indeholder din Offline Wallet. I dette tilfælde skal du IKKE FORBINDE TIL INTERNETTET, når du får adgang til Offline Wallet'en for at forhindre eventuelle angrebsvektorer på dine Bitcoins.**

- **2- Du kan bruge en anden USB-stick, følge den samme proces som ovenfor, og derefter følge de næste trin for at oprette din Online Wallet på den nye USB-stick. Dette hjælper med at forhindre menneskelige fejl ved at få adgang til din Offline Wallet, mens du er forbundet til internettet.**

54. Gå nu til **Electrum Bitcoin Wallet** og gå til **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Kopier din **Master Public Key** (del ikke denne nøgle med nogen. Hvis nogen får adgang til din **Master Public Key**, vil de kunne se dine adresser og hvor meget Bitcoin du ejer).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Lad os nu oprette en anden wallet. Denne gang vil det være vores **Online** wallet (eller watching-only).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Vælg **Standard wallet**. Tryk på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Vælg **Use a master key**. Tryk på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Indsæt din **Master Public Key** som du kopierede fra din **Offline** wallet. Tryk på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Du behøver ikke at tilføje en adgangskode i din watching-only wallet, fordi watching-only wallets ikke kan sende mønter, men det er op til dig. Tryk på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Din watching-only wallet er oprettet, og du vil få en advarsel, der siger **This wallet is watching-only. This means you will not be able to spend Bitcoins with it. Make sure you own the seed phrase or private keys, before you request Bitcoins to be sent to this wallet.**

En watching-only wallet er kun til at vise adresser og Bitcoin saldo, du kan sende Bitcoins fra den, men kun hvis du signerer transaktionen med din **Offline** wallet først.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Nu, det sidste trin, se om adresserne på **Online** wallet matcher **Offline** wallet. Hvis det gør, er du klar. Held og lykke.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
