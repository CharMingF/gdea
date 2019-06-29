---
title: 《模型开发、评估、应用导则》批注：附录A
tags: 1000天持续行动,GDEA
date:   2019-2-13
---

**读书笔记**/热点追踪/论文研读/教程手册
![封面](http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1534259099598.png)

# 附录A
	名词解释，附录提供了很多专业术语的定义，均是与模型相关的，学习专业英语了。

>Accuracy: The closeness of a measured or computed value to its “true” value, where the “true” value is obtained with perfect information. Due to the natural heterogeneity and stochasticity of many environmental systems, this “true” value exists as a distribution rather than a discrete value. In these cases, the “true” value will be a function of spatial and temporal aggregation.

精确度：与计算值或测量值与其”真“值的接近程度。”真值“从更好的信息源获取到的值，由于许多自然系统的异质性和随机性，“真”值一般是作为一种分布，而不是具体的离散的值。在很多案例中，“真”值是空间和时间聚集的函数。

>Algorithm: A precise rule (or set of rules) for solving some problem.

算法：解决一些问题的一系列规则。


>Analytical model: A model that can be solved mathematically in terms of analytical functions. For example, some models that are based on relatively simple differential equations can be solved analytically by combinations of polynomials, exponential, trigonometric, or other familiar functions.

解析模型：用解析函数进行数学求解的模型。例如，一些基于相对简单的微分方程的模型可以通过多项式、指数函数、三角函数或其他初级函数的组合进行解析求解。

>Applicability and utility: One of EPA’s five assessment factors (see definition) that describes the extent to which the information is relevant for the Agency’s intended use (EPA 2003b).
>Application niche: The set of conditions under which the use of a model is scientifically defensible. The identification of application niche is a key step during model development. Peer review should include an evaluation of application niche. An explicit statement of application niche helps decision makers understand the limitations of the scientific basis of the model (EPA 1993).
Application niche uncertainty: Uncertainty as to the appropriateness of a model for use under a specific set of conditions (see “application niche”).

>Assessment factors: Considerations recommended by EPA for evaluating the quality and relevance of scientific and technical information. The five assessment factors are soundness, applicability and utility, clarity and completeness, uncertainty and variability, and evaluation and review (EPA 2003b).

评估要素：EPA考虑的用于评估科学和技术信息的质量的因素。主要有5个主要因素，合理、适用性、适用性、清晰性和完整性，不确定性和变异性，评价和回顾（EPA 2003b)。


>Bias: Systemic deviation between a measured (i.e., observed) or computed value and its “true” value. Bias is affected by faulty instrument calibration and other measurement errors, systemic errors during data collection, and sampling errors such as incomplete spatial randomization during the design of sampling programs.

误差：在测量值和“真”值之间的误差。这些误差是由仪器误差和其他测量误差，数据采集中的系统误差，在不完善的采样过程中采样误差。

>Boundaries: The spatial and temporal conditions and practical constraints under which environmental data are collected. Boundaries specify the area or volume (spatial boundary) and the time period (temporal boundary) to which a model application will apply (EPA 2000a).

边界：环境数据的采集中，空间、时间条件和实际的约束条件。边界指定了面积和体积（空间边界）和时间段（时间边界）在模型应用阶段。

>Boundary conditions: Sets of values for state variables and their rates along problem domain boundaries, sufficient to determine the state of the system within the problem domain.

边界条件：研究范围内的描述变量状态和速率的一系列值，在研究范围内决定了系统的状态。

>Calibration: The process of adjusting model parameters within physically defensible ranges until the resulting predictions give the best possible fit to the observed data (EPA 1994b). In some disciplines, calibration is also referred to as “parameter estimation” (Beck et al. 1994).

校准：校准是调整模型参数使得模拟值和观测值尽可能匹配的过程（EPA 1994b)。在某些情况下，校准也可以称作为“参数确认”（Beck et al.1994)。


>Checks: Specific tests in a quality assurance plan that are used to evaluate whether the specifications (performance criteria) for the project developed at its onset have been met.

复查：在质量保证计划中特殊的测试，用于评估是否满足设定的特殊要求（标准）。



>Clarity and completeness: One of EPA’s five assessment factors (see definition) that describes the degree of clarity and completeness with which the data, assumptions, methods, quality assurance, sponsoring organizations, and analyses employed to generate the information are documented (EPA 2003b).

EPA的五大评估因素之一，用于描述数据、假设、方法、质量保证计划、支持组织和生成的记录的清晰程度和完整性的(EPA 2003b)。

>Class (see “object-oriented platform”): A set of objects that share a common structure and behavior. The structure of a class is determined by the class variables, which represent the state of an object of that class; the behavior is given by the set of methods associated with the class (Booch 1994).

