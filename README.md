### Search Bar Expanding

This project demonstrates a simple HTML and CSS implementation of a search bar that expands when focused. The search bar is initially small and resizes to fill the width of its container when clicked or focused on, creating an intuitive and smooth user experience.

### Features
- Search bar: A search input field styled with CSS that dynamically changes width on focus.
- Accessible label: A hidden label for screen readers, ensuring accessibility.
- Smooth transition: CSS transition effect for smooth expansion of the search bar when focused.

### Code Structure

## HTML:
- Basic structure with a search input field wrapped inside a container.
- A hidden label is included for accessibility.
## CSS:
- The search bar has a default width of 30%, which expands to 100% when focused.
- Transitions and animations are controlled through CSS, giving the input a smooth transition effect.
- Variables are used to control border colors for regular and focused states.

### How it Works

- The search bar is styled to have a smaller initial width (30%), and when the user clicks on the input field (focus), it expands to the full width of its container (100%).
- The transition is handled via the CSS transition property, which smoothens the change in width and border color.
- The .hide class is used to hide the label visually while keeping it available for screen readers for improved accessibility.

### Installation & Usage

1- Clone the repository.
2- Include the index.html and index.css files in your project.
3- Open the index.html file in any web browser to see the expanding search bar in action.

### Demo

When the user clicks on the search input field, the search bar expands from 30% width to 100% of its container. The border also changes color, signaling focus. When the input field is no longer focused, it reverts back to its original state.
Example:
Uploading 0929(1).mp4…


