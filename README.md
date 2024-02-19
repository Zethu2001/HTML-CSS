# HTML-CSS
INTRO TO HTML

<ul>
    <li>To define building block of the web page</li>
    <li>Responsible for marking up the content of a website.</li>
    <li>Hypertext defines the link between the web pages and markup language defines the text document within tag.</li>
    <li></li>
    <li></li>
</ul>

Hepertext Markup Language <br>
*To define building block of the web page.<br>
*Responsible for marking up the content of a website.<br>
*Hypertext defines the link between the web pages and markup language defines the text document within tag.<br>
*HTML is not a case sensitive language<br>
DOM<br>

Document Object Model<br>
*Model that represents the object or elements in a HTLM document.<br>
HTTP<b><br>

Hypertext Transfer Protocol<b><br>
*Is a language that browser and server are using to tslk to one another.<br>
*Not exactly a programming language but a plain text language for communicating over the internet.<br>
*HTTPS - HTTP + encryption<br>
HTML ElEMENTS,<b><br>

*Defines by a start tag, content an end tag.
*Some HTML elements have no content
*Empty elements do not have an end tag.
*Example ,br>

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
*Starts with ol> tag
*Each list item starts with li> tag
*Items will be marked with numbers by default.

Definition Lists
*List items with a definition of each term.
*dl> tag defines the definition list
*dt> tag defines the name.
*dd> tag defines each name.

HTML QUOTES

*cite> and blockquote> serve a semantic purpose.
*They provide a convenient way to apply custom styling.
*Block-level: blockquotes, paragraphs and unordered lists.
*Create separate blocks on the page.

HTML DATE AND TIME INPUTS

*Specifies the date
*Time within the datetime attribute has to be specific.
*Can combine date and time using the datetime attribute.
*time>: used to make anything that specifies a time of day, date or duration.
*Purpose is to determine exact date or time to computers.
*attribute: datetime

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

 An absolute file path is the full URL.
 Relative file paths: points to a file relative to the current page.
 Skill used to reference image files, video files, css and javascript files.

 NAVIGATION

 nav>: set of navigation links
 Is intended only for major blocks of navigation links
 Signifies that it represents the main navigation of the page.
 Not all links of a document should be inside a nav> element.
 We add äria label"of "breadcrumb"to provide context when read aloud.
 In "breadcrumb"links in a "nav"element, using ordered list öl"because the order of links is important.,
 Each link is mark as a link and wrap them in a "footer"element.