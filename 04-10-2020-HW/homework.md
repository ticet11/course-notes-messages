## April 10, 2020 Homework
---

### **Styling with SCSS**

**What is a SCSS mixin?**

A mixin is a tool that lets you reuse code blocks, to avoid repetition. They will accept arguments, when necessary.

**Will SCSS render in the browser?**

No, browsers only read CSS, so it has to be converted.

**How do you assign a variable in SCSS and give me a use case?**

```
$main-color: #3b5859;
$secondary-color: #008080;

.sidebar-container {
    border: 1px solid $secondary-color;
}

.sidebar-container h1 {
    color: $main-color;
}
```

**What is variable scope?**

The more specific variable is the one that gets used.

**What is Pseudo Selector Nesting**

It's just like regular nesting, but with pseudo selectors. Saves a bit of space/time/typing and keeps things looking a bit neater. (I don't remember discussing this specific aspect of nesting in class, though.)

```
.very-cool-link a {
    &:visited {
        color: red;
    }

    $:hover {
        font-size: 2em;
        color: green;
    }
}
```

**Why would you use default variables in SCSS?**

You may have some basic styles you want most of the page to have, like the color of section headers, with a few different colors in between. If you have a default, you only need to enter arguments for the few that are differing.

**What is the purpose of SCSS?**

It's a great way to keep CSS cleaner and easier to work with. You can save a lot of time and type a lot less if you make use of the tools like arguments and loops.

**What are some differences between SASS and SCSS?**

| SASS | SCSS |
| ----------- | ----------- |
| Original Form | More Common |
| Very particular syntax | More user friendly |
| Less Popular | Looks like CSS | 

**What is the SCSS @import Directive used for?**

@import allows you to utilize the content of another file in the file you import to.

**What is the purpose of the @content Directive in SCSS?**

@content allows us to send a code block through a mixin.

---

### **CSS Grid Basics**

**What is the main purpose of CSS Grid?**

CSS Grid is a powerful layout system that makes styling HTML much more intuitive than it was without.

**How do you start using CSS Grid with CSS?**

<pre>
.class-name {
    <b>display: grid;</b>
}
</pre>

**What is grid gap used for?**

grid-gap is the outdated way to put space between your grid items. The new way is, simply, gap.

**What are grid columns?**

Grid columns are the vertical lines.

**What is the CSS grid repeat function?**

The repeat function allows you to create a pattern of measurements for rows or columns, so you don't have to type out each one individually.

**What does 1fr represent?**

A single fractional unit. 1fr alone, is 1/1 or 100%. When you have 1fr 1fr, 1fr represents 1/2 or 50%. Etc.

**What are grid rows?**

Grid rows are the horizontal lines.

**What is the purpose of Justify Items?**

Justify Items aligns items along the row axis.

**What is the purpose of Align Items?**

Align Items aligns items along the column axis.

**What does grid-column-start do?**

grid-column-start defines where an item will begin on the column axis of a grid container.

---

### **Flexing with Flexbox**

**What is the main purpose of Flex Box?**

Another tool to make styling more intuitive than vanilla CSS.

**How do you start using Flex Box with css?**

<pre>
    .class-name {
        <b>display: flex;</b>
    }
</pre>

**Which should you use? Flex Box or CSS Grid?**

You don't have to choose between the 2 and often it can be very beneficial to use both.

**After declaring display flex, which elements are going to be affected by your flex styles?**

The children of the class you declared display: flex will be the grid items.

**What is the purpose of Flex Direction?**

To arrange the flex items in rows or columns.

**What is the purpose of Justify Content?**

Justify Content aligns the items on your main axis. Rows would be the default, so it would align horizontally.

**What is the purpose of Flex Grow?**

Flex Grow instructs how each item will use of the extra space proportionally.

**What is the purpose of Flex Shrink?**

Flex Shrink defines how quickly an item will give up it's own space when the viewport shrinks.

**What is the purpose of Flex Wrap?**

Flex box does not come with a natural wrap, so if you do not use Flex Wrap, your items may go outside the viewport or container.

**What is the purpose of Align Items?**

Align Items aligns the items on the cross direction. Because flexbox goes in rows by default, Align Items would define the vertical alignment.

