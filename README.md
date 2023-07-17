# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

The Challenge is to build out this landing page and get it looking as close to the design as possible.

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![desktop design](./images/Screenshot%202023-07-17%20113817.png)
![mobile design](./images/Screenshot%202023-07-17%20113901.png)

### Links

- Solution URL: [GitHub Solution](https://your-solution-url.com)
- Live Site URL: [Netlify Live Project](https://64b4dfd829229938b0067a2f--lovely-babka-071b6f.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Sass preprocessor

### What I learned

"In this project, I had the opportunity to create a landing page using a combination of HTML, CSS, Sass, Flexbox, and Grid. One of the main skills I developed was the effective use of Sass, particularly leveraging its power mixins, nesting, variables, and parameters. By utilizing mixins, I was able to streamline my code and reuse common styles throughout the project. The nesting feature of Sass allowed me to write more organized and readable styles by nesting selectors within one another. Moreover, I grasped the concept of variables, which enabled me to define reusable values for colors, font sizes, and other properties. With the use of parameters, I could customize the behavior of my mixins based on specific needs. Overall, this project helped me gain a deeper understanding of front-end web development techniques and improved my ability to create responsive and visually appealing landing pages."

```css
@mixin myFlex($align-item, $flex-direction) {
  display: flex;
  justify-content: center;
  align-items: $align-item;
  flex-direction: $flex-direction;
}

@mixin myBtn($bg_color) {
  font-size: $ParaText;
  font-family: $Bai_Jamuree;
  padding: 0.7rem 1.5rem;
  border-radius: 25px;
  border: none;
  background-color: $bg_color;
  color: white;
  font-weight: 800;
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  cursor: pointer;
}

@mixin sectionHeading {
  font-size: 2rem;
  font-family: $Bai_Jamuree;
  font-weight: 800;
  text-align: center;
  color: $Dark_Grayish_Blue;
}

@mixin sectionPara {
  font-size: $ParaText;
  font-family: $Bai_Jamuree;
  font-weight: 400;
  color: $Grayish_Blue;
  text-align: center;
  width: 45%;
  margin-top: 1rem;
  line-height: 1.75rem;
}
```

### Continued development

"Moving forward, I am eager to further enhance my front-end development skills by fully transitioning from CSS3 to Sass. The power and flexibility that Sass provides have become evident to me during this project, and I believe that diving deeper into Sass will greatly strengthen my foundation in front-end development. By utilizing advanced features such as mixins, nesting, variables, and parameters, I aim to streamline my code even further and make it more modular and maintainable. Additionally, I plan to explore other Sass functionalities, such as partials and imports, to organize my stylesheets more efficiently. I am excited to continue learning and implementing best practices in front-end development, keeping up with the latest trends and techniques to create visually stunning and responsive websites."

### Useful resources

- [Sass Preprocer](https://sass-lang.com/) - This helped me for styling my landing page effectively . I really liked superpower of sass like mixin, nesting, variables,parameter.

## Author

- Linkedin - [@im-vashukashyap](https://www.linkedin.com/in/im-vashukashyap/)
- Frontend Mentor - [vashu-kashyap](https://www.frontendmentor.io/profile/vashu-kashyap)
- GitHub - [vashu-kashyap](https://github.com/vashu-kashyap)
