# Attributes in HTML

### What is Attribute?
An attribute provides additional information about an HTML element. It modifies the behaviour or appearance of an element and is specified within the start tag of an element.<br/>
Syntax: ```<tagName attributeName="attributeValue"></tagName>```
<br/>

### Types of Attributes
There are 3 types of attributes:<br/>
- Standard Attribute
- Global Attribute
- Custom Attribute
<br/>

### Standard Attributes
The attributes which are applicable for only particular elements are called Standard attributes. <br/>
EX: ```size attribute```
<br/>
```
<hr size="50">
```
<br/>

### Global Attributes
Global attributes are the attributes that are able to be set on all tags. Most commonly used global attributes as follows:<br/>
EX: ```class, id, style, title ```<br/>
```
    <p style="color:red; background-color: black;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, quod fugiat. Enim repellat officia facilis consequatur nobis expedita maxime reprehenderit qui consequuntur illum. Aliquid, aspernatur corrupti assumenda vero cumque deleniti!</p>
```

### custom attributes
Custom attributes used to store additional data associated with an element.<br/>
The ```data-*``` attributes is used to store custom data private to the page or application. It gives us the ability to embed custom data attributes on all HTML elements. Any attribute on an element whose attribute name starts with ```data-``` is a data attribute.<br/>
