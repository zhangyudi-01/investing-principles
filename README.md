# investing-principles

基于[嘉信理财「7大投资原则」（Charles Schwab 7 Investing Principles）](https://international.schwab.com/investing-principles)构建的个人长期投资体系仓库，核心是一套长期、低成本、规则化的资产配置与执行框架。

## 文件导航

本仓库遵循**「方案 / 纪律 / 记录」三分离**原则，三个关注点各自独立存放、互不混杂：

| 文件 | 角色 | 内容摘要 |
| :--- | :---: | :--- |
| [investing_principles_portfolio.md](investing_principles_portfolio.md) | **方案** | 配置理念、70/30 资产蓝图与标的明细、四大模块配置逻辑——回答「买什么、为什么买」 |
| [investment_discipline_rules.md](investment_discipline_rules.md) | **纪律 / 规则** | 仓位硬性约束、再平衡触发机制（日历定期 + ±5% 阈值熔断）、三情境 SOP、低摩擦执行守则——回答「什么时候动、怎么动」 |
| [investment_capital_ledger.md](investment_capital_ledger.md) | **记录** | 累计投入本金流水与按目标配比拆解的基准分配台账——回答「投了多少、如何拆分」 |

辅助文件：

| 文件 | 说明 |
| :--- | :--- |
| [investment_capital_ledger.xlsx](investment_capital_ledger.xlsx) | 台账的 Excel 版本，便于计算与维护，与 Markdown 台账同步更新 |

## 当前状态（截至 2026-10-22）

- **累计已投入本金**：**$5,027.24**
- **本月追加金额**：**$1,870.00**（**$528 + $1,342**）
- **最新状态**：已更新[投资本金记录与目标配比台账](investment_capital_ledger.md)

## 组合速览

| 资产模块 | 标的 | 目标权重 | 年化费率 |
| :--- | :---: | :---: | :---: |
| 美股全行业底座 | VOO | 30% | 0.03% |
| 美股科技成长卫星 | QQQM | 30% | 0.15% |
| 非美发达国家股票 | VEA / SCHF | 10% | 0.03% |
| 美国中期国债 | VGIT | 30% | 0.03% |
| **合计** | — | **100%** | **0.066%（加权）** |

## 维护约定

- **新增本金投入**：只在[台账](investment_capital_ledger.md)追加流水行并更新累计数，不改动方案与纪律。
- **调整配置或标的是结构性变更**：修改[方案](investing_principles_portfolio.md)，并同步核对[纪律](investment_discipline_rules.md)中的目标配比表述。
- **任何调仓操作**：以[纪律](investment_discipline_rules.md)的触发机制与 SOP 为唯一依据，不做主观波段操作。
