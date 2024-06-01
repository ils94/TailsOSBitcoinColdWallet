# To jest bardzo ważne, aby regularnie aktualizować swoją wersję Tails OS, aby uniknąć wszelkiego rodzaju złośliwych ataków, które mogą skraść Twoje bitcoiny! Jeśli używasz przestarzałej wersji Tails OS, pamiętaj, NIGDY nie łącz się z internetem podczas korzystania z portfela offline! Użyj drugiego pendrive'a USB, aby utworzyć swój portfel online, lub skorzystaj z innych metod, aby mieć portfel online na Androidzie lub iOSie, oraz używaj metod do podpisywania swoich transakcji za pomocą kodów QR. Nie ponoszę odpowiedzialności za żadne kradzieże Twoich bitcoinów, jeśli złamiesz jakiekolwiek zasady bezpieczeństwa, w tym ignorowanie tego ostrzeżenia.

**Ten samouczek został przetłumaczony z angielskiego na polski przy użyciu ChatGPT. Mogą występować błędy tłumaczenia, ale mam nadzieję, że wciąż będzie to sensowne dla polskiej społeczności!**

**Polski Przewodnik: Tworzenie Zimnego Portfela Bitcoin przy użyciu Systemu Tails i Trwałego Przechowywania**

W tym tutorialu będę używał Windows 10. Będziesz również potrzebował pendrive’a o pojemności co najmniej 8GB.

1. Przejdź na stronę https://tails.net/install/download/index.en.html i pobierz obraz USB.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Po pobraniu obrazu USB, zweryfikuj pobieranie, przechodząc na stronę pobierania i przesyłając pobrany obraz, klikając przycisk **Select your download to verify...** Jeśli weryfikacja zakończy się pomyślnie, możesz kontynuować; w przeciwnym razie musisz ponownie pobrać obraz. Następnie pobierz **balenaEtcher** z tego linku: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Podłącz pendrive’a i uruchom **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Wybierz obraz USB, klikając przycisk **Flash from file**. Twój pendrive powinien zostać automatycznie wykryty. Jeśli nie, upewnij się, że wybierasz odpowiedni pendrive. Następnie kliknij przycisk **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Poczekaj na zakończenie procesu flashowania.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Po zakończeniu zamknij **balenaEtcher** i uruchom komputer z pendrive’a.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. W Tails, kliknij przycisk **Start**, aby uruchomić Tails OS.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Przejdź do **Applications** i poszukaj **Persistent Storage** (powinno być w zakładce **Favorites**).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Kliknij przycisk **Continue**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Utwórz silne hasło, aby zaszyfrować instalację systemu Tails OS. Kliknij przycisk **Create Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Poczekaj na zakończenie tworzenia **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. W następnym oknie po zakończeniu powinno być domyślnie włączone **Persistent Folder**. Jeśli nie, włącz je.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Włącz trwałość zarówno dla **Electrum Bitcoin Wallet**, jak i **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Uruchom Tails OS i wprowadź swoje hasło. Następnie kliknij przycisk **Unlock Encryption**, aby odblokować swoje **Tails Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Gdy **Persistent Storage** jest odblokowane, kliknij przycisk **Start Tails**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Teraz połączmy się z siecią Tor. Upewnij się, że twój komputer jest podłączony do kabla Ethernet lub Wi-Fi, i wyszukaj **Tor Connection** w **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Wybierz **Connect to Tor automatically**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Poczekaj na połączenie z siecią Tor.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Po połączeniu kliknij przycisk **Start Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Lub wyszukaj **Tor Browser** w **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. Po otwarciu **Tor Browser** przejdź na tę stronę: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Przewiń stronę w dół, aż zobaczysz **GPG My Public Key**. Kliknij prawym przyciskiem myszy na link i wybierz **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Zapisz plik w **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Teraz przejdź na stronę GitHub Iana Colemana pod tym linkiem: https://github.com/iancoleman/bip39 i przejdź do wersji. Możesz uzyskać dostęp do wersji z tego linku: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Pobierz zarówno **bip39-standalone.html**, jak i **signature.txt.asc**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. Aby pobrać **bip39-standalone.html**, po prostu kliknij i zapisz w **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. Aby zapisać **signature.txt.asc**, zrób to samo co dla **GPG Public Key**, kliknij prawym przyciskiem myszy i wybierz **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Zapisz to w **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Możesz zobaczyć swoje pobrane pliki w ikonie **Downloads** na pasku przeglądarki.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Teraz odłącz Tails OS od internetu. Teraz utworzymy nasz portfel. Brzmi to zbyt paranoidalnie, ale bądźmy bezpieczni, ok?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Przejdź do **Applications** i wyszukaj **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Teraz zaimportujemy klucze i sprawdzimy, czy wszystko jest w porządku z pobranym plikiem **bip39-standalone.html**. Możesz uzupełnić każde polecenie, naciskając **Tab**.

Wpisz:

