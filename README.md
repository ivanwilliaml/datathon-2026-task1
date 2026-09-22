# Datathon 2026 — Task 1: Beijing Traffic Speed Forecasting

Team cupuu — forecasting road-segment traffic speed 5/10/15 steps ahead from two
continuous sensor blocks and English-language event text.

## Open this first
- [`cupuu_Task1_Notebook.ipynb`](./cupuu_Task1_Notebook.ipynb) — the final notebook.
  Rebuilds the submission from scratch: reads data, maps event text to road segments,
  builds features, trains 4 LightGBM variants, blends them by least squares.

## Notable technique
Event text names roads in English while segment metadata uses Chinese characters —
matched via pinyin-based token-overlap scoring, reaching ~99.5% coverage.

No dataset is committed here.
