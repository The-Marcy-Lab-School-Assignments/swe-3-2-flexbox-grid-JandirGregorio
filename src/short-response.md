# Short Response Questions

Answer the following questions in 2-4 sentences each. Be specific and use vocabulary from the lessons.

## Question 1: Flexbox Basics

What is the difference between a **flex container** and a **flex item**? How do you make an element a flex container?

**Your Answer:**

A **flex container** refers to the HTML tag or the parent element that contains all elements that will be affected by the flex attributes. A **flex item** refers to the individual items that exist within a **flex cotainer**. To make an element a flex container, in the _CSS_ file target the **flex container** and write the `display: flex` attribute. Best practice is to use a class name and target it that way in the CSS file.

## Question 2: Main Axis vs Cross Axis

In Flexbox, what is the **main axis** and what is the **cross axis**? How do `justify-content` and `align-items` work with these axes?

**Your Answer:**

In Flexbox, by default `flex-direction` is set to `row`. So in this case, the **main axis** and the **cross axis** are the **horizontal** and **vertical** direction where items are placed in a container, respectively. However, if `flex-direction` is set to `column`, the **main axis** and **cross axis** will switch places. `justify-content` allows programmers to move items on the **main axis** and `align-items` on the **cross axis**.

## Question 3: Flexbox vs Grid

When would you use **Flexbox** vs **CSS Grid**? Give an example of a layout that would be better suited for each.

**Your Answer:**

I would use **Flexbox** when working on a navbar because I can have the items such as search bar, links, and logo on a single block. I can also apply the `justify-content: space-between` to apply space between the items.

I would use **CSS Grid** when displaying items that need to be presented in a matrix manner (e.g. picture gallery). Another aspect to consider is that grid provides the possibility for different grid layouts, making more flexible to use in this case than **Flexbox**.

## Question 4: The `fr` Unit

What does the `fr` unit do in CSS Grid? Explain what `grid-template-columns: 1fr 2fr 1fr` would create.

**Your Answer:**

A fractional unit or `fr` unit utilizes one fraction (or the specified value) of the available space. `grid-template-columns: 1fr 2fr 1fr` creates three columns with `1fr`, `2fr`, and `1fr` of the available space, respectively.

## Question 5: Media Queries

What is a **media query** and why are they important for **responsive web design**? Write an example of a media query that applies styles for screens 768px and wider.

**Your Answer:**

A **media query** is a CSS tool that allows programmers to specify _breakpoints_ that will alter the way things look based on the device's screen size. They are important because it allows us to implement websites that adapt their layout accross different devices. This also ensures the content is displayed with no inconsistencies.

For example:

```css
@media (min-width: 768px) {
    color: magenta;
}
```

This media query will set the font color to magenta when the screen is greater than **768** pixels.

## Question 6: Mobile-First Design

What does **mobile-first design** mean? What are the benefits of taking a mobile-first approach versus a desktop-first approach?

**Your Answer:**

Taking a **mobile-first-design** approach means that the smallest standard screen size is the starting point for the website and then scale it to a larger screen. The benefits is that the code will be cleaner and more predictable because you start with the basics and then add complexity as the screen gets larger. This is also important because websites tend to be more visited on smaller devices rather than large.
