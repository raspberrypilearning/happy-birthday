## Making a birthday card

Let's use what you've learnt about HTML and CSS to make your own custom birthday card.

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/happy-birthday-starter2" width="600" height="450" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>

--- task ---

Open the second [Happy Birthday starter project](https://editor.raspberrypi.org/en/projects/happy-birthday-starter2){:target="_blank"}.

--- /task ---

We've written a lot of code to get you started, but the birthday card looks pretty boring so far, so you're going to make some changes to the HTML and CSS code.

--- task ---

Click **Run** and then the button on the front of the card, and you should see it open to reveal the inside.

--- /task ---

--- task ---

Go to line 14 of the HTML code. Try editing the text to customise your card.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 13
line_highlights: 14
---
      <p id="outside-title">
        Happy Birthday 🎉🎂🎉🎁🎉
      </p>
--- /code ---

--- /task ---

--- task ---

Can you find the HTML code for the robot image, and change the word `robot` to `sun`?

--- /task ---


--- hints ---
--- hint ---

Look on line 17 to find the code and change the word `robot` to `sun`. You'll see the image change when you click on **Run**

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 13
line_highlights: 17
---
      <p id="outside-title">
        Happy Birthday 🎉🎂🎉🎁🎉
      </p>

      <img id="outside-pic" src="sun.png">
--- /code ---

--- /hint ---
--- /hints ---

You can use any of the words `boy`, `diamond`, `dinosaur`, `flowers`, `girl`, `rainbow`, `robot`, `spaceship`, `sun`, `tea`, or `trophy` for a birthday card, or `cracker`, `elf`, `penguin`, `present`, `reindeer`, `santa`, or `snowman` if you would prefer to make a Christmas card.

You can also edit the CSS code of the birthday card.

--- task ---

Click on the file for `style.css`. The first part is all of the CSS styles for the **outside** of the card.

--- /task ---


--- task ---

Change the `background-color` to `lightgreen`.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 4
---
#outside {
  z-index: 1;
  position: absolute;
  background-color: lightgreen;
  width: 100%;
  height: 100%;
--- /code ---

--- /task ---

--- task ---

You can also change the size of an image. Go to the `#outside-pic` CSS code, and change the `width` and `height` of the outside image to `200px` (`px` stands for pixels).

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 23
line_highlights: 24-25
---
#outside-pic {
  width: 200px;
  height: 200px;
}
--- /code ---

--- /task ---

--- task ---

The font can be changed too. Go to the `#outside-title` CSS and change the `font-family` to `Comic Sans MS` and the `font-size` to `16pt`.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 16
line_highlights: 18, 19
---
#outside-title {
  color: black;
  font-family: Comic Sans MS;
  font-size: 16pt;
  text-align: center;
}
--- /code ---

--- /task ---

You can use other fonts, for example:
+ `<span style="font-family: Arial;">arial</span>`
+ `<span style="font-family: impact;">Impact</span>`
+ `<span style="font-family: tahoma;">Tahoma</span>`
