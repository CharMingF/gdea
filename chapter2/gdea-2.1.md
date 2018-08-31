---
title: 《模型开发、评估、应用导则》批注：第二章（1）
tags: 1000天持续行动,GDEA
date:   2018-8-21
---
·[471]|1000天行动计划
**读书笔记**/热点追踪/论文研读/教程手册
![封面](http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1534259099598.png)

# 2 模型为环境决策支持
## 2.1 为什么模型很重要？

	在当前，国内对环境模型的看法已经偏向极端，要么贬低到什么用都没有，不相信模型，认为模型就是玩具，并没有任何实际的作用，看不起玩模型的人，认为不过是自己玩玩数学游戏而已，对模型的结果基本上不屑一顾。另一种极端就是过度夸大模型价值，模型的结果就一定正确，有的甚至认为模型能够解决一切问题。当然，由于大多数模型使用者过去不太踏实的夸张做法，使得现在用户普遍对模型的认识为前者，相对悲观。实际上，从本导则中EPA对模型的态度，我们有启发意义，EPA合理的认可模型的价值，同时通过一些评估模型结果的方法，来让模型更有说服力。

前面我们有对模型进行了定义：“通过对现实的简化，来获得对自然界的物理、生物、经济及社会属性的深入了解和分析”。模型开发者设定边界条件，决定模拟系统的哪些方面，哪些过程是重要的，这些过程怎样通过数学模型高概化表达出来，最终通过什么计算方法来求解运算。也就是说，模型并不能完全的“复刻”复杂的天然存在的自然环境系统，其需要假设并简化才能进行建模。但是，虽然有这些限制，在面对环境领域中的各种各样的亟需解决的问题，模型仍然有非常重要的作用。
> This guidance defines a model as “a simplification of reality that is constructed to gain insights into
select attributes of a particular physical, biological, economic, or social system.” A model developer sets boundary conditions and determines which aspects of the system are to be modeled, which processes are important, how these processes may be represented mathematically, and what computational methods to use in implementing the mathematics. Thus, models are based on simplifying assumptions and cannot completely replicate the complexity inherent in environmental systems. Despite these limitations, models are essential for a variety of purposes in the environmental field. 

目前，模型能够应用的场景主要可以分为：
- 探寻过去。诊断（如影响评价，会导致什么？）和检查分析原因，分析已经发生的事件为何会发生？
- 预测未来。未来结果和未来可能发生的事情。
无论是应用于现状条件下亦或者未来的规划远景条件下，模型再环境管理中均能够发挥重要的作用。对于分析环境和人类的健康问题，还有太过于复杂并不能单单通过经验方法来分析的系统，模型都是重要有力的工具。

> - To diagnose (i.e., assess what happened) and examine causes and precursor conditions (i.e., why it
happened) of events that have taken place.
>- To forecast outcomes and future events (i.e., what will happen).
>Whether applied to current conditions or envisioned future circumstances, models play an important role in environmental management. They are an important tool to analyze environmental and human health questions and characterize systems that are too complex to be addressed solely through empirical means. 

模型可以从不同角度进行分类（附录B），例如基于概念基础和数学求解方法，或者其能够被应用于求解的问题角度，以及应用的区域范围，操作复杂度和分辨率等级等。基于目的和应用，管理决策类模型可以分为三类（CREM2001)：
- 政策分析：政策分析类模型的结果能够影响到国家的管理准则。这些模型用于设置大型、多年类项目的管理措施，例如减少Great湖的酸雨和硫排放的措施。这点类似于我国的很多环境管理条例及办法。
- 国家监管决策：在全面的政策规章建立后，模型能够去用于建立管理决策。例如，利用模型来协助指定联邦特殊农药管理和构建国家污染物排放标准或许可。
- 实施方案。政策和监管决策已经指定后，模型能够进一步用于指导实施方案，模型的运用受为法院法令计划或本地行动的需求而驱动。

