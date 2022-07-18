# webdevelopment-notes
undamentals of web development
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The Internet Analogy
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The whole World Wide Web is based on the underlying infrastructure called the Internet.

 

The terms, Internet and World Wide Web, are often used interchangeably in conversation, but they are not the same thing.

 

Picture a city.  It has stores, art galleries, colleges, arcades, coffee shops, movie theaters, libraries, banks, fruit stands, and on and on. This the Web.

There is, however, much more to the city.  There are postal services, telephone systems, radio and television stations, and so on.  These are not the Web, and they are not the Internet either. They use the Internet the same way that the Web does.

The Internet is collectively the highways, alleyways, sidewalks, sewers, power lines, and general infrastructure of the city.

Here is a scenario.  Let’s say you want to send an email from your Gmail address to your friend’s Yahoo address.  You use streets (the Internet) to get to your post office (Gmail website), where you give them a letter for your friend.  Their mail truck departs from the back of the post office (email protocol), travels down the street (Internet) to the back of the Yahoo post office where it delivers the letter for your friend (email protocol).  The only part of that scenario that involved the Web, was when you walked in front of the post office, the Gmail website.

HTML
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The HTML stands for  HyperText Markup Language. It is the standard markup language for documents designed to be displayed in a web browser. You can make your own website using HTML. It defines the meaning and structure of web content. It can be assisted by technologies such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript to describe a web page's presentation or appearence and fumctionality.

 

The term "hypertext" refers to links that connect online pages inside a single website or between websites. Links are an important part of the Internet. HTML annotates text, pictures, and other content for display in a Web browser using "markup." Tags, which are written in angle brackets, separate HTML elements. Tags like <img /> and <input /> insert content into the page immediately. Other tags, such as <p>, surround and offer information about document text, and may comprise sub-elements of other tags.An element's name inside a tag is case insensitive. It can be written in capital, lowercase, or a combination of both. The <title> tag, for example, can be written as <TITLE>, <Title>, or any other variation. However, it is conventional and advised to write tags in lowercase.

Base Tags
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Title
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
 The <title> tag defines the title of the document. The title must be text-only, and it is shown in the browser's title bar or in the page's tab.

The <title> tag is required in HTML documents!

The contents of a page title is very important for search engine optimization (SEO)! The page title is used by search engine algorithms to decide the order when listing pages in search results.

The <title> element:

Defines a title in the browser toolbar.
Provides a title for the page when it is added to favorites.
Displays a title for the page in search-engine results.
Here are some tips for creating good titles:

