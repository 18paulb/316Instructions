# Creating and editing a simple web page
In this day and age, everything requires a website. Through these instructions, you will learn basic editing of HTML and CSS, the building blocks of websites. You will be using a website called codepen, in which there will be three sections titled HTML, CSS, and JS. The simple web page will be displayed underneath. You will be editing the HTML and CSS sections.

# Requirements:
1. A computer
2. A stable internet connection

# Instructions

1. Open this link in a new tab: https://codepen.io/18paulb/pen/abeOKgd

### Altering Name Heading
1. On the left-hand section titled "HTML", go to the text that says "Hello {Name}".
2. Replace "{Name}" with your name

-- Add picture of name being replaced

3. Go to the middle section titled "CSS" and find the block of code that says
   ```
   .box {
    font-size: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
   }
   ```
4. Change the font-size section from 10px; to a number in the range of 50px and 100px

### Changing The Image
1. Go to Google Images and search up an appropriate image of your choice.
2. Right click and choose "Copy Image Link" or "Copy Image Address" from the dropdown menu.
3. Navigate back to CodePen, in the HTML Section, find where it has this code
```
    <img class="photo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/15/Cat_August_2010-4.jpg/1200px-Cat_August_2010-4.jpg">
```
4. Replace the url found in this code to be the url that you copied from Google Images.


### Changing Body Text
1. Go to HTML Section of CodePen and find where it has this code
```
<p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."
</p>
```
2. Change the text inside of the `<p></p>` tags to be a description of how your day was today

### Changing Background Color
1. Go to CSS Section of CodePen
2. Find where this code section
```
body {
  font-family: system-ui;
  background: orange;
  color: white;
  text-align: center;
}
```
3. Alter the background value and change the word "orange" to "green"
