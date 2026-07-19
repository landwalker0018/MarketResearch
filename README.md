# MarketResearch

面向投资研究的市场分析项目，用于沉淀研究问题、数据来源、分析过程和最终结论。

## 项目结构

```text
docs/         研究计划、方法论和阶段性发现
data/         原始数据说明与可复现的处理结果
notebooks/    探索性分析笔记
src/          可复用的数据处理和分析代码
reports/      图表及最终报告
references/   文献、网页和外部资料索引
tests/        数据处理与分析代码测试
```

## 开始研究

1. 在 `docs/research-plan.md` 定义研究问题、范围和交付物。
2. 在 `data/README.md` 登记数据来源、授权方式和更新日期。
3. 将不可公开的原始数据保留在 `data/raw/`，该目录默认不纳入 Git。
4. 在独立分支中完成研究，通过 Pull Request 合并到 `main`。
5. 将可复核的结论记录在 `docs/findings/`，最终报告放在 `reports/final/`。

## 分支与提交约定

- 研究任务：`research/<topic>`
- 数据处理：`data/<topic>`
- 项目维护：`chore/<topic>`
- 提交信息示例：`research: add semiconductor market overview`

## 数据安全

不要提交账号密码、API 密钥、个人信息、付费数据库原始文件或未经授权传播的材料。提交前请运行 `git status` 并检查变更范围。
