# Миграция / перезаливка

Этот пакет подготовлен как корневая структура для:

```text
https://github.com/romanilyin/stinger-licenses
```

## Полная перезаливка

1. Удалите старую вложенную папку, особенно `Stinger Royalty-Free EULA 1.0/`, если она есть.
2. Скопируйте содержимое папки `stinger-licenses/` из этого архива в корень репозитория.
3. Закоммитьте и запушьте.

Ожидаемая структура корня:

```text
README.md
README.ru.md
LICENSE.md
LICENSE.ru.md
NOTICE.md
NOTICE.ru.md
LICENSES/
  LicenseRef-Stinger-Royalty-Free-EULA-1.0.md
  LicenseRef-Stinger-Royalty-Free-EULA-1.0.ru.md
examples/
  repo-overlays/
    CanonicalPath/
    sgg-perfmeter/
    sgg-unity-mcp-gateway/
manifest.json
.editorconfig
.gitattributes
```

## Язык и имена файлов

Английские файлы используют базовые имена `.md`, чтобы их было удобно читать по умолчанию:

```text
LICENSE.md
README.md
NOTICE.md
LICENSES/LicenseRef-Stinger-Royalty-Free-EULA-1.0.md
```

Русские файлы используют `.ru.md` и являются основными:

```text
LICENSE.ru.md
README.ru.md
NOTICE.ru.md
LICENSES/LicenseRef-Stinger-Royalty-Free-EULA-1.0.ru.md
```

При расхождении, противоречии или разном толковании английской и русской версий применяется русская версия.
