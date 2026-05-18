# Stinger Licenses

Этот репозиторий хранит тексты лицензий, автором которых является **ROMAN ILYIN**.

Английские `.md` файлы используются по умолчанию, чтобы GitHub и большинство читателей могли открывать их напрямую. Русские `.ru.md` файлы являются основными и имеют преимущественную силу. Все остальные языковые файлы являются справочными переводами. При конфликте, различии или разном толковании любого перевода и русской версии применяется русская версия.

## Основная лицензия

| Лицензия | SPDX identifier | Английский справочный текст | Основной русский текст | Индекс переводов |
|---|---|---|---|---|
| Stinger Royalty-Free EULA 1.0 | `LicenseRef-Stinger-Royalty-Free-EULA-1.0` | `LICENSES/LicenseRef-Stinger-Royalty-Free-EULA-1.0.md` | `LICENSES/LicenseRef-Stinger-Royalty-Free-EULA-1.0.ru.md` | `TRANSLATIONS.ru.md` |

## Доступные справочные переводы

```text
zh-CN  Simplified Chinese / китайский упрощённый
ja     Japanese / японский
ko     Korean / корейский
es     Spanish / испанский
pt-BR  Brazilian Portuguese / португальский бразильский
de     German / немецкий
fr     French / французский
it     Italian / итальянский
```

## Stinger Royalty-Free EULA 1.0

`Stinger Royalty-Free EULA 1.0` предназначена для проектов ROMAN ILYIN, которые можно бесплатно и royalty-free использовать в personal, internal, open и commercial End Products, но нельзя продавать, перепродавать, платно распространять или standalone-коммерциализировать сам Asset или Derivative Assets.

Это source-available и royalty-free лицензия для End Products. Она не является OSI-approved open source лицензией, потому что ограничивает standalone resale и standalone commercialization.

## Как использовать в проектном репозитории

Для проекта ROMAN ILYIN, распространяемого под этой лицензией, скопируйте минимум эти файлы в корень проекта:

```text
LICENSE.md       # английский справочный текст для удобства чтения
LICENSE.ru.md    # основной русский текст
NOTICE.md        # project-specific notice, обычно английский по умолчанию
NOTICE.ru.md     # русский project-specific notice, рекомендуется
```

Опциональные справочные переводы тоже можно скопировать, например `LICENSE.zh-CN.md`, `LICENSE.ja.md`, `LICENSE.ko.md`, `LICENSE.es.md`, `LICENSE.pt-BR.md`, `LICENSE.de.md`, `LICENSE.fr.md`, `LICENSE.it.md`.

Готовые примеры для выбранных репозиториев лежат в `examples/repo-overlays/`.

## SPDX

В файлах кода и package metadata используйте:

```text
SPDX-License-Identifier: LicenseRef-Stinger-Royalty-Free-EULA-1.0
```

Для Unity `package.json`:

```json
{
  "license": "LicenseRef-Stinger-Royalty-Free-EULA-1.0"
}
```

## Разрешение на тексты лицензий

Корневой `LICENSE.md` — английская справочная версия разрешения копировать и сохранять тексты лицензий в этом репозитории. Корневой `LICENSE.ru.md` — основной русский текст этого разрешения.

Это разрешение применяется только к документам с текстами лицензий, примерам уведомлений и README-вставкам в этом репозитории. Оно не предоставляет прав на исходный код, ассеты, packages, tools, repositories, trademarks, logos или другие project materials, лицензируемые по этим текстам лицензий.

## Канонический репозиторий

```text
https://github.com/romanilyin/stinger-licenses
```
