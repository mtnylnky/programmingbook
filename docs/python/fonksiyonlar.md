---
layout: default
title: Fonksiyonlar
parent: Python
nav_order: 7
---

# Fonksiyonlar
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Nedir?

Karmaşık birden fazla işlemi bir araya toplayarak, bu işlemleri tekrarlamadan tek adımda yapmanızı sağlamaktır. Örneğin; matematiksel bir işlemi her gereken yerde yeniden yazmak hem yazılımcıya zorluk verecek hem de programa fazladan işlemi birden fazla kez yaptıracaktır. Bunun yerine fonksiyon bir sefer yazılır ve gereken her yerde çağırılır.


## Fonksiyon Oluşturma

Bir fonksiyon oluşturmak için önce `def` komutunu kullanmalısınız. Ardından fonksiyon adınızı yazabilirsiniz. Örnek: `def toplama()` bir fonksiyon örneğidir.

<div class="code-example" markdown="1">
```python
#Burada fonksiyona verilen değerin üssünü alıp sonucu döndürüyoruz
def fonksiyon_adi(deger):
  return deger**2
```
</div>

## Code blocks with rendered examples

To demonstrate front end code, sometimes it's useful to show a rendered example of that code. After including the styles from your project that you'll need to show the rendering, you can use a `<div>` with the `code-example` class, followed by the code block syntax. If you want to render your output with Markdown instead of HTML, use the `markdown="1"` attribute to tell Jekyll that the code you are rendering will be in Markdown format... This is about to get meta...

