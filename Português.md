**Tutorial em Português: Criando uma Carteira Fria de Bitcoin Usando Tails OS e Armazenamento Persistente**

Neste tutorial, usarei o Windows 10. Você também precisará de um pen drive com pelo menos 8GB de espaço.

1. Acesse https://tails.net/install/download/index.pt.html e baixe a imagem USB.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Após baixar a imagem USB, baixe o balenaEtcher deste link: https://tails.net/etcher/balenaEtcher-portable.exe

3. Conecte o pen drive e inicie o balenaEtcher.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Selecione a imagem USB clicando no botão **Flash from file**. Seu pen drive deve ser detectado automaticamente. Se não for, certifique-se de selecionar o pen drive correto. Em seguida, clique no botão **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Aguarde a conclusão do processo de gravação.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Quando terminar, feche o balenaEtcher e inicialize a partir do pen drive.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. No Tails, clique no botão **Start** para iniciar o Tails OS.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Vá para **Applications** e procure por **Persistent Storage** (deve estar na aba Favoritos).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Clique no botão **Continue**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Crie uma senha forte para criptografar sua instalação do Tails OS.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Aguarde a conclusão da criação do **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. Na próxima janela após a conclusão, o **Persistent Folder** deve estar ativado por padrão. Se não estiver, ative-o.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Ative a persistência tanto para o **Electrum Bitcoin Wallet** quanto para o **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Reinicie o Tails OS e insira sua senha. Em seguida, clique no botão **Unlock Encryption** para desbloquear seu armazenamento persistente do Tails.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Uma vez que o armazenamento persistente esteja desbloqueado, clique no botão **Start Tails**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Agora, vamos nos conectar à rede Tor. Certifique-se de que seu computador está conectado a um cabo Ethernet ou Wi-Fi e procure por **Tor Connection** em **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Selecione **Connect to Tor automatically**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Aguarde a conexão à rede Tor.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Uma vez conectado, clique no botão **Start Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Ou procure por **Tor Browser** em **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. Com o **Tor Browser** aberto, acesse este link: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Role a página até ver **GPG My Public Key**. Clique com o botão direito no link e selecione **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Salve o arquivo em **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Agora, acesse a página do GitHub de Ian Coleman neste link: https://github.com/iancoleman/bip39 e vá para Releases. Você pode acessar os releases deste link: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Baixe ambos **bip39-standalone.html** e **signature.txt.asc**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. Para baixar **bip39-standalone.html**, clique nele e salve em **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. Para salvar **signature.txt.asc**, faça o mesmo que para a chave pública GPG: clique com o botão direito e selecione **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Salve em **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Você pode ver seus downloads no ícone **Downloads** na barra do navegador.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Agora, desconecte o Tails OS da internet. Vamos criar nossa carteira agora. Parece muito paranoico, mas vamos ser cautelosos, ok?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Vá para **Applications** e procure por **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Agora, vamos importar as chaves e verificar se tudo está bem com o arquivo **bip39-standalone.html** que baixamos. Você pode completar cada comando pressionando **Tab**.

Digite:

- cd Persistent/
- Pressione Enter
- cd Tor\ Browser/
- Pressione Enter
- ls (este comando é para listar os arquivos no diretório, veja se todos os 3 arquivos que baixamos estão nele)
- Pressione Enter
- gpg --import pubkey.asc
- Pressione Enter
- gpg --verify signature.txt.asc
- Pressione Enter

33. Verifique se diz **Good signature** de Ian. Se disser que está bom, significa que todos os arquivos que baixamos são legítimos.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Agora vamos ver se o hash de **bip39-standalone.html** corresponde ao hash no GitHub de Ian.

Digite:

- sha256sum bip39-standalone.html
- Pressione Enter

35. Verifique se ambos os hashes no Terminal e no GitHub de Ian correspondem. Se corresponderem, então o arquivo **bip39-standalone.html** também é legítimo.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Vá para **Places** e selecione **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Abra o arquivo **bip39-standalone.html**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Aqui está o nosso gerador offline de carteira Bitcoin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Vamos gerar uma carteira de 24 palavras (escolha entre 12 ou 24 para torná-la compatível com qualquer outra carteira).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Clique no botão **GENERATE** e anote suas palavras. Preste MUITA atenção e guarde essas palavras com segurança. Se você as perder ou se alguém as roubar, é game over.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Agora, vá para **Applications** e procure por **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Vamos chamar nossa carteira de **Offline** para lembrar que você só deve acessá-la sem conexão com a internet. Clique em **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Selecione **Standard wallet**. Clique em **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Selecione **I already have a seed**. Clique em **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Digite suas palavras na caixa de texto e clique em **Options**, uma pequena janela aparecerá e você deve selecionar **BIP39 seed** e clicar em **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Verifique se o **BIP39 (checksum: ok)** está selecionado. Clique em **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Selecione **native segwit (p2wpkh)**. Clique em **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Escolha uma senha forte para criptografar sua carteira offline. Clique em **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Sua carteira foi criada. Agora vamos para **View** e **Show Addresses** e **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Veja seus endereços.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Volte para a página **bip39-standalone**, role para baixo até **Derivation Path** e clique na aba **BIP84**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Veja se o primeiro endereço na página da web corresponde ao primeiro endereço mostrado na **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Se ambos os primeiros endereços corresponderem (e o segundo, o terceiro e assim por diante), significa que sua carteira foi importada corretamente para a **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

54. Agora vá para a **Electrum Bitcoin Wallet** e vá para **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Copie sua **Master Public Key** (não compartilhe esta chave com ninguém. Se alguém tiver acesso à sua Master Public Key, poderá ver seus endereços e quanto Bitcoin você possui).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Agora vamos criar outra carteira. Desta vez, será nossa carteira **Online** (ou somente visualização).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Selecione **Standard wallet**. Clique em **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Selecione **Use a master key**. Clique em **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Cole sua **Master Public Key** que você copiou da sua carteira **Offline**. Clique em **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Você não precisa adicionar uma senha em sua carteira watching-only, porque carteiras watching-only não podem enviar moedas, mas fica a seu critério. Clique em **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Sua carteira watching-only é criada, e você será apresentado com um aviso dizendo **This wallet is watching-only. This means you will not be able to spend Bitcoins with it. Make sure you own the seed phrase or private keys, before you request Bitcoins to be sent to this wallet.**

Uma carteira watching-only é apenas para mostrar endereços e saldo de Bitcoin, você pode enviar Bitcoins dela, mas somente se você assinar a transação com sua carteira **Offline** primeiro.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Agora, o último passo, veja se os endereços da carteira **Online** correspondem à carteira **Offline**. Se sim, então você está pronto. Boa sorte.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
