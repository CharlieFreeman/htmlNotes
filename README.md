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

### Other NOTES

| *element* | *What it Does* |
| --- | --- |
| meta | |
| div | Grouping for styling |
| span | Also used for styling |
| GET method | Obtaining info from the user |
| POST method | Similar to the GET method but more secure |
