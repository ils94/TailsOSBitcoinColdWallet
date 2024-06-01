# अपने Tails OS संस्करण को अपडेट रखना बहुत महत्वपूर्ण है ताकि आपकी Bitcoins चुरा लेने वाली किसी भी प्रकार की दुराचारी हमले से बचा जा सके! यदि आप Tails OS का पुराना संस्करण उपयोग कर रहे हैं, तो ध्यान दें कि जब आप अपने ऑफलाइन वॉलेट तक पहुंचते हैं, कभी भी इंटरनेट से कनेक्ट न करें! अपना ऑनलाइन वॉलेट बनाने के लिए दूसरे USB ड्राइव का उपयोग करें, या अन्य माध्यमों का उपयोग करें जिससे Android या iOS पर ऑनलाइन वॉलेट हो और QR कोड द्वारा अपने लेनदेनों के लिए हस्ताक्षर करने के तरीकों का उपयोग करें। यदि आप कोई सुरक्षा नियमों का उल्लंघन करते हैं, इस चेतावनी को नज़रअंदाज़ करने के समेत, तो आपकी Bitcoins की कोई चोरी के लिए मैं जिम्मेदार नहीं हूँ।

**यह ट्यूटोरियल इंग्लिश से हिंदी में ChatGPT का उपयोग करके अनुवादित किया गया था। अनुवाद में कुछ गलतियाँ हो सकती हैं, लेकिन मुझे उम्मीद है कि यह हिंदी बोलने वाले समुदाय के लिए अब भी समझ में आएगा!**

**हिंदी ट्यूटोरियल: Tails ओएस और Persistent Storage का उपयोग करके एक बिटकॉइन कोल्ड वॉलेट बनाना**

इस ट्यूटोरियल में, मैं Windows 10 का उपयोग कर रहा हूँ। आपको कम से कम 8GB की जगह वाली एक USB स्टिक की भी आवश्यकता होगी।

1. https://tails.net/install/download/index.pt.html पर जाएं और USB इमेज डाउनलोड करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. USB इमेज डाउनलोड करने के बाद, डाउनलोड पेज पर जाकर और अपने डाउनलोड किए गए इमेज को अपलोड करके अपने डाउनलोड को सत्यापित करें। **Select your download to verify...** बटन पर क्लिक करें। यदि सत्यापन सफल है, तो आप आगे बढ़ सकते हैं; अन्यथा, आपको इमेज को पुनः डाउनलोड करना होगा। फिर, इस लिंक से **balenaEtcher** डाउनलोड करें: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. अपनी USB स्टिक को प्लग इन करें और **balenaEtcher** शुरू करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. USB इमेज को चुनने के लिए **Flash from file** बटन पर क्लिक करें। आपकी USB स्टिक स्वचालित रूप से डिटेक्ट होनी चाहिए। यदि नहीं, तो सुनिश्चित करें कि आप सही USB स्टिक का चयन कर रहे हैं। फिर, **Flash!** बटन पर क्लिक करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. फ्लैशिंग प्रक्रिया पूरी होने तक प्रतीक्षा करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. एक बार पूरा होने के बाद, **balenaEtcher** को बंद करें और USB स्टिक से बूट करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. Tails में, **Start** बटन पर क्लिक करें ताकि Tails OS शुरू हो सके।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. **Applications** पर जाएं और **Persistent Storage** को खोजें (यह **Favorites** टैब में होना चाहिए)।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. **Continue** बटन पर क्लिक करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. अपने Tails OS स्थापना को एन्क्रिप्ट करने के लिए एक मजबूत पासवर्ड बनाएं। **Create Persistent Storage** बटन पर क्लिक करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. **Persistent Storage** निर्माण के पूरा होने की प्रतीक्षा करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. अगली विंडो में, आपको **Persistent Folder** डिफ़ॉल्ट रूप से चालू होना चाहिए। यदि नहीं, तो इसे चालू करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. **Electrum Bitcoin Wallet** और **GnuPG** दोनों के लिए स्थायित्व चालू करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Tails OS को पुनः शुरू करें और अपना पासवर्ड दर्ज करें। फिर, **Unlock Encryption** बटन पर क्लिक करें ताकि आप अपनी **Tails Persistent Storage** को अनलॉक कर सकें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. **Persistent Storage** अनलॉक होने के बाद, **Start Tails** बटन पर क्लिक करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. अब, Tor नेटवर्क से कनेक्ट करें। सुनिश्चित करें कि आपका कंप्यूटर एक ईथरनेट केबल या वाई-फाई से कनेक्टेड है, और **Applications** में **Tor Connection** खोजें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. **Connect to Tor automatically** को चुनें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Tor नेटवर्क से कनेक्ट होने की प्रतीक्षा करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. एक बार कनेक्ट हो जाने पर, **Start Tor Browser** बटन पर क्लिक करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. या **Applications** में **Tor Browser** खोजें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. **Tor Browser** खोलकर, इस लिंक पर जाएं: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. पेज को नीचे स्क्रॉल करें जब तक कि आप **GPG My Public Key** न देख लें। लिंक पर राइट-क्लिक करें और **Save Link As...** को चुनें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. फ़ाइल को **/home/amnesia/Persistent/Tor Browser** में सहेजें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. अब, इस लिंक पर Ian Coleman's GitHub पेज पर जाएं: https://github.com/iancoleman/bip39 और Releases पर जाएं। आप इस लिंक से भी Releases तक पहुंच सकते हैं: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. **bip39-standalone.html** और **signature.txt.asc** दोनों को डाउनलोड करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. **bip39-standalone.html** डाउनलोड करने के लिए, बस उस पर क्लिक करें और इसे **/home/amnesia/Persistent/Tor Browser** में सहेजें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. **signature.txt.asc** को सेव करने के लिए, उसी प्रकार करें जैसे **GPG Public Key** के लिए किया था और उस पर राइट-क्लिक करें और **Save Link As...** चुनें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. इसे **/home/amnesia/Persistent/Tor Browser** में सहेजें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. आप अपने डाउनलोड्स को ब्राउज़र बार में **Downloads** आइकन में देख सकते हैं।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. अब, Tails OS को इंटरनेट से डिस्कनेक्ट करें। अब हम अपना वॉलेट बनाएंगे। यह बहुत अधिक पैरानोइड लग सकता है, लेकिन सुरक्षित रहना बेहतर है, ठीक है?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. **Applications** में जाएं और **Terminal** खोजें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. अब, हम कुंजियों को इम्पोर्ट करेंगे और देखेंगे कि **bip39-standalone.html** फ़ाइल जो हमने डाउनलोड की है, सब कुछ सही है या नहीं। आप प्रत्येक कमांड को **Tab** दबाकर स्वचालित रूप से पूरा कर सकते हैं।

