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
> The following aspects of a model should be peer-reviewed to establish scientific credibility (SAB 1993a, EPA 1993):
Appropriateness of input data.
Appropriateness of boundary condition specifications.
Documentation of inputs and assumptions.
Applicability and appropriateness of selected parameter values.
Documentation and justification for adjusting model inputs to improve model performance (calibration).
Model application with respect to the range of its validity.
Supporting empirical data that strengthen or contradict the conclusions that are based on model results.

> To be most effective and maximize its value, external peer review should begin as early in the model development phase as possible (EPA 2000b). Because peer review involves significant time and resources, these allocations must be incorporated into components of the project planning and any related contracts. Peer review in the early stages of model development can help evaluate the conceptual basis of models and potentially save time by redirecting misguided initiatives, identifying alternative approaches, or providing strong technical support for a potentially controversial position (SAB 1993a, EPA 1993). Peer review in the later stages of model development is useful as an independent external review of model code (i.e., model verification). External peer review of the applicability of a model to a particular set of conditions should be considered well in advance of any decision making, as it helps avoid inappropriate applications of a model for specific regulatory purposes (EPA 1993).

同行审议是管理者应用模型去做决策分析的后勤保障，完成外部的评审需要的机制包括但不限于：
1. 优秀的科学家陪审团队。
2. 构建外部的同行评审机制如SAB
3. 构建技术工作组。

对于给定模型工程，一些资源提供了评审成员的资格和数量参考(SAB 1993a; EPA 2000c, 1993, 1994a). 关键方面在 附录 D 。
> The peer review logistics are left to the discretion of the managers responsible for applying the model results to decision making. Mechanisms for accomplishing external peer review include (but are not limited to):
Using an ad hoc panel of scientists.
Using an established external peer review mechanism such as the SAB Holding a technical workshop.

> Several sources provide guidance for determining the qualifications and number of reviewers needed for a given modeling project (SAB 1993a; EPA 2000c, 1993, 1994a). Key aspects are summarized in Appendix D of this guidance.


### 4.2.2 质量保证计划和数据质量评估

与同行审查类似的作用，数据质量评估主要确认模型是否依据合理的科学的原则开发而成。虽然不可避免，数据总是有多变性，但是仍然有很多相关的数据质量评估的导则用于降低书的不确定性（附录D，质量保证计划和数据评判标准）：

切实履行QA计划方案也能够用于确认模型应对特殊的情形的表现，其很好的对应了 节4.1 提到的第四个模型评估的问题，模型项目满足QA目标的程度通常是外部同行评审过程的函数。The Guidance for Quality Assurance Project Plans for Modeling (EPA 2002b) 提供了如何进行模型的质量保证计划的一般性说明（例如：规格或者评估标准，模型过程的多阶段评估；矫正的反馈报告；通过或否决过程等）。数据质量评估是模型QA计划的重要部分。

用于参数化和验证的数据的质量还是数量（主要是代表性）都要在模型项目的任何相关阶段进行评估。这种评估能去评价是否获取到的数据足以支撑模型应用，以及通过和观测数据进行对比，确保数据具有被模拟的真实系统的代表性。

> Like peer review, data quality assessment addresses whether a model has been developed according to the principles of sound science. While some variability in data is unavoidable (see Section 4.2.3.1), adhering to the tenets of data quality assessment described in other Agency guidance (Appendix D, Box D2: Quality Assurance Planning and Data Acceptance Criteria) helps minimize data uncertainty.

> Well-executed QA project planning also helps ensure that a model performs the specified task, which addresses the fourth model evaluation question posed in Section 4.1\. As discussed above, evaluating the degree to which a modeling project has met QA objectives is often a function of the external peer review process. The Guidance for Quality Assurance Project Plans for Modeling (EPA 2002b) provides general information about how to document quality assurance planning for modeling (e.g., specifications or assessment criteria development, assessments of various stages of the modeling process; reports to management as feedback for corrective action; and finally the process for acceptance, rejection, or qualification of the output for use) to conform with EPA policy and acquisition regulations. Data quality assessments are a key component of the QA plan for models.

