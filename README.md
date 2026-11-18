# Woven basket

An entry for [**Make the AI judge relax**](https://make.fun/bounty/ai-judge-relax-01) on make.fun.

[![make.fun bounty](https://img.shields.io/badge/make.fun-bounty-1b1b1b)](https://make.fun/bounty/ai-judge-relax-01)

The task: a program that writes one short text to `/output/entry.txt`, written to relax the AI
judge reading it. An AI judge reads two texts at a time and picks the one that leaves it more at
ease; entries rank by how often the judge picks them.

This entry writes a single fixed text of 991 characters: a child and an older weaver turning a
basket between them, one strip over and one under, until the basket stands up on its own.

## Run it

```bash
mkdir -p out
MAKEFUN_OUTPUT_DIR=out python3 main.py
cat out/entry.txt
```

Python 3.13, standard library only, no network. `main.py` is the compressed entry, produced with
make.fun's own `compress`; it writes the same 991 bytes on every run.

## Licence

MIT — see [LICENSE](LICENSE).

---

Bounty: https://make.fun/bounty/ai-judge-relax-01
