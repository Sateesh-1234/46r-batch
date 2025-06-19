# Formatting tags

Formatting tags are the tags that are used to enhance Visual appearance of the text without using any CSS properties. Formatting tags are inline elements. Below are some of the formatting tags.<br/>

### Bold tag
The ```<b>``` tag is an inline element used to apply bold formatting to a span of text inside a paragraph. It does not have any semantic meaning and just used to show in bold font.<br/>
```
    <p>This is <b>bold text</b>.</p>
    <p>
        <b>Full Stack</b> is the most demandable course.
    </p>
```
<br/>

### Strong tag
The ```<strong>``` tag is an inline element used to apply bold formatting to a span of text inside a paragraph. It has a semantic importance compared to the bold tag.<br/>
```
    <p>
        Other times we need to <strong>strong</strong>ly emphasize the importance of a word or phrase. We use strong tags.
    </p>
```
<br/>

### Italic tag
The ```<i>``` tag is an inline element used to apply italic formatting to the span of text of a paragraph. It visually slants the enclosed text. It does not have any semantic meaning and just used to show in italic font.<br/>
```
<p>This is <i>italicized text</i>.</p>

<p>
<i>Full Stack</i> is the most demandable course.
</p>
```
<br/>

### Emphasis tag
The ```<em>``` tag is an inline element used to apply italic formatting to a span of text inside a paragraph. It has a semantic importance compared to the italic tag.<br/>
```
    <p>
      <em>Sometimes</em>, you need to draw attention to a particular word or phrase.
    </p>
```
<br/>

### Small tag
The ```<small>``` tag is used to decrease the font size of the enclosed text. It makes the text appear smaller.<br/>
```
<p>This is <small>small text</small>.</p>
```
<br/>

### Big tag
The ```<big>``` tag is used to increase the font size of the enclosed text. It makes the text appear larger.<br/>

```
<p>This is <big>big text</big>.</p>
```
<br/>

### Underline tag
The ```<u>``` tag is used to apply underline formatting to text. It visually adds an underline to the enclosed text.<br/>
```
<p>This is <u>underlined text</u>.</p>
```
<br/>

### Mark tag
To highlight the text content in an HTML document, we make use of the ```<mark>``` tag. By default, the text is highlighted in the yellow colour.<br/>
```
    <P><mark>Full Stack</mark> is the most demandable course.</P>
```
<br/>

### Subscript tag
The ```<sub>``` tag is used to format text or characters as subscript, appearing below the regular baseline. It reduces the font size and positions the text slightly lower. They are commonly used for chemical formulas, log equations, and other purposes where smaller text is required.<br/>
```
<p>log<sub>10</sub>MN = log<sub>10</sub>M  + log<sub>10</sub>N</p>
<p>H<sub>2</sub>O</p>
```
<br/>

### Superscript tag
The ```<sup>``` tag is used to format text or characters as superscript, appearing above the regular baseline. It reduces the font size and positions the text slightly higher. They are commonly used for mathematical equations, and other purposes where raised character is required.<br/>
```
<p>E = mc<sup>2</sup></p>
<p>(a+b)<sup>2</sup> = a<sup>2</sup> + b<sup>2</sup> + 2ab</p>
```
<br/>

### Strike tag
The html ```<strike>``` or ```<s>``` element was deprecated in the 1999 HTML 4.01 standard, and replaced by the ```<del>``` tag, an element representing deleted text, which web browsers often render as a strikethrough.<br/>
```
  <p>Full Stack is <s>not a</s> most demandable course.</p>
  <p>Full Stack is </strike>not a</strike> most demandable course.</p>
```
<br/>

### Delete & Insert tags
The inserted tag is always paired up with the deleted tag. It is generally used for price drop and etc.

```<del>``` tag is used to strike off the text to represent the deleted text.<br/>

The ```<ins>``` element is used to identify text that has been inserted into a document.<br/>

```
  <p>Buy 4 books at <del>Rs. 499</del> <ins>Rs. 199</ins></p>
```
<br/>

### Monospace tag
The text enclosed in ```<tt>``` tags rendered as the monospace font. It will be rendered in particular font & font size. Monospace tag is used to show the text especially like in textbooks, line printers, teletype, etc. It is no longer supported in HTML5. Instead of ```<tt>``` tag we can use ```<code>, <pre>```<br/>

```
<p><tt>Monospaced texted para using tt tag</tt></p>

<code>Monospaced texted para using code tag</code>

<pre>Monospaced texted para using pretag</pre>
```
<br/>