# Images

> There are many reasons why you might want to add an image to a web page: you might want to include a logo, photograph, illustration, diagram, or chart.

An important aspect of images to note is that they could potentially be subject to copyright. To avoid this you can utilize your own images or you can purchase stock images from a company.

According to HTML & CSS by Jon Duckett images should:

- Be relevant
- Convey information
- Convey the right mood
- Be instantly recognisable
- Fit the color pallete

Adding an image to your site can be done with the `<img>` element. Also note that the `<img>` element is considered and empty element due to to the fact that it does not have a closing tag.

The src within the img element tells the browser wherer it cam fimd the file image.

The alt portion of the img element describes what the image is in the event that someone is unable to see the image itself.

```
<img src="link or folder can go here" alt="This is where the descrption of the image would go">
```

# Color

> The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways: RGB values, Hex codes, Color names.

```
body {
    color: red;
}
```

This above code snippet will change all of the font contained within the body element to red. You can change the colors of other aspects of your page simply by targeting different elements.

- RGB Values
  - Values for red, green, and blue are expressed as numbers between 0 and 255.
- Hex Codes
  - Hex values represent values for red, green, and blue in hexadecimal code.
- Color Names
  - Colors are represented by predefined names. However, they are very limited in number.
- Hue
  - Hue is near to the colloquial idea of color. Technically speaking however, a color can also have saturation and brightness as hue.
- Saturation
  - Saturation refers to the amount of gray in a color. At maximum saturation, there would be no gray in the color. At minimum saturation, the color would be mostly gray.
- Birghtness
  - Brightness (or "value") refers to how much black is in a color. At maximum brightness, there would be no black in the color. At minimum brightness, the color would be very dark.

# Text

**Serif** fonts have extra details on the ends of the main strokes of the letters. These detailsare known as serifs.

**Sans-Serif** fonts have straight ends to letters and therefore have a much cleaner desgin.

**Monospace**
Every letter in a monsopsace(or fixed-width) font is the same width. (Non-monospace fonts have different widths.)

- Weight

  - The font weight not only adds emphasis but can also affect the amount of white space and contrast on a page.

- Style

  - Italic fonts have a cursive aspect to some of the lttering. Oblique font styles take the normal style and put it on an angle.

- Stretch
  \*In condensed(or narrow) versions of the font, letters are thinner and closer to gether. In expanded versios they are thicker and further apart.
