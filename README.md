# Vinícios Barbosa ESLint Configuration
ESLint configuration used by Vinícios Barbosa

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;
- Import Helpers;

## Setup

1. Install the dependencies
```
npm i -D eslint @vinebarbosa/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "@vinebarbosa/eslint-config/react"
  // "extends": "@vinebarbosa/eslint-config/node"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.