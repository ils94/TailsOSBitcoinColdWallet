**このチュートリアルは、ChatGPTを使用して英語から日本語に翻訳されました。翻訳のエラーがあるかもしれませんが、日本語を話すコミュニティにとっても意味が通じることを願っています！**

**日本語チュートリアル：Tails OSと永続ストレージを使用したビットコインのコールドウォレットの作成**

このチュートリアルでは、Windows 10 を使用します。また、少なくとも8GBの空き容量のあるUSBメモリが必要です。

1. https://tails.net/install/download/index.en.html にアクセスし、USB イメージをダウンロードします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. USBイメージをダウンロードしたら、ダウンロードページにアクセスし、**Select your download to verify...** ボタンをクリックしてダウンロードしたイメージをアップロードして、ダウンロードを確認します。確認が成功した場合は続行できます。そうでない場合は、イメージを再ダウンロードする必要があります。その後、このリンクからbalenaEtcherをダウンロードします: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. USBメモリを差し込み、balenaEtcherを起動します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. **Flash from file** ボタンをクリックしてUSBイメージを選択します。USBメモリは自動的に検出されるはずです。検出されない場合は、正しいUSBメモリを選択していることを確認してください。次に、**Flash!** ボタンをクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. フラッシュ処理が完了するのを待ちます。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. 完了したら、balenaEtcherを閉じて、USBメモリから起動します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. Tailsで、**Start** ボタンをクリックしてTails OSを起動します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. **Applications** に移動し、**Persistent Storage** を探します（Favoritesタブにあるはずです）。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. **Continue** ボタンをクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Tails OSのインストールを暗号化するための強力なパスワードを作成します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. **Persistent Storage** の作成が完了するのを待ちます。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. 完了後の次のウィンドウで、**Persistent Folder** がデフォルトでオンになっているはずです。オンになっていない場合は、オンにしてください。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. **Electrum Bitcoin Wallet** と **GnuPG** の永続化をオンにします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Tails OSを再起動し、パスワードを入力します。その後、**Unlock Encryption** ボタンをクリックしてTails Persistent Storageを解除します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Persistent Storageが解除されたら、**Start Tails** ボタンをクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. 次に、Torネットワークに接続します。コンピュータがイーサネットケーブルまたはWi-Fiに接続されていることを確認し、**Applications** で **Tor Connection** を検索します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. **Connect to Tor automatically** を選択します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Torネットワークに接続されるのを待ちます。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. 接続されたら、**Start Tor Browser** ボタンをクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. または、**Applications** で **Tor Browser** を検索します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. **Tor Browser** を開いた状態で、このリンクにアクセスします: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. ページを下にスクロールして、**GPG My Public Key** を見つけます。リンクを右クリックし、**Save Link As...** を選択します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. ファイルを **/home/amnesia/Persistent/Tor Browser** に保存します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. 次に、Ian ColemanのGitHubページにこのリンクからアクセスします: https://github.com/iancoleman/bip39 。Releasesにアクセスします。このリンクからReleasesにアクセスできます: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. **bip39-standalone.html** と **signature.txt.asc** の両方をダウンロードします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. **bip39-standalone.html** をダウンロードするには、クリックして **/home/amnesia/Persistent/Tor Browser** に保存します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. **signature.txt.asc** を保存するには、GPG Public Keyと同様に、右クリックして **Save Link As...** を選択します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. **/home/amnesia/Persistent/Tor Browser** に保存します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. ブラウザバーの **Downloads** アイコンでダウンロードを確認できます。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. 次に、Tails OSをインターネットから切断します。これからウォレットを作成します。少しパラノイアに感じるかもしれませんが、安全のために行いましょう。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. **Applications** に移動し、**Terminal** を検索します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. 次に、ダウンロードした **bip39-standalone.html** ファイルのキーをインポートして、すべてが正常かどうかを確認します。各コマンドを入力する際、**Tab** キーを押して自動補完することができます。

以下を入力します：

