### IF.03.01 Basic Web Techniques
# Reading Assignment 1: WWW and html

## Html
1. Name the components of html elements properly
2. Identify void elements and how they are denoted
3. Identify attributes
4. Write down the correct ``DOCTYPE`` declaration for html 5
4. Write down syntactically correct statements for the following elements
   - Article (``<article>``)
   - Body (``<body>``)
   - line break (``<br/>``)
   - Headings (``<h1>``, ...)
   - Section with meta-information (``<head>``)
   - Top level element (``<html>``)
   - Image named ``Team.jpg`` (``<img src="Team.jpg">``)
   - Paragraph (``<p>``)
   - Section (``<section>``)
   - Label appearing in the title bar (``<title>``)
   - Link to other pages (``<a>``)
   - Comment
   - Head with title and meta elements

## Css
1. Name the components of a css rule properly
2. Use combinators properly: direct child, descendant, adjacent sibling, sibling
3. Specify colors by color names and in hexadecimal notation
4. Declarations for color, background color
5. Pseudo classes for the ``<a>`` element
6. Declaration for background image
7. Declaration for text alignment (left, right, center, justify)
8. Declaration for text decoration (overline, underline, line-through)
9. Declaration for text transformation (uppercase, lowercase, capitalize)
9. Identify the difference between serif and sans-serif fonts
10. Declarations for font families
11. Declarations for font style normal and italic
12. Declarations for font sizes
13. Declarations for font weights

## Answers
### HTML
* 1.**Name the components of html elements properly:**
   <br>
  First of all every HTML Document starts with the &lt;!DOCTYPE html&gt; declaration which declares the version of an HTML document.
  <br>
  The &lt;html&gt; is the opening tag of the HTML document and marks the beginning and the end of the HTML content.
  <br>
  The &lt;html&gt; consists of the &lt;head&gt; element which contains metadata about the document, such as the document's title, character encoding, linked stylesheets, and scripts.
  The &lt;body&gt; element is also a part of the &lt;html&gt; element which is responsible for the visible content of the web page, including text, images, links, and other elements that are displayed in the web browser.
* 2.**Identify void elements and how they are denoted:**
   <br>
  A void element is an element in HTML that doesn't have a closing tag.
  <br>
  It is marked up by a start tag only. Void elements are used to represent elements that have no content.
  <br>
  Some examples for void elements would be:
   * &lt;br&gt;
   * &lt;area&gt;
   * &lt;link&gt;
   * &lt;img&gt;
  <br> <br>
   
* 3.**Identify attributes**

  * All HTML elements can have attributes.
  <br>
  * Attributes provide additional information about elements, and they are always specified in the start tag.
  <br>
  * Attributes usually come in name/value pairs like: name="value", for example the href attribute:
  &lt;a href="index.html">Cheat sheet&lt;/  a&gt;
* 4.**Write down the correct DOCTYPE declaration for html 5**
    * The correct DOCTYPE declaration for HTML5 is:
      <br>
      &lt;!DOCTYPE html&gt;