类（见面向对象的平台）：一系列对象具备共同的结构和属性，类的结构由类型变量决定，类型变量呈现类的状态；类的行为由类的一系列方法决定（Booch 1994).

>Code: Instructions, written in the syntax of a computer language, that provide the computer with a logical process. “Code” can also refer to a computer program or subset. The term “code” describes the fact that computer languages use a different vocabulary and syntax than algorithms that may be written in standard language.

代码：计算机语言编写的指令，表达一系列逻辑进程。代码也指计算机程序或程序集。代码指计算机语言使用的不同的词汇和语法，而不是用标准语言编写的算法。

>Code verification: Examination of the algorithms and numerical technique in the computer code to ascertain that they truly represent the conceptual model and that there are no inherent numerical problems with obtaining a solution (Beck et al. 1994).

代码验证：算法和计算机程序编写的数值计算技术的检查以确保能够表达概念模型，数值求解没有问题（Beck et al.1994)。


>Complexity: The opposite of simplicity. Complex systems tend to have a large number of variables, multiple parts, and mathematical equations of a higher order, and to be more difficult to solve. Used to describe computer models, “complexity” generally refers to the level in difficulty in solving mathematically posed problems as measured by the time, number of steps or arithmetic operations, or memory space required (called time complexity, computational complexity, and space complexity, respectively).

复杂性：简单的反义词。复杂系统倾向于有较多的变量，多模块和更多的高次方程，并较难求解。复杂用于描述计算机模型时，通常从时间、求解步骤、算法操作和内容空间的需求维度衡量求解的数学问题的难度等级。（分别为时间复杂度、计算复杂度、空间复杂度）

>Computational models: Models that use measurable variables, numerical inputs, and mathematical relationships to produce quantitative outputs.

计算模型：使用测量变量、输入和数学关系来生成定量输出的模型。


>Conceptual basis: An underlying scientific foundation of model algorithms or governing equations. The conceptual basis for a model is either empirical (based on statistical relationships between observations) or mechanistic (process-based) or a combination. See definitions for “empirical model” and “mechanistic model.”

基础概念：模型算法或者控制方程的内在的科学基础，模型的概念基础可以为经验的（基于观测值的统计关系求出的）和机理的（基于物理、生物等过程）或两者共同的。

>Conceptual model: A hypothesis regarding the important factors that govern the behavior of an object or process of interest. This can be an interpretation or working description of the characteristics and dynamics of a physical system (EPA 1994b).

概念模型：关于控制关注对象或过程的行为的重要因素的假设。是对物理系统特征和动力学的解释或描述(EPA 1994b)。

>Confounding error: An error induced by unrecognized effects from variables that are not included in the model. The unrecognized, uncharacterized nature of these errors makes them more difficult to describe and account for in statistical analysis of uncertainty (Small and Fishbeck 1999).

混淆错误：由未包含在模型中的变量，且未被识别的效应所引起的错误。这些不能被识别和不可描述的性质使得其更难描述，以及通过不确定性的统计分析去解释(Small和Fishbeck 1999)。

>Constant: A fixed value (e.g., the speed of light, the gravitational force) representing known physical, biological, or ecological activities.

常量：固定值（如光速，重力加速度）呈现物理、生物、生态活动。


>Corroboration (model): Quantitative and qualitative methods for evaluating the degree to which a model corresponds to reality. In some disciplines, this process has been referred to as validation. In general, the term “corroboration” is preferred because it implies a claim of usefulness and not truth.

验证（模型）：用于评估模型模拟值与观测值吻合程度的定量和定性的方法。在某些学科中，此过程称为验证（validation）。一般而言，更多的称为“验证”（corroboration），因为它意味着模型可用，而非其绝对真实。

实际上Corroboration和validation某些时候是不区分的，都是对校准模型的独立验证。

>Data uncertainty: Uncertainty (see definition) that is caused by measurement errors, analytical imprecision, and limited sample sizes during the collection and treatment of data. Data uncertainty, in contrast to variability (see definition), is the component of total uncertainty that is “reducible” through further study.

数据不确定性：在收集和采集数据时，由测量误差、分析不精确和有限的采样范围带来的不确定性（见定义）。数据不确定性，与变异性（定义）不同，其可以通过未来的进一步研究消除的不确定性的组成部分。


>Debugging: The identification and removal of bugs from computer code. Bugs are errors in computer code that range from typos to misuse of concepts and equations.

调试：从电脑代码中寻找并清理Bug，Bug是计算机代码中从误输入到概念和方程的错误使用的错误。

>Deterministic model: A model that provides a solution for the state variables rather than a set of probabilistic outcomes. Because this type of model does not explicitly simulate the effects of data uncertainty or variability, changes in model outputs are solely due to changes in model components or in the boundary conditions or initial conditions.

