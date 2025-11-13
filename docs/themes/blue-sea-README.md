# Blue Sea Theme - Usage Guide

A beautiful, ocean-inspired CSS design system with a refreshing blue color palette. From deep ocean blues to light coastal hues, this theme brings a sense of trust, professionalism, and clarity to your web projects.

## 🌊 Quick Start

### CDN Usage

Add this line to your HTML `<head>`:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/math-u-t/material-design@main/style/blue-sea.css">
```

Or use GitHub's raw content:

```html
<link rel="stylesheet" href="https://raw.githubusercontent.com/math-u-t/material-design/main/style/blue-sea.css">
```

## 📦 Basic Usage

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Blue Sea Theme Example</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/math-u-t/material-design@main/style/blue-sea.css">
</head>
<body>
  <div class="container">
    <h1>Welcome to Blue Sea Theme</h1>
    <p>A beautiful, professional design system.</p>
    <button class="btn btn-primary">Get Started</button>
  </div>
</body>
</html>
```

## 🎨 Component Examples

### Buttons

```html
<!-- Primary Button -->
<button class="btn btn-primary">Primary Button</button>

<!-- Secondary Button -->
<button class="btn btn-secondary">Secondary Button</button>

<!-- Outline Button -->
<button class="btn btn-outline">Outline Button</button>

<!-- Ghost Button -->
<button class="btn btn-ghost">Ghost Button</button>

<!-- Button Sizes -->
<button class="btn btn-primary btn-sm">Small</button>
<button class="btn btn-primary">Default</button>
<button class="btn btn-primary btn-lg">Large</button>

<!-- Icon Button -->
<button class="btn btn-icon btn-primary">🔍</button>

<!-- Disabled Button -->
<button class="btn btn-primary" disabled>Disabled</button>
```

### Forms

```html
<form>
  <label for="email">Email Address</label>
  <input type="email" id="email" placeholder="Enter your email">

  <label for="password">Password</label>
  <input type="password" id="password" placeholder="Enter password">

  <label for="message">Message</label>
  <textarea id="message" placeholder="Your message"></textarea>

  <label>
    <input type="checkbox">
    I agree to the terms and conditions
  </label>

  <button type="submit" class="btn btn-primary">Submit</button>
</form>
```

### Validation States

```html
<input type="text" class="is-valid" placeholder="Valid input">
<span class="form-success">Looks good!</span>

<input type="text" class="is-invalid" placeholder="Invalid input">
<span class="form-error">Please provide a valid value.</span>
```

### Cards

```html
<div class="card">
  <div class="card-header">
    <h3 class="card-title">Card Title</h3>
  </div>
  <div class="card-body">
    <p>Card content goes here. This is a flexible container for various content types.</p>
  </div>
  <div class="card-footer">
    <button class="btn btn-primary">Action</button>
  </div>
</div>
```

### Alerts

```html
<div class="alert alert-info">
  This is an informational message.
</div>

<div class="alert alert-success">
  Success! Your operation completed successfully.
</div>

<div class="alert alert-warning">
  Warning: Please review this information.
</div>

<div class="alert alert-error">
  Error: Something went wrong.
</div>
```

### Badges

```html
<span class="badge badge-primary">Primary</span>
<span class="badge badge-success">Success</span>
<span class="badge badge-warning">Warning</span>
<span class="badge badge-error">Error</span>
<span class="badge badge-neutral">Neutral</span>
```

### Navigation

```html
<nav class="navbar sticky">
  <div class="navbar-container">
    <a href="#" class="navbar-brand">Brand</a>
    <ul class="navbar-nav">
      <li><a href="#" class="active">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Services</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </div>
</nav>
```

### Breadcrumb

```html
<ul class="breadcrumb">
  <li><a href="#">Home</a></li>
  <li><a href="#">Products</a></li>
  <li>Current Page</li>
</ul>
```

### Tabs

```html
<ul class="tabs">
  <li class="active"><a href="#tab1">Tab 1</a></li>
  <li><a href="#tab2">Tab 2</a></li>
  <li><a href="#tab3">Tab 3</a></li>
</ul>
```

### Pagination

