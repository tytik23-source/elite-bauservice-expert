# Elite Bauservice Expert

Сайт кровельной фирмы Elite Bauservice Expert (Dachdecker-Meisterbetrieb, на немецком). Одна статическая страница, без сборки.

- `index.html` — сайт.
- `preview.html` — тот же контент в формате предпросмотра Claude (артефакт).
- `img/` — сюда класть настоящие фотографии.
- `netlify.toml` — готово для деплоя на Netlify (publish = корень).

## Что заменить перед запуском
- Телефон, e-mail, адрес, город и районы в блоке «Einsatzgebiet».
- Цифры в «Über uns» (15+ Jahre, 600+ Projekte) — сейчас примерные.
- Рамки «Foto: …»: внутрь `<div class="ph">` вставить `<img src="img/имя.jpg" alt="описание">`.
- Страницы Impressum и Datenschutz (обязательны в Германии).
- Отправку формы заявки (Netlify Forms, e-mail или CRM).