确定性模型：模型输出确定的状态量，而不是输出一组概率结果。由于此类模型未考虑的数据不确定性或变异性的影响，因此模型输出的变化完全是由模型的结构变化或边界条件或初始条件的变化引起。

>Domain (spatial and temporal): The spatial and temporal domains of a model cover the extent and resolution with respect to space and time for which the model has been developed and over which it should be evaluated.

域（空间和时间）：模型的空间和时间域涵盖了模型开发和评估的空间和时间的范围和分辨率。

>Domain boundaries (spatial and temporal): The limits of space and time that bound a model’s domain and are specified within the boundary conditions (see “boundary conditions”).

域边界（空间和时间）：在边界条件（参见“边界条件”）内被指定的空间和时间限定的模型域。

>Dynamic model: A model providing the time-varying behavior of the state variables.

动态模型：能够模拟状态变量随时间变化行为的模型。

>Empirical model: A model whose structure is determined by the observed relationship among experimental data (Suter 1993). These models can be used to develop relationships that are useful for forecasting and describing trends in behavior, but they are not necessarily mechanistically relevant.

经验模型：结构由观察到的实验数据之间的关系决定的模型（Suter 1993）。这些模型可用于建立能够描述解读和预测未来行为趋势有用的关系，但它们不一定与机理相关。

>Environmental data: Information collected directly from measurements, produced from models, and compiled from other sources such as databases and literature (EPA 2002a).

环境数据：直接来自于测量中收集的信息、模型中生成、或从其他来源（如数据库和文献）挖掘获取到的（EPA 2002a）。

>Evaluation and review: One of EPA’s five assessment factors (see definition) that describes the extent of independent verification, validation, and peer review of the information or of the procedures, measures, methods, or models (EPA 2003b).

评估和审查：EPA的五个评估因素之一（详见定义）。用于描述独立验证和信息或程序，措施，方法或模型的同行评审的标准（EPA 2003b）。

>Expert elicitation: A systematic process for quantifying, typically in probabilistic terms, expert judgments about uncertain quantities. Expert elicitation can be used to characterize uncertainty and fill data gaps where traditional scientific research is not feasible or data are not yet available. Typically, the necessary quantities are obtained through structured interviews and/or questionnaires. Procedural steps can be used to minimize the effects of heuristics and bias in expert judgments.

专家启发：系统化的过程，通常以概率的方式量化，关于不确定性的专家判断。专家启发可用于表征不确定性并填补传统科学研究的不可行性或数据不可用产生的数据缺失。通常，通过结构化访谈和/或问卷调查获得的所需的量化判断。程序步骤能被用于减小降低启发式和偏见在专家判断中的影响。

>Extrapolation: Extrapolation is a process that uses assumptions about fundamental causes underlying the observed phenomena in order to project beyond the range of the data. In general, extrapolation is not considered a reliable process for prediction; however, there are situations where it may be necessary and useful.

外推：外推是使用关于观察到的现象的本质原因的假设来推求超出数据范围的值。一般而言，外推并不能看作可靠的预测过程;但是，有些情况可能是必要和有用的。


> False negative: Also known as a false acceptance decision errors, a false negative occurs when the null hypothesis or baseline condition cannot be rejected based on the available sample data. The decision is made assuming the baseline condition is true when in reality it is false (EPA 2000a).

错误否定： 也被称为统计学中假设检验的第二类错误，原假设是错误的，却没有拒绝原假设。一般发生于无效的假设或极限条件基于可用的简单数据条件下不该被拒绝时拒绝了。在基准条件为真，但实际上其为假的状况下进行决策。

>False positive: Also known as a false rejection decision error, a false positive occurs when the null hypothesis or baseline condition is incorrectly rejected based on the sample data. The decision is made assuming the alternate condition or hypothesis to be true when in reality it is false (EPA 2000a).

错误肯定: 第一类错误，原假设是正确的，却拒绝了原假设，也就是以真为假。


> Forcing/driving variable: An external or exogenous (from outside the model framework) factor that influences the state variables calculated within the model. Such variables include, for example, climatic or environmental conditions (temperature, wind flow, oceanic circulation, etc.).

驱动/强迫变量：模型外部（从模型的框架外部）因素影响模型内部计算的状态变量。这些变量包括气候、环境条件（如温度、风等）。实际上，对于模型而言是重要的边界条件，强迫条件是模型的外部动力条件，可以通俗理解为外界的驱动力。


>Forms (models): Models can be represented and solved in different forms, including analytic, stochastic, and simulation.

形式（模型）:
模型能通过不同的形式来进行求解，如解析方法、随机分析、模拟。

>Function: A mathematical relationship between variables.

函数：
在变量之间的数学关系。

>Graded approach: The process of basing the level of application of managerial controls to an item or work on the intended use of results and degree of confidence needed in the results (EPA 2002b).

