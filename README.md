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
