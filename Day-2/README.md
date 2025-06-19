# Some of the basic, and fundamental tags  
  
### What is a Tag?  
A HTML Tag is a piece of markup language which is enclosed between the angular brackets. The tags intimate to the browser that how to format, and display the content.<br/> 
<br/>
The HTML tag consists of 2 parts:  
- Opening tag - A tag without a forward slash.
- Closing tag - A tag with a forward slash.
<br/>
Think of tags as household taps. If you open the tap, it must be closed.<br/>
<br/>
  
### What is Container?
The opening tag along with the closing tag without any content is called a Container.  
EX: ```<tagName></tagName>``` <br/> 
  
### What is Element?
The Opening tag along with the content, and closing tag together is called an Element.  
EX: ```<tagName>Content</tagName>```<br/>  
  
### Types of Tags?
There are two types of tags:  
- Paired tags
- Self-Closing tags<br/>

### What is a Paired tag?
A tag which has an opening tag, and closing tag is called a Paired tag.  
EX: ```<tagName></tagName>```<br/>  
  
### What is Self Closing Tag?
A Tag which has only an opening tag. These tags will not contain any content.  
EX: ```<tagName>```<br/>  
  
### Heading tags
The heading tags, represented by ```<h1>``` to ```<h6>```, are used in HTML to define headings of different levels, where ```<h1>``` represents the highest level of heading and ```<h6>``` the lowest. The Headings are the paired tags.  

```
    <h1>This is the heading level 1</h1>
    <h2>This is the heading level 2</h2>
    <h3>This is the heading level 3</h3>
    <h4>This is the heading level 4</h4>
    <h5>This is the heading level 5</h5>
    <h6>This is the heading level 6</h6>
```
<br/>

### Paragraph tags
The paragraph tag, represented by ```<p>```, is used in HTML to define a paragraph text. It is a paired tag. Avoid using paragraph tags for single words or short phrases.  
  
```
<p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Commodi vitae voluptatibus, eos delectus voluptatum possimus optio dolores at expedita tempore accusantium enim! Voluptatem enim officiis exercitationem incidunt quis ex in.</p>
``` 
<br/> 
  
### Text breaking elements
HTML condenses consecutive spaces, tabs, or newlines, together known as “whitespace” into a single space. In this context, HTML provides text breaking elements as follows:  
- Line break tag
- Preformatted tag
- Horizontal rule
<br/>

### Line break tag
The ```<br>``` tag represents a line break and is used to create a single line break or line shift within a block of text. It is a self closing tag.  
```
<p>This is the first line. <br>This is the second line.</p>
```  
<br/>
  
### Preformatted tag
Preformatted tag is a reference tag. In order to render a reference text exactly as it is with the indentation, Preformatted tag used.  
```
    public class Main{
        public static void main(String[] args){
          System.out.println("Preformatted tag");
        }
      }
    </pre>
```  
<br/>
  
### horizontal rule
The ```<hr>``` tag represents a horizontal rule or line that can be used to create a thematic break, to visually separate the sections of content within a document.  
```
<h1>Section 1</h1>
<p>This is the content of section 1.</p>
<hr>
<h1>Section 2</h1>
<p>This is the content of section 2.</p>
```  
<br/>
  
### Center tag
It aligns the contents to the center of the web page. It was deprecated from the previous versions of HTML. So we use css properties to align the things.  
```  
<center>
    <h1>Center Tag</h1>
</center>
```  
<br/>
  
### Marquee tag
For scrolling purpose like in tv channels.  
```  
<marquee>This is the default one from right to left</marquee>
```  
<br/>

