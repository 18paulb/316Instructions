# Creating and Editing a Simple Webpage

# Introduction
In this day and age, everything requires a website. Through these instructions, you will learn basic editing of HTML and CSS, the building blocks of websites. 

You will be using a website called CodePen, in which there will be three sections titled HTML, CSS, and JS. The webpage will be displayed underneath. You will be editing the HTML and CSS sections.

![codepen full screenshot](./Introduction.jpg)

# List of Requirements:
1. A computer
2. A stable internet connection

# Numbered Steps


### Preparation Steps
1. Open this link in a new tab: https://codepen.io/18paulb/pen/abeOKgd
2. Out of three tabs opened —**HTML**, **CSS**, and **JS**-click the drop down menu in the top right corner.
3. Select `Minimize Javascript Editor` from the dropdown. We will not be using the JS tab.


### Altering Name Heading
1. In the HTML section (on the left), find the text that says `Hello {Name}`.
2. Replace `{Name}` with your name.
3. In the CSS section (on the right), find the following code:
   ```
   .box {
    font-size: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
   }
   ```
4. Change the line that says `font-size: 10px;` to say `font-size: 40px;` (make sure to keep the semicolon)
5. The header should get larger automatically after a few seconds.

The updated page should look similar to this:
![changed header](./images/changedHeader.png)

### Changing The Image=
1. In the HTML Section, find this line:
```
    <img class="photo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/15/Cat_August_2010-4.jpg/1200px-Cat_August_2010-4.jpg">
```
2. Delete the url found after the `src=` and put in this new url `https://brightspotcdn.byu.edu/31/bf/faa1cee3405387ff8d0d135ffab1/1810-23-0021-1200-4.jpg` (make sure that you have quotes around the link).

The updated page should look similar to this:
![changed image](./images/changedImage.png)

### Changing Background Color
1. In the CSS section, find this code:
```
body {
  font-family: system-ui;
  background: orange;
  color: white;
  text-align: center;
}
```
2. Change the background color by changing `background: orange;` to `background: green;` (make sure not to delete the semicolon at the end of the line)
3. If you'd like, you can try using a different color than green.

The updated page should look similar to this:
![changed background](./images/changedBackground.png)

# Comments, Notes, and Examples

# Troubleshooting
 - If the image you chose from Google Images isn't showing up:
    - Make sure the image link is surrounded by quotes: `"www.example.com/image"`
    - Choose a new image to try instead.
 - If any changes aren't showing up:
    - Check the CSS section for any missing semicolons at the end of lines.
    - Check the HTML section and make sure you haven't deleted any of the tags (things in `<>` brackets)

# Hazard Statements

### ⚠️ Caution ⚠️
If you refresh the CodePen page, you will lose all your progress.

# Conclusion
**Congratulations!** 

By following these steps, you have successfully edited a simple webpage. You’ve learned the basics of using HTML and CSS. Through this exercise, you’ve explored fundamental techniques such as... 

1. Modifying text
2. Changing images
3. Updating body content
4. Altering background colors

These basic steps provide a starting point for editing and personalizing websites. With a bit of practice, you can try making more changes and exploring other features of HTML and CSS to further customize webpages as you become more comfortable with the process.

### Survey
Let us know how you did! Take our survey here: https://forms.gle/XGoQfi4BTCYuYp6V6
