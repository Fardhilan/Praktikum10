# Praktikum10
# Latihan 1
Code :
```
txt = 'Hello World'

# Hitung jumlah karakternya
jumlah_karakter = len(txt)
print(jumlah_karakter)

# Ambil karakter terakhir
karakter_terakhir = txt[-1]
print(karakter_terakhir)

# Ambil karakter index ke-2 sampai index ke-4 (llo)
karakter_2_4 = txt[2:5]
print(karakter_2_4)

# Hilangkan spasi pada text tersebut (HelloWorld)
txt_tanpa_spasi = txt.replace(' ', '')
print(txt_tanpa_spasi)

# Ubah text menjadi huruf besar
txt_huruf_besar = txt.upper()
print(txt_huruf_besar)

# Ubah text menjadi huruf kecil
txt_huruf_kecil = txt.lower()
print(txt_huruf_kecil)

# Ganti karakter H dengan karakter J
txt_ganti_karakter = txt.replace('H', 'J')
print(txt_ganti_karakter)
```
Output 
![image](https://user-images.githubusercontent.com/93815689/208575121-2284cc56-237a-4bc8-8247-16a8a6ace85d.png)
# Latihan 2
Code 
```
umur = 24
txt = 'Hello, nama saya john, dan umur saya adalah {} tahun'
hasil = txt.format(umur)
print(hasil)
```
Output 
![image](https://user-images.githubusercontent.com/93815689/208575537-2400e1c7-6259-4248-9d44-82086f73fb48.png)
