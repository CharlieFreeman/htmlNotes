# HTML and  CSS NOTES

## HTML

## What is HTML?
“HyperText Markup Language”

### Chapter 1 "Structure"

Elements in html are call tags. Every element is placed inside of &lt; &gt;

| *element* | *What it Does* |
| --- | --- |
| html | Document type |
| title | Anything typed here will appear in the top part of the users browser |
| head | Has info on document such as titles, links, stylesheets |
| body | What is displayed in the browser |
| title | Title of the page |
| p | paragraphs |

### Chapter 2 "Text"

| *element* | *What it Does* |
| --- | --- |
| h1-6 | Different headings 1 being most important "larger text" - 6 being the lest important "smallest text". |
| b | bold |
| i | italic |
| sup | superscript |
| sub | subscript |
| br | breaks onto a new line |
| hr | breaks onto a new line but used for things such as a new chapter in a book |
| em | emphasis placed on text |
| blockquote | Used for block quotes in text. It indents your text. Note: the paragraph "p" element is still used inside of a block quote. |
| q | Is used for short quotes |
| strong | Implies strong emphasis to text. Looks kinda like bold. |
| abbr | Is used to abbreviate acronyms. |
| cite | For citing works. |
| dfn | To define terms |
| address | For details about the author such as a physical or web address. |
| del | Shows text that is deleted. |
| ins | Underlines text. |
| s | Line through text. |

### Chapter 3 "Lists"

| *element* | *What it Does* |
| --- | --- |
| ul | Unordered list. To list single items use li |
| ol | Ordered list. To list single items use li |
| table | Creating a table. |
| th | Table Head |
| tr | Table Row |
| td | Table Data |
| Semantic Tags for Tables | Such as "table", "thead", "tbody", and "tfoot". Helps to organize your table better for later use. |

| *Definition List Element* | *What it Does* |
| --- | --- |
| dl | For starting a definition list |
| dt | For the term. |
| dd | For containing the definition of the term. |

Note: You can have list nested inside of each other.

### Chapter 4 "Links"

| *element* | *What it Does* |
| --- | --- |
| a | Anchor used for redirecting the user to specific areas. |
| a href | Redirecting to a url or file.|
| mailto | To create a link that opens someones email.  For Example: &lt;a href-"mailto:charlie.freeman@ksquarelabs.com"&gt; Email Charlie&lt;/a&gt; |
| target | Opens a new window. Example: &lt;a href-"http://theartofdesignstudio.com" target-"_blank"&gt;The Art of Design&lt;/a&gt;|
| id | Links to a specific part of a page for example: &lt;h1 id-"top"&gt;Top of Page&lt;/h1&gt; Note: the "top" is actually what the button is called by html and what it knows to link to. The "Top of Page" is what the button looks like. |
The value of the href attribute starts with
the # symbol Example: &lt;a href="#top"&gt;Top&lt;/a&gt;

### Chapter 5 "Images"

| *element* | *What it Does* |
| --- | --- |
| img src | Linking images |
| alt | Text description of the image. |
| title | To give additional info. |
| Width & Height | &lt;img src="imagePlace.jpg" alt -"title of image " width="600" height="300"/&gt; Note: Is measured in px. |
| figure | Can have more than one image & info. |
| figcaption | Creates text as a caption. |

Note: Images must be saved as .jpeg, .gif, .png.
Resolution for web is 72 ppi.

Stock photos:
www.istockphoto.com,
www.gettyimages.com,
www.veer.com,
www.sxc.hu,
www.fotolia.com

### Chapter 6 "Tables"

| *element* | *What it Does* |
| --- | --- |
| table | Creating a table. |
| th | Table Head |
| tr | Table Row |
| td | Table Data |
| td colspan | Expands the column out by "number here". Example &lt;td colspan="2"&gt;Geography&lt;/td&gt; |
| tb rowspan | Expands the row by "number here" &lt;td rowspan="2"&gt;Movie&lt;/td&gt;|
Long Tables - can be divided by thead, tbody, and tfoot. This keeps your table organized. Also having it this way makes it more clear when read with a screen reader.

