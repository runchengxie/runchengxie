# Hi, I'm Richard

I build reproducible quantitative research, market data, portfolio construction, execution, and market-intelligence systems in Python.

My current work focuses on:

- market data assets, contracts, quality checks, and published datasets
- cross-sectional factor research and tree-based models
- classic alpha factor workflows and out-of-sample validation
- portfolio construction, backtesting, risk analysis, and target-position exports
- broker execution, reconciliation, and operational tooling
- automated market intelligence, report delivery, and A-share thematic screening

## Selected Projects

### [research-workspace](https://github.com/runchengxie/research-workspace)
A public entry point for my quantitative R&D platform. It pins the cooperating repositories and documents how market data, alpha research, portfolio backtesting, strategy orchestration, and `quant-execution-engine` exchange versioned artifacts and target-position files.

### [market-intel](https://github.com/runchengxie/market-intel)
An automated market-intelligence system for global market data, theme scoring, report rendering, web dashboards, and Feishu delivery. It also assembles A-share reports and consumes research artifacts published by `research-workspace`.

### [hot-sector-screener](https://github.com/runchengxie/hot-sector-screener)
An A-share thematic opportunity screener that combines Tonghuashun hot rankings, Eastmoney concepts, KaiPanLa components, and ETF rotation signals to produce a 50–100-stock monitoring universe before market open.

### [quant-execution-engine](https://github.com/runchengxie/quant-execution-engine)
A broker-connected execution layer that consumes standard `targets.json`, runs preflight checks and rebalance previews, tracks orders, reconciles fills, and keeps audit evidence.

### [money-trees](https://github.com/runchengxie/money-trees)
An A-share classic-alpha research and backtesting toolkit covering Alpha101, Alpha191, Alpha158, and Alpha360 workflows, factor stores, model adapters, portfolio construction, rolling backtests, holdout validation, and reproducible artifacts.

### [a-share-zoo-garden](https://github.com/runchengxie/a-share-zoo-garden)
A reproducible thematic index experiment that tracks A-share companies with animal-related names, compares them with the CSI 300, and experiments with a conservative plant-themed universe. It publishes charts and a web page to GitHub Pages and Cloudflare Pages.

### [trading-research-dashboard](https://github.com/runchengxie/trading-research-dashboard)
A web dashboard for trading-strategy research, paper-portfolio experiments, market data, and performance review.

## Private Infrastructure

Some core modules remain private. Their public-facing interfaces and ownership boundaries are documented in `research-workspace`:

- `market-data-platform`: market data assets, contracts, registry, quality checks, and published dataset entry points
- `strategy-pipeline`: cross-sectional research orchestration for model research, evaluation, backtesting, holdings, and `targets.json` exports
- `alpha-research`: reusable alpha research for features, model evidence, walk-forward diagnostics, CPCV/PBO checks, and signal artifacts
- `portfolio-backtester`: portfolio construction and research backtesting for Top-K portfolios, turnover, capacity, exposure, and reports
- `a-share-factor-core`: shared A-share ML components for technical features, training, portfolio optimization, and time-series validation

## What I care about

- reproducible research over vague backtest narratives
- research pipelines that can be rerun from documented inputs
- explicit data contracts, audit trails, and versioned artifacts
- clear boundaries among data, research, backtesting, execution, and operations
- small, inspectable tools that are useful in practice
- interesting ideas with measurable outputs

## Stack

`Python` `Pandas` `NumPy` `scikit-learn` `XGBoost` `LightGBM` `Optuna` `PyArrow/Parquet` `DuckDB` `TuShare` `DolphinDB` `TimescaleDB` `uv` `Ruff` `ty` `GitHub Actions`

## Elsewhere

- Notes / Website: [runchengxie.github.io](https://runchengxie.github.io)

---

## 中文简介

我主要用 Python 构建可复现的量化研究、市场数据、组合构建、交易执行和市场情报工具。

当前主线是把数据平台、alpha 研究、组合回测、策略编排、市场情报和执行引擎划分为清晰的模块，再通过数据契约、版本化研究产物、目标持仓文件和审计证据连接起来。

关注方向：

- A 股数据资产、数据质量检查和可复现数据契约
- 截面因子研究、树模型研究和经典 Alpha 因子流程
- 组合构建、回测、再平衡、风险分析和持仓快照
- 研究到执行之间的 `targets.json` 交接
- 券商执行、订单追踪、对账和交易运维
- 市场情报流水线、报告投递和盘前题材候选池

欢迎查看上面的公开项目（部分核心基础设施为私有仓库，可按需提供）。
