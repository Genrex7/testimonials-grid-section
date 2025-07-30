# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7) challenge on [Frontend Mentor](https://www.frontendmentor.io/). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Testimonials grid section solution](#frontend-mentor---testimonials-grid-section-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [About Me](#about-me)

## Overview

### The challenge

The challenge is to build out this testimonials grid section and get it looking as close to the design as possible.

The users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](/preview.jpg)

### Links

- Solution URL: [Github/Testimonial-Grid-Section]()
- Live Site URL: [Frontend-Mentor/Testimonial-Grid-Section]()

## My process

### Built with

- ![Vite][vite]
- ![NPM][npm]
- ![HTML][html]
- ![CSS][css]
- ![Tailwind CSS][tailwind-css]
- ![Google fonts][google-fonts]
- ![Flexbox][flexbox]
- ![Grid][grid]
- ![Mobile-First-Workflow][mobile-first-workflow]

### What I learned

1.  **Responsive Grid Layouts with Tailwind CSS**:
    One of the key things I learned in this project was how to build responsive layouts using Tailwind CSS’s grid system and breakpoints. This allowed the layout to adapt smoothly across different screen sizes.

    ```html
    <section
    	class="section-testimonials w-[19.5rem] text-[.8125rem] font-medium flex flex-col gap-10 md:w-[80%] md:grid md:grid-cols-2 md:grid-rows-4 desktop:grid desktop:grid-rows-2 desktop:grid-cols-4 desktop:gap-y-8"
    >
    	...
    </section>
    ```

    - I learned how to use responsive utility classes in Tailwind CSS to create flexible and adaptive layouts.

    - I used flex on smaller screens to stack testimonial cards vertically, and switched to grid on larger screens for better structure and spacing.

    - With `md:grid-cols-2 md:grid-rows-4`, I created a two-column layout on medium screens.

    - On desktop screens, I adapted the grid to `desktop:grid-cols-4 desktop:grid-rows-2`, organizing content into a wide four-column grid

2.  **Applying Background Images**:
    I learned how to apply background images effectively using Tailwind CSS. This involved setting the background image, size, and position to ensure it looked good across different devices.

    ```html
    <div
    	class="testimonial desktop:bg-[url(/src/images/bg-pattern-quotation.svg)] bg-no-repeat bg-[top_0rem_right_4.5rem] bg-size-[8rem]"
    ></div>
    ```

    - Used the `bg-[url('/path/to/image.svg')]` utility to set the image.
    - Combined it with bg-no-repeat and custom positioning like `bg-[top_1rem_right_2rem]` to control exactly where the SVG appears.

### Useful resources

- [Vite - DOCS](https://vitejs.dev/guide/) - This helped me understand how to set up a project using Vite and connect it to my HTML and CSS files.
- [Tailwind CSS - DOCS](https://tailwindcss.com/docs/installation/using-vite) - This helped me understand how to use tailwind css for styling the html page.
- [Google Fonts](https://fonts.google.com/) - A great resource for importing fonts easily and making text look unique.

## About Me

- ![Frontend Mentor][frontendmentor] - [@Genrex7](https://www.frontendmentor.io/profile/Genrex7)
- ![Twitter][x] - [@DeepakKMeena07](https://x.com/DeepakKMeena07)

<!-- BADGES -->

[frontendmentor]: https://img.shields.io/badge/Frontend%20Mentor-3F54A3?style=for-the-badge&logo=frontendmentor&logoColor=white
[vite]: https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white
[npm]: https://img.shields.io/badge/NPM-green?style=for-the-badge&logo=npm&logoColor=white
[html]: https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
[css]: https://img.shields.io/badge/CSS-639?style=for-the-badge&logo=css&logoColor=fff
[tailwind-css]: https://img.shields.io/badge/Tailwind_CSS-000?style=for-the-badge&logo=tailwind-css&logoColor=00ADFF
[google-fonts]: https://img.shields.io/badge/Google%20Fonts-4285F4?style=for-the-badge&logo=googlefonts&logoColor=white
[flexbox]: https://img.shields.io/badge/Flexbox-violet?style=for-the-badge&logo=css&logoColor=white
[grid]: https://img.shields.io/badge/Grid-000?style=for-the-badge&logo=css&logoColor=white
[mobile-first-workflow]: https://img.shields.io/badge/Mobile%20First%20Workflow-000?style=for-the-badge&logo=mobile&logoColor=white
[x]: https://img.shields.io/badge/twitter-000?style=for-the-badge&logo=x&logoColor=white