>Models can be classified in various ways (see Appendix B) — for example, based on their conceptual
basis and mathematical solution, the purpose for which they were developed and are applied, the domain
or discipline to which they apply, and the level of resolution and complexity at which they operate. Three
categories of regulatory models have been identified based on their purpose or application (CREM 2001):
-	 Policy analysis. The results of policy analysis models affect national policy decisions. These models are used to set policy for large, multi-year programs or concepts — for example national policy on acid rain and phosphorus reduction in the Great Lakes.
-	 National regulatory decision making. These models inform national regulatory decision making after overall policy has been established. Examples include the use of a model to assist in determining federal regulation of a specific pesticide or to aid in establishing national effluent limitations.
-	 Implementation applications. These models are used in situations where policies and regulations have already been made. Their development and use may be driven by court-ordered schedules and the need for local action. 

环境模型为需要考虑多个互相竞争性目标的环境决策制定者来说是重要的信息源。很多EPA的项目的决策都是基于环境模型的结果决定的。在EPA应用过的包括：
- 模型被用于去模拟许多不同的过程，包括自然（化学、物理和生物）系统，经济现象，决策过程。
- 包括不同类型的模型，如经济、行为、物理、工程设计、健康、生态和输运模型。
- 模型所模拟的对象地理尺度范围从国家尺度到个别区域，不同尺度案例如：
	- 国家空气质量模型用于决策污染物排放标准。
	- 流域水质模型用于决定点源排放总量。
	- 区域人类健康风险模型用于决定废水处理措施的标准。
> Environmental models are one source of information for Agency decision makers who need to consider many competing objectives. A number of EPA programs make decisions based on information from environmental modeling applications. Within the Agency:
	- Models are used to simulate many different processes, including natural (chemical, physical, and
	biological) systems, economic phenomena, and decision processes.
	- Many types of models are employed, including economic, behavioral, physical, engineering design,
	health, ecological, and fate/transport models. 
	- The geographic scale of the problems addressed by a model can vary from national scale to an
individual site. Examples of different scales include:
		-  National air quality models used in decisions about emission requirements.
		-  Watershed-scale water quality models used in decisions about permit limits for point sources.
		-  Site-scale human health risk models used in decisions about hazardous waste cleanup
		measures. 

当然，在政策管理之外，模型也有用武之地。例如，由于模型包含了关于系统机制的清晰的数学变量，其可以作为探索新的科学问题的研究工具，也可作为简化或精细化已存在的科学模式和软件的筛选工具（SAB 1993a,1989)。模型可以是帮助用户研究生态系统、设计领域研究、解译数据、生成结果的工具。

>Models also have useful applications outside the regulatory context. For example, because models
include explicit mathematical statements about system mechanics, they serve as research tools for
exploring new scientific issues and screening tools for simplifying and/or refining existing scientific
paradigms or software (SAB 1993a, 1989). Models can also help users study the behavior of ecological
systems, design field studies, interpret data, and generalize results. 

```
Box 1: Examples of EPA Web Sites Containing Model Descriptions for Individual Programs
National Environmental Research Laboratory Models: http://www.epa.gov/nerl/topics/models.html
Atmospheric Sciences Modeling Division: http://www.epa.gov/asmdnerl/index.html
Office of Water’s Water Quality Modeling: http://www.epa.gov/waterscience/wqm
Center for Subsurface Modeling Support: http://www.epa.gov/ada/csmos.html
National Center for Computational Toxicology: http://www.epa.gov/ncct
Support Center for Regulatory Atmospheric Modeling: http://www.epa.gov/scram001/aqmindex.htm 
```

参考文献：
[1] Gaber N, Foley G, Pascual P, et al. Guidance on the development, evaluation, and application of environmental models[J]. Report, Council for Regulatory Environmental Modeling, 2009, 81.


![页尾](http://comieswater-1254012817.cossh.myqcloud.com/页尾识别new-2017-09-22.png)
微信公众号 | 水环境编Cheng长
网          站 | comieswater.com


![赞赏我](http://comieswater-1254012817.cossh.myqcloud.com/IMG_3077.JPG)

 2018-8-16

