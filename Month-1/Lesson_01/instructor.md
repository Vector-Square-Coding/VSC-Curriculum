# **Week 1: Introduction to HTML Basics**

## **Learning Objectives**
By the end of this session, you will:
- Understand the basic structure of an HTML document.
- Identify and use essential HTML tags, such as `<html>`, `<head>`, `<body>`, `<h1>`-`<h6>`, `<p>`, `<ul>`, `<ol>`, and `<a>`.
- Create a basic webpage with headings, paragraphs, lists, and links.

---

## **Glossary**
Familiarize yourself with these key terms:

- **HTML (HyperText Markup Language)**: The standard language used to create and structure content on the web.
- **Tag**: A keyword surrounded by angle brackets (`< >`) that defines an HTML element (e.g., `<h1>`).
- **Element**: The combination of a start tag, content, and an end tag (e.g., `<h1>Welcome</h1>`).
- **Attribute**: Additional information added to a tag to customize its behavior (e.g., `href` in `<a href="https://example.com">`).
- **Headings**: Tags used to define headings on a webpage (`<h1>` to `<h6>`).
- **Paragraphs**: Tags that define blocks of text (`<p>`).
- **Lists**: Tags used to organize content into lists (`<ul>` for unordered, `<ol>` for ordered).
- **Anchor Tag (`<a>`)**: A tag used to create hyperlinks.

---

## **Coding Exercise**

### **Goal**
Create a simple webpage that introduces yourself using the HTML tags we learned.

### **Instructions**
1. Open your code editor (e.g., Visual Studio Code) and create a file named `index.html`.
2. Copy and paste the following starter code into your file:
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>My First Web Page</title>
    </head>
    <body>
        <!-- Your content goes here -->
    </body>
    </html>
    ```
3. Inside the `<body>` section:
   - Add an `<h1>` heading with your name.
   - Add a `<p>` paragraph describing yourself (e.g., your hobbies or interests).
   - Create an unordered list (`<ul>`) of your favorite hobbies or interests.
   - Add a hyperlink (`<a>`) to your favorite website.

4. Save the file and open it in a web browser to view your webpage.

---

## **Expected Output**
When viewed in a browser, your webpage should resemble the following:

John Doe
Hi! My name is John, and I love exploring new technologies.

Hobbies:
	•	Reading
	•	Hiking
	•	Gaming

---

## **Exit Ticket**
Reflect on what you learned today:
1. What is the purpose of the `<html>`, `<head>`, and `<body>` tags in an HTML document?
2. How do you create a hyperlink in HTML?
3. What is the difference between an unordered list (`<ul>`) and an ordered list (`<ol>`)? 

Write your answers below and submit them at the end of the session.
   # **Week 1: Introduction to HTML Basics**

## **Answer Key for Exit Ticket**

1. **What is the purpose of the `<html>`, `<head>`, and `<body>` tags in an HTML document?**

   - `<html>`: This tag defines the root of an HTML document. It wraps all the content of the page and indicates that the file is an HTML document.
   - `<head>`: This section contains metadata about the document, such as the title, character set, and links to stylesheets or scripts. It does not display on the webpage itself.
   - `<body>`: This section contains all the content that will be visible to users in the browser, such as text, images, lists, and links.

2. **How do you create a hyperlink in HTML?**

   - Use the `<a>` tag along with the `href` attribute to specify the link's destination. For example:
     ```html
     Use Liver Server extention to view  My First Web Page 
     ```

3. **What is the difference between an unordered list (`<ul>`) and an ordered list (`<ol>`)?**

   - `<ul>`: Creates a list with bullet points, where the order of the items does not matter.
   - `<ol>`: Creates a numbered list, where the order of the items is significant.

---

## **Expected Code Example**

Below is an example solution for the coding exercise:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Web Page</title>
</head>
<body>
    <h1>John Doe</h1>
    <p>Hi! My name is John, and I love exploring new technologies.</p>
    
    <h2>Hobbies:</h2>
    <ul>
        <li>Reading</li>
        <li>Hiking</li>
        <li>Gaming</li>
    </ul>
    
    <p>Visit <a href="https://example.com">My Favorite Website</a></p>
</body>
</html>