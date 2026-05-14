# Migration / re-upload guide

This package is prepared as the root structure for:

```text
https://github.com/romanilyin/stinger-licenses
```

## Full re-upload

1. Remove the old nested directory, especially `Stinger Royalty-Free EULA 1.0/`, if it exists.
2. Copy the contents of the `stinger-licenses/` directory from this archive into the repository root.
3. Commit and push.

Expected root structure:

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

## Language and file naming

English files use the base `.md` names for readability:

```text
LICENSE.md
README.md
NOTICE.md
LICENSES/LicenseRef-Stinger-Royalty-Free-EULA-1.0.md
```

Russian files use `.ru.md` and are authoritative:

```text
LICENSE.ru.md
README.ru.md
NOTICE.ru.md
LICENSES/LicenseRef-Stinger-Royalty-Free-EULA-1.0.ru.md
```

If the English and Russian versions conflict, differ, or are interpreted differently, the Russian version controls.
