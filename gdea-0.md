---
title: 《模型开发、评估、应用导则》批注导读（0）
tags: 1000天持续行动,DEA
date:   2018-8-13
---

# 开篇
·[467]|1000天行动计划

**读书笔记**/热点追踪/论文研读/教程手册
    
    最近，教程手册系列到水质模型这块内容了，这部分算是正式开始进入水质模型领域了，有点忐忑，正好发现了这本由美国EPA编写的一本导则《Guidance Document on the Development, Evaluation, and Application of Environmental Models》，里面涵盖了环境模型的定义、种类、建模流程及评估等等内容，觉得很不错，跟大家分享以下。点击**阅读原文**，即可下载原版。

![封面](http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1534259099598.png)
先看下官网介绍：
>Guidance Document on the Development, Evaluation, and Application of Environmental Models
This guidance developed in 2009 provides recommendations for the effective development, evaluation, and use of models in environmental decision making once an environmental issue has been identified. the recommendations are categorized into three sections: model development, model evaluation, and model application. 

本手册的名称已经体现了本书的核心内容，主要是集中模型的在三个方面，**模型开发与建模、模型评估、模型应用**。虽然其在2009年发布，但是我认为一些关键的东西还是适用的，所以决定对本书进行学习和批注。

按照之前的先看目录，对整本书的架构及基本内容做一个了解。不得不说，只看目录字面的意思很难把握具体内容，但是后续根据内容回头再完善修改吧。

![GDEA目录](http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1534261280177.png)

```mindmap!
1 介绍
	1.1 手册的目的及应用范围
	1.2 目标读者
	1.3 组织框架
	1.4 应用声明
2 环境决策支持工具-模型
	2.1 模型的重要性
	2.2 模型适用周期
3 模型开发
	3.1 介绍
	3.2 问题及概念模型开发
		3.2.1 目标
		3.2.2 模型需求的类型和范围
		3.2.3 数据标准
		3.2.4 模型的适用范围
		3.2.5 约束范围
		3.2.6 开发概念模型
	3.3 模型框架选择和开发
		3.3.1 模型复杂度
		3.3.2 模型校准
	3.4 应用工具开发
		3.4.1 输入数据
		3.4.2 模型验证
4 模型评估
	4.1 介绍
	4.2 模型评估
		4.2.1 同行评议
		4.2.2 质量保证计划和数据质量评估
		4.2.3 证实、敏感性分析和不确定分析
			4.2.3.1 不确定的类型
			4.2.3.2 模型进一步证实
			4.2.3.3 敏感性和不确定分析
	4.3 专有模型评估
	4.4 经验中学习
	4.5 模型评估文档化
	4.6 模型评估结论
5 模型应用
	5.1 介绍
	5.2 透明度
		5.2.1 文档
		5.2.2 有效沟通
	5.3 多模型联用
	5.4 模型后审查
附录
A:名词注释
B:环境模型类别
C:质量保证补充材料
D:模型评估的实践
```

可以看出，整个对于模型应用的全流程有了基本的叙述，内容还是比较全面的。

美国EPA经常依赖于环境模型来完成其的使命：保护人类的健康和守护自然环境。在本守则中，模型被定义为：**通过对现实的简化，来获得对自然界的物理、生物、经济及社会属性的深入了解和分析**。
>  “simplification of reality that is constructed to gain insights into select attributes of a particular physical, biological, economic, or social system.

## 小结
本节为导则的开篇，简要介绍了其导则的主要框架和内容。

# 前言

·[468]|1000天行动计划

**读书笔记**/热点追踪/论文研读/教程手册
    

```
本节为前言部分，主要介绍模型开发、评估及应用的主要内容。
```

![封面](http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1534259099598.png)

> Model development can be viewed as a process with three main steps: (a) specify the environmental
> problem (or set of issues) the model is intended to address and develop the conceptual model, (b)
> evaluate or develop the model framework (develop the mathematical model), and (c) parameterize the
> model to develop the application tool. 

模型开发:
模型开发主要由三个步骤构成：

