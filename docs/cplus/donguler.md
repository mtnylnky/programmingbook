---
layout: default
title: Döngüler
parent: C++
nav_order: 5
---

# Döngüler
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## While Döngüsü

<div class="code-example" markdown="1">
```c++
#include <iostream>
using namespace std;
int main () {
   // Local variable declaration:
   int a = 10;
   // while loop execution
   while( a < 20 ) {
      cout << "A degeri: " << a << endl;
      a++;
   }
   return 0;
}
```
</div>
---

## Do While Döngüsü

<div class="code-example" markdown="1">
```c++
#include <iostream>
using namespace std;
int main () {
   // Local variable declaration:
   int a = 10;
   // do loop execution
   do {
      cout << "A degeri: " << a << endl;
      a = a + 1;
   } while( a < 20 );
   return 0;
}
```
</div>

## For Döngüsü

<div class="code-example" markdown="1">
```c++
#include <iostream>
using namespace std;
int main () {
   // for loop execution
   for( int a = 10; a < 20; a = a + 1 ) {
      cout << "value of a: " << a << endl;
   }
   return 0;
}
```
</div>