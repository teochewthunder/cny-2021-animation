# CNY 2021 Animaton 

## Ox Head
The way this SVG is structured is slightly different. Elements within the SVG are segrgated into groups using the `g` tag. Each `g` tag is styled using a CSS class, which will determine their fill color. Therefore, different parts of the ox face are different grouos with different fill colors (brown, orange, pale orange).

This is strategic in the sense that different groups occupy a certain layer. So background shading (pale orange) will remain in the back, while outlining (orange) will be in the middle and highlighting (brown) will be in the front. The only exception are the horns, which occupy their own group and are in the back.

## Heart
This is a very simple set of curves and could probably be done better. The final animation is another white heart overlaid on top of the existing red heart, with the red heart animated. The final effect looks like a stylized red heart animating.

## Text
Manually aligned via trial and error. The alignment will probably differ with font faces and sizes.
