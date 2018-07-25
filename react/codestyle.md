# Code Style

В качестве основного инструмента для проверки стилей мы используем [ESLint](https://eslint.org).

Правила базируются на следующих наборах правил:
- eslint:recommended
- airbnb
- plugin:react/recommended

Также добавляем свои правила:
```
"rules": {
    "class-methods-use-this": 0,
    "global-require": 0,
    "import/first": 0,
    "import/prefer-default-export": 0,
    "jsx-a11y/anchor-is-valid": 0,
    "no-underscore-dangle": 0,
    "no-use-before-define": 0,
    "quotes": ["error", "double"],
    "react/forbid-prop-types": 0,
    "react/jsx-filename-extension": 0,
    "react/require-default-props": 0
  }
```
