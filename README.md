# HTML Basic Tags

### Basic HTML Format
```html
<!DOCTYPE html>
<html>
  <body>
    Hello world!
  </body>
</html>
```
<!DOCTYPE html>
<html>
  <body>
    Hello world!
  </body>
</html>

### Paragraph (Default)
```html
<p>This is a paragraph</p>
```
<p>This is a paragraph</p>

### Paragraph (with alignment attributes)
```html
<p align="left">Paragraph with left alignment</p>
<p align="center">Paragraph with center alignment</p>
<p align="middle">Paragraph with middle alignment</p>
<p align="right">Paragraph with right alignment</p>
<p align="justify">Paragraph with justified alignment</p>
```
<p align="left">Paragraph with left alignment</p>
<p align="center">Paragraph with center alignment</p>
<p align="middle">Paragraph with middle alignment</p>
<p align="right">Paragraph with right alignment</p>
<p align="justify">Paragraph with justified alignment</p>

### Bold
```html
This text is <b>Bold</b>
```
This text is **Bold**

### Italic
```html
This text is <i>Italic</i>
```
This text is _Italic_

### Underline
```html
This text is <u>Underlined</u>
```
This text is <ins>Underlined</ins>

### Strong
```html
This text is <strong>strong</strong>
```
This text is <strong>strong</strong>

### Emphasize
```html
This text is <em>emphasized</em>
```
This text is <em>emphasized</em>

### Delete
```html
This text is <del>deleted</del>
```
This text is <del>deleted</del>

### Line Break
```html
There are <br>three </br>lines
```
There are <br>three </br>lines

### Horizontal Line
```html
There is a horizontal line under this paragraph. <hr>
There is a horizontal line above this paragraph.
```
There is a horizontal line under this paragraph. <hr>
There is a horizontal line above this paragraph.

### Subscript
```html
Chemical formula of water is H<sub>2</sub>O
```
Chemical formula of water is H<sub>2</sub>O

### Superscript
```html
A mathematical formula is (a + b)<sup>2</sup> = a<sup>2</sup> + 2ab + b<sup>2</sup>
```
A mathematical formula is (a + b)<sup>2</sup> = a<sup>2</sup> + 2ab + b<sup>2</sup>

### Heading
```html
<h1>This is h1 heading</h1>
<h2>This is h2 heading</h2>
<h3>This is h3 heading</h3>
<h4>This is h4 heading</h4>
<h5>This is h5 heading</h5>
<h6>This is h6 heading</h6>
```
<h1>This is h1 heading</h1>
<h2>This is h2 heading</h2>
<h3>This is h3 heading</h3>
<h4>This is h4 heading</h4>
<h5>This is h5 heading</h5>
<h6>This is h6 heading</h6>

### Image (Default)
```html
<img src="waterlilly.jpg">
```
<img src="images/waterlilly.jpg">

### Image (with width and height)
```html
<img src="waterlilly.jpg" width="150" height="100">
```
<img src="images/waterlilly.jpg" width="150" height="100">

### Image (with alternative text, if image is missing)
```html
<img src="waterlilly.jpg" alt="An image of a Waterlily">
```
<img src="waterlillly.jpg" alt="An image of a Waterlily">

### Hyperlink (with website)
```html
Visit <a href="https://www.google.com">Google</a>
```
Visit <a href="https://www.google.com">Google</a>

### Hyperlink (open in a new page or tab)
```html
Visit <a href="https://www.google.com" target="_blank">Google</a> in a new tab.
```
Visit <a href="https://www.google.com" target="_blank">Google</a> in a new tab.
<br><br><i>**Note:** GitHub doesn't support new tab link opening as of now. But HTML editors will work fine.</i>

### Hyperlink (with a file)
```html
Open <a href="basic_html_code.html">Basic HTML</a> file. <br>
Open <a href="horse.jpeg">horse</a> image.
```
Open <a href="basic_html_code.html">Basic HTML</a> file. <br>
Open <a href="images/horse.jpeg">horse</a> image.

### Ordered List (Default)
```html
<ol>
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ol>
```
<ol>
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ol>

### Ordered List (with attribute)
```html
<ol type="A">
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ol>
```
<ol type="A">
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ol>

### Ordered List (Roman Number)
```html
<ol type="i">
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ol>
```
<ol type="i">
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ol>

### Ordered List (start from specific number)
```html
<ol type="1" start="13">
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ol>
```
<ol type="1" start="13">
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ol>

### Unordered List (Default)
```html
<ul>
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ol>
```
<ul>
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ul>

### Unordered List (Circle)
```html
<ul type="circle">
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ol>
```
<ul type="circle">
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ul>

### Unordered List (Square)
```html
<ul type="square">
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ol>
```
<ul type="square">
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ul>

### Unordered List (Disk)
```html
<ul type="disk">
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ol>
```
<ul type="disk">
  <li>Banana</li>
  <li>Apple</li>
  <li>Mango</li>
  <li>Lichi</li>
  <li>Orange</li>
  <li>Guava</li>
</ul>

### Nested Ordered and Unordered List
```html
<ul type="disk">
  <li>Fruits</li>
    <ol type="i">
      <li>Banana</li>
      <li>Apple</li>
      <li>Mango</li>
    </ol>
  <li>Vegetables</li>
  <li>Rice</li>
  <li>Oil</li>
</ul>
```
<ul type="disk">
  <li>Fruits</li>
    <ol type="i">
      <li>Banana</li>
      <li>Apple</li>
      <li>Mango</li>
    </ol>
  <li>Vegetables</li>
  <li>Rice</li>
  <li>Oil</li>
</ul>

### Table (Default)
```html
<table>
  <tr>
    <td>Name</td>
    <td>Roll</td>
  </tr>
  <tr>
    <td>John</td>
    <td>230001</td>
  </tr>
  <tr>
    <td>Cristofer</td>
    <td>230002</td>
  </tr>
</table>
```
<table>
  <tr>
    <td>Name</td>
    <td>Roll</td>
  </tr>
  <tr>
    <td>John</td>
    <td>230001</td>
  </tr>
  <tr>
    <td>Cristofer</td>
    <td>230002</td>
  </tr>
</table>

### Table (with double table border)
```html
<table border="1">
  <tr>
    <th>Name</td>
    <th>Roll</td>
  </tr>
  <tr>
    <td>John</td>
    <td>230001</td>
  </tr>
  <tr>
    <td>Cristofer</td>
    <td>230002</td>
  </tr>
</table>
```
<table border="1">
  <tr>
    <th>Name</td>
    <th>Roll</td>
  </tr>
  <tr>
    <td>John</td>
    <td>230001</td>
  </tr>
  <tr>
    <td>Cristofer</td>
    <td>230002</td>
  </tr>
</table>

### Table (with single table border)
```html
<table border="1" cellspacing="0">
  <tr>
    <th>Name</td>
    <th>Roll</td>
  </tr>
  <tr>
    <td>John</td>
    <td>230001</td>
  </tr>
  <tr>
    <td>Cristofer</td>
    <td>230002</td>
  </tr>
</table>
```
<table border="1" cellspacing="0">
  <tr>
    <th>Name</td>
    <th>Roll</td>
  </tr>
  <tr>
    <td>John</td>
    <td>230001</td>
  </tr>
  <tr>
    <td>Cristofer</td>
    <td>230002</td>
  </tr>
</table>
