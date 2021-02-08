---
layout: post
title: Hello GitHub!
---

第一次使用GitHub x Markdown

.

# 這是一個「#」的標題

## 這是兩個「#」的標題

### 這是三個「#」的標題

.

前面加上「* 」或「- 」是清單
* Red
* Green
* Blue

單獨一行打上「--- 」是新章節

---

.

*前後一個「 * 」是斜體*

**前後兩個「*」是粗體**

***前後三個「 * 」是粗體+斜體***

~~前後兩個「~」是刪除線~~

.

超連結是：用「[ ]」將文字包著，然後在後面加上「( )」，並在括號內輸入網址
圖片插入方式是超連結的語法，並在「[ ]」前面加上「!」

回到我的[GitHub](https://hunghsiuwang.github.io/)

.

>前面一個「>」是縮排一個Tab
>>前面兩個「>」是縮排兩個Tab
>>>依此類推

.

# Git指令

* 列出各種git指令

>➜ git --help



.

# 插入程式碼

* C#

```cs
using System;

namespace ConsoleApp
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello GitHub~");
        }
    }
}


```

* C

```c
#include<stdio.h>

int main()
{
    printf("Hello GitHub~\n");

    return 0;
}

```

* Python

```py

print "Hello GitHub~"

```

* PHP

```php
<?php
    echo "Hello GitHub~"
?>

```
