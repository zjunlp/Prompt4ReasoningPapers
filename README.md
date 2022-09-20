# Pretrained Language Models Reasoning Papers

Recently, **chain-of-thought** proposed by Google in the paper ***Chain of Thought Prompting Elicits Reasoning in Large Language Models*** has lead a wave of performing reasoning tasks with pretrained language models. We summarize this by listing the related tasks, datasets and the latest papers.

[TOC]

## Tasks and Datasets

BIG-bench

- **Arithmetic Reasoning**: [GSM8K](https://arxiv.org/abs/2110.14168), [SVAMP](https://aclanthology.org/2021.naacl-main.168.pdf), [ASDiv](https://aclanthology.org/2020.acl-main.92/), [AQuA-RAT](https://aclanthology.org/P17-1015/), [MAWPS](https://aclanthology.org/N16-1136/), [AddSub](https://aclanthology.org/D14-1058/), [MultiArith](https://aclanthology.org/D15-1202/), [SingleEq](https://aclanthology.org/Q15-1042/)
- **Commonsense Reasoning**: [CommonsenseQA](https://aclanthology.org/N19-1421/), [StrategyQA](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00370/100680/Did-Aristotle-Use-a-Laptop-A-Question-Answering), [ARC](https://arxiv.org/abs/1803.05457) [SayCan](https://arxiv.org/abs/2204.01691), [SCAN](http://proceedings.mlr.press/v80/lake18a.html)
- **Symbolic Reasoning**: [Last Letter Concatenation](https://arxiv.org/pdf/2201.11903.pdf), [Coin Flip](https://arxiv.org/pdf/2201.11903.pdf)
- **Logical Reasoning**: [ProofWriter](https://arxiv.org/abs/2207.05221), [EntailmentBank](https://aclanthology.org/2021.emnlp-main.585/), [RuleTaker](https://www.ijcai.org/proceedings/2020/537)
- **Inductive Reasoning**: [CLUTRR](https://aclanthology.org/D19-1458/)
- **Question Answering**: [BoolQA](https://aclanthology.org/N19-1300/), [HotpotQA](https://aclanthology.org/D18-1259/), [OpenBookQA](https://aclanthology.org/D18-1260/)
- **Natural Language Inference**: [ANLI](https://aclanthology.org/2020.acl-main.441/), [e-SNLI](https://proceedings.neurips.cc/paper/2018/file/4c7a167bb329bd92580a99ce422d6fa6-Paper.pdf), [MNLI](https://aclanthology.org/N18-1101/), [RTE](https://tac.nist.gov/publications/2009/additional.papers/RTE5_overview.proceedings.pdf)

## Papers

1. **Chain of Thought Prompting Elicits Reasoning in Large Language Models.**

   *Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed H. Chi, Quoc V. Le, Denny Zhou*. [[pdf](https://arxiv.org/pdf/2201.11903.pdf)], 2022.1

2. **Self-Consistency Improves Chain of Thought Reasoning in Language Models.**

   *Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed H. Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou*. [[pdf](https://arxiv.org/pdf/2203.11171.pdf)], 2022.3

3. **STaR: Self-Taught Reasoner Bootstrapping Reasoning With Reasoning.**

   *Eric Zelikman, Yuhuai Wu, Noah D. Goodman*. [[pdf](https://arxiv.org/pdf/2203.14465v1.pdf)], 2022.3

4. **Can language models learn from explanations in context?**

   *Andrew K. Lampinen, Ishita Dasgupta, Stephanie C. Y. Chan, Kory Matthewson, Michael Henry Tessler, Antonia Creswell, James L. McClelland, Jane X. Wang, Felix Hill*. [[pdf](https://arxiv.org/pdf/2204.02329.pdf)], 2022.4

5. **The Unreliability of Explanations in Few-Shot In-Context Learning.**

   *Xi Ye, Greg Durrett*. [[pdf](https://arxiv.org/pdf/2205.03401.pdf)], 2022.5

6. **Large Language Models are Zero-Shot Reasoners.**

   *Takeshi Kojima, Shixiang Shane Gu, Machel Reid, Yutaka Matsuo, Yusuke Iwasawa*. [[pdf](https://arxiv.org/pdf/2205.11916v2.pdf)], 2022.5

7. **Least-to-Most Prompting Enables Complex Reasoning in Large Language Models.**

   *Denny Zhou, Nathanael Schärli, Le Hou, Jason Wei, Nathan Scales, Xuezhi Wang, Dale Schuurmans, Olivier Bousquet, Quoc Le, Ed Chi*. [[pdf](https://arxiv.org/pdf/2205.10625.pdf)], 2022.5

8. **Generating Natural Language Proofs with Verifier-Guided Search.**

   *Kaiyu Yang, Jia Deng, Danqi Chen*. [[pdf](https://arxiv.org/pdf/2205.12443.pdf)], 2022.5

9. **On the Advance of Making Language Models Better Reasoners.**

   *Yifei Li, Zeqi Lin, Shizhuo Zhang, Qiang Fu, Bei Chen, Jian-Guang Lou, Weizhu Chen*. [[pdf](https://arxiv.org/pdf/2206.02336.pdf)], 2022.6

10. **Emergent Abilities of Large Language Models.**

    *Jason Wei, Yi Tay, Rishi Bommasani, Colin Raffel, Barret Zoph, Sebastian Borgeaud, Dani Yogatama, Maarten Bosma, Denny Zhou, Donald Metzler, Ed H. Chi, Tatsunori Hashimoto, Oriol Vinyals, Percy Liang, Jeff Dean, William Fedus*. [[pdf](https://arxiv.org/pdf/2206.07682.pdf)], 2022.6

11. **Solving Quantitative Reasoning Problems with Language Models.**

    *Aitor Lewkowycz, Anders Andreassen, David Dohan, Ethan Dyer, Henryk Michalewski, Vinay Ramasesh, Ambrose Slone, Cem Anil, Imanol Schlag, Theo Gutman-Solo, Yuhuai Wu, Behnam Neyshabur, Guy Gur-Ari, Vedant Misra*. [[pdf](https://arxiv.org/pdf/2206.14858.pdf)], 2022.6

12. **A Dataset and Benchmark for Automatically Answering and Generating Machine Learning Final Exams.**

    *Sarah Zhang, Reece Shuttleworth, Derek Austin, Yann Hicke, Leonard Tang, Sathwik Karnik, Darnell Granberry, Iddo Drori*. [[pdf](https://arxiv.org/pdf/2206.05442.pdf)], 2022.6

13. **Rational-Augmented Ensembles in Language Models.**

    *Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Denny Zhou*. [[pdf](https://arxiv.org/pdf/2207.00747.pdf)], 2022.7

14. **Language Model Cascades.**

    *David Dohan, Winnie Xu, Aitor Lewkowycz, Jacob Austin, David Bieber, Raphael Gontijo Lopes, Yuhuai Wu, Henryk Michalewski, Rif A. Saurous, Jascha Sohl-dickstein, Kevin Murphy, Charles Sutton*. [[pdf](https://arxiv.org/pdf/2207.10342.pdf)], 2022.7

15. **Faithful Reasoning Using Large Language Models.**

    *Antonia Creswell, Murray Shanahan*. [[pdf](https://arxiv.org/pdf/2208.14271.pdf)], 2022.8

16. **Psychologically-informed chain-of-thought prompts for metaphor understanding in large language models.**

    *Ben Prystawski, Paul Thibodeau, Noah Goodman*. [[pdf](https://arxiv.org/pdf/2209.08141.pdf)], 2022.9