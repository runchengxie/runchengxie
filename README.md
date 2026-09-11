# Hi, I'm Richard

I build reproducible quantitative research, market data, portfolio construction, execution, and market-intelligence systems in Python.

My current work focuses on:

- market data assets, contracts, quality checks, and published datasets
- cross-sectional factor research and tree-based models
- classic alpha factor workflows and out-of-sample validation
- portfolio construction, backtesting, risk analysis, and target-position exports
- broker execution, reconciliation, and operational tooling
- automated market intelligence, report delivery, and A-share thematic screening

## Current Projects

### [quant-trading-workbench](https://github.com/runchengxie/quant-trading-workbench)
The current workbench for market observation, strategy research, paper portfolios, execution experiments, research snapshots, and the web dashboard. It is now the maintenance home for the former `trading-research-dashboard` and `wu-t0-trading-dashboard` projects; those repositories remain useful for historical traceability and rollback only.

### [factor-research-observatory](https://github.com/runchengxie/factor-research-observatory)
An observatory for minute-level factor operators and descriptive factor research. It covers volatility, jumps, liquidity, Hermite features, and a browsable factor catalog with explicit research-status metadata.

### [quant-market-research](https://github.com/runchengxie/quant-market-research)
The canonical public research-notebook and evidence layer for cross-market equities, liquidity, capacity, index replication, micro-cap studies, and Barra/style-factor diagnostics. It turns research questions into executable reports and visual summaries while keeping alpha, signal, IC/decay, and strategy decisions in `quant-research`.

### [quant-intel-platform](https://github.com/runchengxie/quant-intel-platform)
The current market-intelligence platform for global market data, news and theme scoring, report rendering, web dashboards, and Feishu delivery. It supersedes the former `market-intel` repository; the old name remains only in compatibility paths and historical documentation.

### [hot-sector-screener](https://github.com/runchengxie/hot-sector-screener)
An A-share thematic opportunity screener that combines Tonghuashun hot rankings, Eastmoney concepts, KaiPanLa components, and ETF rotation signals to produce a 50–100-stock monitoring universe before market open.

### [money-trees](https://github.com/runchengxie/money-trees)
An A-share classic-alpha research and backtesting toolkit covering Alpha101, Alpha191, Alpha158, and Alpha360 workflows, factor stores, model adapters, portfolio construction, rolling backtests, holdout validation, and reproducible artifacts.

### [a-share-zoo-garden](https://github.com/runchengxie/a-share-zoo-garden)
A reproducible thematic index experiment that tracks A-share companies with animal-related names, compares them with the CSI 300, and experiments with a conservative plant-themed universe. It publishes charts and a web page to GitHub Pages and Cloudflare Pages.

## Integration and Migration Repositories

### [research-workspace](https://github.com/runchengxie/research-workspace)
The former public entry point for the quantitative R&D platform. It is now in sunset transition: it remains useful for historical reproduction, cross-repository version locking, contracts, and migration navigation, but is no longer the default home for new platform or strategy implementation.

The current ownership split is:

- `quant-market-data-platform`: market-data production, quality checks, versioning, and published assets
- `quant-platform`: reusable platform capabilities, portfolio/backtesting infrastructure, contracts, and execution interfaces
- `quant-research`: private strategy IP, factors, machine learning, experiments, evidence, and strategy applications
- `quant-intel-platform`: private market-intelligence platform implementation

The old `market-intel`, `quant-execution-engine`, `alpha-research`, `portfolio-backtester`, `strategy-*`, and
`deep-learning-tick-data-prediction` repositories are retained as migration or compatibility
references while their responsibilities move to the target repositories above.

## Private Infrastructure

Some core modules remain private. Their current ownership is documented in the migration materials in
`research-workspace`; the repository names below are the current target boundaries rather than a
promise that every remote or Python package has already been renamed:

- `quant-market-data-platform`: market data assets, contracts, registry, quality checks, and published dataset entry points
- `quant-platform`: reusable data interfaces, portfolio/backtesting infrastructure, risk, execution interfaces, and shared contracts
- `quant-research`: cross-sectional research, factors, model evidence, walk-forward diagnostics, strategy orchestration, and signal artifacts
- `quant-intel-platform`: market-intelligence data processing, report generation, and delivery platform

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

当前主线是把数据平台、通用量化平台、私有策略研究、市场情报和交易工作台划分为清晰的模块，再通过数据契约、版本化研究产物、目标持仓文件和审计证据连接起来。

关注方向：

- A 股数据资产、数据质量检查和可复现数据契约
- 截面因子研究、树模型研究和经典 Alpha 因子流程
- 组合构建、回测、再平衡、风险分析和持仓快照
- 研究到执行之间的 `targets.json` 交接，以及执行接口和审计边界
- 交易工作台、纸面组合、订单研究和交易运维
- 市场情报流水线、报告投递和盘前题材候选池

欢迎查看上面的公开项目。部分平台、策略研究和市场情报基础设施为私有仓库，旧仓库名称会在迁移完成前继续出现在历史文档和兼容路径中。