> The formation and use of an ad hoc panel of peer reviewers may be subject to the Federal Advisory Committee Act (FACA). Compliance with FACA’s requirements is summarized in Chapter Two of the Peer Review Handbook, “Planning a Peer Review” (EPA 2000c). Guidance on compliance with FACA may be sought from the Office of Cooperative Environmental Management. Legal questions regarding FACA may be addressed to the Cross-Cutting Issues Law Office in the Office of General Counsel.  Note that a technical workshop held for peer review purposes is not subject to FACA if the reviewers provide individual opinions. [ Note that there is no “one time meeting” exemption from FACA. The courts have held that even a single meeting can be subject to FACA. ] An attempt to obtain group advice, whether it be consensus or majority-minority views, likely would trigger FACA requirements.  Other guidance that can help ensure the quality of data used in modeling projects includes:  • Guidance for the Data Quality Objectives Process, a systematic planning process for environmental data collection (EPA 2000a).  • Guidance on Choosing a Sampling Design for Environmental Data Collection, on applying statistical sampling designs to environmental applications (EPA 2002c).  • Guidance for Data Quality Assessment: Practical Methods for Data Analysis, to evaluate the extent to which data can be used for a specific purpose (EPA 2000b).

> Both the quality and quantity (representativeness) of supporting data used to parameterize and (when available) corroborate models should be assessed during all relevant stages of a modeling project. Such assessments are needed to evaluate whether the available data are sufficient to support the choice of the model to be applied (question 2, Section 4.1), and to ensure that the data are sufficiently representative of the true system being modeled to provide meaningful comparison to observational data (question 3, Section 4.1).

### 4.2.3 验证、敏感性分析、不确定分析

”模型究竟多大程度的表达的真实系统？“ 这个问题真的不是很好回答。通常，回答这个问题并不是说把模型结果和观测结果对比下那么简单。节3.1 有提到在开发或者使用环境模式时，模型者和决策者应该考虑在模型应用情境下的可被接受的不确定性程度。为了做好这些，需要去理解模型内在的不确定性，这节就主要通过三部分加深理解：

1.  模型验证（节 4.2.3.2 ），包括全部定性和定量的方法来评估模型与现实的一致性程度。

2.  敏感性分析（节 4.2.3.3），涉及研究到模型输入值或者假设的改变对模型输出的影响或模型的响应。

3.  不确定性分析（节 4.2.3.3），分析模型由于对模型参数真值或其分布缺乏足够的认识而造成的影响。

按照一定方案进行分析，并将结果记录以支撑模型。节4.2.3.1 描述定义了多种不确定性的类型和概念，有关模型的验证和敏感性、不确定性分析帮助评估模型。

* * *

这里多罗嗦下吧，谈下自己的个人理解。所谓的验证、敏感性分析和不确定性分析，实际上是模型校准的一部分工作。前两者在校准前期过程中，而不确定性则是校准后期的一种评估。

验证，简单的说就是模型模拟结果与实际观测值进行对比，当然，这个比较的这个实际测值是独立与校准使用的那套数据的，对于水质模型的季节性变化而言，一般需要独立的2、3年的数据进行验证，才能说这套参数比较成功。

敏感性呢？敏感性，简单就是参数变化对模型的影响。拿生活中来举例，比如车速这个东西，油门和刹车就对其特别的敏感，但是外面的风向、风速可能就不是那么的敏感，车什么颜色吧，这个对车速基本没有影响了。也就是不同的参数对模型的表现的重要性是不同的，当然这里需要注意的是参数和模型表现的对应关系，上述例子中的油门和车速对应，也就是说如果拿车好不好看来说，油门就没那么敏感了。敏感性分析有助于我们校准模型，因为一般模型的参数都会很多，校准过程中肯定会先调整主要的参数。那么模型的评价为啥需要涉及到这个特性呢？我还没有看后面的内容，在这里先猜一下，对敏感性的认识，有助于把娃模型参数及外部条件变化时，模型的表现。还是前面的例子，假如我对车速比较在意，那么我可能更多的就关注刹车和油门，当地的日常平均风速呢，我可以稍微关注下，车的颜色我可能完全不关注。

