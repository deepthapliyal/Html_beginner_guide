HTML beginners guide : 
# Get started 
HTML stands for Hypertext Markup Language, and it's the standard markup language used to create web pages. HTML is a set of tags and attributes that are used to define the structure and content of a web page. 

Let's get started with the basics of HTML:

# 1. The Document Structure:

Every HTML document begins with a doctype declaration that specifies the version of HTML being used. The doctype declaration should always be the first line of your HTML document.

Here's an example:

```
<!DOCTYPE html>
```

Next, you'll need to add the HTML element that wraps around the entire content of the document. This element is known as the "root" element.

```
<html>
  <!-- your content goes here -->
</html>
```

# 2. Head and Body:

Within the root HTML element, you'll typically see two sections: the head and the body.

The head section contains meta information about the document, such as the title of the page, links to stylesheets, and other metadata.

The body section contains the actual content of the web page.

Here's an example:

```
<html>
  <head>
    <title>My Web Page</title>
  </head>
  <body>
    <h1>Welcome to my web page</h1>
    <p>This is the first paragraph of my web page.</p>
  </body>
</html>
```

# 3. Tags:

HTML uses tags to define the different types of content on a web page. Tags are enclosed in angle brackets and can include attributes that provide additional information about the tag.

For example, the h1 tag is used to create a heading on a web page. Here's an example of how to use it:

```
<h1>This is a heading</h1>
```

The p tag is used to create paragraphs of text. Here's an example:

```
<p>This is a paragraph of text.</p>
```

# 4. Attributes:

Attributes provide additional information about a tag. Attributes are added to the opening tag of an element using the following format:

```
<tagname attribute="value">
```

For example, the a tag is used to create links on a web page. The href attribute specifies the URL that the link points to. Here's an example:

```
<a href="http://www.example.com">Click here</a>
```

# 5. Comments:

Comments are used to add notes to your HTML code that are ignored by the browser. Comments are enclosed in `<!--` and `-->`.

Here's an example:

```
<!-- This is a comment -->
```

# 6. Lists:

HTML allows you to create ordered and unordered lists using the ol and ul tags, respectively. Each list item is contained within an li tag.

Here's an example:

```
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

# 7. Images:

Images can be added to a web page using the img tag. The src attribute specifies the location of the image file.

Here's an example:

```
<img src="image.jpg" alt="An example image">
```

# 8. Tables:

HTML allows you to create tables using the table, tr, and td tags. The table tag defines the entire table, the tr tag defines each row, and the td tag defines each cell.

Here's an example:

```
<table>
  <tr>
    <td>Cell 1</td>
    <td>Cell 2</td>
  </tr>
  <tr>
    <td>Cell 3</td>
    <td>Cell 4</td>
</tr>
</table>
```

# 9. Forms:

HTML forms allow users to input data and submit it to a web server. Forms are created using the form tag, and form elements such as text inputs, checkboxes, and buttons are added using various input tags.

Here's an example:

```
<form>
  <label for="username">Username:</label>
  <input type="text" id="username" name="username">
  
  <label for="password">Password:</label>
  <input type="password" id="password" name="password">
  
  <input type="submit" value="Submit">
</form>
```

# 10. CSS:

HTML alone can create a simple webpage, but to style your page with colors, fonts, and layout, you'll need to use CSS. CSS stands for Cascading Style Sheets, and it's used to define the appearance of web content.

CSS code can be added to an HTML document in several ways, but the most common is to use the `<style>` tag within the head section.

Here's an example:

```
<html>
  <head>
    <title>My Web Page</title>
    <style>
      h1 {
        color: red;
      }
      
      p {
        font-family: Arial;
        font-size: 14px;
      }
    </style>
  </head>
  <body>
    <h1>Welcome to my web page</h1>
    <p>This is the first paragraph of my web page.</p>
  </body>
</html>
```

This example changes the color of the h1 tag to red and sets the font family and size for all p tags.

Congratulations! You now have a basic understanding of HTML. With this knowledge, you can start creating your own web pages.
