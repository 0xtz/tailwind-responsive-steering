# Tailwind Responsive Steering

A Tailwind CSS plugin for simplified responsive design, allowing multiple classes to be applied at specific breakpoints using a concise syntax like md-[text-lg flex].

## WARNING

This plugin is a work in progress and is not yet ready for production. We would like to have a more robust solution for this, but for now this is a good enough solution.

## Installation

```bash
npm install tailwind-responsive-steering
```

## Usage

Add the plugin to your tailwind.config.js:

```js
module.exports = {
  plugins: [require("tailwind-responsive-steering")],
};
```

Use in your HTML or JSX:

```html
<div class="md-[text-lg flex items-center] lg-[p-4 m-2]">Content</div>
```

This applies `text-lg`, `flex`, and `items-center` at the `md` breakpoint and `p-4`, `m-2` at the `lg` breakpoint.

## Compatibility

- Tailwind CSS v3 and v4
- Supports all configured breakpoints

## License

MIT
