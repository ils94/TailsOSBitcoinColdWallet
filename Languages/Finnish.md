# On erittäin tärkeää pitää TailsOS-versiosi ajan tasalla välttääksesi minkäänlaista haitallista hyökkäystä, joka voisi varastaa Bitcoinisi! Jos käytät vanhentunutta TailsOS-versiota, muista, että ET SAA KOSKAAN YHDISTÄ INTERNETTIIN, kun käytät offline-lompakkoasi! Käytä toista USB-asemaa luodaksesi online-lompakkosi tai käytä muita keinoja, kuten Android- tai iOS-sovelluksia, ja allekirjoita siirrot QR-koodilla. En ole vastuussa Bitcoiniesi varkaudesta, jos rikot mitään turvallisuussääntöjä, mukaan lukien tämän varoituksen huomiotta jättäminen.

**Suomenkielinen opas: Bitcoin-kylmälompakon luominen TailsOS:lla ja pysyvällä tallennustilalla**

Tässä opetusohjelmassa käytän Windows 10:tä. Tarvitset myös USB-muistitikun, jossa on vähintään 8 Gt tilaa.

1. Mene osoitteeseen https://tails.net/install/download/index.en.html ja lataa **USB image**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Lataaessasi **USB image**, varmista lataus siirtymällä lataussivulle ja lataamalla ladattu kuva napsauttamalla painiketta, joka sanoo **Select your download to verify...**. Jos vahvistus onnistuu, voit jatkaa; muuten sinun täytyy ladata kuva uudelleen. Lataa sitten **balenaEtcher** tästä linkistä: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Liitä USB-tikku ja käynnistä **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Valitse **USB image** napsauttamalla **Flash from file** -painiketta. USB-tikkusi pitäisi tunnistaa automaattisesti. Jos ei, varmista että valitset oikean USB-tikun. Napsauta sitten **Flash!** -painiketta.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Odota, että kirjoitusprosessi valmistuu.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Kun olet valmis, sulje **balenaEtcher** ja käynnistä tietokoneesi USB-tikulta.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. **TailsOS**:ssa, napsauta **Start Tails** -painiketta käynnistääksesi **TailsOS**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Siirry **Applications**-valikkoon ja etsi **Persistent Storage** (sen pitäisi olla **Favorites**-välilehdellä).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Napsauta **Continue**-painiketta.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Luo vahva salasana salataksesi **TailsOS**-asennuksesi. Napsauta **Create Persistent Storage** -painiketta.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Odota, että **Persistent Storage** luodaan.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. Seuraavassa ikkunassa luomisen jälkeen sinulla pitäisi olla **Persistent Folder** oletusarvoisesti päällä. Jos ei, kytke se päälle.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Ota pysyvyys käyttöön sekä **Electrum Bitcoin Wallet**:lle että **GnuPG**:lle.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Käynnistä **TailsOS** uudelleen ja syötä salasanasi. Napsauta sitten **Unlock Encryption** -painiketta avataksesi **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Kun **Persistent Storage** on avattu, napsauta **Start Tails** -painiketta.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Nyt yhdistetään Tor-verkkoon. Varmista, että tietokoneesi on kytketty Ethernet-kaapeliin tai Wi-Fi:iin, ja etsi **Tor Connection** **Applications**-valikosta.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Valitse **Connect to Tor automatically** ja napsauta **Connect to Tor** -painiketta.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Odota, että se yhdistyy Tor-verkkoon.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Kun olet yhteydessä, napsauta **Start Tor Browser** -painiketta.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Tai etsi **Tor Browser** **Applications**-valikosta.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. Kun **Tor Browser** on auki, mene tähän linkkiin: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Vieritä sivua alaspäin, kunnes näet **GPG My Public Key**. Napsauta hiiren oikealla painikkeella linkkiä ja valitse **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Tallenna tiedosto kansioon **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Nyt siirry **Ian Coleman GitHub** -sivulle tästä linkistä: https://github.com/iancoleman/bip39 ja mene julkaisuihin. Voit käyttää julkaisuja tästä linkistä: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Lataa sekä **bip39-standalone.html** että **signature.txt.asc**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. Lataaaksesi **bip39-standalone.html**, napsauta sitä ja tallenna se kansioon **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. Tallentaaksesi **signature.txt.asc**, tee sama kuin **GPG Public Key**:n kanssa ja napsauta sitä hiiren oikealla painikkeella ja valitse **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Tallenna se kansioon **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Voit nähdä latauksesi selaimen latauskuvakkeessa.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Nyt irrota **TailsOS** internetistä. Aiomme nyt luoda lompakkomme. Se kuulostaa liian vainoharhaiselta, mutta ollaan varovaisia, okei?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Mene **Applications**-valikkoon ja etsi **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Nyt tuomme avaimet ja tarkistamme, että kaikki on kunnossa ladatulla **bip39-standalone.html** -tiedostolla. Voit täydentää jokaista komentoa painamalla **Tab**.

Kirjoita:

- cd Persistent/
- Paina Enter
- cd Tor\ Browser/
- Paina Enter
- ls (tämä komento luettelee hakemiston tiedostot, katso onko kaikki kolme lataamaamme tiedostoa siellä)
- Paina Enter
- gpg --import pubkey.asc
- Paina Enter
- gpg --verify signature.txt.asc
- Paina Enter

