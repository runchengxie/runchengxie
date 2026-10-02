# Hi, I'm Richard

I build reproducible quantitative research, market data, portfolio construction, execution, and market-intelligence systems in Python.

My current work focuses on:

- market data assets, contracts, quality checks, and published datasets
- cross-sectional factor research and tree-based models
- classic alpha factor workflows and out-of-sample validation
- portfolio construction, backtesting, risk analysis, and target-position exports
- broker execution, reconciliation, and operational tooling
- public research evidence, automated market reports, and report delivery
- traceable AI-assisted candidate ranking

## Current Projects

### [quant-market-data-platform](https://github.com/runchengxie/quant-market-data-platform)

A market-data foundation for quantitative researchers. It ingests, standardizes, validates, versions, and publishes assets through documented contracts, with current development focused on mainland China.

### [quant-platform](https://github.com/runchengxie/quant-platform)

A reusable framework for research tools: backtesting, portfolio construction, risk analysis, execution simulation, and public research artifact contracts.

### [quant-market-research](https://github.com/runchengxie/quant-market-research)

Reproducible public equity research on indices and ETFs, liquidity, capacity, microcaps, cash flow, and style factors. It publishes methods, reviewed derived results, and a [research website](https://runchengxie.github.io/quant-market-research/).

### [quant-factor-observatory](https://github.com/runchengxie/quant-factor-observatory)

A [public factor research observatory](https://runchengxie.github.io/quant-factor-observatory/) for definitions, data quality, research status, and reviewed aggregate evidence. Its catalogs cover classic alphas, jump risk, Hermite features, fundamentals, and human-capital studies, with private research published only as reviewed and redacted snapshots.

### [quant-intel-platform](https://github.com/runchengxie/quant-intel-platform)

A market-intelligence platform that collects market and news information, validates versioned research artifacts, and produces reports, a public dashboard, and configured delivery. [Market reports](https://runchengxie.github.io/quant-intel-platform/) now live here; `quant-intel-pages` preserves the legacy archive.

### [quant-trading-workbench](https://github.com/runchengxie/quant-trading-workbench)

An interactive workbench for market observation, intraday research, paper-portfolio experiments, and research snapshots across A-share, Hong Kong, and US markets. Its web dashboard helps researchers inspect the evidence behind an idea.

### [money-trees](https://github.com/runchengxie/money-trees)

An A-share classic-alpha toolkit covering Alpha101, Alpha191, Alpha158, and Alpha360, Python and DolphinDB factor generation, genetic factor mining, model adapters, and rolling validation. It also generates aggregate Alpha 810 evidence for the public Observatory.

## Selected Research and Experiments

### [a-share-zoo-garden](https://github.com/runchengxie/a-share-zoo-garden)

A thematic index experiment that selects A-share companies with animal- or plant-related historical names. It maintains separate rule sets, compares both gardens with the CSI 300, and publishes daily index snapshots, constituents, charts, and methodology.

### [ai-stock-picker](https://github.com/runchengxie/ai-stock-picker)

A tool for researchers to rerank an existing A-share or US stock shortlist with a language model. It checks that selections stay within the supplied pool and saves validated JSON results with traceable run evidence.

## How the Projects Fit Together

The projects are maintained independently and connect through documented data and artifact contracts.

| Project | Responsibility |
| --- | --- |
| `quant-market-data-platform` | Market-data ingestion, quality, versioning, and asset publication |
| `quant-platform` | Shared backtesting, portfolio construction, risk, and execution simulation |
| [quant-backtest-runtime](https://github.com/runchengxie/quant-backtest-runtime) | Submitted backtest jobs, worker execution, job state, and result publication |
| `quant-research` (private) | Proprietary strategies, features, models, experiments, and research evidence |
| `quant-market-research` | Independent public market studies, methods, and derived results |
| `quant-factor-observatory` | Factor catalogs, standardized studies, and reviewed public evidence |
| `quant-intel-platform` | Market reports, artifact presentation, dashboards, and delivery |

Production deployment settings remain in private repositories. Raw market data, credentials, and complete research run outputs stay outside source repositories; public research sites use reviewed publication artifacts.

[research-workspace](https://github.com/runchengxie/research-workspace) is archived and remains a historical reproduction and migration reference. The former `alpha-research`, `portfolio-backtester`, `strategy-pipeline`, `quant-execution-engine`, and `deep-learning-tick-data-prediction` repositories are also archived. Current work uses the project owners above.

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

目前主要围绕数据平台、通用量化平台、策略研究、市场情报和交易工作台展开，并通过数据契约、版本化研究产物、目标持仓文件和审计证据把这些部分连接起来。

公开项目主要包括：

- `quant-market-data-platform` 负责数据采集、质量检查和版本化发布，`quant-platform` 提供组合、回测和风险分析能力，`quant-backtest-runtime` 负责回测任务执行。
- `quant-market-research` 发布市场研究方法和结果，`quant-factor-observatory` 展示因子定义、研究状态和审核后的汇总证据。
- `quant-intel-platform` 负责市场日报、看板和报告投递，`quant-trading-workbench` 提供市场观察、日内研究和模拟组合实验。
- `money-trees` 支持经典 Alpha 因子计算、挖掘和验证，`ai-stock-picker` 用大语言模型对已有候选池排序，并保存可追溯的结果。
- `a-share-zoo-garden` 根据公司历史名称构建动植物主题指数，并与沪深 300 比较。

策略细节和完整研究证据保留在私有 `quant-research` 中，生产配置也由私有仓库管理。公开网站展示审核后的研究产物。`research-workspace` 等旧框架仓库已归档，`quant-intel-pages` 保留历史报告，新日报请查看 `quant-intel-platform`。
