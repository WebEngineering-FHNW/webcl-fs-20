# webcl-fs-20
Module Web Clients FS 20

## week 1
- Note that todo items are not yet created:
    - [Todo View](https://webengineering-fhnw.github.io/webcl-fs-20/week1/todo/View.html)

## week 2
- Tested different HTML input elements and styled the form using CSS grid and the `:invalid` CSS pseudoclass
    - [CSS Validation Goodie](https://webengineering-fhnw.github.io/webcl-fs-20/week2/CSSValidation.html)

## week 3
Ever wondered how to draw triangles using pure CSS? Find out by studying the following examples.
- [CSS Goodie - drawing triangles](https://webengineering-fhnw.github.io/webcl-fs-20/week3/CSSTriangle.html): Explains how to draw pure CSS triangles
    - using [border-width](https://developer.mozilla.org/de/docs/Web/CSS/border-width) and [drop-shadow](https://developer.mozilla.org/de/docs/Web/CSS/box-shadow)
    - using [clip-path](https://developer.mozilla.org/de/docs/Web/CSS/clip-path)

## week 4
As we now know how to draw triangles, we proceed to build a collapsible section with a rotating triangle to indicate its status.
- [CSS Goodie - collapsible section with pure CSS](https://webengineering-fhnw.github.io/webcl-fs-20/week4/CSSCollapse.html): Explains how to build a collapsible section using pure CSS 
- [The projector pattern](https://webengineering-fhnw.github.io/webcl-fs-20/week4/todo/View.html)

## week 5
How to build a button with a rainbow colored back blur using an anchor element
- [CS Goodie - back blur](https://webengineering-fhnw.github.io/webcl-fs-20/week5/BackBlur.html)
    - using [Flex](https://developer.mozilla.org/de/docs/Glossary/Flex)
    - using [Pseudo-element](https://developer.mozilla.org/de/docs/Glossary/Pseudo-element)
    - using [filter](https://developer.mozilla.org/de/docs/Web/CSS/filter)
    - using [linear-gradient](https://developer.mozilla.org/de/docs/Web/CSS/linear-gradient)
- [The projector pattern - Persons](https://webengineering-fhnw.github.io/webcl-fs-20/week5/person/View.html)

## week 6
How to build an animated underline to mimic Material Design text fields
- [CSS Goodie - animated underline](https://webengineering-fhnw.github.io/webcl-fs-20/week6/person/View.html)
- [CSS Goodie - animated underline css](https://webengineering-fhnw.github.io/webcl-fs-20/week6/person/instantUpdateProjector.css)
    - using [background-image](https://developer.mozilla.org/de/docs/Web/CSS/background-image)
    - using [background-position](https://developer.mozilla.org/de/docs/Web/CSS/background-position)
    - using [background-repeat](https://developer.mozilla.org/de/docs/Web/CSS/background-repeat)
    - using [background-size](https://developer.mozilla.org/de/docs/Web/CSS/background-size)
    - using [transition](https://developer.mozilla.org/de/docs/Web/CSS/transition)
    
This week we generalized the Person projector, so that it may also be used with other models
- [The projector pattern - Persons](https://webengineering-fhnw.github.io/webcl-fs-20/week6/person/View.html)
- [The projector pattern - Persons js](https://webengineering-fhnw.github.io/webcl-fs-20/week6/person/instantUpdateProjector.js)

## week 7
- table projector
    - [solution 1](https://github.com/WebEngineering-FHNW/webcl-fs-20/pull/10/commits/ad4f0fe5b671fda08b1a726b9d70716bdbad0f37)
    - [solution 2](https://gitlab.fhnw.ch/lion/webcl-person-master-view-table-style)

How tu build buttons with a ripple effect, similar to Material Design buttons
- [CSS Goodie - ripple effect](https://webengineering-fhnw.github.io/webcl-fs-20/week7/CssRipple.html)
    - using [pointer-events](https://developer.mozilla.org/de/docs/Web/CSS/pointer-events)
    - using [clip-path](https://developer.mozilla.org/de/docs/Web/CSS/clip-path)
    - using [mix-blend-mode](https://developer.mozilla.org/de/docs/Web/CSS/mix-blend-mode)
    - using JS [style.setProperty](https://developer.mozilla.org/en-US/docs/Web/API/CSSStyleDeclaration/setProperty)
    - using JS [classList](https://developer.mozilla.org/en-US/docs/Web/API/Element/classList)
    
`<canvas>` is an HTML element which can be used to draw graphics via scripting (usually JavaScript). This can, for instance, be used to draw graphs, combine photos, or create simple (and not so simple) animations.
In the following Canvas Gauge example you may explore how the Canvas-Element, which is part of HTML5, is used to render 2D shapes
- [Canvas Gauge Example](https://webengineering-fhnw.github.io/webcl-fs-20/week7/canvas-gauge-sketch/View.html)
    - [Canvas Glossary](https://developer.mozilla.org/en-US/docs/Glossary/Canvas)
    - [Canvas Tutorial](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial)

## week 8
In this CSS Goodie, you may learn how to implement a spotlight feature. While pressing the ALT-Key on your keyboard, a 
spotlight effect is displayed around your mouse. With this kind of effect, you may draw user attention to the spot 
arround your cursor.
- [CSS Goodie - Spotlight](https://webengineering-fhnw.github.io/webcl-fs-20/week8/CssSpotlight.html)
    - using [mousemove event](https://developer.mozilla.org/en-US/docs/Web/API/Element/mousemove_event)
    - using [translateX CSS transform function](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translateX)
- [Bucket SVG Animation](https://webengineering-fhnw.github.io/webcl-fs-20/week8/svg-bucket-sketch/Bucket.html)
- [Bucket WAF SVG Animation](https://webengineering-fhnw.github.io/webcl-fs-20/week8/svg-bucket-sketch/BucketWAF.html)


## week 9
SVG Animation of a signature where the lines are drawn one after the other by manipulating the strokes with JavaScript
- [CSS Goodie - Signature](https://webengineering-fhnw.github.io/webcl-fs-20/week9/svg-signature-sketch/Signature.html)
    - using [stroke-dasharray](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/stroke-dasharray)
    - using [stroke-dasharray](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/stroke-dashoffset)

## week 10
- Vue.js with SVG
  [repository](https://github.com/dev-ale/webcl-2020-vue-svg-animation)
  [live](https://svg-animation-vue.herokuapp.com/)
- React and Web Components with SVG
  [repository](https://github.com/sabinamp/using-svg)
  [pdf](https://github.com/sabinamp/using-svg/blob/9a2963fe283155a82a8612582fc2e58ff4cf291f/docs/SVGSignatureSketch_inReact.pdf)
- Angular with SVG
  [repository](https://gitlab.fhnw.ch/damir.grgic/svg-eyes-angular)
- optional: Mini
  [repository](https://github.com/Dierk/fs19-wodss-client)
  [live](https://dierk.github.io/fs19-wodss-client/ProjectAllocationBundle.html)

