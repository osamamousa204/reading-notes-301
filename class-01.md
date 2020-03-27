# Responsive web design

Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop. Responsive web design is focused around providing an intuitive and gratifying experience for everyone. Desktop computer and cell phone users alike all benefit from responsive websites.

## Responsive vs. Adaptive vs. Mobile

*Responsive* and *adaptive* web design are closely related, and often transposed as one in the same. Responsive generally means to react quickly and positively to any change, while adaptive means to be easily modified for a new purpose or situation, such as change. 

*Mobile*, on the other hand, generally means to build a separate website commonly on a new domain solely for mobile users. While this does occasionally have its place, it normally isn’t a great idea. Mobile websites can be extremely light but they do come with the dependencies of a new code base and browser sniffing, all of which can become an obstacle for both developers and users.

## Responsive web design is broken down into three main components :

1. flexible layouts
2. media queries
3. flexible media. 

### Flexible Layouts:

flexible layouts is the practice of building the layout of a website with a flexible grid, capable of dynamically resizing to any width. Flexible grids are built using relative length units, most commonly percentages or em units. These relative lengths are then used to declare common grid property values such as width, margin, or padding.

#### Flexible Grid:

Using the flexible grid formula we can take all of the fixed units of length and turn them into relative units. In this example we’ll use percentages but em units would work equally as well. Notice, no matter how wide the parent container becomes, the section and aside margins and widths scale proportionally.

### Media Queries:

Media queries were built as an extension to media types commonly found when targeting and including styles. Media queries provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation for example. Being able to apply uniquely targeted styles opens up a world of opportunity and leverage to responsive web design.


### floats:

The float is a CSS property specifies how an element should float.

**positioned elements ignores the float property**

**CSS Syntax:**
float: none|left|right|initial|inherit;
### clear:

The clear property specifies on which sides of an element floating elements are not allowed to float.
**CSS Syntax:**
clear: none|left|right|both|initial|inherit;

# SMACSS:

SMACSS (pronounced “smacks”) is more style guide than rigid framework. SMACSS is a way to examine your design process and as a way to fit those rigid frameworks into a flexible thought process. It is an attempt to document a consistent approach to site development when using CSS.

At the very core of SMACSS is categorization. By categorizing CSS rules, we begin to see patterns and can define better practices around each of these patterns.

#### There are five types of categories:

1. Base
2. Layout
3. Module
4. State
5. Theme

**Base rules** are the defaults. They are almost exclusively single element selectors but it could include attribute selectors, pseudo-class selectors, child selectors or sibling selectors. Essentially, a base style says that wherever this element is on the page, it should look like this.

**Layout rules** divide the page into sections. Layouts hold one or more modules together.

**Modules** are the reusable, modular parts of our design. They are the callouts, the sidebar sections, the product lists and so on.

**State rules** are ways to describe how our modules or layouts will look when in a particular state. Is it hidden or expanded? Is it active or inactive? They are about describing how a module or layout looks on screens that are smaller or bigger. They are also about describing how a module might look in different views like the home page or the inside page.

**Theme rules** are similar to state rules in that they describe how modules or layouts might look. Most sites don’t require a layer of theming but it is good to be aware of it.

[Home Page](https://osamamousa204.github.io/reading-notes-301/)
