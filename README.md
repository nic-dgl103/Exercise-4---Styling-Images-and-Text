# Exercise 4: Styling Images and Text

## Objectives
Practice styling the content of a webpage using CSS. When you are finished your page could look similar to the example below:</br>
<img src="images/sample-layout.png" width="350">

## Instructions
Remember to:
* Regularly save your files and check out what your web page looks like in a web browser.
* Make regular commits and pushes.
### Step 1: Get set up
* Clone your remote exercise repository onto your local machine.
* Add a comment in the head element of the homepage including: the course code and your section number - your name - Styling Images and Text. Example:
```
<!-- DGL 103 CVS1 - your name - Styling Images and Text -->
```
### Step 2: Style the text
* Change the colours:
  * Give the whole page a background colour of your choice using a HEX value.
  * Change the background colour of the header element to a colour of your choice using an RGB value.
  * Change the colour of all the headings on the page to a colour of your choice using a HEX value.
  * Change the colour of the body copy on the page to a colour of your choice using a HEX value.
  * Change the default colour of the anchor element using a HEX value.
  * The contrast between the background and all the font colours must pass the WebAIM contrast checker test https://webaim.org/resources/contrastchecker/. You will need to run the test three times, once for each font colour. Take screenshots of your test results (you will need to submit them in Brightspace). 
* Change the fonts:
  * Go to https://fonts.google.com/ and find a font family or typeface that is easy to read, select two font weights from that typeface.
  * Copy the link code and paste it in the head of the index file (you may need to first open the side panel in Google Fonts by clicking on the icon of 3 squares in the top right hand corner of the main menu).
  * Copy the font's CSS declaration and, in VS Code, apply it to all the text on the page.
* Change the styling of the text:
  * Apply your two font weights to the content (tip: headings are often bolder than body text).
  * Change the root font size to 62.5%;
  * Change the font size of all the text on the page to the equivalent of 16 pixels using the rem unit.
  * Increase the size of the h1 to the equivalent of 80 pixels using the rem unit.
  * Use the text-transform, font-style, line-height and letter-spacing properties to style any of the content on the page.

### Step 3: Add some images
* Add a logo
  * Add the provided logo image (in the images folder) to the header element. Notice that the logo is a PNG file, this is an appropriate file type for logos with transparent backgrounds.
    * Make the image width 300 pixels using HTML.
* Add an editorial image
  * Download a royalty-free image from this website: https://unsplash.com/. Add the image as an editorial image at the bottom of the page, after the section element. The image must be an appropriate file type and it must be optimized - see your weekly reading for tips on how to optimize an image. 
  * Give the image a caption. 
  * Make the image width 600 pixels using HTML.

### Step 4: Change the layout
* Align all the text on the page to the centre except for the paragraphs.
* Divide the paragraphs into two columns with an automatic width.
* Use the the following declarations to make the layout look like the provided image: `width: 40%; display: inline-block;`
* Resize your browser window to see how the layout of the page shifts with different screen sizes. The image was given an absolute size of 600 pixels in the HTML so it is cut off on a smaller screen. Use CSS to overwrite that dimension and change the image width to 100%, a unit that is relative to the size of its parent element. Resize your browser again to notice the effect.

### Step 4: Format, organize and add comments 
* Use the Prettier VSCode extension to format your code.
* The CSS is so short for this webpage that you don't need to add organizational CSS comments to make it easier to read. Instead, order your CSS style rules in the same hierarchical order as the HTML. Look out for any style rules that you can combine to make the CSS shorter.
* Add a few comments to explain your HTML and CSS code and highlight anything of interest.

### Step 5: Check for errors
* Use the VSCode HTMLHint extension and validate your HTML code to make sure that it is correct: https://validator.w3.org/#validate_by_upload. Take a screenshot of the results.
* Validate your CSS code to make sure that it is correct: https://jigsaw.w3.org/css-validator/ for CSS. Take a screenshot of the results.

**You have now completed your exercise but you still need to push your edits to GitHub and submit it in Brightspace. Make sure to follow the instructions in the How to Complete Your Exercises Guide.**