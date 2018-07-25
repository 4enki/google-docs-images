# 📑 Инструмент для понимания порядка картинок в html-формате Google Docs

## Что происходит?

## Как использовать?

1. Сохранить документ через меню «Файл» → «Скачать как» → «Веб-страница (HTML, ZIP-архив)»;
1. В теле документа перед тегом `</body>` подключить два скрипта и определить корректное название картинок:

   ```html
   <script>
     var imgName = 'new_image_item';
   </script>
   <script src="https://4enki.github.io/google-docs-images/dist/google-docs-images.min.js"></script>
   ```

   jQuery последней версии подключается из [jQuery CDN](https://code.jquery.com/).
1. Обновить страницу.
1. Переименовывать картинки в папке `/images`.

В консоле браузера дублируется информация по каждой картинке;

## Ещё на эту тему 🔥 🔥 🔥 🔥 🔥

## Что дальше-то?

- [x] [Гист-файл](https://gist.github.com/4enki/441700b964e85bbca1c3d50f53887b79) превратить в полноценный репо. Создать один js-файл, который сможет всё;
- [x] Переписать без jQuery, ванильненько;
- [x] Отдавать минифицированную версию JS;
- [x] Вытащить параметр нового имени картинки в отдельный тег при подюкючении;
- [ ] Унифицировать классы и имена переменных, чтобы не пересекаться ни с чем;
- [ ] Рассказать в README историю полную боли;
- [ ] Скриптом сохранять картинки с правильным порядковым номером в суффиксе и именем из перменной;
