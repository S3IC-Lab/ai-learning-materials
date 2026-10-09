# S3IC Lab 阅读导航

面向希望学习深度学习、大语言模型、AI 安全与机器学习理论的同学。根据自己的基础和当前问题选择入口，课程用于建立整体认识，教材与论文用于深入阅读和按需查阅。

## 从哪里开始

- **刚接触深度学习**：从吴恩达课程开始，配合 Dive into Deep Learning 查阅概念。
- **已经有神经网络基础**：进入李宏毅生成式 AI 课程，结合 Transformer 图解和 Hugging Face 教程阅读。
- **对 AI 安全感兴趣**：先了解问题全貌，再选择模型与数据安全、应用安全或对齐方向。
- **希望读懂理论论文**：从机器学习理论入手，遇到数学和优化问题时查阅对应教材。

学习阶段请独立理解和编写代码，不要使用 AI 代写代码。

## 深度学习与大语言模型

以下课程和教程可以结合自己的基础与阅读习惯选择：

- **[吴恩达《深度学习》课程](https://www.bilibili.com/video/BV16r4y1Y7jv/)**：适合初学者系统建立深度学习基础，理解神经网络、反向传播、模型训练与常见架构。基础尚不熟悉时，建议从这里开始。
- **[李宏毅生成式 AI 课程](https://www.bilibili.com/video/BV1SgK7zcE3Y/)**：适合通过中文视频了解生成式 AI 与大语言模型，可以作为这一方向的主要学习入口。
- **[The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)**：通过图解介绍原始 Transformer，适合配合课程阅读。遇到 Self-Attention、Query / Key / Value 等概念时，可以借助图示理解信息如何在模型中流动。
- **[Hugging Face LLM Course](https://huggingface.co/learn/llm-course/en/chapter1/1)**：适合通过结构化文字教程理解大模型及其常见组件。建议先阅读 Transformer 与 Tokenizer，再按需要查阅数据处理、微调等内容。

刚入门可以先看吴恩达，再进入李宏毅的课程；图解和 Hugging Face 教程可随课程穿插阅读，无需重复通读全部内容。B站合集可按主题选看，留意课程年份与章节顺序。

### 配合课程阅读

**[Dive into Deep Learning](https://d2l.ai/)** 将数学解释、模型原理和代码示例放在一起，适合作为深度学习入门阶段的主要参考书。可以先读线性回归、多层感知机与训练基础，再按课程进度查阅卷积网络、注意力机制等章节。

希望系统了解大模型，可阅读 **[《大语言模型》— RUC AI Box](materials/LLM/%E5%A4%A7%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%20RUC%20AI%20Box.pdf)**。先建立整体认识，再围绕当前关注的模型训练、能力或应用问题深入查阅。

希望拓展研究视野，可阅读 **[On the Opportunities and Risks of Foundation Models](materials/LLM/2108.07258v3.pdf)**（[论文页面](https://arxiv.org/abs/2108.07258)）。从摘要和引言开始，再按兴趣选择技术、应用与风险相关部分；阅读具体技术时，可结合后续论文了解进展。

## AI 安全：从问题全貌到研究方向

先阅读 **[Introduction to AI Safety, Ethics, and Society](https://www.aisafetybook.com/textbook)**，了解 AI 风险、安全、伦理与社会影响，再结合 **[《大语言模型安全与隐私保护》](materials/LLM/%E5%A4%A7%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E5%AE%89%E5%85%A8%E4%B8%8E%E9%9A%90%E7%A7%81%E4%BF%9D%E6%8A%A4V20.pdf)** 聚焦大模型场景。

可以按兴趣选择一个方向深入：

- **模型与数据安全**：关注对抗样本、数据投毒、后门与隐私泄露，理解风险来自哪些数据、训练过程或模型行为。
- **大模型应用安全**：关注越狱、提示注入与工具调用风险，理解模型接入外部数据和工具后会出现哪些问题。
- **对齐与可信性**：关注模型行为是否符合预期，以及幻觉、可靠性和安全评测。

应用安全方向可以进一步阅读 **[OWASP Top 10 for Large Language Model Applications](https://genai.owasp.org/llm-top-10/)**。从熟悉的聊天助手、RAG 或工具调用场景出发，阅读相关风险的说明、案例与缓解措施，理解风险出现在哪个环节。

阅读安全方法时，重点关注它保护什么、假设攻击者具备哪些能力、如何评价效果，以及适用于哪些场景。

## 机器学习理论：理解模型为什么能够泛化

从 **[Understanding Machine Learning: From Theory to Algorithms](materials/Understanding%20Machine%20Learning%20%282014%2C%20Cambridge%20University%20Press%29%20-%20libgen.li.pdf)** 入手，理解学习问题的数学表述，以及样本数量、模型复杂度与泛化之间的关系。

建议先读基本定义和学习框架，再进入感兴趣的算法与理论章节。阅读定理时，先看它回答什么问题、需要哪些条件，再看证明如何展开。

**[Lecture Notes: Mathematical Analysis of Machine Learning Algorithms](materials/Lecture%20Notes-%20Mathematical%20Analysis%20of%20Machine%20Learning%20Algorithms.pdf)** 可作为补充阅读入口，结合教材和论文涉及的主题查阅。另可按需查阅 [MLbookSol.pdf](materials/MLbookSol.pdf)。

## 优化：理解训练算法与收敛分析

已经了解梯度下降后，可以阅读 **[Optimization Methods for Large-Scale Machine Learning](materials/Optimization%20Methods%20for%20Large-Scale%20Machine%20Learning.pdf)**，理解大规模训练中不同优化方法的计算成本与适用条件。先看问题设置和方法概览，再围绕感兴趣的算法深入阅读。

需要进一步理解算法复杂度和收敛证明时，阅读 Bubeck 的 **[Convex Optimization: Algorithms and Complexity](materials/convex_optimization_sbubeck.pdf)**。先熟悉凸性与基本优化方法，再看收敛分析，留意光滑性、强凸性等条件如何影响结论。

比较优化方法时，可以同时关注每步计算量、存储需求和收敛条件。

## 数学基础：遇到问题时从这里查

**[Mathematics for Machine Learning](https://mml-book.github.io/)** 适合作为数学查阅的第一站，覆盖线性代数、矩阵分解、向量微积分、概率与优化，并通过机器学习问题说明这些工具的用途。

- 看不懂矩阵表达式时，查阅线性代数与矩阵分解。
- 遇到梯度推导时，查阅向量微积分。
- 遇到概率模型时，查阅概率与分布。

需要进一步理解分析中的定义与证明，可以阅读 Rudin 的 **[Principles of Mathematical Analysis](materials/Principles%20of%20mathematical%20analysis%20%281976%2C%20McGraw-Hill%29%20-%20libgen.pdf)**。适合查阅极限、连续性、微分、积分与函数序列等主题，重点关注定理条件及其使用方式。

涉及测度、Lebesgue 积分、可积性或函数空间时，可以查阅 Folland 的 **[Real Analysis: Modern Techniques and Their Applications](materials/Real%20Analysis_%20Modern%20Techniques%20and%20Their%20Applications%2C%202nd%20edition%20%281999%29%20-%20libgen.pdf)**。建议具备数学分析基础后阅读，尤其留意收敛条件，以及极限、积分等运算可以交换的前提。

先定位论文中不理解的概念，查阅相应定义和定理，再回到原文理解它们在论证中的作用。
