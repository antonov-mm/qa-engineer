
# Первый автотест написанный на Java + junit + selenium

## Описание
Мой первый автотест написанный на Java + junit + selenium.
Адрес тренажёра, где происходит выполнение автотеста -
http://users.bugred.ru

## Шаги выполнения
- Посещение веб страницы `http://users.bugred.ru/user/login/index.html`
- Заполнение полей с авторизацией и нажатие кнопки авторизации в профиль пользователя
- Выход из профиля пользователя
## Настройки

Настройки с драйвером, страницами и некоторыми переменными находятся в файле `/target/test-classes/conf.properties`

## Запуск теста

В терминале ввести команду 
```bash
mvn clean test
```