33. Tarkista, sanooko se **Good signature from Ian Coleman <ian@iancoleman.io>**. Jos se sanoo, että se on hyvä, niin se tarkoittaa, että kaikki ladatut tiedostot ovat laillisia.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Nyt tarkistamme, vastaako **bip39-standalone.html**:n hash Ianin GitHub-sivulla olevaa hashia.

Kirjoita:

- sha256sum bip39-standalone.html
- Paina Enter

35. Tarkista sekä Terminalissa oleva hash että **Ian Coleman GitHub**:n hash. Jos ne vastaavat, niin **bip39-standalone.html** -tiedosto on myös laillinen.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Mene **Places**-valikkoon ja valitse **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Avaa **bip39-standalone.html** -tiedosto.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Tässä on offline-Bitcoin-lompakon generaattorimme.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Luodaan 24-sanan lompakko (valitse joko 12 tai 24, jotta se on yhteensopiva minkä tahansa muun lompakon kanssa).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Napsauta **GENERATE**-painiketta ja kirjoita sanasi ylös. Kiinnitä paljon huomiota ja säilytä nämä sanat turvallisesti. Jos kadotat ne tai joku varastaa ne, peli on ohi.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Nyt mene **Applications**-valikkoon ja etsi **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Nimetään lompakkomme **Offline**, jotta muistat, että sinun pitäisi käyttää sitä vain ilman internet-yhteyttä. Paina **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Valitse **Standard wallet**. Paina **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Valitse **I already have a seed**. Paina **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Kirjoita sanasi tekstikenttään ja napsauta **Options**, pieni ikkuna avautuu ja sinun pitäisi valita **BIP39 seed** ja napsauta **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Katso, onko siinä **BIP39 (checksum: ok)**. Paina **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Valitse **native segwit (p2wpkh)**. Paina **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Valitse vahva salasana salataksesi **Offline**-lompakkosi. Paina **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Lompakkosi on luotu. Nyt mennään **View**-valikkoon ja valitaan **Show Addresses** ja **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Näe osoitteesi.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Palaa **bip39-standalone** -sivulle ja vieritä alas **Derivation Path** -kohtaan ja napsauta **BIP84**-välilehteä.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Katso, vastaako verkkosivun ensimmäinen osoite **Electrum Bitcoin Wallet**:in ensimmäistä osoitetta.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Jos molemmat ensimmäiset osoitteet vastaavat (ja toinen, ja kolmas ja niin edelleen), se tarkoittaa, että lompakkosi on oikein tuotu **Electrum Bitcoin Wallet**:iin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**Tässä osassa luomme Online-lompakkomme, ja sinulla on kaksi vaihtoehtoa:**

- **1- Voit luoda Online-lompakon samassa TailsOS-asennuksessa, joka sisältää Offline-lompakkosi. Tässä tapauksessa sinun EI TULE YHDISTÄ INTERNETTIIN, kun käytät Offline-lompakkoa, jotta estät mahdolliset hyökkäysvektorit Bitcoinesi.**

- **2- Voit käyttää toista USB-muistitikkua, seurata samaa prosessia kuin yllä, ja sitten seurata seuraavia vaiheita luodaksesi Online-lompakon uudelle USB-muistitikulle. Tämä auttaa estämään inhimillisen virheen käyttämällä Offline-lompakkoasi, kun olet yhteydessä internetiin.**

54. Nyt mene **Electrum Bitcoin Wallet**:iin ja mene **Information**-kohtaan.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Kopioi **Master Public Key** (älä jaa tätä avainta kenellekään. Jos joku saa pääsyn **Master Public Key**:si, hän pystyy näkemään osoitteesi ja kuinka paljon Bitcoinia omistat).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Luodaan nyt toinen lompakko. Tällä kertaa se on meidän **Online**-lompakkomme (tai vain katselu).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Valitse **Standard wallet**. Paina **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Valitse **Use a master key**. Paina **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Liitä **Master Public Key**, jonka kopioit **Offline**-lompakostasi. Paina **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Sinun ei tarvitse lisätä salasanaa vain katselu -lompakkoosi, koska vain katselu -lompakot eivät voi lähettää kolikoita, mutta se on sinun päätettävissäsi. Paina **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Katselulompakkosi on luotu, ja sinulle esitetään varoitus, joka sanoo **Tämä lompakko on vain katseltavaksi. Tämä tarkoittaa, että et voi käyttää Bitcoineja sen kanssa. Varmista, että sinulla on siemenlause tai yksityiset avaimet, ennen kuin pyydät lähettämään Bitcoineja tähän lompakkoon.**

Vain katselu -lompakko on tarkoitettu vain osoitteiden ja Bitcoin-saldon näyttämiseen, voit lähettää Bitcoineja siitä, mutta vain jos allekirjoitat tapahtuman **Offline**-lompakollasi ensin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Nyt viimeinen askel, katso, vastaavatko **Online**-lompakon osoitteet **Offline**-lompakon osoitteita. Jos näin on, olet valmis. Onnea.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
