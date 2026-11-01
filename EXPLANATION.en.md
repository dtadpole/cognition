# Thinking and Cognitive Horizons

[README](README.md) · [中文](EXPLANATION.zh-CN.md)

The framework, its key concepts, intellectual background, and references

Compiled: October 2026

## 1. The statement

> Our thinking sets the limits of what we can achieve.
>
> By “thinking,” we mean our level of awareness, the sophistication of our reasoning, the breadth of our intellectual toolkit, and our ability to select, integrate, and revise frameworks in light of evidence. Together, these shape our cognitive horizon, defining how we perceive, evaluate, and act.
>
> The same applies to agents.

*D.Tadpole*

## 2. Cognitive horizon

A cognitive horizon is the scope of what a person or agent can meaningfully perceive, understand, and evaluate. It shapes which factors enter consideration, which explanations can be developed, and which actions can be assessed.

Four capacities shape this horizon: awareness, reasoning, an intellectual toolkit, and the ability to use and revise frameworks. They describe related but distinct strengths. A broad toolkit offers more approaches; sound reasoning helps assess them; awareness brings relevant information into view; framework use connects those resources to a particular situation.

A horizon has both scope and limits. Someone may understand one domain deeply while missing important factors in another. Knowledge, experience, tools, and interaction with others can extend that reach.

Gadamer's philosophical account of understanding treats horizons as shaped by historical context and open to change through engagement with other perspectives. [^1] In an interview published by Warwick Business School, Felix Hovsepian uses cognitive horizon for the knowledge a person or system can potentially possess. [^2]

## 3. Four capacities

### 3.1 Level of awareness

Awareness concerns what enters attention and consideration. It includes noticing relevant facts, recognizing relationships, and being aware of missing information or uncertainty.

Kegan's account of adult mental complexity offers a related perspective on level of awareness: it examines how ways of organizing and interpreting experience develop. [^3]

Awareness of one's own understanding is one aspect of metacognition, which concerns knowledge about cognition and the monitoring of cognitive activity. It includes checking whether we can explain or apply an idea, recognizing uncertainty, and using questions or self-tests to assess what is known. [^4]

For example, noticing a missed deadline is different from recognizing the dependencies, incentives, and changing requirements that may have contributed to it. Greater awareness brings more of the relevant situation into consideration.

### 3.2 Sophistication of reasoning

Reasoning connects observations to explanations, judgments, and choices. Its sophistication involves identifying assumptions, comparing explanations, tracing relationships, handling tradeoffs, and judging uncertainty.

This requires both depth and discipline. A detailed explanation can still rest on a poor assumption. Sound reasoning checks whether evidence supports a conclusion and whether another explanation fits better.

Toplak, West, and Stanovich examine cognitive sophistication through measures of cognitive ability and thinking dispositions, alongside reasoning tasks involving belief bias, base rates, and framing. [^5]

### 3.3 Breadth of the intellectual toolkit

An intellectual toolkit contains the concepts, models, frameworks, methods, and heuristics available for thinking about a problem. Breadth concerns the variety and coverage of these tools.

Different tools make different features visible:

| Tool or perspective | What it helps examine |
| --- | --- |
| Process model | Workflow and bottlenecks |
| Incentive model | How incentives shape behavior |
| Probabilistic model | Uncertainty and the likelihood of outcomes |

Having several approaches makes it possible to examine a situation in more than one way.

A Santa Fe Institute feature describes Scott Page's cognitive repertoire as including information, knowledge, heuristics, representations, and mental models. [^6] Its usefulness depends on understanding each tool's principles, assumptions, and limits, and recognizing the kinds of problems to which it applies.

### 3.4 Selecting, integrating, and revising frameworks

A framework organizes what matters, how observations are interpreted, and which relationships are considered. It shapes the representation of a problem and the approaches considered for solving it.

Research on physics problem solving found that experts organized problems around underlying principles, while novices relied more on surface features. [^7]

Using frameworks well requires three capacities:

| Capacity | What it involves |
| --- | --- |
| Select | Choose a framework whose principles, assumptions, and scope fit the problem |
| Integrate | Connect useful perspectives while handling their agreements, differences, and tradeoffs |
| Revise | Reconsider the assumptions and relationships that organize the problem when evidence challenges them |

A framework's applicability and a person's flexibility are distinct. A framework may fit a narrow range of situations, while a person can learn when to use it and when another approach is needed.

Dajani and Uddin review cognitive flexibility in terms of adapting behavior to changing demands, including set shifting and task switching. [^8] Suedfeld's overview of integrative complexity distinguishes differentiation, recognizing different dimensions, from integration, recognizing connections among them. [^9] These capacities help a thinker move between perspectives and connect them coherently.

A plan can be adjusted within existing assumptions. Revising a framework involves examining the assumptions and relationships that determine how the problem is understood. Argyris's distinction between single-loop and double-loop learning separates correcting action within governing assumptions from examining and changing those assumptions. [^10]

## 4. Thinking, action, and learning

The four capacities shape our cognitive horizon and, through it, how we perceive, evaluate, and act:

