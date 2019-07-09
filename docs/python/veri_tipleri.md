---
layout: default
title: Veri Tipleri
parent: Python
nav_order: 2
---

# Veri Tipleri
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Python Veri Tipleri

Python üzerinde programlama yaparken diğer dillerde olduğu gibi değişkeni tanımlarken veri tipini belirlemenize gerek yoktur. Python sizin yerinize bunu kendisi halleder.

## Veri Tipleri

* int: Tam sayıları ifade eder.
* long: Uzun tam sayıları ifade eder.
* float: Ondalıklı gerçek sayıları ifade eder.
* str: Harf, rakam, özel karakterleri ifade eder.
* bool: True, False gibi değerleri döndürür.
* list: Birden fazla tipi barındıran bir dizeyi ifade eder.
* dict: Sözlük işlevine sahip listeler oluşturmanızı sağlar.

Python yukardaki veri tiplerini ve daha fazlasına destek sağlamaktadır. Eğer farklı bir veri tipine ihtiyaç duyuyorsanız [tıklayınız...](https://www.tutorialspoint.com/python/python_variable_types.htm)

## Tip Dönüşümleri

Tip dönüşümü tanımladığınız değişkenin veri tipinin yetersiz kalması durumunda kullanacağınız bir yöntemdir.

<div class="code-example" markdown="1">
```python
5/4 #Python bu işlemin çıktısını float olarak '1.25' verir
int(5/4) #Bu yöntem ile size tam sayı halini verir yani '1' değerini alırsınız
str(5/4) #İşlem sonucunu string bir ifade olarak '1.25' verir
```
</div>

## type() Fonksiyonu

Tanımladığımız değişkenin tipini verir.

<div class="code-example" markdown="1">
```python
degisken="Merhaba" #Değişkenimizi tanımladık
type(degisken) #Veri tipini öğrenmek için fonskiyon içerisinde değişkeni çağırdık
```

```bash
#Çıktısı
<class 'str'>
```
</div>