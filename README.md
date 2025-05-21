# Strategic AI: Bridging Game Theory and Multi-Agent Systems via Autoformalization

<p align="center">
  <img src="assets/banner.png" width="80%">
</p>

## 🧠 Tutorial Outline

### 🔍 Overview
  - Explores how game theory and multi-agent systems (MAS) can model strategic interactions among agents.
  - Emphasizes recent AI advancements, especially Large Language Models (LLMs), for integrating these fields.
  - Introduces autoformalization techniques and game-theoretic concepts for negotiation, cooperation, and competition.
  - It is a **🕒 half-day tutorial**, split into four parts.

**📘 Materials:**
- <a href="/assets/Strategic_AI_AAMAS__25.pdf" target="_blank">Tutorial slides</a>

**🧰 Tools:**
  - Python 3, Jupyter Notebook, SWI-Prolog for running the examples locally (please follow the [installation instructions](https://github.com/dicelab-rhul/GAMA?tab=readme-ov-file#installation)), <br>
    or     
  - Google Colab for cloud-based execution: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dicelab-rhul/GAMA/blob/main/tutorial/Tutorial.ipynb)

---

### 🎲 Part 1: Introduction to Game Theory and MAS (50 mins)
  - **🚀 Motivation and Relevance**
    - Strategic interactions in AI applications: economics, robotics, autonomous vehicles, auctions, etc.
    - Challenges: non-deterministic environments, bounded rationality.
  - **📘 Game Theory Foundations**
    - Definitions: games, players, strategies, payoffs, equilibria.
    - Game types: cooperative vs. non-cooperative, symmetric vs. asymmetric, zero-sum vs. non-zero-sum.
    - Key concepts: dominance, Pareto optimality, Nash Equilibrium, social welfare.
    - Example games:
      - 🧩 Prisoner’s Dilemma
      - 🔄 Matching Pennies
      - 🤝 Public Goods Game
    - 🎮 Interactive simulations.
  - **🤖 Multi-Agent Systems (MAS)**
    - MAS principles: autonomy, social ability, learning.
    - Agent types: reactive, deliberative, hybrid.
    - 🗣️ Coordination and communication for conflict resolution and goal achievement.
    - Applications:
      - 🚗 Autonomous vehicle traffic management
      - 🎯 Multi-agent reinforcement learning

---

### 🗂️ Part 2: The Game Description Language (GDL) (40 mins)
  - **📜 Introduction to GDL**
    - Origins and role in general game-playing AI.
    - Support for games without prior knowledge.
  - **⏳ Temporal Extensions**
    - Represent dynamic game states over time.
    - Relationship to other action formalisms.
  - **⚙️ Compiling GDLs**
    - Use of Situation Calculus and Event Calculus.
    - Reasoning about legality and effects of actions.
    - Challenges like the inferential frame problem and efficiency improvements.
  - **🎮 Applications of GDL**
    - Game generation.
    - Representing more complex agent interactions.
    - 🔮 Future integration with machine learning.

---

### 🤖 Part 3: Autoformalization, Simulation Framework, and Case Studies (35 mins)
  - **📝 Autoformalization with LLMs**
    - Translating natural language to logic/formal systems.
    - Enhances reasoning and scalability in AI systems.
    - Examples: Answer Set Programming, Temporal Logic, Deductive Reasoning.
  - **🔄 Natural Language to Situation Calculus**
    - Framework for translating interaction scenarios.
    - Integrates with formal solvers for logical reasoning.
  - **🛠️ Simulation Framework**
    - Modular agents capable of autoformalization and decision-making.
    - Python interface handles environment interactions and solver integration.
  - **📊 Case Studies**
    - Examples for 2×2 simultaneous-move games.
    - Showcases applications of the framework.

---

### 🧩 Part 4: Belief Hierarchies and Theory of Mind (35 mins)
  - **🧠 Theory of Mind (ToM)**
    - Modeling agents that reason about others' mental states.
    - ToM as a benchmark for human-like reasoning.
  - **⚠️ Limitations of Standard Game Theory**
    - Unrealistic assumptions: common rationality, shared payoffs.
    - Extensions: player types, belief hierarchies.
  - **🎭 Hypergame Theory**
    - Captures misaligned perceptions and beliefs.
    - Models recursive reasoning ("beliefs about beliefs").
    - 🧪 Demonstration via multi-agent simulation platform.
   
---


## 📚 Bibliography

[1] Chen, Y., Gandhi, R., Zhang, Y., & Fan, C. (2023). *NL2TL: Transforming Natural Languages to Temporal Logics using Large Language Models*. In *Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing*, 15880–15903.

[2] Cosler, M., Hahn, C., Mendoza, D., Schmitt, F., & Trippel, C. (2023). *nl2spec: interactively translating unstructured natural language to temporal logics with large language models*. In *International Conference on Computer Aided Verification*, 383–396. Springer.

[3] Ebner, M., Levine, J., Lucas, S. M., Schaul, T., Thompson, T., & Togelius, J. (2013). *Towards a video game description language*. Dagstuhl Publishing.

[4] Feng, J., Xu, R., Hao, J., Sharma, H., Shen, Y., Zhao, D., & Chen, W. (2023). *Language models can be logical solvers*. arXiv preprint [arXiv:2311.06158](https://arxiv.org/abs/2311.06158).

[5] Harsanyi, J. (1967–1968). *Games with Incomplete Information Played by 'Bayesian' Players, Parts I–III*. Management Science, 14, 159–182, 320–334, 486–502.

[6] Love, N., Genesereth, M., & Hinrichs, T. (2006). *General Game Playing: Game Description Language Specification*. Technical Report, Stanford University.

[7] McCarthy, J., & Hayes, P. J. (1981). *Some Philosophical Problems from the Standpoint of Artificial Intelligence*. In B. L. Webber & N. J. Nilsson (Eds.), *Readings in Artificial Intelligence*, 431–450. Morgan Kaufmann.

[8] Mensfelt, A., Stathis, K., & Tencsenyi, V. (2024). *GAMA: Generative Agents for Multi-Agent Autoformalization*. arXiv preprint [arXiv:2412.08805](https://arxiv.org/abs/2412.08805).

[9] Mensfelt, A., Stathis, K., & Tencsenyi, V. (2024). *Autoformalization of Game Descriptions Using Large Language Models*. In *1st International Workshop on Next-Generation Language Models for Knowledge Representation and Reasoning*, Hanoi, Vietnam. [arXiv:2409.12300](https://arxiv.org/abs/2409.12300).

[10] Mensfelt, A., Stathis, K., & Trencsenyi, V. (2024). *Logic-Enhanced Language Model Agents for Trustworthy Social Simulations*. arXiv preprint [arXiv:2408.16081](https://arxiv.org/abs/2408.16081).

[11] Nash, J. F. (1950). *Equilibrium Points in N-Person Games*. Proceedings of the National Academy of Sciences of the United States of America, 36(1), 48–49.

[12] Pan, L., Albalak, A., Wang, X., & Wang, W. (2023). *Logic-LM: Empowering Large Language Models with Symbolic Solvers for Faithful Logical Reasoning*. In *Findings of the Association for Computational Linguistics: EMNLP 2023*, 3806–3824.

[13] Premack, D., & Woodruff, G. (1978). *Does the chimpanzee have a theory of mind?* Behavioral and Brain Sciences, 1(4), 515–526. [https://doi.org/10.1017/S0140525X00076512](https://doi.org/10.1017/S0140525X00076512)

[14] Rasmusen, E. (2006). *Games and information: An introduction to game theory* (4th ed.). Blackwell, Oxford.

[15] Russell, S. J., & Norvig, P. (2020). *Artificial Intelligence: A Modern Approach* (4th ed.). Pearson, Upper Saddle River, New Jersey.

[16] Sasaki, Y. (2021). *Multi-agent Decision System*. In G. S. Metcalf, K. Kijima, & H. Deguchi (Eds.), *Handbook of Systems Sciences* (pp. 337–352). Springer Singapore. [https://doi.org/10.1007/978-981-15-0720-5_49](https://doi.org/10.1007/978-981-15-0720-5_49)

[17] Shanahan, M. (1999). *The Event Calculus Explained*. In M. J. Wooldridge & M. Veloso (Eds.), *Artificial Intelligence Today: Recent Trends and Developments*, 409–430. Springer Berlin Heidelberg.

[18] Shoham, Y., & Leyton-Brown, K. (2008). *Multiagent Systems: Algorithmic, Game-Theoretic, and Logical Foundations*. Cambridge University Press, USA.

[19] Thielscher, M. (2010). *A General Game Description Language for Incomplete Information Games*. In *Proceedings of AAAI'10*, 994–999.

[20] Thielscher, M. (2011). *The General Game Playing Description Language Is Universal*. In *Proceedings of the 22nd International Joint Conference on Artificial Intelligence (IJCAI)*, 1107–1112.

[21] Thielscher, M. (2011). *Translating General Game Descriptions into an Action Language*. In *Logic Programming, Knowledge Representation, and Nonmonotonic Reasoning*, Lecture Notes in Computer Science, 6565, 300–314. Springer.

[22] Wang, M., Hipel, K. W., & Fraser, N. M. (1988). *Modeling misperceptions in games*. Behavioral Science, 33(3), 207–223.

[23] Wooldridge, M. (2009). *An Introduction to Multiagent Systems* (2nd ed.). Wiley Publishing.

[24] Wu, Y., Jiang, A. Q., Li, W., Rabe, M., Staats, C., Jamnik, M., & Szegedy, C. (2022). *Autoformalization with large language models*. Advances in Neural Information Processing Systems, 35, 32353–32368.

[25] Yang, Z., Ishay, A., & Lee, J. (2023). *Coupling large language models with logic programming for robust and general reasoning from text*. arXiv preprint [arXiv:2307.07696](https://arxiv.org/abs/2307.07696).
