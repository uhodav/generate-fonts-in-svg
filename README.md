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

<dl>
    <dt>`dist`</dt>
    <dd>`fonts`</dd> готовые шрифты
    <dd>`styles`</dd>готовые классы иконок
    <dt>`icons`Папка с файлами svg для создания шрифта</dt>
    <dt>`template`/dt>шаблоны для формирования
    <dt>`.fantasticonrc.js`/dt> файл с настрйоками
</dl>


Используется https://github.com/tancredi/fantasticon/
