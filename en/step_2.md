## What is HTML?

HTML stands for **Hypertext Markup Language**, the language used to make webpages. Let's have a look at an example!

--- task ---

Open the [Happy Birthday starter project](https://editor.raspberrypi.org/en/projects/happy-birthday-starter){:target="_blank"}.

--- /task ---

--- task ---

The code that you can see on the left is HTML. When you click **Run**, you can see the webpage that the HTML code has made on the right.

--- /task ---


HTML uses **tags** to build webpages. Look for this HTML code on line 8 of your code:

```html
<p>Hi. My name is Andy.</p>
```

`<p>` is an example of a tag, and is short for **paragraph**. You can start a paragraph with `<p>`, and end a paragraph with `</p>`.

--- collapse ---
---
title: Can you spot any other tags?
---
One other tag you might have spotted is `<b>`, which stands for __bold__:

```html
<b>running</b>
```

Here are some more:

+ `<html>` and `</html>` mark the start and end of the HTML document
+ `<head>` and `</head>` is where stuff like CSS goes (we'll get to that later)
+ `<body>` and `</body>` is where your website content goes

![screenshot](images/birthday-head-body.png)

--- /collapse ---

--- task ---

Make a change to one of the paragraphs of text in the HTML file (on the left). Click **Run**, and you should see your webpage change (on the right)!

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 7 
line_highlights: 8
---
  <body>
    <p>Hi. My name is Nic.</p>
    <p>I like <b>running</b> and <i>riding my bike</i>.</p>
  </body>
--- /code ---

--- /task ---

If you have made a mistake and want to undo all of your changes, you can press and hold the **Ctrl**, then press the **z** key.

### You need an account to save your projects!

If you have a Raspberry Pi account, the easiest way to save your webpage is to click the **log in to save** button on the top right of the project. This will save a copy of the on your profile.

If you do not yet have a Raspberry Pi account you can create one at [my.raspberrypi.org](https://my.raspberrypi.org/signup).