```html
<ul class="pagination">
  <li><a href="#">Previous</a></li>
  <li><a href="#">1</a></li>
  <li class="active"><a href="#">2</a></li>
  <li><a href="#">3</a></li>
  <li><a href="#">Next</a></li>
</ul>
```

### Grid System

```html
<div class="container">
  <div class="row">
    <div class="col-12 col-md-6 col-lg-4">Column 1</div>
    <div class="col-12 col-md-6 col-lg-4">Column 2</div>
    <div class="col-12 col-md-12 col-lg-4">Column 3</div>
  </div>
</div>
```

### Tables

```html
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Email</th>
      <th>Role</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>John Doe</td>
      <td>john@example.com</td>
      <td>Admin</td>
    </tr>
    <tr>
      <td>Jane Smith</td>
      <td>jane@example.com</td>
      <td>User</td>
    </tr>
  </tbody>
</table>
```

### Progress Bar

```html
<div class="progress">
  <div class="progress-bar" style="width: 70%;"></div>
</div>

<div class="progress">
  <div class="progress-bar success" style="width: 100%;"></div>
</div>
```

### Spinner

```html
<div class="spinner"></div>
<div class="spinner spinner-sm"></div>
<div class="spinner spinner-lg"></div>
```

### Modal

```html
<div class="modal-backdrop show"></div>
<div class="modal show">
  <div class="modal-header">
    <h3 class="modal-title">Modal Title</h3>
  </div>
  <div class="modal-body">
    <p>Modal content goes here.</p>
  </div>
  <div class="modal-footer">
    <button class="btn btn-ghost">Cancel</button>
    <button class="btn btn-primary">Confirm</button>
  </div>
</div>
```

## 🎯 Utility Classes

### Display

```html
<div class="d-flex">Flex container</div>
<div class="d-block">Block element</div>
<div class="d-none">Hidden element</div>
```

### Flexbox

```html
<div class="d-flex justify-center align-center gap-md">
  <div>Item 1</div>
  <div>Item 2</div>
</div>
```

### Spacing

```html
<!-- Margin -->
<div class="m-md">Margin all sides</div>
<div class="mt-lg">Margin top large</div>
<div class="mb-xl">Margin bottom extra large</div>

<!-- Padding -->
<div class="p-md">Padding all sides</div>
<div class="pt-lg">Padding top large</div>
```

### Text

```html
<p class="text-center">Centered text</p>
<p class="text-primary">Primary color</p>
<p class="text-lg font-bold">Large bold text</p>
```

## 🎨 Color Variables

Access theme colors via CSS variables:

```css
:root {
  --color-primary: #0077BE;
  --color-primary-light: #00A8E8;
  --color-primary-dark: #003D5B;

  --color-secondary: #4FC3F7;
  --color-accent: #00BCD4;

  --color-success: #4CAF50;
  --color-warning: #FF9800;
  --color-error: #F44336;
  --color-info: #2196F3;
}
```

## 🔧 Customization

### Override Variables

You can customize the theme by overriding CSS variables:

```html
<style>
  :root {
    --color-primary: #1E88E5;
    --font-primary: 'Your Custom Font', sans-serif;
    --radius-md: 1rem;
  }
</style>
```

### Add Custom Styles

```html
<style>
  .my-custom-component {
    background-color: var(--color-primary);
    padding: var(--spacing-lg);
    border-radius: var(--radius-md);
  }
</style>
```

## 📱 Responsive Design

The theme is mobile-first with these breakpoints:

- **Mobile**: < 640px
- **Tablet**: 640px - 768px
- **Desktop**: 768px - 1024px
- **Large Desktop**: > 1024px

## ♿ Accessibility

The Blue Sea theme follows WCAG 2.1 AA standards:

- Proper color contrast ratios
- Focus visible states for keyboard navigation
- Semantic HTML structure
- Screen reader support with `.sr-only` class

## 📄 License

MIT License - Feel free to use in personal and commercial projects.

## 🔗 Resources

- [GitHub Repository](https://github.com/math-u-t/material-design)
- [Design Documentation](./blue-sea-DESIGN.md)
- [Report Issues](https://github.com/math-u-t/material-design/issues)
