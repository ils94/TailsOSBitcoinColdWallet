**이 튜토리얼은 ChatGPT를 사용하여 영어에서 한국어로 번역되었습니다. 번역 오류가 있을 수 있지만, 한국어를 사용하는 커뮤니티에게 여전히 의미가 있다고 생각합니다!**

**한국어 튜토리얼: Tails OS와 지속적인 저장 공간을 사용하여 비트코인 콜드 월렛 만들기**

이 튜토리얼에서는 Windows 10을 사용할 것입니다. 또한 적어도 8GB의 용량을 갖춘 USB 스틱이 필요합니다.

1. https://tails.net/install/download/index.en.html 에서 USB 이미지를 다운로드합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. USB 이미지를 다운로드한 후, 다운로드 페이지로 이동하여 다운로드한 이미지를 업로드하고 **Select your download to verify...** 버튼을 클릭하여 다운로드를 확인하세요. 확인이 성공하면 계속 진행할 수 있지만, 그렇지 않으면 이미지를 다시 다운로드해야 합니다. 그런 다음, 이 링크에서 **balenaEtcher** 를 다운로드하세요: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. USB 스틱을 연결하고 **balenaEtcher** 를 시작합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. **Flash from file** 버튼을 클릭하여 USB 이미지를 선택합니다. USB 스틱이 자동으로 감지되어야 합니다. 그렇지 않은 경우 올바른 USB 스틱을 선택했는지 확인하고 **Flash!** 버튼을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. 플래싱 프로세스가 완료될 때까지 기다립니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. 완료되면 **balenaEtcher** 를 닫고 USB 스틱에서 부팅합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. Tails에서 **Start** 버튼을 클릭하여 Tails OS를 시작합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. **Applications**에 가서 **Persistent Storage**를 찾으세요 (이것은 **Favorites** 탭에 있어야 합니다).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. **Continue** 버튼을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Tails OS 설치를 암호화하기 위해 강력한 암호를 생성합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. **Persistent Storage** 생성이 완료될 때까지 기다립니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. 완료되면 **Persistent Folder** 가 기본적으로 켜져 있는지 확인합니다. 그렇지 않은 경우 켭니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. **Electrum Bitcoin Wallet** 및 **GnuPG**에 대한 지속성을 켭니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Tails OS를 재부팅하고 암호를 입력합니다. 그런 다음 Tails 지속적인 저장소를 잠금 해제하려면 **Unlock Encryption** 버튼을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. 지속적인 저장소가 잠금 해제되면 **Start Tails** 버튼을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. 이제 Tor 네트워크에 연결해 봅시다. 컴퓨터가 이더넷 케이블이나 Wi-Fi에 연결되어 있는지 확인하고 **Applications**에서 **Tor Connection**을 검색합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. **Connect to Tor automatically** 을 선택합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Tor 네트워크에 연결되기까지 기다립니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. 연결되면 **Start Tor Browser** 버튼을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. 또는 **Applications** 에서 **Tor Browser** 를 검색합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. **Tor Browser** 가 열린 상태에서 이 링크로 이동합니다: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. **GPG My Public Key**를 찾아 마우스 오른쪽 버튼을 클릭하고 **Save Link As...** 을 선택합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. 파일을 **/home/amnesia/Persistent/Tor Browser** 에 저장합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. 이제 Ian Coleman의 GitHub 페이지인 https://github.com/iancoleman/bip39로 이동하고 릴리스로 이동합니다. 릴리스에는 https://github.com/iancoleman/bip39/releases 링크에서 액세스할 수 있습니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. **bip39-standalone.html** 과 **signature.txt.asc** 를 모두 다운로드합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. **bip39-standalone.html** 을 다운로드하려면 클릭하고 **/home/amnesia/Persistent/Tor Browser** 에 저장합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. **signature.txt.asc** 를 저장하려면 GPG 공개 키와 마찬가지로 마우스 오른쪽 버튼을 클릭하고 **Save Link As...** 을 선택합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. **/home/amnesia/Persistent/Tor Browser** 에 저장합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. 브라우저 막대의 **Downloads** 아이콘에서 다운로드를 확인할 수 있습니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. 이제 Tails OS를 인터넷에서 연결 해제합니다. 이제 월렛을 만들어 보겠습니다. 너무 피곤한 소리일 수 있지만, 안전하게 하죠?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. **Applications**으로 이동하고 **Terminal**을 검색합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. 이제 키를 가져 오고 다운로드한 **bip39-standalone.html** 파일이 올바른지 확인합니다. 각 명령을 **Tab** 을 눌러 자동 완성할 수 있습니다.

