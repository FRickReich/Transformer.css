# TRANSFORMER.CSS

### A Lightweight CSS wrapper for css-only animations.

Transformer.css is a css wrapper to create css-only animations, without the use of javascript. The animations are defined by classes inside your html element. 

## What is it for
Transformer.css can be used to easily rotate css elements around their own axis. It can also change the speed, duration, behavior, direction and transistion effect of the animation without a single line of javascript.

Check out a demo of the idea behind it at <http://codepen.io/FRickReich/pen/jhocd>.

## How to use
1. To initiate Transformer.css, all you have todo is add the css file to the head section of your html file:

```html
<link rel="stylesheet" href="styles/transformer.min.css" type="text/css">
```

2. Add some example wrapper classes to your html-element:
```html
<p class="cube rotate90cw time7s normal infinite linear">Test</p>
```

3. Open your file in a browser and check out what happens.

3. Refer to the Demo file to find out what you can do with this.

## Important note
it is important that you always use ALL wrapper classes, otherwise the animation might now run at all.

## License
Copyright (c) 2016 F. Rick Reich. Licensed under the terms of the MIT license.
http://frickreich.mit-license.org/