| Function | Central question |
| --- | --- |
| Perceive | What information, relationships, and possibilities can be noticed and understood? |
| Evaluate | How should evidence, alternatives, uncertainty, and tradeoffs be assessed? |
| Act | What choice should be made, and how should it be carried out? |

Perception supplies evidence for evaluation. Evaluation weighs evidence and alternatives against goals and constraints and guides action. Action produces new evidence. What can be carried out also depends on available resources and circumstances.

Learning from feedback involves checking results against expectations and using the evidence to decide what should be retained or changed. [^4] [^10] It can bring overlooked factors into view, improve reasoning, expand the intellectual toolkit, and prompt framework revision. These changes can reshape the cognitive horizon and influence subsequent perception, evaluation, and action.

Kegan examines how adults develop more complex ways of making sense of experience. [^3] Kegan and Lahey explore how underlying assumptions can constrain change. [^11] The Center for Creative Leadership distinguishes two forms of development: [^12]

| Form of development | What develops |
| --- | --- |
| Horizontal development | Additional knowledge, skills, and methods |
| Vertical development | More complex ways of organizing and interpreting experience |

Both can extend a cognitive horizon, although the four capacities need not develop at the same rate.

## 5. Humans and agents

For agents, the four capacities shape what can be perceived, evaluated, and acted on. The table gives functional interpretations and illustrative tools and mechanisms:

| Concept | Role in an agent | Illustrative tools and mechanisms |
| --- | --- | --- |
| Level of awareness | Notice relevant context and relationships, and assess gaps in information or understanding | Search, retrieval, and environment observations [^13] |
| Sophistication of reasoning | Form and test explanations, compare plans, and check assumptions | Planning [^13]; program execution and verification [^14] |
| Breadth of the intellectual toolkit | Draw on a range of concepts, models, methods, and reusable skills | Knowledge sources and tools [^13]; reusable skill libraries [^14] |
| Select frameworks | Choose a problem representation and analytical approach that fit the task | Problem reformulation, method selection, planning templates |
| Integrate frameworks | Connect perspectives while reconciling their assumptions and differences | Evidence synthesis, comparison of alternative analyses, shared working memory |
| Revise frameworks | Reconsider the assumptions and representations guiding the task | Reflection and episodic memory [^15]; execution feedback and tests [^14] |

These mappings overlap. Memory can help an agent recover context, access a learned method, or retain a correction. [^14] [^15] Its contribution to the cognitive horizon depends on how effectively the agent recognizes relevant information, chooses suitable methods, and uses evidence to revise its approach.

ReAct couples reasoning with actions that obtain information. [^13] Voyager maintains a reusable skill library and uses execution feedback to improve programs. [^14] Reflexion stores reflections on feedback in memory for later attempts. [^15]

## 6. An illustrative example

Consider a person or agent investigating a project that repeatedly misses delivery dates. The initial explanation is that people need to work harder. Suppose the records show that all tasks, regardless of risk, require approval from the same review team, and much of the elapsed time is spent waiting for that approval.

| Capacity | What it involves in this example |
| --- | --- |
| Level of awareness | Notice approval rules, task risk, reviewer availability, and gaps in the evidence supporting the initial explanation. |
| Sophistication of reasoning | Compare workload, changing requirements, and approval delays as explanations. Use timestamps to distinguish working time from waiting time. |
| Breadth of the intellectual toolkit | Draw on process mapping, capacity analysis, and risk analysis to examine workflow, reviewer availability, and approval requirements from different perspectives. |
| Select frameworks | Use process and capacity analysis to investigate waiting, and risk analysis to assess where centralized review is needed. |
| Integrate frameworks | Connect review requirements, reviewer capacity, and task risk to explain the bottleneck and assess which approvals may be delegated. |
| Revise frameworks | Question the assumption that every task needs the same centralized approval, and test review requirements based on risk. |

The broader cognitive horizon brings changes to approval rules, delegation, and reviewer capacity into consideration. These become options the person or agent can understand and assess.

Perceiving brings the queue and its consequences into view. Evaluating compares the options against time, cost, and quality requirements. Acting tests a defined change, such as delegating approval for a set of low-risk tasks.

The pilot's waiting times, delivery times, and rework rates provide feedback on both delivery and quality. The results can support or challenge the revised assumptions and help determine where delegation is appropriate. The practical gain is a broader set of credible ways to improve delivery, together with a way to test which ones work.

## Appendix A: Key terms

| Term | Meaning |
| --- | --- |
| Thinking | Awareness, reasoning, available intellectual tools, and the capacity to use and revise frameworks |
| Level of awareness | The extent to which relevant factors, relationships, gaps, and possibilities enter consideration |
| Sophistication of reasoning | Depth, refinement, and discipline in forming explanations and judgments |
| Intellectual toolkit | Concepts, models, frameworks, methods, and heuristics available for use |
| Framework | Assumptions and relationships that organize understanding or action |
| Cognitive flexibility | Adjusting cognitive sets or strategies to changing circumstances [^8] |
| Integrative complexity | Recognizing different dimensions and connections among them [^9] |
| Cognitive horizon | The scope of what can be meaningfully perceived, understood, and evaluated |

