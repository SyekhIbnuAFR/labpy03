# labpy03

# Latihan1.py

```Python
import random
n=str(input("Masukkan Nama N : "))
for x in range (1,6):
  print("Data Ke : ",x,"=>",random.uniform(0.0,0.5))
print("Selesai")
```

- Penjelasan Algoritma

- Masukkan Nilai N=5.

- Gunakan For Range (Untuk Mengulang Data Dari 1-5).

- Cetak Data Dan Memasukkan (Random.uniform Kurang Kurang Dari 0.5).

- Jika Selesai RUN/jalankan Programnya.

# Output

![latihan1py](https://user-images.githubusercontent.com/46512629/52989718-4e1ed580-3437-11e9-9c2c-8e50d4f1bd04.png)


# Latihan2.py

```Python
max=0
while True:
	a=int(input("Masukkan Bilangan : "))
	if a ==0:
		break
	if a>max:
		max=a
print("Bilangan Terbesar Adalah : ",max)
```

- Penjelasan Algoritma

- Masukkan Max=0

- Gunakan While True (Untuk Perulangan Tak Terbatas. Jika Bilangan Tersebut Bukan Nol, Maka Akan Terus Berulang).

- Gunakan If Jika Masukkan Bilangan Nol Maka Perulangan Akan Berhenti, If Dalam Python Dijalankan Untuk Memeriksa Kondisi Apakah Ini Bernilai Benar Atau Salah.

- Gunakan If Untuk Mencari Nilai Max Atau Bilangan Terbesar, Selanjutnya Jalankan Programya.

# Output

![latihan2py](https://user-images.githubusercontent.com/46512629/53022482-d760f700-348d-11e9-9fc1-fdd5dd0c6fdd.png)


# Program1.py

```python
a = 100000000

for x in range(1,9):
	if(x>=1 and x<=2):
		b = a*0
		print("Laba bulan ke-",x," Sebesar :",b)
	if(x>=3 and x<=4):
		c = a*0.1
		print("Laba bulan ke-",x," Sebesar :",c)
	if(x>=5 and x<=7):
		d = a*0.5
		print("Laba bulan ke-",x," Sebesar :",d)
	if(x==8):
		e = a*0.2
		print("Laba bulan ke-",x," Sebesar :",e)
total = b+b+c+c+d+d+d+e
print("\nTotal laba adalah : ", total)
```

# Penjelasan Algoritma

- Masukkan Nilai a

- Gunakan For untuk Perulangan Dari 1-8, Yang Disebut Counted Loop (Perulangan Yang Terhitung)

- Gunakan If Pertama Untuk Menentukan Laba Bulan Ke-1 Dan Ke-2, Masukkan Variable (b) Kalikan Nilai (a) Dengan Data Bulan 1 Dan 2, Lalu Cetak (x) Dan (b)

- Gunakan If Kedua Untuk Menentukan Laba Bulan Ke-3 Dan Ke-4, Masukkan Variable (b) Kalikan Nilai (a) Dengan Data Bulan 3 Dan 4, Lalu Cetak (x) Dan (c)

= Gunakan If Ketiga Untuk Menentukan Laba Bulan Ke-5 Dan Ke-7, Masukkan Variable (b) Kalikan Nilai (a) Dengan Data Bulan 5 Dan 7, Lalu Cetak (x) Dan (d)

- Gunakan If Keempat Untuk Menentukan Laba Bulan Ke-8, Masukkan Variable (b) Kalikan Nilai (a) Dengan Data Bulan 8, Lalu Cetak (x) Dan (e)

- Selanjutnya Total Keseluruhan Dan Cetak Total

# Output

![program1py](https://user-images.githubusercontent.com/46512629/53023984-ccf42c80-3490-11e9-9fea-d98dea425eeb.png)
