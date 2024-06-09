# Дуже важливо тримати вашу версію TailsOS оновленою, щоб уникнути будь-яких зловмисних атак, які можуть вкрасти ваші Bitcoins! Якщо ви використовуєте застарілу версію TailsOS, пам'ятайте, що НІКОЛИ не підключайтеся до інтернету при доступі до вашого офлайн-гаманця! Використовуйте другий USB-накопичувач для створення вашого онлайн-гаманця або використовуйте інші засоби для мати онлайн-гаманець на Android або iOS, та використовуйте методи підписання ваших транзакцій за допомогою QR-коду. Я не несу відповідальності за будь-яке викрадення ваших Bitcoins, якщо ви порушите будь-які правила безпеки, включаючи ігнорування цього попередження.

**Цей підручник було перекладено з англійської на українську за допомогою ChatGPT. Можуть бути деякі помилки в перекладі, але я сподіваюся, що він все одно буде зрозумілим для україномовної спільноти!**

**Український підручник: Створення холодного Bitcoin гаманця за допомогою TailsOS і постійного сховища**

У цьому підручнику я буду використовувати Windows 10. Вам також знадобиться USB флешка з об'ємом принаймні 8 ГБ.

1. Перейдіть на https://tails.net/install/download/index.en.html і завантажте **USB image**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. Після завантаження **USB image**, перевірте завантаження, перейшовши на сторінку завантаження і завантаживши ваш завантажений образ, натиснувши кнопку, що каже **Select your download to verify...** Якщо перевірка пройшла успішно, ви можете продовжувати; інакше вам потрібно повторно завантажити образ. Потім завантажте **balenaEtcher** за цим посиланням: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Вставте вашу USB флешку і запустіть **balenaEtcher**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Виберіть **USB image**, натиснувши кнопку **Flash from file**. Ваша USB флешка повинна бути автоматично виявлена. Якщо ні, переконайтеся, що ви вибираєте правильну USB флешку. Потім натисніть кнопку **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Дочекайтеся завершення процесу прошивки.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. Після завершення закрийте **balenaEtcher** і завантажтеся з USB флешки.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. У **TailsOS** натисніть кнопку **Start Tails** для запуску **TailsOS**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Перейдіть до **Applications** і знайдіть **Persistent Storage** (вона повинна бути у вкладці **Favorites**).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Натисніть кнопку **Continue**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Створіть надійний пароль для шифрування вашої установки **TailsOS**. Натисніть кнопку **Create Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Дочекайтеся завершення створення **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. У наступному вікні після завершення у вас повинна бути **Persistent Folder** ввімкнена за замовчуванням. Якщо ні, увімкніть її.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Увімкніть стійкість для обох **Electrum Bitcoin Wallet** і **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Перезапустіть **TailsOS** і введіть ваш пароль. Потім натисніть кнопку **Unlock Encryption** для розблокування вашого **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. Після розблокування **Persistent Storage** натисніть кнопку **Start Tails**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Тепер давайте підключимося до мережі Tor. Переконайтеся, що ваш комп'ютер підключений до Ethernet або Wi-Fi, і знайдіть **Tor Connection** у **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Виберіть **Connect to Tor automatically** і натисніть кнопку **Connect to Tor**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Дочекайтеся підключення до мережі Tor.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. Після підключення натисніть кнопку **Start Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Або знайдіть **Tor Browser** у **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. З відкритим **Tor Browser** перейдіть за цим посиланням: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Прокрутіть сторінку вниз, поки не побачите **GPG My Public Key**. Клацніть правою кнопкою миші на посилання і виберіть **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Збережіть файл у **/home/amnesia/Persistent/Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Тепер перейдіть на сторінку **Ian Coleman GitHub** за цим посиланням: https://github.com/iancoleman/bip39 і перейдіть до розділу Випуски. Ви можете отримати доступ до випусків за цим посиланням: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Завантажте обидва **bip39-standalone.html** і **signature.txt.asc**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. Щоб завантажити **bip39-standalone.html**, просто натисніть на нього і збережіть у **/home/amnesia/Persistent/Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. Щоб зберегти **signature.txt.asc**, зробіть те саме, що і для **GPG Public Key**: клацніть правою кнопкою миші і виберіть **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Збережіть його у **/home/amnesia/Persistent/Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Ви можете побачити свої завантаження у значку **Downloads** у панелі браузера.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Тепер відключіть **TailsOS** від інтернету. Зараз ми створимо наш гаманець. Це може здатися параноїдальним, але давайте будемо обережними, добре?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Перейдіть до **Applications** і знайдіть **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Тепер ми імпортуємо ключі і перевіримо, чи все добре з файлом **bip39-standalone.html**, який ми завантажили. Ви можете автоматично заповнити кожну команду, натиснувши **Tab**.

Наберіть:

