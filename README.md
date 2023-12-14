# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
    - [The challenge](#the-challenge)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)


### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [My Live URL](https://product-preview-card-three-eta.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://sass-lang.com/guide/) - For styles


### What I learned

I learned the flex property with flex-grow,flex-shrink, and flex-basis where to use them and get good results.

```html
 <!--I understood how to setup picture element and target one image at a time for different devices and resolution. -->
  <picture>
        <source srcset="images/image-product-desktop.jpg" media="(min-width:700px)">

        <!--Default Image Size-->
        <img src="images/image-product-mobile.jpg" alt="Gabrielle Essence Eau De Parfum">
  </picture>
```

```scss
/*Its important to decide where to use flex property, in this code I learned how to occupy full canvas of the body and control the alignment of content*/

main {
    flex: 1;
    display: flex;
    align-items: center;
}

```

### Useful resources

- [Example resource 1](https://fedmentor.dev/posts/html-plan-product-preview/) : This link was very useful for a semantic stucture and accessibility tricks, very useful for anyone trying to get a good understanding of HTML semantic.
