---
layout: default
title: "Horizon Summary: 2026-10-17 (ZH)"
date: 2026-10-17
lang: zh
---

> 从 17 条内容中筛选出 2 条重要资讯。

---

**科技新闻**
1. [从联想记忆出发，自己推导 Transformer](#item-tech-news-1) ⭐️ 8.0/10
2. [Claude 追溯 NIST 椭圆曲线种子至 lrand48 时间戳](#item-tech-news-2) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [从联想记忆出发，自己推导 Transformer](https://alexwang.ai/posts/associative-memory/) ⭐️ 8.0/10

一篇发布在 alexwang.ai、并在 Hacker News 引发讨论的技术长文，尝试用联想记忆（associative memory）的视角解释 Transformer，让读者从记忆检索的直觉推导出这一架构。文章是教学性梳理，并非新模型、版本或实验结果发布；其价值在于提供一条不同于常规课程的教学路径。Hacker News 的讨论围绕如何把这一框架落到具体例子，以及文章对“你”这一前提的界定展开。

hackernews · speckx · 10月16日 19:01 · [社区讨论](https://news.ycombinator.com/item?id=50122878)

**「背景：什么是联想记忆」** 联想记忆（associative memory）指按相似度而非精确地址检索的记忆存储：用某个键查询时，召回与之对应的值，最基础的实现是把记忆以外积形式累加。Alex Wang 的文章正是从这一概念出发，把线性映射、MLP 和自注意力都视为联想记忆，再一步步推导出注意力公式，而不是让读者直接背下论文里的定义。文章用干扰信号比来定义容量：以 64 维键为例，线性层大约能存 64 条记忆，MLP 约 2,700 条，自注意力则可超过一百万条。

**「社区讨论」** 有读者提出用“50 个州首府”作为具体例子，追问如何从最基础的 tokenization 开始，把联想记忆框架落到实处；另一条评论则认为文章应先说明什么才算一个“你”。作者在讨论中贴出了自己的简短摘要，也有读者表示希望更早接触到这种从记忆角度讲解 Transformer 的视角。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://alexwang.ai/posts/associative-memory/">You could have invented transformers from memory | Alex Wang</a></li>
<li><a href="https://veriwire.news/daily-ai-news/you-could-have-invented-transformers-from-memory-239322/">You could have invented transformers from memory — Veriwire</a></li>
<li><a href="https://elsolitario.org/en/2026/10/17/associative-memory-what-it-is-and-its-link-to-attention/">Associative Memory: What It Is and How It Works</a></li>

</ul>
</details>

**标签**: `#transformers`, `#associative-memory`, `#machine-learning`, `#technical-explainer`, `#neural-networks`

---

<a id="item-tech-news-2"></a>
### [Claude 追溯 NIST 椭圆曲线种子至 lrand48 时间戳](https://www.anthropic.com/research/ecdsa-curve-origins) ⭐️ 8.0/10

密码学研究人员和审计者得到一个据称由 Claude 完成的新解释：NIST P-192、P-224、P-256、P-384 和 P-521 的种子来自 C 库 lrand48 的输出，并以 Unix 时间戳为种子，而不是由哈希算法生成。Anthropic 的研究页面称这一追溯在不到半小时内完成，但第五个二进制种子 B-163 仍未获解释。该结果只说明种子的产生方式，不能证明曲线参数的选择过程，因为生成后丢弃的候选无法被观察。

hackernews · ahlCVA · 10月16日 18:55 · [社区讨论](https://news.ycombinator.com/item?id=50122800)

**「背景」** NIST 在 P-192、P-224、P-256、P-384、P-521 等标准椭圆曲线参数中同时公布了一串“种子”值，其用途是让外界能够验证曲线参数并非随意挑选；但种子究竟如何生成，长期没有公开说明。由于缺乏这一环，外界一直存在曲线可能被刻意构造成带有隐藏性质的猜测，而 Anthropic 的文章称 Claude 用格约简从被截断的生成器状态中反解出 1997 至 1998 年的 Unix 时间戳，从而给出了这些种子的来源。

**「影响」** 对使用这些 NIST 曲线的组织，这项发现没有提供更换曲线或修改实现的理由；它的直接后果是审计解释发生变化：即使种子来源被还原，也无法排除通过搜索时间戳筛选参数的可能性，因此不能据此判断曲线是否存在后门或是否安全。

**「社区讨论」** 评论者 fidotron 强调，确认生成方法不等于确认参数选择，尤其是候选在数月间生成并丢弃后无法审计；teddyh 则提出 B-163 无法解释可能只是发布时抄错一位数字。多条评论以玩笑口吻称，这一结果打击了长期流传的 NIST 曲线阴谋论，但这些只是社区反应，并非独立验证。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/research/ecdsa-curve-origins">Claude reveals ECDSA curve origins \ Anthropic</a></li>
<li><a href="https://aiweekly.co/alerts/anthropic-claude-traced-nist-ecdsa-seeds-to-unix-timestamps">Anthropic: Claude Traced NIST ECDSA Seeds to Unix Timestamps</a></li>

</ul>
</details>

**标签**: `#cryptography`, `#elliptic-curves`, `#NIST`, `#AI-assisted-research`, `#random-number-generation`

---