# HTML-CSS
INTRO TO HTML
<ul>
    <li>Hepertext Markup Language</li>
    <li>To define building block of the web page.</li>
    <li>Responsible for marking up the content of a website</li>
    <li>Hypertext defines the link between the web pages and markup language defines the text document within tag.</li>
    <li>HTML is not a case sensitive language</li>
</ul>

DOM<b>

Document Object Model
*Model that represents the object or elements in a HTLM document.
HTTP<b>

Hypertext Transfer Protocol<b>
*Is a language that browser and server are using to tslk to one another.
*Not exactly a programming language but a plain text language for communicating over the internet.
*HTTPS - HTTP + encryption
HTML ElEMENTS,<b>

*Defines by a start tag, content an end tag.
*Some HTML elements have no content
*Empty elements do not have an end tag.

NESTED HTML ELEMENTS

*They can contain other elements.
*All HTML documents consist of nested HTML elements.

FOUR HTML ELEMENTS

em>: To add emphasis
strong>: To show importance or urgency. It adds meaning to the text.
i>": To display content in italic style.
b>: Allows us to make something bold.

OTHER ELEMENTS

html>: Is the root element and it defines the whole html document.
*Start tag html> and end tag html>
*Inside html> element there is a:
y>: defines the body of a document.
 Inside body> element there are two other elements: h1> and p>
<1>: defines the heading
p>: defines a paragragh.
br>: defines a line break, and is an empty element with a closing tag. 

HTML LISTS
Ordered Lists
*Starts with ul> tag
*Each list item starts with li> tag
*Items will be marked with bullets by default

Ordered Lists
<ul>
<li>Starts with ol> tag</li>
<li>Each list item starts with li> tag</li>
<li>Items will be marked with numbers by default.</li>
</ul>


Definition Lists
<ul>
<li>List items with a definition of each term.</li>
<li>dl> tag defines the definition list</li>
<li>dt> tag defines the name.</li>
<li>dd> tag defines each name.</li>
</ul>

HTML QUOTES

*cite> and blockquote> serve a semantic purpose.
*They provide a convenient way to apply custom styling.
*Block-level: blockquotes, paragraphs and unordered lists.
*Create separate blocks on the page.

HTML DATE AND TIME INPUTS
<ul>
<li>Specifies the date</li>
<li>Time within the datetime attribute has to be specific.</li>
<li>Can combine date and time using the datetime attribute.</li>
<li>time>: used to make anything that specifies a time of day, date or duration.</li>
<li>Purpose is to determine exact date or time to computers.</li>
<li>attribute: datetime</li>
</ul>


HTML CODE, PRE AND BR

*Code: treated as an inline element, meaning it remains part of the sentencr.
"&lt": html entity, display as a less than sign.
"&gt": html entity, display as a greater than sign.
*These entities are useful when you want to display html code on a page instead of executing it.
*br: it indicates where a line break should happen.
*pre: to contain your space, line breaks, helps you to achieve that.
*pre and code are often combined to display a code block with proper indentation.

HTML SUPERSCRIPTS, SUBSCRIPTS AND SMALL TEXT

Subscripts
sub> appears half a character below the normal line, sometimes renered in a smaller font than normal.
They mostly used for chemical formulas.

Superscripts
sup> appears half a character aBOVE THE NORMAL LINE, SOMETIME RENDERED IN SMALLER FONT.
Can be used as exponent

Small Text
small> defines smaller text.
Used in copyright and other side comment.

HTML ATTRIBUTES

Popular attribute: id
Global attributes: attributes that can be used with all html elements.
lang attribute: specifies the language of the elements content.
dir attribute: indicate the text direction for the content in an element.
class: indicate one or more classname for an element.Refers to a class in a style sheet.
lang and dir: global attribets and can be used on any html element.
"LTR" left to right scripts
"RTL"right to left scripts

 ARIA ROLES
 Accessible Rich Internet Application
 Set of roles and attribute that define ways to make web content and web application more accessible to people with disabilities.
 html has a significant impact on human rights.
 ensures that everyone can use the full fuctionality of a complex interface in an app.

 HTML LINKS
 a> tag defines a heperlink
 href attribute indicates the link destination
 links allow users to click their way from page to page.
 links are created using element anchor and add an href attribute with URL enclosed in quotes. This URL is where a link will take us.
 HTTPS: enhanced security

 HTML URL PATHWAYS
<ul>
<li>An absolute file path is the full URL.</li>
<li>Relative file paths: points to a file relative to the current page.</li> 
 Skill used to reference image files, video files, css and javascript files.

</ul>

 NAVIGATION
