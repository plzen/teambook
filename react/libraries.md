# Используемые библиотеки для React Native

Перед добавлением новой бибилиотеки желательно убедиться, что:
- достаточно ли существенна задача, чтобы внедрять новое решение или задачу можно решить более простым способом без добавления новой зависимости;
- новая библиотека решает задачу, которую не решает данный список библиотек;
- она качественно написана.

## Isomorphic
- Static and server‑rendered applications - [next.js](https://github.com/zeit/next.js)
- Custom routing - [next-routes](https://github.com/fridays/next-routes)
- Side Effects - [next-redux-saga](https://github.com/bmealhouse/next-redux-saga)
- Redux Wrapper - [next-redux-wrapper](https://github.com/kirill-konshin/next-redux-wrapper)

## React
- React - [React](https://reactjs.org)
- React Native [React Native](https://facebook.github.io/react-native/)
- Валидация props и state - [PropTypes](https://reactjs.org/docs/typechecking-with-proptypes.html)
- Стилизация компонентов - [styled-components](https://github.com/styled-components/styled-components)
- Работа с className - [classnames](https://github.com/JedWatson/classnames)
- Кастомные иконки - [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)
- Навигация - [React Navigation](https://reactnavigation.org)
- Локализация - [react-native-i18n](https://github.com/AlexanderZaytsev/react-native-i18n)

## Redux
- Хранение стейта - [redux](https://redux.js.org), [redux-persist](https://github.com/rt2zz/redux-persist)
- Связка React и Redux - [react-redux](https://redux.js.org/basics/usage-with-react)
- Работа с формами - [redux-form](https://redux-form.com)
- Side Effects - [redux-saga](https://redux-saga.js.org), [redux-thunk](https://github.com/reduxjs/redux-thunk), [redux-observable](https://redux-observable.js.org)
- Логирование стейта - [redux-logger](https://github.com/evgenyrodionov/redux-logger)

## Работа с сетью/API
- HTTP клиенты - [axios](https://github.com/axios/axios)
- Graph QL - [apollo](https://www.apollographql.com)
- JSON API Normalizer - [json-api-normalizer](https://github.com/yury-dymov/json-api-normalizer)

## Утилиты
- Работа с датой/временем - [momentjs](https://momentjs.com)
- Функциональное программирование - [ramda](https://ramdajs.com)
- Работа с массивами, числами, объектами, строками - [lodash](https://lodash.com). Также можно устанавливать только конкретный пакет, чтобы не тянуть всю библиотеку, типа _lodash.camelcase_
- Работа с селекторами - [reselect](https://github.com/reduxjs/reselect)
- Валидация объектов - [validate.js](https://validatejs.org)

## Анализаторы кода
- Линтер - [ESLint](https://eslint.org)
- Статический анализатор - [Flow](https://flow.org)

## Тестирование
- Snapshot Testing - [jest](https://facebook.github.io/jest/)
- Testing React components - [enzyme](https://github.com/airbnb/enzyme)
- BDD/TDD - [mocha](https://mochajs.org/), [chai](http://www.chaijs.com)