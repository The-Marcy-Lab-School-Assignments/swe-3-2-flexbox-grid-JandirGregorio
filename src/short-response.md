# Short Response Questions

Answer the following questions in 2-4 sentences each. Be specific and use vocabulary from the lessons.

## Question 1: Flexbox Basics

What is the difference between a **flex container** and a **flex item**? How do you make an element a flex container?

**Your Answer:**

A **flex container** refers to the HTML tag or the parent element that contains all child elements. A **flex item** refers to the individual items enclosed in a **flex cotainer**. To make an element a flex container, in the _CSS_ file target the **flex container** and write the `display: flex` attribute. Best practice is to use a class name and target it that way in the CSS file.

## Question 2: Main Axis vs Cross Axis

In Flexbox, what is the **main axis** and what is the **cross axis**? How do `justify-content` and `align-items` work with these axes?

**Your Answer:**

In Flexbox, `flex-direction` is set to `row` by default. In this instance, the **main axis** and **cross axis** are the **horizontal** and **vertical** direction, respectively.

When `flex-direction` is set to `column`, the **main axis** and **cross axis** will swap from its default behavior.

`justify-content` allows programmers to move items on the **main axis** and `align-items` on the **cross axis**. This feature makes element positioning more practical.

## Question 3: Flexbox vs Grid

When would you use **Flexbox** vs **CSS Grid**? Give an example of a layout that would be better suited for each.

**Your Answer:**

I would use **Flexbox** when working on a navbar because I can have the items such as search bar, links, and logo on a single block. I can also apply the `justify-content: space-between` to apply space between the items.

I would use **CSS Grid** when displaying items that need to be presented in a matrix manner (e.g. picture gallery). Another aspect to consider is that grid provides the possibility for different grid layouts, making it more flexible to use in this case than **Flexbox**.

## Question 4: The `fr` Unit

What does the `fr` unit do in CSS Grid? Explain what `grid-template-columns: 1fr 2fr 1fr` would create.

**Your Answer:**

A fractional unit or `fr` unit utilizes one fraction (or the specified value) of the available space. `grid-template-columns: 1fr 2fr 1fr` creates three columns with `1fr`, `2fr`, and `1fr` of the available space, respectively. This means that the middle column takes up 50% of the space, while the outer columns take 25% of the space each.

## Question 5: Media Queries

What is a **media query** and why are they important for **responsive web design**? Write an example of a media query that applies styles for screens 768px and wider.

**Your Answer:**

A **media query** is a CSS tool that allows programmers to specify _breakpoints_ that will alter the way things look based on the device's screen size. They are important because it allows us to implement websites that adapt their layout accross different devices. This also ensures the content is displayed with no inconsistencies.

For example:

```css
@media (min-width: 768px) {
    body {
        color: magenta;
    }
}
```

This media query will set the `body`'s font color to magenta when the screen is greater than **768** pixels.

## Question 6: Mobile-First Design

What does **mobile-first design** mean? What are the benefits of taking a mobile-first approach versus a desktop-first approach?

**Your Answer:**

Taking a **mobile-first-design** approach means that mobile screens are the starting point for the website or application. This allows programmers to add all the complexity and optimization to then scale it to larger screens responsively. This is also important because majority of the website traffic comes from mobile devices.
