# RITOPOS
RITOPOS (Resloving Informatics & Technology Olimpiad Problems OS) - это LFS-based дистрибутив линукс. Был создан для локального сообщества.

# Стандартная конфигурация
## ПО
Как LFS-based дистрибутив, RITOPOS имеет:
- Python 2
- GCC
- Vim
- Sysvinit

Также были добавленны:
- Micro
- Несколько игр

## Пользователи
По умолчанию в RITOPOS есть 2 пользователя:
- `root`     (пароль: `ritopos`)
- `ritopos`  (пароль: `ritopos`)

# Установка и настройка
Предполагается, что установка производится с системы Linux.
Для установки RITOPOS нужно:
1. Разметить диск как вам нужно, создать необходимые файловые системы.
2. Распаковать архив из репозитория.
3. Перенести файлы с распакованного архива на нужный вам раздел.
4. Настроить загрузчик по инструкциям из книги LFS ([Монтирование файловых систем](https://book.linuxfromscratch.ru/12.1/systemv/chapter07/kernfs.html), [Вход в окружение chroot](https://book.linuxfromscratch.ru/12.1/systemv/chapter07/chroot.html), [Настройка загрузки](https://book.linuxfromscratch.ru/12.1/systemv/chapter10/grub.html))

Предполагается, что инструкции по последующей конфигурации из книг [проекта LFS](https://www.linuxfromscratch.org/) также будут работать.
