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
