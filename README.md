# A negative result on shrinkage estimators in small-N replication

An operational negative result on James–Stein shrinkage in small-N replication contexts, with a math-heavy body — a demonstration paper in the [rrxiv](https://rrxiv.com) reference corpus.

**Read the published paper:** [rrxiv.com/papers/rrxiv:2605.00004](https://rrxiv.com/papers/rrxiv:2605.00004)

## What this demonstrates

An operational negative result on James–Stein shrinkage in small-N replication contexts, with a math-heavy body. Seven claims — a worked example of publishing what did not work as a first-class result, not a footnote.

## Build it locally

This repo was created from the [rrxiv-paper-template](https://github.com/random-walks/rrxiv-paper-template).

```bash
./scripts/build.sh          # tectonic → build/main.pdf
./scripts/extract-cir.sh    # rrxiv parse → build/main.cir.json
./scripts/verify.sh         # validate the CIR against the rrxiv schema
```

The `rrxiv` CLI used by these scripts isn't on PyPI yet — install it from source:

```bash
pip install "rrxiv @ git+https://github.com/random-walks/rrxiv-python.git"
```

## License

Dual-licensed, matching the rest of the corpus:

- **Content** — the paper text and figures in `paper/`, plus `rrxiv-meta.json`, under [CC-BY-4.0](./LICENSE-CONTENT).
- **Code** — the `scripts/` and CI under [MIT](./LICENSE-CODE).
