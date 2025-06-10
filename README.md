# SBA 2: Building a Responsive and Accessible Web Page

This Skills-Based Assessment, designed to test the ability to create a well-structured, responsive, and accessible web page using the HTML and CSS techniques we have learned. The assessment will be done based on the use of semantic HTML, CSS layout techniques (including Flexbox and Grid), and the implementation of accessibility features.

## Features

- Semantic HTML5 structure
- Responsive design using Flexbox and CSS Grid
- Accessibility features including:
  - ARIA roles and attributes
  - Keyboard navigation
  - Skip to content link
  - Proper contrast ratios
  - Accessible forms
- Mobile-friendly navigation
- Responsive layout with media queries

## How to View

1. Clone this repository or download the files
2. Open `HomePage.html` in your web browser
3. Test responsiveness by resizing your browser window or using device emulation in developer tools

## Testing Accessibility

To test the accessibility of this page:

1. Use a screen reader (like VoiceOver or NVDA) to navigate the page
2. Try navigating using only your keyboard (Tab, Shift+Tab, Enter)
3. Use browser developer tools to check contrast ratios
4. Validate with tools like WAVE or axe DevTools

## Reflection Questions

1. **What accessibility challenges did you face, and how did you address them?**
   - The main challenge was ensuring all interactive elements were keyboard-navigable and properly labeled. I addressed this by:
     - Adding proper ARIA attributes
     - Ensuring focus states were visible
     - Implementing skip navigation
     - Providing text alternatives for all meaningful images

2. **How did you ensure that your design was responsive and accessible to all users?**
   - Used mobile-first approach with progressive enhancement
   - Implemented responsive navigation that works on all screen sizes
   - Tested with various screen sizes and assistive technologies
   - Ensured text remained readable at all zoom levels

3. **What tools or resources did you find most helpful during this project?**
   - Class lectures and materials
   - MDN Web Docs for HTML and CSS references
   - Screen readers for testing navigation
   - Browser developer tools for responsive testing