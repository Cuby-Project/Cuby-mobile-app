# React + TypeScript + Vite

# Cuby mobile app
---
-<a href="https://github.com/Cuby-Project/Cuby-mobile-app/issues/new/choose">Report a bug</a>--<a href="https://github.com/Cuby-Project/Cuby-mobile-app/issues/new/choose">Request a feature</a>-
</div>

- Configure the top-level `parserOptions` property like this:

You are looking a the mobile part of Cuby, this only the solving capture tool for the app, and in the future a fully fonctionnal mobile version of **Cuby**, you can find the main app at : ![Cuby repo](https://github.com/Cuby-project)


```js
// eslint.config.js
import react from 'eslint-plugin-react'

export default tseslint.config({
  // Set the react version
  settings: { react: { version: '18.3' } },
  plugins: {
    // Add the react plugin
    react,
  },
  rules: {
    // other rules...
    // Enable its recommended rules
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
})
```
