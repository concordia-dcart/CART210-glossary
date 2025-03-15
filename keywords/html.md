## HTML

### Intro
The HyperText Markup Language (HTML) is the building block of the web that constitutes the backbone of all web pages. It is accompanied by CSS (Cascading Style Sheets) and JavaScript (JS) as one of the core web technologies of the World Wide Web. Whilst CSS takes care of styling and JavaScript takes care of interactivity, HTML establishes the structure that holds everything together.[^ebersbach01html]

HTML employs an element-based method of marking up content to arrange web content. Tags are what are used to mark different types of content like headings, paragraphs, images, links, and interactive elements like forms. HTML is one of the foundation web construction languages of the contemporary web and as such is the base language for any web applications or web-site construction. [^ebersbach02html] To a callback of the keyword "CSS" as the frosting of the cake web, HTML is consider the base of the cake of the web.


### A Brief History of HTML
HTML was developed in 1991 by Tim Berners-Lee as a way of formatting and linking web documents. HTML in the early days was not too complicated, with minimal tags for formatting the text and for linking one document to another. With the growth of the web came the growth of HTML.[^ebersbach01html]

- **HTML 2.0 (1995):** The first standardized version, introduced basic form elements. [^ebersbach01html]
- **HTML 3.2 (1997):** Brought table support and basic scripting.
- **HTML 4.01 (1999):** Expanded capabilities with improved styling and multimedia support.
- **XHTML (2000):** Introduced stricter syntax and compliance with XML rules.
- **HTML5 (2014 - Present):** Revolutionized web development with native support for multimedia, semantic elements, and APIs for modern web applications.

The most recent standard is HTML5, constantly updated to keep up with new web technologies and users' expectations. HTML has become essential for web platforms like Wikipedia and Google Docs applications where web-based interfaces and structured content are defining modern digital experiences. [^ebersbach03html]


### How to Structure HTML
At its core, an HTML document follows a standard structure:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Webpage</title>
  </head>
  <body>
    <h1>Welcome to My Website</h1>
    <p>This is a simple paragraph.</p>
  </body>
</html>
```


#### Breaking It Down
- **`<!DOCTYPE html>`**: Declares the document type and version of HTML.
- **`<html>`**: The root element that wraps all content.
- **`<head>`**: Contains metadata like the page title and linked stylesheets.
- **`<title>`**: Sets the page title visible in the browser tab.
- **`<body>`**: Holds the visible content of the webpage.
- **`<h1>` and `<p>`**: Define a heading and a paragraph.



### Real-World Example: The Rise of Blogging Platforms
One significant impact of HTML has been its role in the rise of blogging platforms. Early platforms like **Blogger (1999)** and **WordPress (2003)** utilized HTML to structure user-generated content, allowing people with little to no coding knowledge to publish their thoughts online. These platforms made use of HTML elements such as `<h1>` for post titles, `<p>` for paragraphs, and `<img>` for embedding images, making web publishing accessible to a broader audience. The growth of blogging significantly influenced digital journalism, online marketing, and social media platforms. [^ebersbach05html]



### HTML and CSS: Connecting the Dots
While HTML structures content, CSS is used to style it. You can link an external CSS file to an HTML document using the `<link>` tag within the `<head>` section:

```html
<head>
  <link rel="stylesheet" href="styles.css" />
</head>
```

This method ensures a clean separation between structure and design, making it easier to maintain and update web pages. [^ebersbach04html]




[^ebersbach01html]: Berners-Lee, Tim. 1991. *[WorldWideWeb: Proposal for a HyperText Project](https://www.w3.org/History/1991-WWW-NeXT/)*. Accessed January 21, 2025.  
[^ebersbach02html]: Duckett, Jon. 2011. *HTML & CSS: Design and Build Websites*. Indianapolis: Wiley, pp. 23-45.  
[^ebersbach03html]: Meyer, Eric. 2018. *HTML5 for Web Designers*. Sebastopol, CA: O'Reilly Media, pp. 78-102.  
[^ebersbach04html]: Krug, Steve. 2020. *Don't Make Me Think, Revisited*. 3rd ed. Berkeley: New Riders, pp. 12-30.  
[^ebersbach05html]: Blood, Rebecca. 2002. *The Weblog Handbook: Practical Advice on Creating and Maintaining Your Blog*. Cambridge, MA: Perseus Publishing.  



![HTML](images/html_ai.jpg) 
Caption: Used ChatGPT, prompt: Create an image that represents html
