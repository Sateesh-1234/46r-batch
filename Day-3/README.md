# Block Level Elements Vs Inline Level Elements

### What are Block Level Elements?
Block-level elements are always rendered on a new line one after another and covers the full width available from left to right as far as it can and the browsers automatically add some space (a margin) before and after the element.<br/>The ```<div>``` element is the standard  block-level element, and it is often used as a container for other HTML elements. <br>Examples: ```<div>, <h1> to <h6> , <p>  <hr>, <pre>```
```
  <div>
      <p>Welcome to FrontEnd</p>
      <p>Welcome to FrontEnd</p>
      <p>Welcome to FrontEnd</p>
  </div>
```
<br/>
![Screenshot of the difference b/w Block, and Inline elements](https://media.gcflearnfree.org/content/5e82363212da9215e057b928_03_30_2020/block_vs_inline_diagram.png)

<br/>

### What arte the Inline Level Elements?
Inline elements are the elements that start from the point where the previous element has ended. It takes only the space for its content.<br/>The <span> element is an inline element; it is often used as a container for some text.<br/>
EX: ```span, br, a, img```
```
  <span>Some plain text <span id="inner">with inline text </span>included</span>
```
