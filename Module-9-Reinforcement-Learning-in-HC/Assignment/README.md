# Module 9 – Designing a Reinforcement Learning Scenario for Sepsis Treatment

## Purpose
I explored how reinforcement learning (RL), an AI approach where a system improves its decisions by evaluating the consequences of its actions, could be applied to sepsis treatment in the ICU. I designed a scenario where an RL system would use patient vital signs and lab results to recommend IV fluid amounts and blood pressure medication doses.

## Key Takeaways
I learned that RL works through a continuous feedback loop: the agent takes an action, observes the outcome, and adjusts based on whether the result was positive or negative. In my sepsis scenario, the "state" is the patient's clinical picture (pulse, blood pressure, oxygen levels, lab values), and the "actions" are treatment decisions like fluid volumes and medication doses. The system learns over time which strategies lead to better patient outcomes.

## Insights
This was one of the most forward-looking assignments in the course, and honestly one of my favorites. RL has real potential to personalize treatment in ways that static clinical guidelines cannot, because it adapts to each patient's individual response. But the safety concerns are significant. A system that learns by trial and error cannot be deployed without strong clinician oversight, especially in a scenario like sepsis where the margin for error is extremely small.
