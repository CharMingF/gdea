---
title: 《模型开发、评估、应用导则》批注：第四章(2)
tags: 1000天持续行动,GDEA
date:   2018-12-16
---
·[486]|1000天行动计划
**读书笔记**/热点追踪/论文研读/教程手册
![封面](http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1534259099598.png)

# 4.2 模型评估的最佳实践
    P4.2模型评估的总述，通过定量和定性的两种主要模式来进行评估工作。
上节前言所述的四个问题主要涉及四方面的问题：模型背后框架的科学可靠性、获取到的数据的数量和质量、与观测条件的一致性程度和模型当前应用下的适应性。这个导则描述了一些工具和最佳的实践手段去解决这些问题：同行专家评审；包括数据质量评估在内的QA项目计划（质量保证）；模型校准及验证（关于模型的精确性和预测能力的定性和定量的评价）；敏感性和不确定性分析。这些工具和方法过程包括定性和定量化的技术手段：

>The four questions listed above address the soundness of the science underlying a model, the quality and quantity of available data, the degree of correspondence with observed conditions, and the appropriateness of a model for a given application. This guidance describes several “tools” or best practices to address these questions: peer review of models; QA project planning, including data quality assessment; model corroboration (qualitative and/or quantitative evaluation of a model’s accuracy and predictive capabilities); and sensitivity and uncertainty analysis. These tools and practices include both qualitative and quantitative techniques:

1. 定性评估：模型预测过程中的不确定性的来源可能并不能被量化。例如，模型背后的理论的不确定性，因为理论的行为是通过数学方程呈现环境要素来表达，从而这些理论被模拟呈现出来。模型参数值是否恰当和不能被直接观测或测量到的输入条件（如气体排放估计），这些都需要专家来评价。一些不确定性地方也需要定性评价。关于模型行为和模型预测值对比，这些评价可能都需要涉及专家来进行评价。
2. 定量评估：一些引起不确定性的因素诸如模型的参数和一些输入条件是能够通过定量的手段来进行评估的，主要涉及统计性不确定性和敏感性分析。这些分析也能被用于定量描述与观测数据不同的现状条件是模拟的。但是，因为模型的预测不是观测值，特别需要注意对模型模拟值和观测值差异的量化分析。

>Qualitative assessments: Some of the uncertainty in model predictions may arise from sources whose uncertainty cannot be quantified. Examples are uncertainties about the theory underlying the model, the manner in which that theory is mathematically expressed to represent the environmental components, and the theory being modeled. Subjective evaluation of experts may be needed to determine appropriate values for model parameters and inputs that cannot be directly observed or measured (e.g., air emissions estimates). Qualitative assessments are needed for these sources of uncertainty. These assessments may involve expert elicitation regarding the system’s behavior and comparison with model forecasts.
>Quantitative assessments: The uncertainty in some sources — such as some model parameters and some input data — can be estimated through quantitative assessments involving statistical uncertainty and sensitivity analyses. These types of analyses can also be used to quantitatively describe how model estimates of current conditions may be expected to differ from comparable field observations. However, since model predictions are not directly observed, special care is needed when quantitatively comparing model predictions with field data.

模型的评估是一个不断迭代的过程。然而，这些手段和方法可能需要高效的贯穿模型的评估、测试和应用阶段，其不应该被理解为单独的一个模型评估的步骤。
模型评估应该使用一个现有的恰当和合理的评分的方法来进行管理（EPA 2001,2002b)。这个方法能够满足模型评估随着问题而修改，以及程序不断变化的需求。例如，一个筛选模型（用于提供保守型风险规避方案）被用于风险管理，其应该能够严谨的评估去避免漏报，同时也不能带来显著的数据生成的负担（误报）。理想情况下，决策制定者和模型操作者一起工作在一个项目中去确定合理的模型评估（见3.1）。
>Model evaluation should always be conducted using a graded approach that is adequate and appropriate to the decision at hand (EPA 2001, 2002b). This approach recognizes that model evaluation can be modified to the circumstances of the problem at hand and that programmatic requirements are varied. For example, a screening model (a type of model designed to provide a “conservative” or risk-averse answer) that is used for risk management should undergo rigorous evaluation to avoid false negatives, while still not imposing unreasonable data-generation burdens (false positives) on the regulated community. Ideally, decision makers and modeling staff work together at the onset of new projects to identify the appropriate degree of model evaluation (see Section 3.1).

外部条件也能够影响模型评估过程，例如，在模型的结果需要高昂代价的控制策略和可能引起巨大的争议，此时就需要更加精细的模型评估。在这些案例中，模型的许多方面可能需要仔细审查，模型操作者必须对模型评估过程进行详细的文档记录，以回答和解释可能出现的质问。在模型出现之前未遇到过的特殊性和极端情形，就需要更深层次的模型评估工作。

