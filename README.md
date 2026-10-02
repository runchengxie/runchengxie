# Hi, I'm Richard

I use Python to build tools for quantitative research, market data, portfolio construction, trading, and market reports.

My current work focuses on:

- market data collection, quality checks, and versioned datasets
- cross-sectional factor research and tree-based models
- classic alpha factor workflows and out-of-sample validation
- portfolio construction, backtesting, risk analysis, and target-position exports
- broker execution, reconciliation, and operational tooling
- public research results, automated market reports, and report delivery
- language models for ranking stock candidates and recording how each selection was made

## Current Projects

### [quant-market-data-platform](https://github.com/runchengxie/quant-market-data-platform)

A tool for collecting, cleaning, checking, and publishing market data for quantitative research. Datasets have documented formats and versions. Current development focuses on mainland China.

### [quant-platform](https://github.com/runchengxie/quant-platform)

A shared framework for backtesting, portfolio construction, risk analysis, and execution simulation. It also defines file formats for publishing research results.

### [quant-market-research](https://github.com/runchengxie/quant-market-research)

Equity research on indices and ETFs, liquidity, trading capacity, microcap stocks, cash flow, and style factors. Its [research website](https://runchengxie.github.io/quant-market-research/) publishes methods and reviewed results so readers can examine and reproduce the studies.

### [quant-factor-observatory](https://github.com/runchengxie/quant-factor-observatory)

A [factor research website](https://runchengxie.github.io/quant-factor-observatory/) with factor definitions, data-quality information, study progress, and reviewed summary results. It covers classic alphas, jump risk, Hermite features, fundamentals, and human-capital studies. Results from private research are reviewed and stripped of private details before publication.

### [quant-intel-platform](https://github.com/runchengxie/quant-intel-platform)

A platform that collects market data and news, checks research files, and turns them into reports and a public dashboard. It also sends reports to configured recipients. [Market reports](https://runchengxie.github.io/quant-intel-platform/) now live here. `quant-intel-pages` keeps the historical reports.

### [quant-trading-workbench](https://github.com/runchengxie/quant-trading-workbench)

A workbench for following markets, studying intraday trading ideas, and testing paper portfolios across A-share, Hong Kong, and US markets. Its web dashboard lets researchers inspect the data and results behind an idea.

### [money-trees](https://github.com/runchengxie/money-trees)

An A-share factor research toolkit covering Alpha101, Alpha191, Alpha158, and Alpha360. It supports factor calculation in Python and DolphinDB, factor mining with genetic algorithms, model training, and rolling validation. It also produces Alpha 810 summary results for `quant-factor-observatory`.

## Selected Research and Experiments

### [a-share-zoo-garden](https://github.com/runchengxie/a-share-zoo-garden)

An index experiment based on A-share companies whose historical names contain animal or plant terms. The two groups have separate selection rules. It compares their performance with the CSI 300 and publishes daily index values, constituents, charts, and calculation methods.

### [ai-stock-picker](https://github.com/runchengxie/ai-stock-picker)

A tool that uses a language model to rank an existing shortlist of A-share or US stocks. It checks that the selected stocks come from that shortlist and saves the results as JSON, along with the inputs and records of the model call.

## How the Projects Fit Together

Each project has its own responsibility. They exchange data and results through documented file formats and interfaces.

| Project | Responsibility |
| --- | --- |
| `quant-market-data-platform` | Market-data collection, quality checks, versioning, and publication |
| `quant-platform` | Shared backtesting, portfolio construction, risk, and execution simulation |
| [quant-backtest-runtime](https://github.com/runchengxie/quant-backtest-runtime) | Running submitted backtests, tracking job status, and publishing results |
| `quant-research` (private) | Proprietary strategies, features, models, experiments, and supporting results |
| `quant-market-research` | Public market studies, methods, and results |
| `quant-factor-observatory` | Factor catalogs, standardized studies, and reviewed summary results |
| `quant-intel-platform` | Market reports, research results, dashboards, and report delivery |

Production settings stay in private repositories. Raw market data, credentials, and full research outputs are stored separately from source code. Public research sites publish reviewed results.

[research-workspace](https://github.com/runchengxie/research-workspace) is archived. It preserves older versions and migration documentation. `alpha-research`, `portfolio-backtester`, `strategy-pipeline`, `quant-execution-engine`, and `deep-learning-tick-data-prediction` are also archived. New development takes place in the projects listed above.

## What I care about

- research that can be rerun from documented data and steps
- results that can be checked against the data
- documented data formats, versioned files, and records of each run
- clear responsibilities for data, research, backtesting, execution, and operations
- small tools that are easy to inspect and useful in practice

## Stack

`Python` `Pandas` `NumPy` `scikit-learn` `XGBoost` `LightGBM` `Optuna` `PyArrow/Parquet` `DuckDB` `TuShare` `DolphinDB` `TimescaleDB` `uv` `Ruff` `ty` `GitHub Actions`

## Elsewhere

- Notes / Website: [runchengxie.github.io](https://runchengxie.github.io)

---

## 中文简介

我主要用 Python 开发量化研究和交易工具，包括市场数据处理、因子研究、组合构建、回测、交易执行和市场报告。

这些项目各自负责一部分工作，通过约定的数据格式和接口交换数据与研究结果。

公开项目主要包括：

- `quant-market-data-platform` 采集和检查市场数据，按版本发布数据集。
- `quant-platform` 提供组合构建、回测、风险分析和交易执行模拟工具。
- `quant-backtest-runtime` 执行提交的回测任务，记录任务状态并发布结果。
- `quant-market-research` 发布市场研究方法和结果，方便读者查看和复现。
- `quant-factor-observatory` 展示因子定义、数据质量、研究进展和审核后的汇总结果。
- `quant-intel-platform` 生成市场日报，在网页上展示数据和研究结果，并发送报告。
- `quant-trading-workbench` 用于观察市场、研究日内交易思路和测试模拟组合。
- `money-trees` 计算和挖掘经典因子，训练模型并进行滚动验证。
- `ai-stock-picker` 用大语言模型对已有股票候选名单排序，保存结果、输入数据和模型调用记录。
- `a-share-zoo-garden` 根据公司历史名称构建动植物主题指数，并与沪深 300 比较。

策略细节、模型和完整研究记录保留在私有仓库 `quant-research` 中，生产配置也保存在私有仓库中。原始市场数据、密钥和完整运行结果存放在代码仓库之外。公开网站发布审核后的研究结果。

`research-workspace` 等旧框架仓库已归档，保留历史版本和迁移说明。`quant-intel-pages` 保留历史报告，新日报请查看 `quant-intel-platform`。
