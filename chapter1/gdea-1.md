---
title: 《模型开发、评估、应用导则》批注：第一章(1)
tags: 1000天持续行动,GDEA
date:   2018-8-16
---

# 1 导则介绍
·[469]|1000天行动计划

**读书笔记**/热点追踪/论文研读/教程手册
    
    本节为导则第一章，主要介绍了导则的适用范围及主要内容。

![封面](http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1534259099598.png)
## 1.1 目的和适用范围
EPA为了完成其使命--保护人类健康和守护大自然环境（人类赖以生存的空气、水、土地），采用一系列模型来进行决策支持。模型的类型涉及大气和室内空气模型、地下水和地表水模型、多介质模型、化学平衡模型、暴露模型、有毒物模型、风险评估模型以及经济模型。这些模型可能涉及不同类型的数据，诸如自然地理、经济、社会经济等等，模型复杂度也不尽相同。

国家研究委员会（NRC)的一份报告《环境管理决策模型》指出，对于管理决策而言模型十分关键，因为环境控制与环境质量的时间及空间尺度，使得并不能完全通过观测的方法手段来全面的了解经济活动和环境质量之间的关系（NRC2007)。模型则可以通过长期的历史数据来帮助解释科学现象，并在经验观测被限制及不可用的情形下，预测可能出现的结果及其状态特征。
>The U.S. Environmental Protection Agency (EPA) uses a wide range of models to inform decisions that support its mission of protecting human health and safeguarding the natural environment — air, water, and land — upon which life depends. These models include atmospheric and indoor air models, ground water and surface water models, multimedia models, chemical equilibrium models, exposure models,toxicokinetic models, risk assessment models, and economic models. These models range from simple to complex and may employ a combination of scientific, economic, socio-economic, or other types of data.As stated in the National Research Council (NRC) report Models in Environmental Regulatory Decision Making, models are critical to regulatory decision making because the spatial and temporal scales linking environmental controls and environmental quality generally do not allow for an observational approach to understand the relationship between economic activity and environmental quality (NRC 2007). Models have a long history of helping to explain scientific phenomena and predict outcomes and behavior in settings where empirical observations are limited or not available. 

NRC报告对模型进行了如下的定义：
模型是对现实的抽象简化，旨在增加对所关注的物理、化学、经济及社会系统的指标加深理解。

特别地，本导则则主要聚焦于NRC所列出的部分**计算模型**。这些模型主要使用可量化的**变量**，数值输入，依据数学方程关系获得量化的输出结果。

计算模型：A computational model is a mathematical model in computational science that requires extensive computational resources to study the behavior of a complex system by computer simulation.[2]
Variable: A measured or estimated quantity that describes an object or can be observed in a system and that is subject to change. 
>In particular, this guidance focuses on the subset of all models termed “computational models” by the NRC. These are models that use measurable variables, numerical inputs, and mathematical relationships to produce quantitative outputs. (Note that all terms underlined in this document are defined in the Glossary, Appendix A). 

随着模型在决策支持中变的越来越重要，模型开发、评估过程遵循标准能够确保模型及其结果的科学性、可靠性、合理性及应用。利用模型获取决策支持的过程管理和合理计划方案也变得更加重要（Manno等，2008）。本导则目标为促进对模型开发、评估、应用过程的了解，同时推动合理的利用模型进行决策支持。
>As models become increasingly significant in decision making, it is important that the model development and evaluation processes conform to protocols or standards that help ensure the utility, scientific soundness, and defensibility of the models and their outputs for decision making. It is also increasingly important to plan and manage the process of using models to inform decision making (Manno et al. 2008). This guidance document aims to facilitate a widespread understanding of the processes for model development, evaluation, and application and thereby promote their appropriate application to support informed decision making. 

模型的应用范围十分广泛，如果不考虑地域、模式、概念基础、形式、严肃等级（如应用于筛选值到复杂的分析），那么本导则描述的一般原则及方法基本适用于全部用于决策支持的模型。当然，也适用于一开始并非管理目的，仅仅用于研究目而开发的模型，因为大量的这样的模型随着研究的深入其最后能够用于环境管理。

> Recognizing the diversity of modeling applications throughout the Agency, the principles and practices described in the guidance apply generally to all models used to inform Agency decisions, regardless of domain, mode, conceptual basis, form, or rigor level (i.e., varying from screening-level applications to complex analyses) (EPA 2001). The principles presented in this guidance are also applicable to models not used for regulatory purposes as experience has shown that models developed for research and development have often found useful applications in environmental management purposes. 

本导引用了多方的报告，包括SAB,NRC等同行的经典著作，提供了全面的实践确保其能够评估环境模型的质量。
>This guidance presents recommendations drawn from Agency white papers on environmental modeling,
EPA Science Advisory Board (SAB) reports, NRC’s Models in Environmental Regulatory Decision
Making, and the peer-reviewed literature. It provides an overview of best practices for ensuring and
evaluating the quality of environmental models. 