- cd Persistent/
- Натисніть Enter
- cd Tor\ Browser/
- Натисніть Enter
- ls (ця команда виведе список файлів у директорії, перевірте, чи всі 3 файли, які ми завантажили, у ній)
- Натисніть Enter
- gpg --import pubkey.asc
- Натисніть Enter
- gpg --verify signature.txt.asc
- Натисніть Enter

33. Перевірте, чи з'явиться напис **Good signature from Ian Coleman <ian@iancoleman.io>**. Якщо написано, що підпис хороший, це означає, що всі файли, які ми завантажили, легітимні.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Тепер ми подивимося, чи збігається хеш файлу **bip39-standalone.html** з хешем на GitHub Іана.

Наберіть:

- sha256sum bip39-standalone.html
- Натисніть Enter

35. Звірте хеш в терміналі з хешем на **Ian Coleman GitHub**. Якщо вони збігаються, то файл **bip39-standalone.html** також легітимний.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Перейдіть до **Places** і виберіть **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Відкрийте файл **bip39-standalone.html**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Ось наш офлайн-генератор Bitcoin гаманців.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Давайте згенеруємо гаманець на 24 слова (виберіть 12 або 24, щоб зробити його сумісним з будь-яким іншим гаманцем).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Натисніть кнопку **GENERATE** і запишіть свої слова. Зверніть ДУЖЕ велику увагу і зберігайте ці слова надійно. Якщо ви їх втратите або хтось їх вкраде, це кінець гри.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Тепер перейдіть до **Applications** і знайдіть **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Назвемо наш гаманець **Offline**, щоб нагадати вам, що ви повинні доступатися до нього тільки без інтернет-з'єднання. Натисніть **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Виберіть **Standard wallet**. Натисніть **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Виберіть **I already have a seed**. Натисніть **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Введіть свої слова в текстове поле і натисніть **Options**, з'явиться невелике вікно, і ви повинні вибрати **BIP39 seed** і натиснути **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Перевірте, чи відображається **BIP39 (checksum: ok)**. Натисніть **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Виберіть **native segwit (p2wpkh)**. Натисніть **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Виберіть надійний пароль для шифрування вашого гаманця **Offline**. Натисніть **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Ваш гаманець створено. Тепер перейдіть до **View** і виберіть **Show Addresses** і **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Перегляньте свої адреси.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Поверніться на сторінку **bip39-standalone**, і прокрутіть вниз до **Derivation Path** і натисніть на вкладку **BIP84**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Перевірте, чи збігається перша адреса на веб-сторінці з першою адресою, що відображається в **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Якщо обидві перші адреси збігаються (і друга, і третя і т.д.), це означає, що ваш гаманець був правильно імпортований до **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

**Це частина, де ми створюємо наш онлайн-гаманець, і у вас є два варіанти:**

- **1- Ви можете створити онлайн-гаманець у тій самій інсталяції TailsOS, яка містить ваш офлайн-гаманець. У цьому випадку ВИ НЕ ПОВИННІ ПІДКЛЮЧАТИСЯ ДО ІНТЕРНЕТУ при доступі до офлайн-гаманця, щоб запобігти будь-яким атакам на ваші Bitcoins.**

- **2- Ви можете використовувати інший USB-накопичувач, виконати той самий процес, що й вище, а потім виконати наступні кроки для створення вашого онлайн-гаманця на новому USB-накопичувачі. Це допоможе запобігти помилці підключення до інтернету при доступі до офлайн-гаманця.**

54. Тепер перейдіть до **Electrum Bitcoin Wallet** і до розділу **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Скопіюйте ваш **Master Public Key** (не діліться цим ключем з будь-ким. Якщо хтось отримає доступ до вашого **Master Public Key**, вони зможуть бачити ваші адреси і кількість Bitcoin, які ви маєте).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Тепер створимо ще один гаманець. Цього разу це буде наш **Online** гаманець (або тільки для перегляду).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Виберіть **Standard wallet**. Натисніть **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Виберіть **Use a master key**. Натисніть **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Вставте ваш **Master Public Key**, який ви скопіювали з вашого **Offline** гаманця. Натисніть **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Вам не обов'язково додавати пароль до вашого гаманця тільки для перегляду, оскільки гаманці тільки для перегляду не можуть відправляти монети, але це залежить від вас. Натисніть **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Ваш гаманець тільки для перегляду створено, і ви побачите попередження, що каже **Цей гаманець призначений тільки для перегляду. Це означає, що ви не зможете витрачати Bitcoins з нього. Переконайтеся, що ви маєте сид-фразу або приватні ключі, перш ніж ви запитаєте надсилання Bitcoins на цей гаманець.**

Гаманець тільки для перегляду призначений тільки для показу адрес і балансу Bitcoin, ви можете відправляти Bitcoin з нього, але тільки якщо ви підписуєте транзакцію з вашим **Offline** гаманцем спочатку.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Тепер останній крок, перевірте, чи збігаються адреси **Online** гаманця з **Offline** гаманцем. Якщо так, то ви готові. Удачі.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
