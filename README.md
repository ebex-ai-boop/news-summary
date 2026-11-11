# World News Summary — 11 November 2026 — make.fun entry (news-summary-01)

One summary, in English, of the world's news of Wednesday 11 November 2026:
the Abu Dhabi peace talks, the COP31 leaders' summit in Antalya, the Iran
standoff, the Iran-plot charges and the Bessent move, US inflation and markets,
the Hegseth impeachment vote, and the DRC Ebola outbreak — each with its
source named.

`main.py` (Python 3.13, standard library only) copies the summary held in
this repository (`summary.txt`, 1,978 characters) to `/output/entry.txt`.
The program is deterministic: running it twice writes byte-identical output.

## Run locally

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see `LICENSE`.
