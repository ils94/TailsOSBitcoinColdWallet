# Det är mycket viktigt att hålla din TailsOS-version uppdaterad för att undvika någon form av skadlig attack som kan stjäla dina bitcoins! Om du använder en föråldrad version av TailsOS, kom ihåg att ALDRIG ansluta till internet när du går åt din offline-plånbok! Använd en andra USB-enhet för att skapa din online-plånbok, eller använd andra metoder för att ha en online-plånbok på Android eller iOS, och använd metoder för att signera dina transaktioner med QR-kod. Jag är inte ansvarig för någon stöld av dina bitcoins om du bryter mot några säkerhetsregler, inklusive att ignorera denna varning.

**Deze handleiding is vertaald van Engels naar Nederlands met behulp van ChatGPT. Er kunnen enkele vertaalfouten zijn, maar ik hoop dat het nog steeds begrijpelijk is voor de Nederlandstalige gemeenschap!**

**Svensk handledning: Skapa en Bitcoin Cold Wallet med TailsOS och Persistent Storage**

I denna handledning kommer jag att använda Windows 10. Du behöver också ett USB-minne med minst 8 GB utrymme.

1. Gå till https://tails.net/install/download/index.en.html och ladda ner **USB image**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Efter att ha laddat ner **USB image**, verifiera nedladdningen genom att gå till nedladdningssidan och ladda upp din nedladdade bild genom att klicka på knappen som säger **Select your download to verify...** Om verifieringen är framgångsrik kan du fortsätta; annars måste du ladda ner bilden igen. Ladda sedan ner **balenaEtcher** från denna länk: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Anslut ditt USB-minne och starta **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Välj **USB image** genom att klicka på knappen **Flash from file**. Ditt USB-minne ska automatiskt upptäckas. Om inte, se till att du väljer rätt USB-minne. Klicka sedan på knappen **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Vänta på att blinkningsprocessen ska slutföras.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. När den är klar, stäng **balenaEtcher** och starta från USB-minnet.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. I **TailsOS**, klicka på knappen **Start Tails** för att starta **TailsOS**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Gå till **Applications** och leta efter **Persistent Storage** (det borde vara i fliken **Favorites**).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Klicka på knappen **Continue**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Skapa ett starkt lösenord för att kryptera din **TailsOS**-installation. Klicka på knappen **Create Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Vänta på att skapandet av **Persistent Storage** ska slutföras.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. I nästa fönster efter slutförandet borde du ha **Persistent Folder** aktiverad som standard. Om inte, aktivera den.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Aktivera uthållighet för både **Electrum Bitcoin Wallet** och **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Starta om **TailsOS** och ange ditt lösenord. Klicka sedan på knappen **Unlock Encryption** för att låsa upp din **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. När **Persistent Storage** är upplåst, klicka på knappen **Start Tails**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Låt oss nu ansluta till Tor-nätverket. Se till att din dator är ansluten till en Ethernet-kabel eller Wi-Fi, och sök efter **Tor Connection** i **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Välj **Connect to Tor automatically** och klicka på knappen **Connect to Tor**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Vänta på att det ska ansluta till Tor-nätverket.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. När du är ansluten, klicka på knappen **Start Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Eller sök efter **Tor Browser** i **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. Med **Tor Browser** öppen, gå till denna länk: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Scrolla ner på sidan tills du ser **GPG My Public Key**. Högerklicka på länken och välj **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Spara filen i **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Gå nu till **Ian Coleman GitHub**-sidan på denna länk: https://github.com/iancoleman/bip39 och gå till Releases. Du kan komma åt utgåvor från denna länk: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Ladda ner både **bip39-standalone.html** och **signature.txt.asc**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. För att ladda ner **bip39-standalone.html**, klicka bara på den och spara den i **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. För att spara **signature.txt.asc**, gör samma sak som för **GPG Public Key** och högerklicka på den och välj **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Spara den i **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Du kan se dina nedladdningar i **Downloads**-ikonen i webbläsarens verktygsfält.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Koppla nu bort **TailsOS** från internet. Vi ska nu skapa vår plånbok. Det låter för paranoid, men låt oss vara säkra, okej?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Gå till **Applications** och sök efter **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Nu ska vi importera nycklar och verifiera om allt är bra med **bip39-standalone.html**-filen vi laddade ner. Du kan autokomplettera varje kommando genom att trycka på **Tab**.

Skriv:

