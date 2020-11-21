# SmarttenderFont

> Генерация шрифта иконок [Smarttender](https://smarttender.biz/)

**<a href="https://htmlpreview.github.io/?https://github.com/uhodav/smarttender-fonts/blob/main/dist/icon.html#/bored" target="_blank">Результат</a>**

```bash
# Устанавливаем зависимости
$ npm install

# Добавляем новые иконки в формате svg в папку icons. Имя будет использовано для созданного класса

# Запускаем сборку шрифта
$ npm run generate
```

Результат работы в папке `dist`
`fonts` можно забирать целиком.
Стили из папки `styles` по необходимости

>`dist`\
>> `fonts`        готовые шрифты\
>> `styles`       классы иконок\
> `icons`             файлы svg для создания шрифта\
> `template`          шаблоны для формирования\
> `.fantasticonrc.js` настройки


Используется https://github.com/tancredi/fantasticon/