在过去的导则中，已经对模型项目的质量控制过程有所概述。有很多报告文件能够用于保证模型开发和应用过程的质量控制（见附录C1）。例如，质量控制计划包括模型能否满足，不同的项目工程启动时制定基本应用要求。
>These practices complement the systematic QA planning process for modeling projects outlined in
existing guidance (EPA 2002b). These QA processes produce documentation supporting the quality of
the model development and application process (Appendix C, Box C1: Background on EPA Quality
System). For example, QA plans should contain performance criteria (“specifications”) for a model in the
context of its intended use, and these criteria should be developed at the onset of each project. 

在模型评估阶段，这些要求变为一系列模型质量的测试。技术文件和评估结果为模型满足其使用要求及模型可靠性提供了可查询的记录。
>During the model evaluation process, these criteria are subjected to a series of tests of model quality (“checks”).
Documentation of these specifications and the evaluation results provides a record of how well a model
meets its intended use and the basis for a decision on model acceptability. 

同时，也提供了特定的建议：在模型开发、评估和应用时怎样去评估检查的合理性。遵循导则中强调的这些要求，配合质量控制计划，能够有效的确保模型项目的结果和依据模型得到的决策能够满足环保署的信息质量指导方针（EPA 2002A)。
>The primary purpose of this guidance is to provide specific advice on how to best perform these “checks”
during model development, evaluation, and application. Following the best practices emphasized in this
document, together with well-documented QA project plans, will help ensure that results of modeling
projects and the decisions informed by them heed the principles of the Agency’s Information Quality
Guidelines (EPA 2002a). 

## 小结
导则的应用范围及目的。

## 1.2 适用人员

本导使用广泛，模型开发人员，计算机程序员，模型使用者，政策制定者。其中模型使用者主要指生成模型结果（建模、设置参数等）和使用模型结果的管理者。可以看出，针对模型这个工具，他的用户非常的多，整个模型所涉及的角色也有多种多样，不管时开发模型的人，还是构建模型的人，甚至运用模型结果的管理者都可以从本导则中获取相关信息。

> This document is intended for a wide range of audiences, including model developers, computer
> programmers, model users, policy makers who work with models, and affected stakeholders. Model
> users include those who generate model output (i.e., who set up, parameterize, and run models) and
> managers who use model outputs. 

## 1.3 本导则的结构

本导则主要为大部分模型用户，提供了一种好的模型的评判标准。附录部分则提供了对于特定用户来说更有用的技术信息和例子。本导则的结构来说，主要分为三个核心主题：模型开发、评估和应用。但是必须意识到三个主题并不是为完全严格次序，例如，分析和评估模型与输入数据以确保其质量贯穿模型开发和应用的整个阶段。

> The main body of this document provides an overview of principles of good modeling for all users. The appendices present technical information and examples that may be more appropriate for specific user groups. For organizational simplicity, the main body of this guidance has separate chapters on the three key topics: model development, model evaluation, and model application. However, it is important to note that these three topics are not strictly sequential, For example, the process of evaluating a model and its input data to ensure their quality should be undertaken and documented during all stages of model development and application. 

**第一章**对导则进行了基本介绍和适用范围确定。**第二章**在环境决策中模型的作用。在第二章的末尾的图1展现了模型开发和应用过程的步骤，模型在公共政策过程中的决策。**第三章和第四章**为模型开发（包括问题的确定）和模型评估的流程和方法。**第五章**，则叙述了从环境模型到环境政策及管理决策最有效的实践案例。

附录部分则提供了更多的技术细节和案例。A为全部的划线术语解释和定义。B总结了整合到环境管理中模型的类别。C则为质量管理程序和其他相关主题的背景信息。D为实践操作概览，涉及模型评估，包括模型的同行评议过程的细节信息，特定的技术工具等。

## 1.4 补充说明

> The principles and practices described in this guidance are designed to apply generally to all types of models; however, EPA program and regional offices may modify the recommendations, as appropriate and necessary to the specific modeling project and application. Each EPA office is responsible for implementing the best practices described in a manner appropriate to meet its needs.
> As indicated by the use of non-mandatory language such as “may,” “should,” and “can,” this document provides recommendations and suggestions and does not create legal rights or impose legally binding requirements on EPA or the public.
> The Council for Regulatory Environmental Modeling has also developed the Models Knowledge Base — a Web-based inventory of information on models used in EPA — as a companion product to complement this document. This inventory provides convenient access to standardized documentation on the models’development, scientific basis, user requirements, evaluation studies, and application examples. 

---

参考文献：
[1] Gaber N, Foley G, Pascual P, et al. Guidance on the development, evaluation, and application of environmental models[J]. Report, Council for Regulatory Environmental Modeling, 2009, 81.
[2] Melnik, Roderick, ed. (2015). Mathematical and Computational Modeling: With Applications in Natural and Social Sciences, Engineering, and the Arts. Wiley. ISBN 978-1-118-85398-6.

![页尾](http://comieswater-1254012817.cossh.myqcloud.com/页尾识别new-2017-09-22.png)
微信公众号 | 水环境编Cheng长
网          站 | comieswater.com


![赞赏我](http://comieswater-1254012817.cossh.myqcloud.com/IMG_3077.JPG)

 2018-8-16
 folder=/微信公众号/水环境编Cheng长/

[1]: http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1517576665753.jpg