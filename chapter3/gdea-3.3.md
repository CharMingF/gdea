---
title: 《模型开发、评估、应用导则》批注：第三章(4)
tags: 1000天持续行动,GDEA
date:   2018-8-29
---
·[478]|1000天行动计划
**读书笔记**/热点追踪/论文研读/教程手册
![封面](http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1534259099598.png)

# 3.3 模型框架的选择及开发
    本节为概念模型的选择及开发的相关问题。

一旦团队已经明确了要解决的问题及解决问题所需要的模型后，就需要去定义或开发满足需求的模型框架架构了。模型的框架架构是系统、目标或者所关注问题的过程背后的概念、过程及行为表现，通过规范的数学方程描述出来，一般情况下最后还需要用计算机语言来编程。
>Once the team has specified the problem and type of model needed to address the problem, the next step is to identify or develop a model framework that meets those specifications. A model framework is a formal mathematical specification of the concepts, procedures, and behaviors underlying the system, object, or process relevant to the problem of interest, usually translated into computer software.

对于解决一般的环境问题的机理模型而言，往往不仅仅只有一个模型框架。很多公开的已经存在的模型框架能被用于解决环境评估。许多机构，包括EPA在内，不断的开发和维护了很多模型框架。理想状况下，满足工程需求的模型框架有若干个，那么工程团队可以去选择最好、最适合的模型来解决问题。如何评估现有的模型框架将在后文进行描述。

偶尔的情况下，现有的模型均不太适合，那么EPA则会开发新的模型框架或者修改、增强现有框架以满足需要。

>For mechanistic modeling of common environmental problems, one or more suitable model frameworks may exist. Many existing model frameworks in the public domain can be used in environmental assessments. Several institutions, including EPA, develop and maintain these model frameworks on an ongoing basis. Ideally, more than one model framework will meet the project needs, and the project team can select the best model for the specified problem. Questions to consider when evaluating existing model frameworks are described below.
Sometimes no model frameworks are appropriate to the task, and EPA will develop a new model framework or modify an existing framework to include the additional capabilities needed to address the project needs.

当然，很多评估工作需要耦合多个模型框架，如一个模型的输出被用作另一个的输入（典型的如流域模型计算入湖负荷成为水体模型的边界条件）。如空气质量模型经常会与气象、排放及空气化学输运模型耦合链接。在应用耦合模型时，工程团队在模型开发及评估过程中，不仅仅评估模型的每个单独的部分，同时也要综合评估其整合之后的效果。

>Sometimes no model frameworks are appropriate to the task, and EPA will develop a new model framework or modify an existing framework to include the additional capabilities needed to address the project needs.
Some assessments require linking multiple model frameworks, such that the output from one model is used as input data to another model. For example, air quality modeling often links meteorological, emissions, and air chemistry/transport models. When employing linked models, the project team should evaluate each component model, as well as the full system of integrated models, at each stage of the model development and evaluation process.

无论哪种情况下，选择模型的过程及原因都应该被清晰的描述在文档之中。对于解决问题需要开发或者定义的模型框架，工程团队需要考虑以下问题：
1. 潜在的假设是否科学合理（包括同行评议的理论及方程）。
2. 对于所解决的问题而言，模型的复杂度是否合适？
3. 水量和水质数据是否能够很好的支撑所选择的模型？
4. 模型结构能否反映的概念模型中描述的全部输入？
5. 模型代码能否被编程？如何可以，如何去证实？

这里推荐在评估的过程中应用迭代（Hilborn and Mangel 1997）方法进行科学假说原则测试（Platt 1964）。对于团队评估多个模型框架而言，统计对比待选模型的观测值、范围、实验数据（第四章）将可能有用。
> In all cases, the documentation for the selected model should clearly state why and how the model can and will be used.
As potential model frameworks are identified or developed for addressing the problem, the project team will need to consider several issues, including:
Does sound science (including peer-reviewed theory and equations) support the underlying hypothesis?
	- Is the model’s complexity appropriate for the problem at hand?
	- Do the quality and quantity of data support the choice of model?
	- Does the model structure reflect all the relevant inputs described in the conceptual model?
	- Has the model code been developed? If so, has it been verified?
It is recommended that the evaluation process apply the principles of scientific hypothesis testing (Platt 1964) using an iterative approach (Hilborn and Mangel 1997). If the team is evaluating multiple model frameworks, it may be useful to statistically compare the performance of these competing models with observational, field, or laboratory data (Chapter 4).

模型选择案例（略）。

参考文献：
[1] Gaber N, Foley G, Pascual P, et al. Guidance on the development, evaluation, and application of environmental models[J]. Report, Council for Regulatory Environmental Modeling, 2009, 81.


![页尾](http://comieswater-1254012817.cossh.myqcloud.com/页尾识别new-2017-09-22.png)
微信公众号 | 水环境编Cheng长
网          站 | comieswater.com


![赞赏我](http://comieswater-1254012817.cossh.myqcloud.com/IMG_3077.JPG)

 2018-8-16

