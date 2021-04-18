# CSS
CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.
CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.
p { font-family: Arial;} 
## BLOCK & INLINE ELEMENTS
Block level elements look like they start on a new line. Examples include the <h1>-<h6>, <p> and <div> elements.
Inline elements flow within the text and do not start on a new line. Examples include <b>, <i>, <img>, <em> and <span>.
#### CSS Properties Affect How Elements Are Displayed:
CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.
# COLORS
Color can really bring your pages to life.
## Foreground Color
The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways: 
-	rgb values: These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90).
-	 hex codes: These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80. 
-	color names: There are 147 predefined color names that are recognized by browsers. For example: DarkCyan.
## Background Color
You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values, hex codes, and color names (covered on the next page).
## Contrast
-	Low Contrast: Text is harder to read when there is low contrast between background and foreground colors.
-	High Contrast: Text is easier to read when there is higher contrast between background and foreground colors.
-	Medium Contrast: For long spans of text, reducing the contrast a little bit improves readability.
If text is reversed out (a light color on a dark background), you 
can increase the height between lines and the weight of the font 
to make it easier to read.
## OPACITY
CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity). 
The CSS3 rgba property allows you to specify a color, just like you would with an RGB value, but adds a fourth value to indicate opacity. This value is known as an alpha value and is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).
 The rgba value will only affect the element on which it is applied (not child elements). Because some browsers will not recognize RGBA colors, you can offer a fallback so that they display a solid color. If there are two rules that apply to the same element, the latter of the two will take priority. To create the fallback, you can specify a color as a hex code, color name or RGB value, followed by the rule that specifies an RGBA value. If the browser understands RGBA colors it will use that rule. If it doesn't, it will use the RGB value.


