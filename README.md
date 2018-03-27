# Web Starter Lesson 1

## Contents
- [Overview](##Overview)
- [HTML](##HTML)
  - [The Main HTML Components](###TheMainHTMLComponents)
  - [Exercies](###HTMLExercies)
- [CSS](##CSS)
  - [Exercies](###CSSExercies)

## Overview
This project will help you become familiar with HTML (Hyper Text Markup Language) and CSS (Cascading Stylesheets). By the end of the project you will have a simple static webpage. 

## 1. HTML
HTML is a considered a declairative language, meaning it is used to describe only what is displayed on a page. It does not describe the control flow for rending the page or the pages possible interactions with a user.
### The Main HTML Components

The `index.html` found in the project contains some basic components that should be included in all html documents. The contents should look like this:
``` html
<!DOCTYPE html>
<html>
<head>
    <title>Hello, World!</title>
</head>
<body>
    <!-- this is a comment -->
    <h1>Hello, World!</h1>
    <p>This is a paragraph</p>
</body>
</html>
```

* `<!DOCTYPE html>` - This is a declairation, not a tag. This tells the broswer which html version to use to interpret the all of the tags within the document. This declairation must be the first thing in the html document.

* `<html></html>` - This tag tells the browser this is an html document. This is important for the broswer to know how to interpret tags within the document, and ultamatly how to display or render the page to the user.

* `<head></head>` - the head tag is the container for head elements. These tags have varied purposes, and we will go into more depth on these later. 

* `<title></title>` - This is pretty self-explainitory. It is used to git your html document a title.

* `<body></body>` - All of the content that will be displayed on your webpage will be defined within the body tags.

* Other tags - Tags like `<h1>`, `<p>` and many more are used to give the content within some predefined styling. As you become familair with HTML, you will see more and more tags, and develop and understand of the use of each tag.

These are the basics of HTML. There are thousands of free resoures availible to learn more HTML. Use those resources for rerference and learning. Here are a few I have found to be useful.

* [W3Schools - HTML](https://www.w3schools.com/html/default.asp)
* [MDN - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

### HTML Exercies
1. Make `index.html` a document about you, using heading tags (`<h1>`, `<h2>` ...), paragraph tags (`<p>`), list tags (`<ol>`, `<ul>`), and link tags (`<a>`). Create a section talking about your hobbies. Make an unordered list of things you would like to do at some point in your life. Make an ordered list of your favorite food.

2. Find a picture you like and use the image tag to display it on your page.

3. Create a new HTML document that tells your favorite fable or short story. Include pictures and links. Link to your new page from `index.html`.

## CSS
CSS is a lnaguage that is used to describe the style of a webpage elements. Style includes things like positioning, size, color, etc.

### Selectors
CSS selectors can be generally thought of as identifiers for which elements a set of stylings should be applied to.

For an example of a selector we will use this line of HTML.
``` html
<div>
    <h1 class="greeting">Hello!</h1>
    <p id="introduction">My name is faradayfan. Nice to meet you!.</p>
</div>
```

There are several types of selectors available.

* elements - You can select any elements simply by specifying the element like this:
``` CSS
p {
    color: pink;
}
```

* class - when an HTML element has a class attribute, that class can be referenced in CSS like this: 
``` CSS
.greeting {
    color: pink;
}
```
Notice the `.` before the class name.

* id - when an HTML element has a id attribute, that id can be referenced in CSS like this: 
``` CSS
#id {
    color: green;
}
```

There are more selectors, but these are a good start.

### Properties
CSS Properties are essentially the set of stylings that can be applied to and element. There are many properties. Spend some time becomming familiar with the different ways elements, text and pictures can be styled using CSS. 

### CSS Exercies

1. Add some background color to your pages. Keep in mind the old saying, a little goes a long way.
2. Color your text with a color that fits with your background. I like to use tools to help with the color scheme like [coolors](https://coolors.co/app).
3. Add some borders to help structure the look of your web pages. Look for examples of how other websites use borders.
4. Try to change a style when the cursor hoovering over an element. 