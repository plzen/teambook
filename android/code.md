# Организация кода

Используя подход "Clean Architecture", необходимо использовать многомодульную структуру приложения (presentation, domain, data).

**Domain** - в этом модуле должны находится модели данных, абстрактные репозитории (интерфейсы), интеракторы (UseCases), а также общие для всех модулей константы и расширения. Пример:
```
entity
    Feed
    ...
interactor
    GetFeedListUseCase
    GetFeedUseCase
    ...
repository
    AuthRepository
    FeedRepository
    ...
```

**Data** - модуль в котором находятся имплементации репозиториев и реализации сетевого клиента и DAO. Пример:
```
database
network
repository
    AuthRepositoryImpl
    FeedRepositoryImpl
    ...
```

**Presentation** - модуль с пользовательским интерфейсом, который через промежуточный слой (ViewModel) взаимодействует с данными. Пример структуры Presentation модуля:
```
di
    component
        ApplicationComponent
    module
        ActivityModule
        FragmentModule
        RepositoryModule
    scope
        ActivityScope
        FragmentScope
ui
    feed
        adapter
            FeedAdapter
        item
            FeedItem
        viewmodel
            FeedViewModel
            FeedViewModelFactory
        FeedActivity
        FeedFragment
    ...
MainApplication.kt
```