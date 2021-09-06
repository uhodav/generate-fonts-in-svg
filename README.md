# SvgFont

> Генерация шрифта иконок

**<a href="https://htmlpreview.github.io/?https://github.com/uhodav/smarttender-fonts/blob/main/dist/demo.html#/bored" target="_blank">Результат</a>**

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

+ **`dist`** содержит готовые шрифты и стили
    - **`fonts`** готовые шрифты
        - `SvgFont.eot`
        - `SvgFont.svg`
        - `SvgFont.ttf`
        - `SvgFont.woff`
        - `SvgFont.woff2`
    - `styles`стили иконок
        - `icons.css`
        - `icons.json` используется в storybook
        - `icons.less` используется в компоненте иконок
    - demo.html файл демонстрации
+ **`icons`**             файлы svg для создания шрифта
+ **`template`**          шаблоны для формирования
    - 'css.hbs' шаблон генерации 'icons.css' 
    - 'html.hbs' шаблон генерации 'demo.html'
    - 'less.hbs' шаблон генерации 'icons.less' 
+ `.fantasticonrc.js` настройки


Используется https://github.com/tancredi/fantasticon/
