# labpy03
# Nama = Taufik eka albani
# Nim = 312210347
# Kelas = TI.22.A3

# Latihan 1

# Program Sederhana Untuk Menampilkan N Bilangan Acak Yang Lebih Kecil Dari 0.5

## A. Algoritma Program Untuk Menampilkan N Bilangan Acak Yang Lebih Kecil Dari 0.5
1. Masukan Jumlah N perulangan
2. Proses perulangan sesuai jumlah perulangan yang dinputkan
3. Tampilkan perulangan dengan nilai di bawah 0.5
4. Selesai


# B. Flowchart Program

![flowchart latihan1](https://user-images.githubusercontent.com/46926758/53193448-8e52a380-3643-11e9-9f3e-82b74718a6aa.png)
 
# C. Program Untuk Menampilkan N Bilangan Acak Yang Lebih Kecil Dari 0.5

## > Urutan Pembuatan Program

1. Ketikan Program *print ('Tampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5')*
2. Ketikan Program *jumlah=int(input("Masukan Jumlah N : "))*
3. Ketikan Program *import random*
4. Ketikan Program *for i in range ( jumlah ) :*
5. Ketikan Program *print("Data ke", 1+i,"=>", (random.uniform(0.1,0.5)))* 

### > Penjelasan Alur Program

1. *print ('Tampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5')* Untuk Menampilkan atau Mencetak kalimat Tampilkan N Bilangan Acak         yang Lebih Kecil Dari 0.5

2. *jumlah=int(input("Masukan Jumlah N : "))* Untuk menentukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe data      bilangan bulat

3. *import random**

4. *for i in range ( jumlah )* : Untuk Pengulangan dengan range jumlah

5. *print("Data ke", 1+i,"=>", (random.uniform(0.1,0.5)))* Untuk menampilkan atau mencetak urutan data sesuai jumlah inputan dengan        hasil di bawah 0.5

## D. Hasil

![Screenshot (54)](https://user-images.githubusercontent.com/115517181/199735490-e84bc018-dd63-4aee-8fca-289f161c8d7f.png)

# Latihan 2

# Program Sederhana Untuk Menampilkan Bilangan Terbesar Dari N Buah Data Yang Dinputkan

## A. Algoritma Program Untuk Menampilkan Bilangan Terbesar Dari N Buah Data Yang Dinputkan

1. mulai
2. input bilangan N
3. Jika max < a maka akan lanjut pengulangan
4.Jika a==0 maka akan berhenti proses pengulangan
5. Dan mencetak hasil nilai maxium dari N yang di isikan
6. Selesai

Setelah anda menegetahui Algoritma Dalam sebuah Program Maka Langkah Berikutnya Kita Membuat Flowchartnya. Berikut ini Flowchart Program 

## B. Flowchart Program

![flowchart latihan2](https://user-images.githubusercontent.com/46926758/53195549-73366280-3648-11e9-9741-4b5eba27802d.png)

## C. Program Untuk Menampilkan Bilangan Terbesar Dari N Buah Data Yang Dinputkan


### > Urutan Pembuatan Program

1. Ketikan Program *print ('Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan')*
2. Ketikan Program *max= 0*
3. Ketikan Program *while true:*
4. Ketikan Program *a=int(input("Masukan Bilangan :"))*
5. Ketikan Program *if max < a*
6. Ketikan Program *max=a*
7. Ketikan Program *if a==0:*
8. Ketikan Program *break*
9. Ketikan Program *print("Bilangan Tebesar Adalah :", max)*

### > Penjelasan Alur Program

1. *print ('Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan')* Untuk menampilkan kalimat *Menampilkan Bilangan Terbesar      Dari  N Buah Data Yang Diinputkan*

2. *max= 0* kode max disini untuk menentukan nilai max nya dalah 0

3. *while true:* Untuk perulangan hingga waktu yang tidak di tentukan atau selamanya

4. *a=int(input("Masukan Bilangan :"))* a untuk menginput tipe data interger ( bilangan bulat )

5. *if max < a max=a* jika max kurang dari a maka max = a

6. *if a==0: break* jika a= 0 maka akan berhenti dengan syarat break yang terpenuhi

7. *print("Bilangan Tebesar Adalah :", max)* Menampilkan *Bilangan Tebesar Adalah : Nilai maxiumnya

## D. Hasil 

![Screenshot (55)](https://user-images.githubusercontent.com/115517181/199735508-612ffacf-7d3a-43b3-a15a-ff2c58379b27.png)

# Program 1

# Program Sederhana Untuk Menghitung Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan

## A. Algoritma Program Untuk Menghitung Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan

1. Mulai
2. Input modal misalkan x = 20.000.000 ( deklarasikan )
3. Input presentase untung a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.03x
4. For i in range (len (t)) pengulangan
5. Print (“laba bulan ke-“,i+1,”sebesar:” ,t[i])
6. Menghitung jumlah laba keseluruhan u= (a+b+c+d+e+f+g+h)
7. Print (“total laba adalah:”)
8. selesai

## B. Flowchart Program1

![53196983-d970b480-364b-11e9-846a-f738b6116a58](https://user-images.githubusercontent.com/115517181/199748986-d659e93e-1714-454c-8831-50bc95b1254d.png)

# C. Program Untuk Menghitung Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan



### > Urutan Pembuatan Program

1. Ketikan Program *print ('Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan')*
2. Ketikan Program *x=20000000*
3. Ketikan Program *print (" Modal Awal:",x)*
4. Ketikan Program *a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.03x*
5. Ketikan Program *t=[a,b,c,d,e,f,g,h]*
6. Ketikan Program *For i in range (len (t))*
7. Ketikan Program *Print (“laba bulan ke-“,i+1,”sebesar:” ,t[i])*
8. Ketikan Program *u= (a+b+c+d+e+f+g+h)*
9. Ketikan Program *Print (“total laba adalah:”)*

### > Penjelasan Alur Program

1. *print ('Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan')* Untuk Menampilkan kalimat *Jumlah Laba Hasil Investasi          Seorang Pengusaha Selama 8 Bulan*

2. *x=20000000* Dengan pemisalan atau dideklarasikan x adalah 20000000

3. *print (" Modal Awal:",x)* Menampilkan kalimat *Modal Awal : dan data yang berisi di x yaitu 20000000*

4. *a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.03x* Untuk Mendeklarasikan presentase laba tiap bulan dan di kali         dengan x  atau data inputan modal investasi yaitu 20000000

5. *t=[a,b,c,d,e,f,g,h]* untuk menentukan syarat t= yang berisi a,b,c,d,e,f,g,h

6. *For i in range (len (t)) Print (“laba bulan ke-“,i+1,”sebesar:” ,t[i])* untuk perulangan data dengan isi data yaitu tdengan             menampilkan   urutan laba perbulan sesuai range yang di tentukan dengan hasil ke untukan yang di inpput dari data t

7. *u= (a+b+c+d+e+f+g+h) Print (“total laba adalah:”)* u berisi data penjumlahan data angka yang ada didalam kode             a,b,c,d,e,f,g,h yang akan di tampilakan atau dicetak di jumlah laba selama 8 bulan

## D. Hasil

![Screenshot (56)](https://user-images.githubusercontent.com/115517181/199735520-3d99746a-cac6-4835-80f9-a77d5a25c7e9.png)

# sekian dan trimakasih

 
