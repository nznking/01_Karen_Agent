# Contrarian Chain of Thought (COT) Analysis

This project explores the effectiveness of incorporating a contrarian perspective into the Chain of Thought (COT) reasoning process for large language models. We compare the performance of standard COT and contrarian-enhanced COT across different AI models and question types.

## Project Overview

The main script (`cot_comparison.py`) does the following:

1. Implements standard and contrarian COT approaches
2. Compares performance across three models: GPT-3.5-turbo, GPT-4, and GPT-4-0613
3. Tests these approaches on four questions
4. Scores the outputs based on complexity, diversity, and insightfulness
5. Visualizes the results for easy comparison

### Key Findings

1. The contrarian COT approach generally improved scores across most scenarios, with some exceptions.
2. GPT-3.5-turbo showed consistent improvement with the contrarian approach across all question types.
3. GPT-4 and GPT-4o showed mixed results, with significant improvements in some cases and slight decreases in others.
4. The most substantial improvements were seen in the more complex and ambiguous questions, particularly for GPT-4 models.
5. Interestingly, GPT-4o showed the highest variance in performance across different question types.

These results suggest that the effectiveness of the contrarian COT approach may depend on both the model used and the nature of the question being addressed. Further research is needed to understand the factors influencing these variations in performance.

## Usage

1. Set your OpenAI API key in a `.env` file or as an environment variable.
2. Run the main script:

```
python cot_comparison.py
```

## Related Research

This project draws inspiration from recent advancements in AI reasoning and self-critique mechanisms. Here are some relevant papers:

1. Wei, J., Wang, X., Schuurmans, D., Bosma, M., Ichter, B., Xia, F., Chi, E., Le, Q., & Zhou, D. (2022). Chain-of-Thought Prompting Elicits Reasoning in Large Language Models. arXiv preprint arXiv:2201.11903. https://arxiv.org/abs/2201.11903

2. Shinn, N., Hewitt, L., Lim, J., Monath, N., Bras, R.L., & Gajos, K.Z. (2023). Reflexion: an autonomous agent with dynamic memory and self-reflection. arXiv preprint arXiv:2303.11366. https://arxiv.org/abs/2303.11366

3. Bai, Y., Kadavath, S., Kundu, S., Askell, A., Kernion, J., Jones, A., Chen, A., Goldie, A., Mirhoseini, A., McKee, K., Olsson, C., Hernandez, D., Drain, D., Ganguli, D., Perez, E., Kerr, J., Tran-Johnson, J., Ladish, J., Landau, J., ... Kaplan, J. (2022). Constitutional AI: Harmlessness from AI Feedback. arXiv preprint arXiv:2212.08073. https://arxiv.org/abs/2212.08073

4. Perez, E., Huang, S., Song, F., Cai, T., Ring, R., Astle, J., Gao, J., Yilmaz, G., Banino, A., Mordatch, I., & Killoran, N. (2022). Red Teaming Language Models with Language Models. arXiv preprint arXiv:2202.03286. https://arxiv.org/abs/2202.03286

5. Haoxiang, S., Yuan, W., Zheng, R., Yiquan, W., Liu, Y., & Yanghua, X. (2023). Debate Dynamics of GPT-3.5 and GPT-4: An In-depth Exploration of AI Debating AI. arXiv preprint arXiv:2304.05398. https://arxiv.org/abs/2304.05398

## Contributing

We welcome contributions to this project! Please feel free to submit issues, fork the repository and send pull requests!

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.