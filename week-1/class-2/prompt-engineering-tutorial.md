# Prompt Engineering Tutorial
## Week 1, Class 2

This tutorial provides a structured guide to mastering prompt engineering for research tasks.

## What is Prompt Engineering?

Prompt engineering is the practice of crafting effective inputs to AI systems to obtain optimal outputs for your specific needs. It involves understanding how to structure your requests, provide appropriate context, and guide the AI toward the most helpful responses for your research tasks.

## Why Researchers Need Prompt Engineering Skills

- **Obtain more accurate and relevant information**
- **Save time by getting better responses on the first attempt**
- **Maintain greater control over the style, format, and content of AI outputs**
- **Achieve more consistent and reproducible results**
- **Effectively leverage AI for complex research tasks**

## The Four Components of Effective Prompts

### 1. Context

**What it is**: Background information that helps the AI understand your perspective, knowledge level, goal, and situation.

**Examples for researchers**:
- "I am a doctoral student in cognitive neuroscience studying attention mechanisms..."
- "I'm preparing teaching materials for an undergraduate course on climate science..."
- "I'm working on a grant proposal focused on emerging infectious diseases..."

**Best practices**:
- Specify your field and specialization
- Indicate your expertise level (when relevant)
- Mention the purpose of your request (teaching, research, writing, etc.)
- Reference any relevant theoretical frameworks or approaches

### 2. Instruction

**What it is**: The specific task or question you want the AI to address.

**Examples for researchers**:
- "Compare and contrast these three methodological approaches..."
- "Analyze the potential limitations of this study design..."
- "Generate potential explanations for these unexpected findings..."

**Best practices**:
- Use clear, direct language
- Start with strong action verbs (analyze, compare, explain, generate)
- Focus on one main task per prompt
- Be specific about what you want

### 3. Input Data

**What it is**: The specific information the AI needs to complete your task.

**Examples for researchers**:
- "Here is the abstract of my paper: [text]..."
- "My research variables include: [list]..."
- "The results from our pilot study showed: [data]..."

**Best practices**:
- Provide all necessary information in a structured format
- Highlight the most important elements
- Format data clearly (lists, bullet points, tables, etc.)
- Consider what background information the AI might need

### 4. Output Format

**What it is**: Instructions for how you want the response structured or presented.

**Examples for researchers**:
- "Structure your response as a literature review with distinct sections for theoretical background, empirical findings, and gaps."
- "Present your analysis in a table comparing methodological approaches across the following dimensions: [list]."
- "Format your response as bullet points with 2-3 sentences per point, using academic language."

**Best practices**:
- Specify desired length (word count, number of bullet points, etc.)
- Request specific formats (bullet lists, tables, sections, etc.)
- Indicate level of detail or complexity
- Mention tone and style preferences (e.g., academic, accessible)

## Step-by-Step Process for Creating Effective Research Prompts

### Step 1: Identify Your Specific Need

Before crafting your prompt, clearly identify what you're trying to accomplish:
- What specific research task are you working on?
- What kind of assistance would be most valuable?
- What would an ideal response look like?

### Step 2: Draft Your Initial Prompt

Incorporate the four key components:
1. Write 1-2 sentences of context about your role and purpose
2. Clearly state your primary instruction
3. Include any necessary input data
4. Specify your desired output format

### Step 3: Review and Enhance Your Prompt

Check your draft against these criteria:
- Is the context sufficient for the AI to understand your situation?
- Is the instruction clear and focused?
- Have you provided all necessary information?
- Have you specified how you want the response formatted?

Enhance your prompt by adding:
- Specific constraints (length, style, perspective)
- Examples of what you're looking for (if applicable)
- Clear criteria for evaluating options (if requesting recommendations)

### Step 4: Test and Iterate

1. Submit your prompt to the AI
2. Evaluate the response:
   - Did it address your needs?
   - Is it at the appropriate level of detail?
   - Does it follow your format requirements?
3. Identify areas for improvement
4. Refine your prompt and try again

## Advanced Prompt Engineering Techniques

### Chain-of-Thought Prompting

**Technique**: Ask the AI to walk through its reasoning process step by step.

**Example**: "Analyze these research findings on climate adaptation strategies. Walk through your analysis step by step, considering methodological strengths, limitations, and implications for policy."

**Best for**:
- Complex analytical tasks
- Evaluating research designs
- Understanding causal relationships
- Identifying logical flaws

### Role Prompting

**Technique**: Ask the AI to adopt a specific expert perspective.

**Example**: "As an expert in qualitative research methods, explain how I should approach analyzing interview data from trauma survivors. Consider ethical implications, coding strategies, and interpretation frameworks."

**Best for**:
- Getting specialized disciplinary perspectives
- Accessing expert guidance in areas outside your expertise
- Considering alternative viewpoints on your research

### Few-Shot Learning

**Technique**: Provide examples of the kind of response you want.

**Example**: "Generate research questions on sustainable urban transportation. Here are two examples of the type of questions I'm looking for:
1. 'How do micro-mobility options affect public transit usage in high-density urban areas?'
2. 'What policy incentives most effectively encourage shifts from personal vehicles to sustainable transportation alternatives?'"

**Best for**:
- Teaching the AI your preferred style or format
- Getting consistent types of outputs
- Clarifying complex or nuanced requests

### Self-Critique Prompting

**Technique**: Ask the AI to critique its own response or consider limitations.

