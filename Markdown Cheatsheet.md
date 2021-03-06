# Github Flavored Markdown (GFMD) 

### Table of Contents  
[Text Writing and Line Breaks](../master/Markdown%20Cheatsheet.md#text-writing-and-line-breaks)  
[Text Formatting](../master/Markdown%20Cheatsheet.md#text-formatting)  
[Headings](../master/Markdown%20Cheatsheet.md#headings)  
[Horizontal Rules](../master/Markdown%20Cheatsheet.md#horizontal-rules)  
[Hotkeys](../master/Markdown%20Cheatsheet.md#hotkeys)  
[Emojis](../master/Markdown%20Cheatsheet.md#emojis)  
[Coding](../master/Markdown%20Cheatsheet.md#coding)  
[Blockquotes or Quoting](../master/Markdown%20Cheatsheet.md#blockquotes-or-quoting)  
[Hyperlinks](../master/Markdown%20Cheatsheet.md#hyperlinks)  
[Adding Images](../master/Markdown%20Cheatsheet.md#adding-images)  
[Creating lists](../master/Markdown%20Cheatsheet.md#creating-lists)  
[Checkboxes](../master/Markdown%20Cheatsheet.md#checkboxes)  
[Foldable lists](../master/Markdown%20Cheatsheet.md#foldable-lists)  
[Tables](../master/Markdown%20Cheatsheet.md#tables)  
[HTML Tables and Definition lists](../master/Markdown%20Cheatsheet.md#html-tables-and-definition-lists)  


---

## Text Writing and Line Breaks
To specify a paragraph, leave 2 spaces at the end of the line  

---

## Text Formatting
**Bold Text** is done using `**Bold Text**` or `__Bold Text__`  
*Italic Text* is done using `*Italic Text*` or `_Italic Text_`  
**Bold Text and _Italic Text_** is done using both `**Bold Text and _Italic Text_**`  
~~Strikethrough~~ is done with `~~Strikethrough~~`  
***Strong Bold Text*** is done using `***Strong Bold Text***`  

---

## Headings

```
# H1 gets border-bottom automatically
## H2 gets border-bottom automatically
### H3 Hashes can be on both sides ###
#### H4
##### H5
###### H6

Alt-H1 gets border-bottom automatically
======

Alt-H2 gets border-bottom automatically
------

```

will produce:
# H1 gets border-bottom automatically
## H2 gets border-bottom automatically
### H3 Hashes can be on both sides ###
#### H4
##### H5
###### H6

Alt-H1 gets border-bottom automatically
======

Alt-H2 gets border-bottom automatically
------

---

## Horizontal Rules

Horizontal rule is created using `---` or `***` or `___`on a line by itself.

---
Hyphens

***
Asterisks

___
Underscores

Use an empty blockquote for a large rule 

<pre>
```
```
</pre>  

Makes this:  

```
```

---

### Hotkeys  

```
<kbd>⌘F</kbd>
```

<kbd>⌘F</kbd>  
<kbd>⌃F</kbd>  
<kbd>⌥F</kbd>  

Hotkey list:

|Key |Symbol|  
|---|---|
|Option|⌥|  
|Control|⌃|  
|Command|⌘|  
|Shift|⇧|  
|Caps Lock|⇪|  
|Tab|⇥|  
|Esc|⎋|  
|Power|⌽|  
|Return|↩|  
|Delete|⌫|  
|Up|↑|  
|Down|↓|  
|Left|←|  
|Right|→|  

---

### Emojis

:exclamation: Use emoji icons to enhance text. :+1: Look up emoji codes at [emoji-cheat-sheet.com]



---

### Escape sequence  
You can escape using \\ eg. \\\`

```
\`\`\`
```



---

## Coding

Inline `code` has \`back-ticks\` around it.

---
Block code:
<pre>
\```javascript
var s = "JavaScript syntax highlighting";
alert(s);
\```

\```python
s = "Python syntax highlighting"
print s
\```

\```sh
echo hi
\```

\```
No language indicated, so no syntax highlighting.
But let's throw in a < b>tag< /b>.
\```
</pre>

will produce colored code blocks:

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```
```sh
echo hi
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

Note: You can specify the different syntax highlighting based on the coding language eg. ruby, sh (for shell), php, etc  


---

## Blockquotes or Quoting

You can create a quote using `>`:

```
> This is a quote
```

will produce

> This is a quote

```
> Blockquote
>> Nested quote
```

> Blockquote
>> Nested quote


```
> Blockquotes are very handy in email to emulate reply text.
> On the same line or  
> Another line is part of the same quote. Make sure to add in 2 spaces if you want a new line.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.
```

> Blockquotes are very handy in email to emulate reply text.
> On the same line or  
> Another line is part of the same quote. Make sure to add in 2 spaces if you want a new line.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let’s keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can put Markdown into a blockquote.

---

## Hyperlinks

```
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links.
http://www.example.com or &lt;http://www.example.com&gt; and sometimes
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://www.google.com
[link text itself]: http://www.reddit.com 
```

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links.
http://www.example.com or &lt;http://www.example.com&gt; and sometimes
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://www.google.com
[link text itself]: http://www.reddit.com

---

## Adding Images

```
A logo (hover to see the title text):

Inline-style:
![alt text](https://avatars3.githubusercontent.com/u/15163742?v=4&s=40 "Logo Title Text 1")

Reference-style:
![alt text][logo]

[logo]: https://avatars3.githubusercontent.com/u/15163742?v=4&s=40 "Logo Title Text 2"
```

A logo (hover to see the title text):

Inline-style:
![alt text](https://avatars3.githubusercontent.com/u/15163742?v=4&s=40 "Logo Title Text 1")

Reference-style:
![alt text][logo]

[logo]: https://avatars3.githubusercontent.com/u/15163742?v=4&s=40 "Logo Title Text 2"


---

## Creating lists

Adding a `-` or `*` or `+` will change it into a list:

```
- Item 1  
    1. A numbered list
        1. A nested numbered list
        2. Which is numbered
    2. Which is numbered
* Item 2
    * Nested bullet
        * Sub-nested bullet etc
+ Item 3 
```

will produce

- Item 1  
    1. A numbered list
        1. A nested numbered list
        2. Which is numbered
    2. Which is numbered
* Item 2
    * Nested bullet
        * Sub-nested bullet etc
+ Item 3 

---

## Checkboxes

```
 - [ ] An uncompleted task  
 - [x] A completed task  
```

 - [ ] An uncompleted task  
 - [x] A completed task  

---

## Foldable lists

```
<details>
  <summary>Title 1</summary>
  <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
</details>
```

<details>
  <summary>Title 1</summary>
  <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
</details>


## Tables

```
Colons can be used to align columns.

| Tables | Are | Cool |
| ------------- |:-------------:| -----:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```

Colons can be used to align columns.

| Tables | Are | Cool |
| ------------- |:-------------:| -----:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

---

## HTML Tables and Definition lists

```html
<table>
  <tr>
    <th>ID</th><th>Name</th><th>Rank</th>
  </tr>
  <tr>
    <td>1</td><td>Tom Preston-Werner</td><td>Awesome</td>
  </tr>
  <tr>
    <td>2</td><td>Albert Einstein</td><td>Nearly as awesome</td>
  </tr>
</table>

<dl>
    <dt>Definition list</dt>
    <dd>Is something people use sometimes.</dd>
    <dd>Or not.</dd>
    <dt>Markdown in HTML</dt>
    <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
```

will produce

<table>
  <tr>
    <th>ID</th><th>Name</th><th>Rank</th>
  </tr>
  <tr>
    <td>1</td><td>Tom Preston-Werner</td><td>Awesome</td>
  </tr>
  <tr>
    <td>2</td><td>Albert Einstein</td><td>Nearly as awesome</td>
  </tr>
</table>

<dl>
    <dt>Definition list</dt>
    <dd>Is something people use sometimes.</dd>
    <dd>Or not.</dd>
    <dt>Markdown in HTML</dt>
    <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

[Back to the top. ⇧](../master/Markdown%20Cheatsheet.md/#github-flavored-markdown-gfmd)

  
```
```
  

> A huge thank you to adam-p and other sources for sharing your knowledge. Cheers!

Check out more at https://help.github.com/articles/basic-writing-and-formatting-syntax/


[License](../master/LICENSE)