分级方法：基于预期的结论和置信度等级将项目或工程的管理控制措施应用进行分级的过程。

>Integrity: One of three main components of quality in EPA’s Information Quality Guidelines. “Integrity” refers to the protection of information from unauthorized access or revision to ensure that it is not compromised through corruption or falsification (EPA 2002a).

完整性：EPA信息质量导则中质量三要素之一。 “完整性”是指保护信息免受未经授权的访问或修改，以确保信息不会因腐败或伪造而受到损害（EPA 2002a）。


>Intrinsic variation: The variability (see definition) or inherent randomness in the real-world processes.

内在变异：现实世界过程中的可变性或固有的随机性。


>Loading: The rate of release of a constituent of interest to a particular receiving medium.

负荷：污染物组分进入受纳介质的速率。

>Measurement error: An error in the observed data caused by human or instrumental error during collection. Such errors can be independent or random. When a persistent bias or mis-calibration is present in the measurement device, measurement errors may be correlated among observations (Small and Fishbeck 1999). In some disciplines, measurement error may be referred to as observation error.

测量误差：在观测数据采集过程中由于人为或者设备引起的误差。这类误差是独立且随机的。在测量设施持续的存在偏差时，其能够通过观测数据进行校正（Small and Fishbeck 1999）。在一些学科中，测量误差也指观测误差。

>Mechanistic model: A model whose structure explicitly represents an understanding of physical, chemical, and/or biological processes. Mechanistic models quantitatively describe the relationship between some phenomenon and underlying first principles of cause. Hence, in theory, they are useful for inferring solutions outside the domain in which the initial data were collected and used to parameterize the mechanisms.

机理模型：模型的内在结构通过现有的物理、化学或生物过程显性的表达。机制模型定量地描述了某些现象与潜在的主要原因之间的响应关系。 因此，理论上说，在具备初始数据和参数化的过程条件下，机理模型求解区域外的解是十分好的工具。

>Mode (of a model): The manner in which a model operates. Models can be designed to represent phenomena in different modes. Prognostic (or predictive) models are designed to forecast outcomes and future events, while diagnostic models work “backwards” to assess causes and precursor conditions.

模式\模型：模型运作的行为。 模型可以设计为表示不同模式的现象。 预测类模型旨在预测结果和未来事件，而诊断模型用于“回看”之前状况和解释其原因。

>Model: A simplification of reality that is constructed to gain insights into select attributes of a physical, biological, economic, or social system. A formal representation of the behavior of system processes, often in mathematical or statistical terms. The basis can also be physical or conceptual (NRC 2007).

模型：现实的抽象简化，旨在深入了解所选的物理，生物，经济或社会系统的特性。 系统过程行为的正式呈现，通常以数学或统计术语表示。 其基础也可以是物理的或概念的表达（NRC 2007）。

>Model coding: The process of translating the mathematical equations that constitute the model framework into a functioning computer program.

模型编程：将构建模型的内在数学方程转变为计算机语言的过程。


>Model evaluation: The process used to generate information to determine whether a model and its results are of a quality sufficient to serve as the basis for a regulatory decision.

模型评估：评估以确定模型及其结果质量是否足以作为支撑管理决策的过程。



>Model framework: The system of governing equations, parameterization, and data structures that make up the mathematical model. The model framework is a formal mathematical specification of the concepts and procedures of the conceptual model consisting of generalized algorithms (computer code/software) for different site- or problem-specific simulations (EPA 1994b).

模型框架：构成数学模型的控制方程，参数化和数据结构的系统。 模型框架是由用于不同区域或特定问题的模拟的通用算法（计算机代码/软件）组成的概念模型的过程和概念的数学规范（EPA 1994b）。

>Model framework uncertainty: The uncertainty in the underlying science and algorithms of a model. Model framework uncertainty is the result of incomplete scientific data or lack of knowledge about the factors that control the behavior of the system being modeled. Model framework uncertainty can also be the result of simplifications necessary to translate the conceptual model into mathematical terms.

模型框架不确定性：模型的底层基础科学和算法的不确定性。 模型框架的不确定性由不完整的科学数据或被建模系统的控制因素的过程缺失所引起的。 模型框架不确定性也可能是将概念模型转换为数学方程时因简化造成的。

>Module: An independent or self-contained component of a model, which is used in combination with other components and forms part of one or more larger programs.

模块：模型的独立或自成功能的组件，与其他组件组合构成一个或多个较大程序的一个子功能块。


>Noise: Inherent variability that the model does not characterize (see definition for variability).

噪声：模型没有表征的固有可变性（参见可变性的定义）。

>Objectivity: One of three main components of quality in EPA’s Information Quality Guidelines. It includes whether disseminated information is being presented in an accurate, clear, complete and unbiased manner. In addition, objectivity involves a focus on ascertaining accurate, reliable, and unbiased information (EPA 2002a).

