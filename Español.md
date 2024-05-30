**Este tutorial fue traducido del inglés al español usando ChatGPT. Puede haber algunos errores de traducción, ¡pero espero que aún tenga sentido para la comunidad hispanohablante!**

**Tutorial en Español: Creando una Cartera Fría de Bitcoin Usando Tails OS y Almacenamiento Persistente**

En este tutorial, estaré usando Windows 10. También necesitarás un USB con al menos 8GB de espacio.

1. Ve a https://tails.net/install/download/index.pt.html y descarga la Imagen USB.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Después de descargar la imagen USB, verifique la descarga yendo a la página de descargas y subiendo su imagen descargada haciendo clic en el botón que dice **Select your download to verify...** Si la verificación es exitosa, puede continuar; de lo contrario, debe volver a descargar la imagen. Luego, descargue balenaEtcher desde este enlace: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Conecta tu USB y abre balenaEtcher.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Selecciona la imagen USB haciendo clic en el botón **Flash from file**. Tu USB debería ser detectado automáticamente. Si no, asegúrate de seleccionar el USB correcto. Luego, haz clic en el botón **Flash!**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Espera a que termine el proceso de flash.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Una vez terminado, cierra balenaEtcher y arranca desde el USB.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. En Tails, haz clic en el botón **Start** para iniciar Tails OS.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Ve a **Applications** y busca **Persistent Storage** (debería estar en la pestaña Favoritos).

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Haz clic en el botón **Continue**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Crea una contraseña fuerte para encriptar tu instalación de Tails OS.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Espera a que se complete la creación de **Persistent Storage**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. En la siguiente ventana, deberías tener la **Persistent Folder** activada por defecto. Si no, actívala.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Activa la persistencia tanto para **Electrum Bitcoin Wallet** como para **GnuPG**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Reinicia Tails OS e ingresa tu contraseña. Luego, haz clic en el botón **Unlock Encryption** para desbloquear tu Almacenamiento Persistente de Tails.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Una vez desbloqueado el Almacenamiento Persistente, haz clic en el botón **Start Tails**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Ahora, vamos a conectarnos a la Red Tor. Asegúrate de que tu computadora esté conectada a un cable Ethernet o Wi-Fi, y busca **Tor Connection** en **Applications**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Selecciona **Connect to Tor automatically**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Espera a que se conecte a la Red Tor.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Una vez conectado, haz clic en el botón **Start Tor Browser**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. O busca **Tor Browser** en **Applications**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. Con **Tor Browser** abierto, ve a este enlace: https://iancoleman.io/

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Desplázate hacia abajo hasta que veas **GPG My Public Key**. Haz clic derecho en el enlace y selecciona **Save Link As...**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Guarda el archivo en **/home/amnesia/Persistent/Tor Browser**

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Ahora, ve a la página de GitHub de Ian Coleman en este enlace: https://github.com/iancoleman/bip39 y ve a Releases. Puedes acceder a las versiones desde este enlace: https://github.com/iancoleman/bip39/releases

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Descarga tanto **bip39-standalone.html** como **signature.txt.asc**

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. Para descargar **bip39-standalone.html**, simplemente haz clic en él y guárdalo en **/home/amnesia/Persistent/Tor Browser**

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. Para guardar **signature.txt.asc**, haz lo mismo que para la Clave Pública GPG: haz clic derecho en él y selecciona **Save Link As...**

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Guárdalo en **/home/amnesia/Persistent/Tor Browser**

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Puedes ver tus descargas en el icono **Downloads** en la barra del navegador.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Ahora, desconecta a Tails OS de Internet. Vamos a crear nuestra cartera

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Ve a **Applications** y busca **Terminal**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Ahora, importaremos claves y verificaremos si todo está bien con el archivo **bip39-standalone.html** que descargamos. Puedes autocompletar cada comando presionando **Tab**.

Escribe:

