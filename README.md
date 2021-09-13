# pulkkot-font
**pulkkot** is a custom font that I created by using [Calligraphr](https://www.calligraphr.com/). Calligraphr is a website that allows users to create their own custom fonts at a free cost. I learned about this website thanks to my coworkers. I also used [Font Squirrel](https://www.fontsquirrel.com/) that generates webfont for free. For more detailed tutorial for custom fonts, please check out [this article](https://blog.schoolofcode.co.uk/a-beginners-guide-to-creating-your-very-own-custom-web-font-7b71b16f4ef3). Hope you enjoy this and perhaps have fun making your own as well :balloon:

## What pulkkot means
pulkkot(풀꽃) means 'grass flower' in Korean and I named it after one of my favourite poems.  The poem is below:

<p align="center">
  <img src="https://github.com/kmsunmin/pulkkot-font/blob/main/images/poem.png" />
</p>

## How to install (.otf/.ttf files)
#### Windows:
1. After downloading the font file on your computer, right-click the file and select **Install**.
2. When the font installation is complete, you can use the font.

#### Mac:
1. After downloading the font file on your computer, double-click the file and select **Install Font**.
2. When the font installation is complete, you can use the font.

#### Linux:
1. After downloading the font file on your computer, double-click the file and select **Install** on top right corner.
2. When the font installation is complete, you can use the font.

## How to use pulkkot font for your website
1. After downloading the font files on your computer, upload the font files in `webfont/` (ex: .woff, .woff2, stylesheet.css) in this repository to your website.
2. Open `stylesheet.css` file that has the following code:
   ```css
   @font-face {
       font-family: 'pulkkot';
       src: url('pulkkot-webfont.woff2') format('woff2'),
            url('pulkkot-webfont.woff') format('woff');
       font-weight: normal;
       font-style: normal;
   }
   ```
3. Replace `'pulkkot-webfont.woff'` and `'pulkkot-webfont.woff2'` inside `url()` with the location of the files on your server.
4. After updating `stylesheet.css` file, you can include it on your HTML document. You can put `stylesheet.css` before any of your CSS.
  
    **Example:**
    ```html
    ...
    <link rel="stylesheet" href="path to stylesheet.css for your website" type="text/css" charset="utf-8">
    <link rel="stylesheet" href="path to main.css for your website" type="text/css" charset="utf-8">
    ...
    ```
5. Then, you can use pulkkot font in your main CSS file.
  
    **Example:**
    ```css
    font-family: 'pulkkot', serif;
    ```
  
## Examples
![regular](https://github.com/kmsunmin/pulkkot-font/blob/main/images/regular.png)

![bold](https://github.com/kmsunmin/pulkkot-font/blob/main/images/bold.png)

![example](https://github.com/kmsunmin/pulkkot-font/blob/main/images/example.png)

## License
This font software is licensed under the [SIL Open Font License, Version 1.1](http://scripts.sil.org/OFL). This means that the font can be "used, studied, modified and redistributed freely as long as they are not sold by themselves". More information is available at http://scripts.sil.org/OFL.
