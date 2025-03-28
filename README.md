# Repo-Level Autonomous Program Repair

## Introduction

Up to 2025-01-04, autonomous program repair technologies evaluated on SWE-Bench can be mainly divided into 3 catagories:
Agent-Based Method, Agentless Based Method, and Fine-Tuned Based Method.
The workflow of these methods usually includes 3 phases: localization, repair gen eration, and repair validation.
> @Agent-Based Method  
> @Agentless Based Method  
> @Fine-Tuned Based Method

## Empirical Study

| Cite                                                                                                                              |                           Literature                            | Journal/Conference | Time |               URL                |
|-----------------------------------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------:|:------------------:|:----:|:--------------------------------:|
| Meng, Xiangxin, et al. "An Empirical Study on LLM-based Agents for Automated Bug Fixing." arXiv preprint arXiv:2411.10213 (2024). | An Empirical Study on LLM-based Agents for Automated Bug Fixing |       Arxiv        | 2024 | https://arxiv.org/abs/2405.15793 |

## Papers

| Cite                                                                                                                                                                        |         Literature          | Journal/Conference | Time |    Label    | Resolved% |    LLM     |               URL                |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------:|:------------------:|:----:|:-----------:|:---------:|:----------:|:--------------------------------:|
| Yang, John, et al. "Swe-agent: Agent-computer interfaces enable automated software engineering." arXiv preprint arXiv:2405.15793 (2024).                                    |          SWE-Agent          |    NeurIPS 2023    | 2024 |   @Agent    |    23     | 3.5-S-0620 | https://arxiv.org/abs/2405.15793 |
| Zhang, Yuntong, et al. "Autocoderover: Autonomous program improvement." Proceedings of the 33rd ACM SIGSOFT International Symposium on Software Testing and Analysis. 2024. |        AutoCodeRover        |     ISSTA 2024     | 2024 |   @Agent    |    19     |  4o-0513   | https://arxiv.org/abs/2404.05427 |
| Chen, Dong, et al. "CodeR: Issue Resolving with Multi-Agent and Task Graphs." arXiv preprint arXiv:2406.01304 (2024).                                                       |            CodeR            |       Arxiv        | 2024 |   @Agent    |   28.33   |   4-1106   | https://arxiv.org/abs/2406.01304 |
| Ma, Yingwei, et al. "How to Understand Whole Software Repository?." arXiv preprint arXiv:2406.01422 (2024).                                                                 |      RepoUnderstander       |       Arxiv        | 2024 |   @Agent    |   21.33   |   4-1106   | https://arxiv.org/abs/2406.01422 |
| Arora, Daman, et al. "MASAI: Modular Architecture for Software-engineering AI Agents." arXiv preprint arXiv:2406.11638 (2024).                                              |            MASAI            |       Arxiv        | 2024 |   @Agent    |   27.33   |  4o-0513   | https://arxiv.org/abs/2406.11638 |
| Xia, Chunqiu Steven, et al. "Agentless: Demystifying llm-based software engineering agents." arXiv preprint arXiv:2407.01489 (2024).                                        |          Agentless          |      FSE 2025      | 2024 | @Agentless  |   40.67   |   3.5-S    | https://arxiv.org/abs/2407.01489 |
| Ruan, Haifeng, Yuntong Zhang, and Abhik Roychoudhury. "Specrover: Code intent extraction via llms." arXiv preprint arXiv:2408.02232 (2024).                                 | SpecRover(AutoCodeRover-v2) |     ICSE 2025      | 2024 |   @Agent    |   30.67   |  4o-0513   | https://arxiv.org/abs/2408.02232 |
| Gautam, Anmol, et al. "SuperCoder2. 0: Technical Report on Exploring the feasibility of LLMs as Autonomous Programmer." arXiv preprint arXiv:2409.11190 (2024).             |         SuperCoder          |       Arxiv        | 2024 |   @Agent    |    34     |  4o-0513   | https://arxiv.org/abs/2409.11190 |
| Phan, Huy Nhat, et al. "Hyperagent: Generalist software engineering agents to solve coding tasks at scale." arXiv preprint arXiv:2409.16299 (2024).                         |         HyperAgent          |       Arxiv        | 2024 |   @Agent    |   25.33   |  4o-0513   | https://arxiv.org/abs/2409.16299 |
| Ouyang, Siru, et al. "RepoGraph: Enhancing AI Software Engineering with Repository-level Code Graph." arXiv preprint arXiv:2410.14684 (2024).                               |          RepoGraph          |     ICLR 2025      | 2024 | @Agentless  |   29.67   |  4o-0513   | https://arxiv.org/abs/2410.14684 |
| Antoniades, Antonis, et al. "SWE-Search: Enhancing Software Agents with Monte Carlo Tree Search and Iterative Refinement." arXiv preprint arXiv:2410.20285 (2024).          |         SWE-Search          |     ICLR 2025      | 2024 |   @Agent    |    31     |  4o-0513   | https://arxiv.org/abs/2410.20285 |
| Ma, Yingwei, et al. "Lingma SWE-GPT: An Open Development-Process-Centric Language Model for Automated Software Improvement." arXiv preprint arXiv:2411.00622 (2024).        |       Lingma SWE-GPT        |       Arxiv        | 2024 | @Fine-Tuned |    22     |  4o-0513   | https://arxiv.org/abs/2411.00622 |
| Lei, Bin, et al. "Infant Agent: A Tool-Integrated, Logic-Driven Agent with Cost-Effective API Usage." arXiv preprint arXiv:2411.01114 (2024).                               |        Infant Agent         |       Arxiv        | 2024 |   @Agent    |    30     |  4o-0513   | https://arxiv.org/abs/2411.01114 |
| Liu, Yizhou, et al. "MarsCode Agent: AI-native Automated Bug Fixing." arXiv preprint arXiv:2409.00899 (2024).                                                               |       MarsCode Agent        |       Arxiv        | 2024 |   @Agent    |   39.33   |  4o-0513   | https://arxiv.org/abs/2409.00899 |
| Wang, Xingyao, et al. "OpenHands: An Open Platform for AI Software Developers as Generalist Agents." arXiv preprint arXiv:2407.16741 (2024).                                |          OpenHands          |     ICLR 2025      | 2024 |   @Agent    |   41.67   |   3.5-S    | https://arxiv.org/abs/2407.16741 |
