# Примеры

В этой папке лежат готовые overlay-файлы для отдельных проектов ROMAN ILYIN.

Каждый overlay использует такую схему имён:

```text
LICENSE.md                      # английский справочный текст
LICENSE.ru.md                   # основной русский текст
NOTICE.md                       # английский project-specific notice
NOTICE.ru.md                    # русский project-specific notice
README_LICENSE_SECTION.md       # английская README-вставка
README_LICENSE_SECTION.ru.md    # русская README-вставка
SPDX_HEADER_EXAMPLES.md
```

Скопируйте нужные файлы из `examples/repo-overlays/<repo>/` в корень целевого репозитория. Русский `.ru.md` текст лицензии является основным, даже если файл по умолчанию `LICENSE.md` написан на английском.

## Дополнительные справочные переводы

Каждый overlay также содержит опциональные переводные файлы `LICENSE.<lang>.md` для `zh-CN`, `ja`, `ko`, `es`, `pt-BR`, `de`, `fr` и `it`. Русский `LICENSE.ru.md` остаётся основным и имеющим преимущественную силу.
