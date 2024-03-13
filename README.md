<h1 align="center">Foundation Models for Combinatorial Optimization</h1>

FM4CO contains interesting research papers (1) using **Existing Large Language Models for Combinatorial Optimization**, and (2) building **Domain Foundation Models for Combinatorial Optimization**.

----

### LLMs for Combinatorial Optimization

Most work uses existing LLMs to generate/improve solutions\*, algorithms\* (hyper-heuristic), or parameters\* (hyper-network), achieving remarkable performance when combined with problem-specific heuristics or general meta-heuristics. Other work leverages LLMs to explore the interpretability\* of COP solvers, or to achieve automation\* of problem formulation or domain tools's usage through text prompts. This research direction may receive increasing attention due to the power of LLMs. Currently, we mainly focus on the below problems, and may include more variants (e.g., graph-based COPs) as the community grows:

* Traveling Salesman Problem
* Vehicle Routing Problem
* Scheduling Problem
* (Mixed) Integer Linear Programming

|  Date   |                            Paper                             |                             Link                             |        Problem        |     Venue      |     Remark*      |
| :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: | :-------------------: | :------------: | :--------------: |
| 2023.09 | [Can Language Models Solve Graph Problems in Natural Language?](https://arxiv.org/pdf/2305.10037.pdf) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/Arthur-Heng/NLGraph) |        `Graph`        | *NeurIPS 2023* |     Solution     |
| 2023.09 | [Large Language Models as Optimizers](https://arxiv.org/pdf/2309.03409.pdf) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/google-deepmind/opro) |         `TSP`         |  *ICLR 2024*   |     Solution     |
| 2023.10 | [Chain-of-Experts: When LLMs Meet Complex Operations Research Problems](https://openreview.net/pdf?id=HobyL1B9CZ) |                      &emsp;&emsp;&emsp;                      |        `MILP`         |  *ICLR 2024*   |    Automation    |
| 2023.10 | [OptiMUS: Scalable Optimization Modeling with (MI)LP Solvers and Large Language Models](https://arxiv.org/pdf/2402.10172.pdf) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/teshnizi/OptiMUS) |        `MILP`         |    *ArXiv*     |    Automation    |
| 2023.10 | [AI-Copilot for Business Optimisation: A Framework and A Case Study in Production Scheduling](https://arxiv.org/pdf/2309.13218.pdf) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/pivithuruthejanamarasinghe/AI-Copilot-Data) |        `JSSP`         |    *ArXiv*     |    Automation    |
| 2023.11 | [Large Language Models as Evolutionary Optimizers](https://arxiv.org/pdf/2310.19046.pdf) |                                                              |         `TSP`         |    *ArXiv*     |     Solution     |
| 2023.11 | [Algorithm Evolution Using Large Language Model](https://arxiv.org/pdf/2311.15249.pdf) |                                                              |         `TSP`         |    *ArXiv*     |    Algorithm     |
| 2023.12 | [Mathematical discoveries from program search with large language models](https://www.nature.com/articles/s41586-023-06924-6) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/google-deepmind/funsearch) |         `BPP`         |    *Nature*    |    Algorithm     |
| 2024.01 | [An Example of Evolutionary Computation + Large Language Model Beating Human: Design of Efficient Guided Local Search](https://arxiv.org/pdf/2401.02051.pdf) |                                                              |         `TSP`         |    *ArXiv*     |    Algorithm     |
| 2024.02 | [ReEvo: Large Language Models as Hyper-Heuristics with Reflective Evolution](https://arxiv.org/pdf/2402.01145.pdf) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/ai4co/LLM-as-HH) | `TSP,VRP,OP, MKP,BPP` |    *ArXiv*     |    Algorithm     |
| 2024.02 | [AutoSAT: Automatically Optimize SAT Solvers via Large Language Models](https://arxiv.org/pdf/2402.10705.pdf) |                                                              |         `SAT`         |    *ArXiv*     |    Algorithm     |
| 2024.02 | [From Large Language Models and Optimization to Decision Optimization CoPilot: A Research Manifesto](https://arxiv.org/pdf/2402.16269.pdf) |                                                              |        `MILP`         |    *ArXiv*     |    Automation    |
| 2024.03 | [How Multimodal Integration Boost the Performance of LLM for Optimization: Case Study on Capacitated Vehicle Routing Problems](https://arxiv.org/pdf/2403.01757.pdf) |                                                              |         `VRP`         |    *ArXiv*     |     Solution     |
| 2024.03 | [RouteExplainer: An Explanation Framework for Vehicle Routing Problem](https://arxiv.org/pdf/2403.03585.pdf) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/ntt-dkiku/route-explainer) <br> [![Project-Page](https://img.shields.io/badge/Page-74aa9c?style=for-the-badge)](https://ntt-dkiku.github.io/xai-vrp) |         `VRP`         |  *PAKDD 2024*  | Interpretability |

----

### Domain FMs for Combinatorial Optimization

Building a domain foundation model that can solve a wide range of COPs may be an interesting and challenging topic. Some recent work puts efforts towards this ambitious goal by devising a unified architecture* or representation* for different COPs.

|  Date   |                            Paper                             |                             Link                             |      Problem      |  Venue  |    Remark*     |
| :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: | :---------------: | :-----: | :------------: |
| 2023.05 | [Efficient Training of Multi-task Combinatorial Neural Solver with Multi-armed Bandits](https://arxiv.org/pdf/2305.06361.pdf) |                      &emsp;&emsp;&emsp;                      | `TSP,VRP, OP,KP`  | *ArXiv* |  Architecture  |
| 2024.02 | [Multi-Task Learning for Routing Problem with Cross-Problem Zero-Shot Generalization](https://arxiv.org/pdf/2402.16891.pdf) |                                                              |       `VRP`       | *ArXiv* |  Architecture  |
| 2024.03 | [Towards a Generic Representation of Combinatorial Problems for Learning-Based Approaches](https://arxiv.org/pdf/2403.06026.pdf) | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/corail-research/learning-generic-csp) | `SAT,TSP, COL,KP` | *ArXiv* | Representation |
