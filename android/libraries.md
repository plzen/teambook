# Используемые библиотеки для React Native

Перед добавлением новой бибилиотеки желательно убедиться, что:
- сторонняя библиотека не дублирует функционал официальной;
- достаточно ли существенна задача, чтобы внедрять новое решение или задачу можно решить более простым способом без добавления новой зависимости;
- новая библиотека решает задачу, которую не решает данный список библиотек;
- она качественно написана и поддерживается.

## UI
- Image loading/caching - [Picasso](https://github.com/square/picasso)
                          [Glide](https://github.com/bumptech/glide)
- Layout - [ConstraintLayout](https://developer.android.com/reference/android/support/constraint/ConstraintLayout)
- Sticky header - [Header-decor](https://github.com/edubarr/header-decor)
- RecyclerView snapping - [RecyclerViewSnap](https://github.com/rubensousa/RecyclerViewSnap)
- A lightweight viewpager indicator - [CircleIndicator](https://github.com/ongakuer/CircleIndicator)

## WebView
- Browser - [Chrome Custom Tabs](https://developer.chrome.com/multidevice/android/customtabs)

## DB
- Abstraction layer over SQLite - [Room](https://developer.android.com/topic/libraries/architecture/room)

## DI
- Dependency injection - [Dagger 2 (with Android support)](https://github.com/google/dagger)
- Dependency injection annotation - [javax-inject](https://github.com/javax-inject/javax-inject)

## Network
- HTTP client - [Retrofit 2](https://github.com/square/retrofit)

## Test
- Android Unit Testing Framework - [Robolectric](https://github.com/robolectric/robolectric)
- Framework for unit tests - [Mockito](https://github.com/mockito/mockito)
