---
title: 《模型开发、评估、应用导则》
tags: 1000天持续行动,GDEA
date:   2018-9-12
---


![封面](http://comieswater-1254012817.cossh.myqcloud.com/comieswater/1534259099598.png)

## 3.4 应用工具开发

在模型框架选定及开发完成后，建模人员开始按照框架逐步的添加用于解决问题的特定系统模块，如模型研究区范围域，边界条件，污染源数据，模型参数等。这过程中，通用的模型计算框架被构建为解决特定位置的特定问题的应用工具。模型参数在模型运行或模拟时是一组固定的值，但参数值能够在另外一次运行中被改变，对于参数而言，为了校准（下面会叙述这个概念）模型或指定了模型参数的概率分布情况，可以通过敏感性分析或者不确定性分析来辅助判断。参数能够从样本数据的统计量估计，也有一些是常量，如光速、重力加速度等。在这个模型开发阶段其他的一些任务包括构建模型使用技术报告，模型参数的整合输入，硬件配置计划等。

> Once a model framework has been selected or developed, the modeler populates the framework with the specific system characteristics needed to address the problem, including geographic boundaries of the model domain, boundary conditions, pollution source inputs, and model parameters. In this manner, the generic computational capabilities of the model framework are converted into an application tool to assess a specific problem occurring at a specific location. Model parameters are terms in the model that are fixed during a model run or simulation but can be changed in different runs, either to conduct sensitivity analysis or to perform an uncertainty analysis when probabilistic distributions are selected to model parameters or achieve calibration (defined below) goals. Parameters can be quantities estimated from sample data that characterize statistical populations or they can be constants such as the speed of light and gravitational force. Other activities at this stage of model development include creating a user guide for the model, assembling datasets for model input parameters, and determining hardware requirements.

### 3.4.1 输入数据
如上所述，数据的准确性、精度及变异性是不确定性的主要来源：
1. 准确性：指测量值或者计算值与真实值（在理想状态下获取）的接近程度。由于自然界的固有的异质性和许多环境系统随机性，这种真实值仅仅存在一个分布而非离散值。
2. 变异性：由模型参数的异质性及多样性带来的差异。由于变异性的存在，模型参数的真实值是空间和时间聚合程度的函数。
3. 精度。模型结果的复现质量。对于模型和其他形式的量化信息而言，精度经常指计算结果的小数点位数。这是对模型准确性和正确性的一种衡量。

>- Accracy, refers  to  the  closeness  of  a  measured  or  computed  value  to  its  “true”  value  (the  value obtained with perfect information). Due to the natural heterogeneity and random variability (stochasticity) of many environmental systems, this “true” value exists as a distribution rather than a discrete value.
>- Variability refers to differences attributable to true heterogeneity or diversity in model parameters. Because of variability, the “true” value of model parameters is often a function of the degree of spatial and temporal aggregation.
>- Precision refers to the quality of being reproducible in outcome or performance.  With models and  other forms of quantitative information, precision often refers to the number of decimal places to which a number is computed. This is a measure of the “preciseness” or “exactness” of the model.

建模人员应该选择最恰当的数据用于模型分析，其样本获取、数据采集及分析等过程遵循QA协议的（EPA 2002c，2002d，2000b）。并且，尽可能所有的参数通过关注的系统直接测量获得。

NRC的模型管理决策过程委员会推荐：“对于决策者和模型开发的监督管理应该优先使用适应性策略来协调数据采集和模型。在概念模型开发阶段就应该考虑进行独立的测量和模拟。

>Modelers should always select the most appropriate data — as defined by QA protocols for field sampling, data collection, and analysis (EPA 2002c, 2002d, 2000b) — for use in modeling analyses. Whenever possible, all parameters should be directly measured in the system of interest. The NRC Committee on Models in the Regulatory Decision Process recommends that: “…using adapting strategies to coordinate data collection and modeling should be a priority for decision makers and those responsible for regulatory model development and application. The interdependence of measurements and modeling needs to be fully considered as early as the conceptual model development phase.”



###  3.4.2 模型的校准 

许多模型是通过设置参数来进行校准。附录C提供了作为QA计划一项内容的模型校准的导则（see Box C3: Quality Assurance Planning Suggestions for Model Calibration Activities)。在这个导则中，校准被定义为通过在物理过程允许范围内调整模型参数使得模拟值尽可能与实测值相匹配（EPA 1994b）。在一些术语表达中，校准也被作为模型参数的估计（Beck 等1994）。

>Some models are “calibrated” to set parameters. Appendix C provides guidance on model calibration as  a QA project plan element (see Box C3: Quality Assurance Planning Suggestions for Model Calibration Activities). In this guidance, calibration is defined as the process of adjusting model parameters within physically defensible ranges until the resulting predictions give the best possible fit to the observed data (EPA 1994b). In some disciplines, calibration is also referred to as parameter estimation (Beck et al. 1994).

