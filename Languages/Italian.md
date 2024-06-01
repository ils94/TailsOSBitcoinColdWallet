# È molto importante mantenere aggiornata la tua versione di Tails OS per evitare qualsiasi tipo di attacco malevolo che potrebbe rubare i tuoi Bitcoin! Se stai utilizzando una versione obsoleta di Tails OS, ricorda di NON collegarti mai a internet quando accedi al tuo portafoglio offline! Utilizza una seconda chiavetta USB per creare il tuo portafoglio online, o utilizza altri mezzi per avere un portafoglio online su Android o iOS, e utilizza metodi per firmare le tue transazioni tramite codice QR. Non sono responsabile di eventuali furti dei tuoi Bitcoin se violi qualsiasi regola di sicurezza, incluso ignorare questo avvertimento.

**Questo tutorial è stato tradotto dall'inglese all'italiano usando ChatGPT. Potrebbero esserci alcuni errori di traduzione, ma spero che abbia comunque senso per la comunità di lingua italiana!**

**Tutorial Italiano: Creazione di un Portafoglio Freddo Bitcoin Utilizzando Tails OS e Memoria Persistente**

In questo tutorial, utilizzerò Windows 10. Avrai anche bisogno di una chiavetta USB con almeno 8GB di spazio.

1. Vai su https://tails.net/install/download/index.pt.html e scarica l'immagine USB.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Dopo aver scaricato l'immagine USB, verifica il download andando alla pagina di download e caricando l'immagine scaricata cliccando il pulsante che dice **Select your download to verify...**. Se la verifica è riuscita, puoi procedere; altrimenti, devi riscaricare l'immagine. Poi, scarica **balenaEtcher** da questo link: https://tails.net/etcher/balenaEtcher-portable.exe.

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Collega la tua chiavetta USB e avvia **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Seleziona l'immagine USB cliccando il pulsante **Flash from file**. La tua chiavetta USB dovrebbe essere rilevata automaticamente. In caso contrario, assicurati di selezionare la chiavetta USB corretta. Poi, clicca il pulsante **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Attendi il completamento del processo di flashing.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Una volta terminato, chiudi **balenaEtcher** e avvia il sistema dal dispositivo USB.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. In Tails, clicca il pulsante **Start** per avviare Tails OS.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Vai su **Applications** e cerca **Persistent Storage** (dovrebbe essere nella scheda **Favorites**).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Clicca il pulsante **Continue**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Crea una password sicura per crittografare l'installazione del tuo Tails OS. Clicca sul pulsante **Create Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Attendi il completamento della creazione della **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. Nella finestra successiva, una volta completata, dovresti avere la **Persistent Folder** attivata di default. In caso contrario, attivala.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Attiva la persistenza sia per **Electrum Bitcoin Wallet** sia per **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Riavvia Tails OS ed inserisci la tua password. Poi, clicca sul pulsante **Unlock Encryption** per sbloccare il tuo **Tails Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Una volta che il **Persistent Storage** è sbloccato, clicca sul pulsante **Start Tails**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Ora, connettiamoci alla rete Tor. Assicurati che il tuo computer sia connesso tramite cavo Ethernet o Wi-Fi e cerca **Tor Connection** in **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Seleziona **Connect to Tor automatically**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Attendi la connessione alla rete Tor.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Una volta connesso, clicca il pulsante **Start Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Oppure cerca **Tor Browser** in **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. Con **Tor Browser** aperto, vai a questo link: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Scorri la pagina fino a vedere **GPG My Public Key**. Clicca con il tasto destro sul link e seleziona **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Salva il file in **/home/amnesia/Persistent/Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Ora, vai alla pagina GitHub di Ian Coleman a questo link: https://github.com/iancoleman/bip39 e vai a Releases. Puoi accedere alle releases da questo link: https://github.com/iancoleman/bip39/releases.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Scarica entrambi **bip39-standalone.html** e **signature.txt.asc**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. Per scaricare **bip39-standalone.html**, cliccalo e salvalo in **/home/amnesia/Persistent/Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. Per salvare **signature.txt.asc**, fai lo stesso come per la **GPG Public Key** e clicca con il tasto destro su di essa e seleziona **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Salvalo in **/home/amnesia/Persistent/Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Puoi vedere i tuoi download nell'icona **Downloads** nella barra del browser.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Ora, disconnetti Tails OS da internet. Creeremo il nostro portafoglio ora. Sembra troppo paranoico, ma meglio essere sicuri, ok?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Vai su **Applications** e cerca **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Ora, importeremo le chiavi e verificheremo se tutto è a posto con il file **bip39-standalone.html** che abbiamo scaricato. Puoi completare automaticamente ogni comando premendo **Tab**.

Digita:

