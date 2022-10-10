# Pretrained Language Models Reasoning Papers

![](https://img.shields.io/github/last-commit/zjunlp/PLMReasonPapers?color=green) 
![](https://img.shields.io/badge/PaperNumber-45-brightgreen)

Recently, **chain-of-thought** proposed by Google in the paper ***Chain of Thought Prompting Elicits Reasoning in Large Language Models*** has lead a wave of performing reasoning tasks with pretrained language models. We summarize this by listing the related tasks, datasets and the latest papers.

## Tasks and Datasets

- **Arithmetic Reasoning**: [GSM8K](https://arxiv.org/abs/2110.14168), [SVAMP](https://aclanthology.org/2021.naacl-main.168), [ASDiv](https://aclanthology.org/2020.acl-main.92/), [AQuA-RAT](https://aclanthology.org/P17-1015/), [MAWPS](https://aclanthology.org/N16-1136/), [AddSub](https://aclanthology.org/D14-1058/), [MultiArith](https://aclanthology.org/D15-1202/), [SingleEq](https://aclanthology.org/Q15-1042/)
- **Commonsense Reasoning**: [CommonsenseQA](https://aclanthology.org/N19-1421/), [StrategyQA](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00370/100680/Did-Aristotle-Use-a-Laptop-A-Question-Answering), [ARC](https://arxiv.org/abs/1803.05457) [SayCan](https://arxiv.org/abs/2204.01691), [SCAN](http://proceedings.mlr.press/v80/lake18a.html)
- **Symbolic Reasoning**: [Last Letter Concatenation](https://arxiv.org/abs/2201.11903), [Coin Flip](https://arxiv.org/abs/2201.11903)
- **Logical Reasoning**: [ProofWriter](https://arxiv.org/abs/2207.05221), [EntailmentBank](https://aclanthology.org/2021.emnlp-main.585/), [RuleTaker](https://www.ijcai.org/proceedings/2020/537)
- **Inductive Reasoning**: [CLUTRR](https://aclanthology.org/D19-1458/)
- **Question Answering**: [BoolQA](https://aclanthology.org/N19-1300/), [HotpotQA](https://aclanthology.org/D18-1259/), [OpenBookQA](https://aclanthology.org/D18-1260/)
- **Natural Language Inference**: [ANLI](https://aclanthology.org/2020.acl-main.441/), [e-SNLI](https://proceedings.neurips.cc/paper/2018/file/4c7a167bb329bd92580a99ce422d6fa6-Paper), [MNLI](https://aclanthology.org/N18-1101/), [RTE](https://tac.nist.gov/publications/2009/additional.papers/RTE5_overview.proceedings)
- **A Challenge Large Language Model Benchmarks**: [BIG-bench](https://doi.org/10.48550/arXiv.2206.04615)
- **Science Question Answering (Multimodal)**: [SCIENCEQA](https://scienceqa.github.io/)

## Papers

1. **Transformers as Soft Reasoners over Language.**

    *Peter Clark, Oyvind Tafjord, Kyle Richardson*. [[abs](https://arxiv.org/abs/2002.05867)], 2020.2

2. **Logic-Guided Data Augmentation and Regularization for Consistent Question Answering.**

     *Akari Asai, Hannaneh Hajishirzi*. [[abs](https://arxiv.org/abs/2004.10157)], 2020.4

3. **Injecting Numerical Reasoning Skills into Language Models.**

     *Mor Geva, Ankit Gupta, Jonathan Berant*. [[abs](https://arxiv.org/abs/2004.04487)], 2020.4

4. **PRover: Proof Generation for Interpretable Reasoning over Rules.**

    *Swarnadeep Saha, Sayan Ghosh, Shashank Srivastava, Mohit Bansal*. [[abs](https://arxiv.org/abs/2010.02830)], 2020.10

5. **ProofWriter: Generating Implications, Proofs, and Abductive Statements over Natural Language.**

    *Oyvind Tafjord, Bhavana Dalvi Mishra, Peter Clark*. [[abs](https://arxiv.org/abs/2012.13048)], 2020.12

6. **Explaining Answers with Entailment Trees.**

    *Bhavana Dalvi, Peter Jansen, Oyvind Tafjord, Zhengnan Xie, Hannah Smith, Leighanna Pipatanangkura, Peter Clark*. [[abs](https://arxiv.org/abs/2104.08661)], 2021.4

7. **NaturalProofs: Mathematical Theorem Proving in Natural Language.**

    *Sean Welleck, Jiacheng Liu, Ronan Le Bras, Hannaneh Hajishirzi, Yejin Choi, Kyunghyun Cho*. [[abs](https://arxiv.org/abs/2104.01112)], 2021.4

8. **Logic-Driven Context Extension and Data Augmentation for Logical Reasoning of Text.**

     *Siyuan Wang, Wanjun Zhong, Duyu Tang, Zhongyu Wei, Zhihao Fan, Daxin Jiang, Ming Zhou, Nan Duan*. [[abs](https://arxiv.org/abs/2105.03659)], 2021.5

9. **multiPRover: Generating Multiple Proofs for Improved Interpretability in Rule Reasoning.**

    *Swarnadeep Saha, Prateek Yadav, Mohit Bansal*. [[abs](https://arxiv.org/abs/2106.01354)], 2021.6

10. **Turning Tables: Generating Examples from Semi-structured Tables for Endowing Language Models with Reasoning Skills.**

     *Ori Yoran, Alon Talmor, Jonathan Berant.*  [[abs](https://arxiv.org/abs/2107.07261)], 2021.7

11. **ReasonBERT: Pre-trained to Reason with Distant Supervision.**

     *Xiang Deng, Yu Su, Alyssa Lees, You Wu, Cong Yu, Huan Sun*. [[abs](https://arxiv.org/abs/2109.04912)], 2021.9

12. **Generate & Rank: A Multi-task Framework for Math Word Problems.**

     *Jianhao Shen, Yichun Yin, Lin Li, Lifeng Shang, Xin Jiang, Ming Zhang, Qun Liu*. [[abs](https://arxiv.org/abs/2109.03034)], 2021.9

13. **Generated Knowledge Prompting for Commonsense Reasoning.**

     *Jiacheng Liu, Alisa Liu, Ximing Lu, Sean Welleck, Peter West, Ronan Le Bras, Yejin Choi, Hannaneh Hajishirzi*. [[abs](https://arxiv.org/abs/2110.08387)], 2021.10

14. **Training Verifiers to Solve Math Word Problems.**

     *Karl Cobbe, Vineet Kosaraju, Mohammad Bavarian, Mark Chen, Heewoo Jun, Lukasz Kaiser, Matthias Plappert, Jerry Tworek, Jacob Hilton, Reiichiro Nakano, Christopher Hesse, John Schulman*. [[abs](https://arxiv.org/abs/2110.14168)], 2021.10

15. **Chain of Thought Prompting Elicits Reasoning in Large Language Models.**

    *Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed H. Chi, Quoc V. Le, Denny Zhou*. [[abs](https://arxiv.org/abs/2201.11903)], 2022.1

16. **Natural Language Deduction through Search over Statement Compositions.**

    *Kaj Bostrom, Zayne Sprague, Swarat Chaudhuri, Greg Durrett*. [[abs](https://arxiv.org/abs/2201.06028)], 2022.1

17. **Reasoning Like Program Executors.**

     *Xinyu Pi, Qian Liu, Bei Chen, Morteza Ziyadi, Zeqi Lin, Yan Gao, Qiang Fu, Jian-Guang Lou, Weizhu Chen*. [[abs](https://arxiv.org/abs/2201.11473)], 2022.1

18. **Self-Consistency Improves Chain of Thought Reasoning in Language Models.**

    *Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed H. Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou*. [[abs](https://arxiv.org/abs/2203.11171)], 2022.3

19. **STaR: Bootstrapping Reasoning With Reasoning.**

     *Eric Zelikman, Yuhuai Wu, Noah D. Goodman*. [[abs](https://arxiv.org/abs/2203.14465)], 2022.3

20. **FaiRR: Faithful and Robust Deductive Reasoning over Natural Language.**

     *Soumya Sanyal, Harman Singh, Xiang Ren*. [[abs](https://arxiv.org/abs/2203.10261)], 2022.3

21. **Can language models learn from explanations in context?**

     *Andrew K. Lampinen, Ishita Dasgupta, Stephanie C. Y. Chan, Kory Matthewson, Michael Henry Tessler, Antonia Creswell, James L. McClelland, Jane X. Wang, Felix Hill*. [[abs](https://arxiv.org/abs/2204.02329)], 2022.4

22. **Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language.**

     *Andy Zeng, Maria Attarian, Brian Ichter, Krzysztof Choromanski, Adrian Wong, Stefan Welker, Federico Tombari, Aveek Purohit, Michael Ryoo, Vikas Sindhwani, Johnny Lee, Vincent Vanhoucke, Pete Florence*. [[abs](https://arxiv.org/abs/2204.00598)], 2022.4

23. **Towards Teachable Reasoning Systems.**

     *Bhavana Dalvi, Oyvind Tafjord, Peter Clark*. [[abs](https://arxiv.org/abs/2204.13074)], 2022.4

24. **The Unreliability of Explanations in Few-Shot In-Context Learning.**

     *Xi Ye, Greg Durrett*. [[abs](https://arxiv.org/abs/2205.03401)], 2022.5

25. **Large Language Models are Zero-Shot Reasoners.**

     *Takeshi Kojima, Shixiang Shane Gu, Machel Reid, Yutaka Matsuo, Yusuke Iwasawa*. [[abs](https://arxiv.org/abs/2205.11916)], 2022.5

26. **Least-to-Most Prompting Enables Complex Reasoning in Large Language Models.**

     *Denny Zhou, Nathanael Schärli, Le Hou, Jason Wei, Nathan Scales, Xuezhi Wang, Dale Schuurmans, Olivier Bousquet, Quoc Le, Ed Chi*. [[abs](https://arxiv.org/abs/2205.10625)], 2022.5

27. **Selection-Inference: Exploiting Large Language Models for Interpretable Logical Reasoning.**

     *Antonia Creswell, Murray Shanahan, Irina Higgins*. [[abs](https://arxiv.org/abs/2205.09712)], 2022.5

28. **Generating Natural Language Proofs with Verifier-Guided Search.**

     *Kaiyu Yang, Jia Deng, Danqi Chen*. [[abs](https://arxiv.org/abs/2205.12443)], 2022.5

29. **Maieutic Prompting: Logically Consistent Reasoning with Recursive Explanations.**

     *Jaehun Jung, Lianhui Qin, Sean Welleck, Faeze Brahman, Chandra Bhagavatula, Ronan Le Bras, Yejin Choi.* [[abs](https://arxiv.org/abs/2205.11822)], 2022.5

30. **On the Advance of Making Language Models Better Reasoners.**

     *Yifei Li, Zeqi Lin, Shizhuo Zhang, Qiang Fu, Bei Chen, Jian-Guang Lou, Weizhu Chen*. [[abs](https://arxiv.org/abs/2206.02336)], 2022.6

31. **Emergent Abilities of Large Language Models.**

     *Jason Wei, Yi Tay, Rishi Bommasani, Colin Raffel, Barret Zoph, Sebastian Borgeaud, Dani Yogatama, Maarten Bosma, Denny Zhou, Donald Metzler, Ed H. Chi, Tatsunori Hashimoto, Oriol Vinyals, Percy Liang, Jeff Dean, William Fedus*. [[abs](https://arxiv.org/abs/2206.07682)], 2022.6

32. **Solving Quantitative Reasoning Problems with Language Models.**

     *Aitor Lewkowycz, Anders Andreassen, David Dohan, Ethan Dyer, Henryk Michalewski, Vinay Ramasesh, Ambrose Slone, Cem Anil, Imanol Schlag, Theo Gutman-Solo, Yuhuai Wu, Behnam Neyshabur, Guy Gur-Ari, Vedant Misra*. [[abs](https://arxiv.org/abs/2206.14858)], 2022.6

33. **A Dataset and Benchmark for Automatically Answering and Generating Machine Learning Final Exams.**

     *Sarah Zhang, Reece Shuttleworth, Derek Austin, Yann Hicke, Leonard Tang, Sathwik Karnik, Darnell Granberry, Iddo Drori*. [[abs](https://arxiv.org/abs/2206.05442)], 2022.6

34. **Rationale-Augmented Ensembles in Language Models.**

     *Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Denny Zhou*. [[abs](https://arxiv.org/abs/2207.00747)], 2022.7

35. **Language Model Cascades.**

     *David Dohan, Winnie Xu, Aitor Lewkowycz, Jacob Austin, David Bieber, Raphael Gontijo Lopes, Yuhuai Wu, Henryk Michalewski, Rif A. Saurous, Jascha Sohl-dickstein, Kevin Murphy, Charles Sutton*. [[abs](https://arxiv.org/abs/2207.10342)], 2022.7

36. **Language models show human-like content effects on reasoning.**

     *Ishita Dasgupta, Andrew K. Lampinen, Stephanie C. Y. Chan, Antonia Creswell, Dharshan Kumaran, James L. McClelland, Felix Hill.* [[abs](https://arxiv.org/abs/2207.07051)], 2022.7

37. **Faithful Reasoning Using Large Language Models.**

     *Antonia Creswell, Murray Shanahan*. [[abs](https://arxiv.org/abs/2208.14271)], 2022.8

38. **Psychologically-informed chain-of-thought prompts for metaphor understanding in large language models.**

     *Ben Prystawski, Paul Thibodeau, Noah Goodman*. [[abs](https://arxiv.org/abs/2209.08141)], 2022.9

39. **Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering.**

     *Pan Lu, Swaroop Mishra, Tony Xia, Liang Qiu, Kai-Wei Chang, Song-Chun Zhu, Oyvind Tafjord, Peter Clark, Ashwin Kalyan*. [[abs](https://arxiv.org/abs/2209.09513)], 2022.9

40. **Can Large Language Models Truly Understand Prompts? A Case Study with Negated Prompts.**

     *Joel Jang, Seongheyon Ye, Minjoon Seo*. [[abs](https://arxiv.org/abs/2209.12711)], 2022.9

41. **Knowledge Unlearning for Mitigating Privacy Risks in Language Models.**

     *Joel Jang, Dongkeun Yoon, Sohee Yang, Sungmin Cha, Moontae Lee, Lajanugen Logeswaran, Minjoon Seo.* [[abs](https://arxiv.org/abs/2210.01504)], 2022.10

42. **Complexity-based Prompting for Multi-step Reasoning.**

     *Yao Fu, Hao Peng, Ashish Sabharwal, Peter Clark, Tushar Khot*. [[abs](https://arxiv.org/abs/2210.00720)], 2022.10

43. **Language Models are Greedy Reasoners: A Systematic Formal Analysis of Chain-of-thought.**

     *Abulhair Saparov, He He*. [[abs](https://arxiv.org/abs/2210.01240)], 2022.10

44. **Decomposed Prompting: A Modular Approach for Solving Complex Tasks.**

     *Tushar Khot, Harsh Trivedi, Matthew Finlayson, Yao Fu, Kyle Richardson, Peter Clark, Ashish Sabharwal.* [[abs](https://arxiv.org/abs/2210.02406)], 2022.10

45. **Language Models are Multilingual Chain-of-thought Reasoners.**

     *Freda Shi, Mirac Suzgun, Markus Freitag, Xuezhi Wang, Suraj Srivats, Soroush Vosoughi, Hyung Won Chung, Yi Tay, Sebastian Ruder, Denny Zhou, Dipanjan Das, Jason Wei*. [[abs](https://arxiv.org/abs/2210.03057)], 2022.10
