# Markdown Cheat Sheet

This is a simple markdown cheat sheet for Github users. Hope you find it helpful. 🙂

||<div align="center">Result</div>|<div align="center">Markdown</div>|
|:---:|:---|:---|
|Headings|<h1>Heading L1</h1> <h2>Heading L2</h2> <h3>Heading L3</h3> <h4>Heading L4</h4> <h5>Heading L5</h5> <h6>Heading L6</h6>|`# Heading L1`<br> `## Heading L2`<br> `### Heading L3`<br> `#### Heading L4`<br> `##### Heading L5`<br> `###### Heading L6`<br><br><br> Note: There is a space between the number signs (&num;) and the heading name.|
|Font weights and styles|Normal text<br><br>  **Bold text 1**<br> __Bold text 2__<br><br> *Italic text 1*<br> _Italic text 2_<br><br> _combine **bold** and Italic text_<br><br> ~~strikethrough text~~|`Normal text`<br><br>  `**Bold text 1**`<br> `__Bold text 2__`<br><br> `*Italic text 1*`<br> `_Italic text 2_`<br><br> `_combine **bold** and Italic text_`<br><br> `~~strikethrough text~~`|
|Paragraphs|<p>This is paragraph one.</p><p>This is paragraph two and I am longer than paragraph one.</p>|<p>This is paragraph one.</p><p>This is paragraph two and I am longer than paragraph one.</p><br> Note: Use `a blank line` to separate paragraphs.|
|Line Breaks|<p>This is line one.<br>This is line two and I am longer than line one.<p/>|<p>This is line one.<br>This is line two and I am longer than line one.<p/><br> Note: Add `two or more spaces` after a line to create line breaks.|
|Unordered Lists|<h4>Unordered List</h4><ul><li>Item a</li><li>Item b</li><li>Item c</li></ul><h4>Unordered List with Sub-list</h4><ul><li>Item a</li><li>Item b<ul><li>Item b1</li><li>Item b2</li></ul></li><li>Item c</li></ul>|<h4>Unordered List</h4> `* Item a`<br> `* Item b`<br> `* Item c`<br> <h4>Unordered List with Sub-list</h4> `* Item a`<br> `* Item b`<br> <small>&ensp;&ensp;`* Item b1`</small><br> <small>&ensp;&ensp;`* Item b2`</small><br> `* Item c`<br><br><br> Note:<br> 1. You can use dashes (&minus;) or plus signs (&plus;) to replace asterisks (&ast;) to create the same result.<br> 2. Add `two or more spaces` before an item to create sub-list items.|
|Ordered Lists|<h4>Ordered List</h4><ol><li>First item</li><li>Second item</li><li>Third item</li></ol> <h4>Ordered List with Sub-list</h4> <ol><li>First item</li><li>Second item<ol><li>Item 2a</li><li>Item 2b</li></ol></li><li>Third item</li></ol>|<h4>Ordered List</h4> `1. First item`<br> `2. Second item`<br> `3. Third item`<br> <h4>Unordered List with Sub-list</h4> `1. First item`<br> `1. Second item`<br> <small>&ensp;&ensp;&ensp;`1. Item 2a`</small><br> <small>&ensp;&ensp;&ensp;`1. Item 2a`</small><br> `1. Third item`<br><br><br> Note:<br> 1. The numbers should start with the number one, but the rest of them don’t have to be in numerical order.<br> 2. Add `three or more spaces` before an item to create sub-list items.|
|Checkboxes|![screenshot](https://user-images.githubusercontent.com/13745974/102015478-c6186700-3d53-11eb-9e74-eb1e8f38e0c3.png "checkboxes")<br> ✍️	|`- [ ] Item 1`<br>  `- [x] Item 2`<br>|



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