- cd Persistent/
- Naciśnij Enter
- cd Tor\ Browser/
- Naciśnij Enter
- ls (to polecenie służy do wyświetlenia plików w katalogu, sprawdź, czy wszystkie 3 pobrane pliki są w nim)
- Naciśnij Enter
- gpg --import pubkey.asc
- Naciśnij Enter
- gpg --verify signature.txt.asc
- Naciśnij Enter

33. Sprawdź, czy mówi **Good signature** od Iana. Jeśli mówi, że jest dobra, oznacza to, że wszystkie pobrane pliki są legitne.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Teraz sprawdzimy, czy hash **bip39-standalone.html** zgadza się z hashem na GitHubie Iana.

Wpisz:

- sha256sum bip39-standalone.html
- Naciśnij Enter

35. Sprawdź zarówno hash w Terminalu, jak i hash na GitHubie Iana. Jeśli się zgadzają, oznacza to, że plik **bip39-standalone.html** jest również legitny.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Przejdź do **Places** i wybierz **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Otwórz plik **bip39-standalone.html**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Oto nasz offline generator portfela Bitcoin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Wygenerujmy portfel na 24 słowa (wybierz 12 lub 24, aby był kompatybilny z każdym innym portfelem).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Kliknij przycisk **GENERATE** i zapisz swoje słowa. Zwróć DUŻO uwagi i przechowuj te słowa bezpiecznie. Jeśli je zgubisz lub ktoś je ukradnie, to koniec gry.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Teraz przejdź do **Applications** i wyszukaj **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Nazwijmy nasz portfel **Offline**, aby przypomnieć sobie, że powinieneś mieć do niego dostęp tylko bez połączenia z internetem. Naciśnij **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Wybierz **Standard wallet**. Naciśnij **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Wybierz **I already have a seed**. Naciśnij **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Wpisz swoje słowa w polu tekstowym i kliknij **Options**, pojawi się małe okno, w którym powinieneś wybrać **BIP39 seed** i kliknąć **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Sprawdź, czy **BIP39 (checksum: ok)**. Naciśnij **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Wybierz **native segwit (p2wpkh)**. Naciśnij **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Wybierz silne hasło, aby zaszyfrować swój portfel Offline. Naciśnij **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Twój portfel został utworzony. Teraz przejdź do **View** i wybierz **Show Addresses** oraz **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Zobacz swoje adresy.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Wróć do strony **bip39-standalone** i przewiń w dół do **Derivation Path** i kliknij zakładkę **BIP84**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Sprawdź, czy pierwszy adres na stronie odpowiada pierwszemu adresowi wyświetlanemu w **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Jeśli oba pierwsze adresy się zgadzają (i drugi, i trzeci i tak dalej), oznacza to, że twój portfel został poprawnie zaimportowany do **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**To jest moment, w którym tworzymy nasz Portfel Online, i masz dwie opcje:**

- **1- Możesz stworzyć Portfel Online w tej samej instalacji Tails OS, która zawiera Twój Portfel Offline. W tym przypadku NIE ŁĄCZ SIĘ Z INTERNETEM podczas dostępu do Portfela Offline, aby zapobiec jakimkolwiek wektorom ataku na Twoje Bitcoiny.**

- **2- Możesz użyć innego pendrive'a USB, postępując tak samo jak powyżej, a następnie przejdź do kolejnych kroków, aby stworzyć swój Portfel Online na nowym pendrive'ie USB. Pomaga to zapobiec ludzkim błędom polegającym na dostępie do Twojego Portfela Offline podczas połączenia z internetem.**

54. Teraz przejdź do **Electrum Bitcoin Wallet** i wybierz **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Skopiuj swój **Master Public Key** (nie udostępniaj tego klucza nikomu. Jeśli ktoś uzyska dostęp do twojego Master Public Key, będzie mógł zobaczyć twoje adresy i ile Bitcoinów posiadasz).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Teraz stwórzmy kolejny portfel. Tym razem będzie to nasz portfel **Online** (lub tylko do podglądu).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Wybierz **Standard wallet**. Naciśnij **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Wybierz **Use a master key**. Naciśnij **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Wklej swój **Master Public Key**, który skopiowałeś ze swojego portfela **Offline**. Naciśnij **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Nie musiszdodawać hasła do swojego portfela tylko do podglądu, ponieważ portfele tylko do podglądu nie mogą wysyłać monet, ale to zależy od ciebie. Naciśnij **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Twój portfel tylko do podglądu został utworzony, i zostaniesz poinformowany o ostrzeżeniu mówiącym **Ten portfel jest tylko do podglądu. Oznacza to, że nie będziesz mógł wydawać Bitcoinów z tego portfela. Upewnij się, że posiadasz frazę zapasową (seed) lub klucze prywatne, zanim poprosisz o wysłanie Bitcoinów na ten portfel.**

Portfel tylko do podglądu służy tylko do pokazywania adresów i salda Bitcoin, możesz wysyłać Bitcoiny z niego, ale tylko jeśli podpiszesz transakcję swoim portfelem **Offline**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Teraz ostatni krok, sprawdź, czy adresy portfela **Online** zgadzają się z portfelem **Offline**. Jeśli tak, to wszystko jest gotowe. Powodzenia.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
