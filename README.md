Data science student. I like projects that touch real data end to end — ingestion, storage, analysis, deployment — instead of stopping at a notebook.

### Highlights

**[cudf-bench](https://github.com/alexislowys/cudf-bench)** — GPU benchmark harness that found a performance defect in NVIDIA's cuDF dataframe library: hash groupby is ~1.5x slower on skewed keys (measured at locked clocks) while pandas and Polars get *faster* on the same input. Reproduced by a RAPIDS maintainer on GH200 hardware, kernel-level fix direction now under investigation upstream — [rapidsai/cudf#23256](https://github.com/rapidsai/cudf/issues/23256). Includes a Numba prototype 2.47x faster on the skewed case.

**[insider-tracker](https://github.com/alexislowys/insider-tracker)** — SEC Form 4 insider-trading tracker: cluster-buy signals, screener, per-insider track records (average return, win rate), price charts with trade markers. Next.js + PostgreSQL, EDGAR polling every 5 minutes, email alerts. Live at [insider-tracker-three.vercel.app](https://insider-tracker-three.vercel.app).

**[ai-financial-news](https://github.com/alexislowys/ai-financial-news)** — financial news summarizer with LLM sentiment analysis, built to a $0 AI budget (batching, caching, analyze-once persistence). Next.js + Gemini + Neon Postgres. Live at [ai-financial-news-3i44.vercel.app](https://ai-financial-news-3i44.vercel.app).

Python · C++ · SQL · TypeScript