### Chapter 7 "Forms"

| *element* | *What it Does* |
| --- | --- |
| form | Used for gathering information. Also what your form controls will go into. |
| action & method | Every form requires an action. Two different types of methods such as get and post. Example: &lt;form action="http://www.example.com/subscribe.php"method="get" &gt; |
| id | Used to identify other elements. |
| input | To create different controls such as type="text", name="something", size="2", maxlength="16" |
| textarea | &lt;textarea name="comments"&gt;Comments Here&lt;/textarea&gt; |
| cols & rows | Used in older versions. How many spaces horizontaly and vertically text will take up. |

"Get" method is good for short forms and retrieving data from the web server. "Post" method is good for users uploading files, very long, has sensitive data, and/or add/deletes info from a database.

| *Inputs* | *What it Does* |
| --- | --- |
| type="password" | Characters are blocked out. |
| name="password" | name of password input |
| maxlength="12" | Is used to limit the amount of characters used.|
| size="2" | Displays the a specific number of characters but you can add more. |
| type="radio" | Where the user can pick just one out of a number options. |
| checked | Which value if any selected when the page loads. Note: pg 155|
| type="checkbox" | Allows users to select one or more options. Example: &lt;input type="checkbox" name"service" value type="itunes" checked="checked" /&gt; iTunes (pg:156)|
| select name="Dogs" | Creates a drop down box. |
| option | Different option the user can choose from. Example: &lt; option value="german"&gt;German&lt;/option&gt; This is only one option; you can create multiple options in the select form.|
| &lt;select&gt; | Show more than one option to be selected. |
| multiple | Allows the user to select more than one option. (pg:158)|
| input | User can upload a file. type="file" is a text filed with a Browse button. Example: &lt;input type="file" name="user" /&gt;|
| | input type="submit" will send a form to the server. |
| type="image" | Using an image as a button. Example: &lt;input type="image" src="bla.jpg" width="100" height="20" /&gt;
| button | Allows other elements to appear inside the button; for example an image. |
| type="hidden" | Not shown on the page but can be viewed if you use the View Source option. |
| label | This is good for vision-impaired users. Should be placed before each form control. |
| fieldset | Grouping related controls together |
| legend | Identifies the purpose of the group form. |
|| Example: &lt;fieldset&gt; &lt;legend&gt; Group of controls are place here. &lt;/fieldset&gt;

| *HTML 5: Form Validation and How it's done* |
| :---: |
| required="required" |
|&lt;input type="text" name="username" required="required"/&gt;

Date Input: &lt;input type="date"/&gt;

| Email & URL Input |
| --- |
| input type="email" |
| input type="url" |
| For reference pg 167 |

Search Input: &lt;input="search" name="search" placeholder="Enter keyword"/&gt;

placeholder: For placeholder text. Ex: There until the user clicks to place their info.

### Chapter 8 "Extra Markup"

For HTML5 you use &lt;!DOCTYPE html&gt; at the top of your document to declare which version of html you will be using.

| elements | How they're written and/or what it does. |
| --- | --- |
| comments | &lt;!-- comment goes here --&gt; |
| id attribute | Used to uniquely identify that element from other elements on the page. |
| class attribute | A way to identify multiple elements. |
| block elements | Always start on a new line. Example of block elements are h1, p, ul, li |
| inline elements | Always continue on the same line. Example of inline elements are a, b, em, img. |
| div | Allows you to group a set of elements together in one block-level box. pg:187 |
| span | To differentiate text from surrounding text, contain a number of inline elements, or for controlling the appearance in CSS.
| iframe | A smaller window that has been cut into your webpage. Kinda like a map on you business page.
| scrolling | You can scroll around the map. |
| frameborder | adds a border. |
|seamless | Allows you to move around seamlessly (all directions). |
| meta | Not visible to users and gives info to search engines about your page such as who created it. |