最后就是不确定性了，这个不确定性主要是用于把握模型的可靠性程度。其毕竟是模型，很多方面我们无法完全掌控，不确定性的分析就是相当于我们穷尽各种可能，分析在不同可能下模型的表现。还是上面的例子，试图得到最大的车速，比如我开始只考虑了发动机的功率，通过这其计算出来一个最大车速（比如180 km/h），一般来说比较准确了，但是我还是不敢保证，我不确定是不是还有其他因素会对车速有影响呢？这时候就需要穷尽所有可能的因素了，比如轮胎好不好？车的流线如何？这些因素我全部考虑在内，得出一些结论，比如好的轮胎和差的轮胎最多影响20%的车速，车的形状顶多影响10%的车速，之后我就可以把这个最大车速的范围较为可靠的计算出来(150-180 km/h)，而且比较有信心不管怎么都不会脱离这个范围。

* * *

> The question “How closely does the model approximate the real system of interest?” is unlikely to have a simple answer. In general, answering this question is not simply a matter of comparing model results and empirical data. As noted in Section 3.1, when developing and using an environmental model, modelers and decision makers should consider what degree of uncertainty is acceptable within the context of a specific model application. To do this, they will need to understand the uncertainties underlying the model. This section discusses three approaches to gaining this understanding:
*   Model corroboration (Section 4.2.3.2), which includes all quantitative and qualitative methods for evaluating the degree to which a model corresponds to reality.

*   Sensitivity analysis (Section 4.2.3.3), which involves studying how changes in a model’s input values or assumptions affect its output or response.

*   Uncertainty analysis (Section 4.2.3.3), which investigates how a model might be affected by the lack of knowledge about a certain population or the real value of model parameters.

> Where practical, the recommended analyses should be conducted and their results reported in the documentation supporting the model. Section 4.2.3.1 describes and defines the various types of uncertainty, and associated concepts, inherent in the modeling process that model corroboration and sensitivity and uncertainty analysis can help assess.

#### 4.2.3.1 不确定性的类型

不确定性是存在于模型过程的各个方面。为了成功的把模型获取到的信息应用于决策支持，区分出对模型输出结果（无论是定性和定量方面）有重要影响的不确定性和明确其重要性是非常关键的步骤。

第三章定义的那样，本导则所指的不确定性为**有关特别的要素、参数（输入）、模型等缺乏机理表达引起的不确定性**。对于组织机构，影响模型质量的不确定被归类为以下：

1. 模型架构的不确定性。这类型主要是系统关键行为的机理表达的缺失；空间和时间分辨率的限制；系统的简化等导致的。
2. 模型输入不确定性。由数据测量误差、测量值和输入模型的值（因聚合或平均引起）不一致性，参数值的不确定性导致。
3. 模型适用范围的不确定性。来源于模型使用超出了其开发时限定的条件，或对多个已存在的不同时间和空间尺度的模型开发的耦合模型产生的。

> Uncertainties are inherent in all aspects of the modeling process. Identifying those uncertainties that significantly influence model outcomes (either qualitatively or quantitatively) and communicating their importance is key to successfully integrating information from models into the decision making process. As defined in Chapter 3, uncertainty is the term used in this guidance to describe incomplete knowledge about specific factors, parameters (inputs), or models. For organizational simplicity, uncertainties that affect model quality are categorized in this guidance as:
	- Model framework uncertainty, resulting from incomplete knowledge about factors that control the behavior of the system being modeled; limitations in spatial or temporal resolution; and simplifications of the system.
	- Model input uncertainty, resulting from data measurement errors, inconsistencies between measured values and those used by the model (e.g., in their level of aggregation/averaging), and parameter value uncertainty.
	- Model niche uncertainty, resulting from the use of a model outside the system for which it was originally developed and/or developing a larger model from several existing models with different spatial or temporal scales.
 
（这段话比较难翻译，因为整体比较别扭，所以这里我特别的解释下，所谓的不确定性，主要是引入概率角度来对模型进行分析。因为世界不可知的部分和随机性，导致我们所有发生的事情都不可能百分之百。特别地，模型还是现实的抽象，其更会由很多不确定性的因素存在，导致我们对模型得到的结果不能够百分之百的确信。上面提到了三种的不确定性呢？解释下就是：
- 模型架构。模型是现实问题的抽象，那么其必然有部分的失真。比如时间和空间的分辨率不够，导致表达的不够精细化。模型的简化，使得模型很多过程没有表达出来。甚至模型中对机理过程的表达，也不完全是准确的。那么这些小的问题，就会带来模型结果有一定的偏离，这些是不可避免的，但是我们能够评估其影响有多大，从而给出的结果是一个区间或者带有概率密度函数的结果。
- 模型输入。我们输入模型的数据，本身就因为测量可能存在误差，同时测量值和模型所需要的值之间也存在一定的不匹配性，比如很多时候获取到的数据是平均值，这种数据就引入了一定的不确定因素。
- 模型的适用性。比如模型开发的时候是用于海洋模型，而现在用于内陆水体，那么其中的部分过程是不是存在大的差别，这种带来的模型适用性的问题。

