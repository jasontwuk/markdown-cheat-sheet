# Markdown Cheat Sheet

This is a simple markdown cheat sheet for Github users. Hope you find it helpful. 🙂

||Result|Markdown|
|:---:|:---:|:---:|
|Headings|<h1>Heading L1</h1> <h2>Heading L2</h2> <h3>Heading L3</h3> <h4>Heading L4</h4> <h5>Heading L5</h5> <h6>Heading L6</h6>|`# Heading L1`<br> `## Heading L2`<br> `### Heading L3`<br> `#### Heading L4`<br> `##### Heading L5`<br> `###### Heading L6`<br><br> Note: There is a space between the number signs (#) and the heading name.|
|Font weights and styles|Normal text<br>  **Bold text 1**<br> __Bold text 2__<br> *Italic text 1*<br> _Italic text 2_<br> _combine **bold** and Italic text_<br> ~~strikethrough text~~|`Normal text`<br>  `**Bold text 1**`<br> `__Bold text 2__`<br> `*Italic text 1*`<br> `_Italic text 2_`<br> `_combine **bold** and Italic text_`<br> `~~strikethrough text~~`|
|Paragraphs|<p align="left">This is paragraph one.</p><p align="left">This is paragraph two and I am longer than paragraph one.</p>|<p align="left">This is paragraph one.</p><p align="left">This is paragraph two and I am longer than paragraph one.</p> Note: use `a blank line` to separate paragraphs.|
|Line Breaks|<p align="left">This is line one.</p><p align="left">This is line two and I am longer than line one.<p/>|<p align="left">This is line one.</p><p align="left">This is line two and I am longer than line one.<p/> Note: add `two or more spaces` after a line to create line breaks.|
|Unordered Lists|<h4>Unordered List</h4><ul align="left"><li>item a</li><li>item b</li><li>item c</li></ul><h4>Unordered List with Sub-list</h4><ul align="left"><li>item a</li><li>item b<ul><li>item b1</li><li>item b2</li></ul></li><li>item c</li></ul>|<h4>Unordered List</h4> <div align="left">`* item a`<br> `* item b`<br> `* item c`<br></div> <h4>Unordered List with Sub-list</h4> <div align="left">`* item a`<br> `* item b`<br> <small>&ensp;&ensp;`* item b1`</small><br> <small>&ensp;&ensp;`* item b2`</small><br> `* item c`<br><br> Note:<br> 1. you can use dashes (-) or plus signs (+) to replace asterisks (*) to create the same result.<br> 2. add `two or more spaces` before an item to create sub-list items.</div>|
|Ordered Lists|<h4>Ordered List</h4><ol align="left"><li>First item</li><li>Second item</li><li>Third item</li></ol> <h4>Ordered List with Sub-list</h4> <ol align="left"><li>first item</li><li>second item<ol><li>item 2a</li><li>item 2b</li></ol></li><li>Third item</li></ol>|<h4>Ordered List</h4> <div align="left">`1. first item`<br> `2. second item`<br> `3. Third item`<br></div> <h4>Unordered List with Sub-list</h4> <div align="left">`1. first item`<br> `1. second item`<br> <small>&ensp;&ensp;&ensp;`1. item 2a`</small><br> <small>&ensp;&ensp;&ensp;`1. item 2a`</small><br> `1. Third item`<br><br> Note:<br> 1. The numbers should start with the number one, but the rest of them don’t have to be in numerical order.<br> 2. add `three or more spaces` before an item to create sub-list items.|
|Checkboxes|![screenshot](https://user-images.githubusercontent.com/13745974/101988936-cbfb4300-3c94-11eb-923c-c4ba49483155.png "checkboxes")<br> ✍️	|`- [ ] item 1`<br>  `- [x] item 2`<br>|




---

[Google](www.google.com)

http://www.github.com/

---

![image](https://images.unsplash.com/photo-1606923025907-13b6d83092ef?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80)

---

|column 1|column 2|column 3|
|:---|:---:|---:|
|row 1a|row 1b|row 1c|

---

This is `console.log();`

--- 

Example code block:
```
console.log();
```
---

Example code block with highlight:
```js
console.log();
```
---

Example code block (before and after change):
```diff
- const data = [];
+ const data = {};
```
---

Quote:
> I have idea 1 that is...

I agree with this.

> I have idea 2...

I do not agree with this.

---

When mention an issue in a pull request...

closes #39707

or

fixes #39708

more description...

---
When you want to mention someone: @username

---
Emoji: 🙂 👋