### Chapter 9 "Flash, Video & Audio"

To add a Flash Video to your web page: 1: Convert your video into FLV format. 2: Find an FLV player to play the video. 3: Include the player & video in your page. (Can do this using JavaScript.) Example of code: pg 212

&lt;Video&gt; uses src, poster: image posted until vid is played, width/height, controls, autoplay.

&lt;source&gt; location of the file to be played. Can use source inside of the video element. Can contain attributes such as src, type, codecs.

Adding audio (MP3) to web pages: 1:Use a hosted service. 2: use flash 3: use of html5
&lt;audio src="audio-here.ogg" controls autoplay&gt;

You can list multiple source of audio files by &lt;source src="audio-here.mp3"/&gt;

### Other NOTES

| *element* | *What it Does* |
| --- | --- |
| meta | |
| span | Also used for styling |
| GET method | Obtaining info from the user |
| POST method | Similar to the GET method but more secure |

## CSS

### Chapter "Intro to CSS"

External CSS: This is where the CSS and HTML are separate from each other. Example of setting up in html as follows:

&lt;link href-"css/styles.css" type-"text/css" rel-"stylesheet" />

Internal CSS: This is where the CSS code is paced inside of the HTML code.

###### Example as follows inside of html:

(html)

&lt;head&gt;

