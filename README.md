# Private Evolution Papers, Code Repositories, and Blogs

### 🔗 [Go to the full paper list](https://zinanlin.me/private-evolution-papers/)

[Private Evolution (PE)](https://arxiv.org/abs/2305.15560) is a training-free algorithm for generating differentially private (DP) synthetic data. Unlike traditional methods that require DP fine-tuning of a pre-trained generative model:

* __PE requires no training__ — it only utilizes the __inference APIs__ of foundation models or non-neural-network data synthesis tools. This allows PE to take advantage of any cutting-edge API-based foundation models (e.g., GPT-4), open-source models (e.g., Stable Diffusion, Llama), or tools (e.g., computer graphics-based image synthesis tools).

* PE can even __match or outperform state-of-the-art__ training-based methods in balancing data quality with DP guarantees in some cases.

Since its introduction, PE has been extended by the community to __various data modalities (images, text, tabular), different environments (federated and centralized), and a range of use cases (both training-free and training-based)__.

**PE has been adopted by some of the largest IT companies such as [Microsoft](https://www.microsoft.com/en-us/research/blog/the-crossroads-of-innovation-and-privacy-private-synthetic-data-for-generative-ai/) and [Apple](https://machinelearning.apple.com/research/differential-privacy-aggregate-trends).**

This repository collects papers, code repositories, and blogs related to PE. If you'd like to add your work to the list, feel free to __submit a pull request__, __open an issue__, or __contact me__ (zinanlin AT microsoft.com). Please star the repo to get the latest update!

> 🚀 **Please visit the full paper list at:**  
> 🔗 [https://zinanlin.me/private-evolution-papers/](https://zinanlin.me/private-evolution-papers/)

## News  
* `6/17/2025`: As the list has grown rapidly, maintaining it in the README has become difficult to navigate. I've moved the paper list to the [GitHub Page](https://zinanlin.me/private-evolution-papers/) for improved readability and enhanced features such as filtering and exporting. The source data remains in [this CSV file](https://github.com/fjxmlzn/private-evolution-papers/blob/main/papers.csv) within the repository, so we can continue tracking changes and managing updates via GitHub issues and pull requests.
