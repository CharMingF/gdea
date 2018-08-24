---
title: 《模型开发、评估、应用导则》批注：第三章（1）
tags: 1000天持续行动,GDEA
date:   2018-8-23
---
·[473]|1000天行动计划
**读书笔记**/热点追踪/论文研读/教程手册
	
![封面](http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1534259099598.png)

# 3 模型开发
    模型开发阶段的步骤及参考的建议。
本章为模型开发的讨论，汇总建议总结如下：
1. 监管类模型一旦被应用后就应该持续不断的评估。
2. 在模型开发阶段，在模型开发者和使用者之间的沟通是至关重要的。
3. 概念模型的每一个过程都应该被清晰的阐述（形式包括文字、函数表达式、图形等），其背后的科学机理也应有详细的文档。
4. 时间允许时，其他的模型或者假设应该被一并测试。
5. 尽早进行敏感性分析，并尽可能不断反复测试。
6. 模型的复杂度应该通过在竞争性目标之间恰当的权衡后进行优化处理。
7. 地点空间允许时，模型的参数应该直接通过大量样本点的测量确定。
8. 全部的输入数据应该在模型的质量控制计划标准可接受范围内。

> - Regulatory models should be continually evaluated as long as they are used.
> - Communication between model developers and model users is crucial during model development. 
> - Each element of the conceptual model should be clearly described (in words, functional expressions,diagrams, and graphs, as necessary), and the science behind each element should be clearly documented.
> - When possible, simple competing conceptual models/hypotheses should be tested.
> - Sensitivity analysis should be used early and often.
> - The optimal level of model complexity should be determined by making appropriate tradeoffs among competing objectives.
> - Where possible, model parameters should be characterized using direct measurements of sample populations.
> - All input data should meet data quality acceptance criteria in the QA project plan for modeling.

## 3.1 介绍
在明确目标和问题后，模型就开始开发了。例如，在部门定义了一个需要解决的环境问题，并确定了需要利用模型来提供有效的信息作为决策支撑（见2.2节）。模型开发包括以下内容：
1. 确认模型是否是解决该问题的真正的有效工具，何种类型的模型将是最有用的，是否已经有存在的模型能够来用于解决该问题。
2. 若不存在现成的模型，则需要开发恰当的模型，模型开发则是模型评估的重点。
3. 部门需要持续的跟踪评价现有模型或新的模型是否能够解决环境问题。
 
 >Model development begins after problem identification — i.e., after the Agency has identified an environmental problem it needs to address and has determined that models may provide useful input for the Agency decision making needed to address the problem (see Section 2.2). In this guidance, model development comprises the steps involved in (1) confirming whether a model is, in fact, a useful tool to address the problem; what type of model would be most useful; and whether an existing model can be used for this purpose; as well as (2) developing an appropriate model if one does not already exist. Model development sets the stage for model evaluation (covered in chapter 3), an ongoing process in which the Agency evaluates the appropriateness of the existing or new model to help address the environmental problem.

模型的开发的过程主要分为三步：
1. 确定模型所需要解决的环境问题，开发概念模型。
2. 评估和开发模型框架（开发数学模型）。
3. 参数化模型开发应用工具。
本节3.2，3.3和3.4分别详细描述了上述执行步骤。

模型开发是需要多方（模型开发、模型建模者、决策指定者（业主））协作完成。各方的视角和技能对于开发一个恰当、可信的模型十分的重要。

“分级”（graded approach）的方法应该贯穿整个模型开发过程。要依据使用的模型结果，结果的确信度及部门的资源来反复检查审视模型的应用范围，科学性及模型分析的复杂性。

>As described below, model development is a collaborative effort involving model developers, intended users, and decision makers (the “project team”). The perspective and skills of each group are important to develop a model that will provide an appropriate, credible, and defensible basis for addressing the environmental issue of concern.
A “graded approach” should be used throughout the model development process. This involves repeated examination of the scope, rigor, and complexity of the modeling analysis in light of the intended use of results, degree of confidence needed in the results and Agency resource constraints.

参考文献：
[1] Gaber N, Foley G, Pascual P, et al. Guidance on the development, evaluation, and application of environmental models[J]. Report, Council for Regulatory Environmental Modeling, 2009, 81.


![页尾](http://comieswater-1254012817.cossh.myqcloud.com/页尾识别new-2017-09-22.png)
微信公众号 | 水环境编Cheng长
网          站 | comieswater.com


![赞赏我](http://comieswater-1254012817.cossh.myqcloud.com/IMG_3077.JPG)

 2018-8-16

