# labpy03

(latihan 1)
``` python
import random

n= input("masukan nilai N: 5")

for x in range (1,6):

 print("data ke:",x,"=>",random.uniform(0.0,0.5))  
 ```
 Pengacakan, pembangkit bilangan acak, atau random dapat digunakan untuk berbagai macam hal. Salah satunya adalah untuk memecahkan kasus Monte Carlo. Nilai random kadang dibutuhkan juga untuk menentukan suatu pilihan. Atau digunakan juga untuk membuat id yang ditambahi dari string asal. Randomisasi juga dapat digunakan untuk mengacak suatu tampilan produk, atau digunakan saat proses pelatihan sebuah mesin cerdas.
 
![screenshot 36](https://user-images.githubusercontent.com/46513142/52929534-616a6c00-3377-11e9-9ba9-6b595814625f.png)

 
(latihan 2)
```python
 max=0
 
while True:

    a=int(input("masukan bilangan:"))
    
    if a ==0:
    
        break
        
    if a>max:
    
        max=a
        
print("bilangan terbesar:",max)
```

Melakukan perulangan dengan while, kemudian menambah satu variabel hitung setiap kali mengulang. lalu menanyakan kepada pengguna, apakah mau berhenti mengulang atau tidak?

![screenshot 38](https://user-images.githubusercontent.com/46513142/52929736-3af90080-3378-11e9-91ae-309594590eb0.png)




(latihan 3)
```python

for x in range(1,9):

    if(x>=1 and x<=2):
    
        b = a*0
        
        print("Laba Bulan ke-",x," :",b)
        
    if(x>=3 and x<=4):
    
        b = a*1
        
        print("Laba Bulan ke-",x," :",c)
        
    if(x>=1 and x<=7):
    
        b = a*5
        
        print("Laba Bulan ke-",x," :",d)
        
    if(x==8):
    
        e=a*0.2
        
        print("Laba Bulan ke-",x," :",e)
        
total = b+b+c+c+d+d+d+e

print("\ntotal : ", total)
```
Fungsi range() sering digunakan sebagai counter pada perulangan for. Counter adalah sebuah variabel yang menyimpan hitungan—berapa kali mengulang—perulangan. 

![screenshot 37](https://user-images.githubusercontent.com/46513142/52929633-cb831100-3377-11e9-8d87-ccada83d07d7.png)
