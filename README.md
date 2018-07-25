# 📑 Инструмент для понимания порядка картинок в html-формате Google Docs

## Что происходит?

## Как использовать?

1. Сохранить документ через меню «Файл» → «Скачать как» → «Веб-страница (HTML, ZIP-архив)»;
1. В теле документа перед тегом `</body>` подключить два скрипта:

   ```html
   <script src="https://code.jquery.com/jquery-3.3.1.min.js" integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8=" crossorigin="anonymous"></script>
   <script src="https://4enki.github.io/google-docs-images/dist/google-docs-images.min.js"></script>
   ```

   jQuery последней версии подключается из [jQuery CDN](https://code.jquery.com/).
1. Обновить страницу.

В консоле браузера дублируется информация по каждой картинке;

## Ещё на эту тему 🔥 🔥 🔥 🔥 🔥

## Что дальше-то?

- [x] [Гист-файл](https://gist.github.com/4enki/441700b964e85bbca1c3d50f53887b79) превратить в полноценный репо. Создать один js-файл, который сможет всё;
- [ ] Переписать без jQuery, ванильненько;
- [ ] Отдавать минифицированную версию JS;
- [ ] Вытащить параметр нового имени картинки в отдельный тег при подюкючении;
- [ ] Скриптом сохранять картинки с правильным порядковым номером в суффиксе и именем из перменной;
