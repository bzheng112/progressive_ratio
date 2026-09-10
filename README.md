# progressive_ratio

Is there a neural signature of the breakpoint in the Sun/Bari progressive-ratio SEEG dataset?

- `notebooks/progressive_ratio.ipynb` — the analysis, one cell per step, each step explained before its code
- `code/library.py` — the functions the notebook calls; read it top to bottom, it is short on purpose
- `results/` — tables and figures the notebook writes

Data: the release lives in `My Drive/data/PR-iEEG/raw/bids` (plus `raw/docs`) and is never modified or written to.
Caches, if a step ever needs one, go to `My Drive/data/PR-iEEG/cache/`, never into this repo.
Kernel: `Python (pr-ieeg)` (`~/opt/anaconda3/envs/pr-ieeg`). The dataset is unpublished and private to the collaboration.
