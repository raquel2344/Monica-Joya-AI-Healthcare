# Module 9 – Designing a Reinforcement Learning Scenario for Sepsis Treatment

## Purpose
This assignment explored how reinforcement learning (RL), an AI approach where a system improves its decisions over time by evaluating the consequences of its actions, could be applied to sepsis treatment in the intensive care unit. The paper designed a scenario where an RL system would use patient vital signs and lab results to recommend IV fluid amounts and blood pressure medication doses.

## Key Takeaways
RL works through a continuous feedback loop: the agent takes an action, observes the outcome, and adjusts its strategy based on whether the result was positive or negative. In a sepsis treatment scenario, the "state" is the patient's current clinical picture (pulse, blood pressure, oxygen saturation, lab values), and the "actions" are treatment decisions like fluid volumes and medication doses. Positive rewards are given when patient condition improves, and negative rewards when it worsens. Over time, the system learns which treatment strategies produce the best outcomes.

## Insights
This was one of the most forward-looking assignments in the course. RL has real potential to personalize treatment in ways that static clinical guidelines cannot, because it adapts to each patient's individual response. At the same time, the safety concerns are significant. A system that learns by trial and error cannot be deployed without strong clinician oversight, especially in life-threatening scenarios like sepsis where the margin for error is extremely small.
