## Grid System
Why do we use a grid system?
- It's about readibility
- Goes back to print design
2 Components
- Rows
- Columns
A grid is very similar to how you might expect an excel sheet to look. It's like a table, but it's not a table. 
- Uses **Golden Ratio**
- Grids help you achieve
    + Consistency
    + Harmony
    + Symmetry
- Gutter is the margin/space you have between different elements
    + You must keep horizontal gutter consistent
    + Vertical not as important
The point of the grid is that you chunk together relevant information.
**Rule of Thirds**
- 41% top left
- 20% top right
- 25% bottom left
- 14% bottom right
Structure content according to this. Simplified version of the golden ratio.

## Types of Grids
- Manuscript (example: [zeldman.com](http://zeldman.com))
    + 1 column with all info
    + It's like manuscript or a page of a book
- Column Grids (example: [jessicahische.is](http://jessicahische.com))
    + More than one column
    + Like blog with sidebar
- Modular Layout (example: [dribbble](http://dribbble.com))
    + Broken down into different "modules" on the page
    + Pretty simple, rows and columns
- Hierarchical Grid
    + Sort of a mix of many different layouts
    + Encompassing everything that isn't manuscript or modular is hierarchy
    + Organized by most important content
## Extends and Placeholders
- @extend .classname
    + copies styles from other class
    + use in CSS
- Placeholders
    + %classname style rules don't exist (ghost class)
    + can be copied via @extend %classname (no dot before name) 
Check out The Sass Way, Sassmeister

## Grid Mixins
One way similar to @extend **not useful**
- ghost class @mixin classname()
- call it with @include classname

One way similar to variables - **arguments**

syntax @mixin mixinname($argumentname, $argument2) {  
    font-size: $argumentname;
    color: $argument2;
}

call with @include mixinname(value)

.default {
    @extend %btn;
    @include mixinname(value, value);
}

use camelCase

## Matt Leo - Runs a consultant firm (freelance webdev) Schematical
- life is not a closed book test
    + learn to index
    + learn to bookmark
    + it's all changing
- be ready to learn new stuff as long as you're in this game 
- try things
    + trying and failing as fast as you can is good
    + just don't make the same mistake twice
- build in a safe space
- know your tools
- know how you work and learn
- pragmatic means standards - necessary when scaling
- **Business**
    + niche down, it's how you make money
    + who do you want to work for?
    + what do you want to do?
        * are you a designer?
        * are you a coder?
    + find something that's in demand
    + own the **offering**
        * treat your service like a product
    + use discovery contract
    + Make some noise
        * be interacting, active in communities your industry
        * blogging is a big deal
    + Make hot dogs - your most painful lessons shouldn't be hidden
    + Network

## Other Notes
use <code>Tag</code>