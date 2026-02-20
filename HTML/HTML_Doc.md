If you write any text in an HTML file without using tags, the browser will still show it. However, this has a few limitations.

In the beginning, browsers only displayed plain text. The concept of "Tags" was created to solve this. Tags help to organize and customize that text so it looks like a proper, beautiful web page.

For example, imagine you press "Enter" to start a new line in Notepad. The browser does not understand this. It will just put all the words together on one long line.

HTML tags were created to fix this problem. Tags are special instructions for the web browser. They tell the browser exactly how to show the content.

Here are the main reasons we use HTML tags:

- **Structure:** They tell the browser what is a heading (`<h1>`) and what is a paragraph (`<p>`).

- **Style:** They change how text looks. You can make text bold (`<b>`) or italic (`<i>`).

- **Function:** They turn plain text into a link (`<a>`) that you can click.

- **Media:** They allow you to add pictures and videos to your web page.

### The Nature of HTML Tags
All HTML tags are written inside angle brackets.
- They start with this symbol: <
- They end with this symbol: >

Two Types of Tags
Depending on how they are built, tags are divided into two main groups:

**1. Container Tags:**

These act like a box.
They have a starting tag (like `<h1>`).
They have an ending tag (like `</h1>`). Notice the slash (/) in the ending tag.
You put your text in the middle between them.

Examples: `<html>...</html>, <body>...</body>`

**2. Empty Tags (or Void Tags):**

These do not act like a box.
They do not have an ending tag.
They do not hold text inside them.
They just do one specific action.

Examples: `<br>` (moves to a new line), `<hr>` (draws a horizontal line), `<img>` (shows a picture).

![alt text](<Screenshot From 2026-01-26 12-17-25.png>)

![alt text](<Screenshot From 2026-01-26 12-17-44.png>)

### Understanding `<!DOCTYPE html>`
The very first line in your code is `<!DOCTYPE html>`. This is not an HTML tag. It is an instruction (called a declaration) for the web browser.

Here is what it does:
- Tells the Version: There are many older versions of HTML. This line tells the browser that you are using HTML5, which is the newest version.
- Sets the Rules: It helps the browser understand the newest rules so your web page loads correctly.

**Key Features of DOCTYPE**
- Location: It must always be the very first line of your document. It goes at the top, right above the `<html>` tag.
- Not a Tag: Remember, it is just a message to the browser, not a real tag.
- Case Insensitive: You can use capital letters or small letters. Both `<!DOCTYPE html>` and `<!doctype html>` work perfectly fine.

### Understanding the `<html>` Tag
Every HTML document starts with the `<html>` tag and ends with the `</html>` tag.

Here are the most important things to know about it:
- The Root Element: The `<html>` tag is called the "root element." This means it is the main container for everything else.
- Like a Book Cover: Think of these tags like the front and back covers of a book. All the other code for your web page must go inside them.
- Guides the Browser: It shows the browser exactly where the web page begins and where it ends.
- Identifies the File: When the web browser sees this tag, it immediately knows that it is reading a real HTML page, and not just a normal text file.
