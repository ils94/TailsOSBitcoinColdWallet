**Этот учебник был переведен с английского на русский с помощью ChatGPT. Возможно, есть некоторые ошибки перевода, но я надеюсь, что он все равно понятен русскоязычному сообществу!**

**Руководство на русском языке. Создание холодного биткойн-кошелька с использованием ОС Tails и постоянного хранилища**

В этом руководстве я буду использовать Windows 10. Вам также понадобится флеш-накопитель объемом не менее 8 ГБ.

1. Перейдите на https://tails.net/install/download/index.en.html и загрузите образ USB.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/01.PNG?raw=true)

2. После загрузки USB-образа, проверьте его, перейдя на страницу загрузки и загрузив скачанный образ, нажав кнопку **Select your download to verify...** Если проверка прошла успешно, вы можете продолжить; в противном случае, вам нужно будет скачать образ снова. Затем скачайте balenaEtcher по этой ссылке: https://tails.net/etcher/balenaEtcher-portable.exe

![enter image description here](https://github.com/ils94/TailsOSBitcoinColdWallet/blob/main/Images/60.PNG?raw=true)

3. Подключите флеш-накопитель и запустите balenaEtcher.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/02.png?raw=true)

4. Выберите образ USB, нажав кнопку **Flash from file**. Ваш флеш-накопитель должен быть автоматически обнаружен. Если нет, убедитесь, что вы выбираете правильный флеш-накопитель. Затем нажмите кнопку **Flash!**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/03.png?raw=true)

5. Дождитесь завершения процесса записи.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/04.png?raw=true)

6. После завершения закройте balenaEtcher и загрузитесь с флеш-накопителя.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/05.png?raw=true)

7. В Tails нажмите кнопку **Start**, чтобы запустить Tails OS.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/06.png?raw=true)

8. Перейдите в **Applications** и найдите **Persistent Storage** (он должен быть в закладке Favorites).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/07.png?raw=true)

9. Нажмите кнопку **Continue**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/08.png?raw=true)

10. Создайте надежный пароль для шифрования установки Tails OS.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/09.png?raw=true)

11. Дождитесь завершения создания **Persistent Storage**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/10.png?raw=true)

12. В следующем окне после завершения у вас должна быть включена **Persistent Folder** по умолчанию. Если нет, включите ее.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/11.png?raw=true)

13. Включите постоянство как для **Electrum Bitcoin Wallet**, так и для **GnuPG**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/12.png?raw=true)

14. Перезагрузите Tails OS и введите пароль. Затем нажмите кнопку **Unlock Encryption**, чтобы разблокировать ваше постоянное хранилище Tails.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/13.png?raw=true)

15. После разблокировки постоянного хранилища нажмите кнопку **Start Tails**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/14.png?raw=true)

16. Теперь давайте подключимся к сети Tor. Убедитесь, что ваш компьютер подключен к кабелю Ethernet или Wi-Fi, и найдите **Tor Connection** в **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/15.png?raw=true)

17. Выберите **Connect to Tor automatically**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/16.png?raw=true)

18. Дождитесь подключения к сети Tor.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/17.png?raw=true)

19. После подключения нажмите кнопку **Start Tor Browser**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/18.png?raw=true)

20. Или найдите **Tor Browser** в **Applications**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/19.png?raw=true)

21. С открытым **Tor Browser** перейдите по этой ссылке: https://iancoleman.io/

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/20.png?raw=true)

22. Прокрутите страницу вниз, пока не увидите **GPG My Public Key**. Щелкните правой кнопкой мыши ссылку и выберите **Save Link As...**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/21.png?raw=true)

23. Сохраните файл в **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/22.png?raw=true)

24. Теперь перейдите на страницу GitHub Иэна Коулмана по этой ссылке: https://github.com/iancoleman/bip39 и перейдите к Releases. Вы можете получить доступ к релизам по этой ссылке: https://github.com/iancoleman/bip39/releases

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/23.png?raw=true)

25. Загрузите как **bip39-standalone.html**, так и **signature.txt.asc**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/24.png?raw=true)

26. Чтобы загрузить **bip39-standalone.html**, просто щелкните по нему и сохраните его в **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/25.png?raw=true)

27. Чтобы сохранить **signature.txt.asc**, сделайте то же самое, что с GPG Public Key: щелкните правой кнопкой мыши и выберите **Save Link As...**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/26.png?raw=true)

28. Сохраните его в **/home/amnesia/Persistent/Tor Browser**

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/27.png?raw=true)

29. Вы можете увидеть свои загрузки в значке **Downloads** на панели инструментов браузера.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/28.png?raw=true)

30. Теперь отключите Tails OS от интернета. Мы собираемся создать наш кошелек. Кажется, это слишком параноидально, но давайте будем осторожными, хорошо?

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/29.png?raw=true)

31. Перейдите в **Applications** и найдите **Terminal**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/30.png?raw=true)

32. Теперь мы импортируем ключи и проверяем, все ли в порядке с файлом **bip39-standalone.html**, который мы загрузили. Вы можете автоматически завершить каждую команду, нажав **Tab**.

Напишите:

