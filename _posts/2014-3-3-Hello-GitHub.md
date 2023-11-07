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

表格用「| 」、「 ↲」區分欄、列

|標題1|標題2|標題3|標題4|
|----|----|----|----|
|欄位1|欄位2|欄位3|欄位4|
|欄位5|欄位6|欄位7|欄位8|

.

*前後一個「 * 」是斜體*

**前後兩個「*」是粗體**

***前後三個「 * 」是粗體+斜體***

~~前後兩個「~」是刪除線~~

.

超連結是：用「[ ]」將文字包著，然後在後面加上「( )」，並在括號內輸入網址
圖片插入方式是超連結的語法，並在「[ ]」前面加上「!」

回到我的[GitHub](https://hungsiu.github.io/)

.

>前面一個「>」是縮排一個Tab
>>前面兩個「>」是縮排兩個Tab
>>>依此類推

.

# Git指令

* 列出各種git指令

>➜ git --help：顯示Git指令說明

>➜ git log：檢視git的版本管理內容

>➜ git init：git初始化，並將當前路徑納入版本管理

>➜ git status：顯示目前版本管理的狀態

>➜ git add filename.type：將檔案加入到變更項目，等待Commit

>➜ git commit -m Description：建立Commit，更新版本

>➜ git branch "branchName"：建立新分支(branchName為分支名稱)

>➜ git checkout "branchName"：切換分支(branchName為分支名稱)

>➜ git branch -d "branchName"：刪除分支(branchName為分支名稱)

>➜ git branch -D "branchName"：強制刪除分支(branchName為分支名稱)

>➜ git merge "branchName"：合併到當前分支(branchName為分支名稱)

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

# 建立新頁面方式

以新增一個名為「NewWebsite」的Repository為例

    1.在_posts資料夾內複製一個任意一個.md檔，並將檔名修改為2022-08-18-NewWebsite.md
    2.在2022-08-18-NewWebsite.md中可以更改title、新增預覽說明等
    3.在GitHub新增repository，Repository Name是NewWebsite
    4.點進Repository後，找到Settings > Pages > Theme Chooses
    5.按下Change theme按鈕，選擇一個喜歡的主題
    6.按下Selet theme按鈕更換為新的主題
    7.到個人頁面首頁查看是否新增成功

阿要注意自己的帳號名稱蛤，不要改了帳號名稱自己又忘了
