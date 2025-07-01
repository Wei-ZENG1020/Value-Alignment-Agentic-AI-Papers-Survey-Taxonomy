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
  - [High Generaliability](#high-generaliability)
  - [Limited Generaliability](#limited-generaliability)
- [Values Alignment Evaluation for Agent Systems](#values-alignment-evaluation-for-agent-systems)
- [Methodologies for Agent Value Alignment](#methodologies-for-agent-value-alignment)
- [Datasets](#datasets)
- [Future Directions](#future-directions)


## Papers
### Overview of Our Survey
![](overview.png)
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
| 2025 | [Value alignment in ai large models: Current status, key issues, and normative strategies](https://kns.cnki.net/kcms2/article/abstract?v=HlDkjiDVjGsHl2FZ14zA_d2mQ2rjb62pPbB9UjCNzTbIgKKQK3LMWVnzDsokMfxdUPIjnTpDrLXTZ-Skr4B2hCjs0l6C5G8LKhp1QlSGu9h2k8nSuFpm1YO1vzdHtEgMsIEC4E6QTlLKpm6rIDINjQux-FFwhn1btD2-fJjvsHK2jt94X3BRoA==&uniplatform=NZKPT&language=CHS)                                                                                                                                                       | Necessity, conceptual definitions, theoretical approaches, challenges and future outlook of LLM value alignment |       CNKI                             |

![](takeaways-of-comparisons-of-representative-survey-papers.png)

### The Principles of Values Alignment
![](multi-level-value-alignment-principles.png)
#### The Macro Level Principles of Values Alignment
<table>
  <thead>
    <tr>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Sub-Level</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Sub-sub-Level</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Title</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Time</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="16">Moral Foundation</td>
      <td style="text-align:center; vertical-align:middle;" rowspan="2">Beneficience</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.nature.com/articles/s42256-019-0088-2" target="_blank" rel="noopener noreferrer">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2" target="_blank" rel="noopener noreferrer">ethics guidelines</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">Nature machine intelligence</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">A unified framework of five principles</a><br><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">for ai in society</a></td>
      <td style="text-align:center; vertical-align:middle;">2022</td>
      <td style="text-align:center; vertical-align:top;">Machine learning and the city: Applications inarchitecture and urban design</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="6">Justice &amp; Fairness</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">Nature machine intelligence</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">Ethics of ai: A</a><br><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">systematic literature review of principles and challenges</a></td>
      <td style="text-align:center; vertical-align:middle;">2022</td>
      <td style="text-align:center; vertical-align:top;">Proceedings of the 26th international conference on evaluation andassessment in software engineering</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">A unified framework of five principles</a><br><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">for ai in society</a></td>
      <td style="text-align:center; vertical-align:middle;">2022</td>
      <td style="text-align:center; vertical-align:top;">Machine learning and the city: Applications inarchitecture and urban design</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.sciencedirect.com/science/article/abs/pii/S030645732500041X">Towards realistic evaluation of cultural value alignment in large</a><br><a href="https://www.sciencedirect.com/science/article/abs/pii/S030645732500041X">language models: Diversity enhancement for survey response</a><br><a href="https://www.sciencedirect.com/science/article/abs/pii/S030645732500041X">simulation</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">Information Processing &amp; Management</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://openreview.net/forum?id=yoVq2BGQdP">Achieving fairness in multi-agent</a><br><a href="https://openreview.net/forum?id=yoVq2BGQdP">mdp using reinforcement learning</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:top;">The Twelfth InternationalConference on Learning Representations</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/4dbb61cb68671edc4ca3712d70083b9f-Abstract-Datasets_and_Benchmarks.html">Beavertails: Towards improved safety</a><br><a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/4dbb61cb68671edc4ca3712d70083b9f-Abstract-Datasets_and_Benchmarks.html">alignment of llm via a human-preference dataset</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:top;">Advances inNeural Information Processing Systems</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="2">Honesty</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2308.12014">From instructions</a><br><a href="https://arxiv.org/abs/2308.12014">to intrinsic human values - A survey of alignment goals for big</a><br><a href="https://arxiv.org/abs/2308.12014">models</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://openreview.net/forum?id=zj7YuTE4t8">Improving factuality and reasoning in language models through</a><br><a href="https://openreview.net/forum?id=zj7YuTE4t8">multiagent debate</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">Forty-first International Conference on Machine Learning</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="2">Responsibility</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">Nature machine intelligence</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">Ethics of ai: A</a><br><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">systematic literature review of principles and challenges</a></td>
      <td style="text-align:center; vertical-align:middle;">2022</td>
      <td style="text-align:center; vertical-align:top;">Proceedings of the 26th international conference on evaluation andassessment in software engineering</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="2">Virtue</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2410.02683">Dailydilemmas: Revealing value</a><br><a href="https://arxiv.org/abs/2410.02683">preferences of llms with quandaries of daily life</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:top;">The ThirteenthInternational Conference on Learning Representations, ICLR 2025,Singapore</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2501.07071">Value compass leaderboard: A platform</a><br><a href="https://arxiv.org/abs/2501.07071">for fundamental and validated evaluation of llms values</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="2">Dignity</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">Nature machine intelligence</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://kns.cnki.net/kcms2/article/abstract?v=HlDkjiDVjGvCXuvcEGR1HyyNZRJKbgHMrLGctym2m6XbDHHERqe3gtnbcC-vNmgkJX68I3yqT9vxbzidNLQVehHAnRUO6E21jMv903SX1B1ouRGMYNh59TcdU3e5Dniq8B_c0qZNH8HOVmE1rYWLM_p_ZRmV_bjKal4JaBXqyI0=&uniplatform=NZKPT">Shaping the ethical governance path ofartificial intelligence in</a><br><a href="https://kns.cnki.net/kcms2/article/abstract?v=HlDkjiDVjGvCXuvcEGR1HyyNZRJKbgHMrLGctym2m6XbDHHERqe3gtnbcC-vNmgkJX68I3yqT9vxbzidNLQVehHAnRUO6E21jMv903SX1B1ouRGMYNh59TcdU3e5Dniq8B_c0qZNH8HOVmE1rYWLM_p_ZRmV_bjKal4JaBXqyI0=&uniplatform=NZKPT">the chinese context—based on value-instrument rationality</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">Studies in Science of Science</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="7">Rights Protection</td>
      <td style="text-align:center; vertical-align:middle;" rowspan="3">Freedom &amp; Autonomy</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">Nature machine intelligence</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">A unified framework of five principles</a><br><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">for ai in society</a></td>
      <td style="text-align:center; vertical-align:middle;">2022</td>
      <td style="text-align:center; vertical-align:top;">Machine learning and the city: Applications inarchitecture and urban design</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://kns.cnki.net/kcms2/article/abstract?v=HlDkjiDVjGvCXuvcEGR1HyyNZRJKbgHMrLGctym2m6XbDHHERqe3gtnbcC-vNmgkJX68I3yqT9vxbzidNLQVehHAnRUO6E21jMv903SX1B1ouRGMYNh59TcdU3e5Dniq8B_c0qZNH8HOVmE1rYWLM_p_ZRmV_bjKal4JaBXqyI0=&uniplatform=NZKPT">Shaping the ethical governance path ofartificial intelligence in</a><br><a href="https://kns.cnki.net/kcms2/article/abstract?v=HlDkjiDVjGvCXuvcEGR1HyyNZRJKbgHMrLGctym2m6XbDHHERqe3gtnbcC-vNmgkJX68I3yqT9vxbzidNLQVehHAnRUO6E21jMv903SX1B1ouRGMYNh59TcdU3e5Dniq8B_c0qZNH8HOVmE1rYWLM_p_ZRmV_bjKal4JaBXqyI0=&uniplatform=NZKPT">the chinese context—based on value-instrument rationality</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">Studies in Science of Science</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="4">Privacy</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">Nature machine intelligence</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">Ethics of ai: A</a><br><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">systematic literature review of principles and challenges</a></td>
      <td style="text-align:center; vertical-align:middle;">2022</td>
      <td style="text-align:center; vertical-align:top;">Proceedings of the 26th international conference on evaluation andassessment in software engineering</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://dl.acm.org/doi/full/10.1145/3653982">Hydragan: A cooperative agent</a><br><a href="https://dl.acm.org/doi/full/10.1145/3653982">model for multi-objective data generation</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:top;">ACM Trans. Intell.Syst. Technol.</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2410.11906">Empowering users in digital</a><br><a href="https://arxiv.org/abs/2410.11906">privacy management through interactive llm-based agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:top;">TheThirteenth International Conference on Learning Representations, ICLR2025, Singapore</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="3">Sustainability</td>
      <td style="text-align:center; vertical-align:middle;">Solidarity</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">Nature machine intelligence</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="2">Sustainability</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">Nature machine intelligence</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/ca9567d8ef6b2ea2da0d7eed57b933ee-Abstract-Conference.html">Cooperate or collapse: Emergence of</a><br><a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/ca9567d8ef6b2ea2da0d7eed57b933ee-Abstract-Conference.html">sustainable cooperation in a society of LLM agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:top;">Advances in Neural Information Processing Systems 38: AnnualConference on Neural Information Processing Systems 2024,NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="15">System Governance</td>
      <td style="text-align:center; vertical-align:middle;" rowspan="5">Harmlessness</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">Nature machine intelligence</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">A unified framework of five principles</a><br><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">for ai in society</a></td>
      <td style="text-align:center; vertical-align:middle;">2022</td>
      <td style="text-align:center; vertical-align:top;">Machine learning and the city: Applications inarchitecture and urban design</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2308.12014">From instructions</a><br><a href="https://arxiv.org/abs/2308.12014">to intrinsic human values - A survey of alignment goals for big</a><br><a href="https://arxiv.org/abs/2308.12014">models</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2305.16960">Training socially aligned language models on simulated</a><br><a href="https://arxiv.org/abs/2305.16960">social interactions</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:top;">The Twelfth International Conferenceon Learning Representations, ICLR 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/1eb543faf7c69e8a7eb8b85f70be818f-Abstract-Datasets_and_Benchmarks_Track.html">Safesora: Towards safety alignment of text2video generation</a><br><a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/1eb543faf7c69e8a7eb8b85f70be818f-Abstract-Datasets_and_Benchmarks_Track.html">via a human preference dataset</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:top;">Advances in Neural InformationProcessing Systems</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="2">Trust</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">Nature machine intelligence</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.sciencedirect.com/science/article/abs/pii/S030645732500041X">Towards realistic evaluation of cultural value alignment in large</a><br><a href="https://www.sciencedirect.com/science/article/abs/pii/S030645732500041X">language models: Diversity enhancement for survey response</a><br><a href="https://www.sciencedirect.com/science/article/abs/pii/S030645732500041X">simulation</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">Information Processing &amp; Management</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="6">Transparency</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">Nature machine intelligence</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">A unified framework of five principles</a><br><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119815075.ch45">for ai in society</a></td>
      <td style="text-align:center; vertical-align:middle;">2022</td>
      <td style="text-align:center; vertical-align:top;">Machine learning and the city: Applications inarchitecture and urban design</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">Ethics of ai: A</a><br><a href="https://dl.acm.org/doi/abs/10.1145/3530019.3531329">systematic literature review of principles and challenges</a></td>
      <td style="text-align:center; vertical-align:middle;">2022</td>
      <td style="text-align:center; vertical-align:top;">Proceedings of the 26th international conference on evaluation andassessment in software engineering</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://dl.acm.org/doi/abs/10.1145/3680287">ICA-CRMAS: intelligent</a><br><a href="https://dl.acm.org/doi/abs/10.1145/3680287">context-awareness approach for citation recommendation based</a><br><a href="https://dl.acm.org/doi/abs/10.1145/3680287">on multi-agent system</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACM Trans. Manag. Inf. Syst.</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://openreview.net/forum?id=mDw42ZanmE">A multimodal</a><br><a href="https://openreview.net/forum?id=mDw42ZanmE">automated interpretability agent</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:top;">Forty-first InternationalConference on Machine Learning, ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2405.17631">Biodiscoveryagent: An</a><br><a href="https://arxiv.org/abs/2405.17631">ai agent for designing genetic perturbation experiments</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="2">Usefulness</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2308.12014">From instructions</a><br><a href="https://arxiv.org/abs/2308.12014">to intrinsic human values - A survey of alignment goals for big</a><br><a href="https://arxiv.org/abs/2308.12014">models</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2410.02683">Dailydilemmas: Revealing value</a><br><a href="https://arxiv.org/abs/2410.02683">preferences of llms with quandaries of daily life</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:top;">The ThirteenthInternational Conference on Learning Representations, ICLR 2025</td>
    </tr>
  </tbody>
</table>

#### The Meso Level Principles of Values Alignment
<table>
  <thead>
    <tr>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Sub-Level</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Sub-sub-level</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Title</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Time</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="11">National Level</td>
      <td style="text-align:center; vertical-align:middle;" rowspan="4">The United States</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2310.17551" target="_blank" rel="noopener noreferrer">Unpacking the ethical value</a><br><a href="https://arxiv.org/abs/2310.17551" target="_blank" rel="noopener noreferrer">alignment in big models</a></td>
      <td style="text-align:center; vertical-align:middle;">2022</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">Nature machine intelligence</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://bidenwhitehouse.archives.gov/ostp/ai-bill-of-rights/">Blueprint for an ai bill of rights: Making automated systems</a><br><a href="https://bidenwhitehouse.archives.gov/ostp/ai-bill-of-rights/">work for the american people</a></td>
      <td style="text-align:center; vertical-align:middle;">2022</td>
      <td style="text-align:center; vertical-align:middle;">White House Nimble Books</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.nitrd.gov/pubs/National-Artificial-Intelligence-Research-and-Development-Strategic-Plan-2023-Update.pdf">The national</a><br><a href="https://www.nitrd.gov/pubs/National-Artificial-Intelligence-Research-and-Development-Strategic-Plan-2023-Update.pdf">artificial intelligence research and development strategic plan: 2023</a><br><a href="https://www.nitrd.gov/pubs/National-Artificial-Intelligence-Research-and-Development-Strategic-Plan-2023-Update.pdf">update</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">National Science and Technology Council (US)</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="4">European Union</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://digital-strategy.ec.europa.eu/en/library/ethics-guidelines-trustworthy-ai">Ethics</a><br><a href="https://digital-strategy.ec.europa.eu/en/library/ethics-guidelines-trustworthy-ai">guidelines for trustworthy AI</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">High-level expert group on artificial intelligence</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://artificialintelligenceact.eu/">EU Artificial intelligence act</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">Regulamento da União Europeia (UE)</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2310.17551">Unpacking the ethical value</a><br><a href="https://arxiv.org/abs/2310.17551">alignment in big models</a></td>
      <td style="text-align:center; vertical-align:middle;">2022</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.nature.com/articles/s42256-019-0088-2">The global landscape of ai</a><br><a href="https://www.nature.com/articles/s42256-019-0088-2">ethics guidelines</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">Nature machine intelligence</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="3">China</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.gov.cn/zhengce/zhengceku/202310/content_6908045.htm">Measures for the ethical review of science and</a><br><a href="https://www.gov.cn/zhengce/zhengceku/202310/content_6908045.htm">technology</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">C. A. of Sciences</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;">Standardization of ai ethical governance </td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">ational Artificial Intelligence StandardizationGeneral Group</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2310.17551">Unpacking the ethical value</a><br><a href="https://arxiv.org/abs/2310.17551">alignment in big models</a></td>
      <td style="text-align:center; vertical-align:middle;">2022</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="3">Industry Level</td>
      <td style="text-align:center; vertical-align:middle;">Education</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research">Guidance for generative AI in education</a><br><a href="https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research">and research</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">UNESCO Publishing</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;">Health</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://www.who.int/publications/i/item/9789240084759">Ethics and governance of artificial</a><br><a href="https://www.who.int/publications/i/item/9789240084759">intelligence for health: Guidance on large multi-modal models</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">W. H. Organization</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;">Gaming</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2305.07392">The ethics of ai in games</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">IEEE Transactions onAffective Computing</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="9">Cultural Level</td>
      <td style="text-align:center; vertical-align:middle;" rowspan="4">Large/Small Power Distance<br>Strong/Weak Uncertainty Avoidance<br>Individual/Collectivism</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/">Dimensionalizing cultures: The hofstede model in</a><br><a href="https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/">context</a></td>
      <td style="text-align:center; vertical-align:middle;">2011</td>
      <td style="text-align:center; vertical-align:middle;">Online readings in psychology and culture</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2311.16421">Cdeval: A benchmark for measuring the cultural dimensions of</a><br><a href="https://arxiv.org/abs/2311.16421">large language models</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2406.14805">How well do</a><br><a href="https://arxiv.org/abs/2406.14805">llms represent values across cultures? empirical analysis of llm</a><br><a href="https://arxiv.org/abs/2406.14805">responses based on hofstede cultural dimensions</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2411.06032">Llm-globe: A benchmark evaluating the cultural values</a><br><a href="https://arxiv.org/abs/2411.06032">embedded in llm output</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="3">Long/Short-Term Orientation<br>Masculinity/Femininity</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/">Dimensionalizing cultures: The hofstede model in</a><br><a href="https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/">context</a></td>
      <td style="text-align:center; vertical-align:middle;">2011</td>
      <td style="text-align:center; vertical-align:middle;">Online readings in psychology and culture</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2311.16421">Cdeval: A benchmark for measuring the cultural dimensions of</a><br><a href="https://arxiv.org/abs/2311.16421">large language models</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2406.14805">How well do</a><br><a href="https://arxiv.org/abs/2406.14805">llms represent values across cultures? empirical analysis of llm</a><br><a href="https://arxiv.org/abs/2406.14805">responses based on hofstede cultural dimensions</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="2">Indulgence/Restrained</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/">Dimensionalizing cultures: The hofstede model in</a><br><a href="https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/">context</a></td>
      <td style="text-align:center; vertical-align:middle;">2011</td>
      <td style="text-align:center; vertical-align:middle;">Online readings in psychology and culture</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2311.16421">Cdeval: A benchmark for measuring the cultural dimensions of</a><br><a href="https://arxiv.org/abs/2311.16421">large language models</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
  </tbody>
</table>

#### The Micro Level Principles of Values Alignment
<table>
  <thead>
    <tr>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Sub-Level</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Title</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Time</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="3">Recruiment</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://sciendo-parsed.s3.eu-central-1.amazonaws.com/6472540a215d2f6c89dc43ab/10.1515_mspe-2019-0018.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIA6AP2G7AKLD7LVJ4I/20250701/eu-central-1/s3/aws4_request&X-Amz-Date=20250701T020101Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENH//////////wEaDGV1LWNlbnRyYWwtMSJHMEUCIGwyocJnGwzEazGG47IHioJhcJYKvmdRQapGQwxckITNAiEA46W1g9lMj5bO6v/dJcg6rj5CBHO9J4nbM7z5kfkhdDkqxAUIyv//////////ARACGgw5NjMxMzQyODk5NDAiDNchYkKNnKSQqU5dlyqYBYyq18WaikGIWSEANdyYQdWVsVuMdpJ7EhLwNKwOIn7DzIRbHKdZYmI9BVrNTSGzdz+Nji0WDCHNnRoIISelICoEcJ7+88PmrLg0CgXtqbBkVCTer8pZrLBZU3eyFzn20kyP4JH/foMhPUzBmv+m7hdUNRc6ek7u9M/xlEgojG0Xt1DMO2h0gc4h1wGfM8oFwyHyAluhTKkNs1MpiNa3fSUeklME6ZSq6AEiIdzrzFIQdO4tl+CiXMh+pR6xC3ba951rH6qJyAIRSqIHPOsyD+WEBzZs0fjGjjJgxH+h3IKDupvetAhXz5qRULt4J0PyWSp9uWStoDGH6fXcT7XV30Eyk5pZiTQrStvLvs1xRKM2TZZkYvEg4eK6GpwNnwTIf4kwTjpTOqTpCptGaqYXQom2gAM127ts5ZWJu5HPSxYbjtl+In3mIO6brjskARidxr0xIZvQnJkGxYYpNA+Kq+LKeH7TmntSXT/mD5TGvUvE4stgWPcgDSU3qyO0PrtbPCbxQ7Q2Q10MQVjP9fhxzswIPUmLJxQv+LMPU3lxxgXzvGtxkOY7sW29dAJI6oQclB5nt83dxAtandSjhR0dhX9dHhwO68TyjwQoDL7nNdqHEesRhU0VZkfnXhaE1QS7lT0OZhLL7KVLPIsH2IDzIAo4dxB9oszc3WXKRsR4P9eUV3kZDRaJoZZvE1AGru/iBzk77YYAUEfI9e4nqDxU+VVGoPtGJr0nCpADfbgQfzHF6KAy0+AhK8NWzdpAgEonlZGHbajNMMLRFtJ4p1dh+iKd1MPBQd1dp31d/3UVm0HOmawdaDzxJdMWgpq3TfgAhYmEY50nEqNqt7QcdmoC4UxeEGP6ksv7QbbyqBQb+tlZWyiv8km7X6Yw4O2MwwY6sQHLefZLLMlUBng0okDVdJBFmZs4u6SHx4nUbVQocwcoSL/gLGFPnY9aS4R1HAyTRnKs0mmKZwQOzYrbsal7OuD8sqsxgOt62Ei9xLpr3nQW5WJnIUVsfDe/40X0V7wBgDIbW/SNNEVk9x2ltjvEbYNLJS0BOTeg/DJRefMgk8oOZG76iy/nY/ldFT3B7rpxo5sWF+YHMy+hi8sJDCFZ85uKTegqbQLhECdnE5hBsx1w2G8=&X-Amz-Signature=665b8884bfc6ec19c395ef8ee2a18eae3f1439e37a3dcd5e045902950a5670ee&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject" target="_blank" rel="noopener noreferrer">Recruitment in the times of machine learning</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">Management Systems in Production Engineering</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://ieeexplore.ieee.org/document/8708197">HR analytics and ethics</a></td>
      <td style="text-align:center; vertical-align:middle;">2019</td>
      <td style="text-align:center; vertical-align:middle;">IBM Journal of Research andDevelopment</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:top;"><a href="https://link.springer.com/article/10.1007/S10551-022-05049-6">Ethics of ai-enabled re-cruiting and selection: A review and research agenda</a></td>
      <td style="text-align:center; vertical-align:middle;">2022</td>
      <td style="text-align:center; vertical-align:middle;">Journal ofBusiness Ethics</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;">Legal Consultation</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://arxiv.org/abs/2407.16252">Lawluo: A chinese law firm co-run by llm agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;">Pharmaceutical Company Governance</td>
      <td style="text-align:center; vertical-align:top;"><a href="https://link.springer.com/article/10.1007/s43681-022-00171-7">Operationalising ai governance through ethics-based auditing: an industry case study</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">AI andEthics</td>
    </tr>
  </tbody>
</table>

![](takeaways-of-value-principles.png)

### Agent System Application
#### High Generaliability
<table>
  <thead>
    <tr>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Generalizability</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Category</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Title</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Time</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="68">High</td>
      <td style="text-align:center; vertical-align:middle;" rowspan="5">Tool Using</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=0bmGL4q7vJ" target="_blank" rel="noopener noreferrer">Multi-modal agent tuning: Building avlm-driven agent for efficient tool usage</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=DYMj03Gbri" target="_blank" rel="noopener noreferrer">Agent smith: A single image can jailbreak one million multimodal LLM agents exponentially fast</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20%208a75ee6d4b2eb0b777f549a32a5a5c28-Abstract-Datasets_and_%20%20Benchmarks_Track.html" target="_blank" rel="noopener noreferrer">GTA: A benchmark for general tool agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">Advances in Neural Information Processing Systems</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.624" target="_blank" rel="noopener noreferrer">Injecagent: Benchmarking indirect prompt injections in tool-integrated large language model agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20%20c2f71567cd53464161cab3336e8fc865-Abstract-Datasets_and_%20%20Benchmarks_Track.html" target="_blank" rel="noopener noreferrer">Spider2-v: How far are multimodal agents from automating data science and engineering workflows?</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">Advances in Neural Information Processing Systems</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="14">Dialugue <br>Agents</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1109/TASLP.2024.3357032" target="_blank" rel="noopener noreferrer">Please donate to save a life: Inducing politeness to handle resistance in persuasive dialogue agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">IEEE ACM Trans. Audio Speech<br>Lang. Process</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=b6rA0kAHT1" target="_blank" rel="noopener noreferrer">Archer: Training language model agents via hierarchical multi-turn RL</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://www.ijcai.org/proceedings/2024/1032" target="_blank" rel="noopener noreferrer">Inside out: Emotional multiagent multimodal dialogue systems</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">IJCAI 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.972" target="_blank" rel="noopener noreferrer">KEEP chatting! an attractive dataset for continuous conversation agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=xKDZAW0He3" target="_blank" rel="noopener noreferrer">Secom: On memory construction and retrieval for personalized conversational agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.632" target="_blank" rel="noopener noreferrer">STYLE: improving domain transferability of asking clarification questions in large language model powered conversationalagents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.801" target="_blank" rel="noopener noreferrer">Talk with human-like agents: Empathetic dialogue through perceptible acoustic reception and reaction</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20%20097c514162ea7126d40671d23e12f51b-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">AGILE: A novel reinforcement learning framework of LLM agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3637528.3671646" target="_blank" rel="noopener noreferrer">Intelligent agents with llm-based process automation</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">KDD 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.102" target="_blank" rel="noopener noreferrer">Incharacter: Evaluating personality fidelity in role-playing agents through psychological interviews</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=MCNqgUFTHI" target="_blank" rel="noopener noreferrer">Plug and-play policy planner for large language model powered dialogue agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.274" target="_blank" rel="noopener noreferrer">Probing the uniquely identifiable linguistic patterns of conversational AI agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.125" target="_blank" rel="noopener noreferrer">Socialbench: Sociality evaluation of role-playing conversational agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.307" target="_blank" rel="noopener noreferrer">Speaker verification in agent-generated conversations</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="4">Multimodal Perception</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=K5yeB4dTtS" target="_blank" rel="noopener noreferrer">MLLM as retriever: Interactively learning multimodal retrieval for embodied agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=0bmGL4q7vJ" target="_blank" rel="noopener noreferrer">Multi-modal agent tuning: Building a vlm-driven agent for efficient tool usage</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=DYMj03Gbri" target="_blank" rel="noopener noreferrer">Agent smith: A single image can jailbreak one million multimodal LLM agents exponentially fast</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=QMy2RLnxGN" target="_blank" rel="noopener noreferrer">Doraemongpt: Toward understanding dynamic scenes with large language models (exemplified as A video agent)</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="11">Multi-Agent Collaboration</td>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%203e4d8407cb468850f2f8f4a949e64bf0-Abstract-Datasets_and_%20Benchmarks_Track.html" target="_blank" rel="noopener noreferrer">Adasociety: An adaptive environment with social structures for multi-agent decision-making</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.782" target="_blank" rel="noopener noreferrer">Exploring collaboration mechanisms for LLM agents: A social psychology view</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=%20tmqOhBC4a5" target="_blank" rel="noopener noreferrer">Maximum entropy heterogeneous-agent reinforcement learning</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1109/TFUZZ.2024.3363053" target="_blank" rel="noopener noreferrer">Fuzzy feedback multiagent reinforcement learning for adversarial dynamic multiteam competitions</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">IEEE Trans. Fuzzy Syst.</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://proceedings.mlr.press/v202/ding23d.html" target="_blank" rel="noopener noreferrer">Entity divider with language grounding in multi-agent reinforcement learning</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2023</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1016/j.aei.2024.102646" target="_blank" rel="noopener noreferrer">Collaborative dynamic scheduling in a self-organizing manufacturing system using multi-agent reinforcement learning</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">Adv. Eng. Informatics</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.305" target="_blank" rel="noopener noreferrer">Experiential co-learning of software-developing agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%205a7c947568c1b1328ccc5230172e1e7c-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Swe-agent: Agent-computer interfaces enable automated software engineering</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%206e9f99809b6df59e8fe5c9ffe269bf40-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Learning to cooperate with humans using generative agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%207d6e85e88495104442af94c98e899659-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Long-horizon planning for multi-agent robots in partially observable environments</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.778" target="_blank" rel="noopener noreferrer">360°rea: Towards A reusable experience accumulation with 360° assessment for multi-agent system</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="4">Visual Tasks Processing</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3643565" target="_blank" rel="noopener noreferrer">Cobjeason: Reasoning covered object in image by multi-agent collaboration based on informed knowledge graph</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACM Trans. Knowl. Discov. Data</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20e7c786024ca718f2487712bfe9f51030-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Genartist: Multimodal LLM as an agent for unified image generation and editing</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20c78f639424b8d89ceb4f2efbb4dfe4f4-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Restoreagent: Autonomous image restoration agent via multimodal large language models</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=gAyzjHw2ml" target="_blank" rel="noopener noreferrer">Scenecraft: An LLM agent for synthesizing 3d scenes as blender code</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="6">Natural Language Processing</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1109/TASLP.2024.3375630" target="_blank" rel="noopener noreferrer">Kgagent: Learning a deep reinforced agent for keyphrase generation</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">IEEE ACM Trans. Audio Speech Lang. Process.</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=OTmcsyEO5G" target="_blank" rel="noopener noreferrer">A human inspired reading agent with gist memory of very long contexts</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.12" target="_blank" rel="noopener noreferrer">Text2db: Integration aware information extraction with large language model agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1016/j.ipm.2025.104136" target="_blank" rel="noopener noreferrer">Optimizing text-to-sql conversion techniques through the integration of intelligent agents and large language models</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">Inf. Process. Manag.</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.336" target="_blank" rel="noopener noreferrer">Xmc-agent : Dynamic navigation over scalable hierarchical index for incremental extreme multi-label classification</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.446" target="_blank" rel="noopener noreferrer">A two-agent game for zero-shot relation triplet extraction</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;">Data Generation and Analysis</td>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20b235f0b417e8bf270c0cb19fe0b82c1e-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Transagent: Transfer vision-language foundation models with heterogeneous agent collaboration</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="23">Reasoning, Planning <br>and Decision Optimization</td>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2023/hash/%20029df12a9363313c3e41047844ecad94-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">AVIS: autonomous visual information seeking with large language model agent</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2023</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=s9z0HzWJJp" target="_blank" rel="noopener noreferrer">Sociodojo: Building lifelong analytical agents with real-world text and time series</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=zMwFvxr6CV" target="_blank" rel="noopener noreferrer">Agent instructs large language models to be general zero-shot reasoners</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20d032263772946dd5026e7f3cd22bce5b-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Agent planning with world knowledge model</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%200142921fad7ef9192bd87229cdafa9d4-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Automanual: Constructing instruction manuals by LLM agents via interactive environmental learning</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=zj7YuTE4t8" target="_blank" rel="noopener noreferrer">Improving factuality and reasoning in language models through multiagent debate</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=ffLblkoCw8" target="_blank" rel="noopener noreferrer">Magdi: Structured distillation of multi-agent interaction graphs improves reasoning in smaller language models</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://www.ijcai.org/proceedings/2024/892" target="_blank" rel="noopener noreferrer">Social learning through interactions with other agents: A survey</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">IJCAI 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=7M0EzjugaN" target="_blank" rel="noopener noreferrer">Online continual learning for interactive instruction following agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=l5XQzNkAOe" target="_blank" rel="noopener noreferrer">Travelplanner: A benchmark for real-world planning with language agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.409" target="_blank" rel="noopener noreferrer">Trial and error: Exploration-based trajectory optimization of LLM agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://proceedings.mlr.press/v202/sumers23a.html" target="_blank" rel="noopener noreferrer">Distilling internet-scale vision-language models into embodied agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2023</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2023/hash/%20bb3cfcb0284642a973dd631ec9184f2f-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Grounded decoding: Guiding text generation with grounded models for embodied agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2023</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=OhUoTMxFIH" target="_blank" rel="noopener noreferrer">Robotouille: An asynchronous planning benchmark for LLM agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=usUPvQH3XK" target="_blank" rel="noopener noreferrer">Language agents with reinforcement learning for strategic play in the werewolf game</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%2085f1225db986e629289f402c46eff1a4-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Omnijarvis: Unified vision language-action tokenization enables open-world instruction following agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3637528.3671650" target="_blank" rel="noopener noreferrer">Understanding the weakness of large language model agents within a complex android environment</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">KDD 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20b631da756d1573c24c9ba9c702fde5a9-Abstract-Datasets_and_%20Benchmarks_Track.html" target="_blank" rel="noopener noreferrer">Embodied agent interface: Benchmarking llms for embodied decision making</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3696410.3714825" target="_blank" rel="noopener noreferrer">Tool learning in the wild: Empowering language models as automatic tool agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">WWW 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2023/hash/%204b0eea69deea512c9e2c469187643dc2-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Swiftsage: A generative agent with fast and slow thinking for complex interactive tasks</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2023</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/%20hash/a79f3ef3b445fd4659f44648f7ea8ffd-Abstract-Datasets_and_%20Benchmarks_Track.html" target="_blank" rel="noopener noreferrer">On the effects of data scale on UI control agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.802" target="_blank" rel="noopener noreferrer">Rada: Retrieval-augmented web agent planning with llms</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3696410.3714765" target="_blank" rel="noopener noreferrer">Division-of-thoughts: Harnessing hybrid language model synergy for efficient on-device agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">WWW 2025</td>
    </tr>
  </tbody>
</table>

#### Limited Generaliability
<table>
  <thead>
    <tr>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Generalizability</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;" colspan="2">Category</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Title</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Time</th>
      <th style="font-weight:bold; text-align:center; vertical-align:middle;">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="79">Limited</td>
      <td style="text-align:center; vertical-align:middle;" rowspan="44">Function- driven</td>
      <td style="text-align:center; vertical-align:middle;" rowspan="4">Code Generation</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.269" target="_blank" rel="noopener noreferrer">Mapcoder: Multi-agent code generation for competitive problem solving</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.921" target="_blank" rel="noopener noreferrer">Tailoring with targeted precision: Edit-based agents for open-domain procedure customization</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20820c61a0cd419163ccbd2c33b268816e-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Worldcoder, a model-based LLM agent: Building world models by writing code and interacting with the environment</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%2094f093b41fc2666376fb1f667fe282f3-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Swt-bench: Testing and validating real-world bug-fixes with code agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="15">Social Simulation</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3708985" target="_blank" rel="noopener noreferrer">User behavior simulation with large language model-based agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ACM Trans. Inf. Syst.</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://www.ijcai.org/proceedings/2024/1007" target="_blank" rel="noopener noreferrer">An llm-enhanced agent-based simulation tool for information propagation</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">IJCAI 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%201cb57fcf7ff3f6d37eebae5becc9ea6d-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Can large language model agents simulate human trust behavior?</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=wGtzp4ZT1n" target="_blank" rel="noopener noreferrer">Competeai: Understanding the competition dynamics of large language model-based agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20ca9567d8ef6b2ea2da0d7eed57b933ee-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Cooperate or collapse: Emergence of sustainable cooperation in a society of LLM agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20df2d62b96a4003203450cf89cd338bb7-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Richelieu: Self-evolving llm-based agents for AI diplomacy</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=mM7VurbA4r" target="_blank" rel="noopener noreferrer">SOTOPIA: interactive evaluation for social intelligence in language agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.526" target="_blank" rel="noopener noreferrer">Towards objectively benchmarking social intelligence of language agents at the action level</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2023/hash/%20a3621ee907def47c1b952ade25c67698-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">CAMEL: communicative agents for ""mind"" exploration of large language model society</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2023</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%205875aca1ef70285a35940afbbce0f9fb-Abstract-Datasets_and_%20Benchmarks_Track.html" target="_blank" rel="noopener noreferrer">Roleagent: Building, interacting, and benchmarking high-quality role-playing agents from scripts</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.964" target="_blank" rel="noopener noreferrer">Villageragent: A graph-based multi-agent framework for coordinating complex task dependencies in minecraft</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2023/hash/%206b8dfb8c0c12e6fafc6c256cb08a5ca7-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Describe, explain, plan and select: Interactive planning with llms enables open-world multi-task agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2023</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://proceedings.mlr.press/v202/nottingham23a.html" target="_blank" rel="noopener noreferrer">Do embodied agents dream of pixelated sheep: Embodied decision making using language guided world modelling</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2023</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.698" target="_blank" rel="noopener noreferrer">Sotopia-π: Interactive learning of socially intelligent language agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.215" target="_blank" rel="noopener noreferrer">Timearena: Shaping efficient multitasking language agents in a time-aware simulation</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="19">Graphical User Interface Agents</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.477" target="_blank" rel="noopener noreferrer">On the multi-turn instruction following for conversational web agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.505" target="_blank" rel="noopener noreferrer">Seeclick: Harnessing GUI grounding for advanced visual GUI agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.186" target="_blank" rel="noopener noreferrer">You only look at screens: Multimodal chain-of-action agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=9JQtrumvg8" target="_blank" rel="noopener noreferrer">A real-world webagent with planning, long context understanding, and program synthesis</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=oWdzUpOlkX" target="_blank" rel="noopener noreferrer">Agentoccam: A simple yet strong baseline for llm-based web agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20a6a6891cf1dfc64d664f086cf5976e93-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Synatra: Turning indirect knowledge into direct demonstrations for digital agents at scale,</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=lIVRgt4nLv" target="_blank" rel="noopener noreferrer">Agent S: an open agentic framework that uses computers like a human</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=EEgYUccwsV" target="_blank" rel="noopener noreferrer">Agenttrek: Agent trajectory synthesis via guiding replay with web tutorials</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.50" target="_blank" rel="noopener noreferrer">Visualwebarena: Evaluating multimodal agents on realistic visual web tasks</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=oKn9c6ytLx" target="_blank" rel="noopener noreferrer">Webarena: A realistic web environment for building autonomous agent</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.371" target="_blank" rel="noopener noreferrer">Webvoyager: Building an end-to-end web agent with large multimodal models</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=BRfqYrikdo" target="_blank" rel="noopener noreferrer">Workarena: How capable are web agents at solving common knowledge work tasks?</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3696410.3714842" target="_blank" rel="noopener noreferrer">Large language models empowered personalized web agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">WWW 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://www.ijcai.org/proceedings/2024/711" target="_blank" rel="noopener noreferrer">Screenagent: A vision language model-driven computer control agent</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">IJCAI 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3637528.3671620" target="_blank" rel="noopener noreferrer">Autowebglm: A large language model-based web navigating agent</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACM, 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.539" target="_blank" rel="noopener noreferrer">Coco-agent: A comprehensive cognitive MLLM agent for smartphone GUI automation</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL<br>2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20d8efbb5dd415974eb095c3f06bff1f48-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Autoguide: Automated generation and selection of context-aware guidelines for large language model agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=Dissecting" target="_blank" rel="noopener noreferrer"> adversarial robustness of multimodal LM agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=oVKEAFjEqv" target="_blank" rel="noopener noreferrer">Webrl: Training LLM web agents via self-evolving online curriculum reinforcement learning</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="6">Model Analysis, Evaluation and Improvement</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=DwTgy1hXXo" target="_blank" rel="noopener noreferrer">Dynamic evaluation of large language models by meta probing agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=mDw42ZanmE" target="_blank" rel="noopener noreferrer">A multimodal automated interpretability agent</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20b35c38f70065ac6c694089ca93a015bb-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Ali-agent: Assessing llms’ alignment with human values via agent-based evaluation</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS<br>2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=FQepisCUWu" target="_blank" rel="noopener noreferrer">Chateval: Towards better llm-based evaluators through multi-agent debate</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.48550/arXiv.2504.13192" target="_blank" rel="noopener noreferrer">Cheatagent: Attacking llm-empowered recommender systems via LLM agent</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%200852b88e96d973bd4e21b673f51621d0-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Star-agents: Automatic data optimization with LLM agents for instruction tuning</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="35">Scenario- driven</td>
      <td style="text-align:center; vertical-align:middle;" rowspan="4">Finance</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3637528.3671801" target="_blank" rel="noopener noreferrer">A multimodal foundation agent for financial trading: Tool augmented, diversified, and generalist</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">KDD 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.829" target="_blank" rel="noopener noreferrer">Econagent: Large language model-empowered agents for simulating macroeconomic activities</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20f7ae4fe91d96f50abc2211f09b6a7e49-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Fincon: A synthesized LLM multi-agent system with conceptual verbal reinforcement for enhanced financial decision making</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3688399" target="_blank" rel="noopener noreferrer">Designing heterogeneous LLM agents for financial sentiment analysis</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ACM Trans. Manag. Inf. Syst.</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="5">Science</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=LfJgeBNCFI" target="_blank" rel="noopener noreferrer">Ds-agent: Automated data science by empowering large language models with case-based reasoning</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3680287" target="_blank" rel="noopener noreferrer">ICA-CRMAS: intelligent context-awareness approach for citation recommendation based on multi-agent system</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACM Trans. Manag. Inf. Syst.</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.701" target="_blank" rel="noopener noreferrer">Matplotagent: Method and evaluation for llm-based agentic scientific data visualization</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=9YNyiCJE3k" target="_blank" rel="noopener noreferrer">OSDA agent: Leveraging large language models for de novo design of organic structure directing agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=6z4YKr0GK6" target="_blank" rel="noopener noreferrer">Scienceagentbench: Toward rigorous assessment of language agents for data-driven scientific discovery</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="7">Healthcare</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.33" target="_blank" rel="noopener noreferrer">Medagents: Large language models as collaborators for zero-shot medical reasoning</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=rFpZnn11gj" target="_blank" rel="noopener noreferrer">Pathgen-1.6m: 1.6 million pathology image-text pairs generation through multi-agent collaboration,</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.779" target="_blank" rel="noopener noreferrer">Psychogat: A novel psychological measurement paradigm through interactive fiction games with LLM agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.48550/arXiv.2401.06155" target="_blank" rel="noopener noreferrer">De novo drug design using reinforcement learning with multiple GPT agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">arXiv</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=HAwZGLcye3" target="_blank" rel="noopener noreferrer">Biodiscoveryagent: An AI agent for designing genetic perturbation experiments</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3696410.3714877" target="_blank" rel="noopener noreferrer">Colacare: Enhancing electronic health record modeling through large language model-driven multi-agent collaboration</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ACM 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2023/hash/%207b16688a2b053a1b01474ab5c78ce662-Abstract-Datasets_and_%20Benchmarks.html" target="_blank" rel="noopener noreferrer">Spokenwoz: A large-scale speech-text benchmark for spoken task-oriented dialogue agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2023</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2023</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="5">Game</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=eN1T7I7OpZ" target="_blank" rel="noopener noreferrer">Advancing DRL agents in commercial fighting games: Training, integration, and agent-human alignment</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICML 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.490" target="_blank" rel="noopener noreferrer">Deciphering digital detectives: Understanding LLM behaviors and capabilities in multi-agent mystery games</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.935" target="_blank" rel="noopener noreferrer">STARLING: self-supervised training of text-based reinforcement learning agent with large language models,</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%209dd4533e7e4e5ed809344280609c5b05-Abstract-Datasets_and_%20Benchmarks_Track.html" target="_blank" rel="noopener noreferrer">Whodunitbench: Evaluating large multimodal agents via murder mystery games</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=r1KcapkzCt" target="_blank" rel="noopener noreferrer">Monte carlo planning with large language model for text-based game agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;">Manufacturing</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=r1KcapkzCt" target="_blank" rel="noopener noreferrer">Monte carlo planning with large language model for text-based game agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="4">Robotics</td>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%200520537ba799d375b8ff5523295c337a-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Mobile-agent-v2: Mobile device operation assistant with effective navigation via multi-agent collaboration</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.%20net/forum?id=NltzxpG0nz" target="_blank" rel="noopener noreferrer">Steve-eye: Equipping llm-based embodied agents with visual perception in open worlds</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=S1Bv3068Xt" target="_blank" rel="noopener noreferrer">Can we trust embodied agents? exploring backdoor attacks against embodied llm based decision-making systems</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.37" target="_blank" rel="noopener noreferrer">Opex: A component-wise analysis of llm-centric agents in embodied instruction following</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="3">Urban  Computing</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.findings-acl.362" target="_blank" rel="noopener noreferrer">Geoagent: To empower llms using geospatial tools for address standardization</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20e142fd2b70f10db2543c64bca1417de8-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Large language models as urban residents: An LLM agent framework for personal mobility generation</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20decd42d78c42cea59c95c7c3d40d5e0f-Abstract-Conference.htm" target="_blank" rel="noopener noreferrer">Urbankgent: A unified large language model agent framework for urban knowledge graph construction</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="2">Social  Media</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3696410.3714895" target="_blank" rel="noopener noreferrer">Ask, acquire, understand: A multimodal agent-based framework for social abuse detection in memes</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ACM 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3696410.3714748" target="_blank" rel="noopener noreferrer">Local: Logical and causal fact-checking with llm-based multi-agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ACM 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="2">Autonomous  Driving</td>
      <td style="text-align:center; vertical-align:middle;"><a href="http://papers.nips.cc/paper_files/paper/2024/hash/%20cef5c8dec67597b8543c64bca1417de8-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">SMART: scalable multi agent real-time motion generation via next-token prediction</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">NeurIPS 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.1145/3690624.3709379" target="_blank" rel="noopener noreferrer">Llmlight: Large language models as traffic signal control agents</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">KDD 2025</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;" rowspan="2">Literary  Creation</td>
      <td style="text-align:center; vertical-align:middle;"><a href="https://doi.org/10.18653/v1/2024.acl-long.88" target="_blank" rel="noopener noreferrer">IBSEN: director-actor agent collaboration for controllable and interactive drama script generation</a></td>
      <td style="text-align:center; vertical-align:middle;">2024</td>
      <td style="text-align:center; vertical-align:middle;">ACL 2024</td>
    </tr>
    <tr>
      <td style="text-align:center; vertical-align:middle;"><a href="https://openreview.net/forum?id=HfWcFs7XLR" target="_blank" rel="noopener noreferrer">Agents’ room: Narrative generation through multi-step collaboration</a></td>
      <td style="text-align:center; vertical-align:middle;">2025</td>
      <td style="text-align:center; vertical-align:middle;">ICLR 2025</td>
    </tr>
</tbody></table>

![](takeaways-of-application-scenarios.png)


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

![](takeaways-of-future-directions.png)
