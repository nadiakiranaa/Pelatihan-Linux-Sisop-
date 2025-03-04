# PELATIHAN LINUX SISOP
  
1.Mengunduh program wget, unzip, xxd && membuat folder "artists_who_can_sing" 
  ````
 sudo apt install && wget --no-check-certificate "https://drive.google.com/uc?export=download&id=1lV1HVmPTY_BOAK6ToXymRu7V5eVfR0ut" -O nadia.zip
  ````
   
2. Mendownload file zip menggunakan wget
  ````
  wget --no-check-certificate "https://drive.google.com/uc?export=download&id=1lV1HVmPTY_BOAK6ToXymRu7V5eVfR0ut" -O nadia.zip
  ````
   
3. unzip ke folder “singing_tutorials” 
  ````
 unzip nadia.zip -d singing_tutorials
  ````
   
4. Masuk ke dalam folder & menampilkan list file & melihat list file yang tersembunyi 
  ````
cd singing_tutorials/ && ls -la
  ````
   
5. Mencari file “opera” dibuat oleh “NBAYoungboy” & dimasukkan ke folder “flag.txt”
  ````
 find .*opera*NBAY* && strings .*opera*NBAY*|grep FLAG{ && strings .*opera*NBAY*|grep FLAG{ > flag.txt
  ````
6. Mundur ke directory sebelum & download file “plsrunmeiamnotmalwarefr”
  ````
 cd .. &&  wget https://files.catbox.moe/9l4qu8 -O plsrunmeiamnotmalwarefr
  ````
7. Izin execute dan menjalankan program
  ````
 chmod +x plsrunmeiamnotmalwarefr && ./plsrunmeiamnotmalwarefr 
  ````
8. Melihat program yang dijalankan menggunakan command di terminal linux
  ````
  ps aux
  ````
9. Membuat file bernama ransom.moolah && mengecek keadaan
  ````

  ````
   
  1.a
  ````
  ````
   
  1.a
  ````
  ````
