# Updates to Your AI Workspace and Personalized Assistant

This section summarizes the main updates to your **AI Workspace (Project)** and **Course Personalized Assistant (PA)** to ensure both tools evolve consistently as you progress in this program.

## A. Updates to Your AI Workspace (Project)

Your Workspace is the persistent memory environment that stores course materials, policies, templates, prompts, and all artifacts created during this program. After completing Module 2, apply the updates below.

1. **Upload New Files to the Workspace Knowledge Base:** institutional AI policies, course syllabus, optional additional materials (e.g., accreditation requirements, reading lists, etc.)
2. **Update Workspace Instructions:** modify the Project’s instruction block to reflect new responsibilities.

Add under **How You Work**:

```
- Use uploaded institutional GenAI policies as primary references for all policy‑related outputs.
- Ensure alignment between learning outcomes, activities, pedagogical approaches, and assessments.
- Audit syllabi for internal consistency across dates, expectations, and learning outcomes.
```

Add under **Capabilities**:

```
- Learning outcome alignment checks
- Pedagogical model recommendations
- Syllabus generation, auditing, and refinement
- Policy drafting grounded in institutional documents
- Mapping outcomes → activities → assessments
```

Add under **Behaviors**:

```
- Flag inconsistencies or missing elements and suggest revisions.
- Reflect the institution GenAI policies when generating or updating course materials.
```

> **Note:** If the model you are using restricts the amount of information you can add as instructions in your workspace, then prompt an AI model to summarize the instructions for you.

### B. Updates to Your Course Personalized Assistant (PA)

Your PA becomes a more accurate and responsible tutor by integrating new materials and constraints.

1. **Upload New Files to the PA Knowledge Base:** syllabus, approved GenAI Use Policy, course learning outcomes, weekly schedule, institutional GenAI policy documents.
2. **Update PA Instructions:**

Add under **Core Role / Mission**:

```
- Use only uploaded course materials when answering student questions.
- Reference the GenAI Use Policy whenever students ask about AI usage.
```

Add under **Behaviors**:

```
- Cite relevant sections of the syllabus when responding to student questions.
- If the question touches academic integrity or unclear areas, respond:
  ‘I may need more context or the original file. Please refer to the syllabus or ask your instructor.’
```

Add under **Safety & Boundaries**:

```
- Never provide answers to graded assignments or exams.
- Redirect users to the instructor if they seek prohibited support.
```

3. **Add New Conversation Starters for Students:**

```
Explain the learning outcomes of this course at beginner and advanced levels.
```

```
Summarize the policies on how AI may be used in this course.
```

```
How do the learning outcomes connect to our assignments?
```

### C. Workflow Adjustments Going Forward

**1. All Module 2+ prompts must be issued inside the Workspace**
To ensure:

- Document grounding
- Consistency across versions
- Accurate policy integration
- Alignment across modules

**2. Build incremental outputs instead of isolated chats (each chat should represent one specific set of actions)**
Examples:

- Draft → revise → audit → finalize
- Outcomes → pedagogy → assessments → syllabus integration

**3. Use the PA strictly for student‑facing support** <p>
Workspace = design environment <p>
PA = learning support environment

**4. Update both tools continuously**
As you progress through Modules 3–8, upload:

- Slides
- Assignments
- Activity plans
- Updated schedules
- Assessment rubrics
- Course feedback summaries

### D. Summary Table of Required Updates

| Component                    | Required Update                                                               | Purpose                           |
| ---------------------------- | ----------------------------------------------------------------------------- | --------------------------------- |
| **Workspace Knowledge Base** | Upload policies, syllabus drafts, LOs, learner profiles, pedagogical mappings | Grounded, consistent outputs      |
| **Workspace Instructions**   | Add alignment, auditing, and policy‑compliance behaviors                      | Improve quality and coherence     |
| **PA Knowledge Base**        | Add syllabus, policies, LOs, schedule                                         | Accurate student guidance         |
| **PA Instructions**          | Add boundaries, policy references                                             | Responsible and safe use          |
| **Conversation Starters**    | Add LO, policy, and schedule prompts                                          | Direct student guidance           |
| **Workflow**                 | Use Workspace for all prompts                                                 | Preserve continuity and alignment |
