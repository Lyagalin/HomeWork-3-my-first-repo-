# Инструкция для работы с Markdown

## Выделение текста 

Что бы выделить текст курсиовм нужно выделить  текст (*) или занокм нижнего подчеркивания (_). Например: *вот так*, _вот так_.

Что бы выделить текст поолужирным, необходимо обрамить его (**) или двойным знакм нижнего подчеркивания (__). Например: **вот так**, __Вот так__.

Альтернативные способы выделения текста жирным или курсивом нужны  для того, что бы мы могли совмещать оба способа. Например: _Текст может быть одновременно курсивои и **полужирным**_.

## Списки

что бы добавить ненумерованные списки, необходимо пункуты выделить звездочкой или знаком + 
* Элемент 1
* Элемент 2
* Элеиент 3
+ Элемент 4

Что бы добавить нумеранные списки, необходимо пронумеровать. Например:
1. Первый пункт 
2. Второй пункт 

## Работа с изображениями

Чтобы вставить изображение в текст,достаточно написать следущее:
![Привет, это крузак!](foto-tlc-200-2020_00.jpg)

## Ссылки
что бы создать ссылкку нужно [текст ссылки](ссылка)

Чтобы сделать ссылку нужно [текст ссылки](адрес ссылки)
папример: [Cruser200](Https://example.com)

## Работа с таблицами 

Буква | Цифра | Символ
------ | ------|----------
a      | 4     | $
x      | 365    | (
b      |       | ^  

Буква|Цифра|Символ
---|---|---
a|4|$
 |365|(
b| |^  

Column | Column
------ | ------
\| Cell \|| \| Cell \|  


Column | Column | Column
:----- | :----: | -----:
Left   | Center | Right
align  | align  | align


## Цитаты

## Заключение 
 
 В заключении опишем таблицы
| заголовок 1 | заголовк 2 |
| ----------- | ---------- |
| Ячейка 1    | Ячейка 2 |
| Ячейка 3    | Ячейка 4 |


# Работа с удаленными репозиториями 
## Инициализация репозитория

```sh
git init
```

## Статус репозитория

```sh
git status
```
# Как включить ssh в Windows 10

В ОС Windows 10 по умолчанию уже есть ssh. Его надо только активировать.

Зайдите в Параметры - Приложения - Приложения и возможности - Дополнительные компоненты. В указанном спсике найдите **Клиент OpenSSH**, жмите установить.

Откройте cmd.

Наберите команду 
```sh
C:\Users\USER\> ssh
usage: ssh [-46AaCfGgKkMNnqsTtVvXxYy] [-B bind_interface]
           [-b bind_address] [-c cipher_spec] [-D [bind_address:]port]
           [-E log_file] [-e escape_char] [-F configfile] [-I pkcs11]
           [-i identity_file] [-J [user@]host[:port]] [-L address]
           [-l login_name] [-m mac_spec] [-O ctl_cmd] [-o option] [-p port]
           [-Q query_option] [-R address] [-S ctl_path] [-W host:port]
           [-w local_tun[:remote_tun]] destination [command]
```
Перейдите к созданию ssh ключа.

# Что такое ssh

SSH (англ. Secure Shell — «безопасная оболочка»[1]) — сетевой протокол прикладного уровня, позволяющий производить удалённое управление операционной системой и туннелирование TCP-соединений (например, для передачи файлов). Схож по функциональности с протоколами Telnet и rlogin, но, в отличие от них, шифрует весь трафик, включая и передаваемые пароли. SSH допускает выбор различных алгоритмов шифрования. SSH-клиенты и SSH-серверы доступны для большинства сетевых операционных систем.

#  Как сгенерировать ssh ключ для github

Необходимо выполнить команду
```sh
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```## Инициализация репозитория

```sh
git init
```

## Статус репозитория

```sh
git status
```
# Как включить ssh в Windows 10

В ОС Windows 10 по умолчанию уже есть ssh. Его надо только активировать.

Зайдите в Параметры - Приложения - Приложения и возможности - Дополнительные компоненты. В указанном спсике найдите **Клиент OpenSSH**, жмите установить.

Откройте cmd.

Наберите команду 
```sh
C:\Users\USER\> ssh
usage: ssh [-46AaCfGgKkMNnqsTtVvXxYy] [-B bind_interface]
           [-b bind_address] [-c cipher_spec] [-D [bind_address:]port]
           [-E log_file] [-e escape_char] [-F configfile] [-I pkcs11]
           [-i identity_file] [-J [user@]host[:port]] [-L address]
           [-l login_name] [-m mac_spec] [-O ctl_cmd] [-o option] [-p port]
           [-Q query_option] [-R address] [-S ctl_path] [-W host:port]
           [-w local_tun[:remote_tun]] destination [command]
```
Перейдите к созданию ssh ключа.

# Что такое ssh

SSH (англ. Secure Shell — «безопасная оболочка»[1]) — сетевой протокол прикладного уровня, позволяющий производить удалённое управление операционной системой и туннелирование TCP-соединений (например, для передачи файлов). Схож по функциональности с протоколами Telnet и rlogin, но, в отличие от них, шифрует весь трафик, включая и передаваемые пароли. SSH допускает выбор различных алгоритмов шифрования. SSH-клиенты и SSH-серверы доступны для большинства сетевых операционных систем.

#  Как сгенерировать ssh ключ для github

Необходимо выполнить команду
```sh
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```