客观性：EPA信息质量导则质量评估三要素之一。它包括是否以准确，清晰，完整和无偏见的方式呈现传递信息。此外，客观性还涉及确定准确，可靠和无偏见的信息（EPA 2002a）。

>Object-oriented platform: A type of user interface that models systems using a collection of cooperating “objects.” These objects are treated as instances of a class within a class hierarchy。

面向对象平台：使用一组可操作的“对象”对系统进行建模的一种用户界面类型。这些对象被视为类层次结构中的类的实例。

>Parameters: Terms in the model that are fixed during a model run or simulation but can be changed in different runs as a method for conducting sensitivity analysis or to achieve calibration goals.

参数：模型中的术语，在模型运行或模拟过程中是固定值，但可以在不同的运行情景中改变值，从而进行灵敏度分析或实现校准。

>Parameter uncertainty: Uncertainty (see definition) related to parameter values.

参数不确定度：与参数值相关的不确定度（参见定义）。


>Parametric variation: When the value of a parameter itself is not a constant and includes natural variability. Consequently, the parameter should be described as a distribution (Shelly et al. 2000).

参数变异性：当参数本身的值不是常数且包括变异性时，该参数应描述为概率分布（Shelly等，2000）。


>Perfect information: The state of information where in which there is no uncertainty. The current and future values for all parameters are known with certainty. The state of perfect information includes knowledge about the values of parameters with natural variability.

完美信息：不包含不确定的信息状态。所有参数的当前和未来值都是确定的且已知的，完美信息的状态包括有关参数值的变异性的所有知识。

 
>Mode (of a model): The manner in which a model operates. Models can be designed to represent phenomena in different modes. Prognostic (or predictive) models are designed to forecast outcomes and future events, while diagnostic models work “backwards” to assess causes and precursor conditions.

模式\模型：模型运作的行为。 模型可以设计为表示不同模式的现象。 预测类模型旨在预测结果和未来事件，而诊断模型用于“回看”之前状况和解释其原因。

>Model: A simplification of reality that is constructed to gain insights into select attributes of a physical, biological, economic, or social system. A formal representation of the behavior of system processes, often in mathematical or statistical terms. The basis can also be physical or conceptual (NRC 2007).

模型：现实的抽象简化，旨在深入了解所选的物理，生物，经济或社会系统的特性。 系统过程行为的正式呈现，通常以数学或统计术语表示。 其基础也可以是物理的或概念的表达（NRC 2007）。

>Model coding: The process of translating the mathematical equations that constitute the model framework into a functioning computer program.

模型编程：将构建模型的内在数学方程转变为计算机语言的过程。


>Model evaluation: The process used to generate information to determine whether a model and its results are of a quality sufficient to serve as the basis for a regulatory decision.

模型评估：评估以确定模型及其结果质量是否足以作为支撑管理决策的过程。



>Model framework: The system of governing equations, parameterization, and data structures that make up the mathematical model. The model framework is a formal mathematical specification of the concepts and procedures of the conceptual model consisting of generalized algorithms (computer code/software) for different site- or problem-specific simulations (EPA 1994b).

模型框架：构成数学模型的控制方程，参数化和数据结构的系统。 模型框架是由用于不同区域或特定问题的模拟的通用算法（计算机代码/软件）组成的概念模型的过程和概念的数学规范（EPA 1994b）。

>Model framework uncertainty: The uncertainty in the underlying science and algorithms of a model. Model framework uncertainty is the result of incomplete scientific data or lack of knowledge about the factors that control the behavior of the system being modeled. Model framework uncertainty can also be the result of simplifications necessary to translate the conceptual model into mathematical terms.

模型框架不确定性：模型的底层基础科学和算法的不确定性。 模型框架的不确定性由不完整的科学数据或被建模系统的控制因素的过程缺失所引起的。 模型框架不确定性也可能是将概念模型转换为数学方程时因简化造成的。

>Module: An independent or self-contained component of a model, which is used in combination with other components and forms part of one or more larger programs.

模块：模型的独立或自成功能的组件，与其他组件组合构成一个或多个较大程序的一个子功能块。


>Noise: Inherent variability that the model does not characterize (see definition for variability).

噪声：模型没有表征的固有可变性（参见可变性的定义）。

>Objectivity: One of three main components of quality in EPA’s Information Quality Guidelines. It includes whether disseminated information is being presented in an accurate, clear, complete and unbiased manner. In addition, objectivity involves a focus on ascertaining accurate, reliable, and unbiased information (EPA 2002a).

客观性：EPA信息质量导则质量评估三要素之一。它包括是否以准确，清晰，完整和无偏见的方式呈现传递信息。此外，客观性还涉及确定准确，可靠和无偏见的信息（EPA 2002a）。

