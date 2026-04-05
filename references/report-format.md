# 报告格式

## 周报 (≤150字)

文件：`~/Documents/nation/weekly/YYYY-WNN.md`

```markdown
---
week: 2026-W12
range: 03-10 ~ 03-16
overall: B+
---

# W12 国情咨文

## 评级
| 部门 | 级 | 趋势 | 要点 |
|------|----|------|------|
| NDRC | A | → | Q1项目on track |
| MOF | B | ↓ | 超支15%，聚餐多 |
| MOE | A | ↑ | 读完《xx》，输出2篇笔记 |
| NHC | B | → | 平均sleep 6.5h，运动3次 |
| MFA | A | → | 见了2个key contact |
| MCT | A | ↑ | 周末徒步，happiness avg 8 |
| MOD | A | → | stable，无incident |
| NIA | B | → | 抓到1条A级行业信号 |

亮点：[一条]
预警：[一条]
下周重点：[一条]
```

写完周报后 → 该周的 daily logs 可归档（移到 logs/archive/）。

## 月报 (≤200字)

文件：`~/Documents/nation/monthly/YYYY-MM.md`

```markdown
---
month: 2026-03
overall: B+
---

# 三月宏观报告

总评：[3句话概括]

## 部门月度评级
[同周报表格格式，汇总月度数据]

## 趋势
- 上升：[部门]
- 下降：[部门]
- 稳定：[部门]

## 跨部门联动
[发现的关联，如"NHC下降导致MOD波动"]

## 下月战略建议
[1-2条]
```

写完月报 → 周报可归档。

## 评级汇总规则

取该周期内各部门日志的加权平均：
- 有明确数值的（sleep, energy, happiness）→ 按数值评
- 无数值的（MOD: stable）→ 按出现的关键词评
- 部门无记录 → 标注"无数据"，不编造
