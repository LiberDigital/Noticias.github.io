---
title: Sticky navbar only using CSS
date: 2021/9/19
description: Sticky element using CSS only.
tag: web development
author: You
---
## Learn how to create a sticky element with CSS In your website.

### Step 1 : Add CSS

`
div.sticky {
  position: -webkit-sticky; /* Safari */
  position: sticky;
  top: 0;
}
`

An element with `position: sticky;` is positioned based on the user's scroll position.

A sticky element toggles between `relative` and `fixed`, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like `position:fixed;`).

Note: Internet Explorer, Edge 15 and earlier versions do not support sticky positioning. Safari requires a -webkit- prefix (see example below). You must also specify at least one of `top`, `right`, `bottom` or `left` for sticky positioning to work.