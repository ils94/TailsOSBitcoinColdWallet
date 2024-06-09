# Vrlo je važno da vaša verzija TailsOS-a bude ažurirana kako biste izbjegli bilo kakve zlonamjerne napade koji bi mogli ukrasti vaše Bitcoine! Ako koristite zastarjelu verziju TailsOS-a, sjetite se NIKADA se ne povezivati s internetom kada pristupate svom offline novčaniku! Koristite drugi USB pogon za kreiranje svog online novčanika ili koristite druge metode za imati online novčanik na Androidu ili iOS-u te koristite metode za potpisivanje svojih transakcija pomoću QR koda. Nisam odgovoran za bilo kakvu krađu vaših Bitcoina ako prekršite bilo koje sigurnosne pravila, uključujući ignoriranje ovog upozorenja.

**Ovaj vodič je preveden s engleskog na hrvatski koristeći ChatGPT. Moguće je da ima nekih grešaka u prijevodu, ali se nadam da će i dalje imati smisla za zajednicu koja govori hrvatski!**

**Hrvatski vodič: Kreiranje Bitcoin hladnog novčanika koristeći TailsOS i trajnu pohranu**

U ovom vodiču, koristit ću Windows 10. Trebat će vam i USB stick s najmanje 8GB prostora.

1. Idite na https://tails.net/install/download/index.en.html i preuzmite **USB image**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Nakon preuzimanja **USB image**, provjerite preuzimanje odlaskom na stranicu za preuzimanje i učitajte svoju preuzetu sliku klikom na gumb koji kaže **Select your download to verify...** Ako je provjera uspješna, možete nastaviti; u suprotnom, morate ponovno preuzeti sliku. Zatim preuzmite **balenaEtcher** s ove poveznice: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Priključite svoj USB stick i pokrenite **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Odaberite **USB image** klikom na gumb **Flash from file**. Vaš USB stick bi trebao biti automatski prepoznat. Ako nije, provjerite jeste li odabrali ispravan USB stick. Zatim kliknite na gumb **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Pričekajte da se proces flashanja završi.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Kada završite, zatvorite **balenaEtcher** i pokrenite sustav s USB sticka.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. U **TailsOS**, kliknite gumb **Start Tails** za pokretanje **TailsOS**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Idite na **Applications** i potražite **Persistent Storage** (trebalo bi biti u kartici **Favorites**).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Kliknite gumb **Continue**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Kreirajte jaku lozinku za enkripciju svoje **TailsOS** instalacije. Kliknite gumb **Create Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Pričekajte da se kreiranje **Persistent Storage** završi.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. U sljedećem prozoru nakon završetka, trebali biste imati **Persistent Folder** uključen prema zadanim postavkama. Ako nije, uključite ga.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Uključite trajnost za **Electrum Bitcoin Wallet** i **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Ponovno pokrenite **TailsOS** i unesite svoju lozinku. Zatim kliknite gumb **Unlock Encryption** za otključavanje **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Kada je **Persistent Storage** otključan, kliknite na gumb **Start Tails**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Sada se povežimo na Tor mrežu. Provjerite je li vaše računalo spojeno na Ethernet kabel ili Wi-Fi i potražite **Tor Connection** u **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Odaberite **Connect to Tor automatically** i kliknite gumb **Connect to Tor**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Pričekajte da se poveže na Tor mrežu.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Kada se poveže, kliknite gumb **Start Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Ili potražite **Tor Browser** u **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. S otvorenim **Tor Browser**, idite na ovu poveznicu: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Skrolajte dolje dok ne vidite **GPG My Public Key**. Desnom tipkom miša kliknite poveznicu i odaberite **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Spremite datoteku u **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Sada idite na **Ian Coleman GitHub** stranicu na ovoj poveznici: https://github.com/iancoleman/bip39 i idite na Releases. Možete pristupiti izdanjima s ove poveznice: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Preuzmite obje datoteke **bip39-standalone.html** i **signature.txt.asc**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. Da biste preuzeli **bip39-standalone.html**, jednostavno kliknite na nju i spremite je u **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. Da biste spremili **signature.txt.asc**, učinite isto kao i za **GPG Public Key** i desnom tipkom miša kliknite na nju i odaberite **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Spremite je u **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Možete vidjeti svoje preuzimanja u ikoni **Downloads** u traci preglednika.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Sada isključite **TailsOS** s interneta. Sada ćemo stvoriti naš novčanik. Zvuči previše paranoično, ali budimo sigurni, u redu?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Idite na **Applications** i potražite **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Sada ćemo uvesti ključeve i provjeriti je li sve u redu s datotekom **bip39-standalone.html** koju smo preuzeli. Možete automatski dovršiti svaki naredbu pritiskom na **Tab**.

Upišite:

