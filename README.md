<!-- markdownlint-disable MD022 MD032 -->
# [Shovan Chatterjee](https://twitter.com/shovan_ch)

## 100 Days Of Code - Round 2 Log

**Commitment:** ***I will code for at least an hour a day for the next 100 days.***

Inspired by [Alexander Kallaway](https://twitter.com/ka11away)'s #100DaysOfCode challenge. More details about the challenge can be found here: [100daysofcode.com](http://100daysofcode.com/) or [the official repo](https://github.com/Kallaway/100-days-of-code).

|  Start Date   | End Date     |
| ------------- | ------------ |
| Jan 1st, 2018 | ------------ |

## Goals

- Code 1 hour daily
- Commit progress to github everyday
- Write a medium article every 10 days about lessons learned
- Become MERN stack developer
- Complete the [Fullstack developer path](https://github.com/shovanch/fullstack-web-developer-path)

### January
- Complete the [Udemy JS course](https://www.udemy.com/the-complete-javascript-course/)
- Complete Javascript30
- Make 5 design based frontend projects
- Make 5 JS based frontend projects

### February
 - React Month

### March
- Node Month

# Log

<!--

## XX.
### Day XX: Month X, Xday

**Today's Progress :**

**Thoughts :**

**Thing(s) learned :**

**Link(s) to work :**

---

-->

## 03. Making CSS grid responsive
### Day 03: January 4, Thursday

**Today's Progress :** Had a bit of work left on the CSS grid project from yesterday. Wrote the media queries for the layout. Now, it looks on great on all widths.

**Thoughts :** Missed last day. Had extreme headache. Couldn't focus on work. Neeed to keep this missed day numbers minimal. Writing the media queries for grid and realized how easy it is now compared to the tons of code for floats and even flexbox. Most of the layout can be made responsive at the first place using properties like minmax(), min-content, max-content. Its all buttery smooth. The only problem is browser support. I dont want to write duplicate code for old browsers. So, from now on its going to be all grids. Flexbox at most as fallback. Couldn't start the medium-clone project as expected today. Lets get on with it with full force from tomorrow. 🔥

**Thing(s) learned :**
- How to make CSS grid layout responsive using media queries
- How to make fallback for grid using @supports rule

**Link(s) to work :**
- [CSS grid project code](https://github.com/shovanch/advanced-css-course-projects/tree/master/Nexter)
- [Live project site](https://shovanch.com/advanced-css-course-projects/Nexter/)


---

## 02. Completed Nexter project
### Day 02: January 2, Tuesday

**Today's Progress :** Completed the nexter project as part of Advanced CSS course.

**Thoughts :** Learned lot about CSS Grid in this projects, in various situations and use cases. Will complete the media queries tomorrow. Then, moving on to the project- Cloning the homepage of Medium using grid. Quite excited. The completed project looks really great.

![Webpage gif](https://media.giphy.com/media/d2iYkL9TzZj7kGBO/giphy.gif)

**Thing(s) learned :**
- Using ::before and ::after pseudo elements as grid items
- How to make the commonly used 'Seen on' section

**Link(s) to work :**
- [CSS grid project code](https://github.com/shovanch/advanced-css-course-projects/tree/master/Nexter)
- [Live project site](https://shovanch.com/advanced-css-course-projects/Nexter/)  (Not fully-responsive yet)

---

## 01. Working with CSS Grid
### Day 01: January 1, Monday

**Today's Progress :** Made a reusable card component using grid and flexbox together. Worked on making a image gallery using CSS grid. Quite great, once got the hang of the syntax.

**Thoughts :** So far so good. CSS grid looks quite promising. It also made working with CSS layouts fun instead of the hack-n-slash with float. Important thing to note that Grid and flexbox compliment each other, not as replacement. Grid for 2D, Flexbox for 1D. The image gallery part was really cool. Basically it was just laying the template-columns and then placing each grid item following the grid-lines. Kid's stuff.

![capture](https://user-images.githubusercontent.com/16104985/34470598-f740ecac-ef5a-11e7-9dcc-b674633026f8.PNG)

Also learned a rather cool emmet trick to use while writing HTML markup for this type of image gallery

```html
<!-- This and then pressing tab would-->
(img.gallery__img--$[src="img/gallery-$"][alt="Gallery Image $"])*5

<!-- print this number of times specified in increasing order, 😎-->
<img src="img/gallery-1" alt="Gallery Image 1" class="gallery__img--1">
```
**Thing(s) learned :**
- How to make a simple card component using grid and flexbox
- Grid overlapping method + z-index to position items.
- `<sup>` tag to write superscript numbers
- object-fit property for images to maintain aspect ratio

**Link(s) to work :**
- [CSS grid project code](https://github.com/shovanch/advanced-css-course-projects/tree/master/Nexter)
- [Live project site](https://shovanch.com/advanced-css-course-projects/Nexter/)  (work-in-progress)

---

