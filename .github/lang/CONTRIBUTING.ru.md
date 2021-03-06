# Содействие

Если вы заинтересованны в предоставлении помощи проекту, пожалуйста, сперва изучите [Свод Правил](./CODE_OF_CONDUCT.md).

## Перевод

Перевод состоит из **3** частей, которые вы можете отправить через один запрос (по вашему усмотрению).

### Документация Сайта

Документация сайта содержится в `./github/lang` директории. Если вы желаете отправить перевод, предоставьте последующие файлы с правильным регистром [двубуквенный iso-code для вашего языка](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes).

в к. п. Китайский

- `.github/lang/README.zh.md`
- `.github/lang/CONTRIBUTING.zh.md`

Обновляйте гиперссылки между вашими новыми `README.zh.md` и `CONTRIBUTING.zh.md` файлами, для того чтобы кликая на ***Содействие*** гиперссылка внутри файла `README.zh.md` сразу направляла в `CONTRIBUTING.zh.md` файл.

### i18n

Файлы языка находящиеся в `lang/` и существующие как JavaScript файл именуются как [двубуквенный iso-code системы для вашего языка](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes).

в к. п. Хинди

- `lang/hi.js`

Вы должны скопировать `lang/en.js` и переименовать его в ваш переводимый язык, затем последовательно перевести каждую строку. Будьте аккуратны со строчками где есть индикация кода, чтобы не сломать его.

### Контент сайта

Содержимое сайта находиться в `content/` каталоге под директорией названной в [двубуквенной iso-code системе для вашего языка](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes). 

в к. п. Испанский (континентальный)

- `content/es/`

Вы должны скопировать `content/en/` каталог в вашу новую директорию переводимого языка. Затем выполнить перевод всего содержимого. Будьте аккуратны не повредить HTML код который содержится в файлах. Хоть и заголовок сверху на данный момент не используется, пожалуйста, переведите и его.

На данный момент необходимые файлы для перевода:

- `details.md`
- `index.md`

## Запросы

Пожалуйста найдите необходимый запрос, напишите за дополнительной информацией тем самым подтвердив своё авторство. После этого можете начать работать. О завершении сообщите через pull request.

Чтобы создать pull-request, убедитесь в том, что вы forkнули репозиторий перед созданием новой ветки. ПОЖАЛУЙСТА, НЕ РЕДАКТИРУЙТЕ свою собственную `main` ветку до того как создадите pull-request на эту `main` ветку. Если есть какие либо сомнения, не стесняйтесь и спрашивайте.

## Прочие улучшения

Большая просьба - не создавайте pull-requests ни с того ни с сего. Будьте добры сперва уведомить в "запросах" прежде чем будите над чем-то рабоать.