टाइप करें:

- cd Persistent/
- Enter दबाएं
- cd Tor\ Browser/
- Enter दबाएं
- ls (यह कमांड डायरेक्टरी में फ़ाइलों को सूचीबद्ध करने के लिए है, देखें कि हमने जो 3 फ़ाइलें डाउनलोड की हैं वे सभी इसमें हैं या नहीं)
- Enter दबाएं
- gpg --import pubkey.asc
- Enter दबाएं
- gpg --verify signature.txt.asc
- Enter दबाएं

33. देखें कि यह **Good signature** from Ian कहता है। यदि यह कहता है कि यह अच्छा है, तो इसका मतलब है कि हमने जो सभी फ़ाइलें डाउनलोड की हैं वे वैध हैं।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. अब हम देखेंगे कि **bip39-standalone.html** का हैश Ian के GitHub पर हैश से मेल खाता है या नहीं।

टाइप करें:

- sha256sum bip39-standalone.html
- Enter दबाएं

35. टर्मिनल में हैश और Ian के GitHub पर हैश दोनों की जांच करें। यदि वे मेल खाते हैं, तो **bip39-standalone.html** फ़ाइल भी वैध है।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. **Places** पर जाएं और **Tor Browser (persistent)** चुनें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. **bip39-standalone.html** फ़ाइल खोलें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. यहां हमारा Bitcoin वॉलेट ऑफ़लाइन जेनरेटर है।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. चलो एक 24-शब्द वॉलेट जेनरेट करें (इसे किसी अन्य वॉलेट के साथ संगत बनाने के लिए 12 या 24 में से चुनें)।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. **GENERATE** बटन पर क्लिक करें और अपने शब्दों को लिख लें। बहुत ध्यान दें और इन शब्दों को सुरक्षित रखें। यदि आप उन्हें खो देते हैं या कोई उन्हें चुरा लेता है, तो यह खेल खत्म है।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. अब, **Applications** में जाएं और **Electrum Bitcoin Wallet** खोजें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. चलो हमारे वॉलेट का नाम **Offline** रखें ताकि आपको याद रहे कि आपको इसे केवल इंटरनेट कनेक्शन के बिना एक्सेस करना चाहिए। **Next** दबाएं।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. **Standard wallet** चुनें। **Next** दबाएं।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. **I already have a seed** चुनें। **Next** दबाएं।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. अपने शब्दों को टेक्स्ट बॉक्स में टाइप करें, और **Options** पर क्लिक करें, एक छोटी विंडो दिखाई देगी, और आपको **BIP39 seed** का चयन करना चाहिए और **OK** पर क्लिक करना चाहिए।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. देखें कि **BIP39 (checksum: ok)** कहता है। **Next** दबाएं।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. **native segwit (p2wpkh)** चुनें। **Next** दबाएं।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. अपने **Offline** वॉलेट को एन्क्रिप्ट करने के लिए एक मजबूत पासवर्ड चुनें। **Next** दबाएं।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. आपका वॉलेट बन गया है। अब चलो **View** पर जाएं और **Show Addresses** और **Show Coins** पर क्लिक करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. अपने पतों को देखें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. **bip39-standalone** पेज पर वापस जाएं, और **Derivation Path** पर स्क्रॉल करें और **BIP84** टैब पर क्लिक करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. देखें कि वेबपेज में पहला पता **Electrum Bitcoin Wallet** में दिखाए गए पहले पते से मेल खाता है या नहीं।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. यदि दोनों पहले पते मेल खाते हैं (और दूसरा, और तीसरा और इसी तरह) तो इसका मतलब है कि आपका वॉलेट **Electrum Bitcoin Wallet** में सही ढंग से इम्पोर्ट किया गया था।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**यह वह हिस्सा है जहाँ हम अपना Online Wallet बनाते हैं, और आपके पास दो विकल्प हैं:**

