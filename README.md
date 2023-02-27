# Model Predictive Building Climate Control - Steps Towards Practice
This repository holds my PhD thesis, the source code of the Matlab toolbox I developed for creating (bi)linear thermal models of buildings for use in control systems as well as links to my most important papers. 

## Phd Thesis

A PDF of my thesis is in this repository. 

The thesis investigates the application of Model Predictive Control (MPC) to the climate control of buildings with the goal of improving its energy efficiency. Current practice in the control of Heating, Ventilation, and Air Conditioning (HVAC) systems is the use of Rule-Based Control (RBC). RBC control strategies are well-established but limited by the difficulty of consistently integrating weather predictions and systematically coordinating all actuators – both commonly regarded as ways to improve energy efficiency. The research interest into alternative, more energy efficient control strategies in buildings is mainly driven by three factors: i) a large fraction of the world’s energy consumption occurs in buildings; ii) the majority of the building stock is already in place and refurbishments are expensive while control systems can be upgraded at comparatively low costs; iii) computational power is becoming ever cheaper, enabling the cost-effective use of advanced control techniques.

## BRCM Toolbox

The Building Resistance-Capacitance Modeling (BRCM) Matlab Toolbox facilitates the physical modeling of buildings for MPC. The Toolbox provides a means for the fast generation of (bi-)linear resistance-capacitance type models from basic geometry, construction and building systems data. Moreover, it supports the generation of the corresponding potentially time-varying costs and constraints.

The source code and documentation of the BRCM can soon be found in this repository. 

## Papers

For a list of all my papers, check my [Google Scholar profile](https://scholar.google.com/citations?user=m-92wOQAAAAJ&hl=en&oi=ao).

### Model Predictive Climate Control of a Swiss Office Building: Implementation, Results, and Cost–Benefit Analysis 

[PDF](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/94992/TCST2016_Sturzenegger_building_MPC_AAM.pdf?sequence=2) (2015, IEEE Transactions on Control Systems Technology)

This paper reports the final results of the predictive building control project OptiControl-II that encompassed seven months of model predictive control (MPC) of a fully occupied Swiss office building. First, this paper provides a comprehensive literature review of experimental building MPC studies. Second, we describe the chosen control setup and modeling, the main experimental results, as well as simulation- based comparisons of MPC to industry-standard control using the EnergyPlus simulation software. Third, the costs and benefits of building MPC for cases similar to the investigated building are analyzed. In the experiments, MPC controlled the building reliably and achieved a good comfort level. The simulations suggested a significantly improved control performance in terms of energy and comfort compared with the previously installed industry-standard control strategy. However, for similar buildings and with the tools currently available, the required initial investment is likely too high to justify the deployment in everyday building projects on the basis of operating cost savings alone. Nevertheless, development investments in an MPC building automation framework and a tool for modeling building thermal dynamics together with the increasing importance of demand response and rising energy prices may push the technology into the net benefit range.

### BRCM Matlab Toolbox: Model Generation for Model Predictive Building Control

[PDF](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/95075/2/ACC2014_Sturzenegger_BRCMToolbox_AAM.pdf) (2014, American Control Conference)

Model predictive control (MPC) is a promising alternative in building control with the potential to improve energy efficiency and comfort and to enable demand response capabilities. Creating an accurate building model that is simple enough to allow the resulting MPC problem to be tractable is a challenging but crucial task in the control development.
In this paper we introduce the Building Resistance-Capacitance Modeling (BRCM) Matlab Toolbox that facilitates the physical modeling of buildings for MPC. The Toolbox provides a means for the fast generation of (bi-)linear resistance-capacitance type models from basic building geometry, construction and systems data. Moreover, it supports the generation of the corresponding potentially time-varying costs and constraints. The Toolbox is based on previously validated modeling principles. In a case study a BRCM model was automatically generated from an EnergyPlus input data file and its predictive capabilities were compared to the EnergyPlus model.

### Importance of occupancy information for building climate control

[PDF](https://www.synergy.ch/OptiControl/LiteratureOC/Olde_13_AE_101_521.pdf) (2013, Applied Energy)

This paper investigates the potential of using occupancy information to realize a more energy efficient building climate control. The study focuses on Swiss office buildings equipped with Integrated Room Auto- mation (IRA), i.e. the integrated control of Heating, Ventilation, Air Conditioning (HVAC) as well as lighting and blind positioning of a building zone or room. To evaluate the energy savings potential, different types of occupancy information are used in a Model Predictive Control (MPC) framework, which is well-suited for this study due to its ability to readily include occupancy information in the control.
An MPC controller, which controls the building based on a standard fixed occupancy schedule, is used as a benchmark. The energy use of this benchmark is compared with three other control strategies: first, the same MPC controller which uses the same schedule for control as the benchmark, but turns off the lighting in case of (an instantaneous measurement of) vacancy; second, the same MPC controller which uses the same schedule as the benchmark for control, but turns off lighting and ventilation in case of (an instantaneous measurement of) vacancy; and third, the same MPC controller as the benchmark but using a perfect prediction about the upcoming occupancy.
This comparison is carried out for different buildings, HVAC systems, seasons and occupancy patterns in order to determine their influence on the energy savings potential.
