# Metodlar ve Fonksiyonlar

## Metodlar

```python
num_list = [1,2,3,4]

num_list.append(5)

print(num_list)
help(num_list.append)
```

https://docs.python.org/3.8/library/

## Fonksiyonlar
```python
#f(x) = 2x + 1
#f(x) = y

def f(x):
    return 2 * x + 1

# parametresiz fonksiyon
def f():
    return 5

# print(yaz(x))
def yaz(x):
    print(x)

f(1) # 2 * 1 + 1 = 3
f(2) # 2 * 2 + 1 = 5

print('Ders bitmek uzere.')
yaz('Ders bitmek uzere.')
```

```python
# moduller, kutuphaneler
import time

def yas_hesapla(dogum_yili):
    yas = suanki_yil - dogum_yili
    return yas

# simdiki yili bul
suanki_yil = int(time.strftime("%Y"))

# dogum tarihini iste
dogum_tarihi = int(input('Dogum tarihinizi giriniz.'))

yas = yas_hesapla(dogum_tarihi)

print(yas)
```

* varsayilan parametre