- cd Persistent/
- Presiona Enter
- cd Tor\ Browser/
- Presiona Enter
- ls (este comando es para listar los archivos en el directorio, verifica si los 3 archivos que descargamos están ahí)
- Presiona Enter
- gpg --import pubkey.asc
- Presiona Enter
- gpg --verify signature.txt.asc
- Presiona Enter

33. Verifica si dice **Good signature** de Ian. Si dice que es bueno, significa que todos los archivos que descargamos son legítimos.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Ahora veremos si el hash de **bip39-standalone.html** coincide con el hash en el GitHub de Ian.

Escribe:

- sha256sum bip39-standalone.html
- Presiona Enter

35. Verifica tanto el hash en la Terminal como el hash en el GitHub de Ian. Si coinciden, entonces el archivo **bip39-standalone.html** también es legítimo.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Ve a **Places** y selecciona **Tor Browser (persistent)**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Abre el archivo **bip39-standalone.html**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Aquí está nuestro generador offline de cartera de Bitcoin.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Generemos una cartera de 24 palabras (elige entre 12 o 24 para que sea compatible con cualquier otra cartera).

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Haz clic en el botón **GENERATE** y anota tus palabras. Presta MUCHA atención y guarda estas palabras de forma segura. Si las pierdes o alguien las roba, se acabó el juego.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Ahora, ve a **Applications** y busca **Electrum Bitcoin Wallet**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Nombremos nuestra cartera como **Offline** para recordarte que solo debes acceder a ella sin conexión a Internet. Haz clic en **Next**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Selecciona **Standard wallet**. Haz clic en **Next**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Selecciona **I already have a seed**. Haz clic en **Next**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Escribe tus palabras en el cuadro de texto y haz clic en **Options**, aparecerá una ventana pequeña y deberías seleccionar **BIP39 seed** y hacer clic en **OK**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Verifica si dice **BIP39 (checksum: ok)**. Haz clic en **Next**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Selecciona **native segwit (p2wpkh)**. Haz clic en **Next**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Elige una contraseña fuerte para encriptar tu cartera Offline. Haz clic en **Next**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Tu cartera está creada. Ahora vamos a **View** y **Show Addresses** y **Show Coins**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Mira tus direcciones.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Regresa a la página **bip39-standalone** y desplázate hasta **Derivation Path** y haz clic en la pestaña **BIP84**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Verifica si la primera dirección en la página coincide con la primera dirección mostrada en **Electrum Bitcoin Wallet**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Si coinciden todas las primeras direcciones (y la segunda, y la tercera, etc.), significa que tu cartera fue importada correctamente a **Electrum Bitcoin Wallet**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

54. Ahora ve a **Electrum Bitcoin Wallet** y ve a **Information**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Copia tu **Master Public Key** (no compartas esta clave con nadie. Si alguien obtiene acceso a tu Master Public Key, podrá ver tus direcciones y cuánto Bitcoin posees).

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Ahora crearemos otra cartera. Esta vez, será nuestra cartera **Online** (o de solo lectura).

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Selecciona **Standard wallet**. Haz clic en **Next**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Selecciona **Use a master key**. Haz clic en **Next**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Pega tu **Master Public Key** que copiaste de tu cartera **Offline**. Haz clic en **Next**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. No tienes que agregar una contraseña en tu cartera de solo lectura, porque las carteras de solo lectura no pueden enviar monedas, pero depende de ti. Haz clic en **Next**.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Tu cartera de solo lectura está creada, y se te presentará una advertencia que dice **Esta cartera es de solo lectura. Esto significa que no podrás gastar Bitcoins con ella. Asegúrate de tener la frase semilla o las claves privadas, antes de solicitar que se envíen Bitcoins a esta cartera.**

Una cartera de solo lectura es solo para mostrar direcciones y saldo de Bitcoin, puedes enviar Bitcoins desde ella, pero solo si firmas la transacción con tu cartera **Offline** primero.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Ahora, el último paso, verifica si las direcciones de la cartera **Online** coinciden con la cartera **Offline**. Si es así, entonces todo está listo. Buena suerte.

![imagen](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
