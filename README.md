# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

This challenge was for the user to preview a simple product card using basic HTML and CSS skills,
while optimazing the preview layout accordily to the screen size.

### Screenshot

This is a screenshot for my solution while previewing in a mobile screen:

![mobile preview screenshot](./Screenshot%202022-10-24%20at%2021-18-20%20Mobile%20Frontend%20Mentor%20Product%20preview%20card%20component.png)

This is a screenshot for my solution while previewing in a desktop screen:

![Desktop preview screenshot](./Screenshot%202022-10-24%20at%2021-18-20%Screenshot%202022-10-24%20at%2021-17-35%20Desktop%20Frontend%20Mentor%20Product%20preview%20card%20component.png)

### Links

- Github URL: [Github solution product card](https://github.com/nettopasquale/productCard)
- Live Vercel URL: [Vercel live site product card preview](https://productcard.vercel.app/)

## My process

Basicaly I approached the Mobile-first workflow to ensure the card component would be correctely viewed on mobile screens,
and then I simply adjusted the paddings when it reaches the minimum size for the tablets screens. As the challenge only provided
one product card, it didn't made sense adjusting the card to acomodate for bigger screens, though if it had slider of products,
this would require adjustments.

For the product image, I imported the provided pictures using ```background-image``` css property, and with ```contain size```
to make the picture propertly fit inside de white container.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### Continued development

Actually, I believe the HTML semantics is a field that I should continue to practise and improve position skills with flexbox,
since the main container was, basicaly, an empty container, that only showed the white box, image, with the text sections inside
it. This made a problem to actually position all the text and button correctly inside the box content, and it was worse with
desktop screen.

So one of my main objectives is to improve on HTML semantics to avoid using ```postion: relative``` and ```top and left``` as much
as possible.

## Author

- Github - [nettopasquale](https://github.com/nettopasquale)
- Frontend Mentor - [@nettopasquale](https://www.frontendmentor.io/profile/nettopasquale)
- LinkedIn - [Pasquale Milone Netto](https://www.linkedin.com/in/pasquale-milone-netto/)
