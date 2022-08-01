Прочитать на других языках: [English](CONTRIBUTING.md)

# Добро пожаловать в руководство по внесению вклада Return YouTube Dislikes

Благодарим вас за то, что вы потратили своё время на участие в нашем проекте! Все ваши изменения будут отражены в следующей версии расширения (или на [сайте](https://www.returnyoutubedislike.com/)).

## Приступая к работе

Пожалуйста, используйте Prettier с настройками по умолчанию для форматирования кода.

#### Необходимое

Вам необходимо иметь установленные node и npm, чтобы создать bundled-версию источника.

Версии, используемые при настройке:

- node: 12.18.4
- npm: 6.14.6

Для создания `bundled-content-script.js` который содержит большую часть бизнес-логики этого расширения, вы должны сначала установить все зависимости.

1. Перейдите в корень репозитория и выполните следующее:

```
npm install
```

2. Выполните следующую команду, чтобы создать `bundled-content-script.js`, который используется в `manifest.json`

```
npm start // для создания файла(ов) сборки и запуска наблюдателя за файлами, который выполняет hot-reload при сохранении

// или

npm run build // для создания файла(ов) сборки один раз
```

Поздравляем, теперь вы готовы к разработке!

Если вы новичок в разработке расширений Chrome или вам нужна дополнительная помощь, посмотрите [это руководство на YouTube (англ.)](https://www.youtube.com/watch?v=mdOj6HYE3_0)

### Вопросы

#### Открытие нового вопроса/проблемы

Если у вас возникли проблемы с расширением, пожалуйста, поищите, чтобы убедиться, что о проблеме ещё не сообщалось. Если это не так, откройте вопрос(issue), использование формы проблемы настоятельно рекомендуется, но не является обязательным.

#### Решение вопроса

Если вы нашли проблему, которую, как вам кажется, вы можете решить, не стесняйтесь. Откройте запрос на извлечение(pull request) с исправлением и обязательно укажите вопрос, который вы устраняете.

### Запрос функции

#### Открытие запроса на новую функцию

Если у вас есть идея для расширения, не стесняйтесь открыть запрос на функцию, но, пожалуйста, прежде поищите другие запросы, чтобы убедиться, что функция уже не предложена. Использование формы запроса функции настоятельно рекомендуется, но не является обязательным

#### Внедрение запроса на функцию

Если вы нашли функцию, которую, как вам кажется, вы могли бы реализовать, не стесняйтесь. Откройте запрос на извлечение(pull request) с исправлением и обязательно укажите функцию, которую вы реализуете.

### Какие запросы на извлечение(pull request) мы принимаем?

- Исправления проблем.
- Внедрения новых функций.
- Исправления опечаток и упрощение текста.
- Улучшения сайта.