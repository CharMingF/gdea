---
title: 《模型开发、评估、应用导则》批注：第三章(4)
tags: 1000天持续行动,GDEA
date:   2018-8-29
---

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

### 3.3.1 模型复杂度
    模型复杂度会影响模型的不确定性，实际过程中应该综合考虑模型的架构和数据的不确定性，综合的确定出最恰当的复杂度。
在明确目标及问题的阶段中，团队就应该考虑模型的复杂度。模型复杂度会影响不确定性，不管模型朝着复杂还是简单的方向发展，其的不确定性都会变化。换句话说，在选择比较多种模型架构或者决定使用现有合适的模型时，模型复杂度都是一个重要的评判因素。通常情况下，最优的模型选择是在满足决策需求条件下尽可能简单的模型。基于此理由，在开发新的模型框架时，也应该考虑模型的复杂性。
>During the problem specification stage, the project team will have considered the degree of complexity desired for the model (see Section 3.2.2). As described below, model complexity influences uncertainty. Models tend to uncertainty as they become increasingly simple or increasingly complex. Thus complexity is an important parameter to consider when choosing among competing model frameworks or determining the suitability of the existing model framework to the problem of concern. For the reasons described below, the optimal choice generally is a model that is no more complicated than necessary to inform the regulatory decision. For the same reasons, model complexity is an essential parameter to consider when developing a new model framework.

在对特定的因素、参数（输入）或模型的理解不够完善时，不确定性就会存在。模型的不确定性主要来自于两类：
1. 模型架构的不确定性。该不确定性为模型的背后的科学机理的函数，也就是受模型的方程影响，理论上越多机理的表达，不确定性越小。
2. 数据的不确定性。其来自于采集或者处理数据用于量化模型参数时由测量误差、有限的样本量，分析精度等带来的不确定性。

这两种类型的不确定性有着内在负相关性，其中一个增加时，另外一个则会减少。也就是说，如下图所示，对于每个模型来说都有最优的复杂度。
        
对模型的不确定的考虑是增加模型可信度的重要的工作，这里需要解释下上述两者的关系，模型架构的不确定性，主要是单纯的从模型表达的角度分析，对于复杂度高的模型，由于其表达的过程相对充分，那么其内在的不确定就相对小。但是我们知道，越复杂的模型其变量越多，参数相应的会增多，确定这些参数则需要引入更多的信息，这些信息来自于数据中，越多的数据当然可以更好的用于消除架构上的不确定性，但是我们的数据内在由于误差等存在，其本身也包含一定的不确定性。这就是形成了一对矛盾的过程了。具体可参考之前的一篇文章：[水质模型的构建(3)](https://mp.weixin.qq.com/s?__biz=MjM5Mzg1MzEyOA==&mid=2247484282&idx=1&sn=aebf1d47a39b1575731e26d9c4e74904&chksm=a691f8dd91e671cb75b0335bea9c169383241a16a15fd75cd3572d499bcb3077f842730514ee&mpshare=1&scene=23&srcid=0513fDhTwyHfYVTskoliMy59#rd)
>Uncertainty exists when knowledge about specific factors, parameters (inputs), or models is incomplete. Models have two fundamental types of uncertainty:
>- Model framework uncertainty, which is a function of the soundness of the model’s underlying scientific foundations.
>- Data uncertainty, which arises from measurement errors, analytical imprecision, and limited sample size during collection and treatment of the data used to characterize the model parameters.
>  These two types of uncertainty have a reciprocal relationship, with one increasing as the other decreases. Thus, as illustrated in Figure 3, an optimal level of complexity (the “point of minimum uncertainty”) exists for every model.

![不确定性曲线](http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1535727490548.png)

例如，对于对于空气质量模型，有时候需要在模型可以表达的多个物理过程中妥协。如果目标为预测一个或多个源附近的污染物浓度值，那么化学过程可以被忽略，因为在污染源和受体时间的距离太短，这样的距离对于化学过程来说尺度太小，其对污染物浓度的影响微乎其微。但是，在这种情况下，其他的因素如果对污染物浓度有较大的影响，则必须在模型中表达出来。诸如，建筑物的分布，污染源释放条件的初始特征，扩散速率以及污染物向下风口迁移，羽流等。反之，若目标为预测距离排放口远端污染物浓度时，化学过程变得至关重要了，因为有更充分的时间进行化学反应过程，这时候由于污染物随着大气层迁移输运，所以源的初始释放影响变的很小。到现在为止，同时考虑近区和远区两者的模拟，在当前台式计算机上计算是非常慢的。

>For example, air quality modelers must sometimes compromise when choosing among the physical processes that will be treated explicitly in the model. If the objective is to estimate the pattern of pollutant concentration values near one (or several) source(s), then chemistry is typically of little importance because the distances between the pollutant source and receptor are generally too short for chemical formation and destruction to greatly affect pollutant concentrations. However, in such situations, other factors tend to have a significant effect and must be properly accounted for in the model. These may include building wakes, initial characterization of source release conditions and size, rates of diffusion of pollutants released as they are transported downwind, and land use effects on plume transport. Conversely, when the objective is to estimate pollutant concentrations further from the source, chemistry becomes more important because there is more time for chemical reactions to take place, and initial source release effects become less important because the pollutants become well-mixed as they travel through the atmosphere. To date, attempts to model both near-field dispersion effects and chemistry have been inefficient and slow on desktop computers.

由于上述这些竞争性目标的存在，对假设的简化及成本上需要慎重考虑。如图3描述，随着模型的纳入的物理过程的增加，其复杂度相应增加，就像需要更多的输入数据（复杂度增加意味着模型需要更多的方程来表达其过程，必然引入较多的参数和数据需求），从而导致引入了更多数据方面的不确定性，进而可能使得模型整体的表现降低。不同的模型包含不同类型的不确定性，所以在模型开发阶段早期就对模型进行**敏感性**分析是非常有用的，敏感性分析是为了区分出模型不同参数的重要程度，其是在模型输入或假设条件（包括边界条件和模型方程形式）改变后对模型输出的影响程度（Morgan and Henrion 1990)。