---

事实上，以上三种类型的不确定性是相关，模型架构及框架引起的不确定性是由于不完整的科学数据及所模拟机理过程缺失的结果。模型框架的不确定性也可能是由于概念模型到数学模型转换时简化过程的引起的。在科学文献中，这种类型的不确定性也是指结构误差（Beck 1987），概念误差（Konikow and Bredehoeft 1992)，概念模型中的不确定性（Usunoff et al.1992),或模型误差/不确定性（EPA 1993；Luis and McLaughlin 1992). 结构误差与模型的算法的数学结构紧密相关，概念模型指的是模型控制方程的机理。术语“模型误差”和“模型不确定性”都是表达模型框架不确定性的。

> In reality, all three categories are interrelated. Uncertainty in the underlying model structure or model framework uncertainty is the result of incomplete scientific data or lack of knowledge about the factors that control the behavior of the system being modeled. Model framework uncertainty can also be the result of simplifications needed to translate the conceptual model into mathematical terms as described in Section 3.3. In the scientific literature, this type of uncertainty is also referred to as structural error (Beck 1987), conceptual errors (Konikow and Bredehoeft 1992), uncertainties in the conceptual model (Usunoff et al. 1992), or model error/uncertainty (EPA 1997; Luis and McLaughlin 1992). Structural error relates to the mathematical construction of the algorithms that make up a model, while the conceptual model refers to the science underlying a model’s governing equations. The terms “model error” and “model uncertainty” are both generally synonymous with model framework uncertainty.

许多模型通过不断的迭代更新来逐渐的减小其机理过程不确定性，模型可能随着版本的更新逐渐产生重要的变化。近二十年来，对于预测汽车尾气排放的MOBILE模型，CMAQ模型、QUAL2水质模型等，这些模型都是经过多个版本更新，对主要的科学过程进行了完善和拓展（Scheffe and Morris 1993; Barnwell et al.2004;EPA 1999c,as cited in NRC 2007)。

> Many models are developed iteratively to update their underlying science and resolve existing model framework uncertainty as new information becomes available. Models with long lives may undergo important changes from version to version. The MOBILE model for estimating atmospheric vehicle emissions, the CMAQ (Community Multi-scale Air Quality) model, and the QUAL2 water quality models are examples of models that have had multiple versions and major scientific modifications and extensions in over two decades of their existence (Scheffe and Morris 1993; Barnwell et al. 2004; EPA 1999c, as cited in NRC 2007).

在合适的模型框架被开发后，模型本身若在输入数据并没有足够的质量情况下也带来很大的不确定性，用于校准或验证的实测数据的质量受不确定性和变异性的影响。本导则使用“数据不确定性”来表示在数据采集和处理过程中，测量误差、分析不精确度、有限的样本带来的不确定性。

> When an appropriate model framework has been developed, the model itself may still be highly uncertain if the input data or database used to construct the application tool is not of sufficient quality. The quality of empirical data used for both model parameterization and corroboration tests is affected by both uncertainty and variability. This guidance uses the term “data uncertainty” to refer to the uncertainty caused by measurement errors, analytical imprecision, and limited sample sizes during data collection and treatment.

与数据不确定性不同，变异性常来自于确定的参数的固有的随机性，同时也来自于环境过程的异质性和多样性。变异性的例子包括生态条件的波动，栖息地的变化、人群的基因变异。模型参数的变异与输入数据被聚合（空间或时间）的程度有很大关系。数据的不确定性在能被通过进一步研究而减小（EPA 1997)，则被成为可减小的不确定性。反之，不能通过研究减小的，则被称为不可减小的不确定性。