>External circumstances can affect the rigor required in model evaluation. For example, when the likely result of modeling will be costly control strategies and associated controversy, more detailed model evaluation may be necessary. In these cases, many aspects of the modeling may come under close scrutiny, and the modeler must document the findings of the model evaluation process and be prepared to answer questions that will arise about the model. A deeper level of model evaluation may also be appropriate when modeling unique or extreme situations that have not been previously encountered.

最后，正如前面所说的，一些评估需要多模型耦合，这种耦合对于不确定性的评估和应用模型过程有更多的要求，每个单独的模型和全部整合的模型都需要被评估。

节4.2.1和4.2.2，分别介绍了同行评审和输入数据的质量保证措施。节4.2.3，描述模型的一致性和敏感性分析、不确定性分析（附录D）。
>Finally, as noted earlier, some assessments require the use of multiple, linked models. This linkage has implications for assessing uncertainty and applying the system of models. Each component model as well as the full system of integrated models must be evaluated.
>Sections 4.2.1 and 4.2.2, on peer review of models and quality assurance protocols for input data, respectively, are drawn from existing guidance. Section 4.2.3, on model corroboration activities and the use of sensitivity and uncertainty analysis, provides new guidance for model evaluation (along with Appendix D).

扩展阅读：
Box 6: Examples of Life Cycle Model Evaluation
(from Box 4-5 in NRC’s Models in Environmental Regulatory Decision Making)
The value in evaluating a model from the conceptual stage through the use stage is illustrated in a multi-year project conducted by the Organization for Economic Cooperation and Development (OECD). The project sought to develop a screening model that could be used to assess the persistence and long-range transport potential of chemicals. To ensure its effectiveness, the screening model needed to be a consensus model that had been evaluated against a broad set of available models and data.
This project began at a 2001 workshop to set model performance and evaluation goals that would provide the foundation for subsequent model selection and development (OECD 2002). OECD then established an expert group in 2002. This group began its work by developing and publishing a guidance document on using multimedia models to estimate environmental persistence and long-range transport. From 2003 to 2004, the group compared and assessed the performance of nine available multimedia fate and transport models (Fenner et al. 2005; Klasmeier et al. 2006). The group then developed a parsimonious consensus model representing the minimum set of key components identified in the model comparison. They convened three international workshops to disseminate this consensus model and provide an ongoing model evaluation forum (Scheringer et al. 2006).
In this example, more than half the total effort was invested in the conceptual and model formulation stages, and much of the effort focused on performance evaluation. The group recognized that each model’s life cycle is different, but noted that attention should be given to developing consensus-based approaches in the model concept and formulation stages. Conducting concurrent evaluations at these stages in this setting resulted in a high degree of buy- in from the various modeling groups.

### 4.2.1 同行评审

    P介绍同行评审的重要性。

同行评议为独立评估和机构使用的环境模型的主要机制。其提供了一种独立、专业检查评估，主要实现两方面:
1. 去评估环境模型的假设、方法和结论是否基于合理的科学原则。
2. 模型对于特定的管理决策的适用性（后者的目标对于已有的模型的次级应用是特别重要的）。

对于特定的管理应用，同行审阅获取到的信息也有助于多个竞品的模型的抉择。最后，同行评审对于定义存在模型的限制也是有用的。但是，其并不适用于模型形成的管理决策或者政策（EPA 2000c)。（*译者注：最后一句不知道是啥意思*）

>Peer review provides the main mechanism for independent evaluation and review of environmental models used by the Agency. Peer review provides an independent, expert review of the evaluation in Section 4.1; therefore, its purpose is two-fold:
>1. To evaluate whether the assumptions, methods, and conclusions derived from environmental models are based on sound scientific principles.
>2. To check the scientific appropriateness of a model for informing a specific regulatory decision. (The latter objective is particularly important for secondary applications of existing models.)
>Information from peer reviews is also helpful for choosing among multiple competing models for a specific regulatory application. Finally, peer review is useful to identify the limitations of existing models. Peer review is not a mechanism to comment on the regulatory decisions or policies that are informed by models (EPA 2000c).

在评估计划过程中，同行评审提出的问题及作出一致性记录对于同行评议者回答那些问题应作为质量保证计划的一部分。例如，同行评审者可能关注是否模型能够满足质量评估计划中的所设定的的目标或规格（见3.1节）。

>Peer review charge questions and corresponding records for peer reviewers to answer those questions should be incorporated into the quality assurance project plan, developed during assessment planning (see Section 4.2.2, below). For example, peer reviews may focus on whether a model meets the objectives or specifications that were set as part of the quality assurance plan (see EPA 2002b) (see Section 3.1).

全部用于生成关键决策的模型都是同行评审的对象（EPA 2000c，1993），主要基于以下理由：
1. 模型结果被作为主要的管理或者政策决策支持的基础。
2. 决策涉及到重大投资项目。
3. 角色涉及跨部门或跨机构的应用。

