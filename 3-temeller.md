# Python Temeller
[Geri](2-vscode.md)
## Print
```python
# yorum
print('Hello IZU')
```

## Veri Tipleri

| Ornek | Veri Tipi
|-------|----------
|`x = "Merhaba IZU"`|String|
|`x = 20` | Integer
|`x = 20.5` | Float
|`x = True , x = False` | Boolean
|`x = ['elma', 'armut']`| List (Mutable)
|`x = ('elma', 'armut')`| Tuple (Immutable)
|`x = {'adi': 'Nikita', ]'soyadi': 'Turkmen'}`| Dict
|`x = {'elma', 'armut'}`| Set (Unique)

### Veri Tipleri Ile İşlemler 
* Ozel fonksiyonlar
#### String Islemleri
```python
# f(x) - g(f(x))
ad = 'Nikita'
soyad = 'TURKMEN'
adsoyad = 'Nikita TURKMEN'

print(type(adsoyad)) # type

print(adsoyad)

print(len(adsoyad)) # length

print(adsoyad[0]) # slicing
print(adsoyad[2:])
print(adsoyad[:3])
print(adsoyad[2:4])
print(adsoyad[::2])
print(f'Ad: {ad}, Soyad:{soyad}') # formatting
```
#### Integer
```python
# f(x) - g(f(x))
# integer islemleri
x = 5
print(type(x))

y = 10

z = x + y

print(z)
```

#### Float
```python
x = 20.5
print(x)
```
#### Boolean
```python
x = True
print(x)
```

#### List
```python
# mutable
l = ['elma', 'armut']
print(x[0])
l2 = ['domates', 'salatalik']
l3 = l1 + l2
print(l3)
l2[0] = 'patates'
l2.append('sogan') # eleman ekleme.
l2.pop() # son elemani cikartir.
l2.pop(0)
num_list = [3,10,1,8,9]
num_list.sort()
num_list.reverse()
```

#### Tuple
```python
# immutable
t = ('elma','armut')
print(type(t))
print(len(t))
print(x[0])
```

#### Dictionaries
```python
d = {
    'key1': 'value1',
    'key2': 'value2'
}
print(d['key1'])
d.keys()
d.values()
```