# Автосервис «888» — демо

Один `index.html`: HTML, CSS, JavaScript и SVG встроены в файл. Без фреймворков, сборки, внешних шрифтов и библиотек. Открывается локально или на GitHub Pages.

## Настройки

В конце `index.html` найдите `const CONFIG`. В одном месте меняются цены и названия услуг, номер телефона, график работы, выходные, слоты, часовой пояс и ссылки на карту. Цены и свободные слоты вымышленные.

Телефон и адрес взяты из предоставленного скриншота карточки [2ГИС](https://2gis.ru/ufa/firm/70000001031110807). График Пн–Сб, 09:30–20:00 взят как справочный из [Spravka.City](https://ufa.spravka.city/company/888-96); в скриншоте виден только час открытия. Выходной в воскресенье — предположение для демо. Перед рабочим запуском подтвердите полный график и тексты преимуществ с владельцем.

## Изображение

Иллюстративное изображение автомобиля создано встроенным ImageGen; это не фотография реального сервиса. WebP встроен в `index.html` как data URL, поэтому лендинг остаётся одним автономным файлом. Размер HTML около 214 КБ.

Промпт генерации: «Editorial automotive photograph for a dark, strict, orange-accented landing page. Graphite-gray unbranded modern sedan, front three-quarter view facing left, on a concrete floor inside a dark clean independent repair workshop. No people, logos, lettering or watermark. Wide 3:2 composition, all wheels visible. Dark edges near #111210, subtle warm orange lighting, sharp car detail. Illustrative demo artwork, not the real premises».

## Демо-запись

Услуга → дата → время → имя и телефон → экран результата. Учитываются время Уфы, прошедшее время и выходные. Никаких отправок, аналитики, cookies или сохранения в браузере. Контакты показываются только на странице результата и очищаются при повторной записи или перезагрузке. Для подключения Telegram нужен отдельный сервер: токен бота нельзя размещать в публичном HTML.

## GitHub Pages

Публикация из ветки `main`, каталог `/` (корень). Адрес: https://haevlob.github.io/demo-888/.

Разработка: Дмитрий.
