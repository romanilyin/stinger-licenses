# Copying the license into project repositories

Use this convention in project repositories:

```text
LICENSE.md       # English convenience text, easier to read by default
LICENSE.ru.md    # authoritative Russian text
NOTICE.md        # English project-specific notice
NOTICE.ru.md     # Russian project-specific notice, recommended
```

Ready overlays are available here:

```text
examples/repo-overlays/CanonicalPath/
examples/repo-overlays/sgg-perfmeter/
examples/repo-overlays/sgg-unity-mcp-gateway/
```

## Important language rule

The English `LICENSE.md` is intentionally the default file name for readability on GitHub and package registries. The Russian `LICENSE.ru.md` is the authoritative and controlling text. If the English and Russian versions conflict, differ, or are interpreted differently, the Russian version controls.

## SPDX

In source files:

```text
SPDX-License-Identifier: LicenseRef-Stinger-Royalty-Free-EULA-1.0
```

In Unity `package.json`:

```json
{
  "license": "LicenseRef-Stinger-Royalty-Free-EULA-1.0"
}
```

## Extra translations

Optional convenience translations can be copied as `LICENSE.<lang>.md`, for example `LICENSE.zh-CN.md` and `LICENSE.ja.md`. The Russian `LICENSE.ru.md` remains controlling.
