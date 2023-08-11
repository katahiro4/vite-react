# React + TypeScript + Vite + EsLint + Prettier

├── @types/react-dom@18.2.7
├── @types/react@18.2.20
├── @typescript-eslint/eslint-plugin@5.62.0
├── @typescript-eslint/parser@5.62.0
├── @vitejs/plugin-react-swc@3.3.2
├── eslint-config-prettier@9.0.0
├── eslint-config-standard-with-typescript@37.0.0
├── eslint-plugin-import@2.28.0
├── eslint-plugin-n@16.0.1
├── eslint-plugin-prettier@5.0.0
├── eslint-plugin-promise@6.1.1
├── eslint-plugin-react-hooks@4.6.0
├── eslint-plugin-react-refresh@0.4.3
├── eslint-plugin-react@7.33.1
├── eslint@8.47.0
├── prettier@3.0.1
├── react-dom@18.2.0
├── react@18.2.0
├── typescript@5.1.6
└── vite@4.4.9

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
