# Bitter
## Components
### Box
The Box component is one of the most important components in Bitter. It is used as primitives to construct layouts and compose components. In most cases you can use a Box instead of a div element.

> Box component uses simplified versions of most of the attributes.
> For example, istead of using `onClick` attribute, it uses `press` attribute.
> This is for making sure the codebase is cross platform compatible and minimalistic for the most part.
##### Properties
#
| Property | Type | Description | Default |
| ------ | ------ | ------ | ------ |
| top | mixed | Sets `top` setting depending on the `mode`. |  |
| left | mixed | Sets `left` setting depending on the `mode`. |  |
| bottom | mixed | Sets `bottom` setting depending on the `mode`. |  |
| right | mixed | Sets `right` setting depending on the `mode`. |  |
| flex | mixed | Equals to `flex` in CSS. |  |
| align | string | Equals to `justifyItems` in React. |  |
| justify | string | Equals to `justifyContent` in React. |  |
| direction | string | Equals to `flexDirection` in React. |  |
| wrap | string | Equals to `flexWrap` in React. |  |
| color | string | Equals to `backgroundColor` in React. | "transparent" |
| radius | mixed | Equals to `borderRadius` in React. | `0` |
| shadow | boolean | When `true` applies a shadow from the project settings. | `false` |
| height | mixed | Equals to `height` in CSS. |  |
| width | mixed | Equals to `width` in CSS. |  |
| style | object | Equals to `style` in React. |  |
| press | function | Equals to `onClick` in React. |  |
| opacity | number | Equals to `opacity` in CSS. |  |
| mode | string | Controls the position parameters. You can use `margin`, `padding`, `position` | "margin" |
| position | string | Equals to `position` in CSS. | "relative" |
| overflow | string | Equals to `overflow` in CSS. |  |
| display | string | Equals to `display` in CSS. | "block" |
| all | mixed | Instead of using `top`, `left`, `right`, `bottom`, to apply to all of them. You can use `all`. | `false` |
| border | string | Equals to `border` in CSS. |  |
| styling | string | Equals to `className` in React. |  |
| layer | number | Equals to zIndex in React. |  |
| identifier | string | Equals to `id` in HTML. |  |
| reference | function | Equals to `ref` in React. |  |
