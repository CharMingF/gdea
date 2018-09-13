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







参考文献：
[1] Gaber N, Foley G, Pascual P, et al. Guidance on the development, evaluation, and application of environmental models[J]. Report, Council for Regulatory Environmental Modeling, 2009, 81.


![页尾](http://comieswater-1254012817.cossh.myqcloud.com/页尾识别new-2017-09-22.png)
微信公众号 | 水环境编Cheng长
网          站 | comieswater.com


![赞赏我](http://comieswater-1254012817.cossh.myqcloud.com/IMG_3077.JPG)

 2018-9-12