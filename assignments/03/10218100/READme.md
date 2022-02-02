# assignment 03
Terdapat kode Python berikut ini yang akan digunakan.
```python
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10218100'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char
  print(n, ':', s, sep='')
```

## question 1
Ganti nilai variabel NIM dengan data Anda, jalankan kode yang diberikan, dan tampilkan hasilnya.

### answer 1
Hasil kode di atas adalah
Output:

Traceback (most recent call last):
  File "HelloWorld.py", line 10, in <module>
    s += char
NameError: name 'char' is not defined

compiled on: https://onecompiler.com/python/3xrg64jhh
```
```

## question 2
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char1`, jalankan dan tampilkan hasilnya.

### answer 2
Hasil modifikasi kode di atas adalah
Output:

1:◻
0:
2:◻◻
1:◻
8:◻◻◻◻◻◻◻◻
1:◻
0:
0:

compiled on: https://onecompiler.com/python/3xrg64jhh
```
```

## question 3
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char2`, jalankan dan tampilkan hasilnya.

### answer 3
Hasil modifikasi kode di atas adalah
Output:

1:◼
0:
2:◼◼
1:◼
8:◼◼◼◼◼◼◼◼
1:◼
0:
0:

compiled on: https://onecompiler.com/python/3xrg64jhh
```
```

## question 4
Jelaskan dengan singkat hal yang dihasillkan oleh kode yang diberikan.

### answer 4
Kode di atas berfungsi untuk
+ `s += char1` : mengubah angka menjadi jumlah kotak berwarna putih
+ `s += char2` : mengubah angka menjadi jumlah kotak berwarna hitam
