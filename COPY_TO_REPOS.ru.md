# Как скопировать лицензию в проектные репозитории

В проектных репозиториях используйте такую схему:

```text
LICENSE.md       # английский справочный текст, удобный для чтения по умолчанию
LICENSE.ru.md    # основной русский текст
NOTICE.md        # английский project-specific notice
NOTICE.ru.md     # русский project-specific notice, рекомендуется
```

Готовые overlay-файлы лежат здесь:

```text
examples/repo-overlays/CanonicalPath/
examples/repo-overlays/sgg-perfmeter/
examples/repo-overlays/sgg-unity-mcp-gateway/
```

## Важное правило о языке

Английский `LICENSE.md` намеренно используется как файл по умолчанию для удобства чтения на GitHub и в package registries. Русский `LICENSE.ru.md` является основным и имеющим преимущественную силу текстом. При расхождении, противоречии или разном толковании английской и русской версий применяется русская версия.

## SPDX

В файлах кода:

```text
SPDX-License-Identifier: LicenseRef-Stinger-Royalty-Free-EULA-1.0
```

В Unity `package.json`:

```json
{
  "license": "LicenseRef-Stinger-Royalty-Free-EULA-1.0"
}
```

## Extra translations

Опциональные справочные переводы можно копировать как `LICENSE.<lang>.md`, например `LICENSE.zh-CN.md` и `LICENSE.ja.md`. Основным остаётся русский `LICENSE.ru.md`.