大多数面向过程的环境模型都存在潜在的不确定性，即模型包含的不确定性参数比需要校准的状态变量要多。敏感性分析能够用于去分析那些影响状态变量的关键过程。有时，对于关键过程的速率常量而言，其能被直接的测量-例如，在湖中增加额外的浮游植物生物量（作为一个状态变量）能够测量出其的光合作用速率。直接测量的速率参数能够减少模型的不确定性。

>Most process-oriented environmental models are under-determined; that is, they contain more uncertain parameters than state variables that can be used to perform a calibration. Sensitivity analysis can be used to identify key processes influencing the state variables. Sometimes the rate constant for a key process can be measured directly — for example, measuring the rate of photosynthesis (a process) in a lake in addition to the phytoplankton biomass (a state variable). Direct measurement of rate parameters can reduce model uncertainty.

校准所需的数据库随着时间的不断增加和丰富，那么其开始的调整和估计可能需要重新校准。当量化一个或者多个参数值的数据库不足时，校准测试能被用于去求解得到匹配观测值的参数。但是这些解一般并不能提供有意义的信息，除非他们是在基于物理测量的合理范围内。也就是说，通过这种方式的校准应该足够的谨慎。
>When a calibration database has been developed and improved over time, the initial adjustments and estimates may need period recalibration. When data for quantifying one or more parameter values are limited, calibration exercises can be used to find solutions that result in the ”best fit” of the model. However, these solutions will not provide meaningful information unless they are based on measured physically defensible ranges. Therefore, this type of calibration should be undertaken with caution.

由于这些要点，从EPA到各个不同区域通过校准提高模型表现的方法有所不同。对于特定的模型，相对较好的校准的方法依赖于模型的行为不同而不同。例如，水标准实践部门去校准通过现有模型框架（如CE-QUAL-W2，预测河流水温波动）构建的特定区域模型（如Snake河），这种校准完成后是形成了一个适配特定地点的模型（如，Snake 河流温度模型）。相反，空气部门和辐射部门则使用的模型框架一般不需要根据地点的适配。例如，确定类型的空气模型（如gaussian pume）是根据一系列气象条件进行参数化，也就是说在不同的地理条件下，如果气象条件是类似的，则并不需要重新校准。辐射部门也试图去避免调整超出经验数据基础支撑范围的模型输入，来人为的提升模型表现。OAR提出了有关模型校准的导则，在空气质量模型导则（EPA 2003b）：

>Because of these concerns, the use of calibration to improve model performance varies among EPA offices and regions. For a particular model, the appropriateness of calibration may be a function of the modeling activities undertaken. For example, the Office of Water’s standard practice is to calibrate well- established model frameworks such as CE-QUAL-W2 (a model for predicting temperature fluctuations in rivers) to a specific system (e.g., the Snake River). This calibration generates a site-specific tool (e.g., the “Snake River Temperature” model). In contrast, the Office of Air and Radiation (OAR) more commonly uses model frameworks and models that do not need site-specific adjustments. For example, certain types of air models (e.g., gaussian plume) are parameterized for a range of meteorological conditions, and thus do not need to be “recalibrated” for different geographic locations (assuming the range of conditions is appropriate for the model). OAR also seeks to avoid artificial improvements in model performance by adjusting model inputs outside the ranges supported by the empirical databases. These practices prompted OAR to issue the following statement on model calibration in their Guideline on Air Quality Models (EPA 2003b):

模型的校准并不是一个简单的常识性的操作，校准过程会犯很多错误和认识的误区。一些人试图通过对比模型估计和以单独场景下的测量的结果来校准模型。这种方法由于边界条件和气象数据的不确定性使得其应用场景受到限制，也就是说精确的估计确定位置的时间增量下的浓度是非常的困难的，这种不确定性降低了模型的校准可信度。

>Calibration of models is not common practice and is subject to much error and misunderstanding. There have been attempts by some to compare model estimates and measurements on an event-by-event basis and then calibrate a model with results of that comparison. This approach is severely limited by uncertainties in both source and meteorological data and therefore it is difficult to precisely estimate the concentration at an exact location for a specific increment of time. Such uncertainties make calibration of models of questionable benefit. Therefore, model calibration is unacceptable.

但是，通常来说，模型足以解决特定的管理问题，并从这些案例中获得更多的应用经验。

>In general, however, models benefit from thoughtful adaptation that will enable them to respond adequately to the specifics of each regulatory problem to which they are applied.



参考文献：
[1] Gaber N, Foley G, Pascual P, et al. Guidance on the development, evaluation, and application of environmental models[J]. Report, Council for Regulatory Environmental Modeling, 2009, 81.


![页尾](http://comieswater-1254012817.cossh.myqcloud.com/页尾识别new-2017-09-22.png)
微信公众号 | 水环境编Cheng长
网          站 | comieswater.com


![赞赏我](http://comieswater-1254012817.cossh.myqcloud.com/IMG_3077.JPG)

 2018-9-12