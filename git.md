# Правила работы с git

## Правила работы с Git

Для работы с git используется подход [gitflow](https://nvie.com/posts/a-successful-git-branching-model/).

![Git Flow](resources/git-flow.png)

1. Коммиты должны быть атомарными. Комментарий должен начинаться с глагола в настоящем времени и должен объяснять суть изменений. Например, _Fix app crash when login pressed_
2. В случае, если коммит связан с задачей в Jira, необходимо добавить в начале или в конце код задачи. Например, _[JIRA-123] Fix app crash when login pressed_
3. Перед тем, как сделать коммит, пройдитесь по каждому изменению и убедитесь что отсутствуют: закомментированный код, лишнее логирование, функционал, относящийся к другой задаче.

## Конфигурация Git

В качестве системы контроля версий/репозитория исходного кода используется Git. Хранение исходных кодов в репозитории является обязательным.

У каждого разработчика должно быть корректно настроено имя и рабочий email пользователя в настройках git.
Например, в консоли это можно сделать так:

```
git config --global user.name "Ivan Ivanov"
git config --global user.email "ivanov@pentagon.gov.us"
```

Проверить или изменить конфиг: 
 
```
git config --global --edit
```

Cекция пользователя в нем:

```
[user]
    name = Ivan Ivanov
    email = ivanov@pentagon.gov.us
```
## .gitignore

Используется [стандартный *.gitignore*](https://www.gitignore.io/api/reactnative%2Cvisualstudiocode).
