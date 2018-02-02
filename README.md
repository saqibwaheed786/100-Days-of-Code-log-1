<!-- markdownlint-disable MD022 MD032 -->

# [Shovan Chatterjee](https://twitter.com/shovan_ch)

## 100 Days Of Code - Round 2 Log

**Commitment:** **_I will code for at least an hour a day for the next 100 days._**

Inspired by [Alexander Kallaway](https://twitter.com/ka11away)'s #100DaysOfCode challenge. More details about the challenge can be found here: [100daysofcode.com](http://100daysofcode.com/) or [the official repo](https://github.com/Kallaway/100-days-of-code).

| Start Date    | End Date     |
| ------------- | ------------ |
| Feb 1st, 2018 | ------------ |

## Goals

* Code 1 hour daily
* Commit progress to github everyday
* Write a medium article every 10 days about lessons learned
* Become a MERN stack developer and start freelancing

### Goals for Day 1 - Day 30 (FOCUS -> JS and React)

* Complete the [Udemy JS course](https://www.udemy.com/the-complete-javascript-course/)
* Complete [Javascript30](https://javascript30.com/)
* Build 3 design based frontend projects
* Build 5 JS based frontend projects
* Read the [You don't know JS](https://github.com/getify/You-Dont-Know-JS) book series

* Complete [The React Developer Course](https://www.udemy.com/react-2nd-edition/)
* Build 2 React Projects

# Log

<!--

## XX.
### Day XX: Feb , day

**Today's Progress :**

**Thoughts :**

**Thing(s) learned :**

**Link(s) to work :**

**Tomorrow's Goals**

---

-->

## 01. Learning How JS works

### Day 01: Feb 1, Thursday

**Today's Progress :** Did 'How JS works' section of Complete JS developer course.

**Thoughts :** Learned How JS executes code in the background. Core concepts are really helpful to be a complete developer. It gives a new insight when solving the same problems. <br> Going to break the challenge into short term goals. Like for D30, the goal is to become proficient in JS and get started with React with more time spent on building actual projects.

**Thing(s) learned :**

* Written JS code goes into the JS engine (Ex: Chrome V8 Engine) where it first parsed into AST(Abstract Syntax tree) -> conversion to machine code -> then the machine code gets executed.
* **Execution context** is like a wrapper or container which store the variables and where code is evaluated and executed. Default execution context is global (Which is window object in browser).
* **Execution context** phases are divided into 1. Creation phase and 2. Execution Phase.
* In **Creation Phase**: First, the variable object is created. Code is scanned for function and variable declaration. Which gets moved to the top. Regardless of where they are declared. This behaviour called Hoisting. <br> For each function, a property gets created in the VO and its points to the actual function. As for the variable, it also gets a property is VO, but its value is set as undefined. thats why calling why a variable before its actual declared shows undefined, then it gets defined in execution phase. But, in ES6, this things matter less, as const and let are block scoped.
* **Scopes** : Creating the scope chain is 2nd step of creation phase. <br> Scopes answer where we can access a certain variable. Each function creates a scope. As for _lexical scoping_ it means function written within another function gets access to the scope of outer function. The default scope is global scope (Matters less in ES6).
* **Execution stack VS Scope chain**: Ex. context -> order in which functions are called. <br> Scope chain -> Order in which functions are written lexically.
* **this** : 3rd step of creation of phase of ECxt is determining and setting value of 'this' keyword. <br>
  _In regular function call_ -> 'this' points to the global object (window obj. in browser).
  _In object method call_ -> 'this' points to the object that is calling the method.
* 'this' is not assigned to a value untill a fn. where its actually defined is called. Using this concept, we can use method borrowing to share method between objects.

```javascript
obj1.method = obj2.method;
// calling the method from object 2
obj2.method();
```

**Link(s) to work :**

* [Code examples](https://codepen.io/shovanch/pen/paJdKQ?editors=0012)

**Tomorrow's Goals**

* Complete the DOM section of Complete JS course
* Complete module 1 & 2 of Javascript30

---

<!-- ## 05. Medium UI project
### Day 05: January 19, Friday

**Today's Progress :** Coded two more sections of the Medium UI project. Still have some problem in Firefox, I think most related to grid-row height. Will look into it, after coding it in Chrome. The story feed section seemed bit complex, but at the end it was just changing the flex-direction property and it worked. Cool!!

![Medium clone story feed section](https://user-images.githubusercontent.com/16104985/35186073-56f62e04-fe34-11e7-81d2-e99e61d998ed.png)

**Thoughts :** Over the course of time, my CSS course has improved a lot. Special thanks to the Udemy advanced CSS course. Feels quite confident working with CSS now. Now, need to get to that same level with Javascript too. Starting the JS course from tomorrow.

**Thing(s) learned :** More coding, less learning.

**Link(s) to work :**
- [Live Site](https://shovanch.com/ui-projects/medium-ui) (Work-in-progress)
- [Github Repo](https://github.com/shovanch/ui-projects/tree/master/medium-ui)

---

## 04. Working on MediumUI clone
### Day 04: January 18, Thursday

**Today's Progress :** Back to coding after 2 weeks. Made some progress on the medium UI project. Done with the header and top two sections.

![Medium Homepage clone](https://user-images.githubusercontent.com/16104985/35112487-37cc1cb4-fca4-11e7-853c-5f135b3c7c84.png)

**Thoughts :** Its a good idea to practice both Dev and UI skills by cloning other sites. On that note, working on the medium homepage. Quite confident that I would be able to do it nearly the same. Although there's some margin issue on Firefox. Will debug them after doing it on Chrome.

**Thing(s) learned :** Nothing learnt. Mostly practicing upon the old ones.

**Link(s) to work :**
- [Live Site](https://shovanch.com/ui-projects/medium-ui) (Work-in-progress)
- [Github Repo](https://github.com/shovanch/ui-projects/tree/master/medium-ui)

---

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
<!-- This and then pressing tab would-
(img.gallery__img--$[src="img/gallery-$"][alt="Gallery Image $"])*5

<!-- print this number of times specified in increasing order, 😎
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
 -->
