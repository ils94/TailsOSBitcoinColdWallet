# Labai svarbu atnaujinti savo TailsOS versiją, kad išvengtumėte bet kokių kenkėjiškų atakų, kurios galėtų pavogti jūsų Bitcoin'us! Jei naudojate pasenusią TailsOS versiją, prisiminkite NIEKADA nesijungti prie interneto, kai pasiekiate savo neprisijungusią piniginę! Naudokite antrą USB laikmeną, kad sukurtumėte savo prisijungusią piniginę, arba naudokite kitus būdus, kad turėtumėte prisijungusią piniginę „Android“ arba „iOS“ ir naudokite metodus, kad pasirašytumėte savo sandorius QR kodu. Aš neatsakau už bet kokį jūsų Bitcoin'ų vagystę, jei pažeidžiate bet kokias saugumo taisykles, įskaitant šio įspėjimo ignoravimą.

**Šis pamoka buvo išversta iš anglų į lietuvių kalbą naudojant ChatGPT. Gali būti keletas vertimo klaidų, bet tikiuosi, kad tai vis tiek bus suprantama lietuviškai kalbančiai bendruomenei!**

**Lietuviškas pamoka: Bitcoin šaltosios piniginės kūrimas naudojant TailsOS ir nuolatinę saugyklą**

Šiame vadove naudosiu Windows 10. Taip pat jums reikės USB atmintuko, kurio talpa yra bent 8GB.

1. Eikite į https://tails.net/install/download/index.en.html ir atsisiųskite **USB image**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Atsisiuntę **USB image**, patikrinkite atsisiuntimą apsilankydami atsisiuntimo puslapyje ir įkelkite atsisiųstą vaizdą paspaudę mygtuką, kuriame parašyta **Select your download to verify...**. Jei patikrinimas pavyksta, galite tęsti; kitaip turite iš naujo atsisiųsti vaizdą. Tada atsisiųskite **balenaEtcher** iš šios nuorodos: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Įjunkite savo USB atmintuką ir paleiskite **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Pasirinkite **USB image** paspaudę mygtuką **Flash from file**. Jūsų USB atmintukas turėtų būti automatiškai aptiktas. Jei ne, įsitikinkite, kad pasirinkote teisingą USB atmintuką. Tada spustelėkite mygtuką **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Palaukite, kol baigsis įrašymo procesas.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Baigę uždarykite **balenaEtcher** ir paleiskite kompiuterį iš USB atmintuko.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. **TailsOS** paspauskite mygtuką **Start Tails**, kad paleistumėte **TailsOS**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Eikite į **Applications** ir ieškokite **Persistent Storage** (tai turėtų būti **Favorites** skirtuke).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Spustelėkite mygtuką **Continue**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Sukurkite stiprų slaptažodį, kad užšifruotumėte savo **TailsOS** diegimą. Spustelėkite mygtuką **Create Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Palaukite, kol bus sukurtas **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. Kitame lange, kai baigsis kūrimas, turėtumėte matyti, kad **Persistent Folder** yra įjungtas pagal nutylėjimą. Jei ne, įjunkite jį.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Įjunkite ištisumą tiek **Electrum Bitcoin Wallet**, tiek **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Iš naujo paleiskite **TailsOS** ir įveskite savo slaptažodį. Tada spustelėkite mygtuką **Unlock Encryption**, kad atrakintumėte savo **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Kai **Persistent Storage** bus atrakintas, spustelėkite mygtuką **Start Tails**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Dabar prisijunkime prie Tor tinklo. Įsitikinkite, kad jūsų kompiuteris prijungtas prie Ethernet kabelio arba Wi-Fi, ir ieškokite **Tor Connection** **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Pasirinkite **Connect to Tor automatically** ir spustelėkite mygtuką **Connect to Tor**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Palaukite, kol jis prisijungs prie Tor tinklo.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Prisijungę spustelėkite mygtuką **Start Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Arba ieškokite **Tor Browser** **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. Atidarykite **Tor Browser** ir eikite į šią nuorodą: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Slinkite puslapiu žemyn, kol pamatysite **GPG My Public Key**. Dešiniuoju pelės mygtuku spustelėkite nuorodą ir pasirinkite **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Išsaugokite failą **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Dabar eikite į **Ian Coleman GitHub** puslapį šioje nuorodoje: https://github.com/iancoleman/bip39 ir eikite į Releases. Galite pasiekti releases šioje nuorodoje: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Atsisiųskite abu **bip39-standalone.html** ir **signature.txt.asc**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. Norėdami atsisiųsti **bip39-standalone.html**, tiesiog spustelėkite jį ir išsaugokite **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. Norėdami išsaugoti **signature.txt.asc**, darykite tą patį kaip ir **GPG Public Key** ir dešiniuoju pelės mygtuku spustelėkite jį ir pasirinkite **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Išsaugokite **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Galite matyti savo atsisiuntimus naršyklės juostoje esančiame **Downloads** ikonoje.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Dabar atjunkite **TailsOS** nuo interneto. Dabar sukursime savo piniginę. Tai gali pasirodyti per daug paranojiška, bet būkime saugūs, gerai?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Eikite į **Applications** ir ieškokite **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Dabar importuosime raktus ir patikrinsime, ar viskas gerai su atsisiųstu **bip39-standalone.html** failu. Kiekvieną komandą galite užbaigti paspausdami **Tab**.

Įveskite:

