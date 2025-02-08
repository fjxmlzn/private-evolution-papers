# Private Evolution Papers and Code Repositories

[Private Evolution (PE)](https://arxiv.org/abs/2305.15560) is a training-free algorithm for generating differentially private (DP) synthetic data using foundation models. Unlike traditional methods that require DP fine-tuning of a pre-trained generative model:

* __PE requires no training__ — it only utilizes the __inference APIs__ of models. This allows PE to take advantage of cutting-edge API-based foundation models like GPT-4.
* PE can even __match or outperform state-of-the-art__ training-based methods in balancing data quality with DP guarantees.

This repository collects papers and code repositories related to PE. If you'd like to add your paper and/or code repositories to the list, feel free to __submit a pull request__ or __open an issue__.


| <sub>Title</sub>                                                                                   | <sub>Year</sub> | <sub>Venue</sub>                                                                           | <sub>Name</sub>                   | <sub>Summary</sub>                           | <sub>Links</sub>                                                                                                                                                                         | <sub>Organizations</sub>                                                                                             | <sub>Authors</sub>                                                                                                                                                     |
|----------------------------------------------------------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------|-----------------------------------|----------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <sub>Differentially Private Synthetic Data via Foundation Model APIs 1: Images</sub>               | <sub>2023</sub> | <sub>ICLR 2024, NeurIPS Workshop 2023 __(Oral)__</sub>                                     | <sub>Private Evolution (PE)</sub> | <sub>PE for images</sub>                     | <sub>[[arxiv]](https://arxiv.org/abs/2305.15560) [[code (Private Evolution library)]](https://github.com/microsoft/DPSDA)</sub>                                                          | <sub>MSR</sub>                                                                                                       | <sub>Zinan Lin, Sivakanth Gopi, Janardhan Kulkarni, Harsha Nori, Sergey Yekhanin</sub>                                                                                 |
| <sub>Differentially Private Synthetic Data via Foundation Model APIs 2: Text</sub>                 | <sub>2024</sub> | <sub>ICML 2024 __(Spotlight)__, ICLR Workshop 2024</sub>                                   | <sub>Aug-PE</sub>                 | <sub>PE for text</sub>                       | <sub>[[arxiv]](https://arxiv.org/abs/2403.01749) [[code (original)]](https://github.com/AI-secure/aug-pe) [[code (Private Evolution library)]](https://github.com/microsoft/DPSDA)</sub> | <sub>MSR, UIUC, UChicago</sub>                                                                                       | <sub>Chulin Xie, Zinan Lin, Arturs Backurs, Sivakanth Gopi, Da Yu, Huseyin Inan, Harsha Nori, Haotian Jiang, Huishuai Zhang, Yin Tat Lee, Bo Li, Sergey Yekhanin</sub> |
| <sub>PrE-Text: Training Language Models on Private Federated Data in the Age of LLMs</sub>         | <sub>2024</sub> | <sub>ICML 2024 __(Oral)__, ICLR Workshop 2024 __(Honorable Mention for Best Paper)__</sub> | <sub>PrE-Text</sub>               | <sub>PE for text in federated learning</sub> | <sub>[[arxiv]](https://arxiv.org/pdf/2406.02958) [[code]](https://github.com/houcharlie/PrE-Text)</sub>                                                                                  | <sub>Meta, CMU</sub>                                                                                                 | <sub>Charlie Hou, Akshat Shrivastava, Hongyuan Zhan, Rylan Conway, Trang Le, Adithya Sagar, Giulia Fanti, Daniel Lazar</sub>                                           |
| <sub>CoAutoGen: Cloud-Edge Collaboration Platform for Automated Synthetic Dataset Generation</sub> | <sub>2024</sub> | <sub>-</sub>                                                                               | <sub>CoAutoGen</sub>              | <sub>PE with cloud-edge collaboration</sub>  | <sub>[[code]](https://github.com/TsingZ0/CoAutoGen)</sub>                                                                                                                                | <sub>Shanghai Jiao Tong University</sub>                                                                             | <sub>Jianqing Zhang</sub>                                                                                                                                              |
| <sub>Contrastive Private Data Synthesis via Weighted Multi-PLM Fusion</sub>                        | <sub>2025</sub> | <sub>-</sub>                                                                               | <sub>WASP</sub>                   | <sub>PE with multiple LLMs</sub>             | <sub>[[arxiv]](https://arxiv.org/abs/2502.00245) [[code]](https://anonymous.4open.science/r/WASP)</sub>                                                                                  | <sub>Tsinghua University, Shanghai Jiao Tong University, Harbin Institute of Technology, AsiaInfo Technologies</sub> | <sub>Tianyuan Zou, Yang Liu, Peng Li, Yufei Xiong, Jianqing Zhang, Jingjing Liu, Xiaozhou Ye, Ye Ouyang, Ya-Qin Zhang</sub>                                            |
