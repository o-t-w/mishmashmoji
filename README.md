# mishmashmoji
MishMashMoji is a color emoji font available as both OpenType-SVG and COLRv1.

To have the font work in all browsers, read [this blog post](https://fullystacked.net/posts/new-font-face-syntax/#:~:text=Using%20color%20fonts%20with%20tech()).

Some of the glyphs are taken from the open source [Kablammo typeface](https://fonts.withgoogle.com/kablammo), designed by Travis Kochel, with creative direction by Travis Kochel and Lizy Gershenzon, at Vectro Type. I colorised them in FontLab.

![a screenshot of all the Kablammo emoji in the font](./images/kablammo.avif)

The blob glyphs are customised and colorised versions of the non-color version of [Noto Emoji](https://fonts.google.com/noto/specimen/Noto+Emoji) from Google, with some facial expressions taken from Kablammo. 

![a screenshot of all the blob emoji in the font](./images/blobs.avif)

Thank you to all the original creators. 

This font only covers a very limited set of emoji.

In Chrome and Firefox you can customize the colors of the font.

![A green version of an melting face emoji](./images/greenemoji.avif)

 See this [article](https://css-tricks.com/colrv1-and-css-font-palette-web-typography/) for more information. 

e.g.

```css
@font-palette-values --Slime {
            font-family: mishmashmoji;
            base-palette: 0;
            override-colors:
            9 #30FA0A;
        }

      h1 {
            font-family: mishmashmoji;
            font-palette: --Slime;
        }
```

I also included some unedited versions of emoji I like from [FxEmoji](https://github.com/mozilla/fxemoji) from Mozilla, the Twitter emoji font, the color version of Noto from Google, and the Microsoft emoji font. 

![a screenshot of all the Kablammo emoji in the font](./images/randomemoji.avif)
