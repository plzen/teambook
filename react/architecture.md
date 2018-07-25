# Архитектурные подходы

В качестве основной архитектуры мы используем Flux и конкретно ее реализацию [Redux](https://redux.js.org).

Для обработки side effects используем одну из библиотек из [списка](libraries.md).

Хранение данных в стейте должно быть организовано в [нормализованной форме](https://redux.js.org/recipes/structuring-reducers/normalizing-state-shape). Больше информации по структуре reducers [тут](https://redux.js.org/recipes/structuring-reducers).

Принципы, применяемые при разработке: [SOLID](https://en.wikipedia.org/wiki/SOLID_(object-oriented_design)), [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself), [KISS](https://en.wikipedia.org/wiki/KISS_principle), [YAGNI](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it), [TDD](https://en.wikipedia.org/wiki/Test-driven_development).
