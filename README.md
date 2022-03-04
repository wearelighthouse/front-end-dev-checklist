# Front-end Dev Checklist (WIP)

#### General

- [ ] Filenames correctly match the single template, component, script, etc. inside each file.  
- [ ] 'Magic numbers' are avoided where possible, otherwise have explanation e.g. a suitable variable name or comment.  


#### HTML
- [ ] I’ve used [semantic markup](https://htmlreference.io/).  
- [ ] I’ve used [ARIA properties](https://www.w3.org/TR/using-aria) where applicable.  


#### CSS

- [ ] BEM Class names match up with my HTML structure
- [ ] C for Components, O for Objects, U for Utilities
- [ ] Checked caniuse.com for use of newer CSS properties
- [ ] Tested across multiple screen sizes
- [ ] Tested across multiple browsers
- [ ] Tested across multiple devices
- [ ] Used rems, CSS var(--variables) and $sass-variables in place of magic values (e.g. 27px, #303)
- [ ] Interactive elements have :hover and :focus and :focus-visible states 


#### JavaScript

- [ ] Gracefully degrades without Javascript (where possible).
- [ ]


#### SVG

- [ ]

#### IMG

- [ ] Used alt tag to improve accessibility.
- [ ] Have `loading="lazy"` and `width` and `height` attributes if possible.
