# Dark mode 🌙

Here is an example of dark mode implementation using HTML, SCSS and JavaScript.

### Operation

- Colors for light and dark theme are specified in SCSS variables
  - Light colors selector is `:root` to be used by default
  - Dark colors selector is `[data-theme="dark"]` because we will set an attribute **data-theme** to the **body**
  
- Theme switcher is a checkbox with an `eventListener` on **change**
  - If the checkbox is checked we add the attribute **data-theme** with the value **dark**
  - However we **remove** it to use `:root` colors