**Example**: "Suggest three theoretical frameworks for my research on digital literacy among older adults. Then, critically evaluate the strengths and limitations of each framework for this specific population and research focus."

**Best for**:
- Balancing perspectives
- Identifying potential weaknesses
- Getting more nuanced analysis
- Avoiding one-sided responses

### Prompt Chaining

**Technique**: Breaking complex tasks into a sequence of simpler prompts, where each builds on the previous response.

**Example Sequence**:
1. First prompt: "Help me identify the key variables I should measure in my study on workplace well-being."
2. Second prompt: "Based on these variables [from first response], suggest appropriate measurement instruments for each."
3. Third prompt: "Given these measurement approaches [from second response], outline a data collection protocol that minimizes participant burden."

**Best for**:
- Complex research tasks with multiple components
- Developing detailed research plans
- Literature reviews with multiple stages
- Analysis requiring progressive refinement

## Research-Specific Prompt Templates

### Literature Review Template

```
I am a [your role] researching [specific topic] with a focus on [particular aspect].

I'm currently conducting a literature review and have identified the following key papers:
- [Paper 1: brief description]
- [Paper 2: brief description]
- [Paper 3: brief description]

Please help me:
1. Identify the main themes and connections across these works
2. Highlight methodological approaches used in this area
3. Identify apparent gaps or contradictions in the literature
4. Suggest a logical structure for organizing my literature review

Present your analysis in a structured format with clear headings for each section. For the organizational structure, please provide a visual outline I could follow.
```

### Research Question Development Template

```
I am a [your role] interested in researching [broad topic area].

My specific focus is on [particular aspect or problem].

Background context:
- [Current state of knowledge in this area]
- [Gaps or problems I've identified]
- [Theoretical framework I'm using]

Help me develop 3-5 potential research questions that:
1. Address significant gaps in the current literature
2. Are specific and feasible to investigate
3. Would contribute meaningfully to [field/discipline]
4. Could be addressed using [preferred methodological approach]

For each question, please provide:
- The research question itself (precisely worded)
- Brief rationale for its importance
- Potential methodological approach
- Anticipated challenges
```

### Methodology Selection Template

```
I am a [your role] designing a study to investigate [research question].

My study constraints include:
- [Time constraints]
- [Resource limitations]
- [Population access considerations]
- [Ethical considerations]

I'm considering the following methodological approaches:
- [Approach 1]
- [Approach 2]
- [Approach 3]

Please compare these approaches across the following dimensions:
1. Alignment with my research question
2. Feasibility given my constraints
3. Strengths and limitations
4. Required resources and expertise
5. Potential validity concerns

Present your analysis in a comparative table followed by a recommendation with detailed rationale.
```

### Data Analysis Planning Template

```
I am a [your role] planning the analysis phase for my study on [topic].

My research question is: [specific research question]

I have collected the following data:
- [Data type 1: description and format]
- [Data type 2: description and format]
- [Data type 3: description and format]

My research design is [brief description of design].

Please help me develop a comprehensive analysis plan that includes:
1. Appropriate statistical/analytical approaches for each research question
2. Required data preparation steps
3. Strategy for handling missing data
4. Approach to testing assumptions
5. Potential supplementary analyses

Please structure your response as a step-by-step analysis protocol I could follow, with clear rationale for each recommended approach.
```

## Common Prompt Engineering Mistakes to Avoid

### 1. Being Too Vague

**Problem**: The AI doesn't have enough context to provide a relevant response.

**Example**: "What methodology should I use for my study?"

**Solution**: Specify your research question, variables, constraints, and objectives.

### 2. Overloading with Multiple Requests

**Problem**: The AI may miss parts of your request or provide superficial responses to each part.

**Example**: "Explain mixed methods, help me design my study, critique my research questions, and suggest statistical approaches."

**Solution**: Focus on one main task per prompt, or use prompt chaining for complex requests.

### 3. Not Providing Necessary Context

**Problem**: The AI provides generic information that isn't tailored to your specific needs.

**Example**: "Explain grounded theory approach" (without specifying your field or purpose).

**Solution**: Always include your role, field, purpose, and relevant background information.

### 4. Expecting Perfect Factual Accuracy

**Problem**: Relying on AI for accurate citations or cutting-edge research without verification.

**Example**: "Provide me with the latest findings on CRISPR gene therapy."

**Solution**: Use AI for structure and ideas, but verify factual information independently.

### 5. Neglecting to Specify Format

**Problem**: The AI provides information in a format that doesn't meet your needs.

**Example**: "Tell me about measurement approaches" (without specifying how detailed or structured the response should be).

**Solution**: Always specify your preferred output format, length, and level of detail.

## Practice Exercises

1. **Transform a basic research question** into a detailed prompt using the four-component structure.

2. **Create a template** for a recurring research task you perform.

3. **Apply an advanced technique** like chain-of-thought or role prompting to a complex research problem.

4. **Identify weaknesses** in a prompt you've previously used and improve it.

5. **Develop a prompt chain** for a multi-step research process.

## Conclusion

Prompt engineering is a skill that improves with practice. By thoughtfully structuring your prompts with clear context, instructions, input data, and output format specifications, you can significantly enhance the quality and usefulness of AI responses for your research tasks. Remember to iterate and refine your prompts based on the responses you receive, and to build a personal library of effective prompts for recurring research tasks.