现有的导则建议一个新的模型应该在其第一次应用之前先被同行评议；对于后续的应用，项目管理应该考虑考学\技术\复杂度以及特殊场景去决定是否需要额外的评审（EPA 1993）。为了节约资源，重复的评审应该极力避免。
模型的非首次应用(存在的EPA模型）相比特殊管理信息需要而开发的模型有着不同类型的评估模式。特别的，那些评审可能需要通过设定一系列条件来分析模型应用方面的不确定，而不需要再检查模型框架背后的科学性。例如，一个项目团队决定去使用WASP(水质模型的一种，具有成熟的模型框架）评估水质问题，项目团队则不需要过多的关注模型的框架合理性，而应该引导同行审议的内容偏向WASP的特定的应用方面。

>Existing guidance recommends that a new model should be scientifically peer-reviewed prior to its first application; for subsequent applications, the program manager should consider the scientific/technical complexity and/or the novelty of the particular circumstances to determine whether additional peer review is needed (EPA 1993). To conserve resources, peer review of “similar” applications should be avoided.

>Models used for secondary applications (existing EPA models or proprietary models) will generally undergo a different type of evaluation than those developed with a specific regulatory information need in mind. Specifically, these reviews may deal more with uncertainty about the appropriate application of a model to a specific set of conditions than with the science underlying the model framework. For example, a project team decides to assess a water quality problem using WASP, a well-established water quality model framework. The project team determines that peer review of the model framework itself is not necessary, and the team instead conducts a peer review on their specific application of the WASP framework.

同行评审验证模型的科学可靠性，需要从以下方面着手（SAB 1993a EPA 1993):

1. 输入数据是否合理。
2. 边界条件是否合理。
3. 输入和假设的文档。
4. 所选择的参数的适用性和适用范围。
5. 校准模型的文档（通过调整模型输入去提高模型的表现）。
6. 模型适用性范围。
7. 经验资料或数据如何加强或者削弱通过模型获取到的结论。

为了发挥同行评审的作用和提高其效率，外部的评审应该尽可能在模型开发阶段就开始（EPA 2000b），因为同行评审需要很多时间和资源，其应作为工程计划和条款的组成部分。同行评审在模型开发的早期阶段能够帮助评估模型的基础概念，可能能够通过修正错误方案，在有争议的地方提供强有力的技术支持而节省大量的时间（SAB 1993a，EPA 1993).同样，其也能够在模型开发的后期阶段发挥作用，作为独立的模型代码的外部审核（例如模型验证），模型的适用性的外部审核应该在任何决策支持中被提前考虑，能够有效的避免对于特定管理目的，模型被不恰当的应用（EPA 1993)。
>The following aspects of a model should be peer-reviewed to establish scientific credibility (SAB 1993a, EPA 1993):
Appropriateness of input data.
Appropriateness of boundary condition specifications.
Documentation of inputs and assumptions.
Applicability and appropriateness of selected parameter values.
Documentation and justification for adjusting model inputs to improve model performance (calibration).
Model application with respect to the range of its validity.
Supporting empirical data that strengthen or contradict the conclusions that are based on model results.

>To be most effective and maximize its value, external peer review should begin as early in the model development phase as possible (EPA 2000b). Because peer review involves significant time and resources, these allocations must be incorporated into components of the project planning and any related contracts. Peer review in the early stages of model development can help evaluate the conceptual basis of models and potentially save time by redirecting misguided initiatives, identifying alternative approaches, or providing strong technical support for a potentially controversial position (SAB 1993a, EPA 1993). Peer review in the later stages of model development is useful as an independent external review of model code (i.e., model verification). External peer review of the applicability of a model to a particular set of conditions should be considered well in advance of any decision making, as it helps avoid inappropriate applications of a model for specific regulatory purposes (EPA 1993).

同行审议是管理者应用模型去做决策分析的后勤保障，完成外部的评审需要的机制包括但不限于：
1. 优秀的科学家陪审团队。
2. 构建外部的同行评审机制如SAB
3. 构建技术工作组。

对于给定模型工程，一些资源提供了评审成员的资格和数量参考(SAB 1993a; EPA 2000c, 1993, 1994a). 关键方面在 附录 D 。
>The peer review logistics are left to the discretion of the managers responsible for applying the model results to decision making. Mechanisms for accomplishing external peer review include (but are not limited to):
Using an ad hoc panel of scientists.
Using an established external peer review mechanism such as the SAB Holding a technical workshop.

>Several sources provide guidance for determining the qualifications and number of reviewers needed for a given modeling project (SAB 1993a; EPA 2000c, 1993, 1994a). Key aspects are summarized in Appendix D of this guidance.





参考文献：
[1] Gaber N, Foley G, Pascual P, et al. Guidance on the development, evaluation, and application of environmental models[J]. Report, Council for Regulatory Environmental Modeling, 2009, 81.


![页尾](http://comieswater-1254012817.cossh.myqcloud.com/页尾识别new-2017-09-22.png)
微信公众号 | 水环境编Cheng长
网          站 | comieswater.com


![赞赏我](http://comieswater-1254012817.cossh.myqcloud.com/IMG_3077.JPG)

 2018-8-16

