# Basics of Prompt Engineering
## Week 1, Class 2

---

## Today's Objectives

- Understand what prompt engineering is and why it matters
- Learn key principles for crafting effective prompts
- Explore advanced prompt techniques for research tasks
- Practice refining prompts for specific research applications
- Apply prompt engineering to enhance your research workflow

---

## What is Prompt Engineering?

- The practice of crafting inputs to get optimal outputs from AI systems
- A skill that improves with deliberate practice and iteration
- Combining art and science to effectively communicate with AI
- The foundation for successful AI integration in research

---

## Why Prompt Engineering Matters for Researchers

- Increases efficiency and productivity
- Improves accuracy and relevance of AI outputs
- Helps you get consistent, reproducible results
- Allows more precise control over AI assistance
- Reduces time spent on revisions and corrections

---

## The Anatomy of an Effective Prompt

### Four Key Components:

1. **Context**: Who you are, what you're doing, relevant background
2. **Instruction**: The specific task or question
3. **Input Data**: Information needed to complete the task
4. **Output Format**: How you want the response structured

---

## Prompt Component: Context

**Purpose**: Establishes necessary background for appropriate response

**Examples**:
- "I am a molecular biologist researching protein folding..."
- "I'm preparing a lecture for undergraduate students on..."
- "I'm writing a grant proposal focused on climate adaptation..."

**Tip**: More specific context leads to more tailored responses

---

## Prompt Component: Instruction

**Purpose**: Clearly states what you want the AI to do

**Examples**:
- "Explain the concept of..."
- "Compare and contrast these two methodologies..."
- "Generate 5 potential research questions about..."

**Tip**: Use precise verbs and avoid ambiguity

---

## Prompt Component: Input Data

**Purpose**: Provides specific information needed for the task

**Examples**:
- "Based on these findings: [data points]..."
- "The abstract of my paper reads as follows: [text]..."
- "The variables in my study include: [list]..."

**Tip**: Ensure all necessary information is included

---

## Prompt Component: Output Format

**Purpose**: Specifies how you want the information presented

**Examples**:
- "Respond in bullet points with 2-3 sentences per point."
- "Structure your response as an academic abstract."
- "Use a comparison table with the following headers..."

**Tip**: Be explicit about structure, length, and style

---

## Key Principles of Effective Prompts

1. **Be Specific and Clear**
2. **Provide Relevant Context**
3. **One Task Per Prompt**
4. **Use Examples (Few-Shot Learning)**
5. **Iterate and Refine**
6. **Request Reasoning, Not Just Answers**
7. **Specify Constraints and Parameters**

---

## Principle 1: Be Specific and Clear

**Instead of:**
"Tell me about research methods."

**Try:**
"Explain the key differences between qualitative and quantitative research methods in psychology, with specific examples of when each approach is most appropriate."

---

## Principle 2: Provide Relevant Context

**Instead of:**
"Help me analyze this data."

**Try:**
"I'm a public health researcher analyzing COVID-19 vaccination rates across different demographics. Help me interpret these trends [data] by identifying potential correlations and suggesting causal factors that might explain the patterns."

---

## Principle 3: One Task Per Prompt

**Instead of:**
"Explain methodology, analyze limitations, and suggest improvements for my study."

**Try:**
"First, let's focus on the methodological approach for my study on [topic]. After we've addressed that fully, I'll ask about limitations and potential improvements separately."

---

## Principle 4: Use Examples (Few-Shot Learning)

**Instead of:**
"Generate research questions about climate change adaptation."

**Try:**
"Generate research questions about climate change adaptation. Here are two examples of the type of questions I'm looking for:
1. 'How do urban heat island effects impact vulnerable populations in coastal cities?'
2. 'What governance structures best facilitate community-led climate adaptation initiatives?'"

---

## Principle 5: Iterate and Refine

**Initial Prompt:**
"Explain the p-value in statistical analysis."

**Refined Prompt:**
"Your explanation was helpful, but could you make it more accessible for undergraduate students with limited statistics background? Please use a real-world example and avoid technical jargon when possible."

---

## Principle 6: Request Reasoning, Not Just Answers

**Instead of:**
"What statistical test should I use for my study?"

**Try:**
"I'm comparing anxiety levels between three treatment groups using a 7-point Likert scale. What statistical test would be most appropriate and why? Please explain your reasoning and any assumptions that should be verified."

---

## Principle 7: Specify Constraints and Parameters

**Instead of:**
"Write a literature review on machine learning in healthcare."