>Object-oriented platform: A type of user interface that models systems using a collection of cooperating “objects.” These objects are treated as instances of a class within a class hierarchy。

面向对象平台：使用一组可操作的“对象”对系统进行建模的一种用户界面类型。这些对象被视为类层次结构中的类的实例。

>Parameters: Terms in the model that are fixed during a model run or simulation but can be changed in different runs as a method for conducting sensitivity analysis or to achieve calibration goals.

参数：模型中的术语，在模型运行或模拟过程中是固定值，但可以在不同的运行情景中改变值，从而进行灵敏度分析或实现校准。

>Parameter uncertainty: Uncertainty (see definition) related to parameter values.

参数不确定度：与参数值相关的不确定度（参见定义）。


>Parametric variation: When the value of a parameter itself is not a constant and includes natural variability. Consequently, the parameter should be described as a distribution (Shelly et al. 2000).

参数变异性：当参数本身的值不是常数且包括变异性时，该参数应描述为概率分布（Shelly等，2000）。


>Perfect information: The state of information where in which there is no uncertainty. The current and future values for all parameters are known with certainty. The state of perfect information includes knowledge about the values of parameters with natural variability.

完美信息：不包含不确定的信息状态。所有参数的当前和未来值都是确定的且已知的，完美信息的状态包括有关参数值的变异性的所有知识。


附录介绍了很多模型中的专业术语，这些术语实际上在整个模型过程中非常的常见，这里的翻译只能是抛砖，对于每个术语如果需要可以深入的去了解其，大家也可以留言进行探讨。

Precision: The quality of being reproducible in amount or performance. With models and other forms of quantitative information, “precision” refers specifically to the number of decimal places to which a number is computed as a measure of the “preciseness” or “exactness” with which a number is computed.

>精度： 数量或性能在多次重复时的质量。对于模型和其他形式的定量信息来说，“精度”特指计算数字的小数位数，作为计算结果的“精确度”或“正确度”的度量。


Probability density function: Mathematical, graphical, or tabular expression of the relative likelihoods with which an unknown or variable quantity may take various values. The sum (or integral) of all likelihoods equals 1 for discrete (continous) random variables (Cullen and Frey 1999). These distributions arise from the fundamental properties of the quantities we are attempting to represent. For example, quantities formed from adding many uncertain parameters tend to be normally distributed, and quantities formed from multiplying uncertain quantities tend to be lognormal (Morgan and Henrion 1990).

>概率密度函数：未知或可变的量可能有各种值，通过数学、图形或表格方式来表达其各种值的可能性。对于离散（连续）随机变量（Cullen和Frey，1999），所有随机事件的概率综合等于1。这些分布是所表达的量的基本属性。例如，加和许多不确定参数形成的量往往是正态分布，由乘以不确定量形成的量趋向对数正态的（Morgan和Henrion 1990）。


Program (computer): A set of instructions, written in the syntax of a computer language, that provide the computer with a step-by-step logical process. Computer programs are also referred to as code.

>程序（计算机）：一组用计算机语言编写的指令，为计算机提供逐步的执行逻辑过程，计算机程序也称为代码。


Qualitative assessment: Some of the uncertainty in model predictions may arise from sources whose uncertainty cannot be quantified. Examples are uncertainties about the theory underlying the model, the manner in which that theory is mathematically expressed to represent the environmental components, and the theory being modeled. The subjective evaluations of experts may be needed to determine appropriate values for model parameters and inputs that cannot be directly observed or measured (e.g., air emissions estimates). Qualitative corroboration activities may involve the elicitation of expert judgment on the true behavior of the system and agreement with model-forecasted behavior.

> 定性评估：模型预测中的一些不确定性来源可能无法量化。如与模型的底层基础理论相关的不确定性，其是通过数学方式来表达环境成分和建模的理论。可能需要通过专家的主观调试来确定模型的恰当参数和那些不能直接观测和测量的输入条件（例如，废气排放量）。定性验证可能会获取到系统真实行为的专业判断以及与模型预测行为的共识。

Quality: A broad term that includes notions of integrity, utility, and objectivity (EPA 2002a).

> 质量：一个广义的术语，包括完整性，实用性和客观性的概念（EPA 2002a）。

Quantitative assessment: The uncertainty in some sources — such as some model parameters and some input data — can be estimated through quantitative assessments involving statistical uncertainty and sensitivity analyses. In addition, comparisons can be made for the special purpose of quantitatively describing the differences to be expected between model estimates of current conditions and comparable field observations.

> 定量评估：某些不确定性的来源（例如某些模型参数和一些输入数据），可以通过相关统计不确定性和敏感性分析的定量评估进行估计。此外，特定目的的量化能定量描述当前条件下的模型模拟与对应的现场观测之间的差异。



