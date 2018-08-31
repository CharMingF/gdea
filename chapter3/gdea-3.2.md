---
title: 《模型开发、评估、应用导则》批注：第三章(2)
tags: 1000天持续行动,GDEA
date:   2018-8-25
---
·[474]|1000天行动计划
**读书笔记**/热点追踪/论文研读/教程手册

![封面](http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1534259099598.png)

## 3.2  问题的提出和概念模型开发

问题及目标的明确，作为概念模型开发的重要前置步骤，需要在模型开发者，使用者及决策制定者之间反复的沟通讨论，确保问题的各个方面有清晰的界定，因为这影响着后续一系列选择或模型的框架开发。为了清晰的建立整个模拟过程的目标，模型开发者和使用者之间的沟通是十分重要的。这个阶段模糊的目标会影响整个项目的成功率（Manno et al.2008)。

在定义问题的阶段，项目方需要定义管理和研究的目标，模型的类型和适用范围除了去适配这些目标外，还需要考虑数据标准、模型的应用领域以及任何程序上的限制。上述所有为概念模型开发的基础，概念模型描绘、叙述了系统行为、目标及关注问题的关键点。

明确问题及概念模型定义了模型的需求，整个项目团队能够以此决定是否现有模型能够用于去满足需求或者需要开发新的模型去实现。

>Problem specification, culminating in development of the conceptual model, involves an iterative, collaborative effort among model developers, intended users, and decision makers (the project team) to specify all aspects of the problem that will inform subsequent selection or development of a model framework. Communication between model developers and model users is crucial to clearly establish the objectives of the modeling process; ambiguity at this stage can undermine the chances for success (Manno et al. 2008).
>During problem specification, the project team defines the regulatory or research objectives, the type and scope of model best suited to meet those objectives, the data criteria, the model’s domain of applicability, and any programmatic constraints. These considerations provide the basis for developing a conceptual model, which depicts or describes the most important behaviors of the system, object, or process relevant to the problem of interest. Problem specification and the resulting conceptual model define the modeling needs sufficiently that the project team can then determine whether an existing model can be used to meet those needs or whether a new model should be developed.


这部分对整个3.2节进行了概述，模型开发最重要优先级最高的步骤为明确问题（涉及问题、目标界定等），这个实际上并不是什么需要强调的，这个步骤在所有的工程项目中都有明确的项目目标，但是对于涉及模型的项目来说，这点就不是那么清晰了，我们究竟要模型来做什么？做到什么程度，实现什么样的结果？如何量化等等，回答这些都需要很深入的模型项目经验。

### 3.2.1 确定目标
明确问题的第一步就是定义管理和研究目标（如模型需要去回答什么问题）。团队完成这些内容应该有一个模型目标的文档，文档内容包括关注的变量（如水质指标、流量、费用等），变量的驱动力，恰当的时空尺度，模型所需要的精度等。

### 3.2.2 确定所需模型的类型及适用范围
模型有很多不同的类型，如经验模型vs机理模型，静态模型vs动态模型，模拟vs优化，确定性模型vs不确定性模型，集总式vs分布式。为了选取能够解决问题的最适合的模型，项目团队应该充分讨论和对比分析。

依据问题和数据及其他因素，特定应用的模型的适用范围（包括时空和过程细节）从简单到复杂变化。考虑到不同类型的模型适用于不同的问题，通常采用分级的方法来选择和开发模型，为得到可靠的模型结果提供模型的适用范围、合理性和复杂性的选择。3.3.1 节提供了如何考虑模型复杂度的内容。

>Many different types of models are available, including empirical vs. mechanistic, static vs. dynamic, simulation vs. optimization, deterministic vs. stochastic, and lumped vs. distributed. The project team should discuss and compare alternatives with respect to their ability to meet the objectives in order to determine the most appropriate type of model for addressing the problem.

>The scope (i.e., spatial, temporal and process detail) of models that can be used for a particular application can range from very simple to very complex depending on the problem specification and data availability, among other factors. When different types of models may be appropriate for solving different problems, a graded approach should be used to select or develop models that will provide the scope, rigor, and complexity appropriate to the intended use of and confidence needed in the results. Section 3.3.1 provides more information on considerations regarding model complexity.



### 3.2.3 数据质量标准
这步骤主要是针对数据质量目标（Data quality objectives，DQOs）和确定不确定性的允许范围。DQOs（EPA 2000a）提供了模型质量和其相关的检查的规范标准（见附录C，框图C1，EPA质量控制系统的背景）。一个完美的DQOs，数据质量目标能够有效的引导监测计划的设置和模型开发的过程实施（例如，校准和验证）。在限制了*决策误差*（第一类错误和第二类错误，统计中的术语）时，DQOs为怎么样提出变量需求提供了很好的思路。
	1、第一类错误又称Ⅰ型错误、拒真错误，是指拒绝了实际上成立的、正确的假设，为“弃真”的错误，其概率通常用α表示。假设检验是反证法的思想，依据样本统计量作出的统计推断，其推断结论并非绝对正确，结论有时也可能有错误，错误分为两类。
	2、第二类错误，Ⅱ型错误，接受了实际上不成立的H0 ，也就是错误地判为无差别，这类取伪的错误称为第二类错误，其概率用β表示。简单说就是：你的假设是错误，但你接受该假设。

