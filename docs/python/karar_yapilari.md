---
layout: default
title: Karar Yapıları
parent: Python
nav_order: 4
---

# Karar Yapıları
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Nedir?

Bir koşul durumu oluştuğunda bu koşulun kontrolünü sağlamak amacıyla karar yapıları kullanılır.


## if():

Bir koşulun sağlanıp sağlanmadığını kontrol eder, eğer uygun koşul sağlanıyorsa bir çıktı verir veya değer döndürür. Eğer anlamındadır.

<div class="code-example" markdown="1">
```python
if(2<5):
   print ("2 ,5 'ten küçüktür")
```
</div>

## elif():

Birden fazla koşulun ortaya çıkması durumunda kullanılır. Ard arda if değimi kullanılması programın her birinin tekrar kontrol edilmesini gerektirir fakat elif kullanımında program doğru koşulu bulduğunda durur. 

<div class="code-example" markdown="1">
```python
if(2<5):
   print ("2 ,5 'ten küçüktür")
elif(2>5):
   print("2 , 5'ten büyüktür")
```
</div>

## else:

if ve elif koşullarına uygun olmadığında bu komut kullanılır. Program hiçbir koşula uyum sağlamazsa son uygulanacak işlem olarak belirlenir. Değilse anlamındadır.

<div class="code-example" markdown="1">
```python
if(2<5):
   print ("2 ,5 'ten küçüktür")
elif(2>5):
   print("2 , 5'ten büyüktür")
else:
   print("2 ,5 'e eşittir")
```
</div>