Reducible uncertainty: Uncertainty in models that can be minimized or even eliminated with further study and additional data (EPA 1997). See “data uncertainty.“

> 可减少的不确定性：通过进一步研究和其他额外的数据可以减小甚至消除的模型中的不确定性（EPA 1997）。请参阅“数据不确定性”。


Reliability: The confidence that (potential) users have in a model and in the information derived from the model such that they are willing to use the model and the derived information (Sargent 2000). Specifically, reliability is a function of the performance record of a model and its conformance to best available, practicable science.

>可靠性：（潜在的）用户对模型及使用模型所获得的信息的信心（Sargent 2000）。具体而言，可靠性是模型表现的记录及其与最佳可用和实践性科学的符合度的函数。

Response surface: A theoretical multi-dimensional “surface” that describes the response of a model to changes in its parameter values. A response surface is also known as a sensitivity surface.

> 响应面：理论上的多维“表面”用于描述模型对其参数值变化的响应。响应表面也称为灵敏度表面。[响应面](https://wenku.baidu.com/view/312aab8db8f3f90f76c66137ee06eff9aef849d3.html)

 
Robustness: The capacity of a model to perform well across the full range of environmental conditions for which it was designed.

>稳健性：鲁棒性，模型在其设计的各种环境条件下表现良好的能力。

Screening model: A type of model designed to provide a “conservative” or risk-averse answer. Screening models can be used with limited information and are conservative, and in some cases they can be used in lieu of refined models, even when time or resources are not limited.

> 筛选模型：一种旨在提供“保守”或风险防范结果的模型。即使在时间或资源不受限制的情况下，筛选模型可在有限的信息条件下使用，并遵循保守性，某些情况下它们可以代替精细模型。


Sensitivity: The degree to which the model outputs are affected by changes in selected input parameters (Beck et al. 1994).

> 灵敏度：模型输出受所选输入参数变化影响的程度（Beck等，1994）。

Sensitivity analysis: The computation of the effect of changes in input values or assumptions (including boundaries and model functional form) on the outputs (Morgan and Henrion 1990); the study of how uncertainty in a model output can be systematically apportioned to different sources of uncertainty in the model input (Saltelli et al. 2000a). By investigating the “relative sensitivity” of model parameters, a user can become knowledgeable of the relative importance of parameters in the model.

>敏感性分析：输入条件变化的影响或假设（包括边界和模型函数的形式）的变化对模型输出的影响（Morgan和Henrion 1990);研究模型输出结果的不确定性如何系统地追踪到模型的不同输入来源上（Saltelli等人，2000a）。通过研究模型参数的“相对灵敏度”，用户可以获取模型中重要性的参数。

Simulation model: A model that represents the development of a solution by incremental steps through the model domain. Simulations are often used to obtain solutions for models that are too complex to be solved analytically. For most situations, where a differential equation is being approximated, the simulation model will use finite time step (or spatial step) to “simulate” changes in state variables over time (or space).

>仿真模型：通过模型域的逐增量呈现解变化的模型。模拟通常用于太复杂而无法求解析解的情况。对于大多数情况，在近似微分方程的情况下，仿真模型将使用有限时间步长（或空间步长）来“模拟”状态变量随时间（或空间）的变化。



>本节作为附录A-专有术语的最后一部分内容，虽然很多词我都见过，但是还是很多收获。


Soundness: One of EPA’s five assessment factors (see definition) that describes the extent to which the scientific and technical procedures, measures, methods, or models employed to generate the information are reasonable for and consistent with the intended application (EPA 2003b).

> 完整性：EPA的五个评估因素之一，其旨在表达科学和技术过程，措施，方法或模型等得出的信息和结论，与预期的应用多大程度上合理匹配（EPA 2003b）。

Specifications: Acceptance criteria set at the onset of a quality assurance plan that help to determine if the intended objectives of the project have been met. Specifications are evaluated using a series of associated checks (see definition).

>规范：质量保证计划所设定的验收标准，使用一系列相关检查评估规格（参见定义）确定项目的预期目标是否已达到。


State variables: The dependent variables calculated within a model, which are also often the performance indicators of the models that change over the simulation.

>状态变量：模型中计算的因变量，其也经常作为模型改变模拟之后性能的指示器，实际就是模型所模拟的指标量。


Statistical model: A model built using observations within a probabilistic framework. Statistical models include simple linear or multivariate regression models obtained by fitting observational data to a mathematical function.

> 统计模型：在概率基础上对观测数据处理建立的模型。 统计模型包括将观测数据与数学函数拟合获取的简单线性或多元回归模型。


Steady-state model: A model providing the long-term or time-averaged behavior of the state variables.
> 稳定态模型： 模型仅仅能提供状态变量的长期或时间平均变化的模型。

