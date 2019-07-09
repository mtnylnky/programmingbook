---
layout: default
title: Başlangıç
parent: Python
nav_order: 1
---

# Başlangıç
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Python ?

Nesne yönelimli, yorumsal, modüler, etkileşimli ve yüksek seviyeli bir programlama dilidir. Az kod yazarak daha fazla işlem yapmanıza olanak sağlar. Bu dili tasarlayan Guido van Rossom 'dur.

## Kurulum

Linux kurulumu için aşağıdaki işlemlerinden sisteminize uygun olanını deneyiniz.

[Windows](https://www.python.org/downloads/){: .btn }
[MacOs](https://www.python.org/downloads/mac-osx/){: .btn }

<div class="code-example" markdown="1">
```bash
#Linux için aşağıdaki komutları deneyiniz
#Ubuntu
sudo apt-get install python
#Fedora
sudo dnf install python3
#Arch
pacman -S python
```
</div>

## Kontrol

Python' un sisteminize kurulup kurulmadığını test etmek için aşağıdaki komutu deneyebilirsiniz.

```bash
python --version
#Bu komut ile version kontrolü de yapmış olursunuz.
```

## Merhaba Dünya

Python programlama dilinde ilk çıktımızı almak için aşağıdaki komutu kullanabiliriz.

<div class="code-example" markdown="1">
```python
#print() komutu bir veriyi ekrana yazdırmak istediğimiz zaman kullanabileceğimiz bir komuttur.
print ("Merhaba Dünya")
```
</div>