- cd Persistent/
- Нажмите Enter
- cd Tor\ Browser/
- Нажмите Enter
- ls (эта команда предназначена для перечисления файлов в каталоге, убедитесь, что все 3 файла, которые мы загрузили, есть в нем)
- Нажмите Enter
- gpg --import pubkey.asc
- Нажмите Enter
- gpg --verify signature.txt.asc
- Нажмите Enter

33. Проверьте, указывает ли он **Good signature** от Иэна. Если он говорит, что все в порядке, то это означает, что все загруженные нами файлы подлинные.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/31.png?raw=true)

34. Теперь мы проверим, совпадает ли хеш **bip39-standalone.html** с хешем на GitHub Иэна.

Напишите:

- sha256sum bip39-standalone.html
- Нажмите Enter

35. Проверьте как хеш в терминале, так и хеш на GitHub Иэна. Если они совпадают, то файл **bip39-standalone.html** также подлинный.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/32.png?raw=true)

36. Перейдите в **Places** и выберите **Tor Browser (persistent)**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/33.png?raw=true)

37. Откройте файл **bip39-standalone.html**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/34.png?raw=true)

38. Вот наш генератор офлайн-кошелька Bitcoin.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/35.png?raw=true)

39. Давайте создадим кошелек из 24 слов (выберите 12 или 24, чтобы он был совместим с любым другим кошельком).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/36.png?raw=true)

40. Нажмите кнопку **GENERATE** и запишите свои слова. Обратите ОЧЕНЬ много внимания и храните эти слова в безопасности. Если вы их потеряете или кто-то украдет их, это конец игры.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/37.png?raw=true)

41. Теперь перейдите в **Applications** и найдите **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/38.png?raw=true)

42. Давайте назовем наш кошелек **Offline**, чтобы напомнить вам, что вы должны обращаться к нему только без подключения к Интернету. Нажмите **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/39.png?raw=true)

43. Выберите **Standard wallet**. Нажмите **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/40.png?raw=true)

44. Выберите **I already have a seed**. Нажмите **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/41.png?raw=true)

45. Введите свои слова в текстовое поле и нажмите **Options**, появится небольшое окно, в котором вы должны выбрать **BIP39 seed** и нажать **OK**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/42.png?raw=true)

46. Проверьте, есть ли **BIP39 (checksum: ok)**. Нажмите **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/43.png?raw=true)

47. Выберите **native segwit (p2wpkh)**. Нажмите **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/44.png?raw=true)

48. Выберите надежный пароль для шифрования вашего офлайн-кошелька. Нажмите **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/45.png?raw=true)

49. Ваш кошелек создан. Теперь давайте перейдем к **View** и **Show Addresses** и **Show Coins**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/46.png?raw=true)

50. Просмотрите ваши адреса.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/47.png?raw=true)

51. Вернитесь на страницу **bip39-standalone** и прокрутите до **Derivation Path** и перейдите на вкладку **BIP84**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/48.png?raw=true)

52. Проверьте, совпадает ли первый адрес на веб-странице с первым адресом, показанным в **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/49.png?raw=true)

53. Если совпадают оба первых адреса (и второй, и третий и так далее), это означает, что ваш кошелек был правильно импортирован в **Electrum Bitcoin Wallet**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/50.png?raw=true)

54. Теперь перейдите в **Electrum Bitcoin Wallet** и перейдите в **Information**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/51.png?raw=true)

55. Скопируйте ваш **Master Public Key** (не делясь этим ключом ни с кем. Если кто-то получит доступ к вашему **Master Public Key**, он сможет видеть ваши адреса и сколько Bitcoin вы имеете).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/52.png?raw=true)

56. Теперь создадим еще один кошелек. На этот раз он будет нашим **Online** кошельком (или только для просмотра).

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/53.png?raw=true)

57. Выберите **Standard wallet**. Нажмите **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/54.png?raw=true)

58. Выберите **Use a master key**. Нажмите **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/55.png?raw=true)

59. Вставьте свой **Master Public Key**, который вы скопировали из вашего **Offline** кошелька. Нажмите **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/56.png?raw=true)

60. Вам не нужно добавлять пароль в свой кошелек только для просмотра, потому что кошельки только для просмотра не могут отправлять монеты, но это зависит от вас. Нажмите **Next**.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/57.png?raw=true)

61. Ваш кошелек только для просмотра создан, и вы увидите предупреждение, что **Этот кошелек только для просмотра. Это означает, что вы не сможете тратить биткоины с его помощью. Убедитесь, что у вас есть фраза восстановления или частные ключи, прежде чем запросить отправку биткоинов на этот кошелек.**

Кошелек только для просмотра предназначен только для отображения адресов и баланса биткоинов, вы можете отправлять биткоины из него, но только если подпишете транзакцию с вашим **Offline** кошельком сначала.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/58.png?raw=true)

62. Теперь последний шаг, проверьте, совпадают ли адреса **Online** кошелька с **Offline** кошельком. Если да, то все готово. Удачи.

![enter image description here](https://github.com/ils94/TailsOSBitcoinWallet/blob/main/Images/59.png?raw=true)
