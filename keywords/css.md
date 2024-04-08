## CSS (Cascading Style Sheet)
### Definition
CSS, or Cascading Style Sheet, is a language used to style HTML or XML documents. It is a stylesheet language standardized across web browsers [^mozilla05css]. CSS gives developpers and designers the power to change the presentation of a webpage/website [^meyer01css]. They can personnalize everything from fonts, to colors, to the layout [^robbins02css]. More experienced developpers can even play around with the behavior of a page. CSS is usually written independently from the HTML files in a file of type ".css". It was created to allow HTML files to be exlusively markup [^g04css] (although it is not mandatory).  

There are 3 ways to add CSS to a webpage [^w3school03css]:
1. **External**: CSS is written in an external file and then linked to its respective HTML file with a \<link> tag within the \<head>. Ex:  
```
<head>  
<link rel="stylesheet" href="thecssfile.css">  
</head>
```
2. **Internal**: CSS is written just as if it was in a separate file, but directly in the HTML file within a <style> tag. Ex:  
```
<style>  
body {  
  color: black;  
  padding: 0px;  
}  
</style>
```
3. **Inline**: CSS properties are written inline with the tag they are directly modifying. This way is usually reserved for properties that need to be prioritized in loading. It is not recommended otherwise as it can reduce code readability. Ex:  
```
<body>  
<p style="color:black; padding:5px;">This is a paragraph.</p>  
</body>
```

### Examples

#### Collage demonstrating the importance of CSS in webpages
![NYT website is not feeling well](images/css-polonsky.png)

[^meyer01css]:Meyer, Eric A. 2006. "CSS: The Definitive Guide: The Definitive Guide." O'Reilly Media, Inc.
[^robbins02css]:Robbins, Jennifer Niederst. 2012. "Learning web design: A beginner's guide to HTML, CSS, JavaScript, and web graphics." O'Reilly Media, Inc.
[^g04css]:G, Domantas. 2023. "What is CSS?" Hostinger, Accessed 27-01-2024, https://www.hostinger.com/tutorials/what-is-css.
[^w3school03css]:W3Schools. "CSS How To." W3Schools, Accessed 27-01-2024, https://www.w3schools.com/css/css_howto.asp.
[^mozilla05css]:Mozilla Developer Network. "CSS - Cascading Style Sheets." Accessed 27-01-2024, https://developer.mozilla.org/en-US/docs/Web/CSS.


