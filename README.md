# Frontend Mentor - Pod Request Access Landing Page

This is a solution to the [Pod request access landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/pod-request-access-landing-page-eyTmdkLSG). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

* [Overview](#overview)

  * [The Challenge](#the-challenge)
  * [Screenshot](#screenshot)
  * [Links](#links)
* [My Process](#my-process)

  * [Built With](#built-with)
  * [What I Learned](#what-i-learned)
  * [Continued Development](#continued-development)
  * [Useful Resources](#useful-resources)
* [Author](#author)

---

## Overview

### The Challenge

Users should be able to:

* View the optimal layout for the site depending on their device's screen size
* See hover states for interactive elements
* Receive an error message when the form is submitted if:

  * The `Email address` field is empty: "Oops! Please add your email"
  * The email format is invalid: "Oops! Please check your email"

### Screenshot

![Preview](./preview.jpg)

### Links

* [Live Site URL](https://pod-request-access-landing-page-ruddy.vercel.app/)
* [Solution on Frontend Mentor](https://www.frontendmentor.io/solutions/pod-request-access-landing-page---tailwindcss-S_Bx6w2CPp)

---

## My Process

### Built With

* Semantic HTML5 markup
* TailwindCSS (Utility-first CSS framework)
* Mobile-first responsive design
* Flexbox and CSS Grid layout
* Accessibility-friendly HTML structure

### What I Learned

This project helped me strengthen my skills in:

* Using **TailwindCSS utilities** for responsive layouts and form styling
* Building **mobile-first** components that progressively adapt to larger screens
* Managing **background images responsively** with conditional rendering for mobile, tablet, and desktop
* Implementing **form validation states** using `group-invalid`, `focus-within`, and pseudo-classes in TailwindCSS

Example:

```html
<p class="invisible text-sm group-invalid:visible text-red">
  Oops! Please check your email
</p>
```

### Continued Development

I plan to explore:

* Improving accessibility and semantic structure using ARIA roles
* Using Tailwind’s `@layer` feature for better component organization
* Exploring `form validation` with JavaScript for richer UX

### Useful Resources

* [TailwindCSS Docs](https://tailwindcss.com/docs) – Core reference for utilities
* [CSS Tricks - Responsive Images](https://css-tricks.com/responsive-images-youre-just-changing-resolutions-use-srcset/) – Helped with understanding responsive imagery
* [Hero Patterns](https://heropatterns.com/) – Great for background design inspiration

---

## Author

* Website – [iwaola.me](https://iwaola.me)
* Frontend Mentor – [@fawaziwalewa](https://www.frontendmentor.io/profile/fawaziwalewa)
* Twitter – [@IwalewaFawaz](https://twitter.com/IwalewaFawaz)
