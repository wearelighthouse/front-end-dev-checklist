# Front-end Dev Checklist (WIP)


#### General
- [x] I've included the [Front-end Dev Checklist](https://github.com/wearelighthouse/front-end-dev-checklist) in my PR.
- [ ] Filenames correctly match a single template, component, function, etc. inside each file.
- [ ] 'Magic numbers' are avoided where possible, or have explanation e.g. a suitable variable name or comment.
- [ ] TODOs have been documented elsewhere or have been removed.
- [ ] `console.log()`s. `var_dump`s or other temporary debugging techniques have been removed.
- [ ] No build task or browser warnings/errors have been introduced.
- [ ] Unused code has been removed rather than commented-out.

#### HTML
- [ ] Markup is [semantic](https://htmlreference.io/).
- [ ] [ARIA properties](https://www.w3.org/TR/using-aria) used where applicable.

#### CSS
- [ ] BEM class names match up with HTML structure.
- [ ] Class names have the correct namespace prefixes (c-, o-, s-, t-, u-).
- [ ] Utility classes e.g. `u-ml-4` and `u-color-red` have been used instead of hardcoded values.
- [ ] [Pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes) & [attribut selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Attribute_selectors) have been used over class-based selectors where possible.
- [ ] [Type selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Type_selectors) have only been used within reset, scope, or third-party classes 
- [ ] Interactive elements have `:hover`, `:focus` and `:focus-visible` states.

#### JavaScript
- [ ] Gracefully degrades without client-side JavaScript where possible.

#### Assets (SVG, IMG, etc.)
- [ ] Unnecessary attributes have been removed (either manually, or by using a tool like [SVGOMG](https://jakearchibald.github.io/svgomg/)).
- [ ] Alt tags or visually-hidden text to describe images.
- [ ] `<img>`s have `loading="lazy"` and `width` and `height` attributes if possible.

#### Browser & device support
- [ ] Tested across multiple screen sizes.
- [ ] Tested across multiple browsers.
- [ ] Tested across multiple devices.
- [ ] Checked [caniuse.com](https://caniuse.com/) for support of particular features.