- cd Persistent/
- Enterキーを押します
- cd Tor\ Browser/
- Enterキーを押します
- ls （このコマンドはディレクトリ内のファイルを一覧表示し、ダウンロードしたすべてのファイルがあるかどうかを確認します）
- Enterキーを押します
- gpg --import pubkey.asc
- Enterキーを押します
- gpg --verify signature.txt.asc
- Enterキーを押します

33. Ianからの **Good signature** と表示されているか確認します。表示されている場合、ダウンロードしたすべてのファイルが正当であることを意味します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. 次に、**bip39-standalone.html** のハッシュがIanのGitHubにあるハッシュと一致するかどうかを確認します。

以下を入力します：

- sha256sum bip39-standalone.html
- Enterキーを押します

35. ターミナル内のハッシュとIanのGitHubのハッシュを確認します。一致する場合、**bip39-standalone.html** ファイルも正当です。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. **Places** に移動し、**Tor Browser (persistent)** を選択します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. **bip39-standalone.html** ファイルを開きます。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. ここで、オフラインのBitcoinウォレットジェネレーターを使用します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. 24ワードのウォレットを生成しましょう（他のウォレットと互換性を持たせるために12または24を選択してください）。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. **GENERATE** ボタンをクリックしてワードをメモします。非常に注意深くこれらのワードを保存してください。これらを紛失したり、誰かに盗まれたりすると、ゲームオーバーです。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. 次に、**Applications** に移動し、**Electrum Bitcoin Wallet** を検索します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. ウォレットの名前を **Offline** にして、インターネット接続なしでのみアクセスすることを思い出せるようにします。**Next** をクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. **Standard wallet** を選択します。**Next** をクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. **I already have a seed** を選択します。**Next** をクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. テキストボックスにワードを入力し、**Options** をクリックします。小さなウィンドウが表示され、**BIP39 seed** を選択し、**OK** をクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. **BIP39 (checksum: ok)** と表示されているか確認します。**Next** をクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. **native segwit (p2wpkh)** を選択します。**Next** をクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. オフラインウォレットを暗号化するための強力なパスワードを選択します。**Next** をクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. ウォレットが作成されました。次に、**View** に移動し、**Show Addresses** と **Show Coins** を表示します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. アドレスを確認します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. **bip39-standalone** ページに戻り、**Derivation Path** までスクロールし、**BIP84** タブをクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. ウェブページの最初のアドレスが **Electrum Bitcoin Wallet** に表示される最初のアドレスと一致するか確認します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. 最初のアドレスが一致している場合（および2番目、3番目などが一致している場合）、ウォレットが正しく **Electrum Bitcoin Wallet** にインポートされたことを意味します。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

54. 次に、**Electrum Bitcoin Wallet** に移動し、**Information** にアクセスします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. **Master Public Key** をコピーします（このキーを誰にも共有しないでください。誰かがMaster Public Keyにアクセスすると、アドレスと所有しているBitcoinの量を確認できます）。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. もう1つウォレットを作成しましょう。今回は **Online** ウォレット（または監視専用）にします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. **Standard wallet** を選択します。**Next** をクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. **Use a master key** を選択します。**Next** をクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. コピーした **Master Public Key** を貼り付けます。**Next** をクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. 監視専用ウォレットにはパスワードを追加する必要はありませんが、必要に応じて追加してください。**Next** をクリックします。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. 監視専用ウォレットが作成され、**This wallet is watching-only. This means you will not be able to spend Bitcoins with it. Make sure you own the seed phrase or private keys, before you request Bitcoins to be sent to this wallet.** という警告が表示されます。

監視専用ウォレットはアドレスとBitcoin残高を表示するためだけのものであり、送金することはできませんが、オフラインウォレットでトランザクションに署名してからのみ送金することができます。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. 最後に、**Online** ウォレットのアドレスが **Offline** ウォレットと一致しているかどうかを確認します。一致している場合は、準備完了です。幸運を祈ります。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
