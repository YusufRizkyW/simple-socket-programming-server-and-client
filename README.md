# Tutorial percobaan simple client and server di OS Linux Ubuntu
source code https://github.com/ferryastika/socket-programming-simple-server-and-client

# 1. Pasang IDE di Ubuntu
saya pakai code:block

# 2. Setting copy / paste di VB ( opsional )
Opsional untuk memudahkan copy paste antar host dan guest, buka terminal ubuntu, jalankan command ini
> sudo apt update

lanjut
> sudo apt install build-essential dkms

Tunggu sampai downlod selesai

Terus masuk ke directory tempat anda mendownload file tadi
> cd /media/(ganti pakai username ubuntu)/VBox_GAs_(versi yg di download)/

Lalu jalankan instalasi
> sudo ./VBoxLinuxAdditions.run

Setelah itu restart ubuntu, di Virtual Box sebelum start ke ubuntu pilih menu settings > general > advanced >
> shared clipboard ganti ke bidirectional

> drag and drop ganti ke bidirectional

Klik Ok, kemudian start ubuntu seperti biasa

# 3. Percobaan
Buka code:block dan buat file baru

copy code program server dari file server.c di github, kemudian simpan di directory home

buat file kedua client.c, langkah sama seperti file server.c
