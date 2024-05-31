**Dieses Tutorial wurde von Englisch nach Deutsch mit ChatGPT übersetzt. Es können einige Übersetzungsfehler vorhanden sein, aber ich hoffe, es macht trotzdem Sinn für die Deutsch sprechende Community!**

**Deutsches Tutorial: Erstellen einer Bitcoin Cold Wallet mit Tails OS und Persistentem Speicher**

In diesem Tutorial verwende ich Windows 10. Sie benötigen auch einen USB-Stick mit mindestens 8 GB Speicherplatz.

1. Gehen Sie zu https://tails.net/install/download/index.pt.html und laden Sie das USB-Image herunter.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Nach dem Herunterladen des USB-Images überprüfen Sie den Download, indem Sie auf die Download-Seite gehen und Ihr heruntergeladenes Image hochladen, indem Sie auf die Schaltfläche klicken, die **Select your download to verify...** sagt. Wenn die Überprüfung erfolgreich ist, können Sie fortfahren. Andernfalls müssen Sie das Image erneut herunterladen. Laden Sie dann balenaEtcher von diesem Link herunter: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Stecken Sie Ihren USB-Stick ein und starten Sie balenaEtcher.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Wählen Sie das USB-Image aus, indem Sie auf die Schaltfläche **Flash from file** klicken. Ihr USB-Stick sollte automatisch erkannt werden. Wenn nicht, stellen Sie sicher, dass Sie den richtigen USB-Stick auswählen. Klicken Sie dann auf die Schaltfläche **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Warten Sie, bis der Flash-Vorgang abgeschlossen ist.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Sobald der Vorgang abgeschlossen ist, schließen Sie balenaEtcher und starten Sie von dem USB-Stick.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. Klicken Sie in Tails auf die Schaltfläche **Start**, um Tails OS zu starten.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Gehen Sie zu **Applications** und suchen Sie nach **Persistent Storage** (es sollte im Favoriten-Tab sein).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Klicken Sie auf die Schaltfläche **Continue**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Erstellen Sie ein starkes Passwort, um Ihre Tails OS-Installation zu verschlüsseln.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Warten Sie, bis die Erstellung des **Persistent Storage** abgeschlossen ist.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. In dem nächsten Fenster nach Abschluss sollte der **Persistent Folder** standardmäßig aktiviert sein. Wenn nicht, aktivieren Sie ihn.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Aktivieren Sie die Persistenz sowohl für die **Electrum Bitcoin Wallet** als auch für **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Starten Sie Tails OS neu und geben Sie Ihr Passwort ein. Klicken Sie dann auf die Schaltfläche **Unlock Encryption**, um Ihren Tails Persistenten Speicher zu entsperren.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Sobald der Persistente Speicher entsperrt ist, klicken Sie auf die Schaltfläche **Start Tails**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Verbinden Sie sich nun mit dem Tor-Netzwerk. Stellen Sie sicher, dass Ihr Computer mit einem Ethernet-Kabel oder WLAN verbunden ist, und suchen Sie nach **Tor Connection** in **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Wählen Sie **Connect to Tor automatically**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Warten Sie, bis die Verbindung zum Tor-Netzwerk hergestellt ist.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Sobald verbunden, klicken Sie auf die Schaltfläche **Start Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Oder suchen Sie nach **Tor Browser** in den **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. Mit dem **Tor Browser** geöffnet, gehen Sie zu diesem Link: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Scrollen Sie auf der Seite nach unten, bis Sie **GPG My Public Key** sehen. Klicken Sie mit der rechten Maustaste auf den Link und wählen Sie **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Speichern Sie die Datei in **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Gehen Sie nun auf Ian Colemans GitHub-Seite unter diesem Link: https://github.com/iancoleman/bip39 und gehen Sie zu Releases. Sie können auf die Releases über diesen Link zugreifen: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Laden Sie sowohl **bip39-standalone.html** als auch **signature.txt.asc** herunter

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. Um **bip39-standalone.html** herunterzuladen, klicken Sie einfach darauf und speichern Sie es in **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. Um **signature.txt.asc** zu speichern, tun Sie dasselbe wie für den GPG Public Key: Klicken Sie mit der rechten Maustaste darauf und wählen Sie **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Speichern Sie es in **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Sie können Ihre Downloads im **Downloads** -Symbol in der Browserleiste sehen.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Trennen Sie nun Tails OS vom Internet. Wir werden jetzt unser Wallet erstellen. Es klingt zu paranoid, aber seien wir vorsichtig, okay?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Gehen Sie zu **Applications** und suchen Sie nach **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Jetzt werden wir Schlüssel importieren und überprüfen, ob alles mit der Datei **bip39-standalone.html**, die wir heruntergeladen haben, in Ordnung ist. Sie können jeden Befehl durch Drücken der **Tab** -Taste vervollständigen.

Tippen Sie:

