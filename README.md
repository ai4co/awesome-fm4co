<h1 align="center">FM-COP</h1>

*[Only For Personal Research Purpose]* 

FM-COP contains interesting research papers (1) using existing **Large Language Models for Combinatorial Optimization**, and (2) building **Domain Foundation Models for Combinatorial Optimization**.

(1) Most work uses existing LLMs to generate solutions\*, code\* (hyper-heuristic), or parameters\* (hyper-network), achieving remarkable performance when combined with traditional problem-specific heuristics or general meta-heuristics. Other work leverages LLMs to explore the interpretability\* of COP solvers, or to achieve automation\* of problem formulation or domain tools's usage only through text prompts. This research direction may receive increasing attention due to the power of LLMs. Currently, we mainly focus on the below problems, and may include more variants (e.g., graph-based COPs) as the community grows:

* Traveling Salesman Problem
* Vehicle Routing Problem
* Scheduling Problem
* (Mixed) Integer Linear Programming

(2) This category is still underexplored by the community. Building a unified domain foundation model that can solve a wide range of COPs may be an interesting and challenging research direction. We will include the papers putting efforts towards this ambitious goal when more works pop up.

----

### LLMs for Combinatorial Optimization

|  Date   |                            Paper                             |                             Link                             | Problem |     Venue      |   Affiliation    |     Remark*      |
| :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: | :-----: | :------------: | :--------------: | :--------------: |
| 2023.09 | Can Language Models Solve Graph Problems in Natural Language? |                                                              |  Graph  | [NeurIPS 2023] | Xi'an Jiaotong U |     Solution     |
| 2023.09 |             Large Language Models as Optimizers              |                                                              |   TSP   |  [ICLR 2024]   |     DeepMind     |     Solution     |
| 2023.10 | Large Language Model for Multi-objective Evolutionary Optimization |                                                              |         |     ArXiv      |      CityU       |                  |
| 2023.10 | Chain-of-Experts: When LLMs Meet Complex Operations Research Problems |                                                              |  MILP   |  [ICLR 2024]   |    Zhejiang U    |    Automation    |
| 2023.10 | OptiMUS: Scalable Optimization Modeling with (MI)LP Solvers and Large Language Models |                                                              |  MILP   |     ArXiv      |     Stanford     |    Automation    |
| 2023.10 | AI-Copilot for Business Optimisation: A Framework and A Case Study in Production Scheduling |                                                              |  JSSP   |     ArXiv      |    La Trobe U    |    Automation    |
| 2023.11 |       Large Language Models as Evolutionary Optimizers       |                                                              |         |     ArXiv      |      A*Star      |     Solution     |
| 2023.11 |        Algorithm Evolution Using Large Language Model        |                                                              |         |     ArXiv      |      CityU       |       Code       |
| 2023.12 | Mathematical discoveries from program search with large language models |                                                              |         |    [Nature]    |     DeepMind     |       Code       |
| 2024.01 | An Example of Evolutionary Computation + Large Language Model Beating Human: Design of Efficient Guided Local Search |                                                              |         |     ArXiv      |      CityU       |       Code       |
| 2024.02 | ReEvo: Large Language Models as Hyper-Heuristics with Reflective Evolution |                                                              |         |     ArXiv      |     Peking U     |       Code       |
| 2024.02 | AutoSAT: Automatically Optimize SAT Solvers via Large Language Models |                                                              |   SAT   |     ArXiv      |     Fudan U      |                  |
| 2024.02 |                        Double-blinded                        |                                                              |         |                |                  |                  |
| 2024.02 | Position Paper: From Large Language Models and Optimization to Decision Optimization CoPilot: A Research Manifesto |                                                              |         |     ArXiv      |       IBM        |    Automation    |
| 2024.03 | How Multimodal Integration Boost the Performance of LLM for Optimization: Case Study on Capacitated Vehicle Routing Problems |                                                              |   VRP   |     ArXiv      |      PolyU       |     Solution     |
| 2024.03 | RouteExplainer: An Explanation Framework for Vehicle Routing Problem | [![Code](https://img.shields.io/badge/Code-025E8C?style=for-the-badge)](https://github.com/ntt-dkiku/route-explainer) |   VRP   |     ArXiv      |    NTT Corp.     | Interpretability |
|         |                                                              |                                                              |         |                |                  |                  |

