# HTML Images, CSS Color & Text  

---

## Images  

There are many reasons to add an image to your web page. You may want to include a logo, photograph, illustration, diagram, or chart.  

- To choose an image for your site you can either buy a stock image or get free images online.  
- To add an image to your page you need to use an `<img>` tag.  
- The *src* attribute inside the tag tells the browser where to find the image. The *alt* attribute gives the image text if you cannot see it.  
- You can also use the title attribute to provide additional information about the image.  

There are three main rules to remember when creating images for your website.  
- Save images in the right format  
- Save images at the right size  
- Measure images in pixels  

Photographs are best saves as JPEGs, Illustrations or logos that use flat colors are best saved as GIFs.  

## Color

There are three common ways in which you can indicate your choice of colors.  

- RGB values. These express colors in terms of how much red, green and blue are used. Example (100,100,90)  
- Hex codes. Six-digit codes that represent the amount of red, green and blue in a color preceded by a hash sign. Example #ee3e80  
- Color names. There are 147 predefined colors that are recognized by browsers.  

When picking foreground and background it is important to have enough contrast for the text to be easily legible.  
CSS3 has introduced an extra value for RGB colors to indicate opacity. RGBA  

## Text

The properties that allow you to control the appearance of text can be split into two groups.  

- Those that directly affect the font and its appearence.  
- Those that would have the same effect on text no matter what font you were using.  

**Typeface Terminology**  

- Serif: These fonts have extra details on the ends of the main strokes of the letters.  
- Sans-Serif: These fonts have straight ends to letters.  
- Monospace: Every letter in a monospace font is the same width.  
- Cursive: Cursive fonts either have joining strokes or other cursive characteristics.  
- Fantasy: These fonts are often used for titles as they are decorative.  

When choosing a typeface it is important to understand that a browser will usually only display it if it's installed on that user's computer.  

- The font weight property allows you to create bold text. Whereas the font style property will allow you to create italic text.  
- The text-transform property allows you to change the case of your desired text.  
- Text-decoration allows you to underline, overline, line-through, or blink(flash on and off).  
- Text alignment allows you to control the alignment of the text. Left, Right, Center or Justify(every line in the paragraph should take up the full width of the box).  

You can also use *psuedo-classes* to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.  

## JPEG vs PNG vs GIF  

**Compression**  

Compression can be of two types- lossless and lossy. It is possible to reconstruct images from compressed images if it is lossless compression where as lossy  compression is irreversible.  

JPEG is a lossy compression, whereas PNG and GIF's are not.  

**Transparency**  

Logos and icons often need to be placed on backgrounds with variable colors. So it is desirable that the backgrounds are made transparent so a single image can be used over multiple backgroun variations.  

JPEG images do not support transparency where as PNG and GIF's both do in their own way.  

**Colours**  

- JPEG images can support around 16 million colours.  
- PNG images have two modes. PNG8 and PNG24. The former can support up to 256 colours whereas the latter can handle up to 16 million colours.  
- Gif images are limited to 256 colours.  

**Animation**  

Refers to any change or movement in the image. Of these three formats only GIF supports animation.  



