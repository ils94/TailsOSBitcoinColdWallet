# On väga oluline hoida oma TailsOS versioon ajakohasena, et vältida igasuguseid pahatahtlikke rünnakuid, mis võiksid teie Bitcoine varastada! Kui kasutate aegunud TailsOS-i versiooni, pidage meeles, et ÄRGE ÜHENDAGE INTERNETTI, kui pääsete ligi oma offline rahakotile! Kasutage teist USB-draivi oma online rahakoti loomiseks või kasutage muid vahendeid, et omada online rahakotti Androidil või iOS-il, ja kasutage meetodeid oma tehingute allkirjastamiseks QR-koodi abil. Ma ei vastuta teie Bitcoinide varguse eest, kui rikute mingeid turvareegleid, sealhulgas selle hoiatuse eiramist.

**See juhend tõlgiti inglise keelest eesti keelde, kasutades ChatGPT-d. Tõlkes võib esineda vigu, kuid loodan, et see on endiselt arusaadav eesti keelt kõnelevale kogukonnale!**

**Eesti keeles juhend: Bitcoini külmrahakoti loomine TailsOS-i ja püsisalvestuse abil**

Selles juhendis kasutan Windows 10. Sul on vaja ka vähemalt 8GB ruumiga USB-mälupulka.

1. Mine aadressile https://tails.net/install/download/index.en.html ja laadi alla **USB image**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Pärast **USB image** allalaadimist kinnita allalaadimine, minnes allalaadimise lehele ja laadides oma allalaaditud pildi üles, klõpsates nupule **Select your download to verify...** Kui kinnitamine on edukas, võid jätkata; vastasel juhul pead pildi uuesti alla laadima. Seejärel laadi alla **balenaEtcher** sellelt lingilt: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Ühenda oma USB-mälupulk ja käivita **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Vali **USB image**, klõpsates nupule **Flash from file**. Sinu USB-mälupulk peaks olema automaatselt tuvastatud. Kui ei, siis veendu, et valiksid õige USB-mälupulga. Seejärel klõpsa nupule **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Oota, kuni vilkumisprotsess on lõpule viidud.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Kui valmis, sulge **balenaEtcher** ja käivita arvuti USB-mälupulgalt.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. **TailsOS**-is klõpsa nupule **Start Tails**, et käivitada **TailsOS**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Mine **Applications** ja otsi **Persistent Storage** (see peaks olema **Favorites** vahekaardil).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Klõpsa nupule **Continue**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Loo tugev parool, et krüpteerida oma **TailsOS**-i installatsioon. Klõpsa nupule **Create Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Oota, kuni **Persistent Storage** loomine on lõpule viidud.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. Järgmises aknas peaks **Persistent Folder** olema vaikimisi sisse lülitatud. Kui ei, lülita see sisse.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Lülita püsivus sisse nii **Electrum Bitcoin Wallet** kui ka **GnuPG** jaoks.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Taaskäivita **TailsOS** ja sisesta oma parool. Seejärel klõpsa nupule **Unlock Encryption**, et avada oma **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Kui **Persistent Storage** on avatud, klõpsa nupule **Start Tails**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Nüüd ühendume Tor-võrguga. Veendu, et sinu arvuti on ühendatud Etherneti kaabli või Wi-Fi-ga, ja otsi **Tor Connection** **Applications**-is.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Vali **Connect to Tor automatically** ja klõpsa nupule **Connect to Tor**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Oota, kuni see ühendub Tor-võrguga.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Kui ühendus on loodud, klõpsa nupule **Start Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Või otsi **Tor Browser** **Applications**-is.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. Avatud **Tor Browser**-iga mine sellele lingile: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Keri lehte alla, kuni näed **GPG My Public Key**. Paremklõpsa lingil ja vali **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Salvesta fail asukohta **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Nüüd mine **Ian Coleman GitHub** lehele sellel lingil: https://github.com/iancoleman/bip39 ja mine jaotisesse Releases. Juurdepääs väljalasetele sellelt lingilt: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Laadi alla nii **bip39-standalone.html** kui ka **signature.txt.asc**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. **bip39-standalone.html** allalaadimiseks klõpsa seda ja salvesta asukohta **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. **signature.txt.asc** salvestamiseks tee sama, mis **GPG Public Key** jaoks, paremklõpsa ja vali **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Salvesta see asukohta **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Sa näed oma allalaadimisi brauseri ribal asuvas **Downloads** ikoonis.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Nüüd lahuta **TailsOS** internetist. Me loome nüüd oma rahakoti. See tundub liiga paranoiline, kuid olgem turvalised, eks?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Mine **Applications** ja otsi **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Nüüd impordime võtmed ja kinnitame, kas **bip39-standalone.html** failiga on kõik korras, mille me alla laadisime. Sa saad iga käsku autokomplekteerida, vajutades **Tab**.

Tüüp:

