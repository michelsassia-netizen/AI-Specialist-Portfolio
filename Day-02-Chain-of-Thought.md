# Day 2: Chain-of-Thought (CoT) Reasoning
**Project:** Neighborhood Recycling Calculator (Port-au-Prince)

### The Goal
To prevent AI "hallucinations" (lying/guessing) by forcing the model to show its mathematical logic before giving a final answer.

### The Specialist Prompt
"You are a community leader in Port-au-Prince. We have 500 houses. Each house produces 2 bags of trash weekly. 10% is recyclable. 

**Thinking Process (REQUIRED):**
Before giving the final answer, show these steps:
1. Total weekly bags.
2. 10% recyclable portion.
3. Division by bin capacity (20 bags per bin).

Final Output: State the number of bins clearly."

### What I Learned
- **Visible Logic:** If you don't explicitly tell the AI to "Show your work," it might skip steps and make mistakes.
- **Transparency:** Showing the math builds trust with the people using the tool.
