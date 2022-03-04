# Front-end Dev Checklist (WIP)


#### General

- [x] I've included the [Front-end Dev Checklist](https://github.com/wearelighthouse/front-end-dev-checklist) in my PR.
- [ ] Filenames correctly match the single template, component, script, etc. inside each file.
- [ ] 'Magic numbers' are avoided where possible, otherwise have explanation e.g. a suitable variable name or comment.
- [ ] TODOs have been documented elsewhere or have been removed.
- [ ] `console.log()`s. `var_dump`s or other temporary debugging techniques have been removed.
- [ ] No build task or browser warnings/errors have been introduced.


#### HTML
- [ ] Markup is [semantic](https://htmlreference.io/).
- [ ] [ARIA properties](https://www.w3.org/TR/using-aria) used where applicable.


#### CSS

- [ ] BEM class names match up with HTML structure.
- [ ] Namespace prefixes: `c-` for **c**omponents, `o-` for layout **o**bjects`, `u` for **u**tilities.
- [ ] Utility classes e.g. `u-ml-4` and `u-color-red` have been used instead of hardcoded values.
- [ ] rems and other units have been used in place of `px` where appropriate.
- [ ] Interactive elements have :hover and :focus and :focus-visible states.


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