> In contrast to data uncertainty, variability results from the inherent randomness of certain parameters, which in turn results from the heterogeneity and diversity in environmental processes. Examples of variability include fluctuations in ecological conditions, differences in habitat, and genetic variances among populations (EPA 1997). Variability in model parameters is largely dependent on the extent to which input data have been aggregated (both spatially and temporally). Data uncertainty is sometimes referred to as reducible uncertainty because it can be minimized with further study (EPA 1997). Accordingly, variability is referred to as irreducible because it can be better characterized and represented but not reduced with further study (EPA 1997).

模型应用匹配性是指模型的科学使用的基本条件。应用匹配的不确定性是在一组特殊条件下模型应用恰当性的函数。在已有的模型中选择单个模型或从很多不同时间或空间分辨率模型中选择模型进行耦合时，应用的匹配的不确定性是特别需要注意的（Levins 1992）。

SAB's对MMSOILS(Multimedia Contaminant Fate, Transport and Exposure Model)的综述中提供了有关应用匹配不确定性的案例。SAB质疑使用筛选模型去概化大量的地表异质性特征条件或非水相污染物存在是否合理。SAB认同MMSOILS 模型在其原始开发背景下的应用，但是否定了其在异质条件下的应用。

> A model’s application niche is the set of conditions under which use of the model is scientifically defensible (EPA 1994b). Application niche uncertainty is therefore a function of the appropriateness of a model for use under a specific set of conditions. Application niche uncertainty is particularly important when (a) choosing among existing models for an application that lies outside the system for which the models were originally developed and/or (b) developing a larger model from several existing models with different spatial or temporal scales (Levins 1992).
> The SAB’s review of MMSOILS (Multimedia Contaminant Fate, Transport and Exposure Model) provides a good example of application niche uncertainty. The SAB questioned the adequacy of using a screening- level model to characterize situations where there is substantial subsurface heterogeneity or where non- aqueous phase contaminants are present (conditions differ from default values) (SAB 1993b). The SAB considered the MMSOILS model acceptable within its original application niche, but unsuitable for more heterogeneous conditions.

#### 4.2.3.2 校准及验证 
    本节主要讲述模型的验证，模型验证是评估模型表现重要的过程。

模型和观测是处于相互依赖的关系，这种关系极其复杂，存在递进迭代的关系。观测提供了概念模型的基础和促进模型的开发，以及参数的估计。观测也是验证模型的重要要素。在模型开发完成后，模型能够对于观测数据用于修改已经存在的模型，还是开发新的模型做出判断。观测和模型的处理是独立进行的……虽然环境数据系统应用广泛，如能力评估，变化趋势分析、基础研究，但是在监督管理过程发挥出模型的功能需要观测和模型的很好的融合。依靠模型和观测的迭代的自适应策略，在2003 NRC 报告“Adaptive Monitoring and Assessment for the Comprehensive Everglades Restoration Plan”有详细叙述，并提供了如何提高两者的协调性。
-— NRC Committee on Models in the Regulatory Decision Process (NRC 2007)
>The interdependence of models and measurements is complex and iterative for several reasons. Measurements help to provide the conceptual basis of a model and inform model development, including parameter estimation. Measurements are also a critical tool for corroborating model results. Once developed, models can derive priorities for measurements that ultimately get used in modifying existing models or in developing new ones. Measurement and model activities are often conducted in isolation…Although environmental data systems serve a range of purposes, including compliance assessment, monitoring of trends in indicators, and basic research performance, the importance of models in the regulatory process requires measurements and models to be better integrated. Adaptive strategies that rely on iterations of measurements and modeling, such as those discussed in the 2003 NRC report titled Adaptive Monitoring and Assessment for the Comprehensive Everglades Restoration Plan, provide examples of how improved coordination might be achieved.
— NRC Committee on Models in the Regulatory Decision Process (NRC 2007)

模型的验证包括了定性和定量的两方面的方法，用于评估模型和实际的匹配程度。这些方法的要求是依据模型的类型和应用来确定的。定量的模型验证使用统计学方法去计算模型模拟结果和实测数据的匹配程度。而定量的验证一般为专家问询模型在数据缺乏情形下的表现来评估。这些验证过程推动模型预测符合一致性。