>
>Because of these competing objectives, parsimony (economy or simplicity of assumptions) is desirable in a model. As Figure 3 illustrates, as models become more complex to treat more physical processes, their performance tends to degrade because they require more input variables, leading to greater data uncertainty. Because different models contain different types and ranges of uncertainty, it can useful to conduct sensitivity analysis early in the model development phase to identify the relative importance of model parameters. Sensitivity analysis is the process of determining how changes in the model input values or assumptions (including boundaries and model functional form) affect the model outputs (Morgan and Henrion 1990).

在敏感性分析（第四章及附录D）后如果某些参数对输出影响不大，亦或该参数并没有合理的过程来表达，那么模型可以减少参数数量而降低其复杂度。但是，一个在某些应用场景下影响不大的参数可能在另一些应用场景影响非常大，也就是说不同参数在不同模型中表现不同，这点尤其要注意，具体问题具体分析。在过去部门对模型复盘时，SAB为了透明，其所总结的复杂模型简化导则（SAB 1988)，但是其也强调了对基于过程的重要参数的消除要特别谨慎，因为数据是不够全面或者很难获取到（SAB 1989)。在任何情况下，可获取到的数据的质量及分辨率最终都会限制将要使用的模型类型。也就是说，一定要定义现有的数据和后续的数据监测能否足够用于模型的参数化表达，支撑模型的运行。NRC的模型委员会在管理决策过程方案中推荐的做法是，模型的复杂度在满足决策支撑即可，同时也要尽可能忽略那些对并不能大幅提高模型表现的功能（NRC 2007)。

>Model complexity can be constrained by eliminating parameters when sensitivity analyses (Chapter 4/Appendix D) show that they do not significantly affect the outputs and when there is no process-based rationale for including them. However, a variable of little significance in one application of a model may be more important in a different application. In past reviews of Agency models, the SAB has supported the general guiding principle of simplifying complex models, where possible, for the sake of transparency (SAB 1988), but has emphasized that care should be taken not to eliminate important parameters from process-based models simply because data are unavailable or difficult to obtain (SAB 1989). In any case, the quality and resolution of available data will ultimately constrain the type of model that can be applied. Hence, it is important to identify the existing data and and/or field collection efforts that are needed to adequately parameterize the model framework and support the application of a model. The NRC Committee on Models in the Regulatory Decision Process recommended that models used in the regulatory process should be no more complicated than is necessary to inform regulatory decision and that it is often preferable to omit capabilities that do not substantially improve model performance (NRC 2007).



### 3.3.2 模型编程和验证
编程的过程为将模型的数学方程利用编程语言表达出来，以便通过计算机数值求解。代码的验证为检查代码是否有内在的数值方面问题导致无法求解，要根据其设计的标准进行测试其是否能够正常运行。验证过程应该包括检查计算编程语言的数值问题，以及概念模型和主要控制方程的一致性（Beck et al.1994)。在模型被完全开发出来后，代码的独立性测试作为额外的完整性和质量检查是非常有用的。

> Model coding translates the mathematical equations that constitute the model framework into functioning computer code. Code verification ascertains that the computer code has no inherent numerical problems with obtaining a solution. Code verification tests whether the code performs according to its design specifications. It should include an examination of the numerical technique in the computer code for consistency with the conceptual model and governing equations (Beck et al. 1994). Independent testing of the code once it is fully developed can be useful as an additional check of integrity and quality.

下面这些步骤对于减少代码错误和促进代码验证过程：
1. 编程过程要使用注释行去描述每一部分的目的。这有助于未来修订过程及其他模型者改进模型。
2. 在概念模型开发阶段，采用流程图来表达主要环节。在编程开始时，者有助于展现模型程序的全视角的结构，为模型的每一步的计算过程提供了简单的描述。

