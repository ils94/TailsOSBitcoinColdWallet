**Ce tutoriel a été traduit de l'anglais au français en utilisant ChatGPT. Il peut y avoir des erreurs de traduction, mais j'espère qu'il aura toujours du sens pour la communauté francophone !**

**Tutoriel en Français : Créer un Portefeuille Bitcoin Froid en Utilisant Tails OS et un Stockage Persistant**

Dans ce tutoriel, j'utiliserai Windows 10. Vous aurez également besoin d'une clé USB d'au moins 8 Go d'espace.

1. Allez sur https://tails.net/install/download/index.pt.html et téléchargez l'image USB.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Après avoir téléchargé l'image USB, vérifiez le téléchargement en allant sur la page de téléchargement et en téléchargeant votre image téléchargée en cliquant sur le bouton qui dit **Select your download to verify...** Si la vérification est réussie, vous pouvez continuer ; sinon, vous devez retélécharger l'image. Ensuite, téléchargez **balenaEtcher** depuis ce lien : https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Branchez votre clé USB et démarrez **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Sélectionnez l'image USB en cliquant sur le bouton **Flash from file**. Votre clé USB devrait être détectée automatiquement. Sinon, assurez-vous de sélectionner la bonne clé USB. Ensuite, cliquez sur le bouton **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Attendez la fin du processus de flashage.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Une fois terminé, fermez **balenaEtcher** et démarrez à partir de la clé USB.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. Dans Tails, cliquez sur le bouton **Start** pour lancer Tails OS.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Allez dans **Applications** et cherchez **Persistent Storage** (cela devrait être dans l'onglet **Favorites**).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Cliquez sur le bouton **Continue**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Créez un mot de passe fort pour chiffrer votre installation de Tails OS.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Attendez la fin de la création de **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. Dans la fenêtre suivante après la fin, vous devriez avoir le **Persistent Folder** activé par défaut. Sinon, activez-le.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Activez la persistance pour les deux **Electrum Bitcoin Wallet** et **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Redémarrez Tails OS et entrez votre mot de passe. Ensuite, cliquez sur le bouton **Unlock Encryption** pour déverrouiller votre Persistent Storage de Tails.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Une fois le Persistent Storage déverrouillé, cliquez sur le bouton **Start Tails**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Maintenant, connectons-nous au réseau Tor. Assurez-vous que votre ordinateur est connecté à un câble Ethernet ou au Wi-Fi, et cherchez **Tor Connection** dans **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Sélectionnez **Connect to Tor automatically**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Attendez qu'il se connecte au réseau Tor.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Une fois connecté, cliquez sur le bouton **Start Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Ou cherchez **Tor Browser** dans les **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. Avec **Tor Browser** ouvert, allez sur ce lien : https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Faites défiler la page jusqu'à ce que vous voyiez **GPG My Public Key**. Cliquez avec le bouton droit sur le lien et sélectionnez **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Enregistrez le fichier dans **/home/amnesia/Persistent/Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Maintenant, allez sur la page GitHub de Ian Coleman à ce lien : https://github.com/iancoleman/bip39 et allez dans Releases. Vous pouvez accéder aux releases depuis ce lien : https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Téléchargez à la fois **bip39-standalone.html** et **signature.txt.asc**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. Pour télécharger **bip39-standalone.html**, cliquez simplement dessus et enregistrez-le dans **/home/amnesia/Persistent/Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. Pour enregistrer **signature.txt.asc**, faites la même chose que pour la clé publique GPG : cliquez avec le bouton droit dessus et sélectionnez **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Enregistrez-le dans **/home/amnesia/Persistent/Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Vous pouvez voir vos téléchargements dans l'icône **Downloads** dans la barre du navigateur.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Maintenant, déconnectez Tails OS d'Internet. Nous allons maintenant créer notre portefeuille. Cela semble trop paranoïaque, mais soyons prudents, d'accord ?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Allez dans **Applications** et cherchez **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Maintenant, nous allons importer des clés et vérifier si tout est en ordre avec le fichier **bip39-standalone.html** que nous avons téléchargé. Vous pouvez compléter automatiquement chaque commande en appuyant sur **Tab**.

Tapez :