&lt;style type-"text/css"&gt;

      (css)
          body {

              font-family: helvetica;

              background-color: #DC143C;}

            h6 {

              font-color: #7FFF00;

            }

(html)

&lt;/style&gt;

&lt;/head&gt;

###### Inheritance
Can apply things such as a font family to large elements such as the body or whole page. Example pg:240

### Chapter 11 "Color"

RGB: red, green, blue rgb(100, 100, 100)
Hex Codes: 6 digit code  color: #ee3e80
Color Names: 147 predefined colors

element { background-color: #ee3e80;}

Hue: Is the near to the colloquial idea of color.
Saturation: gray in a color.
Brightness or Value: How much black is in a color.
Lightness: How much white is in a color.
Contrast: the visibility of color on top of another color.

Opacity: The amount you can see through.
RGBA: red, green, blue, alpha. Alpha refers to the transparency.

###### CSS3: HSL & HSLA for color
Alternative to specify color.
Hue, Saturation, Lightness, alpha

Example: backgound-color: hsla(0, 100%, 100%, .5);

### Chapter 12 "Text"
Example: pg 293-296
###### font-family: Helvetica;
Font Types:

Serif: have extra details of main strokes.
Sans-serif: straight ends to letters.
Monospace: every letter is the same width.

Weight, Style, Stretch

Note: Is important to use a standard font because browsers will usually use fonts installed on that users computer.
Good Fonts to use: Georgia, Times, Times New Roman, Arial, Verdana, Helvetica, Courier, Courier New, Comic Sans MS, Monotype Corsiva, Impact, Haettenschwaller

###### font-size:
    pixels (: 12px;), percentages (: 100%;), Ems (: 1.3;)

    Note: EMS is equal to the width of a letter.

###### @font-face
This allows you to use a font that might not be on someones computer.

    @font-face {
      font-family: 'downloaded font name here';
      src: url('font/dafont.eot');}
    p, {
      font-family: downloaded font name here;
    }

###### font formats
eot, woff, ttf/otf, svg

You need these different file formats for your font to work on different browser types. To convert to different types you can use www.fontsquirrel.com/
fontface/generator

###### font-weight
font-weight: bold;

(bold, normal, italic, oblique)

###### Uppercase & Lowercase
text-transform: uppercase;
 (uppercase, lowercase, capitalize)

###### Underline & Strike
text-decoration: underline;
(underline, overline, line-through, blink, none)

###### Leading
line-height: 1.4em;

###### Letter & Word Spacing
letter-spacing: .2em;
word-spacing: 1em;

Note: Kerning

###### Alignment
text-align: left;
(left, right, center, justify)

###### Vertical Alignment
vertical-align: baseline;
(baseline, sub, super, top, text-top, middle, bottom, text-bottom)

###### Indenting Text
text-indent: -9999px;

##### Drop Shadow
text-shadow: -1px -3px 2px #000000;
First indicates left/right, second top/bottom, third amount of blur, fourth color of drop shadow.

###### First Letter or Line
p.intro:first-letter { font-weight: bold;}

and :first-line

###### styling links
:link is to set a style to a link not yet visited, :visited allows you to set a style to a link already visited.

###### Responding to users
:hover, :action, :focus
Focus occurs when a browser discovers you are ready to interact.

### Chapter 13 "Boxes"
###### Box Dimensions
width, height

Can use: pixels, percentages, ems
em the size of the box is based on the text that is inside.

###### Limiting Width
min-width, max-width & min-height, max-height
Can be used to limit the view of a box.

###### Overflowing Content
overflow: hidden;

Overflow is when a box contains more info than is displayed.

(hidden, scroll)

Border: border on a box.
Margin: outside edge of the border.
Padding: space between the border of a box and content contained within.

###### Border Width
(thin, medium, thick, px, and boarder top,right, bottom, left)

###### Border style
border-style: solid, dotted, dashed, double, groove, ridge, inset, outset, hidden/none. Note you can change individual sides such as top, bottom, left, and right.

###### Border-color: #000000;

###### Shorthand border
pg: 312

###### Border Padding
padding: 10px;

margin: 32px;

###### Change Inline/block display
(inline, block, inline-block, none)

###### Hiding Boxes
visibility: hidden;  

or visible

###### border-image
stretch, repeat, round

###### box-shadow
(horizontal offset, vertical offset, blur distance, spread of shadow)

###### round corner
border-top-right-radius  : This changes each edge differently
border-radius: 3px, 12px, 2px, 5px;
or em

### Chapter 14 "List, Tables, and Forms"
 list-style-type

 Unordered Lists:(none, disc, circle, square)
 Ordered Lists: (decimal, decimal-leading zero, lower-alpha, lower-roman, upper-roman)

 ###### list-style-image: url("imageurlhere.jpg");

 ###### list-style-position: outside;
 (outside, inside)

###### Table Properties
width, padding, text-transform, letter-spacing, font-size, border-top, border-bottom, text-align, background-color, :hover

###### Border on Empty Cells
show, hide, inherit

###### Gaps between Cells
border-spacing: 5px 29px; , border-collapse: collapse or separate

###### For aligning Form Info see 345-346

###### cursor styles
auto, crosshair, default, pointer, move, text, wait, help, url("cursor.gif"):

### Chapter 15 "Layout"
###### Normal Flow
position: static;
This stretches the width of the browser window by default.

###### position: relative;
top: 23px;
left: 10px;

Allows you to offset blocks of text.

###### position: absolute;

Allows you to create text that is positioned in an exact location. Example:
p{
  position: absolute;
  top: 4px;
  left: 500px;
  width: 250px;}

###### position: fixed;
An exact position of text. (top, left, padding, margin, width, background-color)

###### z-index
"stacking context" equivalent of using the 'bring to front' and 'send to back' features.

###### float
Floats text to a specific point of a page. pg:370

##### SIDE-BY-SIDE
p{
  width: 230px;
  float: left;
  margin: 5px;
  padding: 5px; background-color: #efefef;}

###### clear
clearing floats move your text boxes to fit on one side. (left, right, both, or none)

###### Parents of Floated Elements
Problem: Some browsers treat the border of a containing element a 0px.
Solution: Setting overflow: auto; width: 100%

###### Creating Multi-Column Layouts with Floats
width, float, margin

Example: column1of2, column2of2 {
  float: left;
  width: 300px;
  margin: 10px;}

Note: Fixed Width Layout is unmoving side to side.
Liquid Layout elements shifts and changes with screen size; side to side.

###### Multiple Style Sheets
@import
Can use a separate &lt;link&gt; on each style sheet.
Example: 395
Note: You place a link such as this within the head of your html.

### Chapter 16 "Images"
###### Controlling Sizes of Images
img.small {
  width: 500px;
  height: 500px;}

  You can have common sizes throughout the css document and label them. Example: small, medium, large.

#### Background Images

  p {background-image: url("imagehere.gif");}

background-repeat & background-attachment:
Repeat: repeated horizontally and vertically.
Repeat-x: repeated horizontally only.
Repeat-y: repeated vertically only.
No-Repeat: Image only shown once.
Fixed: BG stays in one position on the page.
Scroll: BG moves as the user scrolls.

###### background-position: left center;
left top, left center, left bottom, center top, center center, center bottom, right top, right center, right bottom

#### Background SHORTHAND
|  | *order* |
|:---: | :---: |
| 1. | color |
| 2. | image |
| 3. | repeat |
| 4. | attachment |
| 5. | position |
Example:
body {
  background: #78109C url("kat.jpg")
  no-repeat top right;}

##### Image Rollovers & Sprites
Rollover: The image changes when the user moves over it.
Sprite: Using the same image over several different parts of an interface.

##### CSS3 Gradients
background-image: -webkit-linear-gradient(#78109C, #FFF)

##### Contrast of BG Images
hight contrast, low contrast, screen

### Chapter 17 "HTML5 Layout"
For an example of a traditional html layout pg: 431

##### Headers Footers
&lt;header&gt; contains site name and main navigation.
&lt;footer&gt; could contain links and credits.

###### Navigation
primary nav. site.

&lt;artical&gt;
section of a page that could stand alone. They also can nest.

&lt;aside&gt;
Used inside of an article usually stuff that relates to the artical.

&lt;section&gt;
Groups related content together such as common articles. Note: This should not be used to "wrap" an entire page. Leave that to a div.

&lt;hgroup&gt; Groups headers together and treats them as the same header.

##### Figures
&lt;figure&gt;, &lt;figcation&gt;
This used to group items such as images, videos, graphs, diagrams, code samples, text that relates.

#### &lt;div&gt;
Grouping together related elements.

#### Helping Older Browsers Understand
Uses JavaScript HTML5 shiv or HTML5 shim
Example: 442 Should ask about.

# CSS3 The Missing Manual
#### Notes From the Book
For beginners in html
(www.htmldog.com/guides/htmlbeginner)

W3Schools (www.w3schools.com/html)
The &lt;html&gt; tells a browser what language is spoken for the page.

To Follow along: www.sawmac.com/css3/

###Chapter 1 HTML for CSS
Html to organize and Css to look good.

NOTE: For a tutorial on HTML, visit www.w3schools.com/html/html_intro.asp. For a quick list of all available
HTML tags, visit Sitepoint.com’s HTML reference at http://reference.sitepoint.com/html.

&lt;div&gt; for division.

&lt;span&gt; is used for inline elements such as words or phrases. Example: &lt;span class="Something"&gt; or &lt;span this="Words_Here.com"&gt;

&lt;figure&gt; &lt;figcaption&gt; caption used to describe an image or illustration.

Don’t use the &lt;b&gt; and &lt;i&gt; tags to emphasize text.
But you can use these if you're just want to italicize or bold font.

http://validator.w3.org is a good site to validate your page.(html only?)

### Chapter 2 "Creating Styles & Style Sheets"

PG:35 TIP: Some people learn better by doing rather than reading.Ifyou’dliketotryyourhandatcreatingstyles and style sheets first and then come back here to read up on what you just did, turn to page 43 for a hands-on tutorial.

External Style Sheets unified design and a quicker load time.

Internal Style Sheets easy to add to web pages but when you want to make changes to a style you're going to have to update all of you webpages. (Because you had to copy and past it into each individual page.) So far my personal opinion is that External Style Sheets are better....

Note: You can place an internal style after the title but most put it after the head. FYI: &lt;style&gt; is required for an HTML5 doc.

Last page: 43
