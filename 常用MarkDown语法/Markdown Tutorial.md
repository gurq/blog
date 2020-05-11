### Markdown Tutorial



> ==:warning::warning::warning:This page is written by a Chinese programmer, please forgive me for my poor English. It's very grateful if you are willing to point out my mistakes, whether grammar mistakes or the improper expression in my article, thanks a lot.:warning::warning::warning:==



> :bulb:Before we use Markdown，we should learn some basic and the most commonly used grammar

### 1. Headers

* Use `#` to show headers, the first level header uses one `#` , the second level header uses two `##` , and so on. There are six levels of headers. There also should have a space between `#` and header

  # first header

  ## second header

  ### third header

  #### fourth header

  ##### fifth header

  ###### sixth header

  ```
    # first header
    
    ## second header
    
    ### third header
    
    #### fourth header
    
    ##### fifth header
    
    ###### sixth header
  ```

### 2. Quotes

Use `>` to show quotes,  `>>` is used to show the second level quote in the first quote

1.  if you use both `>` and `>>` , when you want to use the first level out of the second level, you should input a new empty line, if not, it will also be the second quote
2.  You can use many other symbol in quote, like emphasis 

> :exclamation: Some editors do not support multiple levels of quotes, it is recommended not to use

demo:

> first quote
> > second quote
> >
> > > third quote

> first quote

```
> first quote
> > second quote
> >
> > > third quote

> first quote
```

### 3. Code blocks

Use ` ``` ` to show code blocks. You can declare code language to make code blocks highlighting

demo:

```javascript
$(document).ready(function() {
  $('pre code').each(function(i, block) {
    hljs.highlightBlock(block);
  });
});
```

```
​```javascript
$(document).ready(function() {
  $('pre code').each(function(i, block) {
    hljs.highlightBlock(block);
  });
});
​```
```

### 4. Inline codes

Use `` to show inline codes

demo:

this is `javascript` code

```  
this is `javascript` code
```

### 5. Links

Use `[](link)` to show links

*   The words in `[]` are what you want to show
*   `link` is the url where you want to link

demo:

I think [xu.ci](https://xu.ci) is a really good blog :kissing_heart:.

```
I think [xu.ci](https://xu.ci) is a really good blog :kissing_heart:.
```

### 6. Math formulas

> :exclamation: The grammar of formula supported by some editors is not the same, here is Typora as an example

Use `$$` to show math formulas

demo:
$$
\sum_{n=1}^{100}{a_n}
$$

```
$$
\sum_{n=1}^{100}{a_n}
$$
```

### 7. Images

Use `![Alt text](/path/to/img.jpg)` to show images

*   `Alt text` is the text displayed if the image cannot be displayed 
*   `/path/to/img.jpg` is the image's url

demo:

![Markdown](https://i.loli.net/2020/03/14/I8wCZN4r9UltqTd.jpg)

```
![Markdown](https://i.loli.net/2020/03/14/I8wCZN4r9UltqTd.jpg)
```

### 8. Todo Lists

Use `- [ ]` and `- [x]` to show todo lists.

- [x] Todo List
- [ ] Todo list

```
- [x] Todo List
- [ ] Todo list
```

### 9. Bold，italic，highlight和delete line

-  Use `**` or `__` to show **bold**

```
**bold**
```

-  Use `*` or `_` to show *italic*

```
*italic*
```

-  Use `***` to show ***both bold and italic*** 

```
***both bold and italic***
```

-  Use `==` to show ==highlight==

> :exclamation: Some editors do not support highlighting

```
==highlight==
```

-  Use `~~` to show ~~delete line~~

```
~~delete line~~
```

-  There is **no space** between `*`，`=` or `_` 

### 10. Lists

Use `1.` to show ordered lists, use `*` or `-` or `+` to show unordered lists. There should be a space behind it

#### demo 1: ordered lists

1.  first
1.  second
1.  third

```
1.  first
1.  second
1.  third
```

#### demo 2: unordered lists

+ first level unordered list

  - second level unordered list

    - third level unordered list

*  first level unordered list

```
+ first level unordered list

  - second level unordered list
  
    - third level unordered list
    
*  first level unordered list
```

### 11. Dividing lines

Use `---` or`***` or`* * *` to show dividing lines

1.  Should more than three
2.  `---` / `***` / `* * *` should between two empty lines

demo:

---

***

* * *

```

---

***

* * *

```

### 12. Tables

default tables:

Heading | Heading | Heading
------- | ------- | -------
Cell   |  Cell   |  Cell
Cell   |  Cell   |  Cell

```
Heading | Heading | Heading
------- | ------- | -------
Cell   |  Cell   |  Cell
Cell   |  Cell   |  Cell
```

align tables:

Heading | Heading | Heading
:----- | :----: | ------:
Left   | Center | Right
Left   | Center | Right

```
Heading | Heading | Heading
:----- | :----: | ------:
Left   | Center | Right
Left   | Center | Right
```

### 13. emoji

Use `:emoji code:` to show emoji in Markdown

[Click here to see all of emoji codes](https://www.webfx.com/tools/emoji-cheat-sheet/)