- cd Persistent/
- Enter 키 누름
- cd Tor\ Browser/
- Enter 키 누름
- ls (이 명령은 디렉터리의 파일을 나열하며, 다운로드한 3개 파일이 모두 있는지 확인합니다)
- Enter 키 누름
- gpg --import pubkey.asc
- Enter 키 누름
- gpg --verify signature.txt.asc
- Enter 키 누름

33. Ian의 **Good signature** 가 나오는지 확인합니다. 모두 좋다고 나오면 다운로드한 모든 파일이 정품이라는 뜻입니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. 이제 **bip39-standalone.html** 의 해시가 Ian의 GitHub에서 제공하는 해시와 일치하는지 확인합니다.

- sha256sum bip39-standalone.html
- Enter 키 누름

35. 터미널과 Ian의 GitHub에서의 해시를 모두 확인합니다. 일치하면 **bip39-standalone.html** 파일도 정품입니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. **Places** 로 이동하여 **Tor Browser (persistent)** 를 선택합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. **bip39-standalone.html** 파일을 엽니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. 여기에 비트코인 지갑 오프라인 생성기가 있습니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. 24 단어 지갑을 생성해 봅시다 (호환성을 위해 12 또는 24 중 하나를 선택하십시오).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. **GENERATE** 버튼을 클릭하고 단어를 작성합니다. 이 단어를 주의 깊게 기록하고 안전하게 보관하십시오. 단어를 분실하거나 누군가가 훔쳐 가면 게임이 끝납니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. 이제 **Applications**로 이동하고 **Electrum Bitcoin Wallet** 을 검색합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. 월렛 이름을 **Offline** 으로 지정하여 인터넷 연결 없이만 액세스해야 함을 상기시킵니다. **Next** 을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. **Standard wallet** 을 선택합니다. **Next** 을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. **I already have a seed** 를 선택합니다. **Next** 을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. 텍스트 상자에 단어를 입력하고 **Options** 을 클릭하면 작은 창이 나타나며 **BIP39 seed** 를 선택하고 **Ok** 을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. **BIP39 (checksum: ok)** 을 확인합니다. **Next** 을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. **native segwit (p2wpkh)** 를 선택합니다. **Next** 을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. 오프라인 월렛을 암호화하기 위해 강력한 암호를 선택합니다. **Next** 을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. 월렛이 생성되었습니다. 이제 **View** 로 이동하고 **Show Addresses** 및 **Show Coins** 를 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. 주소를 확인합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. **bip39-standalone** 페이지로 돌아가 **Derivation Path** 로 스크롤하고 **BIP84** 탭을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. 웹 페이지의 첫 번째 주소가 **Electrum Bitcoin Wallet** 에 표시된 첫 번째 주소와 일치하는지 확인합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. 첫 번째 주소부터 일치하는지 확인합니다 (두 번째, 세 번째 등도 동일). 이렇게 하면 월렛이 올바르게 **Electrum Bitcoin Wallet** 으로 가져온 것입니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

54. 이제 **Electrum Bitcoin Wallet** 로 이동하여 **Information** 로 이동합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. **Master Public Key** 를 복사합니다 (이 키를 다른 사람과 공유하지 마십시오. 누군가가 마스터 공개 키에 액세스하면 여러분의 주소와 소유한 비트코인 금액을 볼 수 있습니다).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. 이제 다른 월렛을 생성해 봅시다. 이번에는 **Online** 월렛 (또는 관전 전용)이 될 것입니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. **Standard wallet** 을 선택합니다. **Next** 을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. **Use a master key** 을 선택합니다. **Next** 을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. **Offline** 월렛에서 복사한 **Master Public Key** 를 붙여 넣습니다. **Next** 을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. 관전 전용 월렛에는 비밀번호를 추가할 필요가 없습니다. 관전 전용 월렛은 코인을 보낼 수 없습니다. 그러나 필요에 따라 추가할 수 있습니다. **Next** 을 클릭합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. 관전 전용 월렛이 생성되었으며 **이 월렛은 관전 전용입니다. 즉, 이 월렛으로 비트코인을 보낼 수 없습니다. 이 월렛으로 비트코인을 보내려면 시드 문구 또는 개인 키를 소유해야 합니다.**라는 경고가 표시됩니다.

관전 전용 월렛은 주소와 비트코인 잔액을 표시하기 위한 것이며, 비트코인을 보낼 수 있지만 **Offline** 월렛으로 트랜잭션을 서명해야 합니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. 이제 **Online** 월렛의 주소가 **Offline** 월렛의 주소와 일치하는지 확인합니다. 일치하는 경우 모두 설정이 완료된 것입니다. 행운을 빕니다.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
