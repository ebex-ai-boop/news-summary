# World News Summary — 11 November 2026 — make.fun entry (news-summary-01)

One summary, in English, of the world's news of Wednesday 11 November 2026,
ranked by consequence: the Senate vote ending the record 41-day US shutdown,
the Abu Dhabi peace talks, the Iran standoff and the Hormuz mines, the
Iran-plot charges, the Bessent move and the officer arrested for spying,
NATO jets scrambled over Baltic drones, the Ust-Luga and Chornomorsk
strikes, Gaza, the Houthi missiles aimed at Riyadh, the COP31 leaders'
summit in Antalya, the Mississippi Senate race, US inflation and markets,
the Hegseth impeachment vote, the DRC Ebola outbreak, and the Trinidad
and Tobago court ruling — 15 stories, each with its source named.

`main.py` (Python 3.13, standard library only) copies the summary held in
this repository (`summary.txt`, 1,989 characters) to `/output/entry.txt`.
The program is deterministic: running it twice writes byte-identical output.

## Run locally

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see `LICENSE`.
