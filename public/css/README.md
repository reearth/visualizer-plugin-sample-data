# Plugin Playground Presets Styling

A consistent UI styling system for Plugin Playground examples.

## Overview

This stylesheet provides a standardized design framework for all plugin examples in the Plugin Playground. It ensures a consistent and modern look across plugins while simplifying the styling process.

## Installation

Add this single line to the beginning of your plugin's CSS:

```css
/* Generic styling system that provides consistent UI components and styling across all plugins */
@import url("https://reearth.github.io/visualizer-plugin-sample-data/public/css/preset-ui.css");
```

## Features

- **Global Settings**: Basic resets, typography (font family, size, and color), and box-sizing.
- **Buttons**: Different styles for primary, danger, neutral, and success buttons, including active and disabled states.
- **Form Elements**: Styling for inputs, placeholders, and common form behaviors.
- **Layout Utilities**: Flex layouts, grid systems, alignment, spacing, and gap utilities.
- **Backgrounds & Text**: Color utilities for backgrounds and text, along with font size and weight helpers.
- **Responsive Design**: Built-in classes for responsive layouts

## Apply Classes

Utilize the predefined CSS classes in your HTML markup to style buttons, forms, layouts, etc. For example:

- Use .btn-primary for primary buttons.
- Apply .display-flex to create a flex container.
- Use .theme-content.light or .theme-content.dark to switch between themes.

## Example Components

### Buttons

```html
<button class="btn-primary">Primary</button>
<button class="btn-danger">Danger</button>
<button class="btn-neutral">Neutral</button>
<button class="btn-success">Success</button>
```

### Form Elements

```html
<input type="text" placeholder="Enter text here" />
```

### Layout

```html
<div class="display-flex gap-8">
  <div class="flex-column">Column 1</div>
  <div class="flex-column">Column 2</div>
</div>
```

### Common Utilities

#### Spacing

- `p-8`: Padding 8px
- `p-16`: Padding 16px
- `mt-8`: Margin top 8px
- `mb-8`: Margin bottom 8px

#### Layout

- `display-flex`: Flex container
- `flex-column`: Column direction
- `flex-between`: Space between items
- `gap-8`: 8px gap between items

#### Visual

- `rounded-sm`: Small border radius
- `primary-shadow`: Standard box shadow
- `primary-background`: Light gray background

## Best Practices

- Import the preset CSS at the beginning of your plugin stylesheet
- Use the provided classes instead of writing custom CSS when possible
- Use semantic button colors based on their function

## License

This styling system is provided as part of the Plugin Playground ecosystem.
