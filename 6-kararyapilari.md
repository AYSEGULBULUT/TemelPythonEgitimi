# Karar Yapilari
[Geri](5-karsilastirmaislemleri.md)
#### If
```python
if kosul
    kod

if True:
    print('Dogru')


ad = input('Adiniz nedir ? ')
yas_str = input(f'Yasin kac {ad} ')
print(f'Merhaba {ad}, {yas_str} yasindasin.')

yas = int(yas_str)

if yas > 17:
    print(f'Merhaba {ad}, resitsin, kulube hosgeldin.')

if yas < 18:
    print(f'Merhaba {ad}, resit degilsin, kulube giris yapamazsin.')

```

#### If / Else
```python
if kosul
    kod
else
    diger kod


if True == False:
    print('if block')
else:
    print('else block')

ad = input('Adiniz nedir ? ')
yas_str = input(f'Yasin kac {ad} ')
print(f'Merhaba {ad}, {yas_str} yasindasin.')

yas = int(yas_str)

if yas > 17:
    print(f'Merhaba {ad}, resitsin, kulube hosgeldin.')
else:
    print(f'Merhaba {ad}, resit degilsin, kulube giris yapamazsin.')

```

#### If / Elif / Else
```python
if kosul
    kod
elif diger_kosul
    diger kod
else
    baska bir kod

if True == False:
    print('if block')
elif True > False:
    print('elif block')
else:
    print('else block')


ad = input('Adiniz nedir ? ')
yas_str = input(f'Yasin kac {ad} ')
print(f'Merhaba {ad}, {yas_str} yasindasin.')

yas = int(yas_str)

if yas >= 65:
    print(f'Merhaba {ad}, resitsin ama evinde otur sokaga cikma yasagin var.')
elif yas > 17:
    print(f'Merhaba {ad}, resitsin, kulube hosgeldin.')
else:
    print(f'Merhaba {ad}, resit degilsin, kulube giris yapamazsin.')
```


```python
sayi = 50
print("1-100 arasinda bir sayi tahmin et: ")
tahmin = int(input())

if sayi < tahmin:
    print('Daha buyuk bir sayi tahmin et')
elif sayi > tahmin:
    print('Daha kucuk bir sayi tahmin et')
else:
    print('Evet! Dogru tahmin')
```
[Donguler](7-donguler.md)