- cd Persistent/
- Appuyez sur Enter
- cd Tor\ Browser/
- Appuyez sur Enter
- ls (cette commande est pour lister les fichiers dans le répertoire, voir si les 3 fichiers que nous avons téléchargés y sont)
- Appuyez sur Enter
- gpg --import pubkey.asc
- Appuyez sur Enter
- gpg --verify signature.txt.asc
- Appuyez sur Enter

33. Vérifiez s'il dit **Good signature** de Ian. S'il dit que c'est bon, cela signifie que tous les fichiers que nous avons téléchargés sont légitimes.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Maintenant, nous allons voir si le hash de **bip39-standalone.html** correspond au hash sur le GitHub de Ian.

Tapez :

- sha256sum bip39-standalone.html
- Appuyez sur Enter

35. Comparez le hash dans le Terminal et le hash sur le GitHub de Ian. S'ils correspondent, alors le fichier **bip39-standalone.html** est également légitime.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Allez dans **Places** et sélectionnez **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Ouvrez le fichier **bip39-standalone.html**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Voici notre générateur de portefeuille Bitcoin hors ligne.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Générons un portefeuille de 24 mots (choisissez 12 ou 24 pour le rendre compatible avec tout autre portefeuille).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Cliquez sur le bouton **GENERATE** et notez vos mots. Faites TRÈS attention et conservez ces mots en sécurité. Si vous les perdez ou si quelqu'un les vole, c'est la fin du jeu.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Maintenant, allez dans **Applications** et cherchez **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Nommons notre portefeuille **Offline** pour vous rappeler que vous ne devez y accéder que sans connexion Internet. Cliquez sur **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Sélectionnez **Standard wallet**. Cliquez sur **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Sélectionnez **I already have a seed**. Cliquez sur **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Tapez vos mots dans la zone de texte, et cliquez sur **Options**, une petite fenêtre apparaîtra, et vous devriez sélectionner **BIP39 seed** et cliquez sur **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Vérifiez si le **BIP39 (checksum: ok)**. Cliquez sur **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Sélectionnez **native segwit (p2wpkh)**. Cliquez sur **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Choisissez un mot de passe fort pour chiffrer votre portefeuille Offline. Cliquez sur **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Votre portefeuille est créé. Maintenant, allons dans **View** et **Show Addresses** et **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Voyez vos adresses.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Revenez à la page **bip39-standalone**, et faites défiler jusqu'à **Derivation Path** et cliquez sur l'onglet **BIP84**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Vérifiez si la première adresse sur la page correspond à la première adresse affichée dans **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Si les deux premières adresses correspondent (et la deuxième, et la troisième, etc.), cela signifie que votre portefeuille a été correctement importé dans **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

54. Maintenant, allez dans **Electrum Bitcoin Wallet** et allez dans **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Copiez votre **Master Public Key** (ne partagez pas cette clé avec qui que ce soit. Si quelqu'un a accès à votre clé publique principale, il pourra voir vos adresses et combien de Bitcoin vous possédez).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Créons maintenant un autre portefeuille. Cette fois, ce sera notre portefeuille **Online** (ou watch-only).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Sélectionnez **Standard wallet**. Cliquez sur **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Sélectionnez **Use a master key**. Cliquez sur **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Collez votre **Master Public Key** que vous avez copiée de votre portefeuille **Offline**. Cliquez sur **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Vous n'avez pas besoin d'ajouter un mot de passe dans votre portefeuille watch-only, car les portefeuilles watch-only ne peuvent pas envoyer de Coins, mais c'est à vous de décider. Cliquez sur **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Votre portefeuille watch-only est créé, et vous recevrez un avertissement disant **Ce portefeuille est en mode consultation uniquement. Cela signifie que vous ne pourrez pas dépenser de Bitcoins avec celui-ci. Assurez-vous de posséder la phrase de récupération ou les clés privées avant de demander que des Bitcoins soient envoyés à ce portefeuille.**

Un portefeuille watch-only est juste pour montrer les adresses et le solde de Bitcoin, vous pouvez envoyer des Bitcoins depuis celui-ci mais seulement si vous signez la transaction avec votre portefeuille **Offline** d'abord.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Maintenant, la dernière étape, vérifiez si les adresses du portefeuille **Online** correspondent au portefeuille **Offline**. Si c'est le cas, alors vous êtes prêt. Bonne chance.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
