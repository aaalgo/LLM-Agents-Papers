# LLM-Agents-Papers
## :writing_hand: Description
Last Updated Time: 2025/2/23

A repo lists papers related to LLM based agent. Includes
- [Survey](#Survey)
- [Technique For Enhancement](#Technique-For-Enhancement)
  - [Planning](#Planning)
  - [Memory Mechanism](#Memory-Mechanism)
  - [Feedback&Reflection](#FeedbackReflection)
  - [RAG](#RAG)
  - [Search](#Search)
- [Interaction](#Interaction)
  - [Role Playing](#Role-Playing)
  - [Conversation](#Conversation)
  - [Game Playing](#Game-Playing)
  - [Human-Agent Interaction](#Human-Agent-Interaction)
  - [Tool Usage](#Tool-Usage)
  - [Simulation](#Simulation)
- [Application](#Application)
  - [Math](#Math)
  - [Chemistry](#Chemistry)
  - [Biology](#Biology)
  - [Physics](#Physics)
  - [Geography](#Geography)
  - [Art](#Art)
  - [Medicine](#Medicine)
  - [Finance](#Finance)
  - [Software Engineering](#Software-Engineering)
  - [Research](#Research)
- [Automation](#Automation)
  - [Workflow](#Workflow)
  - [Automatic Evaluation](#Automatic-Evaluation)
- [Training](#Training)
  - [Fine tuning](#Fine-tuning)
  - [RL](#RL)
  - [DPO](#DPO)
- [Scaling](#Scaling)
  - [Single-Agent Framework](#Single-Agent-Framework)
  - [Multi-Agent System](#Multi-Agent-System)
- [Stability](#Stability)
  - [Safety](#Safety)
  - [Bias](#Bias)
  - [Hallucination](#Hallucination)
- [Infrastructure](#Infrastructure)
  - [Benchmark&Evaluation](#BenchmarkEvaluation)
  - [Environment&Platform](#EnvironmentPlatform)
  - [Dataset](#Dataset)
- [Others](#Others)
## :yellow_heart: Recommendation
For more comprehensive reading, we also recommend other paper lists:
* [zjunlp/LLMAgentPapers](https://github.com/zjunlp/LLMAgentPapers): Must-read Papers on Large Language Model Agents.
* [teacherpeterpan/self-correction-llm-papers](https://github.com/teacherpeterpan/self-correction-llm-papers): This is a collection of research papers for Self-Correcting Large Language Models with Automated Feedback.
* [Paitesanshi/LLM-Agent-Survey](https://github.com/Paitesanshi/LLM-Agent-Survey): A Survey on LLM-based Autonomous Agents.
* [woooodyy/llm-agent-paper-list](https://github.com/woooodyy/llm-agent-paper-list): Must-read papers for LLM-based agents.
* [git-disl/awesome-LLM-game-agent-papers](https://github.com/git-disl/awesome-LLM-game-agent-papers): Must-read papers for LLM-based Game agents.
## :newspaper: Papers
### Survey
- [2025/02/20] **Beyond Self-Talk: A Communication-Centric Survey of LLM-Based Multi-Agent Systems** | [[paper]](https://arxiv.org/abs/2502.14321) | [code]

- [2025/02/18] **Towards a Design Guideline for RPA Evaluation: A Survey of Large Language Model-Based Role-Playing Agents** | [[paper]](https://arxiv.org/abs/2502.13012) | [code]

- [2025/02/16] **A Survey of LLM-based Agents in Medicine: How far are we from Baymax?** | [[paper]](https://arxiv.org/abs/2502.11211) | [code]

- [2025/01/15] **Agentic Retrieval-Augmented Generation: A Survey on Agentic RAG** | [[paper]](https://arxiv.org/abs/2501.09136) | [code]

- [2024/12/23] **A Survey on LLM-based Multi-Agent System: Recent Advances and New Frontiers in Application** | [[paper]](https://arxiv.org/abs/2412.17481) | [code]

- [2024/12/18] **A Survey on Large Language Model-based Agents for Statistics and Data Science** | [[paper]](https://arxiv.org/abs/2412.14222) | [code]

- [2024/12/05] **A Survey on Large Language Model-Based Social Agents in Game-Theoretic Scenarios** | [[paper]](https://arxiv.org/abs/2412.03920) | [code]

- [2024/12/04] **From Individual to Society: A Survey on Social Simulation Driven by Large Language Model-based Agents** | [[paper]](https://arxiv.org/abs/2412.03563) | [code]

- [2024/11/27] **Large Language Model-Brained GUI Agents: A Survey** | [[paper]](https://arxiv.org/abs/2411.18279) | [code]

- [2024/09/27] **A Survey on Complex Tasks for Goal-Directed Interactive Agents** | [[paper]](https://arxiv.org/abs/2409.18538) | [code]

- [2024/09/13] **Agents in Software Engineering: Survey, Landscape, and Vision** | [[paper]](https://arxiv.org/abs/2409.09030) | [code]

- [2024/09/04] **A Survey on Emergent Language** | [[paper]](https://arxiv.org/abs/2409.02645) | [code]

- [2024/08/05] **From LLMs to LLM-based Agents for Software Engineering: A Survey of Current, Challenges and Future** | [[paper]](https://arxiv.org/abs/2408.02479) | [code]

- [2024/07/26] **Large Language Model Agent in Financial Trading: A Survey** | [[paper]](https://arxiv.org/abs/2408.06361) | [code]

- [2024/06/03] **Two Tales of Persona in LLMs: A Survey of Role-Playing and Personalization** | [[paper]](https://arxiv.org/abs/2406.01171) | [[code]](https://github.com/miulab/personallm-survey)

- [2024/06/01] **Towards Rationality in Language and Multimodal Agents: A Survey** | [[paper]](https://arxiv.org/abs/2406.00252) | [code]

- [2024/04/17] **Advancing Social Intelligence in AI Agents: Technical Challenges and Open Questions** | [[paper]](https://arxiv.org/abs/2404.11023) | [code]

- [2024/04/02] **A Survey on Large Language Model-Based Game Agents** | [[paper]](https://arxiv.org/abs/2404.02039) | [[code]](https://github.com/git-disl/awesome-LLM-game-agent-papers)

- [2024/03/26] **Leveraging Large Language Models in Human-Robot Interaction: A Critical Analysis of Potential and Pitfalls** | [[paper]](https://arxiv.org/abs/2405.00693) | [code]

- [2024/03/07] **Promising and worth-to-try future directions for advancing state-of-the-art surrogates methods of agent-based models in social and health computational sciences** | [[paper]](https://arxiv.org/abs/2403.04417) | [code]

- [2024/02/28] **Large Language Models and Games: A Survey and Roadmap** | [[paper]](https://arxiv.org/abs/2402.18659) | [code]

- [2024/02/28] **A Survey on Recent Advances in LLM-Based Multi-turn Dialogue Systems** | [[paper]](https://arxiv.org/abs/2402.18013) | [code]

- [2024/02/05] **Understanding the planning of LLM agents: A survey** | [[paper]](https://arxiv.org/abs/2402.02716) | [code]

- [2024/01/01] **If LLM Is the Wizard, Then Code Is the Wand: A Survey on How Code Empowers Large Language Models to Serve as Intelligent Agents** | [[paper]](https://arxiv.org/abs/2401.00812) | [code]

- [2023/12/31] **A Survey of Personality, Persona, and Profile in Conversational Agents and Chatbots** | [[paper]](https://arxiv.org/abs/2401.00609) | [code]

- [2023/12/19] **Large Language Models Empowered Agent-based Modeling and Simulation: A Survey and Perspectives** | [[paper]](https://arxiv.org/abs/2312.11970) | [code]

- [2023/09/14] **The Rise and Potential of Large Language Model Based Agents: A Survey** | [[paper]](https://arxiv.org/abs/2309.07864) | [code]

- [2023/08/22] **A Survey on Large Language Model based Autonomous Agents** | [[paper]](https://arxiv.org/abs/2308.11432) | [code]

- [2023/06/27] **Next Steps for Human-Centered Generative AI: A Technical Perspective** | [[paper]](https://arxiv.org/abs/2306.15774) | [code]

---
### Technique For Enhancement
#### Planning
- [2025/02/08] **CODESIM: Multi-Agent Code Generation and Problem Solving through Simulation-Driven Planning and Debugging** | [[paper]](https://arxiv.org/abs/2502.05664) | [code]

- [2025/02/06] **Robotouille: An Asynchronous Planning Benchmark for LLM Agents** | [[paper]](https://arxiv.org/abs/2502.05227) | [code]

- [2025/01/27] **MADP: Multi-Agent Deductive Planning for Enhanced Cognitive-Behavioral Mental Health Question Answer** | [[paper]](https://arxiv.org/abs/2501.15826) | [code]

- [2025/01/14] **Talk to Right Specialists: Routing and Planning in Multi-agent System for Question Answering** | [[paper]](https://arxiv.org/abs/2501.07813) | [code]

- [2024/12/30] **Plancraft: an evaluation dataset for planning with LLM agents** | [[paper]](https://arxiv.org/abs/2412.21033) | [code]

- [2024/12/28] **Efficient Multi-Agent Collaboration with Tool Use for Online Planning in Complex Table Question Answering** | [[paper]](https://arxiv.org/abs/2412.20145) | [code]

- [2024/12/13] **Script-Based Dialog Policy Planning for LLM-Powered Conversational Agents: A Basic Architecture for an &#34;AI Therapist&#34;** | [[paper]](https://arxiv.org/abs/2412.15242) | [code]

- [2024/11/13] **One STEP at a time: Language Agents are Stepwise Planners** | [[paper]](https://arxiv.org/abs/2411.08432) | [code]

- [2024/11/05] **Benchmarking Multimodal Retrieval Augmented Generation with Dynamic VQA Dataset and Self-adaptive Planning Agent** | [[paper]](https://arxiv.org/abs/2411.02937) | [code]

- [2024/10/12] **CAMPHOR: Collaborative Agents for Multi-input Planning and High-Order Reasoning On Device** | [[paper]](https://arxiv.org/abs/2410.09407) | [code]

- [2024/10/01] **Self-controller: Controlling LLMs with Multi-round Step-by-step Self-awareness** | [[paper]](https://arxiv.org/abs/2410.00359) | [code]

- [2024/09/30] **Interactive Speculative Planning: Enhance Agent Efficiency through Co-design of System and User Interface** | [[paper]](https://arxiv.org/abs/2410.00079) | [code]

- [2024/09/28] **SELP: Generating Safe and Efficient Task Plans for Robot Agents with Large Language Models** | [[paper]](https://arxiv.org/abs/2409.19471) | [code]

- [2024/09/25] **MSI-Agent: Incorporating Multi-Scale Insight into Embodied Agents for Superior Planning and Decision-Making** | [[paper]](https://arxiv.org/abs/2409.16686) | [code]

- [2024/08/15] **VerilogCoder: Autonomous Verilog Coding Agents with Graph-based Planning and Abstract Syntax Tree (AST)-based Waveform Tracing Tool** | [[paper]](https://arxiv.org/abs/2408.08927) | [code]

- [2024/08/12] **Towards Autonomous Agents: Adaptive-planning, Reasoning, and Acting in Language Models** | [[paper]](https://arxiv.org/abs/2408.06458) | [code]

- [2024/08/01] **AgentGen: Enhancing Planning Abilities for Large Language Model based Agent via Environment and Task Generation** | [[paper]](https://arxiv.org/abs/2408.00764) | [code]

- [2024/07/04] **Controllable Conversations: Planning-Based Dialogue Agent with Large Language Models** | [[paper]](https://arxiv.org/abs/2407.03884) | [code]

- [2024/06/17] **RePrompt: Planning by Automatic Prompt Engineering for Large Language Models Agents** | [[paper]](https://arxiv.org/abs/2406.11132) | [code]

- [2024/06/09] **A Review of Prominent Paradigms for LLM-Based Agents: Tool Use (Including RAG), Planning, and Feedback Learning** | [[paper]](https://arxiv.org/abs/2406.05804) | [code]

- [2024/06/06] **Tool-Planner: Task Planning with Clusters across Multiple Tools** | [[paper]](https://arxiv.org/abs/2406.03807) | [[code]](https://github.com/OceannTwT/Tool-Planner)

- [2024/05/28] **A Human-Like Reasoning Framework for Multi-Phases Planning Task with Large Language Models** | [[paper]](https://arxiv.org/abs/2405.18208) | [code]

- [2024/05/27] **REVECA: Adaptive Planning and Trajectory-based Validation in Cooperative Language Agents using Information Relevance and Relative Proximity** | [[paper]](https://arxiv.org/abs/2405.16751) | [code]

- [2024/04/21] **Socratic Planner: Inquiry-Based Zero-Shot Planning for Embodied Instruction Following** | [[paper]](https://arxiv.org/abs/2404.15190) | [code]

- [2024/04/17] **The Landscape of Emerging AI Agent Architectures for Reasoning, Planning, and Tool Calling: A Survey** | [[paper]](https://arxiv.org/abs/2404.11584) | [code]

- [2024/03/11] **Strength Lies in Differences! Improving Strategy Planning for Non-collaborative Dialogues via Diversified User Simulation** | [[paper]](https://arxiv.org/abs/2403.06769) | [code]

- [2024/03/10] **TRAD: Enhancing LLM Agents with Step-Wise Thought Retrieval and Aligned Decision** | [[paper]](https://arxiv.org/abs/2403.06221) | [code]

- [2024/03/05] **KnowAgent: Knowledge-Augmented Planning for LLM-Based Agents** | [[paper]](https://arxiv.org/abs/2403.03101) | [code]

- [2024/02/29] **PlanGPT: Enhancing Urban Planning with Tailored Language Model and Efficient Retrieval** | [[paper]](https://arxiv.org/abs/2402.19273) | [code]

- [2024/02/18] **What&#39;s the Plan? Evaluating and Developing Planning-Aware Techniques for Language Models** | [[paper]](https://arxiv.org/abs/2402.11489) | [code]

- [2024/02/18] **PreAct: Prediction Enhances Agent&#39;s Planning Ability** | [[paper]](https://arxiv.org/abs/2402.11534) | [code]

- [2024/02/16] **When is Tree Search Useful for LLM Planning? It Depends on the Discriminator** | [[paper]](https://arxiv.org/abs/2402.10890) | [[code]](https://github.com/osu-nlp-group/llm-planning-eval)

- [2024/02/15] **TDAG: A Multi-Agent Framework based on Dynamic Task Decomposition and Agent Generation** | [[paper]](https://arxiv.org/abs/2402.10178) | [code]

- [2024/02/09] **Introspective Planning: Aligning Robots&#39; Uncertainty with Inherent Task Ambiguity** | [[paper]](https://arxiv.org/abs/2402.06529) | [code]

- [2024/02/06] **RAP: Retrieval-Augmented Planning with Contextual Memory for Multimodal LLM Agents** | [[paper]](https://arxiv.org/abs/2402.03610) | [code]

- [2024/02/02] **TravelPlanner: A Benchmark for Real-World Planning with Language Agents** | [[paper]](https://arxiv.org/abs/2402.01622) | [[code]](https://github.com/OSU-NLP-Group/TravelPlanner)

- [2024/01/10] **AutoAct: Automatic Agent Learning from Scratch for QA via Self-Planning** | [[paper]](https://arxiv.org/abs/2401.05268) | [code]

- [2023/11/19] **TPTU-v2: Boosting Task Planning and Tool Usage of Large Language Model-based Agents in Real-world Systems** | [[paper]](https://arxiv.org/abs/2311.11315) | [code]

- [2023/10/09] **Put Your Money Where Your Mouth Is: Evaluating Strategic Planning and Execution of LLM Agents in an Auction Arena** | [[paper]](https://arxiv.org/abs/2310.05746) | [code]

- [2023/08/07] **TPTU: Large Language Model-based AI Agents for Task Planning and Tool Usage** | [[paper]](https://arxiv.org/abs/2308.03427) | [code]

- [2023/08/01] **SelfCheck: Using LLMs to Zero-Shot Check Their Own Step-by-Step Reasoning** | [[paper]](https://arxiv.org/abs/2308.00436) | [code]

- [2023/05/26] **AdaPlanner: Adaptive Planning from Feedback with Language Models** | [[paper]](https://arxiv.org/abs/2305.16653) | [code]

- [2023/05/24] **Reasoning with Language Model is Planning with World Model** | [[paper]](https://arxiv.org/abs/2305.14992) | [code]

- [2023/05/24] **Leveraging Pre-trained Large Language Models to Construct and Utilize World Models for Model-based Task Planning** | [[paper]](https://arxiv.org/abs/2305.14909) | [[code]](https://github.com/GuanSuns/LLMs-World-Models-for-Planning)

- [2023/03/29] **Skill Reinforcement Learning and Planning for Open-World Long-Horizon Tasks** | [[paper]](https://arxiv.org/abs/2303.16563) | [code]

- [2023/02/03] **Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents** | [[paper]](https://arxiv.org/abs/2302.01560) | [code]

- [2022/12/08] **LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models** | [[paper]](https://arxiv.org/abs/2212.04088) | [code]

#### Memory Mechanism
- [2025/02/17] **A-MEM: Agentic Memory for LLM Agents** | [[paper]](https://arxiv.org/abs/2502.12110) | [code]

- [2025/02/08] **On Memory Construction and Retrieval for Personalized Conversational Agents** | [[paper]](https://arxiv.org/abs/2502.05589) | [code]

- [2025/01/20] **Zep: A Temporal Knowledge Graph Architecture for Agent Memory** | [[paper]](https://arxiv.org/abs/2501.13956) | [code]

- [2025/01/15] **Doc-Guided Sent2Sent++: A Sent2Sent++ Agent with Doc-Guided memory for Document-level Machine Translation** | [[paper]](https://arxiv.org/abs/2501.08523) | [code]

- [2024/12/17] **On the Structural Memory of LLM Agents** | [[paper]](https://arxiv.org/abs/2412.15266) | [code]

- [2024/12/17] **Memory-Augmented Agent Training for Business Document Understanding** | [[paper]](https://arxiv.org/abs/2412.15274) | [code]

- [2024/10/10] **DelTA: An Online Document-Level Translation Agent Based on Multi-Level Memory** | [[paper]](https://arxiv.org/abs/2410.08143) | [code]

- [2024/09/28] **Crafting Personalized Agents through Retrieval-Augmented Generation on Editable Memory Graphs** | [[paper]](https://arxiv.org/abs/2409.19401) | [code]

- [2024/09/11] **Agent Workflow Memory** | [[paper]](https://arxiv.org/abs/2409.07429) | [code]

- [2024/09/01] **Self-evolving Agents with reflective and memory-augmented abilities** | [[paper]](https://arxiv.org/abs/2409.00872) | [code]

- [2024/08/18] **HiAgent: Hierarchical Working Memory Management for Solving Long-Horizon Agent Tasks with Large Language Model** | [[paper]](https://arxiv.org/abs/2408.09559) | [code]

- [2024/08/07] **Optimus-1: Hybrid Multimodal Memory Empowered Agents Excel in Long-Horizon Tasks** | [[paper]](https://arxiv.org/abs/2408.03615) | [code]

- [2024/05/29] **Toward Conversational Agents with Context and Time Sensitive Long-term Memory** | [[paper]](https://arxiv.org/abs/2406.00057) | [[code]](https://github.com/Zyphra/TemporalMemoryDataset)

- [2024/04/15] **Memory Sharing for Large Language Model based Agents** | [[paper]](https://arxiv.org/abs/2404.09982) | [[code]](https://github.com/GHupppp/MemorySharingLLM)

- [2024/02/19] **Compress to Impress: Unleashing the Potential of Compressive Memory in Real-World Long-Term Conversations** | [[paper]](https://arxiv.org/abs/2402.11975) | [code]

- [2024/02/07] **InfLLM: Training-Free Long-Context Extrapolation for LLMs with an Efficient Context Memory** | [[paper]](https://arxiv.org/abs/2402.04617) | [code]

- [2024/02/06] **RAP: Retrieval-Augmented Planning with Contextual Memory for Multimodal LLM Agents** | [[paper]](https://arxiv.org/abs/2402.03610) | [code]

- [2024/01/05] **From LLM to Conversational Agent: A Memory Enhanced Architecture with Fine-Tuning of Large Language Models** | [[paper]](https://arxiv.org/abs/2401.02777) | [code]

- [2023/12/22] **Empowering Working Memory for Large Language Model Agents** | [[paper]](https://arxiv.org/abs/2312.17259) | [code]

- [2023/12/22] **Personalized Large Language Model Assistant with Evolving Conditional Memory** | [[paper]](https://arxiv.org/abs/2312.17257) | [code]

- [2023/11/10] **JARVIS-1: Open-World Multi-task Agents with Memory-Augmented Multimodal Language Models** | [[paper]](https://arxiv.org/abs/2311.05997) | [[code]](https://github.com/CraftJarvis/JARVIS-1)

- [2023/06/06] **ChatDB: Augmenting LLMs with Databases as Their Symbolic Memory** | [[paper]](https://arxiv.org/abs/2306.03901) | [code]

- [2023/05/23] **RET-LLM: Towards a General Read-Write Memory for Large Language Models** | [[paper]](https://arxiv.org/abs/2305.14322) | [code]

- [2023/05/17] **MemoryBank: Enhancing Large Language Models with Long-Term Memory** | [[paper]](https://arxiv.org/abs/2305.10250) | [code]

- [2023/05/02] **The Role of Summarization in Generative Agents: A Preliminary Perspective** | [[paper]](https://arxiv.org/abs/2305.01253) | [code]

- [2023/05/01] **Learning to Reason and Memorize with Self-Notes** | [[paper]](https://arxiv.org/abs/2305.00833) | [code]

- [2023/04/26] **Enhancing Large Language Model with Self-Controlled Memory Framework** | [[paper]](https://arxiv.org/abs/2304.13343) | [code]

- [2023/04/21] **Emergent and Predictable Memorization in Large Language Models** | [[paper]](https://arxiv.org/abs/2304.11158) | [code]

#### Feedback&Reflection
- [2025/02/20] **STeCa: Step-level Trajectory Calibration for LLM Agent Learning** | [[paper]](https://arxiv.org/abs/2502.14276) | [code]

- [2025/02/17] **Table-Critic: A Multi-Agent Framework for Collaborative Criticism and Refinement in Table Reasoning** | [[paper]](https://arxiv.org/abs/2502.11799) | [code]

- [2025/02/17] **A Study on Leveraging Search and Self-Feedback for Agent Reasoning** | [[paper]](https://arxiv.org/abs/2502.12094) | [code]

- [2025/02/03] **PlotGen: Multi-Agent LLM-based Scientific Data Visualization via Multimodal Feedback** | [[paper]](https://arxiv.org/abs/2502.00988) | [code]

- [2025/01/26] **Large Language Models as Theory of Mind Aware Generative Agents with Counterfactual Reflection** | [[paper]](https://arxiv.org/abs/2501.15355) | [code]

- [2025/01/23] **AgentRec: Agent Recommendation Using Sentence Embeddings Aligned to Human Feedback** | [[paper]](https://arxiv.org/abs/2501.13333) | [code]

- [2025/01/08] **InfiGUIAgent: A Multimodal Generalist GUI Agent with Native Reasoning and Reflection** | [[paper]](https://arxiv.org/abs/2501.04575) | [code]

- [2024/12/31] **Enhancing LLM Reasoning with Multi-Path Collaborative Reactive and Reflection agents** | [[paper]](https://arxiv.org/abs/2501.00430) | [code]

- [2024/12/22] **A Multi-AI Agent System for Autonomous Optimization of Agentic AI Solutions via Iterative Refinement and LLM-Driven Feedback Loops** | [[paper]](https://arxiv.org/abs/2412.17149) | [code]

- [2024/11/29] **Training Agents with Weakly Supervised Feedback from Large Language Models** | [[paper]](https://arxiv.org/abs/2411.19547) | [code]

- [2024/11/21] **Enhancing LLMs for Power System Simulations: A Feedback-driven Multi-agent Framework** | [[paper]](https://arxiv.org/abs/2411.16707) | [code]

- [2024/11/11] **Using Generative AI and Multi-Agents to Provide Automatic Feedback** | [[paper]](https://arxiv.org/abs/2411.07407) | [code]

- [2024/11/04] **Positive Experience Reflection for Agents in Interactive Text Environments** | [[paper]](https://arxiv.org/abs/2411.02223) | [code]

- [2024/10/29] **Enhancing Financial Question Answering with a Multi-Agent Reflection Framework** | [[paper]](https://arxiv.org/abs/2410.21741) | [code]

- [2024/10/28] **CRAT: A Multi-Agent Framework for Causality-Enhanced Reflective and Retrieval-Augmented Translation with Large Language Models** | [[paper]](https://arxiv.org/abs/2410.21067) | [code]

- [2024/10/25] **OpenWebVoyager: Building Multimodal Web Agents via Iterative Real-World Exploration, Feedback and Optimization** | [[paper]](https://arxiv.org/abs/2410.19609) | [code]

- [2024/10/23] **ReflecTool: Towards Reflection-Aware Tool-Augmented Clinical Agents** | [[paper]](https://arxiv.org/abs/2410.17657) | [code]

- [2024/10/20] **Training Language Models to Critique With Multi-agent Feedback** | [[paper]](https://arxiv.org/abs/2410.15287) | [code]

- [2024/10/16] **PRefLexOR: Preference-based Recursive Language Modeling for Exploratory Optimization of Reasoning and Agentic Thinking** | [[paper]](https://arxiv.org/abs/2410.12375) | [code]

- [2024/10/08] **DataEnvGym: Data Generation Agents in Teacher Environments with Student Feedback** | [[paper]](https://arxiv.org/abs/2410.06215) | [code]

- [2024/10/02] **ExACT: Teaching AI Agents to Explore with Reflective-MCTS and Exploratory Learning** | [[paper]](https://arxiv.org/abs/2410.02052) | [code]

- [2024/10/02] **RGD: Multi-LLM Based Agent Debugger via Refinement and Generation Guidance** | [[paper]](https://arxiv.org/abs/2410.01242) | [code]

- [2024/09/18] **MAgICoRe: Multi-Agent, Iterative, Coarse-to-Fine Refinement for Reasoning** | [[paper]](https://arxiv.org/abs/2409.12147) | [code]

- [2024/09/05] **E2CL: Exploration-based Error Correction Learning for Embodied Agents** | [[paper]](https://arxiv.org/abs/2409.03256) | [code]

- [2024/09/01] **Self-evolving Agents with reflective and memory-augmented abilities** | [[paper]](https://arxiv.org/abs/2409.00872) | [code]

- [2024/08/30] **Tool-Assisted Agent on SQL Inspection and Refinement in Real-World Scenarios** | [[paper]](https://arxiv.org/abs/2408.16991) | [code]

- [2024/08/15] **MAG-SQL: Multi-Agent Generative Approach with Soft Schema Linking and Iterative Sub-SQL Refinement for Text-to-SQL** | [[paper]](https://arxiv.org/abs/2408.07930) | [code]

- [2024/07/25] **Recursive Introspection: Teaching Language Model Agents How to Self-Improve** | [[paper]](https://arxiv.org/abs/2407.18219) | [code]

- [2024/06/09] **A Review of Prominent Paradigms for LLM-Based Agents: Tool Use (Including RAG), Planning, and Feedback Learning** | [[paper]](https://arxiv.org/abs/2406.05804) | [code]

- [2024/06/05] **LLM-based Rewriting of Inappropriate Argumentation using Reinforcement Learning from Machine Feedback** | [[paper]](https://arxiv.org/abs/2406.03363) | [code]

- [2024/06/03] **Re-ReST: Reflection-Reinforced Self-Training for Language Agents** | [[paper]](https://arxiv.org/abs/2406.01495) | [[code]](https://github.com/PlusLabNLP/Re-ReST)

- [2024/03/18] **QueryAgent: A Reliable and Efficient Reasoning Framework with Environmental Feedback-based Self-Correction** | [[paper]](https://arxiv.org/abs/2403.11886) | [code]

- [2024/03/17] **Improving Dialogue Agents by Decomposing One Global Explicit Annotation with Local Implicit Multimodal Feedback** | [[paper]](https://arxiv.org/abs/2403.11330) | [code]

- [2024/03/08] **ChatASU: Evoking LLM&#39;s Reflexion to Truly Understand Aspect Sentiment in Dialogues** | [[paper]](https://arxiv.org/abs/2403.05326) | [code]

- [2024/03/04] **Trial and Error: Exploration-Based Trajectory Optimization for LLM Agents** | [[paper]](https://arxiv.org/abs/2403.02502) | [code]

- [2024/02/27] **Agent-Pro: Learning to Evolve via Policy-Level Reflection and Optimization** | [[paper]](https://arxiv.org/abs/2402.17574) | [code]

- [2024/02/26] **SelectIT: Selective Instruction Tuning for LLMs via Uncertainty-Aware Self-Reflection** | [[paper]](https://arxiv.org/abs/2402.16705) | [code]

- [2024/02/22] **Mirror: A Multiple-perspective Self-Reflection Method for Knowledge-rich Reasoning** | [[paper]](https://arxiv.org/abs/2402.14963) | [code]

- [2024/02/19] **A Critical Evaluation of AI Feedback for Aligning Large Language Models** | [[paper]](https://arxiv.org/abs/2402.12366) | [code]

- [2024/02/06] **AnyTool: Self-Reflective, Hierarchical Agents for Large-Scale API Calls** | [[paper]](https://arxiv.org/abs/2402.04253) | [[code]](https://github.com/dyabel/anytool)

- [2024/02/02] **StepCoder: Improve Code Generation with Reinforcement Learning from Compiler Feedback** | [[paper]](https://arxiv.org/abs/2402.01391) | [code]

- [2023/11/14] **The ART of LLM Refinement: Ask, Refine, and Trust** | [[paper]](https://arxiv.org/abs/2311.07961) | [code]

- [2023/10/31] **Learning From Mistakes Makes LLM Better Reasoner** | [[paper]](https://arxiv.org/abs/2310.20689) | [code]

- [2023/10/12] **A Zero-Shot Language Agent for Computer Control with Structured Reflection** | [[paper]](https://arxiv.org/abs/2310.08740) | [code]

- [2023/07/27] **PanGu-Coder2: Boosting Large Language Models for Code with Ranking Feedback** | [[paper]](https://arxiv.org/abs/2307.14936) | [code]

- [2023/05/22] **Making Language Models Better Tool Learners with Execution Feedback** | [[paper]](https://arxiv.org/abs/2305.13068) | [code]

- [2023/05/17] **Improving Language Model Negotiation with Self-Play and In-Context Learning from AI Feedback** | [[paper]](https://arxiv.org/abs/2305.10142) | [code]

- [2023/04/21] **Improving Grounded Language Understanding in a Collaborative Environment by Interacting with Agents Through Help Feedback** | [[paper]](https://arxiv.org/abs/2304.10750) | [code]

- [2023/04/11] **Teaching Large Language Models to Self-Debug** | [[paper]](https://arxiv.org/abs/2304.05128) | [code]

- [2023/03/30] **Self-Refine: Iterative Refinement with Self-Feedback** | [[paper]](https://arxiv.org/abs/2303.17651) | [code]

#### RAG
- [2025/02/19] **RAG-Gym: Optimizing Reasoning and Search Agents with Process Supervision** | [[paper]](https://arxiv.org/abs/2502.13957) | [code]

- [2025/02/08] **On Memory Construction and Retrieval for Personalized Conversational Agents** | [[paper]](https://arxiv.org/abs/2502.05589) | [code]

- [2025/02/06] **Enhancing Online Learning Efficiency Through Heterogeneous Resource Integration with a Multi-Agent RAG System** | [[paper]](https://arxiv.org/abs/2502.03948) | [code]

- [2025/01/25] **Improving Retrieval-Augmented Generation through Multi-Agent Reinforcement Learning** | [[paper]](https://arxiv.org/abs/2501.15228) | [code]

- [2024/12/31] **MAIN-RAG: Multi-Agent Filtering Retrieval-Augmented Generation** | [[paper]](https://arxiv.org/abs/2501.00332) | [code]

- [2024/12/24] **GeAR: Graph-enhanced Agent for Retrieval-augmented Generation** | [[paper]](https://arxiv.org/abs/2412.18431) | [code]

- [2024/12/20] **Towards Interpretable Radiology Report Generation via Concept Bottlenecks using a Multi-Agentic RAG** | [[paper]](https://arxiv.org/abs/2412.16086) | [code]

- [2024/12/16] **BioRAGent: A Retrieval-Augmented Generation System for Showcasing Generative Query Expansion and Domain-Specific Search for Scientific Q&amp;A** | [[paper]](https://arxiv.org/abs/2412.12358) | [code]

- [2024/12/07] **SLA Management in Reconfigurable Multi-Agent RAG: A Systems Approach to Question Answering** | [[paper]](https://arxiv.org/abs/2412.06832) | [code]

- [2024/11/05] **Benchmarking Multimodal Retrieval Augmented Generation with Dynamic VQA Dataset and Self-adaptive Planning Agent** | [[paper]](https://arxiv.org/abs/2411.02937) | [code]

- [2024/10/28] **CRAT: A Multi-Agent Framework for Causality-Enhanced Reflective and Retrieval-Augmented Translation with Large Language Models** | [[paper]](https://arxiv.org/abs/2410.21067) | [code]

- [2024/10/18] **Toolshed: Scale Tool-Equipped Agents with Advanced RAG-Tool Fusion and Tool Knowledge Bases** | [[paper]](https://arxiv.org/abs/2410.14594) | [code]

- [2024/10/01] **Conversational Exploratory Search of Scholarly Publications Using Knowledge Graphs** | [[paper]](https://arxiv.org/abs/2410.00427) | [code]

- [2024/09/28] **Crafting Personalized Agents through Retrieval-Augmented Generation on Editable Memory Graphs** | [[paper]](https://arxiv.org/abs/2409.19401) | [code]

- [2024/08/18] **Agentic Retrieval-Augmented Generation for Time Series Analysis** | [[paper]](https://arxiv.org/abs/2408.14484) | [code]

- [2024/08/05] **LLM Agents Improve Semantic Code Search** | [[paper]](https://arxiv.org/abs/2408.11058) | [code]

- [2024/08/03] **MALADE: Orchestration of LLM-powered Agents with Retrieval Augmented Generation for Pharmacovigilance** | [[paper]](https://arxiv.org/abs/2408.01869) | [code]

- [2024/07/20] **Golden-Retriever: High-Fidelity Agentic Retrieval Augmented Generation for Industrial Knowledge Base** | [[paper]](https://arxiv.org/abs/2408.00798) | [code]

- [2024/06/26] **Geode: A Zero-shot Geospatial Question-Answering Agent with Explicit Reasoning and Precise Spatio-Temporal Retrieval** | [[paper]](https://arxiv.org/abs/2407.11014) | [code]

- [2024/06/19] **StackRAG Agent: Improving Developer Answers with Retrieval-Augmented Generation** | [[paper]](https://arxiv.org/abs/2406.13840) | [code]

- [2024/06/09] **A Review of Prominent Paradigms for LLM-Based Agents: Tool Use (Including RAG), Planning, and Feedback Learning** | [[paper]](https://arxiv.org/abs/2406.05804) | [code]

- [2024/03/05] **AgentsCourt: Building Judicial Decision-Making Agents with Court Debate Simulation and Legal Knowledge Augmentation** | [[paper]](https://arxiv.org/abs/2403.02959) | [code]

- [2024/02/06] **RAP: Retrieval-Augmented Planning with Contextual Memory for Multimodal LLM Agents** | [[paper]](https://arxiv.org/abs/2402.03610) | [code]

- [2023/12/27] **Automating Knowledge Acquisition for Content-Centric Cognitive Agents Using LLMs** | [[paper]](https://arxiv.org/abs/2312.16378) | [code]

#### Search
- [2025/02/20] **I-MCTS: Enhancing Agentic AutoML via Introspective Monte Carlo Tree Search** | [[paper]](https://arxiv.org/abs/2502.14693) | [code]

- [2025/02/18] **R2-KG: General-Purpose Dual-Agent Framework for Reliable Reasoning on Knowledge Graphs** | [[paper]](https://arxiv.org/abs/2502.12767) | [code]

- [2025/02/18] **Agentic Deep Graph Reasoning Yields Self-Organizing Knowledge Networks** | [[paper]](https://arxiv.org/abs/2502.13025) | [code]

- [2025/02/17] **A Study on Leveraging Search and Self-Feedback for Agent Reasoning** | [[paper]](https://arxiv.org/abs/2502.12094) | [code]

- [2025/02/05] **SymAgent: A Neural-Symbolic Self-Learning Agent Framework for Complex Reasoning over Knowledge Graphs** | [[paper]](https://arxiv.org/abs/2502.03283) | [code]

- [2025/02/02] **Efficient Multi-Agent System Training with Data Influence-Oriented Tree Search** | [[paper]](https://arxiv.org/abs/2502.00955) | [code]

- [2025/01/31] **KBQA-o1: Agentic Knowledge Base Question Answering with Monte Carlo Tree Search** | [[paper]](https://arxiv.org/abs/2501.18922) | [code]

- [2025/01/09] **Search-o1: Agentic Search-Enhanced Large Reasoning Models** | [[paper]](https://arxiv.org/abs/2501.05366) | [code]

- [2024/12/24] **A Novel Task-Driven Method with Evolvable Interactive Agents Using Event Trees for Enhanced Emergency Decision Support** | [[paper]](https://arxiv.org/abs/2501.06193) | [code]

- [2024/12/22] **Multi-Agent Sampling: Scaling Inference Compute for Data Synthesis with Tree Search-Based Agentic Collaboration** | [[paper]](https://arxiv.org/abs/2412.17061) | [code]

- [2024/12/05] **Agent AI with LangGraph: A Modular Framework for Enhancing Machine Translation Using Large Language Models** | [[paper]](https://arxiv.org/abs/2412.03801) | [code]

- [2024/11/07] **CodeTree: Agent-guided Tree Search for Code Generation with Large Language Models** | [[paper]](https://arxiv.org/abs/2411.04329) | [code]

- [2024/10/29] **Synergizing LLM Agents and Knowledge Graph for Socioeconomic Prediction in LBSN** | [[paper]](https://arxiv.org/abs/2411.00028) | [code]

- [2024/10/25] **AGENT-CQ: Automatic Generation and Evaluation of Clarifying Questions for Conversational Search with LLMs** | [[paper]](https://arxiv.org/abs/2410.19692) | [code]

- [2024/10/22] **SELA: Tree-Search Enhanced LLM Agents for Automated Machine Learning** | [[paper]](https://arxiv.org/abs/2410.17238) | [code]

- [2024/10/13] **Expanding Search Space with Diverse Prompting Agents: An Efficient Sampling Approach for LLM Mathematical Reasoning** | [[paper]](https://arxiv.org/abs/2410.09780) | [code]

- [2024/10/13] **LLM-Based Multi-Agent Systems are Scalable Graph Generative Models** | [[paper]](https://arxiv.org/abs/2410.09824) | [code]

- [2024/10/02] **ExACT: Teaching AI Agents to Explore with Reflective-MCTS and Exploratory Learning** | [[paper]](https://arxiv.org/abs/2410.02052) | [code]

- [2024/09/09] **SciAgents: Automating scientific discovery through multi-agent intelligent graph reasoning** | [[paper]](https://arxiv.org/abs/2409.05556) | [code]

- [2024/07/01] **Tree Search for Language Model Agents** | [[paper]](https://arxiv.org/abs/2407.01476) | [code]

- [2024/06/17] **Input Conditioned Graph Generation for Language Agents** | [[paper]](https://arxiv.org/abs/2406.11555) | [[code]](https://github.com/lukasvierling/dynamicgptswarm)

- [2024/02/17] **KG-Agent: An Efficient Autonomous Agent Framework for Complex Reasoning over Knowledge Graph** | [[paper]](https://arxiv.org/abs/2402.11163) | [code]

- [2024/02/16] **When is Tree Search Useful for LLM Planning? It Depends on the Discriminator** | [[paper]](https://arxiv.org/abs/2402.10890) | [[code]](https://github.com/osu-nlp-group/llm-planning-eval)

- [2024/02/09] **CoSearchAgent: A Lightweight Collaborative Search Agent with Large Language Models** | [[paper]](https://arxiv.org/abs/2402.06360) | [code]

- [2023/05/17] **Tree of Thoughts: Deliberate Problem Solving with Large Language Models** | [[paper]](https://arxiv.org/abs/2305.10601) | [code]

### Interaction
#### Role Playing
- [2025/02/20] **InstructAgent: Building User Controllable Recommender via LLM Agent** | [[paper]](https://arxiv.org/abs/2502.14662) | [code]

- [2025/02/18] **SEFL: Harnessing Large Language Model Agents to Improve Educational Feedback Systems** | [[paper]](https://arxiv.org/abs/2502.12927) | [code]

- [2025/02/17] **Can LLM Agents Maintain a Persona in Discourse?** | [[paper]](https://arxiv.org/abs/2502.11843) | [code]

- [2025/02/17] **LM Agents for Coordinating Multi-User Information Gathering** | [[paper]](https://arxiv.org/abs/2502.12328) | [code]

- [2025/02/16] **SCALE: Towards Collaborative Content Analysis in Social Science with Large Language Model Agents and Human Intervention** | [[paper]](https://arxiv.org/abs/2502.10937) | [code]

- [2025/02/13] **Language Agents as Digital Representatives in Collective Decision-Making** | [[paper]](https://arxiv.org/abs/2502.09369) | [code]

- [2025/02/06] **PsyPlay: Personality-Infused Role-Playing Conversational Agents** | [[paper]](https://arxiv.org/abs/2502.03821) | [code]

- [2025/02/03] **Plan-Then-Execute: An Empirical Study of User Trust and Team Performance When Using LLM Agents As A Daily Assistant** | [[paper]](https://arxiv.org/abs/2502.01390) | [code]

- [2025/01/23] **AgentRec: Agent Recommendation Using Sentence Embeddings Aligned to Human Feedback** | [[paper]](https://arxiv.org/abs/2501.13333) | [code]

- [2025/01/15] **Personality Modeling for Persuasion of Misinformation using AI Agent** | [[paper]](https://arxiv.org/abs/2501.08985) | [code]

- [2024/12/28] **BaiJia: A Large-Scale Role-Playing Agent Corpus of Chinese Historical Characters** | [[paper]](https://arxiv.org/abs/2412.20024) | [code]

- [2024/12/22] **Modular Conversational Agents for Surveys and Interviews** | [[paper]](https://arxiv.org/abs/2412.17049) | [code]

- [2024/12/11] **SweetieChat: A Strategy-Enhanced Role-playing Framework for Diverse Scenarios Handling Emotional Support Agent** | [[paper]](https://arxiv.org/abs/2412.08389) | [code]

- [2024/12/10] **My Words Imply Your Opinion: Reader Agent-Based Propagation Enhancement for Personalized Implicit Emotion Analysis** | [[paper]](https://arxiv.org/abs/2412.07367) | [code]

- [2024/11/21] **Towards Full Delegation: Designing Ideal Agentic Behaviors for Travel Planning** | [[paper]](https://arxiv.org/abs/2411.13904) | [code]

- [2024/11/19] **Probing the Capacity of Language Model Agents to Operationalize Disparate Experiential Context Despite Distraction** | [[paper]](https://arxiv.org/abs/2411.12828) | [code]

- [2024/11/12] **SHARP: Unlocking Interactive Hallucination via Stance Transfer in Role-Playing Agents** | [[paper]](https://arxiv.org/abs/2411.07965) | [code]

- [2024/11/04] **A Multi-Task Role-Playing Agent Capable of Imitating Character Linguistic Styles** | [[paper]](https://arxiv.org/abs/2411.02457) | [code]

- [2024/10/28] **Guide-LLM: An Embodied LLM Agent and Text-Based Topological Map for Robotic Guidance of People with Visual Impairments** | [[paper]](https://arxiv.org/abs/2410.20666) | [code]

- [2024/10/24] **Schema-Guided Culture-Aware Complex Event Simulation with Multi-Agent Role-Play** | [[paper]](https://arxiv.org/abs/2410.18935) | [code]

- [2024/09/23] **ERABAL: Enhancing Role-Playing Agents through Boundary-Aware Learning** | [[paper]](https://arxiv.org/abs/2409.14710) | [code]

- [2024/09/19] **FoodPuzzle: Developing Large Language Model Agents as Flavor Scientists** | [[paper]](https://arxiv.org/abs/2409.12832) | [code]

- [2024/09/12] **TravelAgent: An AI Assistant for Personalized Travel Planning** | [[paper]](https://arxiv.org/abs/2409.08069) | [code]

- [2024/09/11] **Using Generative Agents to Create Tip Sheets for Investigative Data Reporting** | [[paper]](https://arxiv.org/abs/2409.07286) | [code]

- [2024/08/28] **Interactive Agents: Simulating Counselor-Client Psychological Counseling via Role-Playing LLM-to-LLM Interactions** | [[paper]](https://arxiv.org/abs/2408.15787) | [code]

- [2024/08/21] **Drama Engine: A Framework for Narrative Agents** | [[paper]](https://arxiv.org/abs/2408.11574) | [code]

- [2024/06/24] **The Effects of Embodiment and Personality Expression on Learning in LLM-based Educational Agents** | [[paper]](https://arxiv.org/abs/2407.10993) | [code]

- [2024/06/17] **HoLLMwood: Unleashing the Creativity of Large Language Models in Screenwriting via Role Playing** | [[paper]](https://arxiv.org/abs/2406.11683) | [code]

- [2024/06/11] **Agent-SiMT: Agent-assisted Simultaneous Machine Translation with Large Language Models** | [[paper]](https://arxiv.org/abs/2406.06910) | [code]

- [2024/06/09] **Peer Review as A Multi-Turn and Long-Context Dialogue with Role-Based Interactions** | [[paper]](https://arxiv.org/abs/2406.05688) | [[code]](https://github.com/chengtan9907/reviewmt)

- [2024/05/28] **TimeChara: Evaluating Point-in-Time Character Hallucination of Role-Playing Large Language Models** | [[paper]](https://arxiv.org/abs/2405.18027) | [code]

- [2024/05/10] **LLM Discussion: Enhancing the Creativity of Large Language Models via Discussion Framework and Role-Play** | [[paper]](https://arxiv.org/abs/2405.06373) | [code]

- [2024/05/08] **LLMs with Personalities in Multi-issue Negotiation Games** | [[paper]](https://arxiv.org/abs/2405.05248) | [code]

- [2024/05/06] **Large Language Models (LLMs) as Agents for Augmented Democracy** | [[paper]](https://arxiv.org/abs/2405.03452) | [code]

- [2024/05/02] **GAIA: A General AI Assistant for Intelligent Accelerator Operations** | [[paper]](https://arxiv.org/abs/2405.01359) | [code]

- [2024/05/01] **&#34;Ask Me Anything&#34;: How Comcast Uses LLMs to Assist Agents in Real Time** | [[paper]](https://arxiv.org/abs/2405.00801) | [code]

- [2024/04/26] **Large Language Model Agent as a Mechanical Designer** | [[paper]](https://arxiv.org/abs/2404.17525) | [code]

- [2024/04/19] **Cooperative Sentiment Agents for Multimodal Sentiment Analysis** | [[paper]](https://arxiv.org/abs/2404.12642) | [[code]](https://github.com/smwanghhh/co-sa)

- [2024/03/31] **DiffAgent: Fast and Accurate Text-to-Image API Selection with Large Language Model** | [[paper]](https://arxiv.org/abs/2404.01342) | [[code]](https://github.com/OpenGVLab/DiffAgent)

- [2024/03/23] **EduAgent: Generative Student Agents in Learning** | [[paper]](https://arxiv.org/abs/2404.07963) | [code]

- [2024/03/19] **Characteristic AI Agents via Large Language Models** | [[paper]](https://arxiv.org/abs/2403.12368) | [code]

- [2024/03/15] **VideoAgent: Long-form Video Understanding with Large Language Model as Agent** | [[paper]](https://arxiv.org/abs/2403.10517) | [code]

- [2024/03/13] **Evaluating Large Language Models as Generative User Simulators for Conversational Recommendation** | [[paper]](https://arxiv.org/abs/2403.09738) | [code]

- [2024/02/29] **On the Decision-Making Abilities in Role-Playing using Large Language Models** | [[paper]](https://arxiv.org/abs/2402.18807) | [code]

- [2024/02/28] **Prospect Personalized Recommendation on Large Language Model-based Agent Platform** | [[paper]](https://arxiv.org/abs/2402.18240) | [code]

- [2024/02/26] **Language Agents as Optimizable Graphs** | [[paper]](https://arxiv.org/abs/2402.16823) | [[code]](https://github.com/metauto-ai/gptswarm)

- [2024/02/22] **Triad: A Framework Leveraging a Multi-Role LLM-based Agent to Solve Knowledge Base Question Answering** | [[paper]](https://arxiv.org/abs/2402.14320) | [code]

- [2024/02/22] **Large Language Models as Urban Residents: An LLM Agent Framework for Personal Mobility Generation** | [[paper]](https://arxiv.org/abs/2402.14744) | [code]

- [2024/02/21] **Neeko: Leveraging Dynamic LoRA for Efficient Multi-Character Role-Playing Agent** | [[paper]](https://arxiv.org/abs/2402.13717) | [code]

- [2024/02/19] **Stick to your Role! Stability of Personal Values Expressed in Large Language Models** | [[paper]](https://arxiv.org/abs/2402.14846) | [code]

- [2024/02/18] **Modelling Political Coalition Negotiations Using LLM-based Agents** | [[paper]](https://arxiv.org/abs/2402.11712) | [code]

- [2024/02/06] **Professional Agents -- Evolving Large Language Models into Autonomous Experts with Human-Level Competencies** | [[paper]](https://arxiv.org/abs/2402.03628) | [code]

- [2024/02/06] **Can Generative Agents Predict Emotion?** | [[paper]](https://arxiv.org/abs/2402.04232) | [code]

- [2024/02/05] **GUARD: Role-playing to Generate Natural-language Jailbreakings to Test Guideline Adherence of Large Language Models** | [[paper]](https://arxiv.org/abs/2402.03299) | [code]

- [2024/01/31] **LLMs Simulate Big Five Personality Traits: Further Evidence** | [[paper]](https://arxiv.org/abs/2402.01765) | [code]

- [2023/12/22] **Personalized Large Language Model Assistant with Evolving Conditional Memory** | [[paper]](https://arxiv.org/abs/2312.17257) | [code]

- [2023/12/21] **ChatGPT as a commenter to the news: can LLMs generate human-like opinions?** | [[paper]](https://arxiv.org/abs/2312.13961) | [code]

- [2023/12/20] **Machine Mindset: An MBTI Exploration of Large Language Models** | [[paper]](https://arxiv.org/abs/2312.12999) | [code]

- [2023/12/19] **Can ChatGPT be Your Personal Medical Assistant?** | [[paper]](https://arxiv.org/abs/2312.12006) | [code]

- [2023/10/13] **AgentCF: Collaborative Learning with Autonomous Language Agents for Recommender Systems** | [[paper]](https://arxiv.org/abs/2310.09233) | [code]

- [2023/10/01] **RoleLLM: Benchmarking, Eliciting, and Enhancing Role-Playing Abilities of Large Language Models** | [[paper]](https://arxiv.org/abs/2310.00746) | [code]

- [2023/09/02] **ModelScope-Agent: Building Your Customizable Agent System with Open-source Large Language Models** | [[paper]](https://arxiv.org/abs/2309.00986) | [code]

- [2023/08/22] **Towards an On-device Agent for Text Rewriting** | [[paper]](https://arxiv.org/abs/2308.11807) | [code]

- [2023/08/10] **LLM As DBA** | [[paper]](https://arxiv.org/abs/2308.05481) | [code]

- [2023/08/03] **InterAct: Exploring the Potentials of ChatGPT as a Cooperative Agent** | [[paper]](https://arxiv.org/abs/2308.01552) | [code]

- [2023/07/11] **Unleashing the Emergent Cognitive Synergy in Large Language Models: A Task-Solving Agent through Multi-Persona Self-Collaboration** | [[paper]](https://arxiv.org/abs/2307.05300) | [code]

- [2023/07/05] **Building Cooperative Embodied Agents Modularly with Large Language Models** | [[paper]](https://arxiv.org/abs/2307.02485) | [code]

- [2023/05/25] **Role-Play with Large Language Models** | [[paper]](https://arxiv.org/abs/2305.16367) | [code]

- [2023/05/09] **TidyBot: Personalized Robot Assistance with Large Language Models** | [[paper]](https://arxiv.org/abs/2305.05658) | [code]

#### Conversation
- [2025/02/20] **Enhancing Conversational Agents with Theory of Mind: Aligning Beliefs, Desires, and Intentions for Human-Like Interaction** | [[paper]](https://arxiv.org/abs/2502.14171) | [code]

- [2025/02/18] **One Size doesn&#39;t Fit All: A Personalized Conversational Tutoring Agent for Mathematics Instruction** | [[paper]](https://arxiv.org/abs/2502.12633) | [code]

- [2025/02/18] **Training Turn-by-Turn Verifiers for Dialogue Tutoring Agents: The Curious Case of LLMs as Your Coding Tutors** | [[paper]](https://arxiv.org/abs/2502.13311) | [code]

- [2025/02/18] **You need to MIMIC to get FAME: Solving Meeting Transcript Scarcity with a Multi-Agent Conversations** | [[paper]](https://arxiv.org/abs/2502.13001) | [code]

- [2025/02/17] **InfoQuest: Evaluating Multi-Turn Dialogue Agents for Open-Ended Conversations with Hidden Context** | [[paper]](https://arxiv.org/abs/2502.12257) | [code]

- [2025/02/13] **Reliable Conversational Agents under ASP Control that Understand Natural Language** | [[paper]](https://arxiv.org/abs/2502.09237) | [code]

- [2025/02/12] **Can a Single Model Master Both Multi-turn Conversations and Tool Use? CoALM: A Unified Conversational Agentic Language Model** | [[paper]](https://arxiv.org/abs/2502.08820) | [code]

- [2025/02/09] **MTPChat: A Multimodal Time-Aware Persona Dataset for Conversational Agents** | [[paper]](https://arxiv.org/abs/2502.05887) | [code]

- [2025/02/09] **HamRaz: A Culture-Based Persian Conversation Dataset for Person-Centered Therapy Using LLM Agents** | [[paper]](https://arxiv.org/abs/2502.05982) | [code]

- [2025/02/08] **On Memory Construction and Retrieval for Personalized Conversational Agents** | [[paper]](https://arxiv.org/abs/2502.05589) | [code]

- [2025/02/06] **PsyPlay: Personality-Infused Role-Playing Conversational Agents** | [[paper]](https://arxiv.org/abs/2502.03821) | [code]

- [2025/01/24] **Unmasking Conversational Bias in AI Multiagent Systems** | [[paper]](https://arxiv.org/abs/2501.14844) | [code]

- [2025/01/23] **Communicating Activations Between Language Model Agents** | [[paper]](https://arxiv.org/abs/2501.14082) | [code]

- [2025/01/19] **IntellAgent: A Multi-Agent Framework for Evaluating Conversational AI Systems** | [[paper]](https://arxiv.org/abs/2501.11067) | [code]

- [2025/01/14] **Developing Enhanced Conversational Agents for Social Virtual Worlds** | [[paper]](https://arxiv.org/abs/2501.16341) | [code]

- [2025/01/03] **PSYCHE: A Multi-faceted Patient Simulation Framework for Evaluation of Psychiatric Assessment Conversational Agents** | [[paper]](https://arxiv.org/abs/2501.01594) | [code]

- [2024/12/30] **Exploring and Controlling Diversity in LLM-Agent Conversation** | [[paper]](https://arxiv.org/abs/2412.21102) | [code]

- [2024/12/24] **Extracting triples from dialogues for conversational social agents** | [[paper]](https://arxiv.org/abs/2412.18364) | [code]

- [2024/12/22] **Modular Conversational Agents for Surveys and Interviews** | [[paper]](https://arxiv.org/abs/2412.17049) | [code]

- [2024/12/21] **InfoTech Assistant : A Multimodal Conversational Agent for InfoTechnology Web Portal Queries** | [[paper]](https://arxiv.org/abs/2412.16412) | [code]

- [2024/12/13] **Script-Based Dialog Policy Planning for LLM-Powered Conversational Agents: A Basic Architecture for an &#34;AI Therapist&#34;** | [[paper]](https://arxiv.org/abs/2412.15242) | [code]

- [2024/12/06] **CALICO: Conversational Agent Localization via Synthetic Data Generation** | [[paper]](https://arxiv.org/abs/2412.05388) | [code]

- [2024/12/05] **Educational-Psychological Dialogue Robot Based on Multi-Agent Collaboration** | [[paper]](https://arxiv.org/abs/2412.03847) | [code]

- [2024/12/01] **Examining Identity Drift in Conversations of LLM Agents** | [[paper]](https://arxiv.org/abs/2412.00804) | [code]

- [2024/11/07] **Thanos: Enhancing Conversational Agents with Skill-of-Mind-Infused Large Language Model** | [[paper]](https://arxiv.org/abs/2411.04496) | [code]

- [2024/11/07] **Interactive Dialogue Agents via Reinforcement Learning on Hindsight Regenerations** | [[paper]](https://arxiv.org/abs/2411.05194) | [code]

- [2024/11/06] **MRJ-Agent: An Effective Jailbreak Agent for Multi-Round Dialogue** | [[paper]](https://arxiv.org/abs/2411.03814) | [code]

- [2024/11/01] **DARD: A Multi-Agent Approach for Task-Oriented Dialog Systems** | [[paper]](https://arxiv.org/abs/2411.00427) | [code]

- [2024/11/01] **ReSpAct: Harmonizing Reasoning, Speaking, and Acting Towards Building Large Language Model-Based Conversational AI Agents** | [[paper]](https://arxiv.org/abs/2411.00927) | [code]

- [2024/10/29] **MARCO: Multi-Agent Real-time Chat Orchestration** | [[paper]](https://arxiv.org/abs/2410.21784) | [code]

- [2024/10/25] **AGENT-CQ: Automatic Generation and Evaluation of Clarifying Questions for Conversational Search with LLMs** | [[paper]](https://arxiv.org/abs/2410.19692) | [code]

- [2024/10/18] **Coherence-Driven Multimodal Safety Dialogue with Active Learning for Embodied Agents** | [[paper]](https://arxiv.org/abs/2410.14141) | [code]

- [2024/10/15] **HR-Agent: A Task-Oriented Dialogue (TOD) LLM Agent Tailored for HR Applications** | [[paper]](https://arxiv.org/abs/2410.11239) | [code]

- [2024/10/10] **Rewriting Conversational Utterances with Instructed Large Language Models** | [[paper]](https://arxiv.org/abs/2410.07797) | [code]

- [2024/09/24] **Automated test generation to evaluate tool-augmented LLMs as conversational AI agents** | [[paper]](https://arxiv.org/abs/2409.15934) | [code]

- [2024/09/23] **Beyond Turn-Based Interfaces: Synchronous LLMs as Full-Duplex Dialogue Agents** | [[paper]](https://arxiv.org/abs/2409.15594) | [code]

- [2024/09/13] **AI-LieDar: Examine the Trade-off Between Utility and Truthfulness in LLM Agents** | [[paper]](https://arxiv.org/abs/2409.09013) | [code]

- [2024/09/06] **Sparse Rewards Can Self-Train Dialogue Agents** | [[paper]](https://arxiv.org/abs/2409.04617) | [code]

- [2024/09/02] **Co-Learning: Code Learning for Multi-Agent Reinforcement Collaborative Framework with Conversational Natural Language Interfaces** | [[paper]](https://arxiv.org/abs/2409.00985) | [code]

- [2024/08/27] **Into the Unknown Unknowns: Engaged Human Learning through Participation in Language Model Agent Conversations** | [[paper]](https://arxiv.org/abs/2408.15232) | [code]

- [2024/08/22] **MDD-5k: A New Diagnostic Conversation Dataset for Mental Disorders Synthesized via Neuro-Symbolic LLM Agents** | [[paper]](https://arxiv.org/abs/2408.12142) | [code]

- [2024/08/13] **What should I wear to a party in a Greek taverna? Evaluation for Conversational Agents in the Fashion Domain** | [[paper]](https://arxiv.org/abs/2408.08907) | [code]

- [2024/08/06] **OpenOmni: A Collaborative Open Source Tool for Building Future-Ready Multimodal Conversational Agents** | [[paper]](https://arxiv.org/abs/2408.03047) | [code]

- [2024/08/03] **Self-Emotion Blended Dialogue Generation in Social Simulation Agents** | [[paper]](https://arxiv.org/abs/2408.01633) | [code]

- [2024/07/31] **Towards Achieving Human Parity on End-to-end Simultaneous Speech Translation via LLM Agent** | [[paper]](https://arxiv.org/abs/2407.21646) | [code]

- [2024/07/13] **Cohesive Conversations: Enhancing Authenticity in Multi-Agent Simulated Dialogues** | [[paper]](https://arxiv.org/abs/2407.09897) | [code]

- [2024/07/04] **Controllable Conversations: Planning-Based Dialogue Agent with Large Language Models** | [[paper]](https://arxiv.org/abs/2407.03884) | [code]

- [2024/07/01] **Empathic Grounding: Explorations using Multimodal Interaction and Large Language Models with Conversational Agents** | [[paper]](https://arxiv.org/abs/2407.01824) | [code]

- [2024/06/30] **CAMON: Cooperative Agents for Multi-Object Navigation with LLM-based Conversations** | [[paper]](https://arxiv.org/abs/2407.00632) | [code]

- [2024/06/09] **Peer Review as A Multi-Turn and Long-Context Dialogue with Role-Based Interactions** | [[paper]](https://arxiv.org/abs/2406.05688) | [[code]](https://github.com/chengtan9907/reviewmt)

- [2024/05/29] **Toward Conversational Agents with Context and Time Sensitive Long-term Memory** | [[paper]](https://arxiv.org/abs/2406.00057) | [[code]](https://github.com/Zyphra/TemporalMemoryDataset)

- [2024/05/16] **Speaker Verification in Agent-Generated Conversations** | [[paper]](https://arxiv.org/abs/2405.10150) | [code]

- [2024/04/19] **Towards Human-centered Proactive Conversational Agents** | [[paper]](https://arxiv.org/abs/2404.12670) | [code]

- [2024/04/10] **Apollonion: Profile-centric Dialog Agent** | [[paper]](https://arxiv.org/abs/2404.08692) | [code]

- [2024/03/17] **Improving Dialogue Agents by Decomposing One Global Explicit Annotation with Local Implicit Multimodal Feedback** | [[paper]](https://arxiv.org/abs/2403.11330) | [code]

- [2024/03/08] **ChatASU: Evoking LLM&#39;s Reflexion to Truly Understand Aspect Sentiment in Dialogues** | [[paper]](https://arxiv.org/abs/2403.05326) | [code]

- [2024/02/25] **Understanding Public Perceptions of AI Conversational Agents: A Cross-Cultural Analysis** | [[paper]](https://arxiv.org/abs/2402.16039) | [code]

- [2024/02/23] **On the Multi-turn Instruction Following for Conversational Web Agents** | [[paper]](https://arxiv.org/abs/2402.15057) | [code]

- [2024/02/20] **CHATATC: Large Language Model-Driven Conversational Agents for Supporting Strategic Air Traffic Flow Management** | [[paper]](https://arxiv.org/abs/2402.14850) | [code]

- [2024/01/29] **Assistive Large Language Model Agents for Socially-Aware Negotiation Dialogues** | [[paper]](https://arxiv.org/abs/2402.01737) | [code]

- [2024/01/10] **Bootstrapping LLM-based Task-Oriented Dialogue Agents via Self-Talk** | [[paper]](https://arxiv.org/abs/2401.05033) | [code]

- [2024/01/02] **CharacterEval: A Chinese Benchmark for Role-Playing Conversational Agent Evaluation** | [[paper]](https://arxiv.org/abs/2401.01275) | [code]

- [2023/12/21] **Team Flow at DRC2023: Building Common Ground and Text-based Turn-taking in a Travel Agent Spoken Dialogue System** | [[paper]](https://arxiv.org/abs/2312.13816) | [code]

- [2023/11/15] **ToolTalk: Evaluating Tool-Usage in a Conversational Setting** | [[paper]](https://arxiv.org/abs/2311.10775) | [code]

- [2023/10/01] **Adapting LLM Agents Through Communication** | [[paper]](https://arxiv.org/abs/2310.01444v2) | [code]

- [2023/06/28] **Inferring the Goals of Communicating Agents from Actions and Instructions** | [[paper]](https://arxiv.org/abs/2306.16207) | [code]

- [2023/04/26] **Multi-Party Chat: Conversational Agents in Group Settings with Humans and Models** | [[paper]](https://arxiv.org/abs/2304.13835) | [code]

- [2023/03/31] **CAMEL: Communicative Agents for &#34;Mind&#34; Exploration of Large Language Model Society** | [[paper]](https://arxiv.org/abs/2303.17760) | [[code]](https://github.com/camel-ai/camel)

#### Game Playing
- [2025/02/01] **Who&#39;s the MVP? A Game-Theoretic Evaluation Benchmark for Modular Attribution in LLM Agents** | [[paper]](https://arxiv.org/abs/2502.00510) | [code]

- [2025/01/24] **Multi-agent KTO: Reinforcing Strategic Interactions of Large Language Model in Language Game** | [[paper]](https://arxiv.org/abs/2501.14225) | [code]

- [2024/12/06] **TeamCraft: A Benchmark for Multi-Modal Multi-Agent Systems in Minecraft** | [[paper]](https://arxiv.org/abs/2412.05255) | [code]

- [2024/11/08] **Game-theoretic LLM: Agent Workflow for Negotiation Games** | [[paper]](https://arxiv.org/abs/2411.05990) | [code]

- [2024/10/28] **Can Machines Think Like Humans? A Behavioral Evaluation of LLM-Agents in Dictator Games** | [[paper]](https://arxiv.org/abs/2410.21359) | [code]

- [2024/09/03] **An Implementation of Werewolf Agent That does not Truly Trust LLMs** | [[paper]](https://arxiv.org/abs/2409.01575) | [code]

- [2024/08/05] **Evaluating and Enhancing LLMs Agent based on Theory of Mind in Guandan: A Multi-Player Cooperative Game under Imperfect Information** | [[paper]](https://arxiv.org/abs/2408.02559) | [code]


---
### Environment&Platform
- [2025/02/14] **The Ann Arbor Architecture for Agent-Oriented Programming** | [[paper]](https://arxiv.org/abs/2502.09903) | [[code]](https://github.com/aaalgo/postline_0.1)

- [2024/06/06] **AgentGym: Evolving Large Language Model-based Agents across Diverse Environments** | [[paper]](https://arxiv.org/abs/2406.04151) | [[code]](https://github.com/woooodyy/agentgym)

- [2024/07/23] **AMONGAGENTS: Evaluating Large Language Models in the Interactive Text-Based Social Deduction Game** | [[paper]](https://arxiv.org/abs/2407.16521) | [code]

- [2024/07/17] **A LLM Benchmark based on the Minecraft Builder Dialog Agent Task** | [[paper]](https://arxiv.org/abs/2407.12734) | [code]

- [2024/06/27] **OmniJARVIS: Unified Vision-Language-Action Tokenization Enables Open-World Instruction Following Agents** | [[paper]](https://arxiv.org/abs/2407.00114) | [code]

- [2024/06/07] **GameBench: Evaluating Strategic Reasoning Abilities of LLM Agents** | [[paper]](https://arxiv.org/abs/2406.06613) | [[code]](https://github.com/Joshuaclymer/GameBench)

- [2024/06/05] **The Good, the Bad, and the Hulk-like GPT: Analyzing Emotional Decisions of Large Language Models in Cooperation and Bargaining Games** | [[paper]](https://arxiv.org/abs/2406.03299) | [code]

- [2024/05/24] **Hacc-Man: An Arcade Game for Jailbreaking LLMs** | [[paper]](https://arxiv.org/abs/2405.15902) | [code]

- [2024/05/23] **Human-Agent Cooperation in Games under Incomplete Information through Natural Language Communication** | [[paper]](https://arxiv.org/abs/2405.14173) | [code]

- [2024/05/08] **LLMs with Personalities in Multi-issue Negotiation Games** | [[paper]](https://arxiv.org/abs/2405.05248) | [code]

- [2024/04/30] **PANGeA: Procedural Artificial Narrative using Generative AI for Turn-Based Video Games** | [[paper]](https://arxiv.org/abs/2404.19721) | [code]

- [2024/04/03] **Learn to Disguise: Avoid Refusal Responses in LLM&#39;s Defense via a Multi-agent Attacker-Disguiser Game** | [[paper]](https://arxiv.org/abs/2404.02532) | [code]

- [2024/03/28] **MineLand: Simulating Large-Scale Multi-Agent Interactions with Limited Multimodal Senses and Physical Needs** | [[paper]](https://arxiv.org/abs/2403.19267) | [[code]](https://github.com/cocacola-lab/mineland)

- [2024/03/18] **How Far Are We on the Decision-Making of LLMs? Evaluating LLMs&#39; Gaming Ability in Multi-Agent Environments** | [[paper]](https://arxiv.org/abs/2403.11807) | [code]

- [2024/02/19] **PsychoGAT: A Novel Psychological Measurement Paradigm through Interactive Fiction Games with LLM Agents** | [[paper]](https://arxiv.org/abs/2402.12326) | [code]

- [2024/02/13] **Large Language Models as Minecraft Agents** | [[paper]](https://arxiv.org/abs/2402.08392) | [code]

- [2024/02/12] **Large Language Models as Agents in Two-Player Games** | [[paper]](https://arxiv.org/abs/2402.08078) | [code]

- [2024/02/04] **Enhance Reasoning for Large Language Models in the Game Werewolf** | [[paper]](https://arxiv.org/abs/2402.02330) | [code]

- [2024/02/02] **PokeLLMon: A Human-Parity Agent for Pokemon Battles with Large Language Models** | [[paper]](https://arxiv.org/abs/2402.01118) | [code]

- [2023/12/29] **Cooperation on the Fly: Exploring Language Agents for Ad Hoc Teamwork in the Avalon Game** | [[paper]](https://arxiv.org/abs/2312.17515) | [code]

- [2023/12/01] **Deciphering Digital Detectives: Understanding LLM Behaviors and Capabilities in Multi-Agent Mystery Games** | [[paper]](https://arxiv.org/abs/2312.00746) | [code]

- [2023/10/31] **Leveraging Word Guessing Games to Assess the Intelligence of Large Language Models** | [[paper]](https://arxiv.org/abs/2310.20499) | [code]

- [2023/09/29] **Suspicion-Agent: Playing Imperfect Information Games with Theory of Mind Aware GPT-4** | [[paper]](https://arxiv.org/abs/2309.17277) | [code]

- [2023/09/18] **MindAgent: Emergent Gaming Interaction** | [[paper]](https://arxiv.org/abs/2309.09971) | [[code]](https://mindagent.github.io/)

- [2023/09/10] **An Appraisal-Based Chain-Of-Emotion Architecture for Affective Language Model Game Agents** | [[paper]](https://arxiv.org/abs/2309.05076) | [code]

- [2023/09/09] **Exploring Large Language Models for Communication Games: An Empirical Study on Werewolf** | [[paper]](https://arxiv.org/abs/2309.04658) | [code]

- [2023/08/23] **Are ChatGPT and GPT-4 Good Poker Players? -- A Pre-Flop Analysis** | [[paper]](https://arxiv.org/abs/2308.12466) | [code]

- [2023/05/31] **Recursive Metropolis-Hastings Naming Game: Symbol Emergence in a Multi-agent System based on Probabilistic Generative Models** | [[paper]](https://arxiv.org/abs/2305.19761) | [code]

- [2023/05/26] **Playing repeated games with Large Language Models** | [[paper]](https://arxiv.org/abs/2305.16867) | [code]

- [2023/05/25] **Ghost in the Minecraft: Generally Capable Agents for Open-World Environments via Large Language Models with Text-based Knowledge and Memory** | [[paper]](https://arxiv.org/abs/2305.17144) | [code]

- [2023/05/08] **Knowledge-enhanced Agents for Interactive Text Games** | [[paper]](https://arxiv.org/abs/2305.05091) | [code]

- [2023/04/06] **Can Large Language Models Play Text Games Well? Current State-of-the-Art and Open Questions** | [[paper]](https://arxiv.org/abs/2304.02868) | [code]

#### Human-Agent Interaction
- [2025/02/17] **Leveraging Dual Process Theory in Language Agent Framework for Real-time Simultaneous Human-AI Collaboration** | [[paper]](https://arxiv.org/abs/2502.11882) | [code]

- [2025/01/28] **CowPilot: A Framework for Autonomous and Human-Agent Collaborative Web Navigation** | [[paper]](https://arxiv.org/abs/2501.16609) | [code]

- [2024/12/20] **Collaborative Gym: A Framework for Enabling and Evaluating Human-Agent Collaboration** | [[paper]](https://arxiv.org/abs/2412.15701) | [code]

- [2024/06/28] **Designing and Evaluating Multi-Chatbot Interface for Human-AI Communication: Preliminary Findings from a Persuasion Task** | [[paper]](https://arxiv.org/abs/2406.19648) | [code]

- [2024/06/11] **Towards Human-AI Collaboration in Healthcare: Guided Deferral Systems with Large Language Models** | [[paper]](https://arxiv.org/abs/2406.07212) | [code]

- [2024/06/02] **Towards a copilot in BIM authoring tool using a large language model-based agent for intelligent human-machine interaction** | [[paper]](https://arxiv.org/abs/2406.16903) | [code]

- [2024/03/05] **ChatCite: LLM Agent with Human Workflow Guidance for Comparative Literature Summary** | [[paper]](https://arxiv.org/abs/2403.02574) | [code]

- [2024/02/20] **Large Language Model-based Human-Agent Collaboration for Complex Task Solving** | [[paper]](https://arxiv.org/abs/2402.12914) | [code]

- [2024/02/18] **Shaping Human-AI Collaboration: Varied Scaffolding Levels in Co-writing with Language Models** | [[paper]](https://arxiv.org/abs/2402.11723) | [code]

- [2024/02/17] **MONAL: Model Autophagy Analysis for Modeling Human-AI Interactions** | [[paper]](https://arxiv.org/abs/2402.11271) | [code]

- [2023/09/22] **Learning to Coordinate with Anyone** | [[paper]](https://arxiv.org/abs/2309.12633) | [code]

- [2023/07/31] **HAGRID: A Human-LLM Collaborative Dataset for Generative Information-Seeking with Attribution** | [[paper]](https://arxiv.org/abs/2307.16883) | [code]

- [2023/04/26] **Multi-Party Chat: Conversational Agents in Group Settings with Humans and Models** | [[paper]](https://arxiv.org/abs/2304.13835) | [code]

#### Tool Usage
- [2025/02/17] **LLM Agents Making Agent Tools** | [[paper]](https://arxiv.org/abs/2502.11705) | [code]

- [2025/02/17] **SMART: Self-Aware Agent for Tool Overuse Mitigation** | [[paper]](https://arxiv.org/abs/2502.11435) | [code]

- [2025/02/16] **OctoTools: An Agentic Framework with Extensible Tools for Complex Reasoning** | [[paper]](https://arxiv.org/abs/2502.11271) | [code]

- [2025/02/12] **Can a Single Model Master Both Multi-turn Conversations and Tool Use? CoALM: A Unified Conversational Agentic Language Model** | [[paper]](https://arxiv.org/abs/2502.08820) | [code]

- [2025/02/07] **Agentic Reasoning: Reasoning LLMs with Tools for the Deep Research** | [[paper]](https://arxiv.org/abs/2502.04644) | [code]

- [2025/02/06] **Division-of-Thoughts: Harnessing Hybrid Language Model Synergy for Efficient On-Device Agents** | [[paper]](https://arxiv.org/abs/2502.04392) | [code]

- [2025/02/05] **ReachAgent: Enhancing Mobile Agent via Page Reaching and Operation** | [[paper]](https://arxiv.org/abs/2502.02955) | [code]

- [2025/01/28] **CowPilot: A Framework for Autonomous and Human-Agent Collaborative Web Navigation** | [[paper]](https://arxiv.org/abs/2501.16609) | [code]

- [2025/01/21] **UI-TARS: Pioneering Automated GUI Interaction with Native Agents** | [[paper]](https://arxiv.org/abs/2501.12326) | [code]

- [2025/01/20] **Mobile-Agent-E: Self-Evolving Mobile Assistant for Complex Tasks** | [[paper]](https://arxiv.org/abs/2501.11733) | [code]

- [2025/01/20] **PlotEdit: Natural Language-Driven Accessible Chart Editing in PDFs via Multimodal LLM Agents** | [[paper]](https://arxiv.org/abs/2501.11233) | [code]

- [2025/01/08] **InfiGUIAgent: A Multimodal Generalist GUI Agent with Native Reasoning and Reflection** | [[paper]](https://arxiv.org/abs/2501.04575) | [code]

- [2025/01/08] **FinSphere: A Conversational Stock Analysis Agent Equipped with Quantitative Tools based on Real-Time Database** | [[paper]](https://arxiv.org/abs/2501.12399) | [code]

- [2025/01/07] **PPTAgent: Generating and Evaluating Presentations Beyond Text-to-Slides** | [[paper]](https://arxiv.org/abs/2501.03936) | [code]

- [2024/12/28] **Efficient Multi-Agent Collaboration with Tool Use for Online Planning in Complex Table Question Answering** | [[paper]](https://arxiv.org/abs/2412.20145) | [code]

- [2024/12/21] **InfoTech Assistant : A Multimodal Conversational Agent for InfoTechnology Web Portal Queries** | [[paper]](https://arxiv.org/abs/2412.16412) | [code]

- [2024/12/12] **AgentTrek: Agent Trajectory Synthesis via Guiding Replay with Web Tutorials** | [[paper]](https://arxiv.org/abs/2412.09605) | [code]

- [2024/12/08] **Cooperative SQL Generation for Segmented Databases By Using Multi-functional LLM Agents** | [[paper]](https://arxiv.org/abs/2412.05850) | [code]

- [2024/12/05] **Aguvis: Unified Pure Vision Agents for Autonomous GUI Interaction** | [[paper]](https://arxiv.org/abs/2412.04454) | [code]

- [2024/11/26] **ShowUI: One Vision-Language-Action Model for GUI Visual Agent** | [[paper]](https://arxiv.org/abs/2411.17465) | [code]

- [2024/11/22] **ScribeAgent: Towards Specialized Web Agents Using Production-Scale Workflow Data** | [[paper]](https://arxiv.org/abs/2411.15004) | [code]

- [2024/11/20] **AdaptAgent: Adapting Multimodal Web Agents with Few-Shot Learning from Human Demonstrations** | [[paper]](https://arxiv.org/abs/2411.13451) | [code]

- [2024/11/15] **The Dawn of GUI Agent: A Preliminary Case Study with Claude 3.5 Computer Use** | [[paper]](https://arxiv.org/abs/2411.10323) | [code]

- [2024/11/04] **WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning** | [[paper]](https://arxiv.org/abs/2411.02337) | [code]

- [2024/11/04] **Attacking Vision-Language Computer Agents via Pop-ups** | [[paper]](https://arxiv.org/abs/2411.02391) | [code]

- [2024/11/02] **Infant Agent: A Tool-Integrated, Logic-Driven Agent with Cost-Effective API Usage** | [[paper]](https://arxiv.org/abs/2411.01114) | [code]

- [2024/10/28] **AutoGLM: Autonomous Foundation Agents for GUIs** | [[paper]](https://arxiv.org/abs/2411.00820) | [code]

- [2024/10/25] **OpenWebVoyager: Building Multimodal Web Agents via Iterative Real-World Exploration, Feedback and Optimization** | [[paper]](https://arxiv.org/abs/2410.19609) | [code]

- [2024/10/24] **Infogent: An Agent-Based Framework for Web Information Aggregation** | [[paper]](https://arxiv.org/abs/2410.19054) | [code]

- [2024/10/23] **ReflecTool: Towards Reflection-Aware Tool-Augmented Clinical Agents** | [[paper]](https://arxiv.org/abs/2410.17657) | [code]

- [2024/10/22] **Large Language Models Empowered Personalized Web Agents** | [[paper]](https://arxiv.org/abs/2410.17236) | [code]

- [2024/10/21] **VipAct: Visual-Perception Enhancement via Specialized VLM Agent Collaboration and Tool-use** | [[paper]](https://arxiv.org/abs/2410.16400) | [code]

- [2024/10/21] **Beyond Browsing: API-Based Web Agents** | [[paper]](https://arxiv.org/abs/2410.16464) | [code]

- [2024/10/18] **Toolshed: Scale Tool-Equipped Agents with Advanced RAG-Tool Fusion and Tool Knowledge Bases** | [[paper]](https://arxiv.org/abs/2410.14594) | [code]

- [2024/10/17] **Web Agents with World Models: Learning and Leveraging Environment Dynamics in Web Navigation** | [[paper]](https://arxiv.org/abs/2410.13232) | [code]

- [2024/10/17] **MeNTi: Bridging Medical Calculator and LLM Agent with Nested Tool Calling** | [[paper]](https://arxiv.org/abs/2410.13610) | [code]

- [2024/10/17] **MobA: A Two-Level Agent System for Efficient Mobile Task Automation** | [[paper]](https://arxiv.org/abs/2410.13757) | [code]

- [2024/10/17] **AgentOccam: A Simple Yet Strong Baseline for LLM-Based Web Agents** | [[paper]](https://arxiv.org/abs/2410.13825) | [code]

- [2024/10/16] **Agent Skill Acquisition for Large Language Models via CycleQD** | [[paper]](https://arxiv.org/abs/2410.14735) | [code]

- [2024/10/10] **Agent S: An Open Agentic Framework that Uses Computers Like a Human** | [[paper]](https://arxiv.org/abs/2410.08164) | [code]

- [2024/10/07] **Navigating the Digital World as Humans Do: Universal Visual Grounding for GUI Agents** | [[paper]](https://arxiv.org/abs/2410.05243) | [code]

- [2024/10/03] **NNetNav: Unsupervised Learning of Browser Agents Through Environment Interaction in the Wild** | [[paper]](https://arxiv.org/abs/2410.02907) | [code]

- [2024/09/24] **Automated test generation to evaluate tool-augmented LLMs as conversational AI agents** | [[paper]](https://arxiv.org/abs/2409.15934) | [code]

- [2024/09/17] **EIA: Environmental Injection Attack on Generalist Web Agents for Privacy Leakage** | [[paper]](https://arxiv.org/abs/2409.11295) | [code]

- [2024/09/01] **TinyAgent: Function Calling at the Edge** | [[paper]](https://arxiv.org/abs/2409.00608) | [code]

- [2024/08/30] **Tool-Assisted Agent on SQL Inspection and Refinement in Real-World Scenarios** | [[paper]](https://arxiv.org/abs/2408.16991) | [code]

- [2024/08/15] **VerilogCoder: Autonomous Verilog Coding Agents with Graph-based Planning and Abstract Syntax Tree (AST)-based Waveform Tracing Tool** | [[paper]](https://arxiv.org/abs/2408.08927) | [code]

- [2024/08/05] **Caution for the Environment: Multimodal Agents are Susceptible to Environmental Distractions** | [[paper]](https://arxiv.org/abs/2408.02544) | [code]

- [2024/08/01] **OmniParser for Pure Vision Based GUI Agent** | [[paper]](https://arxiv.org/abs/2408.00203) | [code]

- [2024/07/26] **AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents** | [[paper]](https://arxiv.org/abs/2407.18901) | [code]

- [2024/07/22] **AssistantBench: Can Web Agents Solve Realistic and Time-Consuming Tasks?** | [[paper]](https://arxiv.org/abs/2407.15711) | [code]

- [2024/07/11] **GTA: A Benchmark for General Tool Agents** | [[paper]](https://arxiv.org/abs/2407.08713) | [code]

- [2024/07/01] **Mobile-Bench: An Evaluation Benchmark for LLM-based Mobile Agents** | [[paper]](https://arxiv.org/abs/2407.00993) | [code]

- [2024/06/17] **GUICourse: From General Vision Language Models to Versatile GUI Agents** | [[paper]](https://arxiv.org/abs/2406.11317) | [[code]](https://github.com/yiye3/guicourse)

- [2024/06/16] **GUI-WORLD: A Dataset for GUI-oriented Multimodal LLM-based Agents** | [[paper]](https://arxiv.org/abs/2406.10819) | [code]

- [2024/06/06] **Tool-Planner: Task Planning with Clusters across Multiple Tools** | [[paper]](https://arxiv.org/abs/2406.03807) | [[code]](https://github.com/OceannTwT/Tool-Planner)

- [2024/06/03] **Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration** | [[paper]](https://arxiv.org/abs/2406.01014) | [[code]](https://github.com/x-plug/mobileagent)

- [2024/06/02] **Towards a copilot in BIM authoring tool using a large language model-based agent for intelligent human-machine interaction** | [[paper]](https://arxiv.org/abs/2406.16903) | [code]

- [2024/05/30] **Large Language Models Can Self-Improve At Web Agent Tasks** | [[paper]](https://arxiv.org/abs/2405.20309) | [code]

- [2024/05/17] **Latent State Estimation Helps UI Agents to Reason** | [[paper]](https://arxiv.org/abs/2405.11120) | [code]

- [2024/05/06] **SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering** | [[paper]](https://arxiv.org/abs/2405.15793) | [code]

- [2024/05/02] **CACTUS: Chemistry Agent Connecting Tool-Usage to Science** | [[paper]](https://arxiv.org/abs/2405.00972) | [[code]](https://github.com/pnnl/cactus)

- [2024/05/01] **Navigating WebAI: Training Agents to Complete Web Tasks with Large Language Models and Reinforcement Learning** | [[paper]](https://arxiv.org/abs/2405.00516) | [code]

- [2024/04/23] **Evaluating Tool-Augmented Agents in Remote Sensing Platforms** | [[paper]](https://arxiv.org/abs/2405.00709) | [code]

- [2024/04/17] **The Landscape of Emerging AI Agent Architectures for Reasoning, Planning, and Tool Calling: A Survey** | [[paper]](https://arxiv.org/abs/2404.11584) | [code]

- [2024/04/17] **Octopus v3: Technical Report for On-device Sub-billion Multimodal AI Agent** | [[paper]](https://arxiv.org/abs/2404.11459) | [code]

- [2024/04/16] **Grounded Language Agent for Product Search via Intelligent Web Interactions** | [[paper]](https://arxiv.org/abs/2404.10887) | [code]

- [2024/04/04] **AutoWebGLM: A Large Language Model-based Web Navigating Agent** | [[paper]](https://arxiv.org/abs/2404.03648) | [[code]](https://github.com/THUDM/AutoWebGLM)

- [2024/04/01] **Rapid Mobile App Development for Generative AI Agents on MIT App Inventor** | [[paper]](https://arxiv.org/abs/2405.01561) | [code]

- [2024/03/05] **InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated Large Language Model Agents** | [[paper]](https://arxiv.org/abs/2403.02691) | [code]

- [2024/03/05] **Android in the Zoo: Chain-of-Action-Thought for GUI Agents** | [[paper]](https://arxiv.org/abs/2403.02713) | [code]

- [2024/02/27] **BASES: Large-scale Web Search User Simulation with Large Language Model based Agents** | [[paper]](https://arxiv.org/abs/2402.17505) | [code]

- [2024/02/26] **Look Before You Leap: Towards Decision-Aware and Generalizable Tool-Usage for Large Language Models** | [[paper]](https://arxiv.org/abs/2402.16696) | [code]

- [2024/02/23] **On the Multi-turn Instruction Following for Conversational Web Agents** | [[paper]](https://arxiv.org/abs/2402.15057) | [code]

- [2024/02/20] **AgentMD: Empowering Language Agents for Risk Prediction with Large-Scale Clinical Tool Learning** | [[paper]](https://arxiv.org/abs/2402.13225) | [code]

- [2024/02/18] **SciAgent: Tool-augmented Language Models for Scientific Reasoning** | [[paper]](https://arxiv.org/abs/2402.11451) | [code]

- [2024/02/16] **ToolSword: Unveiling Safety Issues of Large Language Models in Tool Learning Across Three Stages** | [[paper]](https://arxiv.org/abs/2402.10753) | [[code]](https://github.com/junjie-ye/toolsword)

- [2024/02/08] **UFO: A UI-Focused Agent for Windows OS Interaction** | [[paper]](https://arxiv.org/abs/2402.07939) | [code]

- [2024/02/06] **AnyTool: Self-Reflective, Hierarchical Agents for Large-Scale API Calls** | [[paper]](https://arxiv.org/abs/2402.04253) | [[code]](https://github.com/dyabel/anytool)

- [2024/01/11] **EASYTOOL: Enhancing LLM-based Agents with Concise Tool Instruction** | [[paper]](https://arxiv.org/abs/2401.06201) | [code]

- [2024/01/03] **GPT-4V(ision) is a Generalist Web Agent, if Grounded** | [[paper]](https://arxiv.org/abs/2401.01614) | [code]

- [2023/12/21] **AppAgent: Multimodal Agents as Smartphone Users** | [[paper]](https://arxiv.org/abs/2312.13771) | [code]

- [2023/12/18] **CLOVA: A Closed-Loop Visual Assistant with Tool Usage and Update** | [[paper]](https://arxiv.org/abs/2312.10908) | [[code]](https://clova-tool.github.io/)

- [2023/12/14] **CogAgent: A Visual Language Model for GUI Agents** | [[paper]](https://arxiv.org/abs/2312.08914) | [code]

- [2023/11/19] **TPTU-v2: Boosting Task Planning and Tool Usage of Large Language Model-based Agents in Real-world Systems** | [[paper]](https://arxiv.org/abs/2311.11315) | [code]

- [2023/11/15] **ToolTalk: Evaluating Tool-Usage in a Conversational Setting** | [[paper]](https://arxiv.org/abs/2311.10775) | [code]

- [2023/11/10] **Smart Agent-Based Modeling: On the Use of Large Language Models in Computer Simulations** | [[paper]](https://arxiv.org/abs/2311.06330) | [code]

- [2023/10/12] **A Zero-Shot Language Agent for Computer Control with Structured Reflection** | [[paper]](https://arxiv.org/abs/2310.08740) | [code]

- [2023/08/07] **TPTU: Large Language Model-based AI Agents for Task Planning and Tool Usage** | [[paper]](https://arxiv.org/abs/2308.03427) | [code]

- [2023/06/09] **Mind2Web: Towards a Generalist Agent for the Web** | [[paper]](https://arxiv.org/abs/2306.06070) | [code]

- [2023/05/22] **Making Language Models Better Tool Learners with Execution Feedback** | [[paper]](https://arxiv.org/abs/2305.13068) | [code]

- [2023/05/19] **ToolkenGPT: Augmenting Frozen Language Models with Massive Tools via Tool Embeddings** | [[paper]](https://arxiv.org/abs/2305.11554) | [code]

#### Simulation
- [2025/02/06] **Simulating the Emergence of Differential Case Marking with Communicating Neural-Network Agents** | [[paper]](https://arxiv.org/abs/2502.04038) | [code]

- [2025/02/03] **Eliciting Language Model Behaviors with Investigator Agents** | [[paper]](https://arxiv.org/abs/2502.01236) | [code]

- [2025/01/25] **Are Human Interactions Replicable by Generative Agents? A Case Study on Pronoun Usage in Hierarchical Interactions** | [[paper]](https://arxiv.org/abs/2501.15283) | [code]

- [2025/01/19] **Self-Explanation in Social AI Agents** | [[paper]](https://arxiv.org/abs/2501.13945) | [code]

- [2025/01/12] **LLMs Model Non-WEIRD Populations: Experiments with Synthetic Cultural Agents** | [[paper]](https://arxiv.org/abs/2501.06834) | [code]

- [2024/12/10] **Political Actor Agent: Simulating Legislative System for Roll Call Votes Prediction with Large Language Models** | [[paper]](https://arxiv.org/abs/2412.07144) | [code]

- [2024/11/18] **OASIS: Open Agent Social Interaction Simulations with One Million Agents** | [[paper]](https://arxiv.org/abs/2411.11581) | [code]

- [2024/10/28] **ElectionSim: Massive Population Election Simulation Powered by Large Language Model Driven Agents** | [[paper]](https://arxiv.org/abs/2410.20746) | [code]

- [2024/10/24] **Schema-Guided Culture-Aware Complex Event Simulation with Multi-Agent Role-Play** | [[paper]](https://arxiv.org/abs/2410.18935) | [code]

- [2024/10/18] **SRAP-Agent: Simulating and Optimizing Scarce Resource Allocation Policy with LLM-based Agent** | [[paper]](https://arxiv.org/abs/2410.14152) | [code]

- [2024/10/05] **Large Language Models can Achieve Social Balance** | [[paper]](https://arxiv.org/abs/2410.04054) | [code]

- [2024/09/25] **Plurals: A System for Guiding LLMs Via Simulated Social Ensembles** | [[paper]](https://arxiv.org/abs/2409.17213) | [code]

- [2024/09/14] **Synergistic Simulations: Multi-Agent Problem Solving with Large Language Models** | [[paper]](https://arxiv.org/abs/2409.13753) | [code]

- [2024/09/02] **Agentic Society: Merging skeleton from real world and texture from Large Language Model** | [[paper]](https://arxiv.org/abs/2409.10550) | [code]

- [2024/08/28] **Logic-Enhanced Language Model Agents for Trustworthy Social Simulations** | [[paper]](https://arxiv.org/abs/2408.16081) | [code]

- [2024/08/15] **AgentCourt: Simulating Court with Adversarial Evolvable Lawyer Agents** | [[paper]](https://arxiv.org/abs/2408.08089) | [code]

- [2024/08/03] **Self-Emotion Blended Dialogue Generation in Social Simulation Agents** | [[paper]](https://arxiv.org/abs/2408.01633) | [code]

- [2024/06/26] **Simulating The U.S. Senate: An LLM-Driven Agent Approach to Modeling Legislative Behavior and Bipartisanship** | [[paper]](https://arxiv.org/abs/2406.18702) | [code]

- [2024/06/20] **Artificial Leviathan: Exploring Social Evolution of LLM Agents Through the Lens of Hobbesian Social Contract Theory** | [[paper]](https://arxiv.org/abs/2406.14373) | [code]

- [2024/06/10] **Can Language Models Serve as Text-Based World Simulators?** | [[paper]](https://arxiv.org/abs/2406.06485) | [code]

- [2024/05/12] **Exploring the Potential of Conversational AI Support for Agent-Based Social Simulation Model Design** | [[paper]](https://arxiv.org/abs/2405.08032) | [code]

- [2024/04/23] **BattleAgent: Multi-modal Dynamic Emulation on Historical Battles to Complement Historical Analysis** | [[paper]](https://arxiv.org/abs/2404.15532) | [[code]](https://github.com/agiresearch/battleagent)

- [2024/03/20] **AgentGroupChat: An Interactive Group Chat Simulacra For Better Eliciting Emergent Behavior** | [[paper]](https://arxiv.org/abs/2403.13433) | [code]

- [2024/03/05] **AgentsCourt: Building Judicial Decision-Making Agents with Court Debate Simulation and Legal Knowledge Augmentation** | [[paper]](https://arxiv.org/abs/2403.02959) | [code]

- [2024/02/26] **Unveiling the Truth and Facilitating Change: Towards Agent-based Large-scale Social Movement Simulation** | [[paper]](https://arxiv.org/abs/2402.16333) | [code]

- [2024/02/20] **What if LLMs Have Different World Views: Simulating Alien Civilizations with LLM-based Agents** | [[paper]](https://arxiv.org/abs/2402.13184) | [code]

- [2024/02/07] **Can Large Language Model Agents Simulate Human Trust Behavior?** | [[paper]](https://arxiv.org/abs/2402.04559) | [code]

- [2024/01/08] **SpeechAgents: Human-Communication Simulation with Multi-Modal Multi-Agent Systems** | [[paper]](https://arxiv.org/abs/2401.03945) | [code]

- [2023/12/06] **LLM as OS, Agents as Apps: Envisioning AIOS, Agents and the AIOS-Agent Ecosystem** | [[paper]](https://arxiv.org/abs/2312.03815) | [code]

- [2023/11/28] **War and Peace (WarAgent): Large Language Model-based Multi-Agent Simulation of World Wars** | [[paper]](https://arxiv.org/abs/2311.17227) | [code]

- [2023/10/10] **MetaAgents: Simulating Interactions of Human Behaviors for LLM-based Task-oriented Coordination via Collaborative Generative Agents** | [[paper]](https://arxiv.org/abs/2310.06500) | [code]

- [2023/06/05] **User Behavior Simulation with Large Language Model based Agents** | [[paper]](https://arxiv.org/abs/2306.02552) | [code]

- [2023/05/26] **Training Socially Aligned Language Models on Simulated Social Interactions** | [[paper]](https://arxiv.org/abs/2305.16960) | [code]

- [2023/04/07] **Generative Agents: Interactive Simulacra of Human Behavior** | [[paper]](https://arxiv.org/abs/2304.03442) | [code]

### Application
#### Math
- [2025/02/18] **One Size doesn&#39;t Fit All: A Personalized Conversational Tutoring Agent for Mathematics Instruction** | [[paper]](https://arxiv.org/abs/2502.12633) | [code]

- [2024/10/29] **Flow-DPO: Improving LLM Mathematical Reasoning through Online Multi-Agent Learning** | [[paper]](https://arxiv.org/abs/2410.22304) | [code]

- [2024/10/13] **Expanding Search Space with Diverse Prompting Agents: An Efficient Sampling Approach for LLM Mathematical Reasoning** | [[paper]](https://arxiv.org/abs/2410.09780) | [code]

- [2024/08/03] **MathLearner: A Large Language Model Agent Framework for Learning to Solve Mathematical Problems** | [[paper]](https://arxiv.org/abs/2408.01779) | [code]

- [2024/04/10] **MathVC: An LLM-Simulated Multi-Character Virtual Classroom for Mathematics Education** | [[paper]](https://arxiv.org/abs/2404.06711) | [code]

- [2024/04/06] **MACM: Utilizing a Multi-Agent System for Condition Mining in Solving Complex Mathematical Problems** | [[paper]](https://arxiv.org/abs/2404.04735) | [[code]](https://github.com/bin123apple/macm)

#### Chemistry
- [2025/01/23] **Hypothesis Generation for Materials Discovery and Design Using Goal-Driven and Constraint-Guided LLM Agents** | [[paper]](https://arxiv.org/abs/2501.13299) | [code]

- [2025/01/11] **ChemAgent: Self-updating Library in Large Language Models Improves Chemical Reasoning** | [[paper]](https://arxiv.org/abs/2501.06590) | [code]

- [2024/08/29] **HoneyComb: A Flexible LLM-Based Agent System for Materials Science** | [[paper]](https://arxiv.org/abs/2409.00135) | [code]

- [2024/06/26] **A Review of Large Language Models and Autonomous Agents in Chemistry** | [[paper]](https://arxiv.org/abs/2407.01603) | [code]

#### Biology
- [2024/10/16] **PRefLexOR: Preference-based Recursive Language Modeling for Exploratory Optimization of Reasoning and Agentic Thinking** | [[paper]](https://arxiv.org/abs/2410.12375) | [code]

- [2024/06/29] **BioKGBench: A Knowledge Graph Checking Benchmark of AI Agent for Biomedical Science** | [[paper]](https://arxiv.org/abs/2407.00466) | [code]

- [2024/05/25] **GeneAgent: Self-verification Language Agent for Gene Set Knowledge Discovery using Domain Databases** | [[paper]](https://arxiv.org/abs/2405.16205) | [code]

- [2024/04/27] **CRISPR-GPT: An LLM Agent for Automated Design of Gene-Editing Experiments** | [[paper]](https://arxiv.org/abs/2404.18021) | [code]

- [2024/04/03] **Empowering Biomedical Discovery with AI Agents** | [[paper]](https://arxiv.org/abs/2404.02831) | [code]

- [2024/01/27] **ProtAgents: Protein discovery via large language model multi-agent collaborations combining physics and machine learning** | [[paper]](https://arxiv.org/abs/2402.04268) | [code]

#### Physics
- [2025/01/23] **Hypothesis Generation for Materials Discovery and Design Using Goal-Driven and Constraint-Guided LLM Agents** | [[paper]](https://arxiv.org/abs/2501.13299) | [code]

- [2024/12/09] **StarWhisper Telescope: Agent-Based Observation Assistant System to Approach AI Astrophysicist** | [[paper]](https://arxiv.org/abs/2412.06412) | [code]

- [2024/08/29] **HoneyComb: A Flexible LLM-Based Agent System for Materials Science** | [[paper]](https://arxiv.org/abs/2409.00135) | [code]

- [2024/01/27] **ProtAgents: Protein discovery via large language model multi-agent collaborations combining physics and machine learning** | [[paper]](https://arxiv.org/abs/2402.04268) | [code]

#### Geography
- [2024/12/23] **MineAgent: Towards Remote-Sensing Mineral Exploration with Multimodal Large Language Models** | [[paper]](https://arxiv.org/abs/2412.17339) | [code]

- [2024/07/13] **An Autonomous GIS Agent Framework for Geospatial Data Retrieval** | [[paper]](https://arxiv.org/abs/2407.21024) | [code]

#### Art
- [2025/01/22] **FilmAgent: A Multi-Agent Framework for End-to-End Film Automation in Virtual 3D Spaces** | [[paper]](https://arxiv.org/abs/2501.12909) | [code]

- [2024/10/02] **Agent-Driven Large Language Models for Mandarin Lyric Generation** | [[paper]](https://arxiv.org/abs/2410.01450) | [code]

- [2024/09/05] **LLM-based multi-agent poetry generation in non-cooperative environments** | [[paper]](https://arxiv.org/abs/2409.03659) | [code]

- [2024/08/13] **What should I wear to a party in a Greek taverna? Evaluation for Conversational Agents in the Fashion Domain** | [[paper]](https://arxiv.org/abs/2408.08907) | [code]

- [2024/07/01] **IBSEN: Director-Actor Agent Collaboration for Controllable and Interactive Drama Script Generation** | [[paper]](https://arxiv.org/abs/2407.01093) | [code]

- [2024/04/28] **ComposerX: Multi-Agent Symbolic Music Composition with LLMs** | [[paper]](https://arxiv.org/abs/2404.18081) | [[code]](https://github.com/lllindsey0615/composerx)

- [2024/03/12] **AesopAgent: Agent-driven Evolutionary System on Story-to-Video Production** | [[paper]](https://arxiv.org/abs/2403.07952) | [code]

- [2023/10/18] **MusicAgent: An AI Agent for Music Understanding and Generation with Large Language Models** | [[paper]](https://arxiv.org/abs/2310.11954) | [code]

#### Medicine
- [2025/02/19] **LIDDIA: Language-based Intelligent Drug Discovery Agent** | [[paper]](https://arxiv.org/abs/2502.13959) | [code]

- [2025/02/18] **An LLM-Powered Agent for Physiological Data Analysis: A Case Study on PPG-based Heart Rate Estimation** | [[paper]](https://arxiv.org/abs/2502.12836) | [code]

- [2025/02/18] **Sleepless Nights, Sugary Days: Creating Synthetic Users with Health Conditions for Realistic Coaching Agent Interactions** | [[paper]](https://arxiv.org/abs/2502.13135) | [code]

- [2025/02/13] **PathFinder: A Multi-Modal Multi-Agent System for Medical Diagnostic Decision-Making Applied to Histopathology** | [[paper]](https://arxiv.org/abs/2502.08916) | [code]

- [2025/02/09] **HamRaz: A Culture-Based Persian Conversation Dataset for Person-Centered Therapy Using LLM Agents** | [[paper]](https://arxiv.org/abs/2502.05982) | [code]

- [2025/02/05] **CAMI: A Counselor Agent Supporting Motivational Interviewing through State Inference and Topic Exploration** | [[paper]](https://arxiv.org/abs/2502.02807) | [code]

- [2025/02/02] **Agent-Based Uncertainty Awareness Improves Automated Radiology Report Labeling with an Open-Source Large Language Model** | [[paper]](https://arxiv.org/abs/2502.01691) | [code]

- [2025/01/27] **MADP: Multi-Agent Deductive Planning for Enhanced Cognitive-Behavioral Mental Health Question Answer** | [[paper]](https://arxiv.org/abs/2501.15826) | [code]

- [2025/01/16] **AutoCBT: An Autonomous Multi-agent Framework for Cognitive Behavioral Therapy in Psychological Counseling** | [[paper]](https://arxiv.org/abs/2501.09426) | [code]

- [2025/01/03] **PSYCHE: A Multi-faceted Patient Simulation Framework for Evaluation of Psychiatric Assessment Conversational Agents** | [[paper]](https://arxiv.org/abs/2501.01594) | [code]

- [2024/12/19] **PsyDraw: A Multi-Agent Multimodal System for Mental Health Screening in Left-Behind Children** | [[paper]](https://arxiv.org/abs/2412.14769) | [code]

- [2024/12/17] **RareAgents: Advancing Rare Disease Care through LLM-Empowered Multi-disciplinary Team** | [[paper]](https://arxiv.org/abs/2412.12475) | [code]

- [2024/12/16] **LLMs Can Simulate Standardized Patients via Agent Coevolution** | [[paper]](https://arxiv.org/abs/2412.11716) | [code]

- [2024/12/13] **Script-Based Dialog Policy Planning for LLM-Powered Conversational Agents: A Basic Architecture for an &#34;AI Therapist&#34;** | [[paper]](https://arxiv.org/abs/2412.15242) | [code]

- [2024/12/05] **Educational-Psychological Dialogue Robot Based on Multi-Agent Collaboration** | [[paper]](https://arxiv.org/abs/2412.03847) | [code]

- [2024/12/02] **Medchain: Bridging the Gap Between LLM Agents and Clinical Practice through Interactive Sequential Benchmarking** | [[paper]](https://arxiv.org/abs/2412.01605) | [code]

- [2024/11/21] **PIORS: Personalized Intelligent Outpatient Reception based on Large Language Model with Multi-Agents Medical Scenario Simulation** | [[paper]](https://arxiv.org/abs/2411.13902) | [code]

- [2024/11/16] **Towards Next-Generation Medical Agent: How o1 is Reshaping Decision-Making in Medical Scenarios** | [[paper]](https://arxiv.org/abs/2411.14461) | [code]

- [2024/11/03] **EcoAct: Economic Agent Determines When to Register What Action** | [[paper]](https://arxiv.org/abs/2411.01643) | [code]

- [2024/10/25] **$\texttt{PatentAgent}$: Intelligent Agent for Automated Pharmaceutical Patent Analysis** | [[paper]](https://arxiv.org/abs/2410.21312) | [code]

- [2024/10/23] **ReflecTool: Towards Reflection-Aware Tool-Augmented Clinical Agents** | [[paper]](https://arxiv.org/abs/2410.17657) | [code]

- [2024/10/17] **MeNTi: Bridging Medical Calculator and LLM Agent with Nested Tool Calling** | [[paper]](https://arxiv.org/abs/2410.13610) | [code]

- [2024/10/16] **MedAide: Towards an Omni Medical Aide via Specialized LLM-based Multi-Agent Collaboration** | [[paper]](https://arxiv.org/abs/2410.12532) | [code]

- [2024/10/02] **Zodiac: A Cardiologist-Level LLM Framework for Multi-Agent Diagnostics** | [[paper]](https://arxiv.org/abs/2410.02026) | [code]

- [2024/08/28] **Interactive Agents: Simulating Counselor-Client Psychological Counseling via Role-Playing LLM-to-LLM Interactions** | [[paper]](https://arxiv.org/abs/2408.15787) | [code]

- [2024/08/23] **DrugAgent: Explainable Drug Repurposing Agent with Large Language Model-based Reasoning** | [[paper]](https://arxiv.org/abs/2408.13378) | [code]

- [2024/08/14] **Development of a Large Language Model-based Multi-Agent Clinical Decision Support System for Korean Triage and Acuity Scale (KTAS)-Based Triage and Treatment Planning in Emergency Departments** | [[paper]](https://arxiv.org/abs/2408.07531) | [code]

- [2024/07/18] **CoD, Towards an Interpretable Medical Agent using Chain of Diagnosis** | [[paper]](https://arxiv.org/abs/2407.13301) | [code]

- [2024/07/10] **Virtual Agents for Alcohol Use Counseling: Exploring LLM-Powered Motivational Interviewing** | [[paper]](https://arxiv.org/abs/2407.08095) | [code]

- [2024/07/03] **MentalAgora: A Gateway to Advanced Personalized Care in Mental Health through Multi-Agent Debating and Attribute Control** | [[paper]](https://arxiv.org/abs/2407.02736) | [code]

- [2024/07/02] **MMedAgent: Learning to Use Medical Tools with Multi-modal Agent** | [[paper]](https://arxiv.org/abs/2407.02483) | [code]

- [2024/04/03] **Empowering Biomedical Discovery with AI Agents** | [[paper]](https://arxiv.org/abs/2404.02831) | [code]

- [2024/02/20] **Can Large Language Models be Used to Provide Psychological Counselling? An Analysis of GPT-4-Generated Responses Using Role-play Dialogues** | [[paper]](https://arxiv.org/abs/2402.12738) | [code]

- [2024/02/20] **AgentMD: Empowering Language Agents for Risk Prediction with Large-Scale Clinical Tool Learning** | [[paper]](https://arxiv.org/abs/2402.13225) | [code]

- [2024/02/15] **Knowledge-Infused LLM-Powered Conversational Health Agent: A Case Study for Diabetes Patients** | [[paper]](https://arxiv.org/abs/2402.10153) | [code]

- [2024/02/01] **Generation, Distillation and Evaluation of Motivational Interviewing-Style Reflections with a Foundational Language Model** | [[paper]](https://arxiv.org/abs/2402.01051) | [code]

- [2023/12/19] **Can ChatGPT be Your Personal Medical Assistant?** | [[paper]](https://arxiv.org/abs/2312.12006) | [code]

- [2023/10/03] **Exploring Collaboration Mechanisms for LLM Agents: A Social Psychology View** | [[paper]](https://arxiv.org/abs/2310.02124) | [code]

#### Finance
- [2025/02/08] **Agentic AI Systems Applied to tasks in Financial Services: Modeling and model risk management crews** | [[paper]](https://arxiv.org/abs/2502.05439) | [code]

- [2025/02/01] **MarketSenseAI 2.0: Enhancing Stock Analysis through LLM Agents** | [[paper]](https://arxiv.org/abs/2502.00415) | [code]

- [2025/01/08] **FinSphere: A Conversational Stock Analysis Agent Equipped with Quantitative Tools based on Real-Time Database** | [[paper]](https://arxiv.org/abs/2501.12399) | [code]

- [2024/12/27] **OS-Genesis: Automating GUI Agent Trajectory Construction via Reverse Task Synthesis** | [[paper]](https://arxiv.org/abs/2412.19723) | [code]

- [2024/12/19] **Beyond the Sum: Unlocking AI Agents Potential Through Market Forces** | [[paper]](https://arxiv.org/abs/2501.10388) | [code]

- [2024/11/07] **Enhancing Investment Analysis: Optimizing AI-Agent Collaboration in Financial Research** | [[paper]](https://arxiv.org/abs/2411.04788) | [code]

- [2024/10/29] **Enhancing Financial Question Answering with a Multi-Agent Reflection Framework** | [[paper]](https://arxiv.org/abs/2410.21741) | [code]

- [2024/09/19] **Strategic Collusion of LLM Agents: Market Division in Multi-Commodity Competitions** | [[paper]](https://arxiv.org/abs/2410.00031) | [code]

- [2024/07/18] **dzFinNlp at AraFinNLP: Improving Intent Detection in Financial Conversational Agents** | [[paper]](https://arxiv.org/abs/2407.13565) | [code]

- [2024/07/09] **FinCon: A Synthesized LLM Multi-Agent System with Conceptual Verbal Reinforcement for Enhanced Financial Decision Making** | [[paper]](https://arxiv.org/abs/2407.06567) | [code]

- [2024/07/05] **Towards Automated Functional Equation Proving: A Benchmark Dataset and A Domain-Specific In-Context Agent** | [[paper]](https://arxiv.org/abs/2407.14521) | [code]

- [2024/05/07] **Enhancing the Efficiency and Accuracy of Underlying Asset Reviews in Structured Finance: The Application of Multi-agent Framework** | [[paper]](https://arxiv.org/abs/2405.04294) | [code]

#### Software Engineering
- [2025/02/19] **An LLM-based Agent for Reliable Docker Environment Configuration** | [[paper]](https://arxiv.org/abs/2502.13681) | [code]

- [2025/02/18] **Training Turn-by-Turn Verifiers for Dialogue Tutoring Agents: The Curious Case of LLMs as Your Coding Tutors** | [[paper]](https://arxiv.org/abs/2502.13311) | [code]

- [2025/02/18] **UXAgent: An LLM Agent-Based Usability Testing Framework for Web Design** | [[paper]](https://arxiv.org/abs/2502.12561) | [code]

- [2025/02/11] **Multi-Agent Collaboration for Multilingual Code Instruction Tuning** | [[paper]](https://arxiv.org/abs/2502.07487) | [code]

- [2025/02/10] **SyncMind: Measuring Agent Out-of-Sync Recovery in Collaborative Software Engineering** | [[paper]](https://arxiv.org/abs/2502.06994) | [code]

- [2025/02/08] **CODESIM: Multi-Agent Code Generation and Problem Solving through Simulation-Driven Planning and Debugging** | [[paper]](https://arxiv.org/abs/2502.05664) | [code]

- [2024/12/30] **Training Software Engineering Agents and Verifiers with SWE-Gym** | [[paper]](https://arxiv.org/abs/2412.21139) | [code]

- [2024/12/24] **Molly: Making Large Language Model Agents Solve Python Problem More Logically** | [[paper]](https://arxiv.org/abs/2412.18093) | [code]

- [2024/12/16] **Seeker: Towards Exception Safety Code Generation with Intermediate Language Agents Framework** | [[paper]](https://arxiv.org/abs/2412.11713) | [code]

- [2024/11/07] **CodeTree: Agent-guided Tree Search for Code Generation with Large Language Models** | [[paper]](https://arxiv.org/abs/2411.04329) | [code]

- [2024/10/29] **SceneGenAgent: Precise Industrial Scene Generation with Coding Agent** | [[paper]](https://arxiv.org/abs/2410.21909) | [code]

- [2024/10/09] **DA-Code: Agent Data Science Code Generation Benchmark for Large Language Models** | [[paper]](https://arxiv.org/abs/2410.07331) | [code]

- [2024/10/09] **Seeker: Enhancing Exception Handling in Code with LLM-based Multi-Agent Approach** | [[paper]](https://arxiv.org/abs/2410.06949) | [code]

- [2024/09/02] **Co-Learning: Code Learning for Multi-Agent Reinforcement Collaborative Framework with Conversational Natural Language Interfaces** | [[paper]](https://arxiv.org/abs/2409.00985) | [code]

- [2024/08/19] **GoNoGo: An Efficient LLM-based Multi-Agent System for Streamlining Automotive Software Release Decision-Making** | [[paper]](https://arxiv.org/abs/2408.09785) | [code]

- [2024/08/13] **Diversity Empowers Intelligence: Integrating Expertise of Software Engineering Agents** | [[paper]](https://arxiv.org/abs/2408.07060) | [code]

- [2024/08/05] **LLM Agents Improve Semantic Code Search** | [[paper]](https://arxiv.org/abs/2408.11058) | [code]

- [2024/07/26] **AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents** | [[paper]](https://arxiv.org/abs/2407.18901) | [code]

- [2024/07/01] **Agentless: Demystifying LLM-based Software Engineering Agents** | [[paper]](https://arxiv.org/abs/2407.01489) | [code]

- [2024/06/13] **Multi-Agent Software Development through Cross-Team Collaboration** | [[paper]](https://arxiv.org/abs/2406.08979) | [[code]](https://github.com/openbmb/chatdev)

- [2024/05/06] **SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering** | [[paper]](https://arxiv.org/abs/2405.15793) | [code]

- [2024/04/11] **Behavior Trees Enable Structured Programming of Language Model Agents** | [[paper]](https://arxiv.org/abs/2404.07439) | [[code]](https://github.com/RichardKelley/dendron)

- [2024/04/02] **Self-Organized Agents: A LLM Multi-Agent Framework toward Ultra Large-Scale Code Generation and Optimization** | [[paper]](https://arxiv.org/abs/2404.02183) | [code]

- [2024/03/02] **SceneCraft: An LLM Agent for Synthesizing 3D Scene as Blender Code** | [[paper]](https://arxiv.org/abs/2403.01248) | [code]

- [2024/02/26] **RepoAgent: An LLM-Powered Open-Source Framework for Repository-level Code Documentation Generation** | [[paper]](https://arxiv.org/abs/2402.16667) | [code]

- [2024/02/19] **WorldCoder, a Model-Based LLM Agent: Building World Models by Writing Code and Interacting with the Environment** | [[paper]](https://arxiv.org/abs/2402.12275) | [code]

- [2024/02/02] **StepCoder: Improve Code Generation with Reinforcement Learning from Compiler Feedback** | [[paper]](https://arxiv.org/abs/2402.01391) | [code]

- [2024/02/01] **Executable Code Actions Elicit Better LLM Agents** | [[paper]](https://arxiv.org/abs/2402.01030) | [code]

- [2023/12/28] **Experiential Co-Learning of Software-Developing Agents** | [[paper]](https://arxiv.org/abs/2312.17025) | [code]

- [2023/12/20] **AgentCoder: Multi-Agent-based Code Generation with Iterative Testing and Optimisation** | [[paper]](https://arxiv.org/abs/2312.13010) | [code]

- [2023/07/27] **PanGu-Coder2: Boosting Large Language Models for Code with Ranking Feedback** | [[paper]](https://arxiv.org/abs/2307.14936) | [code]

- [2023/07/16] **ChatDev: Communicative Agents for Software Development** | [[paper]](https://arxiv.org/abs/2307.07924) | [code]

- [2023/04/15] **Self-collaboration Code Generation via ChatGPT** | [[paper]](https://arxiv.org/abs/2304.07590) | [code]

#### Research
- [2025/02/20] **MLGym: A New Framework and Benchmark for Advancing AI Research Agents** | [[paper]](https://arxiv.org/abs/2502.14499) | [code]

- [2025/02/07] **Agentic Reasoning: Reasoning LLMs with Tools for the Deep Research** | [[paper]](https://arxiv.org/abs/2502.04644) | [code]

- [2025/01/08] **Agent Laboratory: Using LLM Agents as Research Assistants** | [[paper]](https://arxiv.org/abs/2501.04227) | [code]

- [2024/10/17] **Chain of Ideas: Revolutionizing Research Via Novel Idea Development with LLM Agents** | [[paper]](https://arxiv.org/abs/2410.13185) | [code]

- [2024/10/12] **Many Heads Are Better Than One: Improved Scientific Idea Generation by A LLM-Based Multi-Agent System** | [[paper]](https://arxiv.org/abs/2410.09403) | [code]

- [2024/10/07] **ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery** | [[paper]](https://arxiv.org/abs/2410.05080) | [code]

- [2024/10/07] **ImProver: Agent-Based Automated Proof Optimization** | [[paper]](https://arxiv.org/abs/2410.04753) | [code]

- [2024/09/23] **Towards a Realistic Long-Term Benchmark for Open-Web Research Agents** | [[paper]](https://arxiv.org/abs/2409.14913) | [code]

- [2024/09/17] **CORE-Bench: Fostering the Credibility of Published Research Through a Computational Reproducibility Agent Benchmark** | [[paper]](https://arxiv.org/abs/2409.11363) | [code]

- [2024/09/12] **DSBench: How Far Are Data Science Agents to Becoming Data Science Experts?** | [[paper]](https://arxiv.org/abs/2409.07703) | [code]

- [2024/09/11] **SUPER: Evaluating Agents on Setting Up and Executing Tasks from Research Repositories** | [[paper]](https://arxiv.org/abs/2409.07440) | [code]

- [2024/09/10] **Language agents achieve superhuman synthesis of scientific knowledge** | [[paper]](https://arxiv.org/abs/2409.13740) | [code]

- [2024/09/09] **SciAgents: Automating scientific discovery through multi-agent intelligent graph reasoning** | [[paper]](https://arxiv.org/abs/2409.05556) | [code]

- [2024/08/26] **MLR-Copilot: Autonomous Machine Learning Research based on Large Language Models Agents** | [[paper]](https://arxiv.org/abs/2408.14033) | [code]

- [2024/08/20] **Automating Knowledge Discovery from Scientific Literature via LLMs: A Dual-Agent Approach with Progressive Ontology Prompting** | [[paper]](https://arxiv.org/abs/2409.00054) | [code]

- [2024/06/13] **ResearchArena: Benchmarking Large Language Models&#39; Ability to Collect and Organize Information as Research Agents** | [[paper]](https://arxiv.org/abs/2406.10291) | [code]

- [2024/05/02] **CACTUS: Chemistry Agent Connecting Tool-Usage to Science** | [[paper]](https://arxiv.org/abs/2405.00972) | [[code]](https://github.com/pnnl/cactus)

- [2024/04/09] **SurveyAgent: A Conversational System for Personalized and Efficient Research Survey** | [[paper]](https://arxiv.org/abs/2404.06364) | [code]

- [2024/02/28] **Data Interpreter: An LLM Agent For Data Science** | [[paper]](https://arxiv.org/abs/2402.18679) | [[code]](https://github.com/geekan/metagpt)

- [2024/02/18] **SciAgent: Tool-augmented Language Models for Scientific Reasoning** | [[paper]](https://arxiv.org/abs/2402.11451) | [code]

- [2024/02/06] **Prioritizing Safeguarding Over Autonomy: Risks of LLM Agents for Science** | [[paper]](https://arxiv.org/abs/2402.04247) | [code]

- [2024/01/08] **MARG: Multi-Agent Review Generation for Scientific Papers** | [[paper]](https://arxiv.org/abs/2401.04259) | [code]

### Automation
#### Workflow
- [2025/02/11] **EvoFlow: Evolving Diverse Agentic Workflows On The Fly** | [[paper]](https://arxiv.org/abs/2502.07373) | [code]

- [2025/02/07] **nvAgent: Automated Data Visualization from Natural Language via Collaborative Agent Workflow** | [[paper]](https://arxiv.org/abs/2502.05036) | [code]

- [2025/02/06] **ScoreFlow: Mastering LLM Agent Workflows via Score-based Preference Optimization** | [[paper]](https://arxiv.org/abs/2502.04306) | [code]

- [2024/12/17] **An Agentic Approach to Automatic Creation of P&amp;ID Diagrams from Natural Language Descriptions** | [[paper]](https://arxiv.org/abs/2412.12898) | [code]

- [2024/12/15] **LAW: Legal Agentic Workflows for Custody and Fund Services Contracts** | [[paper]](https://arxiv.org/abs/2412.11063) | [code]

- [2024/11/22] **ScribeAgent: Towards Specialized Web Agents Using Production-Scale Workflow Data** | [[paper]](https://arxiv.org/abs/2411.15004) | [code]

- [2024/11/12] **BudgetMLAgent: A Cost-Effective LLM Multi-Agent system for Automating Machine Learning Tasks** | [[paper]](https://arxiv.org/abs/2411.07464) | [code]

- [2024/11/08] **Game-theoretic LLM: Agent Workflow for Negotiation Games** | [[paper]](https://arxiv.org/abs/2411.05990) | [code]

- [2024/10/24] **An LLM Agent for Automatic Geospatial Data Analysis** | [[paper]](https://arxiv.org/abs/2410.18792) | [code]

- [2024/10/17] **From Barriers to Tactics: A Behavioral Science-Informed Agentic Workflow for Personalized Nutrition Coaching** | [[paper]](https://arxiv.org/abs/2410.14041) | [code]

- [2024/10/17] **ControlAgent: Automating Control System Design via Novel Integration of LLM Agents and Domain Expertise** | [[paper]](https://arxiv.org/abs/2410.19811) | [code]

- [2024/10/16] **Proactive Agent: Shifting LLM Agents from Reactive Responses to Active Assistance** | [[paper]](https://arxiv.org/abs/2410.12361) | [code]

- [2024/10/14] **AFlow: Automating Agentic Workflow Generation** | [[paper]](https://arxiv.org/abs/2410.10762) | [code]

- [2024/10/10] **Benchmarking Agentic Workflow Generation** | [[paper]](https://arxiv.org/abs/2410.07869) | [code]

- [2024/10/03] **AutoML-Agent: A Multi-Agent LLM Framework for Full-Pipeline AutoML** | [[paper]](https://arxiv.org/abs/2410.02958) | [code]

- [2024/09/11] **Agent Workflow Memory** | [[paper]](https://arxiv.org/abs/2409.07429) | [code]

- [2024/08/16] **The Fellowship of the LLMs: Multi-Agent Workflows for Synthetic Preference Optimization Dataset Generation** | [[paper]](https://arxiv.org/abs/2408.08688) | [code]

- [2024/07/15] **Spider2-V: How Far Are Multimodal Agents From Automating Data Science and Engineering Workflows?** | [[paper]](https://arxiv.org/abs/2407.10956) | [code]

- [2024/07/03] **AgentInstruct: Toward Generative Teaching with Agentic Flows** | [[paper]](https://arxiv.org/abs/2407.03502) | [code]

- [2024/07/01] **AutoFlow: Automated Workflow Generation for Large Language Model Agents** | [[paper]](https://arxiv.org/abs/2407.12821) | [code]

- [2024/06/21] **Autonomous Agents for Collaborative Task under Information Asymmetry** | [[paper]](https://arxiv.org/abs/2406.14928) | [code]

- [2024/03/13] **AutoGuide: Automated Generation and Selection of Context-Aware Guidelines for Large Language Model Agents** | [[paper]](https://arxiv.org/abs/2403.08978) | [code]

- [2024/03/05] **ChatCite: LLM Agent with Human Workflow Guidance for Comparative Literature Summary** | [[paper]](https://arxiv.org/abs/2403.02574) | [code]

#### Automatic Evaluation
- [2025/02/14] **Automated Hypothesis Validation with Agentic Sequential Falsifications** | [[paper]](https://arxiv.org/abs/2502.09858) | [code]

- [2025/01/19] **IntellAgent: A Multi-Agent Framework for Evaluating Conversational AI Systems** | [[paper]](https://arxiv.org/abs/2501.11067) | [code]

- [2025/01/17] **Agent-as-Judge for Factual Summarization of Long Narratives** | [[paper]](https://arxiv.org/abs/2501.09993) | [code]

- [2025/01/03] **PSYCHE: A Multi-faceted Patient Simulation Framework for Evaluation of Psychiatric Assessment Conversational Agents** | [[paper]](https://arxiv.org/abs/2501.01594) | [code]

- [2024/12/28] **M-MAD: Multidimensional Multi-Agent Debate for Advanced Machine Translation Evaluation** | [[paper]](https://arxiv.org/abs/2412.20127) | [code]

- [2024/12/10] **Evaluation Agent: Efficient and Promptable Evaluation Framework for Visual Generative Models** | [[paper]](https://arxiv.org/abs/2412.09645) | [code]

- [2024/11/25] **SAGEval: The frontiers of Satisfactory Agent based NLG Evaluation for reference-free open-ended text** | [[paper]](https://arxiv.org/abs/2411.16077) | [code]

- [2024/11/15] **Large Language Models as User-Agents for Evaluating Task-Oriented-Dialogue Systems** | [[paper]](https://arxiv.org/abs/2411.09972) | [code]

- [2024/09/24] **Automated test generation to evaluate tool-augmented LLMs as conversational AI agents** | [[paper]](https://arxiv.org/abs/2409.15934) | [code]

- [2024/09/22] **The Ability of Large Language Models to Evaluate Constraint-satisfaction in Agent Responses to Open-ended Requests** | [[paper]](https://arxiv.org/abs/2409.14371) | [code]

- [2024/09/13] **Safeguarding Decentralized Social Media: LLM Agents for Automating Community Rule Compliance** | [[paper]](https://arxiv.org/abs/2409.08963) | [code]

- [2024/05/23] **ALI-Agent: Assessing LLMs&#39; Alignment with Human Values via Agent-based Evaluation** | [[paper]](https://arxiv.org/abs/2405.14125) | [code]

- [2024/03/28] **MATEval: A Multi-Agent Discussion Framework for Advancing Open-Ended Text Evaluation** | [[paper]](https://arxiv.org/abs/2403.19305) | [code]

- [2023/08/14] **ChatEval: Towards Better LLM-based Evaluators through Multi-Agent Debate** | [[paper]](https://arxiv.org/abs/2308.07201) | [code]

### Training
#### Fine tuning
- [2025/02/19] **UM_FHS at TREC 2024 PLABA: Exploration of Fine-tuning and AI agent approach for plain language adaptations of biomedical text** | [[paper]](https://arxiv.org/abs/2502.14144) | [code]

- [2025/02/18] **Training Turn-by-Turn Verifiers for Dialogue Tutoring Agents: The Curious Case of LLMs as Your Coding Tutors** | [[paper]](https://arxiv.org/abs/2502.13311) | [code]

- [2025/02/11] **Multi-Agent Collaboration for Multilingual Code Instruction Tuning** | [[paper]](https://arxiv.org/abs/2502.07487) | [code]

- [2025/02/10] **Hephaestus: Improving Fundamental Agent Capabilities of Large Language Models through Continual Pre-Training** | [[paper]](https://arxiv.org/abs/2502.06589) | [code]

- [2025/01/10] **Multiagent Finetuning: Self Improvement with Diverse Reasoning Chains** | [[paper]](https://arxiv.org/abs/2501.05707) | [code]

- [2025/01/03] **AgentRefine: Enhancing Agent Generalization through Refinement Tuning** | [[paper]](https://arxiv.org/abs/2501.01702) | [code]

- [2024/12/30] **Training Software Engineering Agents and Verifiers with SWE-Gym** | [[paper]](https://arxiv.org/abs/2412.21139) | [code]

- [2024/12/30] **Aviary: training language agents on challenging scientific tasks** | [[paper]](https://arxiv.org/abs/2412.21154) | [code]

- [2024/12/16] **Virtual Agent-Based Communication Skills Training to Facilitate Health Persuasion Among Peers** | [[paper]](https://arxiv.org/abs/2412.12061) | [code]

- [2024/11/29] **Training Agents with Weakly Supervised Feedback from Large Language Models** | [[paper]](https://arxiv.org/abs/2411.19547) | [code]

- [2024/11/21] **Star-Agents: Automatic Data Optimization with LLM Agents for Instruction Tuning** | [[paper]](https://arxiv.org/abs/2411.14497) | [code]

- [2024/10/20] **Training Language Models to Critique With Multi-agent Feedback** | [[paper]](https://arxiv.org/abs/2410.15287) | [code]

- [2024/10/16] **Proactive Agent: Shifting LLM Agents from Reactive Responses to Active Assistance** | [[paper]](https://arxiv.org/abs/2410.12361) | [code]

- [2024/10/10] **AgentBank: Towards Generalized LLM Agents via Fine-Tuning on 50000+ Interaction Trajectories** | [[paper]](https://arxiv.org/abs/2410.07706) | [code]

- [2024/07/25] **Recursive Introspection: Teaching Language Model Agents How to Self-Improve** | [[paper]](https://arxiv.org/abs/2407.18219) | [code]

- [2024/06/11] **CoEvol: Constructing Better Responses for Instruction Finetuning through Multi-Agent Cooperation** | [[paper]](https://arxiv.org/abs/2406.07054) | [[code]](https://github.com/lirenhao1997/coevol)

- [2024/04/05] **Social Skill Training with Large Language Models** | [[paper]](https://arxiv.org/abs/2404.04204) | [code]

- [2024/04/02] **CMAT: A Multi-Agent Collaboration Tuning Framework for Enhancing Small Language Models** | [[paper]](https://arxiv.org/abs/2404.01663) | [code]

- [2024/03/29] **Enhancing the General Agent Capabilities of Low-Parameter LLMs through Tuning and Multi-Branch Reasoning** | [[paper]](https://arxiv.org/abs/2403.19962) | [code]

- [2024/03/21] **ReAct Meets ActRe: When Language Agents Enjoy Training Data Autonomy** | [[paper]](https://arxiv.org/abs/2403.14589) | [code]

- [2024/03/19] **Agent-FLAN: Designing Data and Methods of Effective Agent Tuning for Large Language Models** | [[paper]](https://arxiv.org/abs/2403.12881) | [code]

- [2024/02/23] **AgentOhana: Design Unified Data and Training Pipeline for Effective Agent Learning** | [[paper]](https://arxiv.org/abs/2402.15506) | [code]

- [2024/02/21] **Neeko: Leveraging Dynamic LoRA for Efficient Multi-Character Role-Playing Agent** | [[paper]](https://arxiv.org/abs/2402.13717) | [code]

- [2024/02/18] **Learning From Failure: Integrating Negative Examples when Fine-tuning Large Language Models as Agents** | [[paper]](https://arxiv.org/abs/2402.11651) | [code]

- [2024/01/10] **Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training** | [[paper]](https://arxiv.org/abs/2401.05566) | [code]

- [2024/01/05] **From LLM to Conversational Agent: A Memory Enhanced Architecture with Fine-Tuning of Large Language Models** | [[paper]](https://arxiv.org/abs/2401.02777) | [code]

- [2023/12/22] **Pangu-Agent: A Fine-Tunable Generalist Agent with Structured Reasoning** | [[paper]](https://arxiv.org/abs/2312.14878) | [code]

- [2023/11/28] **Embodied Multi-Modal Agent trained by an LLM from a Parallel TextWorld** | [[paper]](https://arxiv.org/abs/2311.16714) | [code]

- [2023/10/19] **AgentTuning: Enabling Generalized Agent Abilities for LLMs** | [[paper]](https://arxiv.org/abs/2310.12823) | [code]

- [2023/10/09] **FireAct: Toward Language Agent Fine-tuning** | [[paper]](https://arxiv.org/abs/2310.05915) | [code]

- [2023/05/26] **Training Socially Aligned Language Models on Simulated Social Interactions** | [[paper]](https://arxiv.org/abs/2305.16960) | [code]

#### RL
- [2025/02/09] **Training Language Models for Social Deduction with Multi-Agent Reinforcement Learning** | [[paper]](https://arxiv.org/abs/2502.06060) | [code]

- [2025/02/06] **Multi-Agent Reinforcement Learning with Focal Diversity Optimization** | [[paper]](https://arxiv.org/abs/2502.04492) | [code]

- [2025/01/25] **Improving Retrieval-Augmented Generation through Multi-Agent Reinforcement Learning** | [[paper]](https://arxiv.org/abs/2501.15228) | [code]

- [2024/11/26] **LLM-Based Offline Learning for Embodied Agents via Consistency-Guided Reward Ensemble** | [[paper]](https://arxiv.org/abs/2411.17135) | [code]

- [2024/11/07] **Interactive Dialogue Agents via Reinforcement Learning on Hindsight Regenerations** | [[paper]](https://arxiv.org/abs/2411.05194) | [code]

- [2024/11/06] **From Novice to Expert: LLM Agent Policy Optimization via Step-wise Reinforcement Learning** | [[paper]](https://arxiv.org/abs/2411.03817) | [code]

- [2024/11/04] **WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning** | [[paper]](https://arxiv.org/abs/2411.02337) | [code]

- [2024/10/11] **Words as Beacons: Guiding RL Agents with High-Level Language Prompts** | [[paper]](https://arxiv.org/abs/2410.08632) | [code]

- [2024/10/10] **MACPO: Weak-to-Strong Alignment via Multi-Agent Contrastive Preference Optimization** | [[paper]](https://arxiv.org/abs/2410.07672) | [code]

- [2024/07/02] **Predicting vs. Acting: A Trade-off Between World Modeling &amp; Agent Modeling** | [[paper]](https://arxiv.org/abs/2407.02446) | [code]

- [2024/06/26] **Mental Modeling of Reinforcement Learning Agents by Language Models** | [[paper]](https://arxiv.org/abs/2406.18505) | [code]

- [2024/06/17] **Input Conditioned Graph Generation for Language Agents** | [[paper]](https://arxiv.org/abs/2406.11555) | [[code]](https://github.com/lukasvierling/dynamicgptswarm)

- [2024/06/05] **LLM-based Rewriting of Inappropriate Argumentation using Reinforcement Learning from Machine Feedback** | [[paper]](https://arxiv.org/abs/2406.03363) | [code]

- [2024/06/03] **Re-ReST: Reflection-Reinforced Self-Training for Language Agents** | [[paper]](https://arxiv.org/abs/2406.01495) | [[code]](https://github.com/PlusLabNLP/Re-ReST)

- [2024/05/30] **Safe Multi-agent Reinforcement Learning with Natural Language Constraints** | [[paper]](https://arxiv.org/abs/2405.20018) | [code]

- [2024/05/17] **LLM-based Multi-Agent Reinforcement Learning: Current and Future Directions** | [[paper]](https://arxiv.org/abs/2405.11106) | [code]

- [2024/05/16] **Fine-Tuning Large Vision-Language Models as Decision-Making Agents via Reinforcement Learning** | [[paper]](https://arxiv.org/abs/2405.10292) | [code]

- [2024/05/01] **Navigating WebAI: Training Agents to Complete Web Tasks with Large Language Models and Reinforcement Learning** | [[paper]](https://arxiv.org/abs/2405.00516) | [code]

- [2024/03/05] **Language Guided Exploration for RL Agents in Text Environments** | [[paper]](https://arxiv.org/abs/2403.03141) | [code]

- [2024/02/17] **Offline Training of Language Model Agents with Functions as Learnable Weights** | [[paper]](https://arxiv.org/abs/2402.11359) | [code]

- [2024/02/02] **StepCoder: Improve Code Generation with Reinforcement Learning from Compiler Feedback** | [[paper]](https://arxiv.org/abs/2402.01391) | [code]

- [2023/10/25] **MultiPrompter: Cooperative Prompt Optimization with Multi-Agent Reinforcement Learning** | [[paper]](https://arxiv.org/abs/2310.16730) | [code]

- [2023/03/29] **Skill Reinforcement Learning and Planning for Open-World Long-Horizon Tasks** | [[paper]](https://arxiv.org/abs/2303.16563) | [code]

#### DPO
- [2025/01/03] **SDPO: Segment-Level Direct Preference Optimization for Social Agents** | [[paper]](https://arxiv.org/abs/2501.01821) | [code]

- [2024/10/29] **Flow-DPO: Improving LLM Mathematical Reasoning through Online Multi-Agent Learning** | [[paper]](https://arxiv.org/abs/2410.22304) | [code]

- [2024/05/31] **Learning to Clarify: Multi-turn Conversations with Action-Based Contrastive Self-Training** | [[paper]](https://arxiv.org/abs/2406.00222) | [code]

### Scaling
#### Single-Agent Framework
- [2025/02/14] **Agentic Verification for Ambiguous Query Disambiguation** | [[paper]](https://arxiv.org/abs/2502.10352) | [code]

- [2025/02/12] **SPeCtrum: A Grounded Framework for Multidimensional Identity Representation in LLM-Based Agent** | [[paper]](https://arxiv.org/abs/2502.08599) | [code]

- [2025/02/09] **AutoAgent: A Fully-Automated and Zero-Code Framework for LLM Agents** | [[paper]](https://arxiv.org/abs/2502.05957) | [code]

- [2025/02/04] **Adaptive Self-improvement LLM Agentic System for ML Library Development** | [[paper]](https://arxiv.org/abs/2502.02534) | [code]

- [2025/01/31] **Enabling Autonomic Microservice Management through Self-Learning Agents** | [[paper]](https://arxiv.org/abs/2501.19056) | [code]

- [2024/12/28] **OneKE: A Dockerized Schema-Guided LLM Agent-based Knowledge Extraction System** | [[paper]](https://arxiv.org/abs/2412.20005) | [code]

- [2024/12/21] **Self-guided Knowledgeable Network of Thoughts: Amplifying Reasoning with Large Language Models** | [[paper]](https://arxiv.org/abs/2412.16533) | [code]

- [2024/12/15] **AgentPS: Agentic Process Supervision for Multi-modal Content Quality Assurance through Multi-round QA** | [[paper]](https://arxiv.org/abs/2412.15251) | [code]

- [2024/12/11] **A Multimodal Social Agent** | [[paper]](https://arxiv.org/abs/2501.06189) | [code]

- [2024/12/11] **Federated In-Context LLM Agent Learning** | [[paper]](https://arxiv.org/abs/2412.08054) | [code]

- [2024/12/04] **How to Correctly do Semantic Backpropagation on Language-based Agentic Systems** | [[paper]](https://arxiv.org/abs/2412.03624) | [code]

- [2024/12/02] **SAUP: Situation Awareness Uncertainty Propagation on LLM Agent** | [[paper]](https://arxiv.org/abs/2412.01033) | [code]

- [2024/12/01] **Towards Adaptive Mechanism Activation in Language Agent** | [[paper]](https://arxiv.org/abs/2412.00722) | [code]

- [2024/11/20] **MindForge: Empowering Embodied Agents with Theory of Mind for Lifelong Collaborative Learning** | [[paper]](https://arxiv.org/abs/2411.12977) | [code]

- [2024/11/16] **IntentGPT: Few-shot Intent Discovery with Large Language Models** | [[paper]](https://arxiv.org/abs/2411.10670) | [code]

- [2024/11/04] **DynaSaur: Large Language Agents Beyond Predefined Actions** | [[paper]](https://arxiv.org/abs/2411.01747) | [code]

- [2024/11/04] **CRMArena: Understanding the Capacity of LLM Agents to Perform Professional CRM Tasks in Realistic Environments** | [[paper]](https://arxiv.org/abs/2411.02305) | [code]

- [2024/10/29] **ADAM: An Embodied Causal Agent in Open-World Environments** | [[paper]](https://arxiv.org/abs/2410.22194) | [code]

- [2024/10/27] **TrajAgent: An Agent Framework for Unified Trajectory Modelling** | [[paper]](https://arxiv.org/abs/2410.20445) | [code]

- [2024/10/22] **Adsorb-Agent: Autonomous Identification of Stable Adsorption Configurations via Large Language Model Agent** | [[paper]](https://arxiv.org/abs/2410.16658) | [code]

- [2024/10/11] **Encoding Agent Trajectories as Representations with Sequence Transformers** | [[paper]](https://arxiv.org/abs/2410.09204) | [code]

- [2024/10/10] **Agents Thinking Fast and Slow: A Talker-Reasoner Architecture** | [[paper]](https://arxiv.org/abs/2410.08328) | [code]

- [2024/10/08] **AgentSquare: Automatic LLM Agent Search in Modular Design Space** | [[paper]](https://arxiv.org/abs/2410.06153) | [code]

- [2024/10/08] **Applying Refusal-Vector Ablation to Llama 3.1 70B Agents** | [[paper]](https://arxiv.org/abs/2410.10871) | [code]

- [2024/09/24] **MOSS: Enabling Code-Driven Evolution and Context Management for AI Agents** | [[paper]](https://arxiv.org/abs/2409.16120) | [code]

- [2024/09/19] **Textualized Agent-Style Reasoning for Complex Tasks by Multiple Round LLM Generation** | [[paper]](https://arxiv.org/abs/2409.12411) | [code]

- [2024/09/15] **Automatic Control With Human-Like Reasoning: Exploring Language Model Embodied Air Traffic Agents** | [[paper]](https://arxiv.org/abs/2409.09717) | [code]

- [2024/09/12] **Self-Supervised Inference of Agents in Trustless Environments** | [[paper]](https://arxiv.org/abs/2409.08386) | [code]

- [2024/09/05] **From MOOC to MAIC: Reshaping Online Teaching and Learning through LLM-driven Agents** | [[paper]](https://arxiv.org/abs/2409.03512) | [code]

- [2024/09/05] **Rx Strategist: Prescription Verification using LLM Agents System** | [[paper]](https://arxiv.org/abs/2409.03440) | [code]

- [2024/09/03] **AgentRE: An Agent-Based Framework for Navigating Complex Information Landscapes in Relation Extraction** | [[paper]](https://arxiv.org/abs/2409.01854) | [code]

- [2024/08/26] **AgentMove: A Large Language Model based Agentic Framework for Zero-shot Next Location Prediction** | [[paper]](https://arxiv.org/abs/2408.13986) | [code]

- [2024/08/19] **Anim-Director: A Large Multimodal Model Powered Agent for Controllable Animation Video Generation** | [[paper]](https://arxiv.org/abs/2408.09787) | [code]

- [2024/08/13] **Causal Agent based on Large Language Model** | [[paper]](https://arxiv.org/abs/2408.06849) | [code]

- [2024/08/02] **Coalitions of Large Language Models Increase the Robustness of AI Agents** | [[paper]](https://arxiv.org/abs/2408.01380) | [code]

- [2024/07/27] **AgentPeerTalk: Empowering Students through Agentic-AI-Driven Discernment of Bullying and Joking in Peer Interactions in Schools** | [[paper]](https://arxiv.org/abs/2408.01459) | [code]

- [2024/07/25] **Enhancing Agent Learning through World Dynamics Modeling** | [[paper]](https://arxiv.org/abs/2407.17695) | [code]

- [2024/07/25] **RestoreAgent: Autonomous Image Restoration Agent via Multimodal Large Language Models** | [[paper]](https://arxiv.org/abs/2407.18035) | [code]

- [2024/07/16] **Preemptive Detection and Correction of Misaligned Actions in LLM Agents** | [[paper]](https://arxiv.org/abs/2407.11843) | [code]

- [2024/07/15] **Sibyl: Simple yet Effective Agent Framework for Complex Real-world Reasoning** | [[paper]](https://arxiv.org/abs/2407.10718) | [code]

- [2024/07/02] **Beyond Numeric Awards: In-Context Dueling Bandits with LLM Agents** | [[paper]](https://arxiv.org/abs/2407.01887) | [code]

- [2024/06/24] **OmAgent: A Multi-modal Agent Framework for Complex Video Understanding with Task Divide-and-Conquer** | [[paper]](https://arxiv.org/abs/2406.16620) | [code]

- [2024/06/07] **SelfGoal: Your Language Agents Already Know How to Achieve High-level Goals** | [[paper]](https://arxiv.org/abs/2406.04784) | [code]

- [2024/05/25] **AutoManual: Constructing Instruction Manuals by LLM Agents via Interactive Environmental Learning** | [[paper]](https://arxiv.org/abs/2405.16247) | [code]

- [2024/05/24] **Intelligent Go-Explore: Standing on the Shoulders of Giant Foundation Models** | [[paper]](https://arxiv.org/abs/2405.15143) | [[code]](https://github.com/conglu1997/intelligent-go-explore)

- [2024/05/16] **Agent Design Pattern Catalogue: A Collection of Architectural Patterns for Foundation Model based Agents** | [[paper]](https://arxiv.org/abs/2405.10467) | [code]

- [2024/04/30] **Large Language Model Agent for Fake News Detection** | [[paper]](https://arxiv.org/abs/2405.01593) | [code]

- [2024/04/28] **Logic Agent: Enhancing Validity with Logic Rule Invocation** | [[paper]](https://arxiv.org/abs/2404.18130) | [code]

- [2024/04/13] **LLMSat: A Large Language Model-Based Goal-Oriented Agent for Autonomous Space Exploration** | [[paper]](https://arxiv.org/abs/2405.01392) | [code]

- [2024/04/01] **TraveLER: A Modular Multi-LMM Agent Framework for Video Question-Answering** | [[paper]](https://arxiv.org/abs/2404.01476) | [code]

- [2024/03/29] **ITCMA: A Generative Agent Based on a Computational Consciousness Structure** | [[paper]](https://arxiv.org/abs/2403.20097) | [code]

- [2024/02/25] **Bootstrapping Cognitive Agents with a Large Language Model** | [[paper]](https://arxiv.org/abs/2403.00810) | [code]

- [2024/02/24] **Empowering Large Language Model Agents through Action Learning** | [[paper]](https://arxiv.org/abs/2402.15809) | [[code]](https://github.com/zhao-ht/learnact)

- [2024/02/20] **Soft Self-Consistency Improves Language Model Agents** | [[paper]](https://arxiv.org/abs/2402.13212) | [code]

- [2024/02/04] **NavHint: Vision and Language Navigation Agent with a Hint Generator** | [[paper]](https://arxiv.org/abs/2402.02559) | [code]

- [2024/01/05] **AFSPP: Agent Framework for Shaping Preference and Personality with Large Language Models** | [[paper]](https://arxiv.org/abs/2401.02870) | [code]

- [2023/11/23] **Controlling Large Language Model-based Agents for Large-Scale Decision-Making: An Actor-Critic Approach** | [[paper]](https://arxiv.org/abs/2311.13884) | [code]

- [2023/11/02] **ProAgent: From Robotic Process Automation to Agentic Process Automation** | [[paper]](https://arxiv.org/abs/2311.10751) | [code]

- [2023/10/16] **CLIN: A Continually Learning Language Agent for Rapid Task Adaptation and Generalization** | [[paper]](https://arxiv.org/abs/2310.10134) | [code]

- [2023/09/29] **Reason for Future, Act for Now: A Principled Framework for Autonomous LLM Agents with Provable Sample Efficiency** | [[paper]](https://arxiv.org/abs/2309.17382) | [code]

- [2023/09/14] **Agents: An Open-source Framework for Autonomous Language Agents** | [[paper]](https://arxiv.org/abs/2309.07870) | [code]

- [2023/09/08] **A Versatile Graph Learning Approach through LLM-based Agent** | [[paper]](https://arxiv.org/abs/2309.04565) | [code]

- [2023/09/05] **Cognitive Architectures for Language Agents** | [[paper]](https://arxiv.org/abs/2309.02427) | [code]

- [2023/05/27] **SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks** | [[paper]](https://arxiv.org/abs/2305.17390) | [code]

- [2023/05/25] **Voyager: An Open-Ended Embodied Agent with Large Language Models** | [[paper]](https://arxiv.org/abs/2305.16291) | [code]

#### Multi-Agent System
- [2025/02/20] **Enhancing Language Multi-Agent Learning with Multi-Agent Credit Re-Assignment for Interactive Environment Generalization** | [[paper]](https://arxiv.org/abs/2502.14496) | [code]

- [2025/02/20] **CORBA: Contagious Recursive Blocking Attacks on Multi-Agent Systems Based on Large Language Models** | [[paper]](https://arxiv.org/abs/2502.14529) | [code]

- [2025/02/17] **Table-Critic: A Multi-Agent Framework for Collaborative Criticism and Refinement in Table Reasoning** | [[paper]](https://arxiv.org/abs/2502.11799) | [code]

- [2025/02/17] **HARBOR: Exploring Persona Dynamics in Multi-Agent Competition** | [[paper]](https://arxiv.org/abs/2502.12149) | [code]

- [2025/02/15] **Divergent Thoughts toward One Goal: LLM-based Multi-Agent Collaboration System for Electronic Design Automation** | [[paper]](https://arxiv.org/abs/2502.10857) | [code]

- [2025/02/13] **PathFinder: A Multi-Modal Multi-Agent System for Medical Diagnostic Decision-Making Applied to Histopathology** | [[paper]](https://arxiv.org/abs/2502.08916) | [code]

- [2025/02/13] **Mind the Gaps: Logical English, Prolog, and Multi-agent Systems for Autonomous Vehicles** | [[paper]](https://arxiv.org/abs/2502.09216) | [code]

- [2025/02/12] **Faithful, Unfaithful or Ambiguous? Multi-Agent Debate with Initial Stance for Summary Evaluation** | [[paper]](https://arxiv.org/abs/2502.08514) | [code]

- [2025/02/12] **If Multi-Agent Debate is the Answer, What is the Question?** | [[paper]](https://arxiv.org/abs/2502.08788) | [code]

- [2025/02/11] **Don&#39;t Just Demo, Teach Me the Principles: A Principle-Based Multi-Agent Prompting Strategy for Text Classification** | [[paper]](https://arxiv.org/abs/2502.07165) | [code]

- [2025/02/11] **Multi-Agent Collaboration for Multilingual Code Instruction Tuning** | [[paper]](https://arxiv.org/abs/2502.07487) | [code]

- [2025/02/10] **KARMA: Leveraging Multi-Agent LLMs for Automated Knowledge Graph Enrichment** | [[paper]](https://arxiv.org/abs/2502.06472) | [code]

- [2025/02/09] **Preventing Rogue Agents Improves Multi-Agent Collaboration** | [[paper]](https://arxiv.org/abs/2502.05986) | [code]

- [2025/02/08] **CODESIM: Multi-Agent Code Generation and Problem Solving through Simulation-Driven Planning and Debugging** | [[paper]](https://arxiv.org/abs/2502.05664) | [code]

- [2025/02/08] **Multi-Agent Simulator Drives Language Models for Legal Intensive Interaction** | [[paper]](https://arxiv.org/abs/2502.06882) | [code]

- [2025/02/07] **S$^2$-MAD: Breaking the Token Barrier to Enhance Multi-Agent Debate Efficiency** | [[paper]](https://arxiv.org/abs/2502.04790) | [code]

- [2025/02/06] **Multi-Agent Reinforcement Learning with Focal Diversity Optimization** | [[paper]](https://arxiv.org/abs/2502.04492) | [code]

- [2025/02/06] **Enhancing Online Learning Efficiency Through Heterogeneous Resource Integration with a Multi-Agent RAG System** | [[paper]](https://arxiv.org/abs/2502.03948) | [code]

- [2025/02/06] **Multi-agent Architecture Search via Agentic Supernet** | [[paper]](https://arxiv.org/abs/2502.04180) | [code]

- [2025/02/04] **Position: Scaling LLM Agents Requires Asymptotic Analysis with LLM Primitives** | [[paper]](https://arxiv.org/abs/2502.04358) | [code]

- [2025/02/04] **Multi-Agent Design: Optimizing Agents with Better Prompts and Topologies** | [[paper]](https://arxiv.org/abs/2502.02533) | [code]

- [2025/02/03] **PlotGen: Multi-Agent LLM-based Scientific Data Visualization via Multimodal Feedback** | [[paper]](https://arxiv.org/abs/2502.00988) | [code]

- [2025/02/03] **ChartCitor: Multi-Agent Framework for Fine-Grained Chart Visual Attribution** | [[paper]](https://arxiv.org/abs/2502.00989) | [code]

- [2025/02/02] **Rethinking Mixture-of-Agents: Is Mixing Different Large Language Models Beneficial?** | [[paper]](https://arxiv.org/abs/2502.00674) | [code]

- [2025/02/02] **Efficient Multi-Agent System Training with Data Influence-Oriented Tree Search** | [[paper]](https://arxiv.org/abs/2502.00955) | [code]

- [2025/01/29] **Layered Chain-of-Thought Prompting for Multi-Agent LLM Systems: A Comprehensive Approach to Explainable Large Language Models** | [[paper]](https://arxiv.org/abs/2501.18645) | [code]

- [2025/01/27] **MADP: Multi-Agent Deductive Planning for Enhanced Cognitive-Behavioral Mental Health Question Answer** | [[paper]](https://arxiv.org/abs/2501.15826) | [code]

- [2025/01/25] **Improving Retrieval-Augmented Generation through Multi-Agent Reinforcement Learning** | [[paper]](https://arxiv.org/abs/2501.15228) | [code]

- [2025/01/24] **Multi-agent KTO: Reinforcing Strategic Interactions of Large Language Model in Language Game** | [[paper]](https://arxiv.org/abs/2501.14225) | [code]

- [2025/01/24] **Unmasking Conversational Bias in AI Multiagent Systems** | [[paper]](https://arxiv.org/abs/2501.14844) | [code]

- [2025/01/22] **FilmAgent: A Multi-Agent Framework for End-to-End Film Automation in Virtual 3D Spaces** | [[paper]](https://arxiv.org/abs/2501.12909) | [code]

- [2025/01/19] **IntellAgent: A Multi-Agent Framework for Evaluating Conversational AI Systems** | [[paper]](https://arxiv.org/abs/2501.11067) | [code]

- [2025/01/16] **AutoCBT: An Autonomous Multi-agent Framework for Cognitive Behavioral Therapy in Psychological Counseling** | [[paper]](https://arxiv.org/abs/2501.09426) | [code]

- [2025/01/14] **Talk to Right Specialists: Routing and Planning in Multi-agent System for Question Answering** | [[paper]](https://arxiv.org/abs/2501.07813) | [code]

- [2025/01/05] **LatteReview: A Multi-Agent Framework for Systematic Review Automation Using Large Language Models** | [[paper]](https://arxiv.org/abs/2501.05468) | [code]

- [2025/01/02] **Harnessing Multi-Agent LLMs for Complex Engineering Problem-Solving: A Framework for Senior Design Projects** | [[paper]](https://arxiv.org/abs/2501.01205) | [code]

- [2024/12/30] **Distributed Mixture-of-Agents for Edge Inference with Large Language Models** | [[paper]](https://arxiv.org/abs/2412.21200) | [code]

- [2024/12/28] **M-MAD: Multidimensional Multi-Agent Debate for Advanced Machine Translation Evaluation** | [[paper]](https://arxiv.org/abs/2412.20127) | [code]

- [2024/12/28] **Efficient Multi-Agent Collaboration with Tool Use for Online Planning in Complex Table Question Answering** | [[paper]](https://arxiv.org/abs/2412.20145) | [code]

- [2024/12/24] **Multi-Agents Based on Large Language Models for Knowledge-based Visual Question Answering** | [[paper]](https://arxiv.org/abs/2412.18351) | [code]

- [2024/12/22] **Multi-Agent Sampling: Scaling Inference Compute for Data Synthesis with Tree Search-Based Agentic Collaboration** | [[paper]](https://arxiv.org/abs/2412.17061) | [code]

- [2024/12/22] **A Multi-AI Agent System for Autonomous Optimization of Agentic AI Solutions via Iterative Refinement and LLM-Driven Feedback Loops** | [[paper]](https://arxiv.org/abs/2412.17149) | [code]

- [2024/12/20] **Mitigating Social Bias in Large Language Models: A Multi-Objective Approach within a Multi-Agent Framework** | [[paper]](https://arxiv.org/abs/2412.15504) | [code]

- [2024/12/19] **PsyDraw: A Multi-Agent Multimodal System for Mental Health Screening in Left-Behind Children** | [[paper]](https://arxiv.org/abs/2412.14769) | [code]

- [2024/12/18] **Gradual Vigilance and Interval Communication: Enhancing Value Alignment in Multi-Agent Debates** | [[paper]](https://arxiv.org/abs/2412.13471) | [code]

- [2024/12/15] **Cultural Palette: Pluralising Culture Alignment via Multi-agent Palette** | [[paper]](https://arxiv.org/abs/2412.11167) | [code]

- [2024/12/13] **AutoPatent: A Multi-Agent Framework for Automatic Patent Generation** | [[paper]](https://arxiv.org/abs/2412.09796) | [code]

- [2024/12/12] **DiverseAgentEntropy: Quantifying Black-Box LLM Uncertainty through Diverse Perspectives and Multi-Agent Interaction** | [[paper]](https://arxiv.org/abs/2412.09572) | [code]

- [2024/12/11] **NAT-NL2GQL: A Novel Multi-Agent Framework for Translating Natural Language to Graph Query Language** | [[paper]](https://arxiv.org/abs/2412.10434) | [code]

- [2024/12/10] **AutoPrep: Natural Language Question-Aware Data Preparation with a Multi-Agent Framework** | [[paper]](https://arxiv.org/abs/2412.10422) | [code]

- [2024/12/07] **SLA Management in Reconfigurable Multi-Agent RAG: A Systems Approach to Question Answering** | [[paper]](https://arxiv.org/abs/2412.06832) | [code]

- [2024/12/06] **Breaking Event Rumor Detection via Stance-Separated Multi-Agent Debate** | [[paper]](https://arxiv.org/abs/2412.04859) | [code]

- [2024/12/06] **Towards Effective GenAI Multi-Agent Collaboration: Design and Evaluation for Enterprise Applications** | [[paper]](https://arxiv.org/abs/2412.05449) | [code]

- [2024/12/06] **Enhancing LLMs for Impression Generation in Radiology Reports through a Multi-Agent System** | [[paper]](https://arxiv.org/abs/2412.06828) | [code]

- [2024/12/06] **TeamCraft: A Benchmark for Multi-Modal Multi-Agent Systems in Minecraft** | [[paper]](https://arxiv.org/abs/2412.05255) | [code]

- [2024/12/05] **Educational-Psychological Dialogue Robot Based on Multi-Agent Collaboration** | [[paper]](https://arxiv.org/abs/2412.03847) | [code]

- [2024/12/01] **Multi-Agent Collaboration in Incident Response with Large Language Models** | [[paper]](https://arxiv.org/abs/2412.00652) | [code]

- [2024/11/28] **MAG-V: A Multi-Agent Framework for Synthetic Data Generation and Verification** | [[paper]](https://arxiv.org/abs/2412.04494) | [code]

- [2024/11/21] **PIORS: Personalized Intelligent Outpatient Reception based on Large Language Model with Multi-Agents Medical Scenario Simulation** | [[paper]](https://arxiv.org/abs/2411.13902) | [code]

- [2024/11/21] **Enhancing LLMs for Power System Simulations: A Feedback-driven Multi-agent Framework** | [[paper]](https://arxiv.org/abs/2411.16707) | [code]

- [2024/11/18] **The Power of Many: Multi-Agent Multimodal Models for Cultural Image Captioning** | [[paper]](https://arxiv.org/abs/2411.11758) | [code]

- [2024/11/12] **BudgetMLAgent: A Cost-Effective LLM Multi-Agent system for Automating Machine Learning Tasks** | [[paper]](https://arxiv.org/abs/2411.07464) | [code]

- [2024/11/11] **Using Generative AI and Multi-Agents to Provide Automatic Feedback** | [[paper]](https://arxiv.org/abs/2411.07407) | [code]

- [2024/11/09] **Mixture of Knowledge Minigraph Agents for Literature Review Generation** | [[paper]](https://arxiv.org/abs/2411.06159) | [code]

- [2024/11/05] **SAUCE: Synchronous and Asynchronous User-Customizable Environment for Multi-Agent LLM Interaction** | [[paper]](https://arxiv.org/abs/2411.03397) | [code]

- [2024/11/05] **SMoA: Improving Multi-agent Large Language Models with Sparse Mixture-of-Agents** | [[paper]](https://arxiv.org/abs/2411.03284) | [code]

- [2024/11/01] **DARD: A Multi-Agent Approach for Task-Oriented Dialog Systems** | [[paper]](https://arxiv.org/abs/2411.00427) | [code]

- [2024/10/30] **ACC-Debate: An Actor-Critic Approach to Multi-Agent Debate** | [[paper]](https://arxiv.org/abs/2411.00053) | [code]

- [2024/10/29] **Flow-DPO: Improving LLM Mathematical Reasoning through Online Multi-Agent Learning** | [[paper]](https://arxiv.org/abs/2410.22304) | [code]

- [2024/10/29] **MARCO: Multi-Agent Real-time Chat Orchestration** | [[paper]](https://arxiv.org/abs/2410.21784) | [code]

- [2024/10/28] **CRAT: A Multi-Agent Framework for Causality-Enhanced Reflective and Retrieval-Augmented Translation with Large Language Models** | [[paper]](https://arxiv.org/abs/2410.21067) | [code]

- [2024/10/27] **AutoKaggle: A Multi-Agent Framework for Autonomous Data Science Competitions** | [[paper]](https://arxiv.org/abs/2410.20424) | [code]

- [2024/10/24] **Schema-Guided Culture-Aware Complex Event Simulation with Multi-Agent Role-Play** | [[paper]](https://arxiv.org/abs/2410.18935) | [code]

- [2024/10/23] **GraphTeam: Facilitating Large Language Model-based Graph Analysis via Multi-Agent Collaboration** | [[paper]](https://arxiv.org/abs/2410.18032) | [code]

- [2024/10/22] **Decoding Time Series with LLMs: A Multi-Agent Framework for Cross-Domain Annotation** | [[paper]](https://arxiv.org/abs/2410.17462) | [code]

- [2024/10/19] **An Electoral Approach to Diversify LLM-based Multi-Agent Collective Decision-Making** | [[paper]](https://arxiv.org/abs/2410.15168) | [code]

- [2024/10/18] **Synthesizing Post-Training Data for LLMs through Multi-Agent Simulation** | [[paper]](https://arxiv.org/abs/2410.14251) | [code]

- [2024/10/17] **AdaSwitch: Adaptive Switching between Small and Large Agents for Effective Cloud-Local Collaborative Learning** | [[paper]](https://arxiv.org/abs/2410.13181) | [code]

- [2024/10/16] **PRefLexOR: Preference-based Recursive Language Modeling for Exploratory Optimization of Reasoning and Agentic Thinking** | [[paper]](https://arxiv.org/abs/2410.12375) | [code]

- [2024/10/13] **LLM-Based Multi-Agent Systems are Scalable Graph Generative Models** | [[paper]](https://arxiv.org/abs/2410.09824) | [code]

- [2024/10/12] **Many Heads Are Better Than One: Improved Scientific Idea Generation by A LLM-Based Multi-Agent System** | [[paper]](https://arxiv.org/abs/2410.09403) | [code]

- [2024/10/11] **JAILJUDGE: A Comprehensive Jailbreak Judge Benchmark with Multi-Agent Enhanced Explanation Evaluation Framework** | [[paper]](https://arxiv.org/abs/2410.12855) | [code]

- [2024/10/11] **PEAR: A Robust and Flexible Automation Framework for Ptychography Enabled by Multiple Large Language Model Agents** | [[paper]](https://arxiv.org/abs/2410.09034) | [code]

- [2024/10/10] **AI-Press: A Multi-Agent News Generating and Feedback Simulation System Powered by Large Language Models** | [[paper]](https://arxiv.org/abs/2410.07561) | [code]

- [2024/10/10] **Multi-Agent Collaborative Data Selection for Efficient LLM Pretraining** | [[paper]](https://arxiv.org/abs/2410.08102) | [code]

- [2024/10/10] **Optima: Optimizing Effectiveness and Efficiency for LLM-Based Multi-Agent System** | [[paper]](https://arxiv.org/abs/2410.08115) | [code]

- [2024/10/10] **Prompt Engineering a Schizophrenia Chatbot: Utilizing a Multi-Agent Approach for Enhanced Compliance with Prompt Instructions** | [[paper]](https://arxiv.org/abs/2410.12848) | [code]

- [2024/10/10] **Diversity of Thought Elicits Stronger Reasoning Capabilities in Multi-Agent Debate Frameworks** | [[paper]](https://arxiv.org/abs/2410.12853) | [code]

- [2024/10/09] **Seeker: Enhancing Exception Handling in Code with LLM-based Multi-Agent Approach** | [[paper]](https://arxiv.org/abs/2410.06949) | [code]

- [2024/10/07] **Adversarial Multi-Agent Evaluation of Large Language Models through Iterative Debates** | [[paper]](https://arxiv.org/abs/2410.04663) | [code]

- [2024/10/06] **MindScope: Exploring cognitive biases in large language models through Multi-Agent Systems** | [[paper]](https://arxiv.org/abs/2410.04452) | [code]

- [2024/10/03] **Towards Implicit Bias Detection and Mitigation in Multi-Agent LLM Interactions** | [[paper]](https://arxiv.org/abs/2410.02584) | [code]

- [2024/10/03] **Agents&#39; Room: Narrative Generation through Multi-step Collaboration** | [[paper]](https://arxiv.org/abs/2410.02603) | [code]

- [2024/10/03] **Can Large Language Models Grasp Legal Theories? Enhance Legal Reasoning with Insights from Multi-Agent Collaboration** | [[paper]](https://arxiv.org/abs/2410.02507) | [code]

- [2024/10/03] **ColaCare: Enhancing Electronic Health Record Modeling through Large Language Model-Driven Multi-Agent Collaboration** | [[paper]](https://arxiv.org/abs/2410.02551) | [code]

- [2024/10/03] **AutoML-Agent: A Multi-Agent LLM Framework for Full-Pipeline AutoML** | [[paper]](https://arxiv.org/abs/2410.02958) | [code]

- [2024/10/02] **RGD: Multi-LLM Based Agent Debugger via Refinement and Generation Guidance** | [[paper]](https://arxiv.org/abs/2410.01242) | [code]

- [2024/10/02] **Zodiac: A Cardiologist-Level LLM Framework for Multi-Agent Diagnostics** | [[paper]](https://arxiv.org/abs/2410.02026) | [code]

- [2024/09/21] **Towards Automated Patent Workflows: AI-Orchestrated Multi-Agent Framework for Intellectual Property Management and Analysis** | [[paper]](https://arxiv.org/abs/2409.19006) | [code]

- [2024/09/21] **GroupDebate: Enhancing the Efficiency of Multi-Agent Debate Using Group Discussion** | [[paper]](https://arxiv.org/abs/2409.14051) | [code]

- [2024/09/20] **Minstrel: Structural Prompt Generation with Multi-Agents Coordination for Non-AI Experts** | [[paper]](https://arxiv.org/abs/2409.13449) | [code]

- [2024/09/18] **MAgICoRe: Multi-Agent, Iterative, Coarse-to-Fine Refinement for Reasoning** | [[paper]](https://arxiv.org/abs/2409.12147) | [code]

- [2024/09/17] **The Art of Storytelling: Multi-Agent Generative AI for Dynamic Multimodal Narratives** | [[paper]](https://arxiv.org/abs/2409.11261) | [code]

- [2024/09/16] **Instigating Cooperation among LLM Agents Using Adaptive Information Modulation** | [[paper]](https://arxiv.org/abs/2409.10372) | [code]

- [2024/09/14] **Synergistic Simulations: Multi-Agent Problem Solving with Large Language Models** | [[paper]](https://arxiv.org/abs/2409.13753) | [code]

- [2024/09/12] **Knowledge Tagging with Large Language Model based Multi-Agent System** | [[paper]](https://arxiv.org/abs/2409.08406) | [code]

- [2024/09/11] **Propaganda to Hate: A Multimodal Analysis of Arabic Memes with Multi-Agent LLMs** | [[paper]](https://arxiv.org/abs/2409.07246) | [code]

- [2024/09/09] **SciAgents: Automating scientific discovery through multi-agent intelligent graph reasoning** | [[paper]](https://arxiv.org/abs/2409.05556) | [code]

- [2024/09/06] **Using Large Language Models to Generate Authentic Multi-agent Knowledge Work Datasets** | [[paper]](https://arxiv.org/abs/2409.04286) | [code]

- [2024/09/05] **xLAM: A Family of Large Action Models to Empower AI Agent Systems** | [[paper]](https://arxiv.org/abs/2409.03215) | [code]

- [2024/09/02] **Co-Learning: Code Learning for Multi-Agent Reinforcement Collaborative Framework with Conversational Natural Language Interfaces** | [[paper]](https://arxiv.org/abs/2409.00985) | [code]

- [2024/08/28] **BattleAgentBench: A Benchmark for Evaluating Cooperation and Competition Capabilities of Language Models in Multi-Agent Systems** | [[paper]](https://arxiv.org/abs/2408.15971) | [code]

- [2024/08/27] **AgentMonitor: A Plug-and-Play Framework for Predictive and Secure Multi-Agent Systems** | [[paper]](https://arxiv.org/abs/2408.14972) | [code]

- [2024/08/24] **Towards Human-Level Understanding of Complex Process Engineering Schematics: A Pedagogical, Introspective Multi-Agent Framework for Open-Domain Question Answering** | [[paper]](https://arxiv.org/abs/2409.00082) | [code]

- [2024/08/22] **MuMA-ToM: Multi-modal Multi-Agent Theory of Mind** | [[paper]](https://arxiv.org/abs/2408.12574) | [code]

- [2024/08/21] **DreamFactory: Pioneering Multi-Scene Long Video Generation with a Multi-Agent Framework** | [[paper]](https://arxiv.org/abs/2408.11788) | [code]

- [2024/08/16] **The Fellowship of the LLMs: Multi-Agent Workflows for Synthetic Preference Optimization Dataset Generation** | [[paper]](https://arxiv.org/abs/2408.08688) | [code]

- [2024/08/15] **MAG-SQL: Multi-Agent Generative Approach with Soft Schema Linking and Iterative Sub-SQL Refinement for Text-to-SQL** | [[paper]](https://arxiv.org/abs/2408.07930) | [code]

- [2024/08/15] **Text2BIM: Generating Building Models Using a Large Language Model-based Multi-Agent Framework** | [[paper]](https://arxiv.org/abs/2408.08054) | [code]

- [2024/08/14] **Development of a Large Language Model-based Multi-Agent Clinical Decision Support System for Korean Triage and Acuity Scale (KTAS)-Based Triage and Treatment Planning in Emergency Departments** | [[paper]](https://arxiv.org/abs/2408.07531) | [code]

- [2024/08/08] **Can LLMs Beat Humans in Debating? A Dynamic Multi-agent Framework for Competitive Debate** | [[paper]](https://arxiv.org/abs/2408.04472) | [code]

- [2024/08/05] **ReDel: A Toolkit for LLM-Powered Recursive Multi-Agent Systems** | [[paper]](https://arxiv.org/abs/2408.02248) | [code]

- [2024/08/05] **Evaluating and Enhancing LLMs Agent based on Theory of Mind in Guandan: A Multi-Player Cooperative Game under Imperfect Information** | [[paper]](https://arxiv.org/abs/2408.02559) | [code]

- [2024/07/23] **LawLuo: A Multi-Agent Collaborative Framework for Multi-Round Chinese Legal Consultation** | [[paper]](https://arxiv.org/abs/2407.16252) | [code]

- [2024/07/21] **Multi-Agent Causal Discovery Using Large Language Models** | [[paper]](https://arxiv.org/abs/2407.15073) | [code]

- [2024/07/19] **NeLLCom-X: A Comprehensive Neural-Agent Framework to Simulate Language Learning and Group Communication** | [[paper]](https://arxiv.org/abs/2407.13999) | [code]

- [2024/07/17] **Towards Collaborative Intelligence: Propagating Intentions and Reasoning for Multi-Agent Coordination with Large Language Models** | [[paper]](https://arxiv.org/abs/2407.12532) | [code]

- [2024/07/16] **InvAgent: A Large Language Model based Multi-Agent System for Inventory Management in Supply Chains** | [[paper]](https://arxiv.org/abs/2407.11384) | [code]

- [2024/07/13] **Synergistic Multi-Agent Framework with Trajectory Learning for Knowledge-Intensive Tasks** | [[paper]](https://arxiv.org/abs/2407.09893) | [code]

- [2024/07/13] **Cohesive Conversations: Enhancing Authenticity in Multi-Agent Simulated Dialogues** | [[paper]](https://arxiv.org/abs/2407.09897) | [code]

- [2024/07/10] **Flooding Spread of Manipulated Knowledge in LLM-Based Multi-Agent Communities** | [[paper]](https://arxiv.org/abs/2407.07791) | [code]

- [2024/07/09] **FinCon: A Synthesized LLM Multi-Agent System with Conceptual Verbal Reinforcement for Enhanced Financial Decision Making** | [[paper]](https://arxiv.org/abs/2407.06567) | [code]

- [2024/07/09] **Internet of Agents: Weaving a Web of Heterogeneous Agents for Collaborative Intelligence** | [[paper]](https://arxiv.org/abs/2407.07061) | [code]

- [2024/07/04] **Solving Zebra Puzzles Using Constraint-Guided Multi-Agent Systems** | [[paper]](https://arxiv.org/abs/2407.03956) | [code]

- [2024/07/03] **MentalAgora: A Gateway to Advanced Personalized Care in Mental Health through Multi-Agent Debating and Attribute Control** | [[paper]](https://arxiv.org/abs/2407.02736) | [code]

- [2024/06/17] **Improving Multi-Agent Debate with Sparse Communication Topology** | [[paper]](https://arxiv.org/abs/2406.11776) | [code]

- [2024/06/13] **Multi-Agent Software Development through Cross-Team Collaboration** | [[paper]](https://arxiv.org/abs/2406.08979) | [[code]](https://github.com/openbmb/chatdev)

- [2024/06/11] **CoEvol: Constructing Better Responses for Instruction Finetuning through Multi-Agent Cooperation** | [[paper]](https://arxiv.org/abs/2406.07054) | [[code]](https://github.com/lirenhao1997/coevol)

- [2024/06/07] **Mixture-of-Agents Enhances Large Language Model Capabilities** | [[paper]](https://arxiv.org/abs/2406.04692) | [code]

- [2024/06/05] **Towards Detecting LLMs Hallucination via Markov Chain-based Multi-agent Debate Framework** | [[paper]](https://arxiv.org/abs/2406.03075) | [code]

- [2024/06/04] **Chain of Agents: Large Language Models Collaborating on Long-Context Tasks** | [[paper]](https://arxiv.org/abs/2406.02818) | [code]

- [2024/06/03] **Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration** | [[paper]](https://arxiv.org/abs/2406.01014) | [[code]](https://github.com/x-plug/mobileagent)

- [2024/05/30] **Safe Multi-agent Reinforcement Learning with Natural Language Constraints** | [[paper]](https://arxiv.org/abs/2405.20018) | [code]

- [2024/05/23] **CityGPT: Towards Urban IoT Learning, Analysis and Interaction with Multi-Agent System** | [[paper]](https://arxiv.org/abs/2405.14691) | [code]

- [2024/05/20] **(Perhaps) Beyond Human Translation: Harnessing Multi-Agent Collaboration for Translating Ultra-Long Literary Texts** | [[paper]](https://arxiv.org/abs/2405.11804) | [code]

- [2024/05/10] **LLM Discussion: Enhancing the Creativity of Large Language Models via Discussion Framework and Role-Play** | [[paper]](https://arxiv.org/abs/2405.06373) | [code]

- [2024/05/07] **Enhancing the Efficiency and Accuracy of Underlying Asset Reviews in Structured Finance: The Application of Multi-agent Framework** | [[paper]](https://arxiv.org/abs/2405.04294) | [code]

- [2024/05/06] **Persona Inconstancy in Multi-Agent LLM Collaboration: Conformity, Confabulation, and Impersonation** | [[paper]](https://arxiv.org/abs/2405.03862) | [code]

- [2024/05/05] **Language Evolution for Evading Social Media Regulation via LLM-based Multi-agent Simulation** | [[paper]](https://arxiv.org/abs/2405.02858) | [code]

- [2024/04/25] **Cooperate or Collapse: Emergence of Sustainable Cooperation in a Society of LLM Agents** | [[paper]](https://arxiv.org/abs/2404.16698) | [code]

- [2024/04/23] **ClinicalAgent: Clinical Trial Multi-Agent System with Large Language Model-based Reasoning** | [[paper]](https://arxiv.org/abs/2404.14777) | [code]

- [2024/04/14] **Confidence Calibration and Rationalization for LLMs via Multi-Agent Deliberation** | [[paper]](https://arxiv.org/abs/2404.09127) | [code]

- [2024/04/12] **Leveraging Multi-AI Agents for Cross-Domain Knowledge Discovery** | [[paper]](https://arxiv.org/abs/2404.08511) | [code]

- [2024/04/09] **Foundation Models to the Rescue: Deadlock Resolution in Connected Multi-Robot Systems** | [[paper]](https://arxiv.org/abs/2404.06413) | [code]

- [2024/04/08] **360$^\circ$REA: Towards A Reusable Experience Accumulation with 360{\deg} Assessment for Multi-Agent System** | [[paper]](https://arxiv.org/abs/2404.05569) | [code]

- [2024/04/06] **MACM: Utilizing a Multi-Agent System for Condition Mining in Solving Complex Mathematical Problems** | [[paper]](https://arxiv.org/abs/2404.04735) | [[code]](https://github.com/bin123apple/macm)

- [2024/04/02] **Self-Organized Agents: A LLM Multi-Agent Framework toward Ultra Large-Scale Code Generation and Optimization** | [[paper]](https://arxiv.org/abs/2404.02183) | [code]

- [2024/04/02] **CMAT: A Multi-Agent Collaboration Tuning Framework for Enhancing Small Language Models** | [[paper]](https://arxiv.org/abs/2404.01663) | [code]

- [2024/03/26] **MAGIS: LLM-Based Multi-Agent Framework for GitHub Issue Resolution** | [[paper]](https://arxiv.org/abs/2403.17927) | [code]

- [2024/03/22] **CACA Agent: Capability Collaboration based AI Agent** | [[paper]](https://arxiv.org/abs/2403.15137) | [code]

- [2024/03/21] **Multi-Agent VQA: Exploring Multi-Agent Foundation Models in Zero-Shot Visual Question Answering** | [[paper]](https://arxiv.org/abs/2403.14783) | [code]

- [2024/03/19] **Embodied LLM Agents Learn to Cooperate in Organized Teams** | [[paper]](https://arxiv.org/abs/2403.12482) | [code]

- [2024/03/12] **Transforming Competition into Collaboration: The Revolutionary Role of Multi-Agent Systems and Language Models in Modern Organizations** | [[paper]](https://arxiv.org/abs/2403.07769) | [code]

- [2024/03/02] **AutoDefense: Multi-Agent LLM Defense against Jailbreak Attacks** | [[paper]](https://arxiv.org/abs/2403.04783) | [code]

- [2024/02/28] **Rethinking the Bounds of LLM Reasoning: Are Multi-Agent Discussions the Key?** | [[paper]](https://arxiv.org/abs/2402.18272) | [code]

- [2024/02/26] **Chain-of-Discussion: A Multi-Model Framework for Complex Evidence-Based Question Answering** | [[paper]](https://arxiv.org/abs/2402.16313) | [code]

- [2024/02/26] **LLMArena: Assessing Capabilities of Large Language Models in Dynamic Multi-Agent Environments** | [[paper]](https://arxiv.org/abs/2402.16499) | [code]

- [2024/02/21] **LLM Based Multi-Agent Generation of Semi-structured Documents from Semantic Templates in the Public Administration Domain** | [[paper]](https://arxiv.org/abs/2402.14871) | [code]

- [2024/02/18] **Benchmark Self-Evolving: A Multi-Agent Framework for Dynamic LLM Evaluation** | [[paper]](https://arxiv.org/abs/2402.11443) | [[code]](https://github.com/nanshineloong/self-evolving-benchmark)

- [2024/02/18] **LongAgent: Scaling Language Models to 128k Context through Multi-Agent Collaboration** | [[paper]](https://arxiv.org/abs/2402.11550) | [code]

- [2024/02/15] **TDAG: A Multi-Agent Framework based on Dynamic Task Decomposition and Agent Generation** | [[paper]](https://arxiv.org/abs/2402.10178) | [code]

- [2024/02/03] **More Agents Is All You Need** | [[paper]](https://arxiv.org/abs/2402.05120) | [code]

- [2024/02/02] **Reasoning Capacity in Multi-Agent Systems: Limitations, Challenges and Human-Centered Solutions** | [[paper]](https://arxiv.org/abs/2402.01108) | [code]

- [2024/02/02] **A Multi-Agent Conversational Recommender System** | [[paper]](https://arxiv.org/abs/2402.01135) | [code]

- [2024/01/11] **Combating Adversarial Attacks with Multi-Agent Debate** | [[paper]](https://arxiv.org/abs/2401.05998) | [code]

- [2024/01/08] **MARG: Multi-Agent Review Generation for Scientific Papers** | [[paper]](https://arxiv.org/abs/2401.04259) | [code]

- [2024/01/08] **SpeechAgents: Human-Communication Simulation with Multi-Modal Multi-Agent Systems** | [[paper]](https://arxiv.org/abs/2401.03945) | [code]

- [2024/01/08] **Why Solving Multi-agent Path Finding with Large Language Model has not Succeeded Yet** | [[paper]](https://arxiv.org/abs/2401.03630) | [code]

- [2023/12/20] **AgentCoder: Multi-Agent-based Code Generation with Iterative Testing and Optimisation** | [[paper]](https://arxiv.org/abs/2312.13010) | [code]

- [2023/10/31] **Multi-Agent Consensus Seeking via Large Language Models** | [[paper]](https://arxiv.org/abs/2310.20151) | [code]

- [2023/10/25] **MultiPrompter: Cooperative Prompt Optimization with Multi-Agent Reinforcement Learning** | [[paper]](https://arxiv.org/abs/2310.16730) | [code]

- [2023/08/22] **ProAgent: Building Proactive Cooperative Agents with Large Language Models** | [[paper]](https://arxiv.org/abs/2308.11339) | [code]

- [2023/08/21] **AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors** | [[paper]](https://arxiv.org/abs/2308.10848) | [code]

- [2023/08/14] **ChatEval: Towards Better LLM-based Evaluators through Multi-Agent Debate** | [[paper]](https://arxiv.org/abs/2308.07201) | [code]

- [2023/08/01] **MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework** | [[paper]](https://arxiv.org/abs/2308.00352) | [code]

- [2023/06/05] **Multi-Agent Collaboration: Harnessing the Power of Intelligent LLM Agents** | [[paper]](https://arxiv.org/abs/2306.03314) | [code]

- [2023/05/31] **Recursive Metropolis-Hastings Naming Game: Symbol Emergence in a Multi-agent System based on Probabilistic Generative Models** | [[paper]](https://arxiv.org/abs/2305.19761) | [code]

- [2023/05/30] **Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate** | [[paper]](https://arxiv.org/abs/2305.19118) | [code]

- [2023/04/26] **Multi-Party Chat: Conversational Agents in Group Settings with Humans and Models** | [[paper]](https://arxiv.org/abs/2304.13835) | [code]

- [2023/04/24] **ChatLLM Network: More brains, More intelligence** | [[paper]](https://arxiv.org/abs/2304.12998) | [code]

### Stability
#### Safety
- [2025/02/20] **CORBA: Contagious Recursive Blocking Attacks on Multi-Agent Systems Based on Large Language Models** | [[paper]](https://arxiv.org/abs/2502.14529) | [code]

- [2025/02/18] **AEIA-MN: Evaluating the Robustness of Multimodal LLM-Powered Mobile Agents Against Active Environmental Injection Attacks** | [[paper]](https://arxiv.org/abs/2502.13053) | [code]

- [2025/02/17] **&#34;Nuclear Deployed!&#34;: Analyzing Catastrophic Risks in Decision-making of Autonomous LLM Agents** | [[paper]](https://arxiv.org/abs/2502.11355) | [code]

- [2025/02/01] **ALU: Agentic LLM Unlearning** | [[paper]](https://arxiv.org/abs/2502.00406) | [code]

- [2025/01/28] **Context is Key for Agent Security** | [[paper]](https://arxiv.org/abs/2501.17070) | [code]

- [2024/12/21] **The Task Shield: Enforcing Task Alignment to Defend Against Indirect Prompt Injection in LLM Agents** | [[paper]](https://arxiv.org/abs/2412.16682) | [code]

- [2024/12/16] **Seeker: Towards Exception Safety Code Generation with Intermediate Language Agents Framework** | [[paper]](https://arxiv.org/abs/2412.11713) | [code]

- [2024/12/09] **The Fusion of Large Language Models and Formal Methods for Trustworthy AI Agents: A Roadmap** | [[paper]](https://arxiv.org/abs/2412.06512) | [code]

- [2024/11/08] **Towards Low-Resource Harmful Meme Detection with LMM Agents** | [[paper]](https://arxiv.org/abs/2411.05383) | [code]

- [2024/11/06] **MRJ-Agent: An Effective Jailbreak Agent for Multi-Round Dialogue** | [[paper]](https://arxiv.org/abs/2411.03814) | [code]

- [2024/11/04] **Attacking Vision-Language Computer Agents via Pop-ups** | [[paper]](https://arxiv.org/abs/2411.02391) | [code]

- [2024/10/22] **AdvWeb: Controllable Black-box Attacks on VLM-powered Web Agents** | [[paper]](https://arxiv.org/abs/2410.17401) | [code]

- [2024/10/18] **Coherence-Driven Multimodal Safety Dialogue with Active Learning for Embodied Agents** | [[paper]](https://arxiv.org/abs/2410.14141) | [code]

- [2024/10/11] **AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents** | [[paper]](https://arxiv.org/abs/2410.09024) | [code]

- [2024/10/09] **I Want to Break Free! Persuasion and Anti-Social Behavior of LLMs in Multi-Agent Settings with Social Hierarchy** | [[paper]](https://arxiv.org/abs/2410.07109) | [code]

- [2024/09/28] **SELP: Generating Safe and Efficient Task Plans for Robot Agents with Large Language Models** | [[paper]](https://arxiv.org/abs/2409.19471) | [code]

- [2024/09/17] **EIA: Environmental Injection Attack on Generalist Web Agents for Privacy Leakage** | [[paper]](https://arxiv.org/abs/2409.11295) | [code]

- [2024/09/13] **AI-LieDar: Examine the Trade-off Between Utility and Truthfulness in LLM Agents** | [[paper]](https://arxiv.org/abs/2409.09013) | [code]

- [2024/08/20] **Athena: Safe Autonomous Agents with Verbal Contrastive Learning** | [[paper]](https://arxiv.org/abs/2408.11021) | [code]

- [2024/08/05] **Caution for the Environment: Multimodal Agents are Susceptible to Environmental Distractions** | [[paper]](https://arxiv.org/abs/2408.02544) | [code]

- [2024/07/23] **RedAgent: Red Teaming Large Language Models with Context-aware Autonomous Language Agent** | [[paper]](https://arxiv.org/abs/2407.16667) | [code]

- [2024/06/05] **BadAgent: Inserting and Activating Backdoor Attacks in LLM Agents** | [[paper]](https://arxiv.org/abs/2406.03007) | [[code]](https://github.com/dpamk/badagent)

- [2024/05/30] **Safe Multi-agent Reinforcement Learning with Natural Language Constraints** | [[paper]](https://arxiv.org/abs/2405.20018) | [code]

- [2024/05/24] **Hacc-Man: An Arcade Game for Jailbreaking LLMs** | [[paper]](https://arxiv.org/abs/2405.15902) | [code]

- [2024/03/02] **AutoDefense: Multi-Agent LLM Defense against Jailbreak Attacks** | [[paper]](https://arxiv.org/abs/2403.04783) | [code]

- [2024/02/17] **Watch Out for Your Agents! Investigating Backdoor Threats to LLM-Based Agents** | [[paper]](https://arxiv.org/abs/2402.11208) | [code]

- [2024/02/16] **ToolSword: Unveiling Safety Issues of Large Language Models in Tool Learning Across Three Stages** | [[paper]](https://arxiv.org/abs/2402.10753) | [[code]](https://github.com/junjie-ye/toolsword)

- [2024/02/02] **TrustAgent: Towards Safe and Trustworthy LLM-based Agents** | [[paper]](https://arxiv.org/abs/2402.01586) | [code]

- [2024/01/11] **Combating Adversarial Attacks with Multi-Agent Debate** | [[paper]](https://arxiv.org/abs/2401.05998) | [code]

- [2023/11/17] **Testing Language Model Agents Safely in the Wild** | [[paper]](https://arxiv.org/abs/2311.10538) | [code]

#### Bias
- [2025/01/29] **Actions Speak Louder than Words: Agent Decisions Reveal Implicit Biases in Language Models** | [[paper]](https://arxiv.org/abs/2501.17420) | [code]

- [2025/01/24] **Unmasking Conversational Bias in AI Multiagent Systems** | [[paper]](https://arxiv.org/abs/2501.14844) | [code]

- [2024/12/20] **Mitigating Social Bias in Large Language Models: A Multi-Objective Approach within a Multi-Agent Framework** | [[paper]](https://arxiv.org/abs/2412.15504) | [code]

- [2024/11/12] **Mitigating Bias in Queer Representation within Large Language Models: A Collaborative Agent Approach** | [[paper]](https://arxiv.org/abs/2411.07656) | [code]

- [2024/10/06] **MindScope: Exploring cognitive biases in large language models through Multi-Agent Systems** | [[paper]](https://arxiv.org/abs/2410.04452) | [code]

- [2024/10/03] **Towards Implicit Bias Detection and Mitigation in Multi-Agent LLM Interactions** | [[paper]](https://arxiv.org/abs/2410.02584) | [code]

- [2024/05/23] **ALI-Agent: Assessing LLMs&#39; Alignment with Human Values via Agent-based Evaluation** | [[paper]](https://arxiv.org/abs/2405.14125) | [code]

- [2024/04/23] **Aligning LLM Agents by Learning Latent Preference from User Edits** | [[paper]](https://arxiv.org/abs/2404.15269) | [code]

- [2024/02/19] **Polarization of Autonomous Generative AI Agents Under Echo Chambers** | [[paper]](https://arxiv.org/abs/2402.12212) | [code]

- [2024/02/14] **Towards better Human-Agent Alignment: Assessing Task Utility in LLM-Powered Applications** | [[paper]](https://arxiv.org/abs/2402.09015) | [code]

- [2024/01/09] **Agent Alignment in Evolving Social Norms** | [[paper]](https://arxiv.org/abs/2401.04620) | [code]

#### Hallucination
- [2025/02/14] **Automated Hypothesis Validation with Agentic Sequential Falsifications** | [[paper]](https://arxiv.org/abs/2502.09858) | [code]

- [2025/02/04] **Position: Stop Acting Like Language Model Agents Are Normal Agents** | [[paper]](https://arxiv.org/abs/2502.10420) | [code]

- [2025/02/03] **SelfCheckAgent: Zero-Resource Hallucination Detection in Generative Large Language Models** | [[paper]](https://arxiv.org/abs/2502.01812) | [code]

- [2025/01/19] **Hallucination Mitigation using Agentic AI Natural Language-Based Frameworks** | [[paper]](https://arxiv.org/abs/2501.13946) | [code]

- [2024/11/25] **Enhancing Multi-Agent Consensus through Third-Party LLM Integration: Analyzing Uncertainty and Mitigating Hallucinations in Large Language Models** | [[paper]](https://arxiv.org/abs/2411.16189) | [code]

- [2024/11/12] **SHARP: Unlocking Interactive Hallucination via Stance Transfer in Role-Playing Agents** | [[paper]](https://arxiv.org/abs/2411.07965) | [code]

- [2024/07/08] **DebUnc: Mitigating Hallucinations in Large Language Model Agent Communication with Uncertainty Estimations** | [[paper]](https://arxiv.org/abs/2407.06426) | [code]

- [2024/06/29] **BioKGBench: A Knowledge Graph Checking Benchmark of AI Agent for Biomedical Science** | [[paper]](https://arxiv.org/abs/2407.00466) | [code]

- [2024/06/17] **Small Agent Can Also Rock! Empowering Small Language Models as Hallucination Detector** | [[paper]](https://arxiv.org/abs/2406.11277) | [code]

- [2024/06/05] **Towards Detecting LLMs Hallucination via Markov Chain-based Multi-agent Debate Framework** | [[paper]](https://arxiv.org/abs/2406.03075) | [code]

- [2024/05/28] **TimeChara: Evaluating Point-in-Time Character Hallucination of Role-Playing Large Language Models** | [[paper]](https://arxiv.org/abs/2405.18027) | [code]

- [2024/02/13] **Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast** | [[paper]](https://arxiv.org/abs/2402.08567) | [[code]](https://github.com/sail-sg/agent-smith)

### Infrastructure
#### Benchmark&Evaluation
- [2025/02/20] **MLGym: A New Framework and Benchmark for Advancing AI Research Agents** | [[paper]](https://arxiv.org/abs/2502.14499) | [code]

- [2025/02/19] **DataSciBench: An LLM Agent Benchmark for Data Science** | [[paper]](https://arxiv.org/abs/2502.13897) | [code]

- [2025/02/13] **EmbodiedBench: Comprehensive Benchmarking Multi-modal Large Language Models for Vision-Driven Embodied Agents** | [[paper]](https://arxiv.org/abs/2502.09560) | [code]

- [2025/02/07] **Evaluating Personality Traits in Large Language Models: Insights from Psychological Questionnaires** | [[paper]](https://arxiv.org/abs/2502.05248) | [code]

- [2025/02/06] **Robotouille: An Asynchronous Planning Benchmark for LLM Agents** | [[paper]](https://arxiv.org/abs/2502.05227) | [code]

- [2025/02/01] **Who&#39;s the MVP? A Game-Theoretic Evaluation Benchmark for Modular Attribution in LLM Agents** | [[paper]](https://arxiv.org/abs/2502.00510) | [code]

- [2025/01/21] **EmbodiedEval: Evaluate Multimodal LLMs as Embodied Agents** | [[paper]](https://arxiv.org/abs/2501.11858) | [code]

- [2024/12/23] **LegalAgentBench: Evaluating LLM Agents in Legal Domain** | [[paper]](https://arxiv.org/abs/2412.17259) | [code]

- [2024/12/19] **Agent-SafetyBench: Evaluating the Safety of LLM Agents** | [[paper]](https://arxiv.org/abs/2412.14470) | [code]

- [2024/12/18] **TheAgentCompany: Benchmarking LLM Agents on Consequential Real World Tasks** | [[paper]](https://arxiv.org/abs/2412.14161) | [code]

- [2024/12/18] **ChinaTravel: A Real-World Benchmark for Language Agents in Chinese Travel Planning** | [[paper]](https://arxiv.org/abs/2412.13682) | [code]

- [2024/12/06] **TeamCraft: A Benchmark for Multi-Modal Multi-Agent Systems in Minecraft** | [[paper]](https://arxiv.org/abs/2412.05255) | [code]

- [2024/12/02] **Medchain: Bridging the Gap Between LLM Agents and Clinical Practice through Interactive Sequential Benchmarking** | [[paper]](https://arxiv.org/abs/2412.01605) | [code]

- [2024/11/05] **Benchmarking Multimodal Retrieval Augmented Generation with Dynamic VQA Dataset and Self-adaptive Planning Agent** | [[paper]](https://arxiv.org/abs/2411.02937) | [code]

- [2024/10/28] **Can Machines Think Like Humans? A Behavioral Evaluation of LLM-Agents in Dictator Games** | [[paper]](https://arxiv.org/abs/2410.21359) | [code]

- [2024/10/25] **AgentSense: Benchmarking Social Intelligence of Language Agents through Interactive Scenarios** | [[paper]](https://arxiv.org/abs/2410.19346) | [code]

- [2024/10/25] **AGENT-CQ: Automatic Generation and Evaluation of Clarifying Questions for Conversational Search with LLMs** | [[paper]](https://arxiv.org/abs/2410.19692) | [code]

- [2024/10/23] **MobileSafetyBench: Evaluating Safety of Autonomous Agents in Mobile Device Control** | [[paper]](https://arxiv.org/abs/2410.17520) | [code]

- [2024/10/16] **Proactive Agent: Shifting LLM Agents from Reactive Responses to Active Assistance** | [[paper]](https://arxiv.org/abs/2410.12361) | [code]

- [2024/10/15] **Revisiting Benchmark and Assessment: An Agent-based Exploratory Dynamic Evaluation Framework for LLMs** | [[paper]](https://arxiv.org/abs/2410.11507) | [code]

- [2024/10/11] **JAILJUDGE: A Comprehensive Jailbreak Judge Benchmark with Multi-Agent Enhanced Explanation Evaluation Framework** | [[paper]](https://arxiv.org/abs/2410.12855) | [code]

- [2024/10/11] **AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents** | [[paper]](https://arxiv.org/abs/2410.09024) | [code]

- [2024/10/10] **Benchmarking Agentic Workflow Generation** | [[paper]](https://arxiv.org/abs/2410.07869) | [code]

- [2024/10/09] **MLE-bench: Evaluating Machine Learning Agents on Machine Learning Engineering** | [[paper]](https://arxiv.org/abs/2410.07095) | [code]

- [2024/10/09] **Embodied Agent Interface: Benchmarking LLMs for Embodied Decision Making** | [[paper]](https://arxiv.org/abs/2410.07166) | [code]

- [2024/10/09] **DA-Code: Agent Data Science Code Generation Benchmark for Large Language Models** | [[paper]](https://arxiv.org/abs/2410.07331) | [code]

- [2024/10/07] **Adversarial Multi-Agent Evaluation of Large Language Models through Iterative Debates** | [[paper]](https://arxiv.org/abs/2410.04663) | [code]

- [2024/10/07] **ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery** | [[paper]](https://arxiv.org/abs/2410.05080) | [code]

- [2024/09/23] **Towards a Realistic Long-Term Benchmark for Open-Web Research Agents** | [[paper]](https://arxiv.org/abs/2409.14913) | [code]

- [2024/09/17] **CORE-Bench: Fostering the Credibility of Published Research Through a Computational Reproducibility Agent Benchmark** | [[paper]](https://arxiv.org/abs/2409.11363) | [code]

- [2024/09/12] **DSBench: How Far Are Data Science Agents to Becoming Data Science Experts?** | [[paper]](https://arxiv.org/abs/2409.07703) | [code]

- [2024/09/11] **SUPER: Evaluating Agents on Setting Up and Executing Tasks from Research Repositories** | [[paper]](https://arxiv.org/abs/2409.07440) | [code]

- [2024/09/02] **ComfyBench: Benchmarking LLM-based Agents in ComfyUI for Autonomously Designing Collaborative AI Systems** | [[paper]](https://arxiv.org/abs/2409.01392) | [code]

- [2024/08/28] **BattleAgentBench: A Benchmark for Evaluating Cooperation and Competition Capabilities of Language Models in Multi-Agent Systems** | [[paper]](https://arxiv.org/abs/2408.15971) | [code]

- [2024/08/19] **BLADE: Benchmarking Language Model Agents for Data-Driven Science** | [[paper]](https://arxiv.org/abs/2408.09667) | [code]

- [2024/08/13] **What should I wear to a party in a Greek taverna? Evaluation for Conversational Agents in the Fashion Domain** | [[paper]](https://arxiv.org/abs/2408.08907) | [code]

- [2024/08/12] **VisualAgentBench: Towards Large Multimodal Models as Visual Foundation Agents** | [[paper]](https://arxiv.org/abs/2408.06327) | [code]

- [2024/07/26] **OfficeBench: Benchmarking Language Agents across Multiple Applications for Office Automation** | [[paper]](https://arxiv.org/abs/2407.19056) | [code]

- [2024/07/26] **AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents** | [[paper]](https://arxiv.org/abs/2407.18901) | [code]

- [2024/07/25] **PersonaGym: Evaluating Persona Agents and LLMs** | [[paper]](https://arxiv.org/abs/2407.18416) | [code]

- [2024/07/23] **AMONGAGENTS: Evaluating Large Language Models in the Interactive Text-Based Social Deduction Game** | [[paper]](https://arxiv.org/abs/2407.16521) | [code]

- [2024/07/22] **AssistantBench: Can Web Agents Solve Realistic and Time-Consuming Tasks?** | [[paper]](https://arxiv.org/abs/2407.15711) | [code]

- [2024/07/12] **IDAT: A Multi-Modal Dataset and Toolkit for Building and Evaluating Interactive Task-Solving Agents** | [[paper]](https://arxiv.org/abs/2407.08898) | [code]

- [2024/07/11] **GTA: A Benchmark for General Tool Agents** | [[paper]](https://arxiv.org/abs/2407.08713) | [code]

- [2024/07/05] **Towards Automated Functional Equation Proving: A Benchmark Dataset and A Domain-Specific In-Context Agent** | [[paper]](https://arxiv.org/abs/2407.14521) | [code]

- [2024/07/01] **MIRAI: Evaluating LLM Agents for Event Forecasting** | [[paper]](https://arxiv.org/abs/2407.01231) | [code]

- [2024/07/01] **ProductAgent: Benchmarking Conversational Product Search Agent with Asking Clarification Questions** | [[paper]](https://arxiv.org/abs/2407.00942) | [code]

- [2024/07/01] **Mobile-Bench: An Evaluation Benchmark for LLM-based Mobile Agents** | [[paper]](https://arxiv.org/abs/2407.00993) | [code]

- [2024/06/28] **Designing and Evaluating Multi-Chatbot Interface for Human-AI Communication: Preliminary Findings from a Persuasion Task** | [[paper]](https://arxiv.org/abs/2406.19648) | [code]

- [2024/06/13] **ResearchArena: Benchmarking Large Language Models&#39; Ability to Collect and Organize Information as Research Agents** | [[paper]](https://arxiv.org/abs/2406.10291) | [code]

- [2024/06/13] **StreamBench: Towards Benchmarking Continuous Improvement of Language Agents** | [[paper]](https://arxiv.org/abs/2406.08747) | [code]

- [2024/06/07] **WildBench: Benchmarking LLMs with Challenging Tasks from Real Users in the Wild** | [[paper]](https://arxiv.org/abs/2406.04770) | [[code]](https://github.com/allenai/wildbench)

- [2024/06/07] **GameBench: Evaluating Strategic Reasoning Abilities of LLM Agents** | [[paper]](https://arxiv.org/abs/2406.06613) | [[code]](https://github.com/Joshuaclymer/GameBench)

- [2024/05/28] **TimeChara: Evaluating Point-in-Time Character Hallucination of Role-Playing Large Language Models** | [[paper]](https://arxiv.org/abs/2405.18027) | [code]

- [2024/05/23] **AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents** | [[paper]](https://arxiv.org/abs/2405.14573) | [code]

- [2024/05/13] **AgentClinic: a multimodal agent benchmark to evaluate AI in simulated clinical environments** | [[paper]](https://arxiv.org/abs/2405.07960) | [code]

- [2024/05/01] **WorkBench: a Benchmark Dataset for Agents in a Realistic Workplace Setting** | [[paper]](https://arxiv.org/abs/2405.00823) | [[code]](https://github.com/olly-styles/workbench)

- [2024/04/23] **Evaluating Tool-Augmented Agents in Remote Sensing Platforms** | [[paper]](https://arxiv.org/abs/2405.00709) | [code]

- [2024/04/22] **How Well Can LLMs Echo Us? Evaluating AI Chatbots&#39; Role-Play Ability with ECHO** | [[paper]](https://arxiv.org/abs/2404.13957) | [code]

- [2024/04/15] **MMInA: Benchmarking Multihop Multimodal Internet Agents** | [[paper]](https://arxiv.org/abs/2404.09992) | [[code]](https://github.com/shulin16/mmina)

- [2024/04/11] **OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments** | [[paper]](https://arxiv.org/abs/2404.07972) | [code]

- [2024/04/09] **AgentQuest: A Modular Benchmark Framework to Measure Progress and Improve LLM Agents** | [[paper]](https://arxiv.org/abs/2404.06411) | [code]

- [2024/04/05] **GroundCocoa: A Benchmark for Evaluating Compositional &amp; Conditional Reasoning in Language Models** | [[paper]](https://arxiv.org/abs/2404.04237) | [code]

- [2024/03/29] **DataAgent: Evaluating Large Language Models&#39; Ability to Answer Zero-Shot, Natural Language Queries** | [[paper]](https://arxiv.org/abs/2404.00188) | [code]

- [2024/03/26] **Sharing the Cost of Success: A Game for Evaluating and Learning Collaborative Multi-Agent Instruction Giving and Following Policies** | [[paper]](https://arxiv.org/abs/2403.17497) | [[code]](https://github.com/clp-research/cost-sharing-reference-game)

- [2024/03/20] **SocialBench: Sociality Evaluation of Role-Playing Conversational Agents** | [[paper]](https://arxiv.org/abs/2403.13679) | [code]

- [2024/03/18] **How Far Are We on the Decision-Making of LLMs? Evaluating LLMs&#39; Gaming Ability in Multi-Agent Environments** | [[paper]](https://arxiv.org/abs/2403.11807) | [code]

- [2024/03/18] **Tur[k]ingBench: A Challenge Benchmark for Web Agents** | [[paper]](https://arxiv.org/abs/2403.11905) | [code]

- [2024/03/13] **Evaluating Large Language Models as Generative User Simulators for Conversational Recommendation** | [[paper]](https://arxiv.org/abs/2403.09738) | [code]

- [2024/03/05] **InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated Large Language Model Agents** | [[paper]](https://arxiv.org/abs/2403.02691) | [code]

- [2024/02/27] **Evaluating Very Long-Term Conversational Memory of LLM Agents** | [[paper]](https://arxiv.org/abs/2402.17753) | [code]

- [2024/02/27] **Benchmarking Data Science Agents** | [[paper]](https://arxiv.org/abs/2402.17168) | [code]

- [2024/02/19] **A Critical Evaluation of AI Feedback for Aligning Large Language Models** | [[paper]](https://arxiv.org/abs/2402.12366) | [code]

- [2024/02/18] **Benchmark Self-Evolving: A Multi-Agent Framework for Dynamic LLM Evaluation** | [[paper]](https://arxiv.org/abs/2402.11443) | [[code]](https://github.com/nanshineloong/self-evolving-benchmark)

- [2024/02/18] **MatPlotAgent: Method and Evaluation for LLM-Based Agentic Scientific Data Visualization** | [[paper]](https://arxiv.org/abs/2402.11453) | [code]

- [2024/02/05] **LLM Agents in Interaction: Measuring Personality Consistency and Linguistic Alignment in Interacting Populations of Large Language Models** | [[paper]](https://arxiv.org/abs/2402.02896) | [code]

- [2024/02/02] **TravelPlanner: A Benchmark for Real-World Planning with Language Agents** | [[paper]](https://arxiv.org/abs/2402.01622) | [[code]](https://github.com/OSU-NLP-Group/TravelPlanner)

- [2024/01/02] **CharacterEval: A Chinese Benchmark for Role-Playing Conversational Agent Evaluation** | [[paper]](https://arxiv.org/abs/2401.01275) | [code]

- [2023/12/28] **How Far Are LLMs from Believable AI? A Benchmark for Evaluating the Believability of Human Behavior Simulation** | [[paper]](https://arxiv.org/abs/2312.17115) | [code]

- [2023/12/26] **RoleEval: A Bilingual Role Evaluation Benchmark for Large Language Models** | [[paper]](https://arxiv.org/abs/2312.16132) | [code]

- [2023/11/16] **ML-Bench: Evaluating Large Language Models and Agents for Machine Learning Tasks on Repository-Level Code** | [[paper]](https://arxiv.org/abs/2311.09835) | [code]

- [2023/11/15] **ToolTalk: Evaluating Tool-Usage in a Conversational Setting** | [[paper]](https://arxiv.org/abs/2311.10775) | [code]

- [2023/10/24] **FANToM: A Benchmark for Stress-testing Machine Theory of Mind in Interactions** | [[paper]](https://arxiv.org/abs/2310.15421) | [code]

- [2023/10/09] **Put Your Money Where Your Mouth Is: Evaluating Strategic Planning and Execution of LLM Agents in an Auction Arena** | [[paper]](https://arxiv.org/abs/2310.05746) | [code]

- [2023/10/02] **SmartPlay: A Benchmark for LLMs as Intelligent Agents** | [[paper]](https://arxiv.org/abs/2310.01557) | [code]

- [2023/10/01] **RoleLLM: Benchmarking, Eliciting, and Enhancing Role-Playing Abilities of Large Language Models** | [[paper]](https://arxiv.org/abs/2310.00746) | [code]

- [2023/08/11] **BOLAA: Benchmarking and Orchestrating LLM-augmented Autonomous Agents** | [[paper]](https://arxiv.org/abs/2308.05960) | [code]

- [2023/08/07] **AgentBench: Evaluating LLMs as Agents** | [[paper]](https://arxiv.org/abs/2308.03688) | [code]

- [2023/04/27] **ChatLog: Carefully Evaluating the Evolution of ChatGPT Across Time** | [[paper]](https://arxiv.org/abs/2304.14106) | [code]

#### Environment&Platform
- [2024/12/30] **Training Software Engineering Agents and Verifiers with SWE-Gym** | [[paper]](https://arxiv.org/abs/2412.21139) | [code]

- [2024/11/05] **SAUCE: Synchronous and Asynchronous User-Customizable Environment for Multi-Agent LLM Interaction** | [[paper]](https://arxiv.org/abs/2411.03397) | [code]

- [2024/08/09] **AutoGen Studio: A No-Code Developer Tool for Building and Debugging Multi-Agent Systems** | [[paper]](https://arxiv.org/abs/2408.15247) | [code]

- [2024/08/06] **OpenOmni: A Collaborative Open Source Tool for Building Future-Ready Multimodal Conversational Agents** | [[paper]](https://arxiv.org/abs/2408.03047) | [code]

- [2024/07/23] **OpenHands: An Open Platform for AI Software Developers as Generalist Agents** | [[paper]](https://arxiv.org/abs/2407.16741) | [code]

- [2024/07/14] **AutoGRAMS: Autonomous Graphical Agent Modeling Software** | [[paper]](https://arxiv.org/abs/2407.10049) | [code]

- [2024/07/12] **IDAT: A Multi-Modal Dataset and Toolkit for Building and Evaluating Interactive Task-Solving Agents** | [[paper]](https://arxiv.org/abs/2407.08898) | [code]

- [2024/07/08] **Coding Reliable LLM-based Integrated Task and Knowledge Agents with GenieWorksheets** | [[paper]](https://arxiv.org/abs/2407.05674) | [code]

- [2024/06/06] **AgentGym: Evolving Large Language Model-based Agents across Diverse Environments** | [[paper]](https://arxiv.org/abs/2406.04151) | [[code]](https://github.com/woooodyy/agentgym)

- [2024/05/23] **AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents** | [[paper]](https://arxiv.org/abs/2405.14573) | [code]

- [2024/02/27] **OmniACT: A Dataset and Benchmark for Enabling Multimodal Generalist Autonomous Agents for Desktop and Web** | [[paper]](https://arxiv.org/abs/2402.17553) | [code]

- [2023/03/14] **CB2: Collaborative Natural Language Interaction Research Platform** | [[paper]](https://arxiv.org/abs/2303.08127) | [code]

#### Dataset
- [2025/02/09] **MTPChat: A Multimodal Time-Aware Persona Dataset for Conversational Agents** | [[paper]](https://arxiv.org/abs/2502.05887) | [code]

- [2025/02/09] **HamRaz: A Culture-Based Persian Conversation Dataset for Person-Centered Therapy Using LLM Agents** | [[paper]](https://arxiv.org/abs/2502.05982) | [code]

- [2025/01/23] **Hypothesis Generation for Materials Discovery and Design Using Goal-Driven and Constraint-Guided LLM Agents** | [[paper]](https://arxiv.org/abs/2501.13299) | [code]

- [2025/01/14] **Agent-Centric Projection of Prompting Techniques and Implications for Synthetic Training Data for Large Language Models** | [[paper]](https://arxiv.org/abs/2501.07815) | [code]

- [2024/12/30] **Plancraft: an evaluation dataset for planning with LLM agents** | [[paper]](https://arxiv.org/abs/2412.21033) | [code]

- [2024/12/28] **BaiJia: A Large-Scale Role-Playing Agent Corpus of Chinese Historical Characters** | [[paper]](https://arxiv.org/abs/2412.20024) | [code]

- [2024/12/24] **Explainable Multi-Modal Data Exploration in Natural Language via LLM Agent** | [[paper]](https://arxiv.org/abs/2412.18428) | [code]

- [2024/12/06] **CALICO: Conversational Agent Localization via Synthetic Data Generation** | [[paper]](https://arxiv.org/abs/2412.05388) | [code]

- [2024/11/28] **MAG-V: A Multi-Agent Framework for Synthetic Data Generation and Verification** | [[paper]](https://arxiv.org/abs/2412.04494) | [code]

- [2024/11/21] **Star-Agents: Automatic Data Optimization with LLM Agents for Instruction Tuning** | [[paper]](https://arxiv.org/abs/2411.14497) | [code]

- [2024/10/18] **Synthesizing Post-Training Data for LLMs through Multi-Agent Simulation** | [[paper]](https://arxiv.org/abs/2410.14251) | [code]

- [2024/10/10] **AgentBank: Towards Generalized LLM Agents via Fine-Tuning on 50000+ Interaction Trajectories** | [[paper]](https://arxiv.org/abs/2410.07706) | [code]

- [2024/09/06] **Using Large Language Models to Generate Authentic Multi-agent Knowledge Work Datasets** | [[paper]](https://arxiv.org/abs/2409.04286) | [code]

- [2024/08/22] **MDD-5k: A New Diagnostic Conversation Dataset for Mental Disorders Synthesized via Neuro-Symbolic LLM Agents** | [[paper]](https://arxiv.org/abs/2408.12142) | [code]

- [2024/08/16] **The Fellowship of the LLMs: Multi-Agent Workflows for Synthetic Preference Optimization Dataset Generation** | [[paper]](https://arxiv.org/abs/2408.08688) | [code]

- [2024/07/12] **IDAT: A Multi-Modal Dataset and Toolkit for Building and Evaluating Interactive Task-Solving Agents** | [[paper]](https://arxiv.org/abs/2407.08898) | [code]

- [2024/06/16] **GUI-WORLD: A Dataset for GUI-oriented Multimodal LLM-based Agents** | [[paper]](https://arxiv.org/abs/2406.10819) | [code]

- [2024/03/19] **Agent-FLAN: Designing Data and Methods of Effective Agent Tuning for Large Language Models** | [[paper]](https://arxiv.org/abs/2403.12881) | [code]

- [2024/02/27] **OmniACT: A Dataset and Benchmark for Enabling Multimodal Generalist Autonomous Agents for Desktop and Web** | [[paper]](https://arxiv.org/abs/2402.17553) | [code]

- [2023/07/31] **HAGRID: A Human-LLM Collaborative Dataset for Generative Information-Seeking with Attribution** | [[paper]](https://arxiv.org/abs/2307.16883) | [code]

### Others
- [2025/02/20] **Optimizing Model Selection for Compound AI Systems** | [[paper]](https://arxiv.org/abs/2502.14815) | [code]

- [2024/12/03] **Large Multimodal Agents for Accurate Phishing Detection with Enhanced Token Optimization and Cost Reduction** | [[paper]](https://arxiv.org/abs/2412.02301) | [code]

- [2024/03/18] **EnvGen: Generating and Adapting Environments via LLMs for Training Embodied Agents** | [[paper]](https://arxiv.org/abs/2403.12014) | [code]

---
## :star: Star History

[![Star History Chart](https://api.star-history.com/svg?repos=AGI-Edgerunners/LLM-Agents-Papers&type=Date)](https://star-history.com/#AGI-Edgerunners/LLM-Agents-Papers&Date)