Stochasticity:Fluctuations in ecological processes that are due to natural variability and inherent randomness.
>随机性：由于自然变化和固有随机性导致在生态过程中的波动。


Stochastic model: A model that includes variability (see definition) in model parameters. This variability is a function of changing environmental conditions, spatial and temporal aggregation within the model framework, and random variability. The solution obtained by the model or output is therefore a function of model components and random variability.
>随机模型：包含变异性参数的模型。其变异性是环境条件、模型框架内的空间和时间综合、以及随机变化的函数。因此，模型的求解也就是要求得到模型组分和随机可变性的函数。


Transparency: The clarity and completeness with which data, assumptions, and methods of analysis are documented. Experimental replication is possible when information about modeling processes is properly and adequately communicated (EPA 2002a).
>透明公开：所记录的数据，假设和分析方法的透明性和完整性。在建模过程的信息进行充分的了解后，实验据此能够复现（EPA 2002a）。

Uncertainty: The term used in this document to describe lack of knowledge about models, parameters, constants, data, and beliefs. There are many sources of uncertainty, including the science underlying a model, uncertainty in model parameters and input data, observation error, and code uncertainty. Additional study and collecting more information allows error that stems from uncertainty to be minimized/reduced (or eliminated). In contrast, variability (see definition) is irreducible but can be better characterized or represented with further study (EPA 2002b, Shelly et al. 2000).
>不确定性：本文档中使用的不确定性术语用于描述有关模型的机理，参数，常量，数据等缺乏而造成的不确定性。不确定性有诸多来源，包括模型的底层科学基础是否完善，模型的参数和输入数据的不确定性，观察误差和编程的代码不确定性。随着进一步的研究和获取更多的信息可以减小甚至消除不确定性。相反，变异性是不可能被消除的，但可以通过进一步研究更好地表征或表示（EPA 2002b，Shelly等人，2000）。


Uncertainty analysis: Investigation of the effects of lack of knowledge or potential errors on the model (e.g, the “uncertainty” associated with parameter values). When combined with sensitivity analysis (see definition), uncertainty analysis allows a model user to be more informed about the confidence that can be placed in model results.
>不确定性分析：分析研究模型缺乏机理基础或潜在误差条件下对模型的影响（例如，与参数值相关的“不确定性”）。当与灵敏度分析（参见定义）一起进行时，不确定性分析可让模型用户充分了解模型结果的置信度。

Uncertainty and variability: One of EPA’s five assessment factors (see definition) that describes the extent to which the variability and uncertainty (quantitative and qualitative) in the information or in the procedures, measures, methods, or models are evaluated and characterized (EPA 2003b).
>不确定性和变异性：EPA的五个评估因素之一，（定量和定性）评估和表征在信息或程序、措施、方法或模型中的变异性和不确定性（EPA 2003b）。

Utility: One of three main components of quality in EPA’s Information Quality Guidelines. “Utility” refers to the usefulness of the information to the intended users (EPA 2002a).
>效用：EPA信息质量指南中，质量控制的三个主要组成部分之一。 “效用”指的是信息对于目标用户的有用性（EPA 2002a）。

Variable: A measured or estimated quantity that describes an object or can be observed in a system and that is subject to change.
>变量：一种可在系统中观察且可能发生变化的对象的测量值或估计量。


Variability: Observed differences attributable to true heterogeneity or diversity. Variability is the result of natural random processes and is usually not reducible by further measurement or study (although it can be better characterized) (EPA 1997).
>变异性：异质性或多样性引起的可观察到的差异。变异性是自然随机过程的结果，尽管可以更好的去表征，但通常不能通过进一步的测量或研究来减少（EPA 1997）。

Verification (code): Examination of the algorithms and numerical technique in the computer code to ascertain that they truly represent the conceptual model and that there are no inherent numerical problems with obtaining a solution (Beck et al 1994).
>验证（代码）：检查计算机代码中的算法和数值方法，以确保其真正能够代表概念模型。并且在求解过程中没有数值求解方面问题（Beck等1994）。


---


由于教程系列文章需要花费很多时间，难免出错，而这里不能进行后续完善，所以推荐大家关注我的博客，获取最新的修正和补充。
公众号的**社群**同步开启，感兴趣可在公众号对话框回复“社群”，获取群号和加入方式。



参考文献：
[1] Gaber N, Foley G, Pascual P, et al. Guidance on the development, evaluation, and application of environmental models[J]. Report, Council for Regulatory Environmental Modeling, 2009, 81.


![页尾](http://comieswater-1254012817.cossh.myqcloud.com/页尾识别new-2017-09-22.png)
微信公众号 | 水环境编Cheng长
网          站 | comieswater.com


![赞赏我](http://comieswater-1254012817.cossh.myqcloud.com/IMG_3077.JPG)

2019-6-29

