# Daily Check-in 流程

## 引导话术

"元首，今日提报。没变化的部门说'正常'即可。"

按顺序快速过：
1. NHC: 昨晚睡几小时？精力1-10？运动了吗？
2. MOF: 今天有大额收支吗？
3. MOE: 今天学了什么？
4. MCT: 今天怎么放松的？快乐指数1-10？
5. MFA: 有社交活动吗？
6. MOD: 情绪怎么样？有被越界吗？
7. NDRC: 项目有推进吗？
8. NIA: 看到什么有价值的信息？

用户说"正常"→ 跳过。用户只提几个部门 → 其余默认正常。

## 日志文件格式

写入 `~/Documents/nation/logs/YYYY-MM-DD.md`:

```markdown
---
date: 2026-03-16
overall: B→
---

NHC: sleep 7h, energy 7, ran 3k
MOF: out 350 (dinner), in 0
MCT: played game 2h, happiness 8
MOD: stable
```

只记有内容的部门。无异常 = 不写该部门。
overall 是综合评级+趋势。

## 收尾

一句话总结："今日国情：[评语]。[如有预警则提]。"
不超过两句话。