- **1- आप Online Wallet को उसी Tails OS की स्थापना में बना सकते हैं जिसमें आपका Offline Wallet होता है। इस स्थिति में, जब आप Offline Wallet का उपयोग करते हैं तो इंटरनेट से कनेक्ट न करें ताकि आपके Bitcoins पर किसी भी प्रकार के अटैक वेक्टर को रोका जा सके।**

- **2- आप एक अन्य USB स्टिक का उपयोग कर सकते हैं, ऊपर दिए गए समान प्रक्रिया का पालन करें, और फिर नए USB स्टिक पर अपना Online Wallet बनाने के लिए अगले चरणों का पालन करें। यह इंटरनेट से जुड़े होते समय आपके Offline Wallet तक पहुंचने में मानवीय त्रुटि को रोकने में मदद करता है।**

54. अब **Electrum Bitcoin Wallet** पर जाएं और **Information** पर जाएं।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. अपने **Master Public Key** को कॉपी करें (इस कुंजी को किसी के साथ साझा न करें। यदि किसी को आपके Master Public Key का एक्सेस मिल जाता है, तो वे आपके पते और आपके पास कितने Bitcoin हैं, यह देख पाएंगे)।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. चलो अब एक और वॉलेट बनाएं। इस बार, यह हमारा **Online** वॉलेट (या केवल देखने के लिए) होगा।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. **Standard wallet** चुनें। **Next** दबाएं।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. **Use a master key** चुनें। **Next** दबाएं।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. अपने **Master Public Key** को पेस्ट करें जिसे आपने अपने **Offline** वॉलेट से कॉपी किया था। **Next** दबाएं।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. आपको अपने केवल देखने वाले वॉलेट में पासवर्ड जोड़ने की आवश्यकता नहीं है, क्योंकि केवल देखने वाले वॉलेट्स सिक्क

े नहीं भेज सकते।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. आपका केवल देखने वाला वॉलेट बनाया गया है, और आपको एक चेतावनी दिखाई जाएगी जिसमें लिखा होगा **यह वॉलेट केवल देखने वाला है। इसका मतलब है कि आप इससे Bitcoins खर्च नहीं कर पाएंगे। सुनिश्चित करें कि आपके पास seed phrase या निजी कुंजियाँ हैं, इससे पहले कि आप इस वॉलेट पर Bitcoins भेजने का अनुरोध करें।**

एक केवल देखने वाला वॉलेट केवल पते और Bitcoin बैलेंस दिखाने के लिए होता है, आप इससे Bitcoins भेज सकते हैं लेकिन केवल तब, जब आप पहले अपने **ऑफ़लाइन** वॉलेट से ट्रांजेक्शन पर हस्ताक्षर करें।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. अब, आखिरी कदम, देखें कि **Online** वॉलेट के पते **Offline** वॉलेट के पतों से मेल खाते हैं। यदि हां, तो आप तैयार हैं। शुभकामनाएं।

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