<ul>
<li>nav>: set of navigation links</li>
 <li>s intended only for major blocks of navigation links</li>
 <li>Signifies that it represents the main navigation of the page.</li>
 <li>Not all links of a document should be inside a nav> element.</li>
 <li>We add äria label"of "breadcrumb"to provide context when read aloud.</li>
 <li>In "breadcrumb"links in a "nav"element, using ordered list öl"because the order of links is important.</li>
 <li>Each link is mark as a link and wrap them in a "footer"element.</li> 
</ul>
 

 HTML WORKING WITH GRAPHICS AND IMAGES

 IMAGES
 <UL>
     <li>Source attribute(src): Tells the browser which image file to load.</li>
     <li>Alt attribute(alt): Provides a text description of the image.</li>
     <li>Alt attribute: Serve as a replacement for the image when it can not be seen.</li>
     <li>Width & Height: Size of the image.</li>
 </UL>
 Image Formats
 <ul>
     <li>Aims for highest possible quality with the smallest file size.</li>
     <li>GIF:Graphics Interchange Format</li>
     -Compressing illustractions that have large areas of the same color.
     <li>SVG:Scalable Vector Graphics</li>
     -Contains instructions for drawing rather than individual pixel.
     <li>JPG:Joint Photographic Expert Group</li>
     -Compressing photographs
     -Can be compressed further by reducing color information, finding the right balance between quality and file size.
     <li>PNG:Portable Network Graphics</li>
     -Newer format that works well when you need transparency in a photograph.
     -It outperforms GIF and JPG in compressing certain types of images.
 </ul>
<ul>
    <li>Responsive Image</li>
    -They automatically adjust to fit the size of the screen.
    <li>Responsive Width</li>
    -Demostrate how the source attribute set in the sizes attribute can be utilized to offer multiple image files to the browser.
    <li>Figcaption and Figures</li>
    -"<figcaption>"defines a caption for a "<figure>"element
    <li>"<figcaption>"element can be placed as the first or last child of the "<figure>" element</li>
    - It supports global attributes in html.
    <li>"<figur>" specifies self-contained content like photos, diagrams and more.</li>
    <li>It relates to the main flow</li>
    <li>It's position is independent of the main flow</li>
    <li>If removed it will not affect the flow of the document.</li>
    <li>It supports global attributes in html.</li>
</ul> 
Working with Media
        <ul>      
<li>Multimedia comes in many different formats. It can be almost anything you can hear or see, like images, music, sound, videos, records, films, animations, and more.</li>
<li>Working with Audio</li>
<li>You can use JavaScript and the HTML media element API to develop your own custom audio player controls rather than depending on pre-built ones.</li>
<li>We will not implement that for this example; instead, we will only add the "controls" attribute.</li>
<li>Then attributes indicate that we want the controls if they are there.</li>
<li>The website now features an audio player.</li>
<li>We'll be able to view the time, play, pause, mute, and explore the timeline thanks to this.</li>
        </ul>
Working with Video
        <ul>
<li> The controls attribute adds video controls, like play, pause, and volume.</li>
<li> It is a good idea to always include width and height attributes. If height and width are not set, the page might flicker while the video loads.</li>
<li> The <source> element allows you to specify alternative video files which the browser may choose from. The browser will use the first recognized format.</li>
        </ul>
        
 HTML Language Support
 <ul>
<li>The lang attribute is used to specify the language of a webpage and If the whole page is in one language, it is quite simple.</li>
<li>Set the language on the main element that wraps everything else, which is usually the HTML element.</li>
<li>In HTML, it's good to have a lang attribute in <html>, e.g. <html lang="en">.</li>
 </ul>
 
Working with the lang and charset attributes
 <ul>
<li>Most languages flow from left to right horizontally, but some flow from right to left. Use the dir attribute to indicate the direction, and it can be applied to any element.</li>
<li>It is helpful when the content on your page goes to same direction you just define it once on the outer HTML element</li>
<li><html lang =”en-US”>  and <html lang =”en-BS”> in this example the content is Engish in United state and Great British</li>
<li><html la>ng =”en-US” dir=”ltr”>  and <html lang =”en-BS” ” dir=”rtl”> this one shows that en-gb is from right to left and other one vice verse.</li>
 </ul>

The Meta Attribute
<ul>
<li>The meta tag defines the metadata about the HTML document while metadata is information about data</li>
<li><meta> tags always go inside the <head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.</li>
<li>There is a method to let web designers take control over the viewport</li>
<li>To specify the charset in HTML, simply include a meta charset tag that equals UTF-8.</li>
</ul> 
    
 HTML Generic Elements, Div and Span
 <ul>
<li>There two elements such as div which is used to create sidebars and sections .</li>
<li>Also div is a block level element  and they are usually used a lot in javascript and CSS</li>
<li>Span is used to mark desired phrase and they can make use of various global attribute</li>
 </ul>

 

