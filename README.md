# CSS-Intermediate-Flexbox-Grid-ResponsiveDesign-Transitions-Animations

testing

## Flexbox

- **Flex containers** are parents
- **flex items** are children

### Parent Properties

- `Flex-flow` is a combination of flex-direction and flex-wrap. e.g. `flex-flow: column wrap`
- `flex-flow: row wrap` is often what you would want for responsive design.
- `space-around` puts space before and after each element. Thus first and last elements will have half the gap on either side than the other elements. The least popular option
- `space-between` puts first and last elements onto edge of container and even space between rest of the elements. usually the better option.
- `space-evenly` puts exactly the same amount of space between each element.
- `align-content: flex-start | flex=end | center | space-between etc` We use these properties to adjust the distance between rows.

### Children Properties

`order: 2` you can use this property to determine order of box. -1 will move to start. 1 will move to the end. 0 is neutral.

`flex-basis:30%`  basically says ‘how wide is this box…sort of’ cannot determine a hard value for width with this, but a close estimation. if you hard-code the width `width:30%` it will negate some of the benefits of flexwrap and the items will always be 30% width and not flex correctly. So, basically use `flex-basis` instead of `width` with flexbox
