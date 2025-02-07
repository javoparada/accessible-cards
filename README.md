# NoJS Accessible Cards

## Overview
This project demonstrates an alternative approach to creating accessible, fully clickable cards using only HTML and CSS—without relying on JavaScript. The solution leverages CSS pseudo-elements and flexbox for layout while ensuring compliance with WCAG accessibility standards.

## Features
- **Fully Clickable Area**: Each card is clickable by applying a `::before` pseudo-element on the anchor tag that extends over the entire card.
- **Semantic HTML**: Uses a `<ul>` list structure with `<li>` elements containing `<article>` elements for each card.
- **Keyboard Navigation**: The approach ensures that users can navigate and interact with the cards using the keyboard, preserving a logical tab order.
- **Focus Styles**: Uses `:has(:focus-visible)` to provide clear focus indication when navigating with the keyboard.

## Accessibility Considerations
- Ensures that screen readers and keyboard users can interact with the card elements effectively.
- Focus visibility is maintained using `:has(:focus-visible)` to highlight active cards.
- `::before` is non-interactive and does not interfere with screen readers, ensuring accessible navigation.

## Conclusion
This approach provides a clean and accessible way to create fully clickable cards without JavaScript, ensuring that users relying on assistive technologies can navigate effectively. It also maintains a semantic and structured HTML approach, enhancing usability and accessibility.

