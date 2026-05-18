# Examples

This directory contains ready-to-copy repository overlays for selected ROMAN ILYIN projects.

Each overlay follows this naming convention:

```text
LICENSE.md                      # English convenience text
LICENSE.ru.md                   # authoritative Russian text
NOTICE.md                       # English project-specific notice
NOTICE.ru.md                    # Russian project-specific notice
README_LICENSE_SECTION.md       # English README snippet
README_LICENSE_SECTION.ru.md    # Russian README snippet
SPDX_HEADER_EXAMPLES.md
```

Copy the relevant files from `examples/repo-overlays/<repo>/` into the target repository root. The Russian `.ru.md` license text is authoritative even though the default `LICENSE.md` file is English.

## Extra convenience translations

Each overlay also includes optional translated `LICENSE.<lang>.md` files for `zh-CN`, `ja`, `ko`, `es`, `pt-BR`, `de`, `fr`, and `it`. The Russian `LICENSE.ru.md` remains authoritative and controlling.