- cd Persistent/
- Vajuta Enter
- cd Tor\ Browser/
- Vajuta Enter
- ls (see käsk loetleb failid kaustas, vaata, kas kõik 3 alla laaditud faili on seal)
- Vajuta Enter
- gpg --import pubkey.asc
- Vajuta Enter
- gpg --verify signature.txt.asc
- Vajuta Enter

33. Vaata, kas seal on kirjas **Good signature from Ian Coleman <ian@iancoleman.io>**. Kui seal on kirjas, et see on hea, siis tähendab see, et kõik allalaaditud failid on legitiimsed.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Nüüd kontrollime, kas **bip39-standalone.html** hash vastab Iani GitHub-is olevale hash-ile.

Tüüp:

- sha256sum bip39-standalone.html
- Vajuta Enter

35. Kontrolli nii Terminalis olevat hash-i kui ka hash-i **Ian Coleman GitHub**-is. Kui need ühtivad, siis on **bip39-standalone.html** fail samuti legitiimne.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Mine **Places** ja vali **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Ava **bip39-standalone.html** fail.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Siin on meie Bitcoin rahakoti offline generaator.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Loo 24-sõnaline rahakott (vali kas 12 või 24, et see oleks ühilduv mis tahes muu rahakotiga).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Klõpsa nupule **GENERATE** ja kirjuta oma sõnad üles. Pööra VÄGA palju tähelepanu ja hoia neid sõnu turvaliselt. Kui sa kaotad need või kui keegi varastab need, on mäng läbi.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Nüüd mine **Applications** ja otsi **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Nimeta oma rahakott **Offline**, et tuletada meelde, et peaksid seda kasutama ainult ilma internetiühenduseta. Vajuta **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Vali **Standard wallet**. Vajuta **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Vali **I already have a seed**. Vajuta **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Sisesta oma sõnad tekstikasti ja klõpsa **Options**, ilmub väike aken ja sa peaksid valima **BIP39 seed** ja klõpsa **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Vaata, kas seal on kirjas **BIP39 (checksum: ok)**. Vajuta **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Vali **native segwit (p2wpkh)**. Vajuta **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Vali tugev parool, et krüpteerida oma **Offline** rahakott. Vajuta **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Sinu rahakott on loodud. Nüüd mine **View** ja **Show Addresses** ning **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Vaata oma aadresse.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Mine tagasi **bip39-standalone** lehele ja keri alla **Derivation Path** juurde ja klõpsa **BIP84** vahekaardile.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Vaata, kas esimene aadress veebilehel vastab esimesele aadressile **Electrum Bitcoin Wallet**-is.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Kui esimene aadress (ja teine, ja kolmas ja nii edasi) ühtivad, tähendab see, et su rahakott on õigesti **Electrum Bitcoin Wallet**-i imporditud.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**See on osa, kus me loome oma online rahakoti ja teil on kaks võimalust:**

- **1- Saate luua online rahakoti sama TailsOS-i installatsiooni sees, mis sisaldab teie offline rahakotti. Sel juhul EI TOHIKS te internetti ühendada, kui pääsete ligi oma offline rahakotile, et vältida rünnakuvektoreid teie Bitcoinide vastu.**

- **2- Saate kasutada teist USB-mälupulka, järgida sama protsessi nagu eespool ja seejärel järgida järgmisi samme, et luua oma online rahakott uuel USB-mälupulgal. See aitab vältida inimlikku eksimust, kui pääsete ligi oma offline rahakotile internetiga ühendatuna.**

54. Nüüd mine **Electrum Bitcoin Wallet**-isse ja mine **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Kopeeri oma **Master Public Key** (ära jaga seda võtit kellegagi. Kui keegi saab juurdepääsu sinu **Master Public Key**-le, saab ta näha sinu aadresse ja kui palju Bitcoine sa omandad).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Lähme nüüd looma teist rahakotti. Seekord on see meie **Online** rahakott (või ainult vaatamine).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Vali **Standard wallet**. Vajuta **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Vali **Use a master key**. Vajuta **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Kleebi oma **Master Public Key**, mille kopeerisid oma **Offline** rahakotist. Vajuta **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Sul pole vaja lisada parooli oma ainult vaadatavasse rahakotti, sest ainult vaadatavad rahakotid ei saa münte saata, kuid see on sinu otsustada. Vajuta **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Sinu ainult vaadatav rahakott on loodud ja sulle esitatakse hoiatus, öeldes **See rahakott on ainult vaatamise režiimis. See tähendab, et te ei saa sellega Bitcoine kulutada. Veenduge, et omate seemnefraasi või privaatvõtmeid enne, kui taotlete Bitcoine sellesse rahakotti saata.**

Ainult vaadatav rahakott on mõeldud ainult aadresside ja Bitcoin saldode näitamiseks, sa saad saata Bitcoine sellest, kuid ainult siis, kui allkirjastad tehingu esmalt oma **Offline** rahakotiga.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Nüüd, viimane samm, vaata, kas **Online** rahakoti aadressid ühtivad **Offline** rahakoti aadressidega. Kui jah, siis oled valmis. Õnn kaasa.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