>Model corroboration includes all quantitative and qualitative methods for evaluating the degree to which a model corresponds to reality. The rigor of these methods varies depending on the type and purpose of the model application. Quantitative model corroboration uses statistics to estimate how closely the model results match measurements made in the real system. Qualitative corroboration activities may include expert elicitation to obtain beliefs about a system’s behavior in a data-poor situation. These corroboration activities may move model forecasts toward consensus.


对于新开发的模型框架或未经测试的数学过程，推荐采用正规的验证过程。正规的验证可能涉及的过程有，针对模型验收的假设的公式测试，验证数据集的独立性测试和定量测试准则。许多案例中，获取用于正式模型验证的独立的验证数据集是非常昂贵或不可能的，这种情况下，模型的评估可能需要采用本节后续介绍的其他评估工具的组合分析。

>For newly developed model frameworks or untested mathematical processes, formal corroboration procedures may be appropriate. Formal corroboration may involve formulation of hypothesis tests for model acceptance, tests on datasets independent of the calibration dataset, and quantitative testing criteria. In many cases, collecting independent datasets for formal model corroboration is extremely costly or otherwise unfeasible. In such circumstances, model evaluation may be appropriately conducted using a combination of other evaluation tools discussed in this section.

鲁棒性（Robustness)是表达模型对于不同设计的环境条件下表现同等的好的特征（Reckhow 1994；Borsuk et al.2002)。用于验证和校准的数据集的相似度某种程度上可用来分析模型鲁棒性。例如，如果用于验证模型的的数据集与校准模型的数据集统计学上相似或基本一致，那么验证的过程就不能确认模型校准的表现，且不能帮助确定模型的鲁棒性。反之，当验证数据集和校准数据集显著不同时，验证过程则能确认模型的表现和鲁棒性。

>Robustness is the capacity of a model to perform equally well across the full range of environmental conditions for which it was designed (Reckhow 1994; Borsuk et al. 2002). The degree of similarity among datasets available for calibration and corroboration provides insight into a model’s robustness. For example, if the dataset used to corroborate a model is identical or statistically similar to the dataset used to calibrate the model, then the corroboration exercise has provided neither an independent measure of the model’s performance nor insight into the model’s robustness. Conversely, when corroboration data are significantly different from calibration data, the corroboration exercise provides a measure of both model performance and robustness.

对于同样应用需求中，在多个模型中选择可用模型时，推荐采用定量模型的验证方法。如，模型通过观测值和模拟值的差异的统计学上的表现进行排名进而选择（e.g.,EPA 1992)。EPA的空气和辐射部门经常这样操作。在发现某个模型表现比给定的其他模型明显要好时，OAR则推荐该模型作为空气质量模型导则中的优先应用模型（EPA 2003a).如果模型表现基本一致，则要通过其他因素诸如历史应用、使用的广泛性、资源需求等来进行对比选择。
>Quantitative model corroboration methods are recommended for choosing among multiple models that are available for the same application. In such cases, models may be ranked on the basis of their statistical performance in comparison to the observational data (e.g., EPA 1992). EPA’s Office of Air and Radiation evaluates models in this manner. When a single model is found to perform better than others in a given category, OAR recommends it in the Guidelines on Air Quality Models as a preferred model for application in that category (EPA 2003a). If models perform similarly, then the preferred model is selected based on other factors, such as past use, public familiarity, cost or resource requirements, and availability.

模型的验证模型评估的重要过程，通常情况下，我们模型经过一套数据校准后，要用另外一套数据来进行验证，这套数据最好与校准所用数据有显著的不同，这样一方面能够让我们确认模型的校准的准确性，同时能够确认模型的鲁棒性（适用性），而显著不同，这里就有不同的要求，比如水质模型一般回选择多年的，如果采用枯水年校准，一般选择丰水年验证，再选择另外一年进行二次验证，从而确定模型参数的合理性。

---