* 5.**Write down syntactically correct statements for the following elements**
    * Article (``<article>``) :
    ```html
    <article>
        <h1>This is a header<h1>
        <p>
            Paragraph one
        <p>
    </article>
    ```
    * Body (``<body>``) : 
    ```html
    <body>
        <article>
        
        </article>
    </body>
    ```
    * line break (``<br/>``) :
    ```html
    <p>
        Some text here
        <br>
        Some other text here
    <p>
    ```
  
    * Headings (``<h1>``, ...) :
    ```html
    <section>
        <h1>Title</h1>
    <section>
    ```
  
    * Section with meta-information (``<head>``) :
    ```html
    <head>
        ...
    </head>
    ```
  
    * Top level element (``<html>``) :
    ```html
    <html>
        <head>
            ...
        <head>
  
        <body>
            ...
        <body>
    <html>
    ```
    
    * Image named ``Team.jpg`` (``<img src="Team.jpg">``) :
    ```html
    <p>
        <img src="Team.jpg" alt="Picture">
    </p>
    ```
  
    * Paragraph (``<p>``) :
    ```html
    <article>
       <p>First Par<p> 
    <article>
    ```

  * Section (``<section>``)
  ```html
  <body>
    <article>
        <section>
            ...
        <section>
    <article>
  <body>
  ```

    * Label appearing in the title bar (``<title>``)
    ```html
    <head>
        <meta charset="UTF-8">
        <title>Title</title>
    </head>
    ```
  
    * Link to other pages (``<a>``) :
    ```html
    <p>
       <a href="cheatsheet.html">Cheatsheet</a>
    </p>
    ```
    * Comment :
    ```html
    <p>
       <a href="cheatsheet.html">Cheatsheet</a>
        <!-- This is a comment -->
    </p>    
    ```
  * Head with title and meta elements
  ```html
  <head>
        <meta charset="UTF-8">
        <title>Assignment 2</title>
  </head>
  ```
  
### CSS

* 1.**Name the components of a css rule properly**
    * There are 4 components in a css rule.
    * CSS selectors are used to "find" (or select) the HTML elements you want to style.
    * The Declaration Block defines the actual styles that will be applied to the selected element.
    * The property specifies what aspect of the selected element(s) you want to style.
    * The value is the specific setting you want to apply to the property. It determines how the selected element(s) should appear or behave.
* 2.**Use combinators properly: direct child, descendant, adjacent sibling, sibling**
    * ```css
      article section {
       font-weight: 100; 
      }
      
      article > section{
      font-weight: 200;
      }
      
      article + section{
      font-weight: 300;
      }
      
      article ~ section {
      font-weight: 400;
      }
      ```
    
* 3.**Specify colors by color names and in hexadecimal notation**
  * With CSS, a color is most often specified by:    
    - a valid color name - like "red"
    <br>
    - a HEX value - like "#808080"

* 4.**Declarations for color, background color**
    * ```css
      body {
      color: green;
      background-color: lightblue;
      }
      ```
* 5.**Pseudo classes for the &lt;a&gt; element**
    * This would be an example for a pseudo class: 
      ```css
      a:link {  
      color: blue;
      text-decoration: none;
      }
      ```  
* 6.**Declaration for background image**
    * ```css
      body {
        background-image: url("image.jpg");
      }
      ```
* 7.**Declaration for text alignment (left, right, center, justify)**
    * ```css
      
      h1 {
      text-align: center;
      }

      h2 {
      text-align: left;
      }

      h3 {
      text-align: right;
      }
      ```
* 8.**Declaration for text decoration (overline, underline, line-through)**
    * ```css
      text-decoration-line
      text-decoration-color
      text-decoration-style
      text-decoration-thickness
      text-decoration
      ```
* 9.**Declaration for text transformation (uppercase, lowercase, capitalize)**
    * ```css
      p.uppercase {
      text-transform: uppercase;
      }

      p.lowercase {
      text-transform: lowercase;
      }

      p.capitalize {
      text-transform: capitalize;
      }
      ```
* 10.**Identify the difference between serif and sans-serif fonts**
    * Serif fonts have a small stroke at the edges of each letter. They create a sense of formality and elegance.
      Sans-serif fonts have clean lines (no small strokes attached). They create a modern and minimalistic look.
* 11.**Declarations for font families**
    * ```css
      .p1{
        font-family: "Times New Roman", Times, serif;
      }
      
      .p2{
        font-family: Arial, Helvetica, sans-serif;
      }
      
      .p3{
        font-family: "Lucida Console", "Courier New", monospace;
      }
      ```
* 12.**Declarations for font style normal and italic**
    * ```css
      p {
      font-style: normal;
      }
      
      em {
      font-style: italic;
      }
      ```
* 13.**Declarations for font sizes**
    * ```css
      p {
      font-size: 16px;
      }
      ```
* 14.**Declarations for font weights**
    * ```css
      p {
      font-weight: 100;
      }
      ```