# من المهم جدًا الحفاظ على تحديث نسخة TailsOS الخاصة بك لتجنب أي نوع من الهجمات الخبيثة التي قد تسرق عملات البيتكوين الخاصة بك! إذا كنت تستخدم نسخة قديمة من TailsOS، تذكر ألا تتصل بالإنترنت أبدًا عند الوصول إلى محفظتك غير المتصلة بالإنترنت! استخدم محرك أقراص USB ثانيًا لإنشاء محفظتك عبر الإنترنت، أو استخدم وسائل أخرى للحصول على محفظة عبر الإنترنت على Android أو iOS، واستخدم طرق الفجوة الهوائية لتوقيع معاملاتك بواسطة رمز QR. أنا لست مسؤولًا عن أي سرقة لعملات البيتكوين الخاصة بك إذا خرقت أي قواعد أمنية، بما في ذلك تجاهل هذا التحذير.

**تم ترجمة هذا الدرس من الإنجليزية إلى العربية باستخدام ChatGPT. قد تكون هناك بعض الأخطاء في الترجمة، لكنني آمل أن يكون مفهوماً للمجتمع الناطق بالعربية!**

**دروس باللغة العربية: إنشاء محفظة باردة للبيتكوين باستخدام نظام Tails والتخزين الدائم**

في هذا الدليل، سأستخدم نظام التشغيل Windows 10. ستحتاج أيضًا إلى محرك USB بسعة لا تقل عن 8 جيجابايت.

1. انتقل إلى https://tails.net/install/download/index.pt.html وقم بتنزيل صورة USB.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. بعد تنزيل صورة USB، قم بالتحقق من التنزيل بالانتقال إلى صفحة التنزيل وتحميل الصورة التي تم تنزيلها بالنقر على الزر الذي يقول **Select your download to verify...**. إذا نجحت عملية التحقق، يمكنك المتابعة؛ وإلا، يجب عليك إعادة تنزيل الصورة. بعد ذلك، قم بتنزيل **balenaEtcher** من هذا الرابط: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. قم بتوصيل محرك USB وبدء **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. اختر صورة USB بالنقر على زر **Flash from file**. يجب أن يتم اكتشاف محرك USB تلقائيًا. إذا لم يكن كذلك، تأكد من تحديد محرك USB الصحيح. ثم انقر على زر **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. انتظر حتى تكتمل عملية الفلاش.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. بعد الانتهاء، أغلق **balenaEtcher** وقم بالتمهيد من محرك USB.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. في Tails، انقر على زر **Start** لبدء Tails OS.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. انتقل إلى **Applications** وابحث عن **Persistent Storage** (يجب أن يكون في علامة التبويب **Favorites**).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. انقر على زر **Continue**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. أنشئ كلمة مرور قوية لتشفير تثبيت Tails OS الخاص بك. انقر فوق زر **Create Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. انتظر حتى تكتمل عملية إنشاء **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. في النافذة التالية بعد الانتهاء، يجب أن يكون **Persistent Folder** مفعلاً افتراضيًا. إذا لم يكن كذلك، فقم بتشغيله.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. قم بتشغيل الاستمرارية لكل من **Electrum Bitcoin Wallet** و **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. أعد تشغيل Tails OS وأدخل كلمة المرور الخاصة بك. ثم انقر على زر **Unlock Encryption** لفتح تخزين Tails Persistent.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. بمجرد فتح التخزين المستمر، انقر على زر **Start Tails**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. الآن، دعنا نتصل بشبكة Tor. تأكد من أن جهاز الكمبيوتر الخاص بك متصل بكابل Ethernet أو Wi-Fi، وابحث عن **Tor Connection** في **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. اختر **Connect to Tor automatically**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. انتظر حتى يتم الاتصال بشبكة Tor.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. بمجرد الاتصال، انقر على زر **Start Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. أو ابحث عن **Tor Browser** في **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. عند فتح **Tor Browser**، انتقل إلى هذا الرابط: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. قم بالتمرير إلى أسفل الصفحة حتى ترى **GPG My Public Key**. انقر بزر الماوس الأيمن على الرابط واختر **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. احفظ الملف في **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. الآن، انتقل إلى صفحة GitHub الخاصة بـ Ian Coleman على هذا الرابط: https://github.com/iancoleman/bip39 وانتقل إلى الإصدارات. يمكنك الوصول إلى الإصدارات من هذا الرابط: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. قم بتنزيل كل من **bip39-standalone.html** و **signature.txt.asc**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. لتنزيل **bip39-standalone.html**، انقر عليه واحفظه في **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. لحفظ **signature.txt.asc**، افعل نفس الشيء كما هو الحال بالنسبة لـ GPG Public Key: انقر بزر الماوس الأيمن عليه واختر **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. احفظه في **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. يمكنك رؤية تنزيلاتك في أيقونة **Downloads** في شريط المتصفح.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. الآن، افصل Tails OS عن الإنترنت. نحن على وشك إنشاء محفظتنا الآن. يبدو الأمر مفرط في الحذر، لكن لنكن آمنين، حسنًا؟

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. انتقل إلى **Applications** وابحث عن **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. الآن، سنستورد المفاتيح ونتحقق مما إذا كان كل شيء جيدًا مع ملف **bip39-standalone.html** الذي قمنا بتنزيله. يمكنك إكمال كل أمر بالضغط على **Tab**.

