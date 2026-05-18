# Apply this multilingual overlay

This archive is arranged as the root of the `stinger-licenses` repository.

Recommended workflow:

```bash
# from a local clone of https://github.com/romanilyin/stinger-licenses
rsync -av --exclude .git /path/to/unpacked/stinger-licenses/ ./

git status
git add .
git commit -m "Add convenience translations for Stinger Royalty-Free EULA 1.0"
git push
```

Do not use `--delete` unless you intentionally want to remove files that are not present in this archive.

## Language priority

The English `.md` files remain the default files for GitHub readability.
The Russian `.ru.md` files are the primary and controlling versions.
All other language files are convenience translations only.
If a translation conflicts with, differs from, or is interpreted differently from the Russian version, the Russian version controls.

## Added convenience translations

```text
zh-CN  Simplified Chinese
ja     Japanese
ko     Korean
es     Spanish
pt-BR  Brazilian Portuguese
de     German
fr     French
it     Italian
```

## Important distinction

Root `LICENSE.<lang>.md` files describe permission to copy and preserve the license texts in this repository.
The actual full EULA translations are in `LICENSES/`.

For project repositories such as `CanonicalPath`, `sgg-perfmeter`, and `sgg-unity-mcp-gateway`, ready-to-copy EULA overlays are in `examples/repo-overlays/`.
