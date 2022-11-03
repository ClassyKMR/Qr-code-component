# Frontend Mentor - QR code component

![Design preview for the QR code component coding challenge](./design/desktop-preview.jpg)

## Welcome! 👋

Thanks for checking out this front-end coding challenge.

This is my first project from Frontend Mentor.

## What I learned

In this project I learned how to properly name CSS classes using BEM convention. 

```css
.block { }
.block__text { }
.block__text--heading { }
```

Also I learned how to center divisions using Flexbox layout.

```css
html {
display: flex;
justify-content: center;
align-items: center;
}
```

This was very basic project and I had a lot of fun during my work. In the next, more complicated projects I will extend README files.

## Mistakes that was made

### 1. Non descriptive alt attribute of the image

    Alternative text to QR image was "QR Image". For the users which use screen reader that text would be useless. It was changed to inform what the QR code does and where it redirects. Now the alt text is "QR Image redirecting to frontendmentor.io".

### 2. Not using `<h1>` element

    Instead of using `<h1>` and `<h2>` elements I used only `<p>` elements. These elements should be used to emphasize primary information in the card.

### 4. Not using `<main>` element

    It is a good practice to use `<main>` element to represent the dominant content of the `<body>` element. Previously content of the website was wrapped in `<div>` element.

### 3. Using absolute length units instead of relative length units

    All units used in project was initially in pixels. It is not a good way to create truly responsive layout. In context of font size it is especially bad practice because it can create problems for users with vision impairments.

