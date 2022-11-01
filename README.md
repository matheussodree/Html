# _Html Documentation_
### _Html documentation to assist in studies_

* Basic Html Structure
~~~html

<HTML>
<HEAD>
<TITLE> first example </TITLE>
</HEAD>
<BODY>
  <h1> Hello world </h1>
</BODY>
</HTML>

~~~

* Paragraphs
~~~html

  The <P> tag is used to define the beginning of a new paragraph,
leaving a blank line between this and the previous text.
  
  The ALIGN parameter sets the paragraph text alignment and can
assume the values 'left', 'right', 'center' and 'justify', corresponding respectively
left, right, center and justified alignments. 

  If the ALIGN parameter is not specified, by default the paragraph will be aligned
to the left.

  Basic syntax: <P> Text </P>
  Full syntax: <P ALIGN= left | right | center | justify > Text </P>

~~~

* Horizontal Lines
~~~hmtl

The <HR> tag inserts a dividing line at the position where it is placed.
There is no </HR> tag.
  The main parameters of this command are:

1. SIZE= "number" - Sets the width of the line and must be specified in
pixels.
2. WIDTH= number | number% - Specifies the length of the line in
pixels or percentage of window size.
3. ALIGN= left | center | right - Specifies the horizontal alignment of the
line.
4. COLOR= color - Specifies the color of the line.
5.NOSHADE - Indicates that the line should not receive the shadow effect.
Basic syntax: <HR>
Full syntax: <HR SIZE= number WIDTH= number | number%
ALIGN= left | center | right COLOR= NOSHADE color>
  
  I modified the 'paragraph.html' example as shown below.

<HTML>
<HEAD>
<TITLE> Paragraphs and Line Breaks </TITLE>
</HEAD>
<BODY>
<P ALIGN=center>Using P:</P>
<P> Let's separate this sentence with the of paragraph. </P>
  To check the difference.
** <HR ALIGN=center WIDTH=75% SIZE=15 COLOR=blue NOSHADE> **
<P ALIGN=center>Using BR:</P>
<P> Now we separate the lines using <BR>
the line break markup. <BR>
Did you notice?
</BODY>
</HTML>

~~~

* Style Markers
~~~html

These commands allow the programmer to create a series of effects on the
text by changing the font shape and size. 

All tags of this type must be specified in pairs, marking the beginning and end of the text to be formatted.

The main text style commands are:
-> Bold - Applies the bold style. Syntax: <B> text </B>;
-> Italic - Applies the italic style. Syntax: <I> text </I>;
-> Underline - Applies the underline style. Syntax: <U>text </U>;
-> Strong - Similar to bold. Syntax: <STRONG> text </STRONG>;
-> Typewriter - Makes text evenly spaced. Syntax: <TT> text </TT>;
-> Big - Enlarges the font and applies the bold style. Syntax: <BIG> text </BIG>;
-> Small - Reduces the font. Syntax: <SMALL> text </SMALL>;
-> Superscript - Raises the text and lowers its body. Syntax: <SUP> text </SUP>;
-> Subscript - Lowers the text and makes its body smaller. Syntax: <SUB> text </SUB>;
-> Pulsing - Causes the text to flash. This effect does not work on everyone the Browsers. Syntax: <BLINK> text </BLINK>;

~~~

* Headers
~~~html

Another way to change the font size and apply a bold style to text is to use <H> tags.

The HTML language has six commands, from H1 to H6, which apply a different font size to the text that they may contain.

In addition to modifying the size, the H commands insert blank lines above and below the line of formatted text.

The command H1 has the largest size, while H6 has the smallest font size.

The basic syntax for this command is: <Hn>Text </Hn>.
Where n is the number from 1 to 6 corresponding to the header size.

The example below allows you to view header sizes.
Enter it saving as 'cabec.html'.
<HTML>
<HEAD>
<TITLE> Headers </TITLE>
</HEAD>
<BODY>
<H1> Header with size 1 </H1>
<H2> Header with size 2 </H2>
<H3> Header with size 3 </H3>
<H4> Header with size 4 </H4>
<H5> Header with size 5 </H5>
<H6> Header with size 6 </H6>
</BODY>
</HTML>
~~~  

* Centralization of texts and other elements
~~~html

To center a header, paragraph or figure within the width of the page, 
the <CENTER> and </CENTER> tags surrounding the element to be centered must be used.

Syntax: <CENTER> [Elements to be centered] </CENTER>.

<HTML>
<HEAD>
<TITLE> Headers </TITLE>
</HEAD>
<BODY>
<CENTER>
<H1> Header with size 1 </H1>
<H2> Header with size 2 </H2>
<H3> Header with size 3 </H3>
<H4> Header with size 4 </H4>
<H5> Header with size 5 </H5>
<H6> Header with size 6 </H6>
</CENTER>
</BODY>
</HTML>
~~~
* The FONT marker
~~~html

