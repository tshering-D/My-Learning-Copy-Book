# My Learning Copy Book

A personal copy book for anything I learn during my PhD and beyond:
practical Markdown tutorials, notes, and cheat sheets.

**📖 Read it in the wiki: https://github.com/tshering-D/My-Learning-Copy-Book/wiki**

## Contents

| Page | What it covers |
| :--- | :--- |
| [HPC Command-Line Cheat Sheet](https://github.com/tshering-D/My-Learning-Copy-Book/wiki/HPC-Command%E2%80%90Line-Cheat-Sheet) | PBS job submission and monitoring, file transfer, `grep`, `sed` and other everyday cluster commands |
| [Running graphREML on a PBS HPC Cluster](https://github.com/tshering-D/My-Learning-Copy-Book/wiki/Running-graphREML-on-a-PBS-HPC-Cluster) | Setting up and running graphREML heritability enrichment on PBS |
| [ABC model on chr22](https://github.com/tshering-D/My-Learning-Copy-Book/wiki/ABC-model-on-chr22) | Running the Activity-by-Contact enhancer-gene workflow on the chromosome 22 test data |
| [Interpretation of chr22 (K562 datasets)](https://github.com/tshering-D/My-Learning-Copy-Book/wiki/Interpretation-of-chr22-(K562-datasets)) | What each ABC output file means and how to read the results |

## How it's maintained

The pages are written in Obsidian, in a `Learning Copy Book` folder of my notes vault,
and published to the wiki with [`scripts/publish-wiki`](scripts/publish-wiki):

```bash
scripts/publish-wiki "path/to/vault/Learning Copy Book" --dry-run   # preview
scripts/publish-wiki "path/to/vault/Learning Copy Book"             # publish
```

The folder is the source of truth: each note becomes a wiki page (`My Page.md` → `My-Page`),
the note named after the folder becomes `Home`, Obsidian `[[links]]` are converted to wiki links,
and notes with `publish: false` in their properties stay private. Edits made directly on the
wiki are overwritten by the next publish, so edit in Obsidian.

## Purpose

- Keep short, practical notes on tools, methods, and concepts I learn.
- Build a personal reference I can come back to later.
- Start simple and grow over time.

## License

Happy for anyone to use these notes if they're useful to you.