- cd Persistent/
- Pritisnite Enter
- cd Tor\ Browser/
- Pritisnite Enter
- ls (ova naredba je za popis datoteka u direktoriju, provjerite jesu li sve tri datoteke koje smo preuzeli u njemu)
- Pritisnite Enter
- gpg --import pubkey.asc
- Pritisnite Enter
- gpg --verify signature.txt.asc
- Pritisnite Enter

33. Provjerite piše li **Good signature from Ian Coleman <ian@iancoleman.io>**. Ako piše da je dobra, to znači da su sve preuzete datoteke legitimne.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Sada ćemo provjeriti je li hash **bip39-standalone.html** odgovara hashu na Ianovom GitHubu.

Upišite:

- sha256sum bip39-standalone.html
- Pritisnite Enter

35. Provjerite oba hash-a u Terminalu i hash na **Ian Coleman GitHub**. Ako se podudaraju, datoteka **bip39-standalone.html** također je legitimna.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Idite na **Places** i odaberite **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Otvorite datoteku **bip39-standalone.html**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Ovo je naš generator Bitcoin novčanika izvan mreže.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Stvorimo novčanik s 24 riječi (odaberite ili 12 ili 24 kako bi bio kompatibilan s bilo kojim drugim novčanikom).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Kliknite na gumb **GENERATE** i zapišite svoje riječi. Obratite puno pažnje i spremite te riječi na sigurno. Ako ih izgubite ili ih netko ukrade, igra je gotova.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Sada idite na **Applications** i potražite **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Nazovimo naš novčanik **Offline** kako bismo se podsjetili da mu trebate pristupati samo bez internetske veze. Pritisnite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Odaberite **Standard wallet**. Pritisnite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Odaberite **I already have a seed**. Pritisnite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Upišite svoje riječi u tekstualni okvir i kliknite **Options**, pojavit će se mali prozor i trebate odabrati **BIP39 seed** i kliknite **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Provjerite piše li **BIP39 (checksum: ok)**. Pritisnite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Odaberite **native segwit (p2wpkh)**. Pritisnite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Odaberite jaku lozinku za enkripciju vašeg **Offline** novčanika. Pritisnite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Vaš novčanik je stvoren. Sada idite na **View** i **Show Addresses** i **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Pogledajte svoje adrese.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Vratite se na stranicu **bip39-standalone** i skrolajte dolje do **Derivation Path** i kliknite na karticu **BIP84**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Provjerite odgovara li prva adresa na web stranici prvoj adresi prikazanoj u **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Ako se obje prve adrese podudaraju (i druga, i treća i tako dalje), to znači da je vaš novčanik pravilno uvezen u **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**Ovo je dio gdje stvaramo naš Online Novčanik, i imate dvije opcije:**

**1- Možete stvoriti Online Novčanik unutar iste instalacije TailsOS-a koja sadrži vaš Offline Novčanik. U ovom slučaju, NE BISTE TREBALI BITI SPOJENI NA INTERNET kada pristupate Offline Novčaniku kako biste spriječili bilo kakve vektore napada na vaše Bitcoine.**

**2- Možete koristiti drugi USB stick, slijediti isti postupak kao i gore navedeno, a zatim slijediti sljedeće korake kako biste stvorili svoj Online Novčanik na novom USB sticku. Ovo pomaže u sprječavanju ljudske pogreške prilikom pristupa vašem Offline Novčaniku dok ste spojeni na internet.**

54. Sada idite na **Electrum Bitcoin Wallet** i idite na **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Kopirajte svoj **Master Public Key** (nemojte dijeliti ovaj ključ s nikim. Ako netko dobije pristup vašem **Master Public Key**, moći će vidjeti vaše adrese i koliko Bitcoina imate).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Sada stvorimo drugi novčanik. Ovaj put, bit će to naš **Online** novčanik (ili samo za gledanje).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Odaberite **Standard wallet**. Pritisnite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Odaberite **Use a master key**. Pritisnite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Zalijepite svoj **Master Public Key** koji ste kopirali iz svog **Offline** novčanika. Pritisnite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Ne morate dodati lozinku u svoj novčanik samo za gledanje, jer novčanici samo za gledanje ne mogu slati Coine, ali to je na vama. Pritisnite **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Vaš novčanik samo za gledanje je stvoren i bit ćete obaviješteni s upozorenjem koje kaže **Ovaj novčanik je samo za praćenje. To znači da nećete moći trošiti Bitcoine s njim. Provjerite posjedujete li frazu za oporavak ili privatne ključeve prije nego što zatražite da se Bitcoini pošalju na ovaj novčanik.**

Novčanik samo za gledanje je samo za prikazivanje adresa i Bitcoin stanja, možete slati Bitcoine iz njega samo ako potpišete transakciju s vašim **Offline** novčanikom prvo.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Sada, zadnji korak, provjerite odgovaraju li adrese **Online** novčanika adresama **Offline** novčanika. Ako je tako, onda ste sve postavili. Sretno.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
