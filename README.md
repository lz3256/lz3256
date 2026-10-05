# Linfeng Zhao

[Research portfolio](https://lz3256.github.io/) · [GitHub](https://github.com/lz3256)

I build research projects in financial machine learning: numerical reasoning over financial reports, trade-event modeling, and implied-volatility forecasting. My repositories include implementation details, controlled experiments, recorded results, and limitations.

我的项目围绕金融数值推理、逐笔成交建模和隐含波动率研究展开，重点是把数据处理、实验对照和结果解释做清楚。

## Selected projects

| Project | Research question | Work completed |
| --- | --- | --- |
| [FinDelta](https://github.com/lz3256/fin-delta) | How do training duration, arithmetic execution, and label quality affect financial numerical reasoning? | FinQA data pipeline, LoRA SFT and DPO, an evidence-bound arithmetic executor, and matched label-repair experiments across three seeds. |
| [TAQ Event Lab](https://github.com/lz3256/taq-event-lab) | How does trade-event tokenization behave under different exposure and compute budgets? | Small Transformer baselines, TAQ cleaning audits, comparisons across repeated seeds, downstream direction tasks, and frozen-representation probes. |
| [IV Surface Lab](https://github.com/lz3256/iv-surface-lab) | Do implied-volatility features add information to return and variance forecasts? | SPX option-surface construction, SPY data audits, HAR benchmarks, rolling forecasts, and documented empirical comparisons. |

## Earlier work

- [Ethereum modularity research](https://github.com/lz3256/eth-modularity-volatility): transaction graphs, event studies, and exploratory volatility associations; the current ROC metrics are in sample.
- [AAPL LSTM prototype](https://github.com/lz3256/aapl_lstm_trading): sequence classification and a paper-trading adapter, with documented evaluation issues.
- [Machine Learning Data Collection](https://github.com/lz3256/Bootcamp_ML): public datasets, loading notes, and an inspection entry point.
- [MachineTrader](https://github.com/lz3256/MachineTrader): a project index and proposed development outline.

## Research approach

I document data sources, split rules, comparison budgets, uncertainty, and experiments that did not confirm a benefit. Research metrics are interpreted within their sample and evaluation design; they are not evidence of live trading performance.

FinDelta uses a custom FinQA cohort. TAQ Event Lab uses trade records for AAPL, MSFT, AMZN, and NVDA. IV Surface Lab uses optionsDX SPX option chains and CRSP SPY data. Vendor market records are excluded from the public repositories; TAQ and IV projects provide separate synthetic demos.

## Credits

FinDelta, TAQ Event Lab, and IV Surface Lab were developed with substantial assistance from OpenAI Codex for implementation, analysis, debugging, and documentation. Dataset attribution, method inspirations, and experiment limitations are recorded in each repository.