- cd Persistent/
- Paspauskite Enter
- cd Tor\ Browser/
- Paspauskite Enter
- ls (ši komanda skirta išvardinti katalogo failus, pažiūrėkite, ar visi 3 atsisiųsti failai yra jame)
- Paspauskite Enter
- gpg --import pubkey.asc
- Paspauskite Enter
- gpg --verify signature.txt.asc
- Paspauskite Enter

33. Patikrinkite, ar yra užrašas **Good signature from Ian Coleman <ian@iancoleman.io>**. Jei užrašas yra geras, tai reiškia, kad visi atsisiųsti failai yra autentiški.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Dabar patikrinkime, ar **bip39-standalone.html** maišos kodas atitinka Ian GitHub esančią maišą.

Įveskite:

- sha256sum bip39-standalone.html
- Paspauskite Enter

35. Patikrinkite, ar maiša Terminale atitinka maišą Ian GitHub. Jei jie sutampa, tada **bip39-standalone.html** failas taip pat yra autentiškas.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Eikite į **Places** ir pasirinkite **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Atidarykite **bip39-standalone.html** failą.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Čia yra mūsų Bitcoin piniginės neprisijungus generatorius.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Sukurkime 24 žodžių piniginę (pasirinkite arba 12, arba 24, kad ji būtų suderinama su bet kuria kita pinigine).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Spustelėkite mygtuką **GENERATE** ir užrašykite savo žodžius. Labai atidžiai atkreipkite dėmesį ir saugokite šiuos žodžius saugiai. Jei juos prarasite arba jei kas nors juos pavogs, tai bus žaidimo pabaiga.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Dabar eikite į **Applications** ir ieškokite **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Pavadinkime savo piniginę **Offline**, kad primintų, jog turėtumėte ją naudoti tik be interneto ryšio. Spustelėkite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Pasirinkite **Standard wallet**. Spustelėkite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Pasirinkite **I already have a seed**. Spustelėkite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Įveskite savo žodžius į teksto laukelį ir spustelėkite **Options**, atsiras mažas langelis, kuriame turėtumėte pasirinkti **BIP39 seed** ir spustelėti **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Patikrinkite, ar rodomas **BIP39 (checksum: ok)**. Spustelėkite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Pasirinkite **native segwit (p2wpkh)**. Spustelėkite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Pasirinkite stiprų slaptažodį, kad užšifruotumėte savo **Offline** piniginę. Spustelėkite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Jūsų piniginė sukurta. Dabar eikime į **View** ir pasirinkite **Show Addresses** ir **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Peržiūrėkite savo adresus.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Grįžkite į **bip39-standalone** puslapį ir slinkite žemyn iki **Derivation Path** ir spustelėkite **BIP84** skirtuką.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Patikrinkite, ar pirmasis adresas tinklalapyje atitinka pirmąj į adresą, rodomą **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Jei abu pirmieji adresai sutampa (taip pat antras, trečias ir t.t.), tai reiškia, kad jūsų piniginė buvo teisingai importuota į **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**Ši dalis yra skirta mūsų internetinei piniginei sukurti, ir turite dvi galimybes:**

- **1- Galite sukurti internetinę piniginę toje pačioje TailsOS instaliacijoje, kurioje yra jūsų neprisijungusi piniginė. Tokiu atveju NETURĖTUMĖTE PRISIJUNGTI PRIE INTERNETO, kai naudojatės neprisijungusia pinigine, kad išvengtumėte bet kokių atakų vektorių jūsų bitkoinams.**

- **2- Galite naudoti kitą USB atmintinę, laikytis tos pačios procedūros kaip aukščiau, ir tada sekti kitus žingsnius, kad sukurtumėte internetinę piniginę naujoje USB atmintinėje. Tai padeda išvengti žmogiškų klaidų, kai naudojatės neprisijungusia pinigine būdami prisijungę prie interneto.**

54. Dabar eikite į **Electrum Bitcoin Wallet** ir pasirinkite **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Nukopijuokite savo **Master Public Key** (nesidalinkite šiuo raktu su niekuo. Jei kas nors gautų jūsų **Master Public Key**, jie galės matyti jūsų adresus ir kiek Bitcoin turite).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Dabar sukursime kitą piniginę. Šį kartą tai bus mūsų **Online** piniginė (arba tik žiūrėjimo).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Pasirinkite **Standard wallet**. Spustelėkite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Pasirinkite **Use a master key**. Spustelėkite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Įklijuokite savo **Master Public Key**, kurį nukopijavote iš savo **Offline** piniginės. Spustelėkite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Jūsų žiūrėjimo tik piniginėje nereikia pridėti slaptažodžio, nes žiūrėjimo tik piniginės negali siųsti monetų, tačiau tai yra jūsų pasirinkimas. Spustelėkite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Jūsų žiūrėjimo tik piniginė sukurta ir jums bus pateiktas įspėjimas, kad **Ši piniginė yra tik stebėjimui. Tai reiškia, kad negalėsite naudoti jos Bitcoin'ų siuntimui. Įsitikinkite, kad turite sėklos frazę arba privačius raktus prieš prašydami Bitcoin'ų būti išsiųstų į šią piniginę.**

Žiūrėjimo tik piniginė yra tik adresų ir Bitcoin balanso rodymui, galite siųsti Bitcoin iš jos, bet tik tada, jei pasirašysite operaciją su savo **Offline** pinigine pirmiausia.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Dabar, paskutinis žingsnis, patikrinkite, ar **Online** piniginės adresai atitinka **Offline** piniginės adresus. Jei taip, tada jūs visiškai pasiruošę. Sėkmės.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