>Box 8: Example: Comparing Results from Models of Varying Complexity
(From Box 5-4 in NRC ’s Models in Environmental Regulatory Decision Making)
The Clean Air Mercury Rule requires industry to reduce mercury emissions from coal-fired power plants. A potential benefit is the reduced human exposure and related health impacts from methylmercury that may result from reduced concentrations of this toxin in fish. Many challenges and uncertainties affect assessment of this benefit. In its assessment of the benefits and costs of this rule, EPA used multiple models to examine how changes in atmospheric deposition would affect mercury concentrations in fish, and applied the models to assess some of the uncertainties associated with the model results (EPA 2005).
EPA based its national-scale benefits assessment on results from the mercury maps (MMaps) model. This model assumes a linear, steady-state relationship between atmospheric deposition of mercury and mercury concentrations in fish, and thus assumes that a 50% reduction in mercury deposition rates results in a 50% decrease in fish mercury concentrations. In addition, MMaps assumes instantaneous adjustment of aquatic systems and their ecosystems to changes in deposition — that is, no time lag in the conversion of mercury to methylmercury and its bioaccumulation in fish. MMaps also does not deal with sources of mercury other than those from atmospheric deposition. Despite those limitations, the Agency concluded that no other available model was capable of performing a national-scale assessment.
To further investigate fish mercury concentrations and to assess the effects of MMaps ’ assumptions, EPA applied more detailed models, including the spreadsheet-based ecological risk assessment for the fate of mercury (SERAFM) model, to five well-characterized ecosystems. Unlike the steady-state MMaps model, SERAFM is a dynamic model which calculates the temporal response of mercury concentrations in fish tissues to changes in mercury loading. It includes multiple land-use types for representing watershed loadings of mercury through soil erosion and runoff. SERAFM partitions mercury among multiple compartments and phases, including aqueous phase, abiotic participles (for example, silts), and biotic particles (for example, phytoplankton). Comparisons of SERAFM’s predictions with observed fish mercury concentrations for a single fish species in four ecosystems showed that the model under- predicted mean concentrations for one water body, over-predicted mean concentrations for a second water body, and accurately predicted mean concentrations for the other two. The error bars for the observed fish mercury concentrations in these four ecosystems were large, making it difficult to assess the models’ accuracy. Modeling the four ecosystems also showed how the assumed physical and chemical characteristics of the specific ecosystem affected absolute fish mercury concentrations and the length of time before fish mercury concentrations reached steady state.
Although EPA concluded that the best available science supports the assumption of a linear relationship between atmospheric deposition and fish mercury concentrations for broad-scale use, the more detailed ecosystem modeling demonstrated that individual ecosystems were highly sensitive to uncertainties in model parameters. The Agency also noted that many of the model uncertainties could not be quantified. Although the case studies covered the bulk of the key environmental characteristics, EPA found that extrapolating the individual ecosystem case studies to account for the variability in ecosystems across the country indicated that those case studies might not represent extreme conditions that could influence how atmospheric mercury deposition affected fish mercury concentrations in a water body.
This example illustrates the usefulness of investigating a variety of models at varying levels of complexity.
hierarchical modeling approach, such as that used in the mercury analysis, can provide justification for simplified model assumptions or potentially provide evidence for a consistent bias that would negate the assumption that a simple model is appropriate for broad-scale application.

#### 4.2.3.3 敏感性和不确定性分析 
    介绍敏感性和不确定性。

敏感性分析是研究模型的输入改变后其的响应过程（Saltelli et al.2000a)。敏感性分析是一种推荐的工具，用于将环境模型的中的最重要的和最不重要的不确定因素特征化。
>Sensitivity analysis is the study of how a model’s response can be apportioned to changes in model inputs (Saltelli et al. 2000a). Sensitivity analysis is recommended as the principal evaluation tool for characterizing the most and least important sources of uncertainty in environmental models.

不确定分析研究模型参数的真实值或未知的概率分布。不确定性有时候可以通过收集额外的数据和深入研究减小。EPA 导则（e.g. ,EPA 1997)将不确定性按照其考虑输入数据变异性还是模型参数分为两种类型。之前提到的，模型参数和输入数据的变异性能够通过深入研究来更好的特征化，但是通常其并不能被减小（EPA 1997)。
>Uncertainty analysis investigates the lack of knowledge about a certain population or the real value of model parameters. Uncertainty can sometimes be reduced through further study and by collecting additional data. EPA guidance (e.g., EPA 1997) distinguishes uncertainty analysis from methods used to account for variability in input data and model parameters. As mentioned earlier, variability in model parameters and input data can be better characterized through further study but is usually not reducible (EPA 1997).

