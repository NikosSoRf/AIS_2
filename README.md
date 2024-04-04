## Пояснение к работе
определение папки

```
cd /home/noks/Desktop/ASI-main

```
## Запуск Makefile.

make all

cd app
## Запуск сервера

```
./server [PORT] [ДИРЕКТОРИЯ] [MAX_CLIENTS] [MAX_FILE_SIZE]
./server 4026 ~/Downloads 2 10000

```
## Запуск от рута
su -
## Запуск параллельно
sudo apt install parallel

## Запуск клиента

```

./client [IP] [SERVER PORT] [FILENAME]
parallel -j0 ./client 127.0.0.1 4026 :::
/home/noks/Desktop/ASI-main/Haru
/home/noks/Desktop/ASI-main/Haru1
/home/noks/Desktop/ASI-main/Haru2
/home/noks/Desktop/ASI-main/Haru3
или
parallel -j0 ./client 127.0.0.1 4026 :::
/home/noks/Desktop/ASI-main/son1
/home/noks/Desktop/ASI-main/son2
```
## Удаление сборки
```
make clean
```
