# Layout Plan – Phase 4

## Standard I will follow

I am using **Dave Gray’s standard breakpoints** from Lesson 17:

- Small: 576px  
- Medium: 768px  
- Large: 992px  
- Extra Large: 1200px  
- Landscape: max-height: 425px and min-aspect-ratio: 7/4  

---

## My Responsiveness using Media Queries

### Header
- **All Sizes:** Stays full width and centered.
- **Landscape/Small Screens:** Reduce padding for better fit.

### Navigation (nav)
- **Small (576px):** Stacks vertically or collapses.
- **Medium (768px):** May hide or become inline in a tighter layout.
- **Large (992px+):** Horizontal inline-block nav bar returns.
- **Landscape:** Font size reduces, layout stays inline.

### Main Content (main)
- **Small:** Sections stack vertically, images scale 100%.
- **Medium:** Adds side spacing and larger font.
- **Large:** Grid layout for 2 columns.
- **XL:** Grid expands spacing; visuals more spread.
- **Landscape:** Padding reduces, column gap may shrink.

### Sidebar (if used)
- **Small:** Moves below main.
- **Large:** Floats beside main using Grid or Flexbox.

### Footer
- **All Sizes:** Stays centered and sticky.
- **Landscape:** Padding shrinks and text becomes smaller.

---

## Accessibility

- All images have descriptive `alt` text.
- Links use meaningful descriptions.
- Proper heading structure without skipped levels.
- Semantic HTML elements used instead of generic `<div>`s.
- Strong color contrast for readability.