## Appendix B: References

[^1]: Malpas, J. (2025). [Hans-Georg Gadamer](https://plato.stanford.edu/archives/fall2025/entries/gadamer/). In E. N. Zalta & U. Nodelman (Eds.), *The Stanford Encyclopedia of Philosophy* (Fall 2025 ed.), section 3.2. Scholarly overview of horizons in Gadamer's hermeneutics. Entry first published 2003; substantively revised 2022.

[^2]: Warwick Business School. (2018). [How will the 4th Industrial Revolution affect business?](https://www.wbs.ac.uk/news/how-will-the-4th-industrial-revolution-affect-business/). Institutional news interview reporting Hovsepian's use of cognitive horizon for human and AI knowledge.

[^3]: Kegan, R. (1994). [*In over our heads: The mental demands of modern life*](https://www.jstor.org/stable/j.ctv1pncpfb). Harvard University Press. Adult-development theory, mental complexity, and ways of knowing.

[^4]: Flavell, J. H. (1979). [Metacognition and cognitive monitoring: A new area of cognitive-developmental inquiry](https://doi.org/10.1037/0003-066X.34.10.906). *American Psychologist, 34*(10), 906-911. Conceptual model of metacognitive knowledge, experiences, goals, and strategies. [Full text (PDF)](https://www.neurodyspaca.org/IMG/pdf/flavell_-_1979_-_metacognition_and_cognitive_monitoring.pdf).

[^5]: Toplak, M. E., West, R. F., & Stanovich, K. E. (2014). [Rational thinking and cognitive sophistication: Development, cognitive abilities, and thinking dispositions](https://doi.org/10.1037/a0034910). *Developmental Psychology, 50*(4), 1037-1048. Empirical study of reasoning tasks and measures of cognitive sophistication. [PubMed record](https://pubmed.ncbi.nlm.nih.gov/24188038/).

[^6]: Santa Fe Institute. (2017). [Page's ‘The Diversity Bonus’ makes the business case for diverse teams](https://santafe.edu/news-center/news/pages-diversity-bonus-makes-business-case-diverse-teams). Institutional news feature describing Page's account of cognitive repertoires.

[^7]: Chi, M. T. H., Feltovich, P. J., & Glaser, R. (1981). [Categorization and representation of physics problems by experts and novices](https://doi.org/10.1207/s15516709cog0502_2). *Cognitive Science, 5*(2), 121-152. Four experiments on problem representation in physics.

[^8]: Dajani, D. R., & Uddin, L. Q. (2015). [Demystifying cognitive flexibility: Implications for clinical and developmental neuroscience](https://doi.org/10.1016/j.tins.2015.07.003). *Trends in Neurosciences, 38*(9), 571-578. Review of cognitive flexibility, set shifting, and task switching. [Full text](https://pmc.ncbi.nlm.nih.gov/articles/PMC5414037/).

[^9]: Suedfeld, P. (updated 2004). [Suedfeld's integrative complexity research](https://www2.psych.ubc.ca/~psuedfeld/CXY.html). University of British Columbia. Research overview defining differentiation and integration; the year records the page's stated update.

[^10]: Argyris, C. (1976). [Single-loop and double-loop models in research on decision making](https://doi.org/10.2307/2391848). *Administrative Science Quarterly, 21*(3), 363-375. Theoretical analysis of learning, feedback, and governing assumptions in organizational decision making.

[^11]: Kegan, R., & Lahey, L. L. (2009). [*Immunity to change: How to overcome it and unlock the potential in yourself and your organization*](https://store.hbr.org/product/immunity-to-change-how-to-overcome-it-and-unlock-the-potential-in-yourself-and-your-organization/1736). Harvard Business Press. Applied account of development and assumptions that sustain resistance to change.

[^12]: Center for Creative Leadership. (2025). [Vertical vs. horizontal development: Why your leaders need both to succeed](https://www.ccl.org/articles/leading-effectively-articles/developing-talent-youre-probably-missing-vertical-development/). Institutional explanation of horizontal and vertical leadership development.

[^13]: Yao, S., Zhao, J., Yu, D., Du, N., Shafran, I., Narasimhan, K., & Cao, Y. (2022; revised 2023). [ReAct: Synergizing reasoning and acting in language models](https://arxiv.org/abs/2210.03629v3). *arXiv preprint*, 2210.03629v3. Interleaved reasoning, action, and information gathering.

[^14]: Wang, G., Xie, Y., Jiang, Y., Mandlekar, A., Xiao, C., Zhu, Y., Fan, L., & Anandkumar, A. (2023). [Voyager: An open-ended embodied agent with large language models](https://arxiv.org/abs/2305.16291v2). *arXiv preprint*, 2305.16291v2. Reusable skills, execution feedback, and program improvement in Minecraft.

[^15]: Shinn, N., Cassano, F., Berman, E., Gopinath, A., Narasimhan, K., & Yao, S. (2023). [Reflexion: Language agents with verbal reinforcement learning](https://arxiv.org/abs/2303.11366v4). *arXiv preprint*, 2303.11366v4. Reflection on task feedback and episodic memory for subsequent attempts.