>Several early steps can help minimize later programming errors and facilitate the code verification process. For example:
>- Using “comment” lines to describe the purpose of each component within the code during development makes future revisions and improvements by different modelers and programmers more efficient.
>- Using a flow chart when the conceptual model is developed and before coding begins helps show the overall structure of the model program. This provides a simplified description of the calculations that will be performed in each step of the model.

在封装模型时，考虑到模型行为，将模型/程序分解为若干部分或者模块化也是一种非常有用的方法。这使得模型使用者能够去分别测试每个子模块的行为，加快了测试的速度，从而增强了编程团队的信心。模块是指一个或者更大的软件中独立的一个子模块。相对于直接对大模块进行操作，将大型模块分解为多个小模块，有助于模型的测试和查错（定位和修正错误）。分解的模块也很容易在未来的其他模型项目中进行复用，更新，增强功能或移除而不需要改动全局的模型架构。

>Breaking the program/model into component parts or modules is also useful for careful consideration of model behavior in an encapsulated way. This allows the modeler to test the behavior of each sub- component separately, expediting testing and increasing confidence in the program. A module is an independent piece of software that forms part of one or more larger programs. Breaking large models into discrete modules facilitates testing and debugging (locating/correcting errors) compared to large programs. The approach also makes it easier to re-use relevant modules in future modeling projects, or to update, add, or remove sections of the model without altering the overall program structure.

在一般任务中采用通用算法能够节省时间和资源，从而能够将更多的精力放在开发和改进模型新需求的内容。算法是用来解决问题的一个（一系列）精确的规则。通用算法通常会作为开源代码发表（e.g. Press 1992）。开发者能够学习使用机构的模块和代码去避免重新造轮子。CREM模块基础知识包含了模块的网络目录，提供了很多模型的资源。
>Use of generic algorithms for common tasks can often save time and resources, allowing efforts to focus on developing and improving the original aspects of a new model. An algorithm is a precise rule (or set of rules) for solving some problem. Commonly used algorithms are often published as “recipes” with publicly available code (e.g., Press 1992). Developers should review existing Agency models and code to minimize duplication of effort. The CREM models knowledge base, which will contain a Web- accessible inventory of models, will provide a resource model developers can use for this purpose.

软件工程在最近几年飞速的发展，并在技术和平台领域快速的进步。例如，在过去推荐的通用开发语言中没有使用面向对象的平台进行开发，而如今已经采用了。面向对象的平台模型系统使用了操作对象的指令集。这些对象作为类的实例继承对象的特性，类是一系列共享行为和架构的对象。类的架构是由类的变量决定，其用来声明类的对象；同时其通过类的一系列方法来进行操作（Booch 1994）。模型通过面向对象的平台开发时，用户应该输出平台生成实际的数学关系，作为代码验证的一部分。
>Software engineering has evolved rapidly in recent years and continues to advance rapidly with changes in technology and user platforms. For example, some of the general recommendations for developing computer code given above do not apply to models that are developed using object-oriented platforms. Object-oriented platform model systems use a collection of cooperating “objects.” These objects are treated as instances of a class within a class hierarchy, where a class is a set of objects that share a common structure and behavior. The structure of a class is determined by the class variables, which represent the state of an object of that class; the behavior is given by the set of methods associated with the class (Booch 1994). When models are developed with object-oriented platforms, the user should print out the actual mathematical relationships the platform generates and review them as part of the code validation process.

关于编程风格和约定有非常多的参考资料，其提供了很多针对模型开发和测试特定技术建议。（例如，The Elements of Programming Style [ Kernigham and Plaugher 1988 ]）。另外，Guidance for Quality Assurance Project Plans for Modeling (EPA 2002b) 也有很多有关代码验证的实践，对于其遵循特定更多QA计划（见附录C，BOX C2）。

>Many references on programming style and conventions provide specific, technical suggestions for developing and testing computer code (e.g., The Elements of Programming Style [Kernigham and Plaugher 1988]). In addition, the Guidance for Quality Assurance Project Plans for Modeling (EPA 2002b) suggests a number of practices during code verification to “check” how well it follows the “specifications” laid out during QA planning (Appendix C, Box C2: Configuration Tests Specified in the QA Program).

参考文献：
[1] Gaber N, Foley G, Pascual P, et al. Guidance on the development, evaluation, and application of environmental models[J]. Report, Council for Regulatory Environmental Modeling, 2009, 81.


![页尾](http://comieswater-1254012817.cossh.myqcloud.com/页尾识别new-2017-09-22.png)
微信公众号 | 水环境编Cheng长
网          站 | comieswater.com


![赞赏我](http://comieswater-1254012817.cossh.myqcloud.com/IMG_3077.JPG)

 2018-8-16