- a）确定利用模型解决的环境问题，并开发概念模型。
- b）评估和开发模型框架（开发相应的数学模型）；
- c）参数化模型，开发相应的应用工具。

> Model evaluation is the process for generating information over the life cycle of the project that helps
> determine whether a model and its analytical results are of sufficient quality to serve as the basis for a
> decision. Model quality is an attribute that is meaningful only within the context of a specific model
> application. In simple terms, model evaluation provides information to help answer the following
> questions: (a) How have the principles of sound science been addressed during model development? (b)
> How is the choice of model supported by the quantity and quality of available data? (c) How closely does
> the model approximate the real system of interest? (d) How well does the model perform the specified
> task while meeting the objectives set by quality assurance project planning? 

模型评估:
贯穿于整个项目的周期中，反复的分析、判定模型和模型结果是否能够支撑决策。模型的质量是在特定的模型应用场景下的评估结果。简单来说，模型评估是为了回答下面的问题：

- a）在模型开发过程中是否具备了科学上的可靠性？
- b）如何选择支撑模型的水量和水质数据？
- c）模型结果和真实世界的吻合程度？
- d）满足质量保证的条件下，模型应用的表现如何？

> Model application (i.e., model-based decision making) is strengthened when the science underlying the
> model is transparent. The elements of transparency emphasized in this guidance are (a) comprehensive
> documentation of all aspects of a modeling project (suggested as a list of elements relevant to any
> modeling project) and (b) effective communication between modelers, analysts, and decision makers.
> This approach ensures that there is a clear rationale for using a model for a specific regulatory
> application. 

模型应用:
如果模型背后的机理够透明，那么模型的应用（如决策支持）将更有说服力。透明在本导主要强调的有以下几种：
a）模型项目的各个方面有全面的技术文档说明（建议任何与模型项目相关的内容都以列表形式给出）。
b）在建模者、分析者、业主之间有着高效沟通，这确保了使用模型支撑管理决策时有清晰的本质原理。

> This guidance recommends best practices to help determine when a model, despite its uncertainties, can
> be appropriately used to inform a decision. Specifically, it recommends that model developers and users:
> (a) subject their model to credible, objective peer review; (b) assess the quality of the data they use; (c)
> corroborate their model by evaluating the degree to which it corresponds to the system being modeled;
> and (d) perform sensitivity and uncertainty analyses. Sensitivity analysis evaluates the effect of changes
> in input values or assumptions on a model's results. Uncertainty analysis investigates the effects of lack
> of knowledge and other potential sources of error in the model (e.g., the “uncertainty” associated with
> model parameter values). When conducted in combination, sensitivity and uncertainty analysis allow
> model users to be more informed about the confidence that can be placed in model results. A model’s
> quality to support a decision becomes better known when information is available to assess these factors. 

本导则主要用于帮助决定不确定性条件下的模型决策。特别的，建议模型开发者和用户：

- a）通过可靠的、客观的同行评议。
- b）确定使用数据的可靠性。
- c）通过评估对应的系统被模拟的程度来证实模型的可靠性。
- d）进行敏感性和不确定性分析。敏感性分析用于评估输入值的改变对模型结果的影响。不确定性分析则用于评估模型没有考虑到的内容及其他潜在的误差所带来的影响（例如模型参数不确定性的影响）。结合上述分析后，允许模型使用者对待模型的结果更有信心。
  在满足上述分析后，支持决策的模型质量能够变的更好。

---

原文链接：https://www.epa.gov/measurements-modeling/guidance-document-development-evaluation-and-application-environmental-models

参考文献：
[1] Gaber N, Foley G, Pascual P, et al. Guidance on the development, evaluation, and application of environmental models[J]. Report, Council for Regulatory Environmental Modeling, 2009, 81.


![页尾](http://comieswater-1254012817.cossh.myqcloud.com/页尾识别new-2017-09-22.png)
微信公众号 | 水环境编Cheng长
网          站 | comieswater.com


![赞赏我](http://comieswater-1254012817.cossh.myqcloud.com/IMG_3077.JPG)

 2018-8-13