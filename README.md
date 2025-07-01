# Value-Alignment-Agentic-AI-Papers-Survey-Taxonomy
This repository is created to support the survey paper [Application-Driven Value Alignment in Agentic AI Systems: Survey and Perspectives](https://arxiv.org/abs/2506.09656), by collecting and categorizing relevant research papers and datasets on value alignment in agentic AI systems.

We welcome contributions, discussions, and issues related to value alignment for agentic AI. If you have any questions, feel free to contact Zengwei_hnu@163.com. (We recommend cc'ing zhuhengshu@gmail.com as a precaution in case of any delivery issues.)

We will continue to update both the [arXiv](https://arxiv.org/abs/2506.09656) paper and this repository regularly. If you find our survey useful for your research, please cite the following paper:

```bibtex
@article{AgenticAIValueAlignment,
  title={Application-Driven Value Alignment in Agentic AI Systems: Survey and Perspectives},
  author={Zeng, Wei and Zhu, Hengshu and Qin, Chuan and Wu, Han and Cheng, Yihang and Zhang, Sirui and Jin, Xiaowei and Shen, Yinuo and Wang, Zhenxing and Zhong, Feimin and Xiong, Hui},
  journal={arXiv preprint arXiv:2506.09656},
  year={2025}
}
```


## Bookmarks
- [Overview of Our Survey](#overview-of-our-survey)
- [Related Survey](#related-survey)
- [The Principles of Values Alignment](#the-principles-of-values-alignment)
  - [Macro Level](#the-macro-level-principles-of-values-alignment)
  - [Meso Level](#the-meso-level-principles-of-values-alignment)
  - [Micro Level](#the-micro-level-principles-of-values-alignment)
- [Agent System Application](#agent-system-application)
- [Values Alignment Evaluation for Agent Systems](#values-alignment-evaluation-for-agent-systems)
- [Methodologies for Agent Value Alignment](#methodologies-for-agent-value-alignment)
- [Datasets](#datasets)
- [Future Directions](#future-directions)


## Papers
### Overview of Our Survey

### Related Survey
| Time |                                                                          Title                                                                         |                                                     Keywords                                                    |                Venue               |
|:----:|:------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------:|:----------------------------------:|
| 2025 |          [The rise and potential of large language model based agents: a survey](https://link.springer.com/article/10.1007/s11432-024-4222-0)          |          Communication structures, practical applications and societal systems etc. of LLM-based agents         | Science China Information Sciences |
| 2025 |                           [A Survey on Alignment for Large Language Model Agents](https://openreview.net/forum?id=gkxt5kZS84)                          |          Value alignment objectives, datasets, techniques, and evaluation methods for LLM-based agents          |             Openreview             |
| 2025 |                               [Multi-Agent Collaboration Mechanisms: A Survey of LLMs](https://arxiv.org/abs/2501.06322)                               |        Conceptual framework, interaction mechanisms, and application overview of LLM-based agent systems        |                arXiv               |
| 2024 |                    [Large Language Model based Multi-Agents: A Survey of Progress and Challenges](https://arxiv.org/abs/2402.01680)                    |           Capabilities, framework Analysis, and ppplication overview of LLM-based multi-agent systems           |                arXiv               |
| 2024 |                [A survey on large language model based autonomous agents](https://link.springer.com/article/10.1007/s11704-024-40231-1)                |        Constituent modules, application overview, and evaluation methods of LLM-based autonomous agents:        |    Frontiers of Computer Science   |
| 2023 |                                        [AI Alignment: A Comprehensive Survey](https://arxiv.org/abs/2310.19852)                                        |           Motivations and objectives, alignment methods, and assurance and governance of AI alignment           |                arXiv               |
| 2023 |              [From Instructions to Intrinsic Human Values -- A Survey of Alignment Goals for Big Models](https://arxiv.org/abs/2308.12014)             |                              Definition and evaluation of LLM alignment objectives                              |                arXiv               |
| 2023 |                                      [Large Language Model Alignment: A Survey](https://arxiv.org/abs/2309.15025)                                      |                         Definition, categories, testing, and evaluation of LLM alignment                        |                arXiv               |
| 2023 |                                 [Unpacking the Ethical Value Alignment in Big Models](https://arxiv.org/abs/2310.17551)                                |                  Definition, normative principles, and technical methods of LLM value alignment                 |                arXiv               |
| 2023 |              [Trustworthy LLMs: a Survey and Guideline for Evaluating Large Language Models' Alignment](https://arxiv.org/abs/2308.05374)              |                                    Alignment objectives for trustworthy LLMs                                    |                arXiv               |
| 2024 | [Towards Bidirectional Human-AI Alignment: A Systematic Review for Clarifications, Framework, and Future Directions](https://arxiv.org/abs/2406.09264) |               Challenges, fundamental definitions, and alignment frameworks of LLM value alignment              |                arXiv               |
| 2025 |                                                                                                                                                        | Necessity, conceptual definitions, theoretical approaches, challenges and future outlook of LLM value alignment |                                    |

### The Principles of Values Alignment
![](multi-level-value-alignment-principles.png)
#### The Macro Level Principles of Values Alignment
<table class="tg"><tbody>
  <tr>
    <td class="tg-9wq8">Sub-Level</td>
    <td class="tg-9wq8">Sub-sub-Level</td>
    <td class="tg-9wq8">Title</td>
    <td class="tg-9wq8">Time</td>
    <td class="tg-9wq8">Venue</td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="16">Moral Foundation</td>
    <td class="tg-9wq8" rowspan="2">Beneficience</td>
    <td class="tg-hq1h"><a href="https://www.nature.com/articles/s42256-019-0088-2" target="_blank" rel="noopener noreferrer">The global landscape of aiethics guidelines</a></td>
    <td class="tg-9wq8">2019</td>
    <td class="tg-9wq8">Nature machine intelligence</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45" target="_blank" rel="noopener noreferrer">A unified framework of five principles</a><br><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45" target="_blank" rel="noopener noreferrer">for ai in society</a></td>
    <td class="tg-9wq8">2022</td>
    <td class="tg-c3ow">Machine learning and the city: Applications inarchitecture and urban design</td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="6">Justice &amp; Fairness</td>
    <td class="tg-hq1h"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
    <td class="tg-9wq8">2019</td>
    <td class="tg-9wq8">Nature machine intelligence</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">Ethics of ai: A</a><br><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">systematic literature review of principles and challenges</a></td>
    <td class="tg-9wq8">2022</td>
    <td class="tg-c3ow">Proceedings of the 26th international conference on evaluation andassessment in software engineering</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">A unified framework of five principles</a><br><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">for ai in society</a></td>
    <td class="tg-9wq8">2022</td>
    <td class="tg-c3ow">Machine learning and the city: Applications inarchitecture and urban design</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://www.sciencedirect.com/science/article/abs/pii/S030645732500041X">Towards realistic evaluation of cultural value alignment in large</a><br><a href="https://www.sciencedirect.com/science/article/abs/pii/S030645732500041X">language models: Diversity enhancement for survey response</a><br><a href="https://www.sciencedirect.com/science/article/abs/pii/S030645732500041X">simulation</a></td>
    <td class="tg-9wq8">2025</td>
    <td class="tg-9wq8">Information Processing &amp; Management</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://openreview.net/forum?id=yoVq2BGQdP">Achieving fairness in multi-agent</a><br><a href="https://openreview.net/forum?id=yoVq2BGQdP">mdp using reinforcement learning</a></td>
    <td class="tg-9wq8">2023</td>
    <td class="tg-c3ow">The Twelfth InternationalConference on Learning Representations</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/4dbb61cb68671edc4ca3712d70083b9f-Abstract-Datasets_and_Benchmarks.html">Beavertails: Towards improved safety</a><br><a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/4dbb61cb68671edc4ca3712d70083b9f-Abstract-Datasets_and_Benchmarks.html">alignment of llm via a human-preference dataset</a></td>
    <td class="tg-9wq8">2023</td>
    <td class="tg-c3ow">Advances inNeural Information Processing Systems</td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="2">Honesty</td>
    <td class="tg-hq1h"><a href="https://arxiv.org/abs/2308.12014" target="_blank" rel="noopener noreferrer">From instructions</a><br><a href="https://arxiv.org/abs/2308.12014" target="_blank" rel="noopener noreferrer">to intrinsic human values - A survey of alignment goals for big</a><br><a href="https://arxiv.org/abs/2308.12014" target="_blank" rel="noopener noreferrer">models</a></td>
    <td class="tg-9wq8">2023</td>
    <td class="tg-9wq8">arXiv</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://openreview.net/forum?id=zj7YuTE4t8">Improving factuality and reasoning in language models through</a><br><a href="https://openreview.net/forum?id=zj7YuTE4t8">multiagent debate</a></td>
    <td class="tg-9wq8">2023</td>
    <td class="tg-9wq8">Forty-first International Conference on Machine Learning</td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="2">Responsibility</td>
    <td class="tg-hq1h"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
    <td class="tg-9wq8">2019</td>
    <td class="tg-9wq8">Nature machine intelligence</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">Ethics of ai: A</a><br><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">systematic literature review of principles and challenges</a></td>
    <td class="tg-9wq8">2022</td>
    <td class="tg-c3ow">Proceedings of the 26th international conference on evaluation andassessment in software engineering</td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="2">Virtue</td>
    <td class="tg-hq1h"><a href="https://arxiv.org/abs/2410.02683">Dailydilemmas: Revealing value</a><br><a href="https://arxiv.org/abs/2410.02683">preferences of llms with quandaries of daily life</a></td>
    <td class="tg-9wq8">2025</td>
    <td class="tg-c3ow">The ThirteenthInternational Conference on Learning Representations, ICLR 2025,Singapore</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://arxiv.org/abs/2501.07071">Value compass leaderboard: A platform</a><br><a href="https://arxiv.org/abs/2501.07071">for fundamental and validated evaluation of llms values</a></td>
    <td class="tg-9wq8">2025</td>
    <td class="tg-9wq8">arXiv</td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="2">Dignity</td>
    <td class="tg-hq1h"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
    <td class="tg-9wq8">2019</td>
    <td class="tg-9wq8">Nature machine intelligence</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Shaping the ethical governance path ofartificial intelligence in the chinese context—based on value-instrument rationality</td>
    <td class="tg-9wq8">2025</td>
    <td class="tg-9wq8">Studies in Science of Science</td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="7">Rights Protection</td>
    <td class="tg-9wq8" rowspan="3">Freedom &amp; Autonomy</td>
    <td class="tg-hq1h"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
    <td class="tg-9wq8">2019</td>
    <td class="tg-9wq8">Nature machine intelligence</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">A unified framework of five principles</a><br><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">for ai in society</a></td>
    <td class="tg-9wq8">2022</td>
    <td class="tg-c3ow">Machine learning and the city: Applications inarchitecture and urban design</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Shaping the ethical governance path ofartificial intelligence in the chinese context—based on value-instrument rationality</td>
    <td class="tg-9wq8">2025</td>
    <td class="tg-9wq8">Studies in Science of Science</td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="4">Privacy</td>
    <td class="tg-hq1h"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
    <td class="tg-9wq8">2019</td>
    <td class="tg-9wq8">Nature machine intelligence</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">Ethics of ai: A</a><br><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">systematic literature review of principles and challenges</a></td>
    <td class="tg-9wq8">2022</td>
    <td class="tg-c3ow">Proceedings of the 26th international conference on evaluation andassessment in software engineering</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://dl.acm.org/doi/full/10.1145/3653982">Hydragan: A cooperative agent</a><br><a href="https://dl.acm.org/doi/full/10.1145/3653982">model for multi-objective data generation</a></td>
    <td class="tg-9wq8">2024</td>
    <td class="tg-c3ow">ACM Trans. Intell.Syst. Technol.</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://arxiv.org/abs/2410.11906">Empowering users in digital</a><br><a href="https://arxiv.org/abs/2410.11906">privacy management through interactive llm-based agents</a></td>
    <td class="tg-9wq8">2025</td>
    <td class="tg-c3ow">TheThirteenth International Conference on Learning Representations, ICLR2025, Singapore</td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="3">Sustainability</td>
    <td class="tg-9wq8">Solidarity</td>
    <td class="tg-hq1h"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
    <td class="tg-9wq8">2019</td>
    <td class="tg-9wq8">Nature machine intelligence</td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="2">Sustainability</td>
    <td class="tg-hq1h"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
    <td class="tg-9wq8">2019</td>
    <td class="tg-9wq8">Nature machine intelligence</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/ca9567d8ef6b2ea2da0d7eed57b933ee-Abstract-Conference.html">Cooperate or collapse: Emergence of</a><br><a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/ca9567d8ef6b2ea2da0d7eed57b933ee-Abstract-Conference.html">sustainable cooperation in a society of LLM agents</a></td>
    <td class="tg-9wq8">2024</td>
    <td class="tg-c3ow">Advances in Neural Information Processing Systems 38: AnnualConference on Neural Information Processing Systems 2024,NeurIPS 2024</td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="15">System Governance</td>
    <td class="tg-9wq8" rowspan="5">Harmless</td>
    <td class="tg-hq1h"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
    <td class="tg-9wq8">2019</td>
    <td class="tg-9wq8">Nature machine intelligence</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">A unified framework of five principles</a><br><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">for ai in society</a></td>
    <td class="tg-9wq8">2022</td>
    <td class="tg-c3ow">Machine learning and the city: Applications inarchitecture and urban design</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://arxiv.org/abs/2308.12014">From instructions</a><br><a href="https://arxiv.org/abs/2308.12014">to intrinsic human values - A survey of alignment goals for big</a><br><a href="https://arxiv.org/abs/2308.12014">models</a></td>
    <td class="tg-9wq8">2023</td>
    <td class="tg-9wq8">arXiv</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://arxiv.org/abs/2305.16960">Training socially aligned language models on simulated</a><br><a href="https://arxiv.org/abs/2305.16960">social interactions</a></td>
    <td class="tg-9wq8">2024</td>
    <td class="tg-c3ow">The Twelfth International Conferenceon Learning Representations, ICLR 2024</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/1eb543faf7c69e8a7eb8b85f70be818f-Abstract-Datasets_and_Benchmarks_Track.html">Safesora: Towards safety alignment of text2video generation</a><br><a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/1eb543faf7c69e8a7eb8b85f70be818f-Abstract-Datasets_and_Benchmarks_Track.html">via a human preference dataset</a></td>
    <td class="tg-9wq8">2024</td>
    <td class="tg-c3ow">Advances in Neural InformationProcessing Systems</td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="2">Trust</td>
    <td class="tg-hq1h"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
    <td class="tg-9wq8">2019</td>
    <td class="tg-9wq8">Nature machine intelligence</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://www.sciencedirect.com/science/article/abs/pii/S030645732500041X">Towards realistic evaluation of cultural value alignment in large</a><br><a href="https://www.sciencedirect.com/science/article/abs/pii/S030645732500041X">language models: Diversity enhancement for survey response</a><br><a href="https://www.sciencedirect.com/science/article/abs/pii/S030645732500041X">simulation</a></td>
    <td class="tg-9wq8">2025</td>
    <td class="tg-9wq8">Information Processing &amp; Management</td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="6">Transparency</td>
    <td class="tg-hq1h"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
    <td class="tg-9wq8">2019</td>
    <td class="tg-9wq8">Nature machine intelligence</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">A unified framework of five principles</a><br><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">for ai in society</a></td>
    <td class="tg-9wq8">2022</td>
    <td class="tg-c3ow">Machine learning and the city: Applications inarchitecture and urban design</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">Ethics of ai: A</a><br><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">systematic literature review of principles and challenges</a></td>
    <td class="tg-9wq8">2022</td>
    <td class="tg-c3ow">Proceedings of the 26th international conference on evaluation andassessment in software engineering</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://dl.acm.org/doi/abs/10.1145/3680287">ICA-CRMAS: intelligent</a><br><a href="https://dl.acm.org/doi/abs/10.1145/3680287">context-awareness approach for citation recommendation based</a><br><a href="https://dl.acm.org/doi/abs/10.1145/3680287">on multi-agent system</a></td>
    <td class="tg-9wq8">2024</td>
    <td class="tg-9wq8">ACM Trans. Manag. Inf. Syst.</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://openreview.net/forum?id=mDw42ZanmE">A multimodal</a><br><a href="https://openreview.net/forum?id=mDw42ZanmE">automated interpretability agent</a></td>
    <td class="tg-9wq8">2024</td>
    <td class="tg-c3ow">Forty-first InternationalConference on Machine Learning, ICML 2024</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://arxiv.org/abs/2405.17631">Biodiscoveryagent: An</a><br><a href="https://arxiv.org/abs/2405.17631">ai agent for designing genetic perturbation experiments</a></td>
    <td class="tg-9wq8">2024</td>
    <td class="tg-9wq8">arXiv</td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="2">Usefulness</td>
    <td class="tg-hq1h"><a href="https://arxiv.org/abs/2308.12014">From instructions</a><br><a href="https://arxiv.org/abs/2308.12014">to intrinsic human values - A survey of alignment goals for big</a><br><a href="https://arxiv.org/abs/2308.12014">models</a></td>
    <td class="tg-9wq8">2023</td>
    <td class="tg-9wq8">arXiv</td>
  </tr>
  <tr>
    <td class="tg-hq1h"><a href="https://arxiv.org/abs/2410.02683">Dailydilemmas: Revealing value</a><br><a href="https://arxiv.org/abs/2410.02683">preferences of llms with quandaries of daily life</a></td>
    <td class="tg-9wq8">2025</td>
    <td class="tg-c3ow">The ThirteenthInternational Conference on Learning Representations, ICLR 2025</td>
  </tr>
</tbody></table>

#### The Meso Level Principles of Values Alignment
<table class="tg"><tbody>
  <tr>
    <td class="tg-nrix">Sub-Level</td>
    <td class="tg-nrix">Sub-sub-level</td>
    <td class="tg-nrix">Title</td>
    <td class="tg-nrix">Time</td>
    <td class="tg-nrix">Venue</td>
  </tr>
  <tr>
    <td class="tg-nrix" rowspan="11">National Level</td>
    <td class="tg-nrix" rowspan="4">The United States</td>
    <td class="tg-p59o"><a href="https://arxiv.org/abs/2310.17551" target="_blank" rel="noopener noreferrer">Unpacking the ethical value</a><br><a href="https://arxiv.org/abs/2310.17551" target="_blank" rel="noopener noreferrer">alignment in big models</a></td>
    <td class="tg-nrix">2022</td>
    <td class="tg-nrix">arXiv</td>
  </tr>
  <tr>
    <td class="tg-p59o"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
    <td class="tg-nrix">2019</td>
    <td class="tg-nrix">Nature machine intelligence</td>
  </tr>
  <tr>
    <td class="tg-p59o"><a href="https://bidenwhitehouse.archives.gov/ostp/ai-bill-of-rights/">Blueprint for an ai bill of rights: Making automated systems</a><br><a href="https://bidenwhitehouse.archives.gov/ostp/ai-bill-of-rights/">work for the american people</a></td>
    <td class="tg-nrix">2022</td>
    <td class="tg-nrix">White House Nimble Books</td>
  </tr>
  <tr>
    <td class="tg-p59o"><a href="https://www.nitrd.gov/pubs/National-Artificial-Intelligence-Research-and-Development-Strategic-Plan-2023-Update.pdf" target="_blank" rel="noopener noreferrer">The national</a><br><a href="https://www.nitrd.gov/pubs/National-Artificial-Intelligence-Research-and-Development-Strategic-Plan-2023-Update.pdf" target="_blank" rel="noopener noreferrer">artificial intelligence research and development strategic plan: 2023</a><br><a href="https://www.nitrd.gov/pubs/National-Artificial-Intelligence-Research-and-Development-Strategic-Plan-2023-Update.pdf" target="_blank" rel="noopener noreferrer">update</a></td>
    <td class="tg-nrix">2023</td>
    <td class="tg-nrix">National Science and Technology Council (US)</td>
  </tr>
  <tr>
    <td class="tg-nrix" rowspan="4">European Union</td>
    <td class="tg-p59o"><a href="https://digital-strategy.ec.europa.eu/en/library/ethics-guidelines-trustworthy-ai" target="_blank" rel="noopener noreferrer">Ethics</a><br><a href="https://digital-strategy.ec.europa.eu/en/library/ethics-guidelines-trustworthy-ai" target="_blank" rel="noopener noreferrer">guidelines for trustworthy AI</a></td>
    <td class="tg-nrix">2019</td>
    <td class="tg-nrix">High-level expert group on artificial intelligence</td>
  </tr>
  <tr>
    <td class="tg-p59o"><a href="https://artificialintelligenceact.eu/">EU Artificial intelligence act</a></td>
    <td class="tg-nrix">2024</td>
    <td class="tg-nrix">Regulamento da Uni茫o Europeia (UE)</td>
  </tr>
  <tr>
    <td class="tg-p59o"><a href="https://arxiv.org/abs/2310.17551">Unpacking the ethical value</a><br><a href="https://arxiv.org/abs/2310.17551">alignment in big models</a></td>
    <td class="tg-nrix">2022</td>
    <td class="tg-nrix">arXiv</td>
  </tr>
  <tr>
    <td class="tg-p59o"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
    <td class="tg-nrix">2019</td>
    <td class="tg-nrix">Nature machine intelligence</td>
  </tr>
  <tr>
    <td class="tg-nrix" rowspan="3">China</td>
    <td class="tg-p59o"><a href="https://www.gov.cn/zhengce/zhengceku/202310/content_6908045.htm">Measures for the ethical review of science and</a><br><a href="https://www.gov.cn/zhengce/zhengceku/202310/content_6908045.htm">technology</a></td>
    <td class="tg-nrix">2023</td>
    <td class="tg-nrix">C. A. of Sciences</td>
  </tr>
  <tr>
    <td class="tg-nrix">Standardization of ai ethical governance </td>
    <td class="tg-nrix">2023</td>
    <td class="tg-nrix">ational Artificial Intelligence StandardizationGeneral Group</td>
  </tr>
  <tr>
    <td class="tg-p59o"><a href="https://arxiv.org/abs/2310.17551">Unpacking the ethical value</a><br><a href="https://arxiv.org/abs/2310.17551">alignment in big models</a></td>
    <td class="tg-nrix">2022</td>
    <td class="tg-nrix">arXiv</td>
  </tr>
  <tr>
    <td class="tg-nrix" rowspan="3">Industry Level</td>
    <td class="tg-nrix">Education</td>
    <td class="tg-p59o"><a href="https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research">Guidance for generative AI in education</a><br><a href="https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research">and research</a></td>
    <td class="tg-nrix">2023</td>
    <td class="tg-nrix">UNESCO Publishing</td>
  </tr>
  <tr>
    <td class="tg-nrix">Health</td>
    <td class="tg-p59o"><a href="https://www.who.int/publications/i/item/9789240084759">Ethics and governance of artificial</a><br><a href="https://www.who.int/publications/i/item/9789240084759">intelligence for health: Guidance on large multi-modal models</a></td>
    <td class="tg-nrix">2024</td>
    <td class="tg-nrix">W. H. Organization</td>
  </tr>
  <tr>
    <td class="tg-nrix">Gaming</td>
    <td class="tg-p59o"><a href="https://arxiv.org/abs/2305.07392">The ethics of ai in games</a></td>
    <td class="tg-nrix">2023</td>
    <td class="tg-nrix">IEEE Transactions onAffective Computing</td>
  </tr>
  <tr>
    <td class="tg-nrix" rowspan="9">Cultural Level</td>
    <td class="tg-nrix" rowspan="4">Large/Small Power Distance<br>Strong/Weak Uncertainty Avoidance<br>Individual/Collectivism</td>
    <td class="tg-p59o"><a href="https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/">Dimensionalizing cultures: The hofstede model in</a><br><a href="https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/">context</a></td>
    <td class="tg-nrix">2011</td>
    <td class="tg-nrix">Online readings in psychology and culture</td>
  </tr>
  <tr>
    <td class="tg-p59o"><a href="https://arxiv.org/abs/2311.16421">Cdeval: A benchmark for measuring the cultural dimensions of</a><br><a href="https://arxiv.org/abs/2311.16421">large language models</a></td>
    <td class="tg-nrix">2023</td>
    <td class="tg-nrix">arXiv</td>
  </tr>
  <tr>
    <td class="tg-p59o"><a href="https://arxiv.org/abs/2406.14805">How well do</a><br><a href="https://arxiv.org/abs/2406.14805">llms represent values across cultures? empirical analysis of llm</a><br><a href="https://arxiv.org/abs/2406.14805">responses based on hofstede cultural dimensions</a></td>
    <td class="tg-nrix">2024</td>
    <td class="tg-nrix">arXiv</td>
  </tr>
  <tr>
    <td class="tg-p59o"><a href="https://arxiv.org/abs/2411.06032">Llm-globe: A benchmark evaluating the cultural values</a><br><a href="https://arxiv.org/abs/2411.06032">embedded in llm output</a></td>
    <td class="tg-nrix">2024</td>
    <td class="tg-nrix">arXiv</td>
  </tr>
  <tr>
    <td class="tg-nrix" rowspan="3">Long/Short-Term OrientationMasculinity/Femininity</td>
    <td class="tg-p59o"><a href="https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/">Dimensionalizing cultures: The hofstede model in</a><br><a href="https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/">context</a></td>
    <td class="tg-nrix">2011</td>
    <td class="tg-nrix">Online readings in psychology and culture</td>
  </tr>
  <tr>
    <td class="tg-p59o"><a href="https://arxiv.org/abs/2311.16421">Cdeval: A benchmark for measuring the cultural dimensions of</a><br><a href="https://arxiv.org/abs/2311.16421">large language models</a></td>
    <td class="tg-nrix">2023</td>
    <td class="tg-nrix">arXiv</td>
  </tr>
  <tr>
    <td class="tg-p59o"><a href="https://arxiv.org/abs/2406.14805">How well do</a><br><a href="https://arxiv.org/abs/2406.14805">llms represent values across cultures? empirical analysis of llm</a><br><a href="https://arxiv.org/abs/2406.14805">responses based on hofstede cultural dimensions</a></td>
    <td class="tg-nrix">2024</td>
    <td class="tg-nrix">arXiv</td>
  </tr>
  <tr>
    <td class="tg-nrix" rowspan="2">Indulgence/Restrained</td>
    <td class="tg-p59o"><a href="https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/">Dimensionalizing cultures: The hofstede model in</a><br><a href="https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/">context</a></td>
    <td class="tg-nrix">2011</td>
    <td class="tg-nrix">Online readings in psychology and culture</td>
  </tr>
  <tr>
    <td class="tg-p59o"><a href="https://arxiv.org/abs/2311.16421">Cdeval: A benchmark for measuring the cultural dimensions of</a><br><a href="https://arxiv.org/abs/2311.16421">large language models</a></td>
    <td class="tg-nrix">2023</td>
    <td class="tg-nrix">arXiv</td>
  </tr>
</tbody></table>

|    Sub-Level   |                                      Sub-sub-level                                     |                                                                                                      Title                                                                                                     | Time |                             Venue                             |
|:--------------:|:--------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----:|:-------------------------------------------------------------:|
| National Level |                                    The United States                                   |                                                             [Unpacking the ethical valuealignment in big models](https://arxiv.org/abs/2310.17551)                                                             | 2022 |                             arXiv                             |
|                |                                                                                        |                                                        [The global landscape of aiethics guidelines](https://www.nature.com/articles/s42256-019-0088-2)                                                        | 2019 |                  Nature machine intelligence                  |
|                |                                                                                        |                            [Blueprint for an ai bill of rights: Making automated systemswork for the american people](https://bidenwhitehouse.archives.gov/ostp/ai-bill-of-rights/)                            | 2022 |                    White House Nimble Books                   |
|                |                                                                                        | [The nationalartificial intelligence research and development strategic plan: 2023update](https://www.nitrd.gov/pubs/National-Artificial-Intelligence-Research-and-Development-Strategic-Plan-2023-Update.pdf) | 2023 |          National Science and Technology Council (US)         |
|                |                                     European Union                                     |                                            [Ethicsguidelines for trustworthy AI](https://digital-strategy.ec.europa.eu/en/library/ethics-guidelines-trustworthy-ai)                                            | 2019 |       High-level expert group on artificial intelligence      |
|                |                                                                                        |                                                                     [EU Artificial intelligence act](https://artificialintelligenceact.eu/)                                                                    | 2024 |               Regulamento da União Europeia (UE)              |
|                |                                                                                        |                                                             [Unpacking the ethical valuealignment in big models](https://arxiv.org/abs/2310.17551)                                                             | 2022 |                             arXiv                             |
|                |                                                                                        |                                                        [The global landscape of aiethics guidelines](https://www.nature.com/articles/s42256-019-0088-2)                                                        | 2019 |                  Nature machine intelligence                  |
|                |                                          China                                         |                                       [Measures for the ethical review of science andtechnology(trial)](https://www.gov.cn/zhengce/zhengceku/202310/content_6908045.htm)                                       | 2023 |                       C. A. of Sciences                       |
|                |                                                                                        |                                                                             Standardization of ai ethical governance (2023 edition)                                                                            | 2023 | ational Artificial Intelligence Standardization General Group |
|                |                                                                                        |                                                             [Unpacking the ethical valuealignment in big models](https://arxiv.org/abs/2310.17551)                                                             | 2022 |                             arXiv                             |
| Industry Level |                                        Education                                       |                                     [Guidance for generative AI in educationand research](https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research)                                    | 2023 |                       UNESCO Publishing                       |
|                |                                         Health                                         |                            [Ethics and governance of artificialintelligence for health: Guidance on large multi-modal models](https://www.who.int/publications/i/item/9789240084759)                           | 2024 |                       W. H. Organization                      |
|                |                                         Gaming                                         |                                                                          [The ethics of ai in games](https://arxiv.org/abs/2305.07392)                                                                         | 2023 |            IEEE Transactions on Affective Computing           |
| Cultural Level | Large/Small Power Distance  Strong/Weak Uncertainty Avoidance  Individual/Collectivism |                                                   [Dimensionalizing cultures: The hofstede model incontext](https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/)                                                   | 2011 |           Online readings in psychology and culture           |
|                |                                                                                        |                                              [Cdeval: A benchmark for measuring the cultural dimensions oflarge language models](https://arxiv.org/abs/2311.16421)                                             | 2023 |                             arXiv                             |
|                |                                                                                        |                         [How well dollms represent values across cultures? empirical analysis of llmresponses based on hofstede cultural dimensions](https://arxiv.org/abs/2406.14805)                         | 2024 |                             arXiv                             |
|                |                                                                                        |                                                 [Llm-globe: A benchmark evaluating the cultural valuesembedded in llm output](https://arxiv.org/abs/2411.06032)                                                | 2024 |                             arXiv                             |
|                |                   Long/Short-Term Orientation Masculinity/Femininity                   |                                                   [Dimensionalizing cultures: The hofstede model incontext](https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/)                                                   | 2011 |           Online readings in psychology and culture           |
|                |                                                                                        |                                              [Cdeval: A benchmark for measuring the cultural dimensions oflarge language models](https://arxiv.org/abs/2311.16421)                                             | 2023 |                             arXiv                             |
|                |                                                                                        |                         [How well dollms represent values across cultures? empirical analysis of llmresponses based on hofstede cultural dimensions](https://arxiv.org/abs/2406.14805)                         | 2024 |                             arXiv                             |
|                |                                  Indulgence/Restrained                                 |                                                   [Dimensionalizing cultures: The hofstede model incontext](https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/)                                                   | 2011 |           Online readings in psychology and culture           |
|                |                                                                                        |                                              [Cdeval: A benchmark for measuring the cultural dimensions oflarge language models](https://arxiv.org/abs/2311.16421)                                             | 2023 |                             arXiv                             |
#### The Micro Level Principles of Values Alignment
|             Sub-Level             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       Title                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Time |                     Venue                    |
|:---------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----:|:--------------------------------------------:|
|             Recruiment            | [Recruitment in the times of machine learning](https://sciendo-parsed.s3.eu-central-1.amazonaws.com/6472540a215d2f6c89dc43ab/10.1515_mspe-2019-0018.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIA6AP2G7AKLD7LVJ4I%2F20250701%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Date=20250701T020101Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaDGV1LWNlbnRyYWwtMSJHMEUCIGwyocJnGwzEazGG47IHioJhcJYKvmdRQapGQwxckITNAiEA46W1g9lMj5bO6v%2FdJcg6rj5CBHO9J4nbM7z5kfkhdDkqxAUIyv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARACGgw5NjMxMzQyODk5NDAiDNchYkKNnKSQqU5dlyqYBYyq18WaikGIWSEANdyYQdWVsVuMdpJ7EhLwNKwOIn7DzIRbHKdZYmI9BVrNTSGzdz%2BNji0WDCHNnRoIISelICoEcJ7%2B88PmrLg0CgXtqbBkVCTer8pZrLBZU3eyFzn20kyP4JH%2FfoMhPUzBmv%2Bm7hdUNRc6ek7u9M%2FxlEgojG0Xt1DMO2h0gc4h1wGfM8oFwyHyAluhTKkNs1MpiNa3fSUeklME6ZSq6AEiIdzrzFIQdO4tl%2BCiXMh%2BpR6xC3ba951rH6qJyAIRSqIHPOsyD%2BWEBzZs0fjGjjJgxH%2Bh3IKDupvetAhXz5qRULt4J0PyWSp9uWStoDGH6fXcT7XV30Eyk5pZiTQrStvLvs1xRKM2TZZkYvEg4eK6GpwNnwTIf4kwTjpTOqTpCptGaqYXQom2gAM127ts5ZWJu5HPSxYbjtl%2BIn3mIO6brjskARidxr0xIZvQnJkGxYYpNA%2BKq%2BLKeH7TmntSXT%2FmD5TGvUvE4stgWPcgDSU3qyO0PrtbPCbxQ7Q2Q10MQVjP9fhxzswIPUmLJxQv%2BLMPU3lxxgXzvGtxkOY7sW29dAJI6oQclB5nt83dxAtandSjhR0dhX9dHhwO68TyjwQoDL7nNdqHEesRhU0VZkfnXhaE1QS7lT0OZhLL7KVLPIsH2IDzIAo4dxB9oszc3WXKRsR4P9eUV3kZDRaJoZZvE1AGru%2FiBzk77YYAUEfI9e4nqDxU%2BVVGoPtGJr0nCpADfbgQfzHF6KAy0%2BAhK8NWzdpAgEonlZGHbajNMMLRFtJ4p1dh%2BiKd1MPBQd1dp31d%2F3UVm0HOmawdaDzxJdMWgpq3TfgAhYmEY50nEqNqt7QcdmoC4UxeEGP6ksv7QbbyqBQb%2BtlZWyiv8km7X6Yw4O2MwwY6sQHLefZLLMlUBng0okDVdJBFmZs4u6SHx4nUbVQocwcoSL%2FgLGFPnY9aS4R1HAyTRnKs0mmKZwQOzYrbsal7OuD8sqsxgOt62Ei9xLpr3nQW5WJnIUVsfDe%2F40X0V7wBgDIbW%2FSNNEVk9x2ltjvEbYNLJS0BOTeg%2FDJRefMgk8oOZG76iy%2FnY%2FldFT3B7rpxo5sWF%2BYHMy%2Bhi8sJDCFZ85uKTegqbQLhECdnE5hBsx1w2G8%3D&X-Amz-Signature=665b8884bfc6ec19c395ef8ee2a18eae3f1439e37a3dcd5e045902950a5670ee&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject) | 2019 | Management Systems in Production Engineering |
|                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      [HR analytics and ethics](https://ieeexplore.ieee.org/document/8708197)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 2019 |    IBM Journal of Research and Development   |
|                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    [Ethics of ai-enabled re-cruiting and selection: A review and research agenda](https://link.springer.com/article/10.1007/S10551-022-05049-6)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | 2022 |          Journal of Business Ethics          |
|         Legal Consultation        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                [Lawluo: A chinese law firm co-run by llm agents](https://arxiv.org/abs/2407.16252)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 2024 |                     arXiv                    |
| Pharmaceutical Company Governance |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                [Operationalising ai governance through ethics-based auditing: an industry case study](https://link.springer.com/article/10.1007/s43681-022-00171-7)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | 2023 |                 AI and Ethics                |

### Agent System Application
| Time  | Title | Keywords | Venue | Paper |
| :---: | :---: | :------: | :---: | :---: |
| Row 1 | Data  |   Data   | Data  | Data  |
| Row 2 | Data  |   Data   | Data  | Data  |
| Row 3 | Data  |   Data   | Data  | Data  |
### Values Alignment Evaluation for Agent Systems
### Methodologies for Agent Value Alignment


## Datasets
| Time | Dataset | Paper | Keywords | Level | Venue |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 2025 | [DEFSurveySim](https://github.com/alexc-l/DEF-Survey-Sim) | [Towards realistic evaluation of cultural value alignment in large language models: Diversity enhancement for survey response simulation](https://www.sciencedirect.com/science/article/abs/pii/S030645732500041X?dgcid=author) | Nation, Culture | Macro Level, Meso Level | Information Processing & Management |
| 2025 | [NaVAB](https://huggingface.co/datasets/JadenGGGeee/NaVAB) | [Benchmarking Multi-National Value Alignment for Large Language Models](https://arxiv.org/abs/2504.12911) | Nation | Meso Level | arXiv preprint arXiv:2504.12911 |
| 2024 | [CultureSPA](https://github.com/shaoyangxu/culturespa) | [Self-Pluralising Culture Alignment for Large Language Models](https://arxiv.org/html/2410.12971v1) | Nation, Culture | Macro Level, Meso Level | arXiv preprint arXiv:2410.12971 |
| 2024 | [DailyDilemmas](https://huggingface.co/datasets/kellycyy/daily_dilemmas) | [DailyDilemmas: Revealing Value Preferences of LLMs with Quandaries of Daily Life](https://arxiv.org/abs/2410.02683) | Harmlessness, Responsibility, Justice & Fairness, Harmlessness, Virtue | Macro Level | arXiv preprint arXiv:2410.02683 |
| 2024 | [HofstedeCulturalDimensions](https://github.com/juliakharchenko/multilingual-ai-alignment) | [How Well Do LLMs Represent Values Across Cultures? Empirical Analysis of LLM Responses Based on Hofstede Cultural Dimensions](https://arxiv.org/abs/2406.14805) | Culture | Macro Level | arXiv preprint arXiv:2406.14805 |
| 2024 | [IndieValueCatalog](https://github.com/liweijiang/indievalue/tree/master) | [Can Language Models Reason about Individualistic Human Values and Preferences?](https://arxiv.org/abs/2410.03868) | Justice & Fairness | Macro Level | arXiv preprint arXiv:2410.03868 |
| 2024 | [KorNAT](https://huggingface.co/datasets/jiyounglee0523/KorNAT) | [KorNAT: LLM Alignment Benchmark for Korean Social Values and Common Knowledge](https://arxiv.org/abs/2402.13605) | Nation, Culture,Justice & Fairness | Macro Level, Meso Level | arXiv preprint arXiv:2402.13605 |
| 2024 | [LLMGlobe](https://github.com/raovish6/LLM-GLOBE?tab=readme-ov-file) | [LLM-GLOBE: A Benchmark Evaluating the Cultural Values Embedded in LLM Output](https://arxiv.org/abs/2411.06032) | Harmlessness, Justice & Fairness, Privacy, Beneficence, Responsibility | Macro Level | arXiv preprint arXiv:2411.06032 |
| 2024 | [Moral Beliefs](https://github.com/mumu-lily/moral-beliefs) | [Evaluating Moral Beliefs across LLMs through a Pluralistic Framework](https://arxiv.org/abs/2411.03665) | Nation, Culture,Justice & Fairness, Solidarity, Sustainability, Transparency | Macro Level, Meso Level | arXiv preprint arXiv:2411.03665 |
| 2024 | [Moral Stories](https://github.com/demelin/moral_stories) | [Measuring Human-AI Value Alignment in Large Language Models](https://ojs.aaai.org/index.php/AIES/article/view/31703) | Harmlessness, Justice & Fairness, Responsibility, Beneficence, Dignity, Virtue, Freedom & Autonomy | Macro Level | Proceedings of the AAAI/ACM Conference on AI, Ethics, and Society |
| 2024 | [PkuSafeRLHF](https://huggingface.co/datasets/PKU-Alignment/PKU-SafeRLHF) | [Pku-saferlhf: Towards multi-level safety alignment for llms with human preference](https://arxiv.org/abs/2406.15513v2) | Harmlessness, Freedom & Autonomy, Justice & Fairness,Turst, Privacy, Responsibility， Beneficence | Macro Level, Meso Level | arXiv preprint arXiv:2406.15513 |
| 2024 | [ProgressGym](https://github.com/pku-alignment/progressgym) | [ProgressGym: Alignment with a Millennium of Moral Progress](https://arxiv.org/abs/2406.20087) | Harmlessness， Freedom & Autonomy， Turst， Dignity， Beneficence | Macro Level | Advances in Neural Information Processing Systems |
| 2024 | [SafeSora](https://github.com/pku-alignment/safe-sora) | [SafeSora: Towards Safety Alignment of Text2Video Generation via a Human Preference Dataset](https://arxiv.org/abs/2406.14477) | Harmlessness,Usefulness，Responsibility | Macro Level | Advances in Neural Information Processing Systems |
| 2023 | [MFQ(Moral Foundations Questionnaire)](https://github.com/abdulhaim/moral_foundations_llms) | [Moral Foundations of Large Language Models](https://arxiv.org/abs/2310.15337) | Turst, Responsibility | Macro Level | |
| 2023 | [BeaverTails](https://sites.google.com/view/pku-beavertails) | [Beavertails: Towards improved safety alignment of llm via a human-preference dataset](https://arxiv.org/abs/2307.04657) | Harmlessness, Justice & Fairness, Privacy, Beneficence, Responsibility | Macro Level | Advances in Neural Information Processing Systems |
| 2023 | [CBBQ(Chinese Bias Benchmark Dataset)](https://github.com/YFHuangxxxx/CBBQ) | [CBBQ: A Chinese Bias Benchmark Dataset Curated with Human-AI Collaboration for Large Language Models](https://arxiv.org/abs/2306.16244) | China(Safeguarding national security and adhering to the core socialist values) | Meso Level | arXiv preprint arXiv:2306.16244 |
| 2023 | [CDEval](https://drive.google.com/drive/folders/1m6IIyNfDuiInpCNlrWxfu3vd_xtcG757?usp=drive_link) | [CDEval: A Benchmark for Measuring the Cultural Dimensions of Large Language Models](https://arxiv.org/abs/2311.16421) | Cultural, Eduaction, Individualism | Macro Level, Meso Level | arXiv preprint arXiv:2311.16421 |
| 2023 | [CORGI-PM](https://github.com/yizhilll/corgi-pm) | [CORGI-PM: A Chinese Corpus For Gender Bias Probing and Mitigation](https://arxiv.org/abs/2301.00395) | Justice & Fairness | Macro Level | arXiv preprint arXiv:2301.00395 |
| 2023 | [Cvalues](https://github.com/x-plug/cvalues) | [Cvalues: Measuring the values of chinese large language models from safety to responsibility.](https://arxiv.org/abs/2307.09705) | Harmlessness, Responsibility | Macro Level, Meso Level | arXiv preprint arXiv:2307.09705 |
| 2023 | [DecodingTrust](https://huggingface.co/datasets/AI-Secure/DecodingTrust) | [DecodingTrust: A Comprehensive Assessment of Trustworthiness in GPT Models](https://arxiv.org/abs/2306.11698) | Privacy, Justice & Fairness, Harmlessness | Macro Level | Cited on |
| 2023 | [EEC(Equity Evaluation Corpus)](https://saifmohammad.com/WebPages/Biases-SA.html) | [Examining Gender and Race Bias in Two Hundred Sentiment Analysis Systems](https://arxiv.org/abs/1805.04508) | Harmlessness | Macro Level | arXiv preprint arXiv:2311.04892 |
| 2023 | [Flames](https://github.com/AI45Lab/Flames) | [Flames: Benchmarking Value Alignment of LLMs in Chinese](https://arxiv.org/abs/2311.06899) | Justice & Fairness, Responsibility, Harmlessness, Privacy | Macro Level | arXiv preprint arXiv:2311.06899 |
| 2023 | [GlobalOpinionQA](https://huggingface.co/datasets/Anthropic/llm_global_opinions) | [Towards Measuring the Representation of Subjective Global Opinions in Language Models](https://arxiv.org/abs/2306.16388) | Nation, Culture | Macro Level, Meso Level | arXiv preprint arXiv:2306.16388 |
| 2023 | [Persona Bias](https://huggingface.co/datasets/allenai/persona-bias) | [Bias Runs Deep: Implicit Reasoning Biases in Persona-Assigned LLMs](https://arxiv.org/abs/2311.04892) | Dignity | Macro Level | arXiv preprint arXiv:2311.04892 |
| 2023 | [Social Chemistry 101](https://github.com/mbforbes/social-chemistry-101) | [TrustGPT: A Benchmark for Trustworthy and Responsible Large Language Models](https://arxiv.org/abs/2306.11507) | Justice & Fairness,Harmlessness， Responsibility， Dignity， Beneficence | Macro Level | arXiv preprint arXiv:2306.11507 |
| 2023 | [ToxiGen](https://github.com/microsoft/SafeNLP) | [An Empirical Study of Metrics to Measure Representational Harms in Pre-Trained Language Models](https://arxiv.org/abs/2301.09211) | Justice & Fairness | Macro Level | arXiv preprint arXiv:2301.09211 |
| 2022 | [CDial-Bias](https://github.com/para-zhou/cdial-bias?tab=readme-ov-file) | [Towards Identifying Social Bias in Dialog Systems: Frame, Datasets, and Benchmarks](https://arxiv.org/abs/2202.08011) | Virtue | Macro Level | arXiv preprint arXiv:2202.08011 |
| 2022 | [Moral Integrity Corpus](https://github.com/SALT-NLP/mic) | [The Moral Integrity Corpus: A Benchmark for Ethical Dialogue Systems](https://arxiv.org/abs/2204.03021) | Justice & Fairness, Responsibility, Beneficence, Dignity, Virtue | Macro Level | arXiv preprint arXiv:2204.03021 |
| 2022 | [MoralExceptQA](https://huggingface.co/datasets/feradauto/MoralExceptQA) | [When to Make Exceptions: Exploring Language Models as Accounts of Human Moral Judgment](https://arxiv.org/abs/2210.01478) | Solidarity, Harmlessness, Responsibility, Beneficence, Dignity | Macro Level | Advances in neural information processing systems |
| 2022 | [ValueNet](https://liang-qiu.github.io/ValueNet/) | [Valuenet: A new dataset for human value driven dialogue system.](https://arxiv.org/abs/2112.06346) | Freedom & Autonomy，Beneficence， Harmlessness， Dignity， Freedom & Autonomy | Macro Level | Proceedings of the AAAI Conference on Artificial Intelligence |
| 2021 | [BBQ(Bias Benchmark for QA)](https://github.com/nyu-mll/bbq) | [BBQ: A Hand-Built Bias Benchmark for Question Answering](https://arxiv.org/abs/2110.08193) | Justice & Fairness | Macro Level | arXiv preprint arXiv:2110.08193 |
| 2021 | [BOLD](https://dl.acm.org/doi/abs/10.1145/3442188.3445924) | [BOLD: Dataset and Metrics for Measuring Biases in Open-Ended Language Generation](https://dl.acm.org/doi/abs/10.1145/3442188.3445924) | Justice & Fairness | Macro Level | Proceedings of the 2021 ACM conference on fairness, accountability, and transparency |
| 2021 | [Scruples](https://github.com/allenai/scruples) | [Scruples: A Corpus of Community Ethical Judgments on 32,000 Real-Life Anecdotes](https://arxiv.org/abs/2008.09094) | Beneficence | Macro Level | Proceedings of the AAAI Conference on Artificial Intelligence |
| 2020 | [CrowS-Paris](https://github.com/nyu-mll/crows-pairs) | [CrowS-Pairs: A Challenge Dataset for Measuring Social Biases in Masked Language Models](https://arxiv.org/abs/2010.00133) | Justice & Fairness | Macro Level | arXiv preprint arXiv:2010.00133 |
| 2020 | [ETHICS](https://github.com/hendrycks/ethics) | [Aligning AI With Shared Human Values](https://arxiv.org/abs/2008.02275) | Justice & Fairness, Responsibility, Beneficence, Dignity, Usefulness | | arXiv preprint arXiv:2008.02275 |
| 2020 | [StereoSet](https://github.com/moinnadeem/StereoSet) | [StereoSet: Measuring stereotypical bias in pretrained language models](https://arxiv.org/abs/2004.09456) | Justice & Fairness | Macro Level | arXiv preprint arXiv:2004.09456 |
| 2020 | [UnQover](https://github.com/allenai/unqover) | [UnQovering Stereotyping Biases via Underspecified Questions](https://arxiv.org/abs/2010.02428) | Justice & Fairness | Macro Level | arXiv preprint arXiv:2010.02428 |
| 2019 | [Social Bias Frames](https://maartensap.com/social-bias-frames/) | [Social Bias Frames: Reasoning about Social and Power Implications of Language](https://arxiv.org/abs/1911.03891) | Freedom & Autonomy | Macro Level | arXiv preprint arXiv:1911.03891 |
| 2019 | [WikiGenderBias](https://aclanthology.org/attachments/2020.acl-main.265.Dataset.zip) | [Towards Understanding Gender Bias in Relation Extraction](https://arxiv.org/abs/1911.03642) | Dignity | Macro Level | arXiv preprint arXiv:1911.03642 |
| 2018 | [WinoBias](https://github.com/uclanlp/corefBias/tree/master/WinoBias/wino) | [Gender Bias in Coreference Resolution: Evaluation and Debiasing Methods](https://arxiv.org/abs/1804.06876) | Solidarity | Macro Level | arXiv preprint arXiv:1804.06876 |
| 2018 | [WinoGender](https://github.com/rudinger/winogender-schemas) | [Gender Bias in Coreference Resolution](https://arxiv.org/abs/1804.09301) | Justice & Fairness | Macro Level | arXiv preprint arXiv:1804.09301 |

## Future Directions

