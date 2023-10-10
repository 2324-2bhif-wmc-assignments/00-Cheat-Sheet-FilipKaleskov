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
* 1.    **Name the components of html elements properly:**
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
    

  