- cd Persistent/
- Drücken Sie Enter
- cd Tor\ Browser/
- Drücken Sie Enter
- ls (dieser Befehl listet die Dateien im Verzeichnis auf, sehen Sie nach, ob alle 3 Dateien, die wir heruntergeladen haben, darin enthalten sind)
- Drücken Sie Enter
- gpg --import pubkey.asc
- Drücken Sie Enter
- gpg --verify signature.txt.asc
- Drücken Sie Enter

33. Überprüfen Sie, ob **Good signature** von Ian angezeigt wird. Wenn es gut ist, bedeutet das, dass alle von uns heruntergeladenen Dateien legitim sind.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Jetzt werden wir überprüfen, ob der Hash von **bip39-standalone.html** mit dem Hash auf Ians GitHub übereinstimmt.

Tippen Sie:

- sha256sum bip39-standalone.html
- Drücken Sie Enter

35. Überprüfen Sie sowohl den Hash im Terminal als auch den Hash auf Ians GitHub. Wenn sie übereinstimmen, ist die Datei **bip39-standalone.html** ebenfalls legitim.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Gehen Sie zu **Places** und wählen Sie **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Öffnen Sie die Datei **bip39-standalone.html**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Hier ist unser Bitcoin Wallet Offline-Generator.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Generieren wir ein 24-Wort-Wallet (wählen Sie entweder 12 oder 24, um es mit jedem anderen Wallet kompatibel zu machen).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Klicken Sie auf die Schaltfläche **GENERATE** und notieren Sie Ihre Wörter. Achten Sie sehr darauf und speichern Siesie sicher. Wenn Sie sie verlieren oder wenn sie gestohlen werden, ist es vorbei.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Gehen Sie jetzt zu **Applications** und suchen Sie nach **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Nennen wir unser Wallet **Offline**, um Sie daran zu erinnern, dass Sie nur darauf zugreifen sollten, wenn Sie nicht mit dem Internet verbunden sind. Klicken Sie auf **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Wählen Sie **Standard Wallet**. Klicken Sie auf **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Wählen Sie **I already have a seed**. Klicken Sie auf **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Geben Sie Ihre Wörter in das Textfeld ein und klicken Sie auf **Options**, ein kleines Fenster wird erscheinen, und Sie sollten **BIP39 seed** auswählen und auf **OK** klicken.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Überprüfen Sie, ob der **BIP39 (checksum: ok)**. Klicken Sie auf **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Wählen Sie **native segwit (p2wpkh)**. Klicken Sie auf **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Wählen Sie ein starkes Passwort, um Ihr Offline-Wallet zu verschlüsseln. Klicken Sie auf **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Ihr Wallet ist erstellt. Gehen Sie jetzt zu **View** und wählen Sie **Show Addresses** und **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Sehen Sie Ihre Adressen.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Gehen Sie zurück zur **bip39-standalone** Seite und scrollen Sie zu **Derivation Path** und klicken Sie auf den **BIP84** Tab.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Überprüfen Sie, ob die erste Adresse auf der Webseite mit der ersten Adresse in der **Electrum Bitcoin Wallet** übereinstimmt.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Wenn beide ersten Adressen übereinstimmen (und die zweite und die dritte und so weiter), bedeutet das, dass Ihr Wallet korrekt in die **Electrum Bitcoin Wallet** importiert wurde.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

54. Gehen Sie jetzt zur **Electrum Bitcoin Wallet** und gehen Sie zu **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Kopieren Sie Ihren **Master Public Key** (geben Sie diesen Schlüssel nicht an Dritte weiter. Wenn jemand Zugriff auf Ihren Master Public Key erhält, kann er Ihre Adressen und den Betrag an Bitcoin sehen, den Sie besitzen).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Erstellen wir jetzt ein weiteres Wallet. Diesmal wird es unser **Online**-Wallet sein (oder nur zum Anzeigen).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Wählen Sie **Standard Wallet**. Klicken Sie auf **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Wählen Sie **Use a master key**. Klicken Sie auf **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Fügen Sie Ihren **Master Public Key** ein, den Sie aus Ihrem **Offline**-Wallet kopiert haben. Klicken Sie auf **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Sie müssen kein Passwort in Ihrem nur zum Anzeigen Wallet hinzufügen, da nur zum Anzeigen Wallets keine Coins senden können, aber es liegt an Ihnen. Klicken Sie auf **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Ihr nur zum Anzeigen Wallet ist erstellt, und Sie erhalten eine Warnung, die besagt **Dieses Wallet ist nur zum Anzeigen. Das bedeutet, dass Sie keine Bitcoins damit senden können. Stellen Sie sicher, dass Sie die Seed-Phrase oder die privaten Schlüssel besitzen, bevor Sie Bitcoins an dieses Wallet senden lassen.**

Ein nur zum Anzeigen Wallet dient nur zum Anzeigen von Adressen und dem Bitcoin-Guthaben. Sie können Bitcoins von ihm senden, aber nur, wenn Sie die Transaktion mit Ihrem **Offline**-Wallet zuerst signieren.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Überprüfen Sie nun, ob die Adressen des **Online**-Wallets mit dem **Offline**-Wallet übereinstimmen. Wenn ja, dann sind Sie fertig. Viel Glück.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
