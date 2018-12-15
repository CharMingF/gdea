---
title: 《模型开发、评估、应用导则》批注：第四章(1)
tags: 1000天持续行动,GDEA
date:   2018-12-15
---
·[485]|1000天行动计划
**读书笔记**/热点追踪/论文研读/教程手册
![封面](http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1534259099598.png)

# 4 模型评价
    P19，介绍模型评价的重要性，引出模型评价。


## 4.1 引言
> Models will always be constrained by computational limitations, assumptions and knowledge gaps. They can best be viewed as tools to help inform decisions rather than as machines to generate truth or make decisions. Scientific advances will never make it possible to build a perfect model that accounts for every aspect of reality or to prove that a given model is correct in all aspects for a particular regulatory application. These characteristics…suggest that model evaluation be viewed as an integral and ongoing part of the life cycle of a model, from problem formulation and model conceptualization to the development and application of a computational tool.
> — NRC Committee on Models in the Regulatory Decision Process (NRC 2007)

由于计算上的限制，前提假设及机理的缺失导致模型总是不完美的。所以，其最好将其作为一种辅助决策的工具而不能直接生成真相或用来做决策的“机器”。科学在持续不断的进步使得不可能构建出完美的模型去解释现实的方方面面，或在某方面进行管理应用时在各个方面都是正确的。这些特征使得模型评价贯穿于建模和不断改进模型的全周期中（从提出问题到开发到应用概念工具）。

>The natural complexity of environmental systems makes it difficult to mathematically describe all relevant processes, including all the intrinsic mechanisms that govern their behavior. Thus, policy makers often rely on models as tools to approximate reality when making decisions that affect environmental systems. The challenge facing model developers and users is determining when a model, despite its uncertainties, can be appropriately used to inform a decision. Model evaluation is the process used to make this determination. In this guidance, model evaluation is defined as the process used to generate information to determine whether a model and its analytical results are of a quality sufficient to serve as the basis for a decision. Model evaluation is conducted over the life cycle of the project, from development through application.

环境系统天然的复杂特性使得其很难用数学方程准确描述其内在机理的各个相关过程。也就是说，决策制定者在做出影响环境系统的决策时，经常需要依靠模型作为工具去尽可能接近真相。模型开发者和使用者需要确定什么样的模型（即使其带有不确定性）可用于去形成决策，而模型评价就是用于帮助评估模型。在这个导则中，模型评价被定义为产生信息去判定一个模型及其的结果是否靠谱，可以作为决策的基础。模型评价是贯穿整个项目周期，从开发到应用。

>In simple terms, model evaluation provides information to help answer four main questions (Beck 2002b):  
>1. How have the principles of sound science been addressed during model development?
>2. How is the choice of model supported by the quantity and quality of available data?
>3. How closely does the model approximate the real system of interest?
>4. How does the model perform the specified task while meeting the objectives set by QA project planning?  
>  These four factors address two aspects of model quality. The first factor focuses on the intrinsic mechanisms and generic properties of a model, regardless of the particular task to which it is applied. In contrast, the latter three factors are evaluated in the context of the use of a model within a specific set of conditions . Hence, it follows that model quality is an attribute that is meaningful only within the context of a specific model application. A model's quality to support a decision becomes known when information is available to assess these factors.

模型评估提供信息去帮助回答以下问题（Beck 2002b）：
1. 在模型开发过程中，可靠科学的原则如何被使用？
2. 支撑模型的数据的质量和数量如何？
3. 模型所能表达的与关注的真实系统差距有多大？
4. 针对QA工程计划的目标，模型在解决特定的需求时，表现如何？

这四个问题旨在解决模型质量的两个方面，首先，关注模型内在的机制和固有普遍特性，而不考虑其应用在特定任务下的表现。而另一方面，后三点问题则主要关注模型在特定条件下使用的表现。也就是说，认为模型质量是基于模型在特定应用情境下的一种特性。在弄清上述问题后，模型是否能够支持决策变的相对清晰。

> The NRC committee recommends that evaluation of a regulatory model continue throughout the life of a model and that an evaluation plan could:
> - Describe the model and its intended uses.
> - Describe the relationship of the model to data, including the data for both inputs and corroboration.
> - Describe how such data and other sources of information will be used to assess the ability of the model to meet its intended task.
> - Describe all the elements of the evaluation plan by using an outline or diagram that shows how the elements relate to the model’s life cycle.
> - Describe the factors or events that might trigger the need for major model revisions or the circumstances that might prompt users to seek an alternative model. These can be fairly broad and qualitative.
> - Identify the responsibilities, accountabilities, and resources needed to ensure implementation of the evaluation plan.

