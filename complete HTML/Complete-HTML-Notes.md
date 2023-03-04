This files contain all the important points and thoery related to HTML.

<<=======================>>
(section-1) HTML Introduction:- 


-> HTML stands for Hyper Text Markup Language.
-> HTML Markup language for creating Web pages.
-> HTML describes the basic of Web Page. 
-> HTML tell the browser how to display content. 
-> HTML consists of series of elements.


<---------->
for ex:- A simple HTML document.

<!DOCTYPE html>

<html>
  <head>
    <title></title>
  </head>
  <body>
    <h1></h1>
  </body>
</hmtl>

<---------->

<<======================>>

(Note to learn HTML you need a simple text editor it may be Notepad or TextEdit (for Mac) or VS Code etc...)


<<======================>>


(section-2) HTML Basics:-


-> The <!DOCTYPE> Declaration

The <!DOCTYPE> declaration represents the document type, and helps browsers to display web pages correctly.

It must only appear once, at the top of the page.

ex- <!DOCTYPE html>

-> The <html> element is the root element of an HTML page.



<<======================>>


<<======================>>


(section-3) HTML Element:-


An HTML element is defined by a start tag, some content and an end tag. 

ex:- <tagname>content</tagname>
   
     <h1>Heading 1</h1>

Note: Some HTML elements have no content (like the <br> element). These elements are called empty elements. Empty elements do not have an end tag!.

HTML tags are not case sensitive: <P> means the same as <p>.



<<=====================>>


<<=====================>>

(section-4) HTML Attributes:- 


-> All HTML elements can have attributes
-> Attributes provide additional information about elements
-> Attributes are always specified in the start tag
-> Attributes usually come in name/value pairs like: name="value"

ex:- (i) The href Attribute 

The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:

<a href="https://www.w3schools.com">Visit W3Schools</a>

(ii) The src Attributes

The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:

<img src="img_girl.jpg">

Absolute URL -  Example: src="https://www.w3schools.com/images/img_girl.jpg".

Relative URL - Example: src="/images/img_girl.jpg".


(iii) The width and height Attributes:- 

The <img> tag should also contain the width and height attributes, which specify the width and height of the image (in pixels):

<img src="img_girl.jpg" width="500" height="600">


(iv) The alt Attribute:- 

The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed.

<img src="img_girl.jpg" alt="Girl with a jacket">

(v) The style Attribute:- 

The style attribute is used to add styles to an element, such as color, font, size, and more.

<p style="color:red;">This is a red paragraph.</p>


<<====================>>


<<====================>>


(section-5) HTML Headings:- 


HTML headings are titles or subtitles that you want to display on a webpage.


HTML headings are defined with the <h1> to <h6> tags.

<h1> defines the most important heading. <h6> defines the least important heading.

ex:- 
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>



<<====================>>


<<====================>>


(section-6) HTML Paragraphs:- 


A paragraph always starts on a new line, and is usually a block of text.

The HTML <p> element defines a paragraph.

A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.

ex:- <p>This is a paragraph.</p>
     <p>This is another paragraph.</p>


----> HTML Horizontal Rules

The <hr> tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.

----> HTML Line Breaks

The HTML <br> element defines a line break.

---->  The HTML <pre> Element

The HTML <pre> element defines preformatted text.

The text inside a <pre> element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks:





Tag	    Description
<p>	    Defines a paragraph
<hr>	Defines a thematic change in the content
<br>	Inserts a single line break
<pre>	Defines pre-formatted text


<<====================>>



<<====================>>






<<====================>>