虽然敏感性和不确定性有一定的相关性，但是敏感性是有关模型变量的“算法特性”，而不确定性则是参数的特性。敏感性分析评估的是模型的对特定参数的“敏感性”，而不确定性分析则是评估有关参数的“不确定性”。两种类型的分析对于增加用户对模型结果的确信度都是非常重要的。不确定性分析和敏感性分析的方法在附录D讨论。
> Although sensitivity and uncertainty analysis are closely related, sensitivity is algorithm-specific with respect to model “variables” and uncertainty is parameter-specific. Sensitivity analysis assesses the “sensitivity” of the model to specific parameters and uncertainty analysis assesses the “uncertainty” associated with parameter values. Both types of analyses are important to understand the degree of confidence a user can place in the model results. Recommended techniques for conducting uncertainty and sensitivity analysis are discussed in Appendix D.

NRC 委员会指出不确定性分析不仅要考虑环境管理模型本身，而且也要与政策制定者交流不确定性。为促进模型不确定性的沟通，委员会推荐采用考虑未知量为随机变量和决策制定者通过列出一系列可能的值进行情景分析的混合方法。
>The NRC committee pointed out that uncertainty analysis for regulatory environmental modeling involves not only analyzing uncertainty, but also communicating the uncertainties to policy makers. To facilitate communication of model uncertainty, the committee recommends using hybrid approaches in which unknown quantities are treated probabilistically and explored in scenario-assessment mode by decision makers through a range of plausible values. The committee further acknowledges (NRC 2007) that:

委员会进一步说明（NRC 2007)：
有效的不确定性交流需要与相关的决策人员深度的沟通交流，去确保他们明白有关不确定性的来源和特点，以及不确定可能造成的影响的必要信息。也就是说，环境管理的不确定性分析的表现需要分析和决策制定者广泛的讨论。
Effective uncertainty communication requires a high level of interaction with the relevant decision
makers to ensure that they have the necessary information about the nature and sources of uncertainty and their consequences. Thus, performing uncertainty analysis for environmental regulatory activities requires extensive discussion between analysts and decision makers.

---
本小节内容比较少，导则的内容主要介绍思路，具体的方法还在附录中，也就是其仅仅说要注意什么内容，本节简要介绍了敏感性分析和不确定性分析，两者都是模型评估的重要的量化手段，其中不确定性分析尤其重要，不确定性我们也介绍很多遍了，这里定义不再赘述，不确定性就是你对模型模拟的结果的确信程度，你有多大把握你给出的结果是正确的。这点非常重要？为什么？

因为对于模型从业者来说，遇到的最大的问题就是模型准不准？如果不准，有啥用？经常听到有很多不同领域的模型玩家，在评审时被专家问住：“你的模型结果效果渲染很酷，也非常清晰，那么我想知道你的模型准么？”，通常这时候，很多人底气一下子就不足了，虽然自己踏实的做出来的，但是自己也不知道准不准。

那么，不确定性就是一种解药，只要是模型就有误差，这是模型本身存在不可回避的本质属性，但是我们能通过不确定性分析来增加我们模型结果的可靠度，比如，我最后给出的模型结果不是一个具体的值，而是不确定分析下的一个范围，或者不同值出现的概率，这样，我就能够很有底气的去回答模型准不准的问题。

没人能试图准确预测未来，但是我们能够利用各种工具来尽可能合理应对未来。

4.2节翻译完了，这节内容丰富，如何评估模型，是使用者需要关注的，也是建模者需要关注的，甚至所有人都需要关注的，我们现在的模型大部分都是缺失这部分工作的，从而导致模型的应用受限，我们要转变观念，将模型作为工具，让其帮助我们更好的决策。

---

参考文献：
[1] Gaber N, Foley G, Pascual P, et al. Guidance on the development, evaluation, and application of environmental models[J]. Report, Council for Regulatory Environmental Modeling, 2009, 81.

![页尾](http://comieswater-1254012817.cossh.myqcloud.com/页尾识别new-2017-09-22.png)
微信公众号 | 水环境编Cheng长
网          站 | comieswater.com


![赞赏我](http://comieswater-1254012817.cossh.myqcloud.com/IMG_3077.JPG)

2019-1-27
