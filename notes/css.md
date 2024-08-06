# CSS

## 1. CSS
- CSS stands for Cascading Style Sheets
- Used to style and layout web pages
- Separates the presentation from the HTML structure

## 2. CSS Syntax
- Selector: Targets HTML elements
- Declaration block: Contains one or more declarations
- Declaration: Property-value pair
```css
selector {
  property: value;
}
```

## 3. Selectors
- Element selector: `p`
- Class selector: `.classname`
- ID selector: `#idname`
- Attribute selector: `[attribute]`
- Descendant selector: `div p`
- Child selector: `div > p`

## 4. Colors
- Named colors: `red`, `blue`, `green`
- Hexadecimal: `#FF0000` (red)
- RGB: `rgb(255, 0, 0)` (red)
- RGBA: `rgba(255, 0, 0, 0.5)` (semi-transparent red)

## 5. Units
- Pixels: `px`
- Percentages: `%`
- Em: `em` (relative to font-size)
- Rem: `rem` (relative to root element's font-size)
- Viewport units: `vw`, `vh`

## 6. Box Model
- Content: The actual content of the element
- Padding: Space between content and border
- Border: Surrounds the padding
- Margin: Space outside the border

## 7. Display Properties
- `block`: Takes up full width
- `inline`: Takes up only necessary width
- `inline-block`: Combines features of both
- `flex`: Enables flexible box layout
- `grid`: Enables grid layout

## 8. Positioning
- `static`: Default positioning
- `relative`: Relative to its normal position
- `absolute`: Relative to nearest positioned ancestor
- `fixed`: Relative to the viewport

## 9. Flexbox
- Container properties: `display: flex`, `flex-direction`, `justify-content`, `align-items`
- Item properties: `flex-grow`, `flex-shrink`, `flex-basis`

## 10. CSS Grid
- Container properties: `display: grid`, `grid-template-columns`, `grid-template-rows`, `gap`
- Item properties: `grid-column`, `grid-row`

## 11. Responsive Design
- Media queries: `@media screen and (max-width: 600px) { ... }`
- Fluid layouts
- Flexible images: `max-width: 100%`

## 12. CSS Variables (Custom Properties)
```css
:root {
  --main-color: #007bff;
}
body {
  color: var(--main-color);
}
```

## 13. Transitions and Animations
- Transitions: Smooth changes between property values
- Animations: More complex, keyframe-based movements

## 14. Inheritance
- Some properties are inherited from parent elements
- Can be controlled with `inherit`, `initial`, and `unset` keywords

## 15. Specificity
- Determines which CSS rule is applied when conflicts occur
- More specific selectors take precedence