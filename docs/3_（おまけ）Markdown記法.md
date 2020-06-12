# 3_（おまけ）Markdown記法

## h(tag), list, 
# h1
## h2
### h3
#### h4

* list
+ list
- list

1. list
2. list
3. list
```
# h1
## h2
### h3
#### h4

* list
+ list
- list

1. list
2. list
3. list
```
## code block, escape
```
code
```

\# escape

`inline`

\```

code

\```

\# escape

\`inline`

## Link
[yahoo](https://www.yahoo.co.jp)
![LGTM](https://cdn.lgtmoon.dev/images/74051)
```
[yahoo](https://www.yahoo.co.jp)
![LGTM](https://cdn.lgtmoon.dev/images/74051)
```
## 引用, italic, bold, 打ち消し
> hoge
>> hoge
>>> hoge

_italic_
*italic*

__blod__
**bold**

~~打ち消し~~

```
> hoge
>> hoge
>>> hoge

_italic_
*italic*

__blod__
**bold**

~~打ち消し~~
```

## horizon
***
* * *
---
- - - 

```
***
* * *
---
- - - 
```

## table
|left|center|right|
|:--|:---:|--:|
|leftttttt|centerrrrrr|righttttttt|

```
|left|center|right|
|:--|:---:|--:|
|leftttttt|centerrrrrr|righttttttt|
```

## checkbox(Vuepressでは使用できないっぽい。)
- [] ch1
- [x] ch1

```
- [] ch1
- [x] ch1
```

## VSCode md preview：
Ctrl + Shift + V

## このファイルをMarkdownで見たい
${link} + .md

ex)
http://localhost:8080/start.html.md

## 数式(Vuepressでは別途plugin必要。)
```math
y=mc^2
```

## 絵文字
:large_blue_diamond:
```
:large_blue_diamond:
```
(EMOJI CHEAT SHEET)[https://www.webfx.com/tools/emoji-cheat-sheet/]