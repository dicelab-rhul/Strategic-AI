# Strategic AI: Bridging Game Theory and Multi-Agent Systems via Autoformalization

## 🧠 Tutorial Outline

### 🔍 Overview
  - Explores how game theory and multi-agent systems (MAS) can model strategic interactions among agents.
  - Emphasizes recent AI advancements, especially Large Language Models (LLMs), for integrating these fields.
  - Introduces autoformalization techniques and game-theoretic concepts for negotiation, cooperation, and competition.
  - It is a **🕒 half-day tutorial**, split into four parts.

---

### 🎲 Part 1: Introduction to Game Theory and MAS (60 mins)
  - **🚀 Motivation and Relevance**
    - Strategic interactions in AI applications: economics, robotics, autonomous vehicles, auctions, etc.
    - Challenges: non-deterministic environments, bounded rationality.
  - **📘 Game Theory Foundations**
    - Definitions: games, players, strategies, payoffs, equilibria.
    - Game types: cooperative vs. non-cooperative, symmetric vs. asymmetric, zero-sum vs. non-zero-sum.
    - Solution concepts: dominance, Pareto optimality, Nash Equilibrium, social welfare.
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

### 🗂️ Part 2: The Game Description Language (GDL) (60 mins)
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
    - Board and video game generation.
    - Representing complex mechanics and agent interactions.
    - 🔮 Future integration with machine learning.

---

### 🧩 Part 3: Belief Hierarchies and Theory of Mind (60 mins)
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

### 🤖 Part 4: Autoformalization, Simulation Framework, and Case Studies (60 mins)
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

## 💻 Technical Setup

Before attending the tutorial, please ensure you have the following setup ready to fully participate in the hands-on components:

- **🧰 Tools**
  - Python 3, Jupyter Notebook, SWI-Prolog for running the examples locally, <br>
    or     
  - Google Colab for cloud-based execution.