**Try:**
"Write a 500-word summary of the key developments in machine learning applications for diagnostic imaging in healthcare from 2018-2023. Focus on clinical applications rather than technical implementations, and highlight remaining challenges."

---

## Advanced Prompt Engineering Techniques

1. **Chain-of-Thought Prompting**
2. **Self-Reflection Prompting**
3. **Role Prompting**
4. **Persona Specification**
5. **Step-by-Step Instruction**
6. **Template Creation**

---

## Chain-of-Thought Prompting

**Purpose**: Encourages AI to show its reasoning process

**Example**:
"Analyze the potential confounding variables in this study design. Walk through your thinking step-by-step, considering participant selection, measurement approaches, and environmental factors."

---

## Self-Reflection Prompting

**Purpose**: Asks AI to evaluate its own outputs

**Example**:
"Generate three potential theoretical frameworks for my research on teacher burnout. Then, critically evaluate the strengths and limitations of each framework for this specific research question."

---

## Role Prompting

**Purpose**: Frames response from a specific perspective

**Example**:
"As an expert in qualitative research methods, explain how I should approach coding interview data about patient experiences with telehealth."

---

## Persona Specification

**Purpose**: Customizes response to specific audience needs

**Example**:
"I need to explain my research on quantum computing to three different audiences: fellow physicists, undergraduate computer science students, and potential industry partners. Generate appropriate explanations for each audience."

---

## Step-by-Step Instruction

**Purpose**: Breaks complex tasks into manageable steps

**Example**:
"Help me develop a mixed-methods research design:
1. First, suggest appropriate quantitative methods for measuring [variable]
2. Then, recommend complementary qualitative approaches
3. Next, advise on integration strategies for the two data types
4. Finally, outline potential challenges and mitigation strategies"

---

## Template Creation

**Purpose**: Reusable prompt structures for recurring tasks

**Example Template for Literature Analysis**:
```
I'm researching [topic] with a focus on [specific aspect].
Key papers in this area include [1-2 references].
Please help me:
1. Identify the main theoretical perspectives in this literature
2. Summarize methodological approaches commonly used
3. Highlight current debates or contradictions
4. Suggest potential gaps for further research
```

---

## Common Prompt Engineering Mistakes

1. **Being too vague or general**
2. **Overloading with multiple requests**
3. **Failing to provide necessary context**
4. **Not specifying output format**
5. **Expecting factual accuracy without verification**
6. **Using ambiguous terminology**
7. **Not iterating based on responses**

---

## Research-Specific Prompt Applications

- Literature Review Organization
- Research Question Refinement
- Methodology Selection
- Explanation Generation
- Writing Assistance
- Data Interpretation Support
- Teaching Material Development

---

## Example: Literature Review Prompting

**Effective Prompt:**
```
I'm conducting a literature review on the relationship between gut microbiome and depression. 

I've identified these key papers: [citations]

Please help me:
1. Create a concept map of the main themes and relationships
2. Identify methodological patterns across studies
3. Highlight contradictory findings
4. Suggest a logical organization structure for my review
5. Identify potential gaps in the current literature

Respond with a structured outline including brief explanations for each section.
```

---

## Example: Methodology Selection Prompting

**Effective Prompt:**
```
I'm designing a study to investigate how social media use affects academic performance among university students.

My research questions are:
1. [question 1]
2. [question 2]

My constraints include:
- Limited budget ($X)
- 6-month timeframe
- Access to student population at my university

Please compare 3 potential methodological approaches, analyzing strengths, limitations, resource requirements, and alignment with my research questions.
```

---

## Ethical Considerations in Prompt Engineering

- Transparency about AI assistance
- Verification of factual information
- Avoiding misleading or manipulative prompting
- Proper attribution in academic work
- Privacy considerations when sharing research data
- Maintaining human judgment and oversight

---

## Building Your Prompt Library

- Develop templates for recurring research tasks
- Document successful prompts
- Create prompt chains for complex workflows
- Organize by research stage or task type
- Share effective prompts with colleagues
- Continuously refine based on results

---

## Let's Practice!

- Open your preferred AI assistant
- We'll work through targeted exercises
- Focus on applying specific techniques
- Refine prompts based on responses
- Document effective approaches

---

## Next Steps

- Continue refining prompt skills
- Complete Week 1 assessment
- Begin building your prompt library
- Apply these techniques to your research tasks
- Prepare for Week 2: Research Assistance & Literature Review

---

## Questions?