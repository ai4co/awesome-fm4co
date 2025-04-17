<h1 align="center">Foundation Models for Combinatorial Optimization</h1>

FM4CO contains interesting research papers (1) using **Existing Large Language Models for Combinatorial Optimization**, and (2) building **Domain Foundation Models for Combinatorial Optimization**.

----

### LLMs for Combinatorial Optimization

Most research utilizes existing FMs from language and vision domains to generate/improve solutions\* or algorithms\* (hyper-heuristic), yielding impressive results when integrated with problem-specific heuristics or general meta-heuristics. Other studies employ LLMs to investigate the interpretability\* of COP solvers, automate problem formulation*, or simplify the use of domain-specific tools through text prompts. Given the capabilities of LLMs, this area of research is likely to garner increasing interest.

|  Date   |                            Paper                             |                             Link                             |        Problem        |     Venue      |     Remark*      |
| :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: | :-------------------: | :------------: | :--------------: |
| 2023.07 | [Large Language Models for Supply Chain Optimization](https://arxiv.org/pdf/2307.03875) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/microsoft/OptiGuide) | `Supply_Chain` | *arXiv* | Algorithm w. Interpretability |
| 2023.09 | [Can Language Models Solve Graph Problems in Natural Language?](https://arxiv.org/pdf/2305.10037) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/Arthur-Heng/NLGraph) |        `Graph`        | *NeurIPS 2023* |     Solution     |
| 2023.09 | [Large Language Models as Optimizers](https://arxiv.org/pdf/2309.03409) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/google-deepmind/opro) |         `TSP`         |  *ICLR 2024*   |     Solution     |
| 2023.10 | [Chain-of-Experts: When LLMs Meet Complex Operations Research Problems](https://openreview.net/pdf?id=HobyL1B9CZ) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/xzymustbexzy/Chain-of-Experts) |        `MILP`         |  *ICLR 2024*   |    Formulation    |
| 2023.10 | [OptiMUS: Scalable Optimization Modeling with (MI)LP Solvers and Large Language Models](https://arxiv.org/pdf/2402.10172) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/teshnizi/OptiMUS) |        `MILP`         |  *ICML 2024*   |    Formulation    |
| 2023.10 | [AI-Copilot for Business Optimisation: A Framework and A Case Study in Production Scheduling](https://arxiv.org/pdf/2309.13218) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/pivithuruthejanamarasinghe/AI-Copilot-Data) |        `JSSP`         |    *arXiv*    |    Formulation    |
| 2023.11 | [Large Language Models as Evolutionary Optimizers](https://arxiv.org/pdf/2310.19046) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/cschen1205/LMEA) |         `TSP`         | *CEC 2024* |     Solution     |
| 2023.11 | [Algorithm Evolution Using Large Language Model](https://arxiv.org/pdf/2311.15249) |                                             &emsp;&emsp;&emsp;                 |         `TSP`         |    *arXiv*    |    Algorithm     |
| 2023.12 | [Mathematical discoveries from program search with large language models](https://www.nature.com/articles/s41586-023-06924-6) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/google-deepmind/funsearch) |         `BPP`         |    *Nature*    |    Algorithm     |
| 2023.12 | [NPHardEval: Dynamic Benchmark on Reasoning Ability of Large Language Models via Complexity Classes](https://arxiv.org/pdf/2312.14890) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/casmlab/NPHardEval) | `TSP,KP, GCP,MSP` | *ACL 2024* | Benchmark |
| 2024.02 | [ReEvo: Large Language Models as Hyper-Heuristics with Reflective Evolution](https://arxiv.org/pdf/2402.01145) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/ai4co/reevo) <br> [![Project-Page](https://img.shields.io/badge/Page-74aa9c?style=for-the-badge)](https://github.com/ai4co/reevo) | `TSP,VRP,OP, MKP,BPP,EDA` |    *NeurIPS 2024*    |    Algorithm     |
| 2024.02 | [AutoSAT: Automatically Optimize SAT Solvers via Large Language Models](https://arxiv.org/pdf/2402.10705) |                                                              |         `SAT`         |    *arXiv*    |    Algorithm     |
| 2024.02 | [From Large Language Models and Optimization to Decision Optimization CoPilot: A Research Manifesto](https://arxiv.org/pdf/2402.16269) |                                                              |        `MILP`         |    *arXiv*    |    Formulation    |
| 2024.03 | [How Multimodal Integration Boost the Performance of LLM for Optimization: Case Study on Capacitated Vehicle Routing Problems](https://arxiv.org/pdf/2403.01757) |  |         `VRP`         |    *arXiv*    |     Solution     |
| 2024.03 | [RouteExplainer: An Explanation Framework for Vehicle Routing Problem](https://arxiv.org/pdf/2403.03585.pdf) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/ntt-dkiku/route-explainer) <br> [![Project-Page](https://img.shields.io/badge/Page-74aa9c?style=for-the-badge)](https://ntt-dkiku.github.io/xai-vrp) |         `VRP`         |  *PAKDD 2024*  | Interpretability |
| 2024.03 | [Can Large Language Models Solve Robot Routing?](https://arxiv.org/pdf/2403.10795) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/Zhehui-Huang/LLM_Routing) <br> [![Project-Page](https://img.shields.io/badge/Page-74aa9c?style=for-the-badge)](https://sites.google.com/view/words-to-routes) |         `TSP,VRP`         |    *arXiv*    |    Algorithm     |
| 2024.05 | [Evolution of Heuristics: Towards Efficient Automatic Algorithm Design Using Large Language Model](https://arxiv.org/pdf/2401.02051) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/FeiLiu36/EoH) | `TSP,BPP, FSSP` |  *ICML 2024*   |    Algorithm     |
| 2024.05 | [ORLM: Training Large Language Models for Optimization Modeling](https://arxiv.org/pdf/2405.17743) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/Cardinal-Operations/ORLM) | `General OPT` | *Operations Research* | Formulation |
| 2024.05 | [Self-Guiding Exploration for Combinatorial Problems](https://arxiv.org/pdf/2405.17950) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/Zangir/LLM-for-CP) | `TSP,VRP,BPP, AP,KP,JSSP` | *NeurIPS 2024* | Solution |
| 2024.06 | [Eyeballing Combinatorial Problems: A Case Study of Using Multimodal Large Language Models to Solve Traveling Salesman Problems](https://arxiv.org/pdf/2406.06865) |  | `TSP` | *ISBCom 2024* | Solution |
| 2024.07 | [Visual Reasoning and Multi-Agent Approach in Multimodal Large Language Models (MLLMs): Solving TSP and mTSP Combinatorial Challenges](https://arxiv.org/pdf/2407.00092) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/ahmed-abdulhuy/Solving-TSP-and-mTSP-Combinatorial-Challenges-using-Visual-Reasoning-and-Multi-Agent-Approach-MLLMs-) | `TSP,mTSP` | *arXiv* | Solution |
| 2024.07 | [Solving General Natural-Language-Description Optimization Problems with Large Language Models](https://arxiv.org/pdf/2407.07924) | [![Code](https://img.shields.io/badge/Demo-74aa9c?style=for-the-badge)](https://opt.alibabacloud.com/chat) | `MILP` | *NAACL 2024* | Formulation |
| 2024.08 | [Diagnosing Infeasible Optimization Problems Using Large Language Models](https://arxiv.org/pdf/2308.12923) |  | `MILP` | *INFOR* | Formulation |
| 2024.08 | [LLMs can Schedule](https://arxiv.org/pdf/2408.06993) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/starjob42/datasetjsp) | `JSSP` | *arXiv* | Solution |
| 2024.09 | [Multi-objective Evolution of Heuristic Using Large Language Model](https://arxiv.org/pdf/2409.16867) |  | `TSP,BPP` | *AAAI 2025* | Algorithm |
| 2024.10 | [Towards Foundation Models for Mixed Integer Linear Programming](https://arxiv.org/pdf/2410.08288) |  |          `MILP`           |    *ICLR 2025*    | Formulation |
| 2024.10 | [LLMOPT: Learning to Define and Solve General Optimization Problems from Scratch](https://arxiv.org/pdf/2410.13213) | | `General OPT` | *ICLR 2025* | Formulation |
| 2024.10 | [Large Language Model-driven Large Neighborhood Search for Large-Scale MILP Problems](https://openreview.net/forum?id=Usk4KzBxLW) | | `MILP` | *Under Review* | Algorithm |
| 2024.10 | [HeurAgenix: A Multi-Agent LLM-Based Paradigm for Adaptive Heuristic Evolution and Selection in Combinatorial Optimization](https://openreview.net/forum?id=xxSK3ZNAhh) | | `TSP,CVRP,JSSP, MaxCut,MKP` | *Under Review* | Algorithm |
| 2024.10 | [Efficient Heuristics Generation for Solving Combinatorial Optimization Problems Using Large Language Models](https://openreview.net/forum?id=0fwJMANq9P) | | `TSP,CVRP, BPP,MKP` | *Under Review* | Algorithm |
| 2024.10 | [OptiBench: Benchmarking Large Language Models in Optimization Modeling with Equivalence-Detection Evaluation](https://openreview.net/forum?id=KD9F5Ap878) | | `MILP` | *Under Review* | Benchmark |
| 2024.10 | [OptiBench Meets ReSocratic: Measure and Improve LLMs for Optimization Modeling](https://openreview.net/forum?id=fsDZwS49uY) | | `MILP` | *ICLR 2025* | Benchmark |
| 2024.10 | [DRoC: Elevating Large Language Models for Complex Vehicle Routing via Decomposed Retrieval of Constraints](https://openreview.net/forum?id=s9zoyICZ4k) | | `48VRPs` | *ICLR 2025* | Formulation |
| 2024.10 | [STARJOB: Dataset for LLM-Driven Job Shop Scheduling](https://openreview.net/forum?id=z4Ho599uOL) | | `JSSP` | *Under Review* | Solution |
| 2024.10 | [LLM4Solver: Large Language Model for Efficient Algorithm Design of Combinatorial Optimization Solver](https://openreview.net/forum?id=XTxdDEFR6D) | | `MILP` | *Under Review* | Algorithm |
| 2024.10 | [Unifying All Species: LLM-based Hyper-Heuristics for Multi-objective Optimization](https://openreview.net/forum?id=sUywd7UhFT) | | `TSP` | *Under Review* | Algorithm |
| 2024.10 | [Evo-Step: Evolutionary Generation and Stepwise Validation for Optimizing LLMs in OR](https://openreview.net/forum?id=aapUBU9U0D) | | `MILP` | *Under Review* | Formulation |
| 2024.10 | [Automatic programming via large language models with population self-evolution for dynamic job shop scheduling problem](https://arxiv.org/pdf/2410.22657) | | `DyJSSP` | *arXiv* | Algorithm |
| 2024.11 | [Large Language Models for Combinatorial Optimization of Design Structure Matrix](https://arxiv.org/pdf/2411.12571) | | `DSM` | *arXiv* | Solution |
| 2024.12 | [HSEvo: Elevating Automatic Heuristic Design with Diversity-Driven Harmony Search and Genetic Algorithm Using LLMs](https://arxiv.org/pdf/2412.14995) |[![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/datphamvn/HSEvo) | `TSP,BPP,OP` | *AAAI 2025* | Algorithm |
| 2024.12 | [Evaluating LLM Reasoning in the Operations Research Domain with ORQA](https://arxiv.org/pdf/2412.17874) |[![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/nl4opt/ORQA) | `General OR` | *AAAI 2025* | Benchmark |
| 2025.01 | [Monte Carlo Tree Search for Comprehensive Exploration in LLM-Based Automatic Heuristic Design](https://arxiv.org/pdf/2501.08603) |[![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/zz1358m/MCTS-AHD-master) | `TSP,CVRP,KP, BPP,MKP,ASP` | *arXiv* | Algorithm |
| 2025.01 | [Bridging Visualization and Optimization: Multimodal Large Language Models on Graph-Structured Combinatorial Optimization](https://arxiv.org/pdf/2501.11968) || `Influence Maximization, Network Dismantling` | *arXiv* | Algorithm |
| 2025.01 | [Can Large Language Models Be Trusted as Black-Box Evolutionary Optimizers for Combinatorial Problems?](https://arxiv.org/pdf/2501.15081) || `Influence Maximization` | *arXiv* | Algorithm |
| 2025.02 | [Improving Existing Optimization Algorithms with LLMs](https://arxiv.org/pdf/2502.08298) || `MIS` | *arXiv* | Algorithm |
| 2025.02 | [Planning of Heuristics: Strategic Planning on Large Language Models with Monte Carlo Tree Search for Automating Heuristic Optimization](https://arxiv.org/pdf/2502.11422) || `TSP,FSSP` | *arXiv* | Algorithm |
| 2025.02 | [GraphThought: Graph Combinatorial Optimization with Thought Generation](https://arxiv.org/pdf/2502.11607) || `MIS,MVC,TSP` | *arXiv* | Algorithm |
| 2025.02 | [EquivaMap: Leveraging LLMs for Automatic Equivalence Checking of Optimization Formulations](https://arxiv.org/pdf/2502.14760) |[![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/HumainLab/EquivaMap)| `MILP` | *arXiv* | Algorithm |
| 2025.02 | [ARS: Automatic Routing Solver with Large Language Models](https://arxiv.org/pdf/2502.15359) |[![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/Ahalikai/ARS-Routbench)| `VRP` | *arXiv* | Benchmark & Algorithm |
| 2025.02 | [Text2Zinc: A Cross-Domain Dataset for Modeling Optimization and Satisfaction Problems in MiniZinc](https://arxiv.org/pdf/2503.10642) | [![Data](https://img.shields.io/badge/Data-20B2AA?style=for-the-badge)](https://huggingface.co/datasets/skadio/text2zinc)| `LP,MIP,CP` | *arXiv* | Formulation (Dataset) |
| 2025.02 | [GraphArena: Evaluating and Exploring Large Language Models on Graph Computation](https://openreview.net/pdf?id=Y1r9yCMzeA) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/squareRoot3/GraphArena/tree/master) | `MVC,MIS,MCP,TSP,MCS,GED` | *ICLR 2025* | Benchmark & Dataset & Model|
| 2025.03 | [Leveraging Large Language Models to Develop Heuristics for Emerging Optimization Problems](https://arxiv.org/pdf/2503.03350) |[![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/nico-koltermann/contextual-evolution-of-heuristics)| `UPMP` | *arXiv* | Algorithm |
| 2025.03 | [OR-LLM-Agent: Automating Modeling and Solving of Operations Research Optimization Problem with Reasoning Large Language Model](https://arxiv.org/pdf/2503.10009) |[![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/bwz96sco/or_llm_agent)| `OP` | *arXiv* | Formulation |
| 2025.03 | [Combinatorial Optimization for All: Using LLMs to Aid Non-Experts in Improving Optimization Algorithms](https://arxiv.org/pdf/2503.10968) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/camilochs/comb-opt-for-all)<br> [![Project-Page](https://img.shields.io/badge/Page-74aa9c?style=for-the-badge)](https://camilochs.github.io/comb-opt-for-all/)| `TSP` | *arXiv* | Algorithm |
| 2025.03 | [Automatic MILP Model Construction for Multi-Robot Task Allocation and Scheduling Based on Large Language Models](https://arxiv.org/pdf/2503.13813) || `MILP` | *arXiv* | Formulation |
| 2025.03 | [Code Evolution Graphs: Understanding Large Language Model Driven Design of Algorithms](https://arxiv.org/pdf/2503.16668) || `BBO, TSP, BPP` | *arXiv* | Interpretability |
| 2025.04 | [CO-Bench: Benchmarking Language Model Agents in Algorithm Search for Combinatorial Optimization](https://arxiv.org/pdf/2504.04310) || `General COP` | *arXiv* | Benchmark |
| 2025.04 | [Algorithm Discovery With LLMs: Evolutionary Search Meets Reinforcement Learning](https://arxiv.org/pdf/2504.05108) || `BP, TSP, FP` | *arXiv* | Algorithm |

----

### Domain FMs for Combinatorial Optimization

Developing a domain FM capable of solving a wide range of COPs presents an intriguing and formidable challenge. Recent efforts in this area aim towards this ambitious goal by creating a unified architecture or representation applicable across various COPs.

|  Date   |                            Paper                             |                             Link                             |                 Problem                  |    Venue     |
| :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------------------------------------: | :----------: |
| 2022.08 | [One Model, Any CSP: Graph Neural Networks as Fast Global Search Heuristics for Constraint Satisfaction](https://arxiv.org/pdf/2208.10227) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/toenshoff/ANYCSP) | `CSP` | *IJCAI 2023* |
| 2023.05 | [Efficient Training of Multi-task Combinatorial Neural Solver with Multi-armed Bandits](https://arxiv.org/pdf/2305.06361) |                      &emsp;&emsp;&emsp;                      |             `TSP,VRP,OP,KP`              |   *arXiv*    |
| 2024.02 | [Multi-Task Learning for Routing Problem with Cross-Problem Zero-Shot Generalization](https://arxiv.org/pdf/2402.16891) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/FeiLiu36/MTNCO) |                 `16VRPs`                 |  *KDD 2024*  |
| 2024.03 | [Towards a Generic Representation of Combinatorial Problems for Learning-Based Approaches](https://arxiv.org/pdf/2403.06026) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/corail-research/learning-generic-csp) |             `SAT,TSP,COL,KP`             |   *CPAIOR 2024*    |
| 2024.04 | [Cross-Problem Learning for Solving Vehicle Routing Problems](https://arxiv.org/pdf/2404.11677) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/Zhuoyi-Lin/Cross_problem_learning) |              `TSP,OP,PCTSP`              | *IJCAI 2024* |
| 2024.05 | [MVMoE: Multi-Task Vehicle Routing Solver with Mixture-of-Experts](https://arxiv.org/pdf/2405.01029) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/RoyalSkye/Routing-MVMoE) |                 `16VRPs`                 | *ICML 2024*  |
| 2024.06 | [RouteFinder: Towards Foundation Models for Vehicle Routing Problems](https://arxiv.org/pdf/2406.15007) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/ai4co/routefinder) <br> [![Project-Page](https://img.shields.io/badge/Page-74aa9c?style=for-the-badge)](https://ai4co.github.io/routefinder/) |                 `24VRPs`                 |    *ICML 2024 Workshop on FM*    |
| 2024.06 | [GOAL: A Generalist Combinatorial Optimization Agent Learner](https://arxiv.org/pdf/2406.15079) |          [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/naver/goal-co)                                              | `(A)TSP,5VRPs,OP,JSSP, OSSP,UMSP,KP,MVC, MIS,MCLP,TRP,SOP` |   *ICLR 2025*   |
| 2024.08 | [UNCO: Towards Unifying Neural Combinatorial Optimization through Large Language Model](https://arxiv.org/pdf/2408.12214) |                                                              |        `TSP,CVRP,KP, MVCP,SMTWTP`        |   *arXiv*    |
| 2024.09 | [MAPF-GPT: Imitation Learning for Multi-Agent Pathfinding at Scale](https://arxiv.org/pdf/2409.00134) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/Cognitive-AI-Systems/MAPF-GPT) |                  `MAPF`                  |   *AAAI 2025*    |
| 2024.10 | [Toward Learning Generalized Cross-Problem Solving Strategies for Combinatorial Optimization](https://openreview.net/forum?id=VnaJNW80pN) | |                  `TSP,VRP,SDVRP, OP,PCTSP,SPCTSP`                  |   *Under Review*   |
| 2024.10 | [Learning General Representations Across Graph Combinatorial Optimization Problems](https://openreview.net/forum?id=elmTU101oS) | |                  `7GDPs`                  | *Under Review* |
| 2024.10 | [Solving Diverse Combinatorial Optimization Problems with a Unified Model](https://openreview.net/forum?id=Kc3yoIL5oR) | |                  `(A)TSP,CVRP,OP,PCTSP, SPCTSP,KP,MIS,FFSP`                  | *Under Review* |
| 2024.10 | [SHIELD: Multi-task Multi-distribution Vehicle Routing Solver with Sparsity & Hierarchy in Efficiently Layered Decoder](https://openreview.net/forum?id=AMbIvaD4Rr) | | `16VRPs` | *Under Review* |
| 2024.10 | [Unified Neural Solvers for General TSP and Multiple Combinatorial Optimization Tasks via Problem Reduction and Matrix Encoding](https://openreview.net/forum?id=yEwakMNIex) | | `(A)TSP,DHCP, 3SAT` | *ICLR 2025* |
| 2024.11 | [CaDA: Cross-Problem Routing Solver with Constraint-Aware Dual-Attention](https://arxiv.org/pdf/2412.00346) | | `16VRPs` | *arXiv* |
| 2024.12 | [Multi-task Representation Learning for Mixed Integer Linear Programming](https://arxiv.org/pdf/2412.14409) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/caidog1129/MILP_multitask) | `MILP` | *arXiv* |

