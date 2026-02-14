## Create Rubrics with GenAI

### Purpose

Develop clear, consistent rubrics using structured prompting, ensuring transparency and alignment with learning outcomes.

**Prompt Template — Instructional**

```
Create a rubric for the following assignment:
[Paste the assignment here or upload it in the prompt]

Use the following criteria:
[Criterion 1, Criterion 2, ..., Criterion N]

Create a 1–5 Likert scale and ensure the total points equal 10.
```

**Additional Prompt Variant — Role-Based + Chain-of-Thought**

```
You are an assessment specialist on [Course Name/Topic]. Create a detailed analytic rubric for the assignment below.
Include 4 criteria, each with 4 performance levels, and point values that total 100 points.
[Paste assignment description here]

Explain your reasoning step-by-step as you generate a rubric for this assignment.
Identify the core skills being assessed, justify each criterion, and then produce the final rubric table.
```

**Rubric Audit Prompt**

```
Audit the rubric below for clarity, comprehensiveness, redundancy, and misalignment with the assignment.
Suggest revisions and then provide an improved version.
[Paste rubric]
```

**Rubric Difficulty Leveling Prompt**

```
Generate three rubric versions for the same assignment:
- Introductory level
- Intermediate level
- Advanced level

Each version should reflect increasing expectations in cognitive demand.
```

**Rubric for Multimodal Deliverables**

```
Create a rubric for an assignment where students submit two deliverables:
1) A written report
2) An AI-generated multimodal asset (e.g., image, podcast script, or diagram)

The rubric should evaluate both independently and their integration.
```

**Rubric for Partial AI Use Transparency**

```
Create a rubric that includes a specific criterion assessing transparency in how students used AI during the assignment (e.g., listing prompts, describing AI contributions).
```
