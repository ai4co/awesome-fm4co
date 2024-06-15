<h1 align="center">Foundation Models for Combinatorial Optimization</h1>

FM4CO contains interesting research papers (1) using **Existing Large Language Models for Combinatorial Optimization**, and (2) building **Domain Foundation Models for Combinatorial Optimization**.

----

### LLMs for Combinatorial Optimization

Most research utilizes existing LLMs to generate/improve solutions\*, algorithms\* (hyper-heuristic), or parameters\* (hyper-network), yielding impressive results when integrated with problem-specific heuristics or general meta-heuristics. Other studies employ LLMs to investigate the interpretability\* of COP solvers, automate problem formulation, or simplify the use of domain-specific tools through text prompts. Given the capabilities of LLMs, this area of research is likely to garner increasing interest. Currently, we mainly focus on the below problems, and may include more variants (e.g., graph-based COPs) as the community grows:

* Traveling Salesman Problem
* Vehicle Routing Problem
* Scheduling Problem
* (Mixed) Integer Linear Programming

|  Date   |                            Paper                             |                             Link                             |        Problem        |     Venue      |     Remark*      |
| :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: | :-------------------: | :------------: | :--------------: |
| 2023.09 | [Can Language Models Solve Graph Problems in Natural Language?](https://arxiv.org/pdf/2305.10037) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/Arthur-Heng/NLGraph) |        `Graph`        | *NeurIPS 2023* |     Solution     |
| 2023.09 | [Large Language Models as Optimizers](https://arxiv.org/pdf/2309.03409) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/google-deepmind/opro) |         `TSP`         |  *ICLR 2024*   |     Solution     |
| 2023.10 | [Chain-of-Experts: When LLMs Meet Complex Operations Research Problems](https://openreview.net/pdf?id=HobyL1B9CZ) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/xzymustbexzy/Chain-of-Experts) |        `MILP`         |  *ICLR 2024*   |    Automation    |
| 2023.10 | [OptiMUS: Scalable Optimization Modeling with (MI)LP Solvers and Large Language Models](https://arxiv.org/pdf/2402.10172) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/teshnizi/OptiMUS) |        `MILP`         |  *ICML 2024*   |    Automation    |
| 2023.10 | [AI-Copilot for Business Optimisation: A Framework and A Case Study in Production Scheduling](https://arxiv.org/pdf/2309.13218) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/pivithuruthejanamarasinghe/AI-Copilot-Data) |        `JSSP`         |    *ArXiv*     |    Automation    |
| 2023.11 | [Large Language Models as Evolutionary Optimizers](https://arxiv.org/pdf/2310.19046) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/cschen1205/LMEA) |         `TSP`         | *CEC 2024* |     Solution     |
| 2023.11 | [Algorithm Evolution Using Large Language Model](https://arxiv.org/pdf/2311.15249) |                                             &emsp;&emsp;&emsp;                 |         `TSP`         |    *ArXiv*     |    Algorithm     |
| 2023.12 | [Mathematical discoveries from program search with large language models](https://www.nature.com/articles/s41586-023-06924-6) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/google-deepmind/funsearch) |         `BPP`         |    *Nature*    |    Algorithm     |
| 2024.02 | [Large Language Models as Hyper-Heuristics for Combinatorial Optimization](https://arxiv.org/pdf/2402.01145) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/ai4co/LLM-as-HH) | `TSP,VRP,OP, MKP,BPP,EDA` |    *ArXiv*     |    Algorithm     |
| 2024.02 | [AutoSAT: Automatically Optimize SAT Solvers via Large Language Models](https://arxiv.org/pdf/2402.10705) |                                                              |         `SAT`         |    *ArXiv*     |    Algorithm     |
| 2024.02 | [From Large Language Models and Optimization to Decision Optimization CoPilot: A Research Manifesto](https://arxiv.org/pdf/2402.16269) |                                                              |        `MILP`         |    *ArXiv*     |    Automation    |
| 2024.03 | [How Multimodal Integration Boost the Performance of LLM for Optimization: Case Study on Capacitated Vehicle Routing Problems](https://arxiv.org/pdf/2403.01757) |                                                              |         `VRP`         |    *ArXiv*     |     Solution     |
| 2024.03 | [RouteExplainer: An Explanation Framework for Vehicle Routing Problem](https://arxiv.org/pdf/2403.03585.pdf) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/ntt-dkiku/route-explainer) <br> [![Project-Page](https://img.shields.io/badge/Page-74aa9c?style=for-the-badge)](https://ntt-dkiku.github.io/xai-vrp) |         `VRP`         |  *PAKDD 2024*  | Interpretability |
| 2024.03 | [From Words to Routes: Applying Large Language Models to Vehicle Routing](https://arxiv.org/pdf/2403.10795) | [![Project-Page](https://img.shields.io/badge/Page-74aa9c?style=for-the-badge)](https://sites.google.com/view/words-to-routes) |         `VRP`         |    *ArXiv*     |    Algorithm     |
| 2024.05 | [Evolution of Heuristics: Towards Efficient Automatic Algorithm Design Using Large Language Model](https://arxiv.org/pdf/2401.02051) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/FeiLiu36/EoH) | `TSP`,`BPP`, `FSSP`  |  *ICML 2024*   |    Algorithm     |
| 2024.05 | [Self-Guiding Exploration for Combinatorial Problems](https://arxiv.org/pdf/2405.17950) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/Zangir/LLM-for-CP) | `TSP`,`VRP`,`BPP`, `AP`,`KP`,`JSSP` | *ArXiv* | Solution |
| 2024.06 | [Eyeballing Combinatorial Problems: A Case Study of Using Multimodal Large Language Models to Solve Traveling Salesman Problems](https://arxiv.org/pdf/2406.06865) |  | `TSP` | *ArXiv* | Solution |

----

### Domain FMs for Combinatorial Optimization

Developing a domain foundation model capable of solving a wide range of COPs presents an intriguing and formidable challenge. Recent efforts in this area aim towards this ambitious goal by creating a unified architecture* or representation* applicable across various COPs.

|  Date   |                            Paper                             |                             Link                             |       Problem       |    Venue     |    Remark*     |        Paradigm         |
| :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: | :-----------------: | :----------: | :------------: | :---------------------: |
| 2023.05 | [Efficient Training of Multi-task Combinatorial Neural Solver with Multi-armed Bandits](https://arxiv.org/pdf/2305.06361) |                      &emsp;&emsp;&emsp;                      |  `TSP,VRP, OP,KP`   |   *ArXiv*    |  Architecture  |                         |
| 2024.02 | [Multi-Task Learning for Routing Problem with Cross-Problem Zero-Shot Generalization](https://arxiv.org/pdf/2402.16891) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/FeiLiu36/MTNCO) |        `VRP`        |  *KDD 2024*  |  Architecture  | Compositional Zero-Shot |
| 2024.03 | [Towards a Generic Representation of Combinatorial Problems for Learning-Based Approaches](https://arxiv.org/pdf/2403.06026) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/corail-research/learning-generic-csp) |  `SAT,TSP, COL,KP`  |   *ArXiv*    | Representation |                         |
| 2024.04 | [Cross-Problem Learning for Solving Vehicle Routing Problems](https://arxiv.org/pdf/2404.11677) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/Zhuoyi-Lin/Cross_problem_learning) | `TSP`,`OP`, `PCTSP` | *IJCAI 2024* |  Architecture  |  Efficient Fine-Tuning  |
| 2024.05 | [MVMoE: Multi-Task Vehicle Routing Solver with Mixture-of-Experts](https://arxiv.org/pdf/2405.01029) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/RoyalSkye/Routing-MVMoE) |        `VRP`        | *ICML 2024*  |  Architecture  |                         |
