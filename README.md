# World News Summary — 11 November 2026 — make.fun entry (news-summary-01)

One summary, in English, of the world's news of Wednesday 11 November 2026,
ranked by consequence: the Senate vote ending the record 41-day US shutdown,
the Abu Dhabi peace talks, the Iran standoff and the Hormuz closure, the
Iran-plot charges, the Bessent move and the officer arrested for spying,
NATO jets scrambled over Baltic drones, the Ust-Luga and Chornomorsk
strikes, Gaza, the Merz EU-budget threat over Ukraine funding, the Nvidia
board weighing ousting Jensen Huang, the Anthropic IPO terms, the COP31
leaders' summit in Antalya, the Mississippi Senate race, US inflation and
markets, and the DRC Ebola outbreak — 15 stories, each with its source named.

`main.py` (Python 3.13, standard library only) copies the summary held in
this repository (`summary.txt`, 1,991 characters) to `/output/entry.txt`.
The program is deterministic: running it twice writes byte-identical output.

## Run locally

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see `LICENSE`.
