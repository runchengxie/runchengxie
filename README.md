# Hi, I'm Richard

I build reproducible quantitative research, market data, portfolio construction, and execution infrastructure in Python.

My current work focuses on:

- market data assets, contracts, and health checks
- cross-sectional factor and tree-model research
- classic alpha factor workflows
- portfolio construction, backtesting, and target-position exports
- broker execution, reconciliation, and operational tooling
- automated market intelligence and A-share thematic screening

## Selected Projects

### [research-workspace](https://github.com/runchengxie/research-workspace)
A public entry map for my quantitative R&D platform. It pins and documents how market data, alpha research, portfolio backtesting, strategy orchestration, and `quant-execution-engine` hand off to each other through versioned contracts and target-position files.

### [market-intel](https://github.com/runchengxie/market-intel)
An automated market-intelligence system for global market data, theme scoring, factor analysis, daily report rendering, and Feishu distribution, with additional A-share data jobs and report pipelines.

### [hot-sector-screener](https://github.com/runchengxie/hot-sector-screener)
An A-share thematic opportunity screener that combines Tonghuashun hot rankings, Eastmoney concepts, KaiPanLa components, and ETF rotation signals to produce a 50-100 stock monitoring universe before market open.

### [quant-execution-engine](https://github.com/runchengxie/quant-execution-engine)
A broker-connected execution layer that consumes standard `targets.json`, runs preflight checks and rebalance previews, tracks orders, reconciles fills, and keeps audit evidence.

### [money-tree](https://github.com/runchengxie/money-tree)
An A-share classic-alpha research and backtesting toolkit for Alpha101, Alpha191, Alpha158, and Alpha360 workflows, including factor stores, model adapters, portfolio construction, rolling backtests, holdout validation, and reproducible artifacts.

### [a-share-animal-index](https://github.com/runchengxie/a-share-animal-index)
A reproducible thematic index experiment tracking A-share companies with animal-related names, benchmarked against CSI 300.

## Private Infrastructure

Some core platform modules are private and available upon request:

- `market-data-platform`: shared market data asset platform, contracts, registry, quality checks, and published dataset entry points
- `strategy-pipeline`: low-frequency cross-sectional research orchestration layer for model research, evaluation, backtesting, holdings, and `targets.json` exports
- `alpha-research`: reusable alpha research package for features, model evidence, walk-forward diagnostics, CPCV/PBO checks, and signal artifacts
- `portfolio-backtester`: reusable portfolio construction and research backtesting package for Top-K portfolios, turnover, capacity, exposure, and reports
- `a-share-factor-core`: shared A-share ML core for technical features, training, portfolio optimization, and time-series validation

## What I care about

- reproducibility over vague backtest storytelling
- research pipelines that can be rerun
- explicit data contracts, audit trails, and reproducible artifacts
- clear boundaries between data, research, backtesting, execution, and operations
- tools that are small, inspectable, and actually usable
- interesting ideas with measurable outputs

## Stack

`Python` `Pandas` `NumPy` `scikit-learn` `XGBoost` `LightGBM` `Optuna` `PyArrow/Parquet` `DuckDB` `TuShare` `DolphinDB` `TimescaleDB` `uv` `Ruff` `ty` `GitHub Actions`

## Elsewhere

- Notes / Website: [runchengxie.github.io](https://runchengxie.github.io)

---

## 中文简介

我主要用 Python 构建可复现的量化研究、市场数据、组合构建与交易执行工具。

当前主线是把数据平台、alpha 研究、组合回测、策略编排和执行引擎拆成清晰边界，并通过数据契约、研究产物、目标持仓文件和审计证据衔接起来。

关注方向：

- A股数据资产、数据质量检查与可复现数据契约
- 截面因子研究、树模型研究与经典 Alpha 因子流程
- 组合构建、回测、再平衡与持仓快照
- 研究到执行的 `targets.json` 交接
- 券商执行、订单追踪、对账和交易运维
- 市场情报流水线和盘前题材候选池

欢迎查看上面的公开项目（部分核心基础设施为私有仓库，可按需提供）。
