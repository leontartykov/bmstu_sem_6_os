# Файловая система /proc

## Задание:
Написать программу – загружаемый модуль ядра (LKM) – которая
поддерживает чтение из пространства пользователя и запись в
пространство пользователя из пространства ядра.
После загрузки модуля пользователь должен иметь возможность
загружать в него строки с помощью команды echo, а затем считывать их с
помощью команды cat.