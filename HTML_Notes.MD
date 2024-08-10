# HTML Notes

---

## 1. Introduction to HTML

**HTML** stands for HyperText Markup Language. It is used to structure content on the web. HTML elements are the building blocks of HTML pages. These elements are represented by tags.

### Basic HTML Document Structure

An HTML document starts with a `<!DOCTYPE html>` declaration followed by the `<html>` tag. Here’s the basic structure of an HTML document:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html> 
```
### **Note** : The basic HTML structure includes several important elements:

`<!DOCTYPE html>`: This declaration defines the document type and HTML version. It helps browsers render the page correctly.    
`<html>`: The root element of an HTML document.   
`<head>`: Contains metadata, including the character set, viewport settings, and links to external resources like CSS.  
`<title>`: Sets the title of the page, which appears in the browser tab.  
`<body>`: The section where the visible content of the page is placed.

### Tip: Make sure to use proper indentation and structure within the `<body>` tag to keep your content organized and readable.

## 2. Common HTML Tags
### Headings
Headings are used to define titles and subtitles on a web page. They help organize content and improve accessibility.

**Syntax**
```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
<h3>Sub-subheading</h3>
```
### Paragraphs
Paragraphs are used to define blocks of text.

**Syntax**
```html
<p>HTML is the standard markup language for creating web pages.</p>
```
**Note**: Ensure paragraphs are used to separate distinct sections of text for better readability.

### Links
Links allow users to navigate to other pages or resources.

**Syntax**
```html
<a href="https://www.google.com">Search on Google</a>
```
**Tip**: Use descriptive link text to improve accessibility and SEO.


### Images
Images are included using the `<img>` tag.

**Syntax**
```html
<img src="https://www.example.com/logo.png" alt="Example Logo">
```
**Note**: Always include an alt attribute to provide text for screen readers and improve SEO.

### Lists
Lists can be either ordered or unordered.

**Unorder List**
```
- HTML
- CSS
- JavaScript
```
**Order List**
```
1. Install VS Code
2. Learn HTML
3. Practice Coding
```
### Tables
Tables organize data into rows and columns.

**Syntax**
```
| Name      | Age  |
|-----------|------|
| John Doe  | 30   |
```
**Note**: Ensure tables are used for data and not for layout purposes.

## 3. Forms in HTML
Forms collect user input.

### Basic Form Structure
**Syntax**
```html
<form action="/submit-form" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    <input type="submit" value="Submit">
</form>
```
**Note**: Use proper form elements and attributes to ensure functionality and accessibility.

## 4. Multimedia in HTML
 ### Embedding Videos
Use the `<video>` tag to include videos.
**Syntax**
```html
<video controls>
    <source src="movie.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```
### Embedding Audio
Use the `<audio>` tag to include audio files.

**Syntax**
```html
<audio controls>
    <source src="audio.mp3" type="audio/mp3">
    Your browser does not support the audio element.
</audio>
```
### Embedding iframes
Use the `<iframe>` tag to embed other web pages.

**Syntax**
```html
<iframe src="https://www.example.com" title="Example Site"></iframe>
```
## 5. Semantic HTML
Semantic HTML tags describe the purpose of the element.

`<header>`: Defines a header for a document or section.   
`<nav>`: Defines a navigation container.  
`<main>`: Defines the main content.   
`<footer>`: Defines a footer.  
`<article>`: Defines independent content.   
`<section>`: Defines a section in a document.
```html
<header>
    <h1>Welcome to My Website</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
</header>
<main>
    <article>
        <h2>About HTML</h2>
        <p>HTML is the standard markup language for creating web pages.</p>
    </article>
    <section>
        <h2>More Information</h2>
        <p>You can learn more about HTML on the official documentation website.</p>
    </section>
</main>
<footer>
    <p>Contact us: info@example.com</p>
</footer>
```
**Note**: Use semantic tags to improve the structure and accessibility of your content.

## 6. Best Practices


• **Use Semantic HTML**: Improves accessibility and SEO.
• **Keep Your Code Organized**: Consistent indentation and spacing.
• **Optimize Images**: Use appropriate formats and compression.
• **Validate Your HTML**: Use validators to check for errors.
• **Use External Styles and Scripts**: Keep HTML clean.

## 7. Useful Resources
[Visit MDN Web Docs-HTML](https://developer.mozilla.org/en-US/docs/Web/HTML "Go to MDN Reference")
[HTML Validator - W3C](https://validator.w3.org/ "Go to Google")
```

### **Explanation**

- **Inline Notes**: You can add notes immediately after the code blocks using regular text.
- **Additional Tips and Notes**: Add explanatory notes or tips to provide context or best practices. You can use **bold** or **italic** for emphasis.
- **HTML within Markdown**: For advanced styling or layout, you can use HTML directly within Markdown files if needed.

This approach keeps your Markdown organized and ensures that notes and explanations are clearly separated from the code blocks.
```
# THANK YOU !

