# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- [GitHub repository](https://github.com/SabineEmden/fm-3-column-preview-card-component)
- [Live site](https://sabineemden.github.io/fm-3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I needed a refresher on best practices for custom web fonts. I had taken a deep dive into this topic for my Frontend Mentor [QR code component solution](https://github.com/SabineEmden/qr-code-component).

The font families in this project are [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca) for normal text and [Big Shoulders](https://fonts.google.com/specimen/Big+Shoulders) for headings. Both are available as variable fonts. Lexend Deca has a weight axis. Big Shoulders has a weight axis and an optical size axis. Optical size adapts the style to specific text sizes. This project uses Lexend Deca only in regular (400) font weight and 15 px font size, Big Shoulders only in bold (700) font weight and 40 px font size. The files I downloaded from Google Fonts contain variable and static versions of the font families.

For Lexend Deca, the TTF file for the variable font has a size of 175 Kb. The size of TTF file for Lexend Deca Regular as a static font is only 78 Kb. I decided to use the static file. Inspection with [Wakamai Fondue](https://wakamaifondue.com/) showed 845 glyphs, much more than the 95 glyphs that are usually enough for English-only websites. Subsetting the font to Basic Latin with the [Font Subsetter](https://everythingfonts.com/subsetter) by Everything Fonts and converting the file to WOFF2 with the [ttf to woff2 converter](https://everythingfonts.com/ttf-to-woff2) also by Everything Fonts reduced the size to 9 Kb.

For Big Shoulders, the TTF file for the variable font has a size of 319 Kb. The size of the TTF file for Big Shoulders 24 pt Bold as a static font is only 95 Kb. A font size of 24 pt is equivalent to 32 px. The next larger font size available in the download as a static font is 36 pt or 48 px. I decided to use the static 24 pt font. Inspection with Wakamai Fondue showed 1065 glyphs. Subsetting the font to Basic Latin and converting the file to WOFF2 reduced the size to 10 Kb.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

I'm an aspiring web developer and a former chemist. What I bring from chemistry to software development is a systematic approach to problem solving and the perseverance to not give up easily.

- Frontend Mentor - [SabineEmden](https://www.frontendmentor.io/profile/SabineEmden)
- Personal Website - [Sabine Emden](https://www.sabineemden.com/)
- Mastodon - [@sabineemden](https://social.tchncs.de/@sabineemden)

## Acknowledgments

This project uses Josh Comeau's [CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/).

The font families in this project are [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca) and [Big Shoulders](https://fonts.google.com/specimen/Big+Shoulders). The fonts are licensed under the [Open Font License](https://openfontlicense.org/open-font-license-official-text/).
