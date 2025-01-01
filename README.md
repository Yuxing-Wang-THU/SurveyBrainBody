<div align=center><img src="images/cover2.png" width="96%"></div>

<!-- [![arXiv](https://img.shields.io/badge/arXiv-1912.12033-b31b1b.svg)](https://arxiv.org/abs/1912.12033) -->
[![Survey](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) 
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Yuxing-Wang-THU/Awesome-Brain-Body-Co-Design-of-Embodied-Agents/graphs/commit-activity)
[![GitHub issues](https://img.shields.io/github/issues/Yuxing-Wang-THU/Awesome-Brain-Body-Co-Design-of-Embodied-Agents)](https://github.com/Yuxing-Wang-THU/Awesome-Brain-Body-Co-Design-of-Embodied-Agents/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![GitHub license](https://badgen.net/github/license/Naereen/Strapdown.js)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)
![visitors](https://visitor-badge.laobi.icu/badge?page_id=Yuxing-Wang-THU.Awesome-Brain-Body-Co-Design-of-Embodied-Agent&left_color=green&right_color=red)
![GitHub stars](https://img.shields.io/github/stars/Yuxing-Wang-THU/Awesome-Brain-Body-Co-Design-of-Embodied-Agents.svg?style=flat&label=Star)
# 🚀 Brain-Body Co-Design of Embodied Agents: A Survey
<p style="text-align:justify;"> Human bodies have been carefully refined through the long process of evolution, enabling us to utilize our bodies to solve a multitude of tasks skillfully. This capability, natural to humans, remains challenging for embodied agents, such as robots. The difficulty arises because successful interactions are highly dependent on the synergy between <b>brain, body, and environment</b>. Recent years, the concept of <b>Brain-Body Co-Design (BBCD)</b> has garnered growing cross-disciplinary research interest. Unlike traditional approaches to embodied agent design, which focus primarily on optimizing an agent’s <b>controlling brain</b> within a fixed <b>body morphology</b>, BBCD highlights the concurrent optimization of both elements, leading agents to superior adaptability and task performance.</p>

<div align=center><img src="images/cover4.jpg" width="99%"></div>

<p style="text-align:justify;"><b>🔑 Contributions to Embodied AI:</b> To the best of our knowledge, this survey is the <b>first</b> attempt to survey Brain-Body Co-Design approaches in the context of Embodied AI. We envision this survey as an essential starting point for researchers from different academic backgrounds entering this exciting and rapidly evolving field.</p></b>

# 📋 Update List
**2025/01/01**: Happy New Year! I am updating the survey on this topic and will fully update the site when the survey is updated to Arxiv.

# 🔥 Comments
* [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)**Feel free to pull requests or contact us if you find any related papers that are not included here.**
The process to submit a pull request is as follows:
- a. Fork the project into your own repository.
- b. Add the Title, Paper link, Conference, Project/Code link in `README.md` using the following format:
```python
  |[Title](Paper Link)|Conference|Agent Type|[Code/Project](Code/Project link)|
```
- c. Submit the pull request to this branch.

* **We will update this page on a regular basis! So stay tuned~ :tada::tada::tada:. If you do find our survey or the repository helpful, please consider kindly giving a :star:. 谢谢你, Thanks a lot, Спасибо, ありがとう, 감사합니다, Merci, Grazie, Obrigado, Danke, شكراً**

# 🎥 Contents
<p style="text-align:justify;">In this survey, we systematically investigate recent progress in BBCD across simulated and real-world scenarios. We begin by defining the BBCD problem and positioning it with respect to related fields. Subsequently, we propose a novel framework for categorizing the state-of-the-art BBCD approaches, under which we analyze their co-design spaces, methodologies, benchmarks, and applications. Finally, we highlight the current challenges in the field and provide insights for potentially interesting future directions.</p>

## 🎥 Introduction of Brain-Body Co-Design Problem
TODO:::
## 🎥 Introduction of our Taxonomy
In general, a robot’s ability to learn a task depends on three major system components, namely, the body (morphology, hardware), the brain (controller, software), and the learning algorithm.
TODO:::
## 🎥 Quick Menu
- [🚀 Brain-Body Co-Design of Embodied Agents: A Survey](#-brain-body-co-design-of-embodied-agents-a-survey)
- [📋 Update List](#-update-list)
- [🔥 Comments](#-comments)
- [🎥 Contents](#-contents)
  - [🎥 Introduction of Brain-Body Co-Design Problem](#-introduction-of-brain-body-co-design-problem)
  - [🎥 Introduction of our Taxonomy](#-introduction-of-our-taxonomy)
  - [🎥 Quick Menu](#-quick-menu)
- [:star: Bi-Level Co-Design Methods ](#star-bi-level-co-design-methods-)
  - [ EA (Morphology Evolution) + RL(Control Learning) ](#-ea-morphology-evolution--rlcontrol-learning-)
  - [ EA (Morphology Evolution) + Fixed(Control Learning) ](#-ea-morphology-evolution--fixedcontrol-learning-)
  - [Others](#others)
- [:star: End-to-end Co-Design](#star-end-to-end-co-design)
  - [Co-Design with Unknown Environment Dynamics](#co-design-with-unknown-environment-dynamics)
  - [Co-Design with Differentiable Environment Dynamics](#co-design-with-differentiable-environment-dynamics)
- [Brain-Body-Environment Co-Design](#brain-body-environment-co-design)
  - [Others(Actuating Shape-Changed robots)](#othersactuating-shape-changed-robots)
- [Brain-Body Co-Design Benchmarks](#brain-body-co-design-benchmarks)
- [Brain-Body Co-Design in Real World](#brain-body-co-design-in-real-world)
- [Other Surveys Recommended](#other-surveys-recommended)
- [✉ Contact Information](#-contact-information)
- [Star History](#star-history)

Detailed information can be found in our survey paper.

# <a id="1.">:star: Bi-Level Co-Design Methods </a>

## <a id="1.1"> EA (Morphology Evolution) + RL(Control Learning) </a>

|Paper| Published in |Co-Designed Agent|Code&Page|                               
|:---------|:---------------------------------------------------|:-------------:|:-------------|
|[Generating Freeform Endoskeletal Robots](https://arxiv.org/pdf/2412.01036)|**Arxiv 2024**|Endoskeletal Robot|[Page](https://endoskeletal.github.io/)|
|[Leveraging Hyperbolic Embeddings for Coarse-to-Fine Robot Design](https://arxiv.org/pdf/2311.00462)|**ICLR 2024**|Modular Soft Robot|[Code](https://github.com/drdh/HERD)&[Page](https://sites.google.com/view/hyperbolic-robot-design)|
|[Evolving Physical Instinct for Morphology and Control Co-Adaption](https://ieeexplore.ieee.org/abstract/document/10342243)|**IROS 2023**|Legged Robot|N/A|
|[MorphVAE: Advancing Morphological Design of Voxel-Based Soft Robots with Variational Autoencoders](https://ojs.aaai.org/index.php/AAAI/article/view/28904)|**AAAI 2024**|Modular Soft Robot|[Code](https://github.com/WoodySJR/MorphVAE)|
|[Structural Optimization of Lightweight Bipedal Robot via SERL](https://arxiv.org/pdf/2408.15632)|**IROS 2024**|Bipedal Robot|[Page](https://serl-iros2024.github.io/)|
|[CompetEvo: Towards Morphological Evolution from Competition](https://arxiv.org/pdf/2405.18300)|**IJCAI 2024**|Rigid Robot|[Code](https://github.com/KJaebye/competevo)&[Page](https://competevo.github.io/)|
|[Evolution-based Shape and Behavior Co-design of Virtual Agents](https://ieeexplore.ieee.org/abstract/document/10403977)|**IEEE TVCG 2024**|Rigid Robot|N/A|
|[Co-Designing Tools and Control Policies for Robust Manipulation](https://arxiv.org/pdf/2409.11113)|**Arxiv 2024**|Robot Tools|[Page](https://sites.google.com/view/robust-codesign/)|
|[Sample-Efficient Co-Design of Robotic Agents Using Multi-fidelity Training on Universal Policy Network](https://arxiv.org/pdf/2309.04085)|**AI 2024**|Rigid Robot|[Page](https://n-kish.github.io/ecode/)|
|[Effective Design and Interpretation in Voxel-Based Soft Robotics: A Part Assembly Approach with Bayesian Optimization](https://direct.mit.edu/isal/proceedings/isal2024/36/26/123476)|**ALIFE 2024**|Modular Soft Robot|N/A|
|[Evolution of Developmental Plasticity of Soft Virtual Creatures in Changing Environments](https://ieeexplore.ieee.org/document/10611998)|**CEC 2024**|Modular Soft Robot|N/A|
|[GA-based Co-Design Algorithm with Successive Halving](https://ieeexplore.ieee.org/abstract/document/10371512)|**IIAIAAI 2024**|Modular Soft Robot|N/A|

## <a id="1.2"> EA (Morphology Evolution) + Fixed(Control Learning) </a>
|Paper| Published in |Co-Designed Agent|Code&Page|                               
|:---------|:---------------------------------------------------|:-------------:|:-------------|
[A ’MAP’ to find high-performing soft robot designs: Traversing complex design spaces using MAP-elites and Topology Optimization](https://arxiv.org/pdf/2407.07591)|**IROS 2024**|Rigid Manipulator|N/A|
[A Unified Substrate for Body-Brain Co-evolution](https://arxiv.org/pdf/2203.12066)|**GECCO 2022**|Vitual Creature|[Page](https://iclr.cc/virtual/2022/8103)|
[GLSO: Grammar-guided Latent Space Optimization for Sample-efficient Robot Design Automation](https://proceedings.mlr.press/v205/hu23c/hu23c.pdf)|**CoRL 2022**|Rigid-Bodied Robot|[Code](https://github.com/JiahengHu/GLSO)|
|[RoboGrammar: Graph Grammar for Terrain-Optimized Robot Design](https://cdfg.mit.edu/assets/files/robogrammar.pdf) |**SIGGRAPH Asia 2020**|3D Rigid-Bodied Robot|[Code](https://github.com/allanzhao/RoboGrammar)&[Page](https://www.youtube.com/watch?v=JmuLW5So4FU)|
|[A comparative analysis on genome pleiotropy for evolved soft robots](https://dl.acm.org/doi/abs/10.1145/3520304.3528977) |**GECCO 2022**|3D Modular Soft Robot|[Code](https://github.com/Co-Evolve/genome-pleiotropy)|
|[Codesign of Humanoid Robots for Ergonomic Collaboration with Multiple Humans via Genetic Algorithms and Nonlinear Optimization](https://arxiv.org/pdf/2312.07459) |**Humanoids 2023**|Humanoid Robot|[Code](https://github.com/ami-iit/paper_sartore_2023_humanoids_codesign-ga-nl)|
|[Synergizing Morphological Computation and Generative Design: Automatic Synthesis of Tendon-Driven Grippers](https://arxiv.org/pdf/2410.07865) |**IROS 2024**|Tendon-Driven Grippers|[Code](https://github.com/aimclub/rostok)&[Page](https://rostok.readthedocs.io/en/latest/)|
|[Computational Design of Closed-Chain Linkages: Respawn Algorithm for Generative Design](https://ieeexplore.ieee.org/abstract/document/10341425) |**IROS 2023**|Tendon-Driven Grippers|N/A|


## Others
|Paper| Published in |Co-Designed Agent|Code&Page|                               
|:---------|:---------------------------------------------------|:-------------:|:-------------|
[Subtract to adapt: Autotomic robots](https://par.nsf.gov/servlets/purl/10492896)|**RoboSoft 2023**|Modular Soft Robot|N/A|
[A comparison of controller architectures and learning mechanisms for arbitrary robot morphologies](https://arxiv.org/pdf/2309.13908)|**SSCI 2023**|Modular Rigid Robot|N/A|
[How Perception, Actuation, and Communication Impact the Emergence of Collective Intelligence in Simulated Modular Robots](https://ieeexplore.ieee.org/document/10791479)|**ALIFE 2024**|Modular Robot|N/A|
[Co-Optimization of Robot Design and Control: Enhancing Performance and Understanding Design Complexity](https://arxiv.org/pdf/2409.08621)|**Arxiv 2024**|Mixed Robots|[Code](https://github.com/EtorArza/NestedOpt)|
|[Investigating Premature Convergence in Co-optimization of Morphology and Control in Evolved Virtual Soft Robots](https://books.google.com.hk/books?hl=zh-CN&lr=&id=Y4f9EAAAQBAJ&oi=fnd&pg=PA38&ots=IjMl3-hZx0&sig=JnsRuJQAu0ksg_AOW7c0GxXUG1I&redir_esc=y#v=onepage&q&f=false)|**EuroGP 2024**|Modular Soft Robot|N/A|

# :star: End-to-end Co-Design

## Co-Design with Unknown Environment Dynamics
|Paper| Published in |Co-Designed Agent|Code&Page|                               
|:---------|:---------------------------------------------------|:-------------:|:-------------|
|[Curriculum-based co-design of morphology and control of voxel-based soft robots](https://openreview.net/pdf?id=r9fX833CsuN)|**ICLR 2023**|Modular Soft Robot|[Code](https://github.com/Yuxing-Wang-THU/ModularEvoGym)&[Page](https://yuxing-wang-thu.github.io/projects/1_project/)|
|[PreCo: Enhancing Generalization in Co-Design of Modular Soft Robots via Brain-Body Pre-Training](https://proceedings.mlr.press/v229/wang23b/wang23b.pdf)|**CoRL 2023**|Modular Soft Robot|[Code](https://github.com/Yuxing-Wang-THU/ModularEvoGym)&[Page](https://yuxing-wang-thu.github.io/projects/1_project/)|
|[Learning to Design and Use Tools for Robotic Manipulation](https://arxiv.org/pdf/2311.00754)|**CoRL 2023**|Robot Manipulator Tools|[Page](https://robotic-tool-design.github.io/)|

## Co-Design with Differentiable Environment Dynamics
|Paper| Published in |Co-Designed Agent|Code&Page|                               
|:---------|:---------------------------------------------------|:-------------:|:-------------|
|[Making use of design-aware policy optimization in legged-robotics co-design](https://openreview.net/pdf?id=utaVaqRVO4)|**Workshop@CoRL 2024**|Legged Robot|N/A|
|[Computational synthesis of locomotive soft robots by topology optimization](https://www.science.org/doi/pdf/10.1126/sciadv.adn6129)|**Science Advances 2024**|Soft Robot|N/A|
|[4D topology optimization: Integrated optimization of the structure and self-actuation of soft bodies for dynamic motions](https://arxiv.org/pdf/2302.00905)|**Computer Methods in Applied Mechanics and Engineering 2023**|Soft Robot|N/A|
|[DiffuseBot: Breeding Soft Robots With Physics-Augmented Generative Diffusion Models](https://arxiv.org/pdf/2302.00905)|**NIPS 2023**|Soft Gripper|[Code](https://github.com/EvolutionGym/evogym)&[Page](https://diffusebot.github.io/)|
|[Differentiable Soft-Robot Generation](https://dl.acm.org/doi/10.1145/3583131.3590408)|**GECCO 2023**|Soft Robot|N/A|
|[Topology optimization of locomoting soft bodies using material point method](https://arxiv.org/pdf/2203.16793)|**Structural and Multidisciplinary Optimization 2023**|Soft Robot|N/A|
|[Task2Morph: Differentiable Task-inspired Framework for Contact-Aware Robot Design](https://arxiv.org/pdf/2403.19093)|**IROS 2023**|Rigid Robot hand|[Code](https://github.com/Caiyishuai/Task2Morph)|
|[Evolution and learning in differentiable robots](https://arxiv.org/pdf/2405.14712)|**RSS 2024**|Rigid Robot|[Code](https://github.com/lstrgar/ELDiR)&[Page](https://sites.google.com/view/eldir)|
|[Computational co-design of structure and feedback controller for locomoting soft robots](https://arxiv.org/pdf/2407.09270)|**Arxiv 2024**|Soft Robot|[N/A]|

# Brain-Body-Environment Co-Design
|Paper| Published in |Co-Designed Agent|Code&Page|                               
|:---------|:---------------------------------------------------|:-------------:|:-------------|
|[Co-Designing Manipulation Systems Using Task-Relevant Constraints](https://www.static.tu.berlin/fileadmin/www/10002220/Publications/Vaish-22-ICRA.pdf)|**ICRA 2022**|Rigid Manipulator|N/A|
|[LLM-POET: Evolving Complex Environments using Large Language Models](https://arxiv.org/pdf/2406.04663)|**GECCO 2024 Companion**|2D Modular Soft Robot</br>(Voxel-Based Soft Robot)|N/A|
|[Evolving Complex Environments in Evolution Gym using Large Language Models](https://ieeexplore.ieee.org/abstract/document/10626609)|**ICASSPW 2024**|2D Modular Soft Robot</br>(Voxel-Based Soft Robot)|N/A|

## Others(Actuating Shape-Changed robots)
|Paper| Published in |Co-Designed Agent|Code&Page|                               
|:---------|:---------------------------------------------------|:-------------:|:-------------|
|[Shape change and control of pressure-based soft agents](https://direct.mit.edu/isal/proceedings/isal2022/34/37/112294)|**ALIFE 2022**|pressure-based soft robot|[Code](https://github.com/pigozzif/PressureSoftAgents)&[Page](https://pressuresoftagents.github.io/)|
|[DittoGym: Learning to Control Soft Shape-Shifting Robots](https://arxiv.org/pdf/2401.13231)|**ICLR 2024**|Soft Shape-Shifting Robots|[Code](https://github.com/suninghuang19/dittogym)&[Page](https://dittogym.github.io/)|

# <a id="4.">Brain-Body Co-Design Benchmarks</a>

|Benchmark| Co-Design Papers used this benchmark|Agent| Differentiable|                                
|:---------|:---------------------------------------------------|:-------------:|:--:|
|Evolution Gym</br>[Code](https://github.com/EvolutionGym/evogym)&[Page](https://evolutiongym.github.io/)</br>ModularEvoGym</br>[Code](https://github.com/Yuxing-Wang-THU/ModularEvoGym)&[Page](https://github.com/Yuxing-Wang-THU/ModularEvoGym)|[Evolution gym: A large-scale benchmark for evolving soft robots (**NIPS 2021**)](https://arxiv.org/abs/2201.09863)</br>1. [PreCo: Enhancing Generalization in Co-Design of Modular Soft Robots via Brain-Body Pre-Training (**CoRL 2023**)](https://proceedings.mlr.press/v229/wang23b/wang23b.pdf)</br>2. [Rapidly Evolving Soft Robots via Action Inheritance (**IEEE TEC 2024**)](https://ieeexplore.ieee.org/abstract/document/10296048)</br>3. [How the morphology encoding influences the learning ability in body-brain co-optimization (**GECCO 2023**)](https://arts.units.it/retrieve/38193007-3420-4082-8af5-9de6a3385725/2023-GECCO-MorphologyEncodingLearningInVSRs-Post_print.pdf)</br>4. [Curriculum-based co-design of morphology and control of voxel-based soft robots (**ICLR 2023**)](https://openreview.net/pdf?id=r9fX833CsuN)</br>5. [Co-evolving morphology and control of soft robots using a single genome (**SSCI 2022**)](https://arxiv.org/pdf/2212.11517)</br>6. [A Morphological Transfer-Based Multi-Fidelity Evolutionary Algorithm for Soft Robot Design (**IEEE CIM 2024**)](https://ieeexplore.ieee.org/abstract/document/10709670)</br>7. [Lamarckian Co-design of Soft Robots via Transfer Learning (**GECCO 2024**)](https://dl.acm.org/doi/abs/10.1145/3638529.3654180)</br>8. [Investigating Premature Convergence in Co-optimization of Morphology and Control in Evolved Virtual Soft Robots (**EuroGP 2024**)](https://arxiv.org/pdf/2402.09231)</br>9. [MorphVAE: Advancing Morphological Design of Voxel-Based Soft Robots with Variational Autoencoders (**AAAI 2024**)](https://ojs.aaai.org/index.php/AAAI/article/view/28904)</br>10. [LLM-POET: Evolving Complex Environments using Large Language Models (**GECCO 2024 Companion**)](https://arxiv.org/pdf/2406.04663)</br>11. [HeteroMorpheus: Universal Control Based on Morphological Heterogeneity Modeling (**IJCAI 2024**)](https://arxiv.org/pdf/2408.01230)</br>12. [Towards Multi-Morphology Controllers with Diversity and Knowledge Distillation (**GECCO 2024**)](https://dl.acm.org/doi/pdf/10.1145/3638529.3654013)</br>13. [Subtract to adapt: Autotomic robots (**RoboSoft 2023**)](https://par.nsf.gov/servlets/purl/10492896)</br>14. [Comparative studies of evolutionary methods and RL for learning behavior of virtual creatures (**SSCI 2022**)](https://ieeexplore.ieee.org/abstract/document/10022282)</br>15. [Effective Design and Interpretation in Voxel-Based Soft Robotics: A Part Assembly Approach with Bayesian Optimization **(ALIFE 2024)**](https://direct.mit.edu/isal/proceedings/isal2024/36/26/123476)</br>16. [Evolution of Developmental Plasticity of Soft Virtual Creatures in Changing Environments **(CEC 2024)**](https://ieeexplore.ieee.org/document/10611998)</br>17. [GA-based Co-Design Algorithm with Successive Halving **(IIAIAAI 2023)**](https://ieeexplore.ieee.org/abstract/document/10371512)|2D Modular Soft Robot</br>(Voxel-Based Soft Robot)|`No`|
|DiffRedMax (DiffHand)</br>[Code](https://github.com/eanswer/DiffHand)&[Page](https://diffhand.csail.mit.edu/)|[An End-to-End Differentiable Framework for Contact-Aware Robot Design **(RSS 2021)**](https://cdfg.mit.edu/assets/files/robogrammar.pdf)</br>1. [Task2Morph: Differentiable Task-inspired Framework for Contact-Aware Robot Design **(IROS 2023)**](https://ieeexplore.ieee.org/document/10341360)|3D Rigid Contact-Aware Robot|`Yes`|
|RoboGrammar</br>[Code](https://github.com/allanzhao/RoboGrammar)&[Page](https://www.youtube.com/watch?v=JmuLW5So4FU)|[RoboGrammar: Graph Grammar for Terrain-Optimized Robot Design **(SIGGRAPH Asia 2020)**](https://cdfg.mit.edu/assets/files/robogrammar.pdf)</br>1. [GLSO: Grammar-guided Latent Space Optimization for Sample-efficient Robot Design Automation **(CoRL 2022)**](https://proceedings.mlr.press/v205/hu23c/hu23c.pdf)|3D Rigid-Bodied Robot|`No`|
|DiffuseBot</br>[Code]([(https://github.com/zswang666/drive-anywhere))&[Page](https://diffusebot.github.io/)|[DiffuseBot: Breeding Soft Robots With Physics-Augmented Generative Diffusion Models **(NIPS 2023)**](https://openreview.net/pdf?id=1zo4iioUEs)|3D Soft Robot|`Yes`|
|Rostok</br>[Code](https://github.com/aimclub/rostok)&[Page](https://rostok.readthedocs.io/en/latest/)|[Synergizing Morphological Computation and Generative Design: Automatic Synthesis of Tendon-Driven Grippers **(IROS 2024)**](https://arxiv.org/pdf/2410.07865)|3D Rigid Gripper|`No`|
|SoftZoo</br>[Code](https://github.com/zswang666/softzoo)&[Page](https://sites.google.com/view/softzoo-iclr-2023)|[Softzoo: A soft robot co-design benchmark for locomotion in diverse environments **(ICLR 2023)**](https://openreview.net/pdf?id=Xyme9p1rpZw)|3D Soft Robot|`Yes`|
|RoboSumo</br>[Code](https://github.com/openai/robosumo)&[Page](https://sites.google.com/view/adaptation-via-metalearning)|[Continuous adaptation via meta-learning in nonstationary and competitive environments **(ICLR 2018)**](https://arxiv.org/pdf/1710.03641)</br>1. [CompetEvo: Towards Morphological Evolution from Competition **(IJCAI 2024)**](https://arxiv.org/pdf/2405.18300)|3D Rigid Robot|`No`|
|2D-VSR-Sim</br>[Code](https://github.com/giorgia-nadizar/NeuralModelsVSR)&[Page](https://giorgia-nadizar.github.io/NeuralModelsVSR/)</br>2D-MR-Sim</br>[Code](https://github.com/ericmedvet/2dmrsim)&[Page](https://github.com/ericmedvet/2dmrsim)</br>2D-Robot-Evolution</br>[Code](https://github.com/ericmedvet/2d-robot-evolution/)&[Page](https://github.com/ericmedvet/2d-robot-evolution/)|[2D-VSR-Sim: a Simulation Tool for the Optimization of 2-D Voxel-based Soft Robots **(SoftwareX 2020)**](https://medvet.inginf.units.it/publications/2020-j-mbds-vsr/)</br>1. [An experimental comparison of evolved neural network models for controlling simulated modular soft robots (**Applied Soft Computing**)](https://www.sciencedirect.com/science/article/pii/S1568494623006282) </br>2. [On the Schedule for Morphological Development of Evolved Modular Soft Robots (**EuroGP 2022**)](https://medvet.inginf.units.it/publications/2022-c-nmm-schedule/)</br>3. [Optimizing the Sensory Apparatus of Voxel-based Soft Robots through Evolution and Babbling (**Springer Nature Computer Science 2022**)](https://medvet.inginf.units.it/publications/2021-j-fmi-optimizing/)</br>4. [Merging Pruning and Neuroevolution: towards Robust and Efficient Controllers for Modular Soft Robots (**KER 2021**)](https://medvet.inginf.units.it/publications/2021-j-nmnhpz-merging/)</br>5. [Evolving Hebbian Learning Rules in Voxel-based Soft Robots **(IEEE TechRxiv 2021)**](https://medvet.inginf.units.it/publications/2021-p-fimp-evolving/)</br>6. [On the Effects of Pruning on Evolved Neural Controllers for Soft Robots **(NEWK@GECCO 2021)**](https://medvet.inginf.units.it/publications/2021-c-nmpzn-effects/)</br>7. [Criticality-driven Evolution of Adaptable Morphologies of Voxel-Based Soft-Robots **(Frontiers in Robotics and AI 2021)**](https://medvet.inginf.units.it/publications/2021-j-tmn-criticality/)</br>8. [Biodiversity in Evolved Voxel-based Soft Robots **(GECCO 2021)**](https://medvet.inginf.units.it/publications/2021-c-mbpr-biodiversity/)</br>9. [Beyond Body Shape and Brain: Evolving the Sensory Apparatus of Voxel-based Soft Robots **(EvoAPPS 2021)**](https://medvet.inginf.units.it/publications/2021-c-fim-beyond/)</br>10. [Evolution of Distributed Neural Controllers for Voxel-based Soft Robots **(GECCO 2020)**](https://medvet.inginf.units.it/publications/2020-c-mbdf-evolution/)</br>11. [Evolving Modular Soft Robots without Explicit Inter-Module Communication using Local Self-Attention **(GECCO 2022)**](https://softrobots.github.io/)</br>12. [No-brainer: Morphological Computation driven Adaptive Behavior in Soft Robots **(SAB 2024)**](https://arxiv.org/pdf/2407.16613)|Modular Soft Robot|`No`|
|Sorotoki</br>[Code](https://github.com/BJCaasenbrood/SorotokiCode)&[Page](https://bjcaasenbrood.github.io/SorotokiCode/)|[Sorotoki: A Matlab Toolkit for Design, Modeling, and Control of Soft Robots **(IEEE ACCESS)**](https://openreview.net/pdf?id=1zo4iioUEs)|Soft Robot|`No`|


# <a id="4.">Brain-Body Co-Design in Real World</a>
|Paper| Published in |Co-Designed Agent|                               
|:---------|:---------------------------------------------------|:-------------:|
|[Soft Robots Learn to Crawl: Jointly Optimizing Design and Control with Sim-to-Real Transfer](https://arxiv.org/pdf/2202.04575)|**RSS 2022**|Soft Robot|
|[DiffuseBot: Breeding Soft Robots With Physics-Augmented Generative Diffusion Models](https://openreview.net/pdf?id=1zo4iioUEs)|**NIPS 2023**|Soft Robot|
[Computational synthesis of locomotive soft robots by topology optimization](https://www.science.org/doi/pdf/10.1126/sciadv.adn6129)|**Science Advances 2024**|Soft Robot|
[Co-Designing Manipulation Systems Using Task-Relevant Constraints](https://www.static.tu.berlin/fileadmin/www/10002220/Publications/Vaish-22-ICRA.pdf)|**ICRA 2022**|Rigid Manipulator|
[A ’MAP’ to find high-performing soft robot designs: Traversing complex design spaces using MAP-elites and Topology Optimization](https://arxiv.org/pdf/2407.07591)|**IROS 2024**|Rigid Manipulator|
[Using neuroevolution for designing soft medical devices](https://www.sciencedirect.com/science/article/pii/S2667379724000639)|**BIR 2024**|Soft Medical Device|
|[Structural Optimization of Lightweight Bipedal Robot via SERL](https://arxiv.org/pdf/2408.15632)|**IROS 2024**|Bipedal Robot|[Page](https://serl-iros2024.github.io/)|
|[Evolution and learning in differentiable robots](https://arxiv.org/pdf/2405.14712)|**RSS 2024**|Rigid Robot|[Code](https://github.com/lstrgar/ELDiR)&[Page](https://sites.google.com/view/eldir)|
|[Co-Designing Tools and Control Policies for Robust Manipulation](https://arxiv.org/pdf/2409.11113)|**Arxiv 2024**|Robot Tools|[Page](https://sites.google.com/view/robust-codesign/)|

# <a id="4.">Other Surveys Recommended</a>
- [Exploring Embodied Intelligence in Soft Robotics: A Review](https://www.mdpi.com/2313-7673/9/4/248)</br>Zikai Zhao, et al., 2024, Bio-Inspired and Biomimetic Intelligence in Robotics  
- [Collective Intelligence for Deep Learning: A Survey of Recent Developments](https://journals.sagepub.com/doi/pdf/10.1177/26339137221114874)</br>David Ha and Yujin Tang, 2022, Collective Intelligence  
- [Bridging evolutionary algorithms and reinforcement learning: A comprehensive survey on hybrid algorithms](https://ieeexplore.ieee.org/abstract/document/10637292)</br>Pengyi Li and Jianye Hao, et al., 2022, IEEE Transactions on Evolutionary Computation  
- [Design Optimization of Soft Robots: A Review of the State of the Art](https://ieeexplore.ieee.org/document/9237112)</br>FeiFei Chen and Michael Yu Wang, 2022, IEEE Robotics & Automation Magazine  
    
# <a id="4.">✉ Contact Information</a>
This repo is developed and maintained by [Yuxing Wang](https://yuxing-wang-thu.github.io/).

For any questions, please feel free to email `wyx20@tsinghua.org.cn`.

# Star History
[![Star History Chart](https://api.star-history.com/svg?repos=Yuxing-Wang-THU/Awesome-Brain-Body-Co-Design-of-Embodied-Agents&type=Date)](https://star-history.com/#Yuxing-Wang-THU/Awesome-Brain-Body-Co-Design-of-Embodied-Agents)