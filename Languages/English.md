# It is very important to keep your Tails OS version updated to avoid any kind of malicious attack that could steal your Bitcoins! If you are using an outdated version of Tails OS, remember to NEVER connect to the internet when accessing your offline wallet! Use a second USB drive to create your online wallet, or use other means to have an online wallet on Android or iOS, and use methods to sign your transactions by QR Code. I am not responsible for any theft of your Bitcoins if you break any security rules, including ignoring this warning.

**English Tutorial: Creating a Bitcoin Cold Wallet Using Tails OS and Persistent Storage**

In this tutorial, I will be using Windows 10. You will also need a USB stick with at least 8GB of space.

1. Go to https://tails.net/install/download/index.en.html and download the USB Image.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. After downloading the USB image, verify the download by going to the download page and uploading your downloaded image by clicking the button that says **Select your download to verify...** If the verification is successful, you may proceed; otherwise, you must redownload the image. Then, download **balenaEtcher** from this link: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Plug in your USB stick and start **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Select the USB image by clicking the **Flash from file** button. Your USB stick should be automatically detected. If not, ensure you are selecting the correct USB stick. Then, click the **Flash!** button.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Wait for the flashing process to complete.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Once finished, close **balenaEtcher** and boot from the USB stick.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. In Tails, click the **Start** button to initiate Tails OS.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Go to **Applications** and look for **Persistent Storage** (it should be in the **Favorites** tab).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Click the **Continue** button.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Create a strong password to encrypt your Tails OS installation. Click the **Create Persistent Storage** button.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Wait for the **Persistent Storage** creation to complete.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. In the next window upon completion, you should have the **Persistent Folder** turned on by default. If not, turn it on.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Turn on persistence for both the **Electrum Bitcoin Wallet** and **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Restart Tails OS and enter your password. Then, click the **Unlock Encryption** button to unlock your **Tails Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Once the **Persistent Storage** is unlocked, click the **Start Tails** button.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Now, let's connect to the Tor Network. Make sure your computer is connected to an Ethernet cable or Wi-Fi, and search for **Tor Connection** in **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Select **Connect to Tor automatically**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Wait for it to connect to the Tor Network.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Once connected, click the **Start Tor Browser** button.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Or search for **Tor Browser** in the **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. With **Tor Browser** open, go to this link: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Scroll down the page until you see **GPG My Public Key**. Right-click the link and select **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Save the file in **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Now, go to Ian Coleman's GitHub page at this link: https://github.com/iancoleman/bip39 and go to Releases. You can access releases from this link: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Download both **bip39-standalone.html** and **signature.txt.asc**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. To download **bip39-standalone.html**, just click it and save it in **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. To save **signature.txt.asc**, do the same as for the **GPG Public Key** and right-click it and select **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Save it in **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. You can see your downloads in the **Downloads** icon in the browser bar.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Now, disconnect Tails OS from the internet. We are going to create our wallet now. It sounds too paranoid, but let's be safe, okay?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Go to **Applications** and search for **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Now, we will import keys and verify if everything is good with the **bip39-standalone.html** file we downloaded. You can autocomplete each command by pressing **Tab**.

Type:

- cd Persistent/
- Press Enter
- cd Tor\ Browser/
- Press Enter
- ls (this command is to list the files in the directory, see if all 3 files we downloaded are in it)
- Press Enter
- gpg --import pubkey.asc
- Press Enter
- gpg --verify signature.txt.asc
- Press Enter

33. Check if it says **Good signature** from Ian. If it says it's good, then it means that all files we downloaded are legit.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Now we will see if the hash of **bip39-standalone.html** matches the hash on Ian's GitHub.

Type:

- sha256sum bip39-standalone.html
- Press Enter

35. Check both the hash in the Terminal and the hash on Ian's GitHub. If they match, then the **bip39-standalone.html** file is also legit.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Go to **Places** and select **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Open the **bip39-standalone.html** file.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Here is our Bitcoin wallet offline generator.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Let's generate a 24-word wallet (choose either 12 or 24 to make it compatible with any other wallet).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Click the **GENERATE** button and write down your words. Pay A LOT of attention and store these words safely. If you lose them or if someone steals them, it's game over.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Now, go to **Applications** and search for **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Let's name our wallet **Offline** to remind you that you should only access it without an internet connection. Hit **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Select **Standard wallet**. Hit **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Select **I already have a seed**. Hit **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Type in your words in the text box, and click **Options**, a small window will appear, and you should select **BIP39 seed** and click **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. See if the the **BIP39 (checksum: ok)**. Hit **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Select **native segwit (p2wpkh)**. Hit **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Choose a strong password to encrypt your **Offline** wallet. Hit **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Your wallet is created. Now let's go to **View** and **Show Addresses** and **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. See your addresses.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Go back to **bip39-standalone** page, and scroll down to **Derivation Path** and click the **BIP84** tab.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. See if the first address in the webpage matches the first address shown in the **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. If both first addresses matches (and the second, and the third and so on) it means your wallet was correctly imported to **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**This is the part where we create our Online Wallet, and you have two options:**

- **1- You can create the Online Wallet within the same installation of Tails OS that contains your Offline Wallet. In this case, you should NOT CONNECT TO THE INTERNET when accessing the Offline Wallet to prevent any attack vectors on your Bitcoins.**

- **2- You can use another USB stick, follow the same process as above, and then follow the next steps to create your Online Wallet on the new USB stick. This helps prevent human error of accessing your Offline Wallet while connected to the internet.**

54. Now go to **Electrum Bitcoin Wallet** and go to **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Copy your **Master Public Key** (do not share this key with anyone. If someone get access to your Master Public Key, they will be able to see your addresses and how much Bitcoin your own).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Let's now create another wallet. This time, it will be our **Online** wallet (or watching-only).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Select **Standard wallet**. Hit **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Select **Use a master key**. Hit **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Paste your **Master Public Key** that you copied from your **Offline** wallet. Hit **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. You don't have to add a password in your watching-only wallet, because watching-only wallets cannot send Coins, but it up to you. Hit **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Your watching-only wallet is created, and you will be presented with a warning saying **This wallet is watching-only. This means you will not be able to spend Bitcoins with it. Make sure you own the seed phrase or private keys, before you request Bitcoins to be sent to this wallet.**

A watching-only wallet is just for showing addresses and Bitcoin balance, you can send Bitcoins from it but only if you sign the transaction with your **Offline** wallet first.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Now, the last step, see if the addresses of the **Online** wallet matches the **Offline** wallet. If so, then you are all set. Good luck.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