The <FONT> and </FONT> tags allow the programmer to modify the font size, type and color of a text.

Its parameters are:

SIZE= number - Specifies the font size to be used and can range from 1 to 7. 
If a number is specified preceded by plus or minus signs, 
the default font size (size 3) will be, respectively, increased or decreased by that value.
So size= 2 and size= -1 have the same practical effect.

FACE= name - Allows you to choose a different font for the text. 
Various font types can be specified, so that if the system does not have the first option, 
the second is automatically loaded, and so on.
One can therefore write: FACE= font1, font2, font3 . 
In this case, font1 is the programmer's preferred font, 
font2 is their second choice, and font3 is their last.

COLOR= color - Specifies the color of the text. Its value can be specified
by the color name in English, in the case of more common colors. 
However, in the general case, the color specification is done through the RGB (Red-Green-Blue) standard. 
In this pattern, the color is described by a 6-digit number,
where the first two correspond to the intensity of the red color, 
the middle two to the green color and the last two to the blue color. 
The resulting color will be a combination of these three. 
The numerical base used for the representation of colors in the RGB standard is hexadecimal, 
which gives us 256 possibilities of intensity for each basic color (from 0 to 255). 
It is written: COLOR= rrggbb or COLOR= name .

Basic syntax: <FONT> Text </FONT>.
Full syntax: <FONT FACE= name SIZE= number COLOR= color >
Text </FONT>.

<HTML>
<HEAD>
<TITLE> Text Colors </TITLE>
</HEAD>
<BODY>
<FONT SIZE= 7 COLOR= #0C01BD >P</FONT>
<FONT SIZE= 6 COLOR= #655E7D >e</FONT>
<FONT SIZE= 5 COLOR= #A39A4B >t</FONT>
<FONT SIZE= 4 COLOR= #EEF303 >-</FONT>
<FONT SIZE= 4 COLOR= #EEF303 >T</FONT>
<FONT SIZE= 5 COLOR= #A39A4B >e</FONT>
<FONT SIZE= 6 COLOR= #655E7D >l</FONT>
<FONT SIZE= 7 COLOR= #0C01BD >e</FONT>
</BODY>
</HTML>
~~~

* The IMG bookmark
~~~html

The IMG marker inserts an image into the body of the document.
Its main parameters are:
SRC= file name or URL - Name or address (URL) of the image to be displayed. This parameter is mandatory.

ALT= Text - Displays the specified text when the Browser does not find the image or when the cursor passes over the figure.

ALIGN= Top | Middle | Bottom - Specifies the alignment of the image relative to the line of text where it is displayed.

ALIGN= Left | Right - Specifies the alignment of the image relative to the side edges of the window.

ISMAP - Determines that the figure is an image map. We will deal with this subject in more detail in one of our next chapters.

WIDTH= "number | number%" - Specifies the display width of the
image in pixels or in relation to the width of the window, regardless of its original size. When you change the horizontal dimension of the image, the vertical dimension is automatically modified so that the original aspect ratio is maintained.

HEIGHT= number | number% - Specifies the display height of the
image in pixels or in relation to the width of the window, regardless of its original size. When you change the image's vertical dimension, the horizontal dimension is automatically modified so that the original aspect ratio is maintained. If we want to force a distortion in the original aspect ratio of the image, we have to use the WIDTH and HEIGHT parameters simultaneously.

BORDER= number - Specifies, in pixels, the width of the image's border. The zero value removes the border.

VSPACE= number - Determines, in pixels, the space that should be left blank at the top and bottom of the image.
HSPACE= number - Determines, in pixels, the space that should be left blank on the sides of the image.

Basic syntax: <IMG SRC= file name or URL >.

Full syntax: <IMG SRC= file name or URL WIDTH= number
HEIGHT= number BORDER= number ALT= Text
VSPACE= number HSPACE= number ALIGN= Top | Middle | Bottom | Left | Right >.
~~~ 

* Links

~~~html

The <A> and </A> tags can mark text or an image as a hyperlink, 
as well as create an address to a specific part of a document that will be referred to by a link.
The main parameters of the <A> command are:

HREF= file name or URL - Specify the URL address to which the link is associated. 
Can be used for references inside and outside the document.

NAME= name - Specifies the name of the section of a document that is referred 
to by a hypertext link.

Document 1:
<HTML>
<HEAD>
<TITLE> Links 1 </TITLE>
</HEAD>
<BODY>
<CENTER>
<H1>Document 1 </H1>
<BR>
Click <A HREF= links2.html > here </A> to access document 2.
</CENTER>
</BODY>
</HTML>

Document 2:
<HTML>
<HEAD>
<TITLE> Links 2 </TITLE>
</HEAD>
<BODY>
<CENTER>
<H1>Document 2 </H1>
<P> Did you notice the link working? </P>
</CENTER>
</BODY>
</HTML>

~~~
