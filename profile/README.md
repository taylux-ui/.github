# Taylux Component Library

![Taylux Design System](https://via.placeholder.com/800x200?text=Taylux+Design+System)

Taylux is a modern, lightweight component library available for both Vue.js and React. Built with flexibility and developer experience in mind, Taylux provides a comprehensive set of UI components that are easy to customize and implement.

[![npm version](https://img.shields.io/npm/v/taylux.svg?style=flat)](https://www.npmjs.com/package/taylux)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🚀 Features

- 📦 Rich set of UI components
- 🎨 Highly customizable with CSS variables
- 🌓 Dark mode support
- ♿ Accessibility first
- 📱 Responsive design
- 🔧 Easy to integrate
- ⚡ Lightweight and performant
- 🎯 TypeScript support
- 💪 Framework agnostic CSS utilities

## 📦 Installation

### Vue.js

```bash
# npm
npm install @taylux/vue

# yarn
yarn add @taylux/vue

# pnpm
pnpm add @taylux/vue
```

### React

```bash
# npm
npm install @taylux/react

# yarn
yarn add @taylux/react

# pnpm
pnpm add @taylux/react
```

## 🔧 Usage

### Vue.js

```vue
import { createApp } from 'vue';
import App from './App.vue';
import Taylux from "@taylux/vue";

const app = createApp(App);

app.use(Taylux);
app.mount('#app');
```

```vue
<template>
  <div>
    <TayluxButton variant="primary" size="md">
      Click me!
    </TayluxButton>
  </div>
</template>
```

### React

```jsx
import { Button } from '@taylux/react'

function App() {
  return (
    <Button variant="primary" size="md">
      Click me!
    </Button>
  )
}
```

## 🎨 Customization

Taylux uses CSS variables for easy theming. You can override these variables in your CSS:

```css
:root {
  --taylux-primary: #2563eb;
  --taylux-primary-hover: #1d4ed8;
  --taylux-secondary: #f3f4f6;
  --taylux-secondary-hover: #e5e7eb;
  --taylux-radius: 4px;
}
```

## 📚 Components

- Buttons
  - Primary
  - Secondary
  - Tertiary
  - Danger
  - Outline
  - Ghost


## 📖 Documentation

For detailed documentation and examples, visit our documentation site:
[https://docs.taylux.dev](https://docs.taylux.dev)

## 🤝 Contributing

We love your input! We want to make contributing to Taylux as easy and transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

### Development

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

Taylux is [MIT licensed](./LICENSE.md).

## 🔗 Links

- [Documentation](https://docs.taylux.dev)
- [GitHub](https://github.com/taylux/taylux)
- [npm Package](https://www.npmjs.com/package/taylux)
- [Contributing Guidelines](./CONTRIBUTING.md)
- [Code of Conduct](./CODE_OF_CONDUCT.md)

## 💖 Sponsors

Become a sponsor and get your logo on our README on GitHub with a link to your site.

## 🙏 Thanks

Thanks to all contributors who have helped make Taylux better!
