# Pelatihan-Linux-2025
Pelatihan Linux 2025

1. Mengunduh program wget, unzip, dan xxd, lalu membuat folder baru bernama “artists_who_can_sing” dan masuk ke dalam folder tersebut
```bash
sudo apt install wget unzip xxd && mkdir artist_who_can_sing && cd artist_who_can_sing
```
2. Mendownload file zip menggunakan wget
```bash
wget "https://drive.usercontent.google.com/u/0/uc?id=1lV1HVmPTY_BOAK6ToXymRu7V5eVfR0ut&export=download" -O tutorials.zip
```
3. Unzip ke dalam folder baru yang bernama “singing_tutorials”
```bash
mkdir singing_tutorials && unzip tutorials.zip -d singing_tutorials
```
4. Masuk ke dalam folder "singing_tutorials" dan menampilkan list file termasuk yang tersembunyi
```bash
cd singing_tutorials && ls -la
```
5. Mencari file "opera" oleh "NBAYoungboy", cari yang berisi FLAG{isi} kemudian tampilkan satu baris dengan link benar dan pipe hasilnya ke flag.txt pada direktori sebelumnya
```bash
find . -name "*_opera_*_NBAYoungboy*" | grep -rIh "FLAG{.*}" | head -n 1 > ../flag.txt
```
6. Mundur satu folder kemudian download sebuah file baru dengan ketentuan nama “plsrunmeiamnotmalwarefr”
```bash
cd ../ && wget https://files.catbox.moe/9l4qu8 -O plsrunmeiamnotmalwarefr
```
7. Dapatkan izin untuk execute kemudian jalankan program
```bash
chmod +x plsrunmeiamnotmalwarefr
```
8. Jalankan program tersebut
```bash
./plsrunmeiamnotmalwarefr ps aux
```
9. Buat file bernama ransom.moolah
```bash
touch ransom.moolah
```
10. Mematikan process
```bash
^C
```
```bash
(or) kill ___
```
```bash
rm (file)
```
```bash
clear
```
