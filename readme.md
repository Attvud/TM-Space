# TM Space :ok_hand: Sitis Design system ~ v.2.1.0

Этот репозиторий создан, чтобы упростить жизнь всем, кто будет в дальнейшем работать над этим проектом. 

**Быстрые ссылки**
- [Video for developers 1](https://youtu.be/5WmXNMbPCjc) || [Video for developers 2](https://youtu.be/I9QZN2ghsqU)
- [Video ~ desktop](https://vk.com/video554674725_456239018) || [Video ~ mobile](https://vk.com/video554674725_456239017)
- [InVision ~ desktop](https://invis.io/YZTGIYLBTGP#/379022878_UX-_UI_-_Desktop_-_-_Home) || [InVision ~ mobile](https://projects.invisionapp.com/share/54T6IEY7KVF#/screens/376018575)
- [Скачать исходник](/1%20Sources)
- Скачать логотип - [без текста](/2%20Export/branding/1%20Project%20Logo.svg), [с текстом](/2%20Export/branding/1%20Project%20Logo%20With%20Text.svg)
- [Скачать иконки](#icons)
- [Написать дизайнеру](mailto:w@res.pm)
- [Правки 1](https://youtu.be/5FkpfrZyQvg)

**Коротко о главном**

* отслеживайте изменения в UX/UI 24/7, получая обновления по почте. Долой бесконечные поиски нужных файлов и сообщений в месседжерах! Теперь все в одном месте.
* [история версий](/1%20Sources) UX/UI.
* я могу оптимизировать все SVG иконки через API **SVGO**, все PNG изображения через API **Tiny PNG** и все Jpeg изображения через API **JPEGmini**. Нужно - [дайте знать](mailto:w@res.pm).

## Color scheme

![Color scheme](/2%20Export/~%20guidelines/RU/github/color%20scheme.jpg)

На изображении выше показаны цвета, которые были использованы в дизайне. Использовать другие оттенки нельзя. В [исходнике](/1%20Sources) на странице **"~ settings & branding > Color settings"** вы сможете найти все палитры, в том числе и с оттенками серого.

Вот [SCSS код](/3%20Docs/system/color%20system.scss), который автоматически сгенерирует переменные для основного и второстепенного цвета, а также для их оттенков + добавит палитру для оттенков серого. Важно использовать указанные оттенки серого. Если я буду проверять качество **Front end** по этому проекту - это будет обязательным требованием.

Воспользовавшись этим решением вы легко сможете создавать поведение для элементов (hover, focus и т.д.) и обращаться к каждому цвету и его оттенку по имени переменной.

P.S.: Если цвета в "Primary palette" и "Secondary palette" не отличаются – значит в проекте использовался только один цвет в качестве основного.

## Typography

- **Arial** – десктоп
- **Roboto** – для устройств под управлением Android
- **SF Pro** – для устройств под управлением iOS и macOS

**Обязательно нужно использовать этот код в десктопном Front end**

```
body {
    font-family: "-apple-system",BlinkMacSystemFont,Arial,sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
```

## Icons

![Icons](/2%20Export/~%20guidelines/RU/github/icons.jpg)

В этом проекте используются [Rounded](/2%20Export/icons/rounded) иконки + иконки брендов. Система дизайна экспортирует все доступные ей иконки. Вам нужны только те, которые используются в UX/UI.

![Footer](/2%20Export/~%20guidelines/RU/github/footer.png)