اكتب:

- cd Persistent/
- اضغط Enter
- cd Tor\ Browser/
- اضغط Enter
- ls (هذا الأمر لعرض الملفات في الدليل، تأكد من وجود جميع الملفات الثلاثة التي قمنا بتنزيلها)
- اضغط Enter
- gpg --import pubkey.asc
- اضغط Enter
- gpg --verify signature.txt.asc
- اضغط Enter

33. تحقق مما إذا كانت تقول **Good signature** من Ian. إذا قالت إنها جيدة، فهذا يعني أن جميع الملفات التي قمنا بتنزيلها شرعية.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. الآن سنرى ما إذا كانت تجزئة **bip39-standalone.html** تتطابق مع التجزئة على GitHub الخاص بـ Ian.

اكتب:

- sha256sum bip39-standalone.html
- اضغط Enter

35. تحقق من كل من التجزئة في Terminal والتجزئة على GitHub الخاص بـ Ian. إذا تطابقت، فإن ملف **bip39-standalone.html** شرعي أيضًا.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. انتقل إلى **Places** واختر **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. افتح ملف **bip39-standalone.html**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. هنا هو مولد محفظة Bitcoin غير المتصل بالإنترنت.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. دعنا ننشئ محفظة بـ 24 كلمة (اختر إما 12 أو 24 لتكون متوافقة مع أي محفظة أخرى).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. انقر على زر **GENERATE** واكتب كلماتك. انتبه بشدة واحتفظ بهذه الكلمات بأمان. إذا فقدتها أو سرقها أحدهم، انتهى الأمر.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. الآن، انتقل إلى **Applications** وابحث عن **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. دعنا نسمي محفظتنا **Offline** لتذكيرك بأنه يجب الوصول إليها فقط بدون اتصال بالإنترنت. اضغط على **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. اختر **Standard wallet**. اضغط على **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. اختر **I already have a seed**. اضغط على **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. اكتب كلماتك في مربع النص، وانقر على **Options**، ستظهر نافذة صغيرة، ويجب عليك اختيار **BIP39 seed** والنقر على **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. تحقق مما إذا كان **BIP39 (checksum: ok)**. اضغط على **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. اختر **native segwit (p2wpkh)**. اضغط على **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. اختر كلمة مرور قوية لتشفير محفظتك غير المتصلة. اضغط على **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. تم إنشاء محفظتك. الآن دعنا نذهب إلى **View** و **Show Addresses** و **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. انظر إلى عناوينك.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. ارجع إلى صفحة **bip39-standalone**، وقم بالتمرير إلى **Derivation Path** وانقر على علامة التبويب **BIP84**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. تحقق مما إذا كان العنوان الأول في صفحة الويب يتطابق مع العنوان الأول المعروض في **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. إذا تطابقت العناوين الأولى (والثانية، والثالثة وهكذا)، فهذا يعني أن محفظتك قد تم استيرادها بشكل صحيح إلى **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

54. الآن اذهب إلى **Electrum Bitcoin Wallet** وانتقل إلى **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. انسخ **Master Public Key** الخاص بك (لا تشارك هذا المفتاح مع أي شخص. إذا حصل شخص ما على مفتاحك العام الرئيسي، سيتمكن من رؤية عناوينك ومقدار Bitcoin التي تمتلكها).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. دعنا ننشئ محفظة أخرى الآن. هذه المرة، ستكون محفظتنا **Online** (أو فقط للمراقبة).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. اختر **Standard wallet**. اضغط على **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. اختر **Use a master key**. اضغط على **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. الصق **Master Public Key** الذي نسخته من محفظتك **Offline**. اضغط على **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. لا تحتاج إلى إضافة كلمة مرور في محفظة المشاهدة فقط، لأن محافظ المشاهدة فقط لا يمكنها إرسال العملات، ولكن الأمر متروك لك. اضغط على **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. تم إنشاء محفظة المشاهدة فقط الخاصة بك، وستظهر لك تحذير يقول **This wallet is watching-only. This means you will not be able to spend Bitcoins with it. Make sure you own the seed phrase or private keys, before you request Bitcoins to be sent to this wallet.**

محفظة المشاهدة فقط هي فقط لعرض العناوين ورصيد Bitcoin، يمكنك إرسال Bitcoins منها ولكن فقط إذا قمت بتوقيع الصفقة باستخدام محفظتك **Offline** أولاً.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. الآن، الخطوة الأخيرة، تحقق مما إذا كانت عناوين المحفظة **Online** تطابق عناوين المحفظة **Offline**. إذا كان الأمر كذلك، فأنت جاهز. حظا سعيدا.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
