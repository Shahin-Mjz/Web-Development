# Different Types of Selectors

When styling a web page, there are many types of selectors available that allow developers to be as broad or as specific
<br>
as they need to be when selecting HTML elements to apply CSS rules to.

Here you will learn about some of the common CSS selectors that you will use as a developer.

**Element Selectors**

The element selector allows developers to select HTML elements based on their element type.

For example, if you use `p` as the selector, the rule will apply to all `p` elements on the webpage.

<i>HTML</i>
```html
<p>Once upon a time...</p>
<p>In a hidden land...</p>
```

<i>CSS</i>
```css
p { 
  color: blue; 
}
```

**ID Selectors**

The ID selector uses the id attribute of an HTML element. Since the id is unique within a webpage, 
<br>
it allows the developer to select a specific element for styling. ID selectors are prefixed with a `#` character.

<i>HTML</i>
```html
<span id="latest">New!</span>
```

<i>CSS</i>
```css
#latest { 
  background-color: purple; 
}
```

**Class Selectors**

Elements can also be selected based on the class attribute applied to them. The CSS rule has been applied to all
<br>
elements with the specified class name. The class selector is prefixed with a `.` character.

In the following example, the CSS rule applies to both elements as they have the `navigation` CSS class applied to
<br>
them.

```html
<a class="navigation">Go Back</a>
<p class="navigation">Go Forward</p>
```

```css
.navigation { 
  margin: 2px;
}
```

**Element with Class Selector**

A more specific method for selecting HTML elements is by first selecting the HTML element, then selecting the CSS
<br>
class or ID.

The example below selects all `p` elements that have the CSS class `introduction` applied to them.

<i>HHTML</i>
```html
<p class="introduction"></p>
```

<i>CSS</i>
```css
p.introduction { 
  margin: 2px;
}
```

**Descendant Selectors**

Descendant selectors are useful if you need to select HTML elements that are contained within another selector.

Let's explore an example.

You have the following HTML structure and CSS rule.

<i>HTML</i>
```html
<div id="blog">
  <h1>Latest News</h1>
  <div>
    <h1>Today's Weather</h1>
    <p>The weather will be sunny</p>
  </div>
  <p>Subscribe for more news</p>
</div>
<div>
  <h1>Archives</h
```1>
</div>

<i>CSS</i>
```css
#blog h1 {
  color: blue;
}
```

The CSS rule will select all `h1` elements that are contained within the element with the ID `blog`. The CSS rule will not
<br>
apply to the `h1` element containing the text `Archives`.

<i>CSS</i>
```css
#blog div h1 {
  color: blue;
}
```

**Child Selectors**

Child selectors are more specific than descendant selectors. They only select elements that are immediate
<br>
descendants (children) of a selector (the parent).

For example, you have the following HTML structure:

<i>HTML</i>
```html
<div id="blog">
  <h1>Latest News</h1>
  <div>
    <h1>Today's Weather</h1>
    <p>The weather will be sunny</p>
  </div>
  <p>Subscribe for more news</p>
</div>
```

If you wanted to style the `h1` element containing the text `Latest News`, you can use the following child selector:

<i>CSS</i>
```css
#blog > h1 {
  color: blue;
}
```

This will select the element with the ID `blog` (the parent), then it will select all `h1` elements that are contained directly
<br>
in that element (the children). The structure of the child selector is a CSS selector followed by the child combinator
<br>
symbol `>` followed by another CSS selector.

**Note** that this will not go beyond a single depth level. Therefore, the CSS rule will **not** be applied to the `h1` element
<br>
containing the text `Today's Weather`.

**:hover Pseudo-Class**

A special keyword called a pseudo-class allows developers to select elements based on their state. Don't worry too
<br>
much about what that means right now. For now, let's look at how the hover pseudo-class allows you to style an
<br>
element when the mouse cursor hovers over the element.

The simplest example of this is changing the color of a hyperlink when it is hovered over. To do this, you add
<br>
the `:hover` pseudo-class to the end of the selector. In the following example, adding `:hover`  to the `a` element will
<br>
change the color of the hyperlink to orange when it is hovered over.

<i>CSS</i>
```css
a:hover {
  color: orange;
}
```

This pseudo-class is very useful for creating visual effects based on user interaction.

**Other Selectors**

There are many other CSS selectors available to style your webpage.
