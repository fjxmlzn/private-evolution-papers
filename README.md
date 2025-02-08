# Private Evolution Papers and Code Repositories

[Private Evolution (PE)](https://arxiv.org/abs/2305.15560) is a training-free algorithm for generating differentially private (DP) synthetic data using foundation models. Unlike traditional methods that require DP fine-tuning of a pre-trained generative model:

* __PE requires no training__ — it only utilizes the __inference APIs__ of models. This allows PE to take advantage of cutting-edge API-based foundation models like GPT-4.
* PE can even __match or outperform state-of-the-art__ training-based methods in balancing data quality with DP guarantees.

This repository collects papers and code repositories related to PE. If you'd like to add your paper and/or code repositories to the list, feel free to __submit a pull request__ or __open an issue__.


| Title                                                                                   | Year | Venue                                                                           | Name                   | Summary                           | Links                                                                                                                                                                         | Organizations                                                                                             | Authors                                                                                                                                                     |
|-----------------------------------------------------------------------------------------|------|---------------------------------------------------------------------------------|------------------------|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Differentially Private Synthetic Data via Foundation Model APIs 1: Images               | 2023 | ICLR 2024, NeurIPS Workshop 2023 __(Oral)__                                     | Private Evolution (PE) | PE for images                     | [[arxiv]](https://arxiv.org/abs/2305.15560) <br/><br/> [[code (Private Evolution library)]](https://github.com/microsoft/DPSDA)                                                          | MSR                                                                                                       | Zinan Lin, Sivakanth Gopi, Janardhan Kulkarni, Harsha Nori, Sergey Yekhanin                                                                                 |
| Differentially Private Synthetic Data via Foundation Model APIs 2: Text                 | 2024 | ICML 2024 __(Spotlight)__, ICLR Workshop 2024                                   | Aug-PE                 | PE for text                       | [[arxiv]](https://arxiv.org/abs/2403.01749) <br/><br/>[[code (original)]](https://github.com/AI-secure/aug-pe) <br/><br/>[[code (Private Evolution library)]](https://github.com/microsoft/DPSDA) | MSR, UIUC, UChicago                                                                                       | Chulin Xie, Zinan Lin, Arturs Backurs, Sivakanth Gopi, Da Yu, Huseyin Inan, Harsha Nori, Haotian Jiang, Huishuai Zhang, Yin Tat Lee, Bo Li, Sergey Yekhanin |
| PrE-Text: Training Language Models on Private Federated Data in the Age of LLMs         | 2024 | ICML 2024 __(Oral)__, ICLR Workshop 2024 __(Honorable Mention for Best Paper)__ | PrE-Text               | PE for text in federated learning | [[arxiv]](https://arxiv.org/pdf/2406.02958) <br/><br/>[[code]](https://github.com/houcharlie/PrE-Text)                                                                                  | Meta, CMU                                                                                                 | Charlie Hou, Akshat Shrivastava, Hongyuan Zhan, Rylan Conway, Trang Le, Adithya Sagar, Giulia Fanti, Daniel Lazar                                           |
| CoAutoGen: Cloud-Edge Collaboration Platform for Automated Synthetic Dataset Generation | 2024 | -                                                                               | CoAutoGen              | PE with cloud-edge collaboration  | [[code]](https://github.com/TsingZ0/CoAutoGen)                                                                                                                                | Shanghai Jiao Tong University                                                                             | Jianqing Zhang                                                                                                                                              |
| Contrastive Private Data Synthesis via Weighted Multi-PLM Fusion                        | 2025 | -                                                                               | WASP                   | PE with multiple LLMs             | [[arxiv]](https://arxiv.org/abs/2502.00245) <br/><br/>[[code]](https://anonymous.4open.science/r/WASP)                                                                                  | Tsinghua University, Shanghai Jiao Tong University, Harbin Institute of Technology, AsiaInfo Technologies | Tianyuan Zou, Yang Liu, Peng Li, Yufei Xiong, Jianqing Zhang, Jingjing Liu, Xiaozhou Ye, Ye Ouyang, Ya-Qin Zhang                                            |

