**这篇教程是使用ChatGPT从英语翻译成中文的。可能会有一些翻译错误，但我希望它对讲中文的社区来说仍然有意义！**

**中文教程：使用Tails OS和持久存储创建比特币冷钱包**

在本教程中，我将使用Windows 10。你还需要一个至少8GB空间的USB棒。

1. 访问 https://tails.net/install/download/index.en.html 并下载USB映像。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. 下载USB映像后，通过访问下载页面并点击 **Select your download to verify...** 按钮上传已下载的映像来验证下载。如果验证成功，你可以继续；否则，你必须重新下载映像。然后，从此链接下载 **balenaEtcher**：https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. 插入你的USB棒并启动 **balenaEtcher**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. 通过点击 **Flash from file** 按钮选择USB映像。你的USB棒应该会自动检测到。如果没有，确保你选择了正确的USB棒。然后，点击 **Flash!** 按钮。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. 等待闪存过程完成。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. 完成后，关闭 **balenaEtcher** 并从USB棒启动。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. 在Tails中，点击 **Start** 按钮启动Tails OS。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. 进入 **Applications** 并寻找 **Persistent Storage**（它应该在 **Favorites** 标签中）。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. 点击 **Continue** 按钮。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. 创建一个强密码来加密您的 Tails OS 安装。点击 **Create Persistent Storage** 按钮。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. 等待 **Persistent Storage** 创建完成。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. 在完成后的下一个窗口中，默认情况下，你应该已经开启了 **Persistent Folder**。如果没有，请打开它。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. 为 **Electrum Bitcoin Wallet** 和 **GnuPG** 开启持久性。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. 重启Tails OS并输入你的密码。然后，点击 **Unlock Encryption** 按钮解锁你的Tails持久存储。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. 一旦持久存储解锁，点击 **Start Tails** 按钮。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. 现在，让我们连接到Tor网络。确保你的计算机连接到以太网电缆或Wi-Fi，并在 **Applications** 中搜索 **Tor Connection**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. 选择 **Connect to Tor automatically**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. 等待连接到Tor网络。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. 一旦连接，点击 **Start Tor Browser** 按钮。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. 或者在 **Applications** 中搜索 **Tor Browser**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. 打开 **Tor Browser**，访问这个链接：https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. 向下滚动页面直到看到 **GPG My Public Key**。右键点击链接并选择 **Save Link As...**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. 将文件保存到 **/home/amnesia/Persistent/Tor Browser**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. 现在，访问Ian Coleman's GitHub页面，通过这个链接：https://github.com/iancoleman/bip39 并进入Releases。你可以通过这个链接访问Releases：https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. 下载 **bip39-standalone.html** 和 **signature.txt.asc**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. 要下载 **bip39-standalone.html**，只需点击并保存到 **/home/amnesia/Persistent/Tor Browser**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. 要保存 **signature.txt.asc**，和GPG公共密钥一样操作：右键点击并选择 **Save Link As...**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. 将其保存到 **/home/amnesia/Persistent/Tor Browser**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. 你可以在浏览器栏中的 **Downloads** 图标中看到你的下载。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. 现在，断开Tails OS的互联网连接。我们现在要创建钱包。听起来很偏执，但还是安全点吧，好吗？

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. 进入 **Applications** 并搜索 **Terminal**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. 现在，我们将导入密钥并验证我们下载的 **bip39-standalone.html** 文件是否正常。你可以通过按 **Tab** 自动完成每个命令。

输入：

- cd Persistent/
- 按Enter
- cd Tor\ Browser/
- 按Enter
- ls（这个命令是列出目录中的文件，查看我们下载的所有3个文件是否在其中）
- 按Enter
- gpg --import pubkey.asc
- 按Enter
- gpg --verify signature.txt.asc
- 按Enter

33. 检查是否显示 **Good signature** 来自Ian。如果显示为好，那么这意味着我们下载的所有文件都是合法的。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. 现在我们将查看 **bip39-standalone.html** 的哈希值是否与Ian的GitHub上的哈希值匹配。

输入：

- sha256sum bip39-standalone.html
- 按Enter

35. 检查终端中的哈希值和Ian的GitHub上的哈希值是否匹配。如果匹配，那么 **bip39-standalone.html** 文件也是合法的。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. 进入 **Places** 并选择 **Tor Browser (persistent)**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. 打开 **bip39-standalone.html** 文件。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. 这里是我们的比特币钱包离线生成器。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. 让我们生成一个24词钱包（选择12或24中的一个，以使其与其他任何钱包兼容）。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. 点击 **GENERATE** 按钮并写下你的单词。非常注意并安全地存储这些单词。如果你丢失它们或有人偷了它们，就完蛋了。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. 现在，进入 **Applications** 并搜索 **Electrum Bitcoin Wallet**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. 让我们将钱包命名为 **Offline** 以提醒你只能在没有互联网连接时访问它。点击 **Next**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. 选择 **Standard wallet**。点击 **Next**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. 选择 **I already have a seed**。点击 **Next**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. 在文本框中输入你的单词，然后点击 **Options**，会出现一个小窗口，你应该选择 **BIP39 seed** 并点击 **OK**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. 查看是否显示 **BIP39 (checksum: ok)**。点击 **Next**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. 选择 **native segwit (p2wpkh)**。点击 **Next**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. 选择一个强密码来加密你的离线钱包。点击 **Next**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. 你的钱包已创建。现在，进入 **View** 并选择 **Show Addresses** 和 **Show Coins**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. 查看你的地址。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. 回到 **bip39-standalone** 页面，向下滚动到 **Derivation Path** 并点击 **BIP84** 标签。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. 查看网页上的第一个地址是否与 **Electrum Bitcoin Wallet** 中显示的第一个地址匹配。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. 如果第一个地址匹配（以及第二个、第三个等），则表示你的钱包已正确导入到 **Electrum Bitcoin Wallet** 中。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

54. 现在，进入 **Electrum Bitcoin Wallet** 并选择 **Information**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. 复制你的 **Master Public Key**（不要与任何人分享这个密钥。如果有人获取你的主公钥，他们将能够看到你的地址和拥有多少比特币）。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. 现在我们要创建另一个钱包。这次，它将是我们的 **Online** 钱包（或仅监视钱包）。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. 选择 **Standard wallet**。点击 **Next**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. 选择 **Use a master key**。点击 **Next**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. 粘贴你从 **Offline** 钱包复制的 **Master Public Key**。点击 **Next**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. 你不必在仅监视钱包中添加密码，因为仅监视钱包不能发送硬币，但这取决于你。点击 **Next**。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. 你的仅监视钱包已创建，并会提示 **This wallet is watching-only. This means you will not be able to spend Bitcoins with it. Make sure you own the seed phrase or private keys, before you request Bitcoins to be sent to this wallet.**

仅监视钱包只是用于显示地址和比特币余额，你可以从中发送比特币，但前提是你首先用你的 **Offline** 钱包签署交易。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. 现在，最后一步，查看 **Online** 钱包的地址是否与 **Offline** 钱包匹配。如果匹配，那么你就准备好了。祝你好运。

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
