# CHARTS

**Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.**

**The First rhing we need to insert a chart is The canvas element**

At first sight a canvas looks like the img element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the canvas element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified

**The rendering context**

**_The canvas element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. In this tutorial, we focus on the 2D rendering context._**

**APPLYING COLORS AND STYLES**

we used only the default line and fill styles. Here we will explore the canvas options we have at our disposal to make our drawings a little more attractive. You will learn how to add different colors, line styles, gradients, patterns and shadows to your drawings.color is a string representing a CSS color element, a gradient object, or a pattern object

**Drawing text**

The canvas rendering context provides two methods to render text:

- A fillText
- A strokeText
