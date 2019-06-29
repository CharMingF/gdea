---
title: 《模型开发、评估、应用导则》批注：第五章(3)
tags: 1000天持续行动,GDEA
date:   2019-2-12
---
·[503]|1000天行动计划
**读书笔记**/热点追踪/论文研读/教程手册
![封面](http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1534259099598.png)

	本节内容都比较少，这里一个关键点就是模型的后审查，一般来说我们往往随着项目的结束，也就彻底结束了，实际上随着后续数据的继续收集，对模型进行完善和继续升级也是非常重要的，毕竟模型是一种动态的工具，其并非一成不变的。
	
### 5.2.2 高效沟通

模型的过程应该与任何对模型结果有兴趣的人充分的沟通。全部的技术信息应该以决策支持者能够解释和理解的方式记录。Risk Characterization Handbook (EPA 2000d)通过以下几点来使得阐述更加清晰：

- 提供必要的细节时，尽可能简洁。
- 使用朴实的语言来使得建模者、政策制定者等能够充分理解。
- 避免专业术语和过度专业的用词，首次使用时应特别定义声明。
- 提供模型的方程。
- 使用清晰和恰当的方法去高效呈现其的数学关系。
- 清晰的描述量化的输出结果。
- 恰当的使用图表来呈现技术数据 (see Morgan and Henrion, 1990, for suggestions).。

模型项目的结论和其他的关键的要点应该清晰的陈述，具有挑战性的任务是如何将模型的细节过程和其限制描述给决策制定者。决策制定者应该对模型的框架充分的理解，对其模型结果存在潜在的假设限制条件充分的知悉。这些和QA计划实践中所要求的是一致的，均讨论了数据质量和其使用背景下的限制条件(EPA 2000e)。

>The modeling process should effectively communicate uncertainty to anyone interested in the model results. All technical information should be documented in a manner that decision makers and stakeholders can readily interpret and understand. Recommendations for improving clarity, adapted from the Risk Characterization Handbook (EPA 2000d), include the following:
Be as brief as possible while still providing all necessary details.
Use plain language that modelers, policy makers, and the informed lay person can understand. Avoid jargon and excessively technical language. Define specialized terms upon first use.
Provide the model equations.
Use clear and appropriate methods to efficiently display mathematical relationships.
Describe quantitative outputs clearly.
Use understandable tables and graphics to present technical data (see Morgan and Henrion, 1990, for suggestions).
 
>The conclusions and other key points of the modeling project should be clearly communicated. The challenge is to characterize these essentials for decision makers, while also providing them with more detailed information about the modeling process and its limitations. Decision makers should have sufficient insight into the model framework and its underlying assumptions to be able to apply model results appropriately. This is consistent with QA planning practices that assert that all technical reports must discuss the data quality and any limitations with respect to their intended use (EPA 2000e).

## 5.3 多模型应用
前面章节提到的内容，多模型有时候能够应用特定的决策支持需求；例如，多个空气质量模型，应用于管理时每个都有各自的优势和缺陷。在其他情况下，可能会使用替代模型（有工业界和学术界研究人员所开发）进而产生了替代的风险评估（例如工业界的CARES农药暴露模型）。去解决这个问题的一种方法是使用不同复杂度多个模型去模拟同样的问题（NRC 2007)。这就同时提供了不同模型的结果敏感性，以及模型的可靠性的分析。已有学者展现了使用多模型能够增加模型结果的可靠度（Manno et al. 2008)（见BOX 8-第四章）。但是，资源限制和时间限制可能不允许对全部可能的模型进行评估分析。

>As mentioned in earlier chapters, multiple models sometimes apply to a certain decision making need; for example, several air quality models, each with its own strengths and weaknesses, might be applied for regulatory purposes. In other situations, stakeholders may use alternative models (developed by industry and academic researchers) to produce alternative risk assessments (e.g., CARES pesticide exposure model developed by industry). One approach to address this issue is to use multiple models of varying complexities to simulate the same phenomena (NRC 2007). This may provide insight into how sensitive the results are to different modeling choices and how much trust to put in the results from any one model. Experience has shown that running multiple models can increase confidence in the model results (Manno et al. 2008) (see Box 8 in Chapter 4 for an example). However, resource limitations or regulatory time constraints may limit the capacity to fully evaluate all possible models.


## 5.4 模型后审查
由于时间复杂度，有限的时间，资源的缺乏和机理缺失等原因，技术决策经常会建立在不完全的信息条件下和基于不完美的模型。有时，及时模型开发者努力去追求科学合理性，但是科学是持续不断的向前发展的。考虑到这种现实条件，决策制定者应该对模型结果进行迭代，进而不断完善基于模型获取的决策。这个过程包括推动模进行后审查去评估和提高模型及其预测能力去进行更有价值的预测。验证过程（4.2.3.2节讨论）描述了模型与系统过去行为的吻合程度，而模型后审查则评估了其未来条件下的模型能力（Anderson 和Woessner 1992)。
>Due to time complexity, constraints, scarcity of resources, and/or lack of scientific understanding, technical decisions are often based on incomplete information and imperfect models. Further, even if model developers strive to use the best science available, scientific knowledge and understanding are continually advancing. Given this reality, decision makers should use model results in the context of an iterative, ever-improving process of continuous model refinement to demonstrate the accountability of model-based decisions. This process includes conducting model post-audits to assess and improve a model and its ability to provide valuable predictions for management decisions. Whereas corroboration (discussed in Section 4.2.3.2) demonstrates the degree to which a model corresponds to past system behavior, a model post-audit assesses its ability to model future conditions (Anderson and Woessner 1992).


模型的后评估是通过修补挑调整或者管理行为，观察确定是否实际的系统会按照模型预测的进行响应。全部模型的后审查由于时间资源限制未必可行，但是审查的目标是能够提升模型的框架和模型参数估计，在TMDL的项目综述中，NRC 推荐EPA通过选择“部分TMDL后执行任务去收集验证数据评估模型的预测误差"(NRC 2001)。后审查也应该评估模型的开发和使用效率(Manno et al. 2008)。
>A model post-audit involves monitoring the modeled system, after implementing a remedial or management action, to determine whether the actual system response concurs with that predicted by the model. Post-auditing of all models is not feasible due to resource constraints, but targeted audits of commonly used models may provide valuable information for improving model frameworks and/or model parameter estimates. In its review of the TMDL program, the NRC recommended that EPA implement this approach by selectively targeting “some post-implementation TMDL compliance monitoring for verification data collection to assess model prediction error” (NRC 2001). The post-audit should also evaluate how effectively the model development and use process engaged decision makers and other stakeholders (Manno et al. 2008).



参考文献：
[1] Gaber N, Foley G, Pascual P, et al. Guidance on the development, evaluation, and application of environmental models[J]. Report, Council for Regulatory Environmental Modeling, 2009, 81.


![页尾](http://comieswater-1254012817.cossh.myqcloud.com/页尾识别new-2017-09-22.png)
微信公众号 | 水环境编Cheng长
网          站 | comieswater.com


![赞赏我](http://comieswater-1254012817.cossh.myqcloud.com/IMG_3077.JPG)

2019-2-12

