# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](./images/Web%20capture_18-1-2024_212314_.jpeg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Vercel](https://qr-code-component-gray-rho.vercel.app/)

## My process

1. Added the img to the html doc and an h2 and p element.
2. Added my name to the attribute section and attached a link to my LinkedIn profile
3. Analysed the image to estimate the correct height and width of the card
4. Added the releventa styling to the elements (color, padding, e.t.c)
5. Imported the Google Font 'Outfit'
6. Adjusted the font size, weight and the text alignment
7. Added box-shadow to the finished product

### Built with

- HTML5
- CSS properties

### What I learned

The correct way to add an image path to an image in your folder:

I used to do this:

```html
<img src="/images/image-qr-code.png" alt="qr code to Frontend Mentor Website" />
```

which did not work as the image would not display on my website. However, after a quick Google search I fured out that I did not add the period before the forward slash which is why it did not work even though the file path was correct.

The correct way to do it is:

```html
<img
  src="./images/image-qr-code.png"
  alt="qr code to FRontend Mentor website"
/>
```

### Useful resources

- [SheCodes box-shadow generator](https://www.example.com) - This helped me create the box shadow without having to code, and then generated the code for me to paste to the element.
- [SheCodes image Uploader](https://www.shecodes.io/uploads) - Allows you to upload an image from your pc to a server and provides you with a link to use that will always be available to use.

## Author

- LinkedIn - [Noceba Jack](www.linkedin.com/in/noceba-jack)
- Frontend Mentor - [@Noceba-Jack](https://www.frontendmentor.io/profile/Noceba-Jack)