- cd Persistent/
- Tryck på Enter
- cd Tor\ Browser/
- Tryck på Enter
- ls (detta kommando är för att lista filerna i katalogen, se om alla 3 filer vi laddade ner finns där)
- Tryck på Enter
- gpg --import pubkey.asc
- Tryck på Enter
- gpg --verify signature.txt.asc
- Tryck på Enter

33. Kontrollera om det står **Good signature from Ian Coleman <ian@iancoleman.io>**. Om det står att det är bra betyder det att alla filer vi laddade ner är legitima.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Nu ska vi se om hashvärdet för **bip39-standalone.html** matchar hashvärdet på Ian's GitHub.

Skriv:

- sha256sum bip39-standalone.html
- Tryck på Enter

35. Kontrollera både hashvärdet i Terminalen och hashvärdet på **Ian Coleman GitHub**. Om de matchar, är **bip39-standalone.html**-filen också legitim.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Gå till **Places** och välj **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Öppna **bip39-standalone.html**-filen.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Här är vår Bitcoin-plånbok offline-generator.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Låt oss generera en 24-ords plånbok (välj antingen 12 eller 24 för att göra den kompatibel med alla andra plånböcker).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Klicka på knappen **GENERATE** och skriv ner dina ord. Var mycket uppmärksam och förvara dessa ord säkert. Om du tappar bort dem eller om någon stjäl dem, är det game over.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Gå nu till **Applications** och sök efter **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Låt oss namnge vår plånbok **Offline** för att påminna dig om att du endast ska komma åt den utan internetanslutning. Klicka på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Välj **Standard wallet**. Klicka på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Välj **I already have a seed**. Klicka på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Skriv in dina ord i textfältet och klicka på **Options**, ett litet fönster kommer att visas, och du ska välja **BIP39 seed** och klicka på **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Se om det står **BIP39 (checksum: ok)**. Klicka på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Välj **native segwit (p2wpkh)**. Klicka på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Välj ett starkt lösenord för att kryptera din **Offline** plånbok. Klicka på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Din plånbok är skapad. Gå nu till **View** och välj **Show Addresses** och **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Se dina adresser.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Gå tillbaka till **bip39-standalone**-sidan och scrolla ner till **Derivation Path** och klicka på **BIP84**-fliken.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Se om den första adressen på webbsidan matchar den första adressen som visas i **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Om båda första adresserna matchar (och den andra, och den tredje och så vidare) betyder det att din plånbok korrekt importerades till **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**Det här är det avsnitt där vi skapar vår Online Plånbok, och du har två alternativ:**

- **1- Du kan skapa den Online Plånboken inom samma installation av TailsOS som innehåller din Offline Plånbok. I det här fallet bör du INTE ANSLUTA TILL INTERNET när du går åt den Offline Plånboken för att förhindra eventuella attackvektorer mot dina Bitcoins.**

- **2- Du kan använda en annan USB-sticka, följa samma process som ovan, och sedan följa de nästa stegen för att skapa din Online Plånbok på den nya USB-stickan. Detta hjälper till att förhindra mänskliga fel av att komma åt din Offline Plånbok medan du är ansluten till internet.**

54. Gå nu till **Electrum Bitcoin Wallet** och gå till **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Kopiera din **Master Public Key** (dela inte denna nyckel med någon. Om någon får tillgång till din **Master Public Key**, kommer de att kunna se dina adresser och hur mycket Bitcoin du äger).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Låt oss nu skapa en annan plånbok. Denna gång kommer det att vara vår **Online** plånbok (eller endast för visning).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Välj **Standard wallet**. Klicka på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Välj **Use a master key**. Klicka på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Klistra in din **Master Public Key** som du kopierade från din **Offline** plånbok. Klicka på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Du behöver inte lägga till ett lösenord i din endast-visningsplånbok, eftersom endast-visningsplånböcker inte kan skicka mynt, men det är upp till dig. Klicka på **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Din endast-visningsplånbok är skapad, och du kommer att presenteras med en varning som säger **Den här plånboken är enbart för granskning. Det innebär att du inte kommer att kunna spendera Bitcoins med den. Se till att du äger fröfrasen eller privata nycklar innan du begär att Bitcoins ska skickas till den här plånboken.**

En endast-visningsplig plånbok är bara för att visa adresser och Bitcoin-saldo, du kan skicka Bitcoins från den men endast om du signerar transaktionen med din **Offline** plånbok först.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Nu, det sista steget, se om adresserna för **Online** plånboken matchar **Offline** plånboken. Om så är fallet är du klar. Lycka till.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