Go for a longer, descriptive title (avoid one- or two-word titles)
Search engines will display about 50-60 characters of the title, so try not to have titles longer than that
Do not use just a list of words as the title (this may reduce the page's position in search results)
So, try to make the title as accurate and meaningful as possible!

Example:

<!DOCTYPE html>
<html>
     <head>
          <title>HTML Elements Reference</title>
     </head>
     
     <body>
          <h1>This is a heading</h1>
          <p>This is a paragraph.</p>
     </body>
</html>
 

Body
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The <body> tag defines the document's body.

The <body> element contains all the contents of an HTML document, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.

Note: There can only be one <body> element in an HTML document

Div & Span
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
HTML <div> and <span> Tags

Both <div> and <span> is used to define parts of a web page. The <span> element shows the inline portion of a document. The <div> elements show a block-level portion of a document.
A div is a block-level element and a span is an inline element.
The div should be used to wrap sections of a document, while use spans to wrap small portions of text, images, etc.
 

Example:

<div>Demo Text, with <span>some other</span> text.</div>
The <div> element is used while creating CSS based layouts in html, whereas <span> element is used to stylize texts.
 

Script
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The <script> tag is used to embed executable code in a HTML document. The executable code is usually JavaScript code, but the tag also supports JSON or  WebGL's GLSL shader programming language.

Basic use of <script> tag:
 

<script>
 //inline script here
</script>

<!-- Embedding a javascript file  -->
<script src="file.js"></script>
The script tag has multiple attributes:

src
type
async
crossorigin
defer
integrity
nomodule
nonce
referrerpolicy
 

src
src attribute specifies the URI of the external script. This is required if the script is not embedded directly within the document.

 

type
type attribute indicates the type of script represented. The value of this attribute will be in one of the following categories:

Omitted or JavaScript MIME type: Indicates the script is JavaScript. 
Module: Causes the code to be treated as a JavaScript module. 
Any other value: Makes the browser treat it as a data block which wont be processed.
 

async
For classic scripts, if the async attribute is present, then the classic script will be fetched in parallel to parsing and evaluated as soon as it is available.

For module scripts, if the async attribute is present then the scripts and all their dependencies will be executed in the defer queue, therefore they will get fetched in parallel to parsing and evaluated as soon as they are available.

This attribute allows the elimination of parser-blocking JavaScript where the browser would have to load and evaluate scripts before continuing to parse. defer has a similar effect in this case.

 

defer
This Boolean attribute is set to indicate to a browser that the script is meant to be executed after the document has been parsed, but before firing DOMContentLoaded.

Style
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The <style> tag is used to provide style information to the HTML document. It contains CSS code which is applied to the document based on the CSS code provided between the style opening and closing tag.

Example:

<head>
  <style>
    h2 {
      color: pink;
    }
  </style>
</head>
<body>
  <h2>Hello World, this is colored text </h2>
</body>
This will change the color of all h2 tags to pink.

Attributes of <style> tag:

media: Defines which media to apply the styles (accepts media query value).
nonce
title
P tag
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The <p> tag means a paragraph.

Paragraphs are block level elements. (block level elements take up the full width available). 

Example:

<p>This is a paragraph. </p>
 

Meta Tags
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
HTML <meta> Tag

The <meta> tag defines metadata about an HTML document. Metadata is data (information) about data.
<meta> tags always go inside the <head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.
Metadata will not be displayed on the page, but is machine parsable.
Metadata is used by browsers (how to display content or reload page), search engines (keywords), and other web services.
There is a method to let web designers take control over the viewport (the user's visible area of a web page), through the <meta> tag.
Example:

<head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
 

Attributes

Attribute	Value	Description
charset	character_set	Specifies the character encoding for the HTML document
content	text	Specifies the value associated with the http-equiv or name attribute
http-equiv	content-security-policy
content-type
default-style
refresh	Provides an HTTP header for the information/value of the content attribute
name	application-name
author
description
generator
keywords
viewport
 

 

Define keywords for search engines:

 

<meta name="keywords" content="HTML, CSS, JavaScript">
Define a description of your web page:

<meta name="description" content="Free Web tutorials for HTML and CSS">
Define the author of a page:

<meta name="author" content="John Doe">
Refresh document every 30 seconds:

<meta http-equiv="refresh" content="30">
Setting the viewport to make your website look good on all devices:

<meta name="viewport" content="width=device-width, initial-scale=1.0">
Setting the Viewport:

The viewport is the user's visible area of a web page. It varies with the device - it will be smaller on a mobile phone than on a computer screen.
You should include the following <meta> element in all your web pages:
<meta name="viewport" content="width=device-width, initial-scale=1.0">
This gives the browser instructions on how to control the page's dimensions and scaling.
The width=device-width part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).
The initial-scale=1.0 part sets the initial zoom level when the page is first loaded by the browser.
Here is an example of a web page without the viewport meta tag, and the same web page with the viewport meta tag:
Tip: If you are browsing this page with a phone or a tablet, you can click on the two links below to see the difference.
Layout
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Header
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The <header> tag is used to represent introductory content of the page/document. Mostly, it contains navigation elements or some heading elements like a logo, page name etc.

Example:

<header>
  <h1>This is heading inside header</h1>
</header>
 

Nav
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The <nav> tag is used to define the navigation section of a page. It's purpose is to provide navigation links to the other parts of website or to any external website. The navigation sections usually contains a list or a nested list of navigation links for the website.

Example:

<nav>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="/about">About Us</a></li>
    <li><a href="/contact">Contact Us</a></li>
  </ul>
</nav>
 

Section
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
 

 The <section> tag is used to define the generalised section of a page if the page doesn't have a more specific semantic element to represent it. Each section should have a heading.

Example:

<section>
  <h2>Section Title</h2>
  <p>This is the section content</p>
</section>
 

Aside
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
 The <aside> tag is used to define a portion of a document whose content is only indirectly related to the document's main content. 

Example:

<aside>
    <p>This is a sample text.</p>
</aside>
 

Footer
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Lists
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Ordered list
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Ordered list

The HTML <ol> tag defines an ordered list. An ordered list can be numerical or alphabetical.

An ordered list:

     1. The first list item

     2. The second list item

     3. The third list item

An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.

The list items will be marked with numbers by default:

Example:
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
How the HTML code above looks in a browser:

    1. Coffee

    2. Milk

 

Ordered HTML List - The Type Attribute
The type attribute of the <ol> tag, defines the type of the list item marker:

Type	Description
type="1"	The list items will be numbered with numbers (default)
type="A"	The list items will be numbered with uppercase letters
type="a"	The list items will be numbered with lowercase letters
type="I"	The list items will be numbered with uppercase roman numbers
type="i"	The list items will be numbered with lowercase roman numbers
 

Examples:

Numbers:
<ol type="1">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
Uppercase Letters:
<ol type="A">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
Lowercase Letters:
<ol type="a">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
Uppercase Roman Numbers:
<ol type="I">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
Lowercase Roman Numbers:
<ol type="i">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
 
Control List Counting
By default, an ordered list will start counting from 1. If you want to start counting from a specified number, you can use the start attribute:

Example:
<ol start="50">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
 

Unordered list
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Unordered list

The HTML <ul> tag defines an unordered (bulleted) list.

An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.

The list items will be marked with bullets (small black circles) by default:

Example:
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
How the HTML code above looks in a browser:

     • Coffee

     • Milk

An unordered list:

     • List item

     • List item

     • List item

 

Unordered HTML List - Choose List Item Marker

The CSS list-style-type property is used to define the style of the list item marker. It can have one of the following values:

Value	Description
disc	Sets the list item marker to a bullet (default)
circle	Sets the list item marker to a circle
square	Sets the list item marker to a square
none	The list items will not be marked
Example:
- Disc
<ul style="list-style-type:disc;">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
- Circle
<ul style="list-style-type:circle;">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
 - Square
<ul style="list-style-type:square;">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
 - None
<ul style="list-style-type:none;">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
 

Description list
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Media
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Adding Audio
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The HTML <audio> element is used to play an audio file on a web page.

Example:

 <audio controls>
         <source src="sasuketheme.ogg" type="audio/ogg">
         <source src="naruto.mp3" type="audio/mpeg">
         Your browser does not support the audio element.
 </audio> 
 

Working:

The controls attribute adds audio controls, like play, pause, and volume.
The <source> element allows you to specify alternative audio files which the browser may choose from. The browser will use the first recognized format.
The text between the <audio> and </audio> tags will only be displayed in browsers that do not support the <audio> element.
 

Audio Formats:

There are three supported audio formats: MP3, WAV, and OGG. The browser support for the different formats is:

Browser	MP3	WAV	OGG
Edge/IE	YES	NO	NO
Chrome	YES	YES	YES
Firefox	YES	YES	YES
Safari	YES	YES	NO
Opera	YES	YES	YES
Adding Images
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
HTML Images

Images can improve the design and the appearance of a web page.

Example:
<img src="pic_trulli.jpg" alt="Italian Trulli">
HTML Images Syntax

The HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image
Syntax
<img src="url" alt="alternatetext">
The src Attribute

The required src attribute specifies the path (URL) to the image.

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise, your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

Example
<img src="img_chania.jpg" alt="Flowers in Chania">

 

 

Adding video
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
 <video> element is used to show a video on a web page.

Example:

 <video width="320" height="240" controls>
       <source src="movie.mp4" type="video/mp4">
       <source src="movie.ogg" type="video/ogg">
       Your browser does not support the video tag.
</video> 
 

Working:

The controls attribute adds video controls, like play, pause, and volume.

It is a good idea to always include width and height attributes. If height and width are not set, the page might flicker while the video loads.

The <source> element allows you to specify alternative video files which the browser may choose from. The browser will use the first recognized format.

The text between the <video> and </video> tags will only be displayed in browsers that do not support the <video> element.

 

Autoplay attribute:

To start a video automatically use the autoplay attribute:
<video width="320" height="240" autoplay>
        <source src="movie.mp4" type="video/mp4">
        <source src="movie.ogg" type="video/ogg">
        Your browser does not support the video tag.
</video> 
 

Video formats:

There are three supported video formats: MP4, WebM, and Ogg. The browser support for the different formats is:

 Browser	MP4	WebM	Ogg
Edge	YES	YES	YES
Chrome	YES	YES	YES
Firefox	YES	YES	YES
Safari	YES	YES	NO
Opera	YES	YES	YES
Iframe
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
 HTML Iframes

An HTML iframe is used to display a web page within a web page

 

HTML Iframes- Syntax

The HTML <iframe> tag specifies an inline frame.

An inline frame is used to embed another document within the current HTML document.

Syntax:

<iframe src="url" title="description">
Tip: It is a good practice to always include a title attribute for the <iframe>. This is used by screen readers to read out what the content of the iframe is.

 

HTML Iframes- Set Height & Width

Use the height and width attributes to specify the size of the iframe.

The height and width are specified in pixels by default:

Example:

<iframe src="demo_iframe.htm" height="200" width="300" title="Iframe Example"></iframe>
Or you can add the style attribute and use the CSS height and width properties:

Example:

<iframe src="demo_iframe.htm" style="height:200px;width:300px;" title="Iframe Example"></iframe>
 

Iframe- Remove the Border

By default, an iframe has a border around it.

To remove the border, add the style attribute and use the CSS border property:

Example:

<iframe src="demo_iframe.htm" style="border:none;" title="Iframe Example"></iframe>
 

Iframe- Target for a Link

An iframe can be used as the target frame for a link.

The target attribute of the link must refer to the name attribute of the iframe:

Example:

<iframe src="demo_iframe.htm" name="iframe_a" title="Iframe Example"></iframe>

<p><a href="https://www.newtonschool.co" target="iframe_a">Newton School</a></p>
 

 

HTML Plug-ins

Plug-ins are computer programs that extend the standard functionality of the browser.

Plug-ins were designed to be used for many different purposes:

To run Java applets
To run Microsoft ActiveX controls
To display Flash movies
To display maps
To scan for viruses
To verify a bank id
 

Warning !

Most browsers no longer support Java Applets and Plug-ins.
ActiveX controls are no longer supported in any browsers.
The support for Shockwave Flash has also been turned off in modern browsers.
 

The <object> element

The <object> element is supported by all browsers.
The <object> element defines an embedded object within an HTML document.
It was designed to embed plug-ins (like Java applets, PDF readers, and Flash Players) in web pages, but can also be used to include HTML in HTML:
Example:

<object width="100%" height="500px" data="snippet.html"></object>
 

Embeding images using <object> element.

Example:

<object data="audi.jpeg"></object>
 

The <embed> Element

The <embed> element is supported in all major browsers.
The <embed> element also defines an embedded object within an HTML document.
Web browsers have supported the <embed> element for a long time. However, it has not been a part of the HTML specification before HTML5.
Example:
<embed src="audi.jpeg">
 

Note that the <embed> element does not have a closing tag. It can not contain alternative text.
The <embed> element can also be used to include HTML in HTML.
Example:
<embed width="100%" height="500px" src="snippet.html">
 

HTML Tables
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
                                                     HTML Tables
A table is just a combination of rows and columns on a webpage. Example:



Define an HTML Table:
The <table> tag defines an HTML table.

Each table row is defined with a <tr> tag. Each table header is defined with a <th> tag. Each table data/cell is defined with a <td> tag.

By default, the text in <th> elements are bold and centered.

By default, the text in <td> elements are regular and left-aligned.

 

The main part is the table tag, and it consists of two parts: the table head and table body. The <thead> consists of the main head of the table and <tbody> consists of the body of the table. 

<tr> is used to justify that it is the part of a row. Inside the <tr> tag, we give the headings of a row under the <th> tag.

lets make the above table:

<table>
  <thead><tr>
    <th>Country</th>
    <th>Capital</th> 
    <th>Language</th>
  </tr></thead>
  <tbody>
  <tr>
    <td>India</td>
    <td>New Delhi</td>
    <td>Hindi</td>
  </tr>
  <tr>
    <td>France</td>
    <td>Paris</td>
    <td>French</td>
  </tr>
  <tr>
    <td>NewZealand</td>
    <td>Wellington</td>
    <td>English</td>
  </tr>
</table>

Output:

Country	Capital	Language
India	New Delhi	Hindi
France	Paris	French
NewZealand	Wellington	English
Let's Do some Styling(CSS):

The HTML style attribute is used to add styles to an element, such as color, font, size, and more.

The HTML style attribute has the following syntax:<tagname style="property:value;">

The property is a CSS property. The value is a CSS value.
The CSS background-color property defines the background color for an HTML element.
Now let's add some background  colour to our above table:

<table>
  <thead><tr style="background-color:green;">
    <th>Country</th>
    <th>Capital</th> 
    <th>Language</th>
  </tr></thead>
  <tbody>
  <tr>
    <td>India</td>
    <td>New Delhi</td>
    <td>Hindi</td>
  </tr>
  <tr>
    <td>France</td>
    <td>Paris</td>
    <td>French</td>
  </tr>
  <tr>
    <td>NewZealand</td>
    <td>Wellington</td>
    <td>English</td>
  </tr>
</table>
Output:

Country	Capital	Language
India	New Delhi	Hindi
France	Paris	French
NewZealand	Wellington	English
 

 

Basic Table Structure

 

The <table> tag defines an HTML table.
Each table row is defined with a <tr> tag. Each table header is defined with a <th> tag. Each table data/cell is defined with a <td> tag.
By default, the text in <th> elements are bold and centered.
By default, the text in <td> elements are regular and left-aligned.
Example
A simple HTML table:

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
Note: The <td> elements are the data containers of the table.
They can contain all sorts of HTML elements; text, images, lists, other tables, etc.
Tr tag
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The <tr> (Table row) tag defines a row of cells in a table. The row's cells can then be established using a mix of <td> (data cell) and <th> (header cell) elements.

 

Example:

<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
        <td>Data 3</td>
    </tr>
</table>
Here, <tr> was used twice to create 2 rows, one for header elements and one for data elements.

Td tag
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
 

The <td> (table data) tag defines a cell of a table that contains data. It is used inside a <tr> (table row) tag to create a data cell in the specified row.

 

Example:

<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
        <td>Data 3</td>
    </tr>
</table>
Here, <td> tag is used 3 times inside the <tr> tag to create 3 data cells in the second row.

 

Attributes:
colspan:  This attribute defines the number of columns the data cell extends. Default value is 1. Max value is 1000.
headers:  This attribute contains the list of space separated strings, each corresponding to the id attribute of the <th> elements that apply to this element.
rowspan:  This attribute defines the number of rows the data cell extends. Default value is 1. If its value is set to 0, it will extend until the end of the table section that the cell belongs to. 
Th tag
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The <th> (table header) tag defines a cell of a table as header of a group of data cells. It is used inside a <tr> (table row) tag to create a header cell in the specified row.

 

Example:

<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
        <td>Data 3</td>
    </tr>
</table>
Here, <th> tag is used 3 times inside the <tr> tag to create 3 header cells in the first row.

Attributes:
colspan:  This attribute defines the number of columns the header cell extends. Default value is 1. Max value is 1000.
headers:  This attribute contains the list of space separated strings, each corresponding to the id attribute of the <th> elements that apply to this element.
rowspan:  This attribute defines the number of rows the data cell extends. Default value is 1. If its value is set to 0, it will extend until the end of the table section that the cell belongs to. 
abbr:  This attribute contains short abbreviated description of cell's content. 
scope:  This attribute defines the cells that the header element (<th>) relates to. It can have following values:
row: Header relates to all cells of the row it belongs to.
col: Header relates to all cells of the column it belongs to.
rowgroup: Header belongs to a rowgroup and relates to all of its cells. The cells can be to the right or left of the header, depending on value of dir attribute in <table>.
colgroup: Header belongs to a colgroup and relates to all of its cells.
Tbody
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
 

The <tbody> tag encapsulates a set of table rows (<tr> elements), indicating that they comprise the body of the table (<table>). 

 

Example:

<table>
  <thead>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
        <td>Data 3</td>
    </tr>
    <tr>
        <td>Data 4</td>
        <td>Data 5</td>
        <td>Data 6</td>
    </tr>
  </tbody>
</table>
​
Here, <tbody> is used to club all data rows.

Thead
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The <thead> tag defines a set of table rows (<tr> elements), indicating that they comprise the head of the columns of the table (<table>). 

 

Example:

<table>
  <thead>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
        <td>Data 3</td>
    </tr>
    <tr>
        <td>Data 4</td>
        <td>Data 5</td>
        <td>Data 6</td>
    </tr>
  </tbody>
</table>
​
Here, <thead> is used to club all rows of header cells.

Attributes
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Attributes:

     • HTML elements can have attributes.

     • Attributes provide additional information about an element.

     • Attributes are always specified in the start tag.

     • Attributes come in name/value pairs like: name="value".

 

Attribute Example

HTML links are defined with the tag. The link address is specified in the href attribute:

Example

<a href="http://www. xitecsolutions.com">This is a link</a>

 

Always Quote Attribute Values

Attribute values should always be enclosed in quotes.

Double style quotes are the most common, but single style quotes are also allowed.

Tip: In some rare situations, when the attribute value itself contains quotes, it is necessary to use single quotes: name='John "ShotGun" Nelson'HTML

 

Tip: Use Lowercase Attributes

Attribute names and attribute values are case-insensitive.

Newer versions of (X)HTML will demand lowercase attributes.

 

Below is a list of some attributes that are standard for most HTML elements:

Attribute	Value	Description
class	classname	Specifies a class name for an element
id	id	Specifies a unique id for an element
style	style_defination	Specifies an inline style for an element
title	tooltip_text	Specifies extra information about an element (displayed as a tool tip)
Src
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Href
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Height
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Width
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Alt
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Semantic HTML
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Article
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Figcaption
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Figure
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Summary
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
When you type a web address into your browser(in terms of the above analogy) -:

The browser goes to the DNS server, and finds the real address of the server that the website lives on (you find the address of the shop).
The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client (you go to the shop and order your goods). This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.
If the server approves the client's request, the server sends the client a "200 OK" message, which means "Of course you can look at that website! Here it is", and then starts sending the website's files to the browser as a series of small chunks called data packets (the shop gives you your goods, and you bring them back to your house).
The browser assembles the small chunks into a complete website and displays it to you (the goods arrive at your door).
Main
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43


HTML Forms
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
HTML Forms are used to select different kinds of user input.
HTML forms are used to pass data to a server.
A form can contain input elements like text fields, checkboxes, radio-buttons, submit
buttons and more. A form can also contain select lists, textarea, fieldset, legend, and label
elements.
The <form> tag is used to create an HTML form:
<form>
input elements
</form>
Base Elements
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Form tag
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The <form> tag represents a document section containing interactive controls for submitting information.

 

Example:

<form>
  <div>
    <label for="name">Enter name: </label>
    <input type="text" name="name" id="name" required>
  </div>
  <div>
    <label for="email">Enter email ID: </label>
    <input type="email" name="email" id="email" required>
  </div>
    <input type="submit" value="Subscribe!">
</form>
 

Attributes:
name: Specifies the name of the form
rel: Creates a hyperlink or annotation depending on the value.
action: The URL that processes the form submission. 
method: The HTTP method to submit the form with. Accepts values:
post: Form data sent as request body.
get: Form data appended to action URL with ? separator.
enctype: It determines the MIME Type of the form submission if the form method is POST.
application/x-www-form-urlencoded
multipart/form-data
text/plain
target: Indicates where to display the response after submitting the form. In HTML5, it is a name/keyword for a browsing context. Following keywords have special meanings:
_self (default): Load into the same browsing context as the current one.
_blank: Load into a new unnamed browsing context.
_parent: Load into the parent browsing context of the current one. If no parent, behaves the same as _self.
_top: Load into the top-level browsing context. If no parent, behaves the same as _self.
Input tag
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The <input> tag is used to create interactive controls for web based forms to accept data from user. The type attribute of the input tag determines the type of the input to accept from the user.

 

Example:

<form>
  <div>
    <label for="name">Enter name: </label>
    <input type="text" name="name" id="name" required>
  </div>
  <div>
    <label for="email">Enter email ID: </label>
    <input type="email" name="email" id="email" required>
  </div>
    <input type="submit" value="Subscribe!">
</form>
Here, one input has the type text and one has the type email.

 

Attributes:
type: Defines the type of input to accept from the user. Can accept the following values:
button
checkbox
color
date
datetime
datetime-local
email
file
hidden
image
month
number
password
radio
range
reset
search
tel
text
time
url
week
accept: Defines expeted file type in file upload controls
alt: alt attribute for image type
autocomplete: Hint for form autofill feature
autofocus: Automatically focus the form control when the page is loaded.
disabled: Defines whether the form control is disabled
pattern: Checks if the value follows the given pattern
placeholder: Text that appears in the form control when it has no value set
required: Boolean. A value is required or must be check for the form to be submittable.
value: Initial value of the control
Text Input
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The Input Element

The most important form element is the input element.

The input element is used to select user information.

An input element can vary in many ways, depending on the type attribute.

An input element can be of type text field, checkbox, password, radio button, submit button, and more.

The most used input types are described below.

Label
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The labels are what follow the TLD. A label can be anything, from one letter to a full sentence. The label located right before the TLD can also be referred as a Secondary Level Domain (SLD). A domain name can have many labels (or components), it is not mandatory nor necessary to have 3 labels to form a domain name. For instance, www.inf.ed.ac.uk is a correct domain name. For any domain name you might have control over (e.g. geeksforgeeks.org), you can create "subdomains" with different content located at each, for example practice.geeksforgeeks.org

Radio button
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Radio Buttons

<input type="radio"/> defines a radio button. Radio buttons let a user select ONLY ONE of a limited number of choices:

<form>

<input type="radio" name="sex" value="male"/> Male<br/>

<input type="radio" name="sex" value="female"/> Female

</form>

How the HTML code above looks in a browser:

 Male
 Female
Checkbox
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
<input name="name" />
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Submit button
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Submit Button

<input type="submit"/> defines a submit button.

A submit button is used to send form data to a server. The data is sent to the page specified in the form's action attribute. The file defined in the action attribute usually does something with the received input:

<form name="input" action="html_form_action.asp" method="get">

Username: <input type="text" name="user"/>

<input type="submit" value="submit"/>

</form>

How the HTML code above looks in a browser:

Username: 
  
If you type some characters in the text field above, and click the "Submit" button, the browser will send your input to a page called "html_form_action.asp". The page will show you the received input.

Form attributes
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Action
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Target
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Method attr
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Form Elements
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Text area
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Text Fields

<input type="text"/> defines a one-line input field that a user can enter text into:

<form>

First name:<input type="text" name="firstname"/><br>

Last name:<input type="text" name="lastname"/>

</form>

How the HTML code above looks in a browser:

First name: 

Last name: 
 
Note: The form itself is not visible. Also note that the default width of a text field is 20 characters.

Select
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Buttons
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Fieldset
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Output tag
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Optgroup
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Option tag
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input types
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type button
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type checkbox
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type color
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type date
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type datetime-local
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type email
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type file
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type hidden
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type image
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type month
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type number
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type password
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type radio
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type range
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type search
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type submit
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type tel
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type text
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type url
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type week
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input type reset
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Input attributes
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Value
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Readonly
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Disabled
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Maxlength,min and max
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Multiple
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Pattern
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Placeholder
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Required
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Step
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Autofocus
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Height and Width
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
List and datalist
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Autocomplete
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
CSS
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
The language that we use to style an HTML document is CSS.

CSS specifies how HTML elements should appear. CSS specifies how elements should appear on a screen, on paper, in speech, or in other forms of media.

Selectors
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
CSS Selectors
A CSS selector selects the HTML element(s) you want to style.

CSS selectors are used to "find" (or select) the HTML elements you want to style.

We can divide CSS selectors into five categories:

Simple selectors (select elements based on name, id, class)
Combinator selectors (select elements based on a specific relationship between them)
Pseudo-class selectors (select elements based on a certain state)
Pseudo-elements selectors (select and style a part of an element)
Attribute selectors (select elements based on an attribute or attribute value)
1.The CSS element Selector
The element selector selects HTML elements based on the element name.

Example
Here, all <p> elements on the page will be center-aligned, with a red text color: 

p {
  text-align: center;
  color: red;
}
 
2.The CSS id Selector
The id selector uses the id attribute of an HTML element to select a specific element.

The id of an element is unique within a page, so the id selector is used to select one unique element!

To select an element with a specific id, write a hash (#) character, followed by the id of the element.

Example
The CSS rule below will be applied to the HTML element with id="para1": 

#para1 {
  text-align: center;
  color: red;
}
3.The CSS class Selector
The class selector selects HTML elements with a specific class attribute.

To select elements with a specific class, write a period (.) character, followed by the class name.

Example
In this example all HTML elements with class="center" will be red and center-aligned: 

.center {
  text-align: center;
  color: red;
}
You can also specify that only specific HTML elements should be affected by a class.

Example
In this example only <p> elements with class="center" will be red and center-aligned: 

p.center {
  text-align: center;
  color: red;
}
HTML elements can also refer to more than one class.

Example
In this example the <p> element will be styled according to class="center" and to class="large": 

<p class="center large">This paragraph refers to two classes.</p>
4.The CSS Universal Selector
The universal selector (*) selects all HTML elements on the page.

Example
The CSS rule below will affect every HTML element on the page: 

* {
  text-align: center;
  color: blue;
}
5.The CSS Grouping Selector
The grouping selector selects all the HTML elements with the same style definitions.

Look at the following CSS code (the h1, h2, and p elements have the same style definitions):

h1 {
  text-align: center;
  color: red;
}

h2 {
  text-align: center;
  color: red;
}

p {
  text-align: center;
  color: red;
}
It will be better to group the selectors, to minimize the code.

To group selectors, separate each selector with a comma.

In this example we have grouped the selectors from the code above: 

h1, h2, p {
  text-align: center;
  color: red;
}

6.CSS Combinators
A combinator is something that explains the relationship between the selectors.

A CSS selector can contain more than one simple selector. Between the simple selectors, we can include a combinator.

There are four different combinators in CSS:

descendant selector (space)
child selector (>)
adjacent sibling selector (+)
general sibling selector (~)
6.1 Descendant Selector
The descendant selector matches all elements that are descendants of a specified element.

The following example selects all <p> elements inside <div> elements: 

Example
div p {
  background-color: yellow;
}
 

6.2 Child Selector (>)
The child selector selects all elements that are the children of a specified element.

The following example selects all <p> elements that are children of a <div> element:

Example
div > p {
  background-color: yellow;
 

6.3 Sibling Selector (+)
The adjacent sibling selector is used to select an element that is directly after another specific element.

Sibling elements must have the same parent element, and "adjacent" means "immediately following".

The following example selects the first <p> element that are placed immediately after <div> elements:

Example
div + p {
  background-color: yellow;
}

 
6.4 General Sibling Selector (~)
The general sibling selector selects all elements that are siblings of a specified element.

The following example selects all <p> elements that are siblings of <div> elements: 

Example
div ~ p {
  background-color: yellow;
}
7.CSS Pseudo-classes
What are Pseudo-classes?
A CSS pseudo-class is a keyword added to a selector that specifies a special state of the selected element(s). For example, :hover can be used to change a button's color when the user's pointer hovers over it.
A pseudo-class is used to define a special state of an element.

For example, it can be used to:

Style an element when a user hovers over it
Style visited and unvisited links differently
Style an element when it gets focus
Syntax
The syntax of pseudo-classes:

selector:pseudo-class {
  property: value;
}
 
Hover on <div>
An example of using the :hover pseudo-class on a <div> element:

Example
div:hover {
  background-color: blue;
}
8. CSS Pseudo-elements
What are Pseudo-Elements?
A CSS pseudo-element is used to style specified parts of an element.

For example, it can be used to:

Style the first letter, or line, of an element
Insert content before, or after, the content of an element
Syntax
The syntax of pseudo-elements:

selector::pseudo-element {
  property: value;
}
The ::first-line Pseudo-element
The ::first-line pseudo-element is used to add a special style to the first line of a text.

The following example formats the first line of the text in all <p> elements:

Example 
p::first-line {
  color: #ff0000;
  font-variant: small-caps;
}
Note: The ::first-line pseudo-element can only be applied to block-level elements.

The following properties apply to the ::first-line pseudo-element:

font properties
color properties
background properties
word-spacing
letter-spacing
text-decoration
vertical-align
text-transform
line-height
clear
9. CSS Attribute Selectors
Style HTML Elements With Specific Attributes
It is possible to style HTML elements that have specific attributes or attribute values.

CSS [attribute] Selector
The [attribute] selector is used to select elements with a specified attribute.

The following example selects all <a> elements with a target attribute:

Example
a[target] {
  background-color: yellow;
}
CSS [attribute="value"] Selector
The [attribute="value"] selector is used to select elements with a specified attribute and value.

The following example selects all <a> elements with a target="_blank" attribute:

Example
a[target="_blank"] {
  background-color: yellow;
 

 
Basic Selectors
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Element selector
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Id selector
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Class selector
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Universal/global selector
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Grouping selector
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Combinators
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Descendant selector (space)
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Child selector (>)
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Adjacent sibling selector (+)
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
General sibling selector (~)
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Pseudo classes
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:active
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:checked
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:disabled
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:empty
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:enabled
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:first-child
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:first-of-type
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:focus
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:hover
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:in-range
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:invalid
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:lang(language)
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:last-child
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:last-of-type
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:link
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:not(selector)
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:nth-child(n)
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:nth-last-child(n)
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:nth-last-of-type(n)
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:nth-of-type(n)
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:only-of-type
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:only-child
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:optional
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:out-of-range
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:read-only
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:read-write
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:required
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:root
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:target
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:valid
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
:visited
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Pseudo elements
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
::after
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
::before
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
::first-letter
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
::first-line
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
::selection
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Selector-Attributes
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
[attribute]
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
[attribute=value]
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
[attribute~=value]
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
[attribute|=value]
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
[attribute^=value]
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
[attribute$=value]
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
[attribute*=value]
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
CSS Styling
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
CSS Colours
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Color Names
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Background Color
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Text Color
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Border Color
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Color Values
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
CSS Backgrounds
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Background-color
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Background-image
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Background-repeat
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Background-position
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Background
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Box Model
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:

Explanation of the different parts:

Content - The content of the box, where text and images appear
Padding - Clears an area around the content. The padding is transparent
Border - A border that goes around the padding and content
Margin - Clears an area outside the border. The margin is transparent
The box model allows us to add a border around elements, and to define space between elements.

Example
Demonstration of the box model:

div {  
width: 300px;  
border: 15px solid green;  
padding: 50px;  
margin: 20px;
}
Width and Height of an Element
In order to set the width and height of an element correctly in all browsers, you need to know how the box model works.

Important: When you set the width and height properties of an element with CSS, you just set the width and height of the content area. To calculate the full size of an element, you must also add padding, borders, and margins.

div {
  width: 320px;
  padding: 10px;
  border: 5px solid gray;
  margin: 0;
}
320px (width)

20px (left + right padding)

10px (left + right border)

0px (left + right margin)

= 350px

The total width of an element should be calculated like this:

Total element width = width + left padding + right padding + left border + right border + left margin + right margin

The total height of an element should be calculated like this:

Total element height = height + top padding + bottom padding + top border + bottom border + top margin + bottom margin

CSS Gradients
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
CSS Margin and Padding
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
CSS Shadows
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
CSS text-effects
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Pre Flexbox
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Display block
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Display inline
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Display table
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Animations
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
What are CSS Animations?
An animation lets an element gradually change from one style to another.

You can change as many CSS properties you want, as many times as you want.

To use CSS animation, you must first specify some keyframes for the animation.

Keyframes hold what styles the element will have at certain times.

The @keyframes Rule
When you specify CSS styles inside the @keyframes rule, the animation will gradually change from the current style to the new style at certain times.

To get an animation to work, you must bind the animation to an element.

The following example binds the "example" animation to the <div> element. The animation will last for 4 seconds, and it will gradually change the background-color of the <div> element from "red" to "yellow":

/* The animation code */
@keyframes example {
  from {background-color: red;}
  to {background-color: yellow;}
}

/* The element to apply the animation to */
div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
}
Note: The animation-duration property defines how long an animation should take to complete. If the animation-duration property is not specified, no animation will occur, because the default value is 0s (0 seconds).

In the example above we have specified when the style will change by using the keywords "from" and "to" (which represents 0% (start) and 100% (complete)).

It is also possible to use percent. By using percent, you can add as many style changes as you like.

The following example will change the background-color of the <div> element when the animation is 25% complete, 50% complete, and again when the animation is 100% complete:

/* The animation code */
@keyframes example {
  0%   {background-color: red;}
  25%  {background-color: yellow;}
  50%  {background-color: blue;}
  100% {background-color: green;}
}

/* The element to apply the animation to */
div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
}
The following example will change both the background-color and the position of the <div> element when the animation is 25% complete, 50% complete, and again when the animation is 100% complete:

/* The animation code */
@keyframes example {
  0%   {background-color:red; left:0px; top:0px;}
  25%  {background-color:yellow; left:200px; top:0px;}
  50%  {background-color:blue; left:200px; top:200px;}
  75%  {background-color:green; left:0px; top:200px;}
  100% {background-color:red; left:0px; top:0px;}
}

/* The element to apply the animation to */
div {
  width: 100px;
  height: 100px;
  position: relative;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
}

Delay an Animation
The animation-delay property specifies a delay for the start of an animation.

The following example has a 2 seconds delay before starting the animation:

div {
  width: 100px;
  height: 100px;
  position: relative;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
  animation-delay: 2s;
}
Negative values are also allowed. If using negative values, the animation will start as if it had already been playing for N seconds.

In the following example, the animation will start as if it had already been playing for 2 seconds:

div {
  width: 100px;
  height: 100px;
  position: relative;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
  animation-delay: -2s;
}

Set How Many Times an Animation Should Run
The animation-iteration-count property specifies the number of times an animation should run.

The following example will run the animation 3 times before it stops:

div {
  width: 100px;
  height: 100px;
  position: relative;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
  animation-iteration-count: infinite;
}

Run Animation in Reverse Direction or Alternate Cycles
The animation-direction property specifies whether an animation should be played forwards, backwards or in alternate cycles.

The animation-direction property can have the following values:

normal - The animation is played as normal (forwards). This is default
reverse - The animation is played in reverse direction (backwards)
alternate The animation is played forwards first, then backwards
alternate-reverse - The animation is played backwards first, then forwards
The following example will run the animation in reverse direction (backwards):

div {
  width: 100px;
  height: 100px;
  position: relative;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
  animation-direction: reverse;
}
The following example uses the value "alternate" to make the animation run forwards first, then backwards:

div {
  width: 100px;
  height: 100px;
  position: relative;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
  animation-iteration-count: 2;
  animation-direction: alternate;
}
The following example uses the value "alternate-reverse" to make the animation run backwards first, then forwards:

div {
  width: 100px;
  height: 100px;
  position: relative;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
  animation-iteration-count: 2;
  animation-direction: alternate-reverse;
}

Specify the Speed Curve of the Animation
The animation-timing-function property specifies the speed curve of the animation.

The animation-timing-function property can have the following values:

ease - Specifies an animation with a slow start, then fast, then end slowly (this is the default)
linear - Specifies an animation with the same speed from start to end
ease-in - Specifies an animation with a slow start
ease-out - Specifies an animation with a slow end
ease-in-out - Specifies an animation with a slow start and end
cubic-bezier(n,n,n,n) - Lets you define your own values in a cubic-bezier function
The following example shows some of the different speed curves that can be used:

#div1 {animation-timing-function: linear;}
#div2 {animation-timing-function: ease;}
#div3 {animation-timing-function: ease-in;}
#div4 {animation-timing-function: ease-out;}
#div5 {animation-timing-function: ease-in-out;}

Specify the fill-mode For an Animation
CSS animations do not affect an element before the first keyframe is played or after the last keyframe is played. The animation-fill-mode property can override this behavior.

The animation-fill-mode property specifies a style for the target element when the animation is not playing (before it starts, after it ends, or both).

The animation-fill-mode property can have the following values:

none - Default value. Animation will not apply any styles to the element before or after it is executing
forwards - The element will retain the style values that is set by the last keyframe (depends on animation-direction and animation-iteration-count)
backwards - The element will get the style values that is set by the first keyframe (depends on animation-direction), and retain this during the animation-delay period
both - The animation will follow the rules for both forwards and backwards, extending the animation properties in both directions
The following example lets the <div> element retain the style values from the last keyframe when the animation ends:

div {
  width: 100px;
  height: 100px;
  background: red;
  position: relative;
  animation-name: example;
  animation-duration: 3s;
  animation-fill-mode: forwards;
}
The following example lets the <div> element get the style values set by the first keyframe before the animation starts (during the animation-delay period):

div {
  width: 100px;
  height: 100px;
  background: red;
  position: relative;
  animation-name: example;
  animation-duration: 3s;
  animation-delay: 2s;
  animation-fill-mode: both;
}

Animation Shorthand Property
The example below uses six of the animation properties:

div {
  animation-name: example;
  animation-duration: 5s;
  animation-timing-function: linear;
  animation-delay: 2s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
}
The same animation effect as above can be achieved by using the shorthand animation property:

div {
  animation: example 5s linear 2s infinite alternate;
}


CSS Animation Properties
The following table lists the @keyframes rule and all the CSS animation properties:
Property	Description
@keyframes	Specifies the animation code
animation	A shorthand property for setting all the animation properties
animation-delay	Specifies a delay for the start of an animation
animation-direction	Specifies whether an animation should be played forwards, backwards or in alternate cycles
animation-duration	Specifies how long time an animation should take to complete one cycle
animation-fill-mode	Specifies a style for the element when the animation is not playing (before it starts, after it ends, or both)
animation-iteration-count	Specifies the number of times an animation should be played
animation-name	Specifies the name of the @keyframes animation
animation-play-state	Specifies whether the animation is running or paused
animation-timing-function	Specifies the speed curve of the animation

 
Responsive CSS
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Flexbox
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Before the Flexbox Layout module, there were four layout modes:

Block, for sections in a webpage
Inline, for text
Table, for two-dimensional table data
Positioned, for the explicit position of an element
The Flexible Box Layout Module makes it easier to design a flexible responsive layout structure without using float or positioning.

 

 

Flexbox Elements
To start using the Flexbox model, you need to first define a flex container.

Create a Flex Container
 

1
2
3
The element above represents a flex container (big box) with three flex items.

Example
A flex container with three flex items:

 

<div class="flex-container">  
<div>1</div>  
<div>2</div>  
<div>3</div>
</div>
 
CSS Flex Container
 

Parent Element (Container)
 In the example shown above, the blue colored box is a flex container which holds 3 flex items.

A div container becomes flexible when its display property is set to flex .

 

.container {
  display: flex;
}
After a container is set flexible, multiple properties can be applied to it.

Flex container properties are:

flex-direction
flex-wrap
flex-flow
justify-content
align-items
align-content
 

 

flex-direction Property
The flex-direction property defines the direction to stack the flex items.

It can be set to:

flex-direction: row
flex-direction: column
flex-direction: row-reverse
flex-direction: column-reverse
 

Example:
 

1
2
3
This is flex-direction set to column.

 

 

flex-wrap Property
The flex-wrap property determines whether to wrap the flex items.

It can be set to:

flex-wrap: wrap
flex-wrap: no-wrap
flex-wrap: wrap-reverse
 

Example:
 

1
2
3
4
5
6
7
8
9
10
11
12
13
14
This is flex-wrap set to wrap.

 

 

flex-flow Property
The flex-flow property is a shorthand property to set both flex-direction and flex-wrap.

It can be set as:

 

.container {
  display: flex;
  flex-flow: row-reverse wrap;
}
 

 

justify-content Property
The justify-content aligns the flex items along the axis of flex-direction (aligns horizontally if flex direction is row).

It can be set to:

justify-content: flex-start (aligns from start)
justify-content: flex-end (aligns from end)
justify-content: center (aligns to the center)
justify-content: space-around (equal space between each div and the container ends)
justify-content: space-between (equal space between each div)
 

Example:
 

1
2
3
4
5
This container is set to space around property.

 

 

align-content Property
The align-content aligns the flex items perpendicular to the axis of flex-direction (aligns vertically if flex direction is row).

It can be set to:

align-content: flex-start (aligns from start)
align-content: flex-end (aligns from end)
align-content: center (aligns to the center)
align-content: space-around (equal space between each div and the container ends)
align-content: space-between (equal space between each div)
align-content: stretch (stretches the flex items to occupy remaining space)
 

Example:
 

1
2
3
4
5
Here align content is set to center.

 

 

CSS Flex Items
Child Element (Item)
When a container is set flex, all of its direct child elements become flex automatically.

So, all the boxes marked with numbers in the above examples are flex items inside a flex container.

Properties of flex item are:

order
flex-grow
flex-shrink
flex-basis
flex
align-self
 

order Property
The order property allows you to specify the order of flex item inside the container.

It can be set to any number (only numbers). Default value is 0 for all elements.

order: 4
 

Example:
 

1
2
3
4
Here the elements are given order 2, 1, 4, 3.

 

flex-grow Property
The flex-grow property specifies how much a flex item will grow relative to other flex items in the container.

It can be set to any number (only numbers). Default value is 0 for all elements:

flex-grow: 4 (this item will grow more than other elements set at 0)
 

Example:
 

1
2
3
Here 2nd flex item is given flex-grow of 2 which will take more space than default flex-grow of 1st and 3rd div.

 

flex-shrink Property
The flex-shrink property specifies how much a flex item will shrink relative to other flex items in the container.

It can be set to any number (only numbers). Default value is 1 for all elements:

flex-shrink: 4 (this item will grow more than other elements set at 1)
 

 

flex-basis Property
The flex-basis property specifies the initial length of a flex item

It can be set to any length like width.

flex-basis: 100px
 

Example:
 

1
2
3
Here the 2nd div is given flex-basis of 200px.

 

flex Property
The flex property is a shorthand property for flex-grow, flex-shrink, and flex-basis properties.

It can be set as:

flex: 0 0 200px (grow shrink basis)
 

 

align-self Property
The align-self property is used to specify the alignment of the flex item with respect to its container.

This property overrides the container's align-items property. 

It supports all the properties similar to align-items

align-items: stretch
 

Example:
 

1
2
3
Here, the container has align-items set to center and 2nd div has align-self set to stretch overriding the center property.

 

 

Flex-direction
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Flex-wrap
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Flex-flow
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Justify-content
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Align-items
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Align-content
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Order
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Flex-grow
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Flex-shrink
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Flex-basis
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Flex
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Align-self
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Media Queries
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Mobile first web design
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
Breakpoint
https://my.newtonschool.co/course/1v1rva7istnn/template/oxe6o52lgci7/topic-notes/md7vb982jh43
View