DQOs应该包括对于模型结果用于目标时的总的不确定性的接受程度的声明（附录C，框图C2）。不确定性描述了有关模型可能缺失的机理，参数和变量及数据的可信度。明确定义出水量或水质的不确定性的容忍范围，能够有效的帮助工程计划者去制定**质量保证计划**和设置恰当的边界条件以及模型开发的复杂度的规范。

>This step includes developing data quality objectives (DQOs) and specifying the acceptable range of uncertainty. DQOs (EPA 2000a) provide specifications for model quality and associated checks (see Appendix C, Box C1: Background on EPA Quality System). Well-defined DQOs guide the design of monitoring plans and the model development process (e.g., calibration and verification). The DQOs provide guidance on how to state data needs when limiting decision errors (false positives or false negatives) relative to a given decision. The DQOs should include a statement about the acceptable level of total uncertainty that will still enable model results to be used for the intended purpose (Appendix C, Box C2: Configuration Tests Specified in the QA Program). Uncertainty describes the lack of knowledge about models, parameters, constants, data, and beliefs. Defining the ranges of acceptable uncertainty — either qualitatively or quantitatively — helps project planners generate “specifications” for quality assurance planning and partially determines the appropriate boundary conditions and complexity for the model being developed.

### 3.2.4 模型应用域
这里的域并非仅仅为空间上的区域，而是整个模型的domain，包括模型的机理、动力学等。
为了能够选择恰当的模型，工程团队必须理解模型的应用域，如在使得模型具备科学性的一组条件或者系统的哪些特点要通过模型表达。这涉及到定义模型模拟的的环境域，指定在域范围内的动力学过程和边界条件，如与政策\管理\研究目标相关的输运及转换过程，目标及问题需要的输运和转化的时间和空间尺度，以及其他特殊的影响模型选择和模型构建的域条件。

>To select an appropriate model, the project team must understand the model’s domain of applicability — i.e., the set of conditions under which use of the model is scientifically defensible and the relevant characteristics of the system to be modeled. This involves identifying the environmental domain to be modeled and then specifying the processes and conditions within that domain, including the transport and transformation processes relevant to the policy/management/research objectives, the important time and space scales inherent in transport and transformation processes within that domain in comparison to the time and space scales of the problem objectives, and any peculiar conditions of the domain that will affect model selection or new model construction.

### 3.2.5 编程限制讨论
在这个阶段中，工程团队也需要去考虑任何模型的限制因素。包括项目周期及费用，数据可获得性，获取更多的数据需要的资源，法规及制度因素，计算资源限制，模型人员的经验和专业程度等。

>At this stage, the project team also needs to consider any factors that could constrain the modeling process. This discussion should include considerations of time and budget, available data or resources to acquire more data, legal and institutional factors, computer resource constraints, and the experience and expertise of the modeling staff.

### 3.2.6 开发概念模型
概念模型主要描述与问题密切相关的系统、目标及过程中的最关键的内容。开发概念模型时，模型开发者应充分参考相关文献、类似的项目、前人经验及相关的成功应用的模型工程。在开发过程中，开发者要清晰的文档（不限于文字、公式、图表、动画）来陈述概念模型的每一个要素，同时也要对每个要素背后的科学解释（如实验、数学方程，经验假设，同行文献）尽可能的进行数学形式的表达。为了扩展其灵活性，模型者还应该提供假设、尺度、反馈机制及静态/动态行为的信息，同时还有每部分的假设的优缺点，潜在影响均要描述清楚。

>A conceptual model depicts or describes the most important behaviors of the system, object, or process relevant to the problem of interest. In developing the conceptual model, the model developer may consider literature, fieldwork, applicable anecdotal evidence, and relevant historical modeling projects. The developer should clearly describe (in words, functional expressions, diagrams, and/or graphs) each element of the conceptual model and should document the science behind each element (e.g., laboratory experiments, mechanistic evidence, empirical data supporting the hypothesis, peer-reviewed literature) in mathematical form, when possible. To the extent feasible, the modeler should also provide information on assumptions, scale, feedback mechanisms, and static/dynamic behaviors. When relevant, the strengths and weaknesses of each constituent hypothesis should be described.










参考文献：
[1] Gaber N, Foley G, Pascual P, et al. Guidance on the development, evaluation, and application of environmental models[J]. Report, Council for Regulatory Environmental Modeling, 2009, 81.


![页尾](http://comieswater-1254012817.cossh.myqcloud.com/页尾识别new-2017-09-22.png)
微信公众号 | 水环境编Cheng长
网          站 | comieswater.com


![赞赏我](http://comieswater-1254012817.cossh.myqcloud.com/IMG_3077.JPG)

 2018-8-16

