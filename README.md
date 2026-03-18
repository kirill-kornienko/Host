# Домашнее задание к занятию «Защита хоста» - `Корниенко Кирилл`


### Задание 1. 

1. Установите eCryptfs.
2. Добавьте пользователя cryptouser.
3. Зашифруйте домашний каталог пользователя с помощью eCryptfs.

*В качестве ответа пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.*

### Ответ:

1. Добавьте пользователя cryptouser.

![adduser](https://github.com/kirill-kornienko/Host/blob/main/sudo%20adduser%20cryptouser.png)

3. Зашифруйте домашний каталог пользователя с помощью eCryptfs.

![ecryptfs](https://github.com/kirill-kornienko/Host/blob/main/sudo%20ecryptfs.png)

![sudo_ecryptfs](https://github.com/kirill-kornienko/Host/blob/main/sudo%20ecryptfs.png)

![toush](https://github.com/kirill-kornienko/Host/blob/main/touch.png)

![private](https://github.com/kirill-kornienko/Host/blob/main/private.png)



### Задание 2

1. Установите поддержку LUKS.

2. Создайте небольшой раздел, например, 100 Мб.

3. Зашифруйте созданный раздел с помощью LUKS.


*В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.*

### Ответ:

1. Установите поддержку LUKS.

![luks](https://github.com/kirill-kornienko/Host/blob/main/luks.png)

2. Создайте небольшой раздел, например, 100 Мб.

![lsblk](https://github.com/kirill-kornienko/Host/blob/main/lsblk.png)

3. Зашифруйте созданный раздел с помощью LUKS.

![mkfs](https://github.com/kirill-kornienko/Host/blob/main/mkfs.png)

![secret](https://github.com/kirill-kornienko/Host/blob/main/secret.png)

![bad](https://github.com/kirill-kornienko/Host/blob/main/bad%20option.png)

![test](https://github.com/kirill-kornienko/Host/blob/main/test_txt.png)