- cd Persistent/
- Premi Invio
- cd Tor\ Browser/
- Premi Invio
- ls (questo comando serve a elencare i file nella directory, verifica se tutti i 3 file che abbiamo scaricato sono presenti)
- Premi Invio
- gpg --import pubkey.asc
- Premi Invio
- gpg --verify signature.txt.asc
- Premi Invio

33. Controlla se dice **Good signature** da Ian. Se dice che è buona, significa che tutti i file scaricati sono legittimi.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Ora verificheremo se l'hash di **bip39-standalone.html** corrisponde all'hash su GitHub di Ian.

Digita:

- sha256sum bip39-standalone.html
- Premi Invio

35. Confronta l'hash nel Terminale con l'hash su GitHub di Ian. Se corrispondono, il file **bip39-standalone.html** è anche legittimo.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Vai su **Places** e seleziona **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Apri il file **bip39-standalone.html**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Ecco il nostro generatore offline di portafogli Bitcoin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Generiamo un portafoglio da 24 parole (scegli tra 12 o 24 per renderlo compatibile con qualsiasi altro portafoglio).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Clicca il pulsante **GENERATE** e annota le tue parole. Presta MOLTA attenzione e conserva queste parole in modo sicuro. Se le perdi o se qualcuno te le ruba, è finita.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Ora, vai su **Applications** e cerca **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Nomina il tuo portafoglio **Offline** per ricordarti che dovresti accedervi solo senza connessione a internet. Premi **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Seleziona **Standard wallet**. Premi **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Seleziona **I already have a seed**. Premi **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Inserisci le tue parole nella casella di testo, e clicca **Options**, apparirà una piccola finestra, e dovresti selezionare **BIP39 seed** e cliccare **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Verifica se dice **BIP39 (checksum: ok)**. Premi **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Seleziona **native segwit (p2wpkh)**. Premi **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Scegli una password forte per crittografare il tuo portafoglio **Offline**. Premi **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Il tuo portafoglio è stato creato. Ora vai su **View** e **Show Addresses** e **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Guarda i tuoi indirizzi.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Torna alla pagina **bip39-standalone** e scorri fino a **Derivation Path** e clicca la scheda **BIP84**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Verifica se il primo indirizzo nella pagina web corrisponde al primo indirizzo mostrato nel **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Se entrambi i primi indirizzi corrispondono (e il secondo, e il terzo e così via), significa che il tuo portafoglio è stato importato correttamente in **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**Questa è la parte in cui creiamo il nostro Online Wallet, e hai due opzioni:**

- **1- Puoi creare l'Online Wallet all'interno della stessa installazione di Tails OS che contiene il tuo Offline Wallet. In questo caso, NON DOVRESTI CONNETTERTI A INTERNET quando accedi all'Offline Wallet per prevenire qualsiasi vettore di attacco sui tuoi Bitcoin.**

- **2- Puoi usare un'altra chiavetta USB, seguire lo stesso processo di cui sopra e poi seguire i prossimi passaggi per creare il tuo Online Wallet sulla nuova chiavetta USB. Questo aiuta a prevenire l'errore umano di accedere al tuo Offline Wallet mentre sei connesso a internet.**

54. Ora vai su **Electrum Bitcoin Wallet** e vai su **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Copia il tuo **Master Public Key** (non condividere questa chiave con nessuno. Se qualcuno ha accesso al tuo Master Public Key, potrà vedere i tuoi indirizzi e quanto Bitcoin possiedi).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Ora creiamo un altro portafoglio. Questa volta, sarà il nostro portafoglio **Online** (o solo di visualizzazione).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Seleziona **Standard wallet**. Premi **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Seleziona **Use a master key**. Premi **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Incolla il tuo **Master Public Key** che hai copiato dal tuo portafoglio **Offline**. Premi **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Non è necessario aggiungere una password nel portafoglio solo di visualizzazione, poiché i portafogli solo di visualizzazione non possono inviare monete, ma la scelta è tua. Premi **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Il tuo portafoglio solo di visualizzazione è stato creato e ti verrà presentato un avviso che dice **Questo portafoglio è solo di visualizzazione. Ciò significa che non sarai in grado di spendere Bitcoin con esso. Assicurati di possedere la frase di recupero o le chiavi private, prima di richiedere l'invio di Bitcoin a questo portafoglio.**

Un portafoglio solo di visualizzazione serve solo a mostrare gli indirizzi e il saldo Bitcoin, puoi inviare Bitcoin da esso ma solo se firmi la transazione con il tuo portafoglio **Offline** prima.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Ora, l'ultimo passaggio, verifica se gli indirizzi del portafoglio **Online** corrispondono al portafoglio **Offline**. Se sì, allora sei a posto. Buona fortuna.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