NRC委员会认为管理模型的评估应在模型的全部应用期，评估计划能够：
- 描述模型及其应用。
- 模型与数据的关系，包括用于输入和校准的数据。
- 描述数据和其他信息源如何被用于去支持模型实现目标任务。
- 通过使用图表展示模型的应用过程的全部评估计划的要素。
- 描述可能引起主要模型修改或者使得用户更换模型的因素和事件，这些应能够定性。
- 定义出责任、职责及资源需求去确保评估计划的执行。

>As stated above, the goal of model evaluation is to ensure model quality. At EPA, quality is defined by the Information Quality Guidelines (IQGs) (EPA 2002a). The IQGs apply to all information that EPA disseminates, including models, information from models, and input data (see Appendix C, Box C4: Definition of Quality). According to the IQGs, quality has three major components: integrity, utility, and objectivity. This chapter focuses on addressing the four questions listed above by evaluating the third component, objectivity — specifically, how to ensure the objectivity of information from models by considering their accuracy, bias, and reliability.

 模型评估的目标是确保模型的质量，在EPA，模型质量是通过IQGs(EPA 2002a)来定义。IQGs包含了EPA发布的全部信息，包括模型及从模型得出的和模型输入（见附录C）。根据IQGs，质量主要包括三个指标：完整、效用、客观。这章主要集中于之前用于评估这三个指标的四个问题，特别是根据精确性、乖离率、可靠性来如何确定从模型获取到的结论的客观性。

>Accuracy, as described in Section 2.4, is the closeness of a measured or computed value to its “true” value, where the “true” value is obtained with perfect information.
>Bias describes any systematic deviation between a measured (i.e., observed) or computed value and its “true” value. Bias is affected by faulty instrument calibration and other measurement errors, systematic errors during data collection, and sampling errors such as incomplete spatial randomization during the design of sampling programs.
>Reliability is the confidence that (potential) users have in a model and its outputs such that they are willing to use the model and accept its results (Sargent 2000). Specifically, reliability is a function of the model’s performance record and its conformance to best available, practicable science.

精确性，在2.4节已经有所描述，是表达测量值或者计算值和真实值的接近程度，真实值来源于更好的信息。

乖离则描述了测量值或计算值与真实值之间的系统性误差，可能是由于数据采集过程中未校准的仪器和其他测量误差、系统误差，还有采样设计中的诸如不完整的空间随机布设带来的采样误差。

可靠性，则为用户对模型和输出结果的信任度，即他们对模型和结果的接受程度（Sargent 2000）。可靠性是模型表现和它的历史及实践科学一致性的函数。

>This chapter describes principles, tools, and considerations for model evaluation throughout all stages of development and application. Section 4.2 presents a variety of qualitative and quantitative best practices for evaluating models. Section 4.3 discusses special considerations for evaluating proprietary models. Section 4.4 explains why retrospective analysis of models, conducted after a model has been applied, can be important to improve individual models and regulatory policies and to systematically enhance the overall modeling field. Finally, Section 4.5 describes how the evaluation process culminates in a decision whether to apply the model to decision making. Section 4.6 reviews the key recommendations from this chapter.


扩展阅读：
**Box 5: Model Evaluation Versus Validation Versus Verification**
Model evaluation should not be confused with model validation. Different disciplines assign different meanings to these terms and they are often confused. For example, Suter (1993) found that among models used for risk assessments, misconception often arises in the form of the question “Is the model valid?” and statements such as “No model should be used unless it has been validated.” Suter further points out that “validated” in this context means (a) proven to correspond exactly to reality or (b) demonstrated through experimental tests to make consistently accurate predictions.
Because every model contains simplifications, predictions derived from a model can never be completely accurate and a model can never correspond exactly to reality. In addition, “validated models ” (e.g., those that have been shown to correspond to field data) do not necessarily generate accurate predictions of reality for multiple applications (Beck 2002a). Thus, some researchers assert that no model is ever truly “validated”; models can only be invalidated for a specific application (Oreskes et al. 1994). Accordingly, this guidance focuses on process and techniques for model evaluation rather than model validation or invalidation.
“Verification” is another term commonly applied to the evaluation process. However, in this guidance and elsewhere, model verification typically refers to model code verification as defined in the model development section. For example, the NRC Committee on Models in the Regulatory Decision Process (NRC 2007) provides the following definition:
Verification refers to activities that are designed to confirm that the mathematical framework
embodied in the module is correct and that the computer code for a module is operating according
to its intended design so that the results obtained compare favorably with those obtained using
known analytical solutions or numerical solutions from simulators based on similar or identical mathematical frameworks.



参考文献：
[1] Gaber N, Foley G, Pascual P, et al. Guidance on the development, evaluation, and application of environmental models[J]. Report, Council for Regulatory Environmental Modeling, 2009, 81.


![页尾](http://comieswater-1254012817.cossh.myqcloud.com/页尾识别new-2017-09-22.png)
微信公众号 | 水环境编Cheng长
网          站 | comieswater.com


![赞赏我](http://comieswater-1254012817.cossh.myqcloud.com/IMG_3077.JPG)

 2018-12-15