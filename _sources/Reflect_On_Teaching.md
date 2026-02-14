## Reflect on Teaching Effectiveness Using Feedback and Data

### Purpose

Use AI to synthesize quantitative and qualitative student feedback, combining SPoI data, assignment outcomes, and reflection notes.

#### Use Case 1: Create a Student Perception of Instruction Form (SPoI)

**Prompt Template — Role-Based with Embedded Instructional Structure**

```
You are an instructional designer tasked with creating a course evaluation form titled "Student Perception of Instruction (SPoI)" for the course [Course Name].
Use the set of questions and structure proposed below.

## Instructions:
1. Group the questions into quantitative (Likert scale) and qualitative (open-ended) sections.
2. For each **quantitative question**, provide a 5-point Likert scale with the following response options (unless otherwise specified):
   - Strongly Agree
   - Agree
   - Neutral
   - Disagree
   - Strongly Disagree
   - Not Applicable (optional where relevant)
3. For each **qualitative question**, provide a space for open-ended feedback.
4. Maintain the order, labeling, and clarity of the original items.
5. Return the output in a markdown format suitable for use in an online survey or printed form.

## Open-Ended Questions (Qualitative):
1. How many hours per week did you spend on this course outside of class time?
2. Describe the instructor’s overall presentation and explanation of content.
3. What instructional methods helped you learn the material?
4. Which course materials were most useful? Please explain.
5. Which course materials were least useful? Please explain.
6. Which assignments best supported your learning? Please explain.
7. Which assignments were most troublesome? Please explain.
8. Would you recommend this class to others? Why or why not?

## Likert Scale Questions (Quantitative):
9. The instructor seems concerned with whether I learned the course content.
10. The instructor helped me understand the course content.
11. The instructor generated interest in the course.
12. The learning environment was positive and engaging.
13. Course activities and assignments facilitated my ability to analyze, solve problems, and/or think critically.
14. The following helped with my learning in the course:
   a. How the course was organized
   b. How the course content was delivered
   c. Interactions between the instructor and the students
   d. Availability of the instructor outside of class
   e. Required materials (e.g., books, publications)
15. Overall, this course was effective in improving my knowledge of course content.
16. Overall, this course was a valuable educational experience.
17. (If applicable) For service-learning courses: Were the service-learning activities related to the content of the course? Please explain.

## Output Format:
Please return the form formatted in a DOCX file ready to be imported by a Google or Microsoft Form.
```

**Additional Prompt Variant — Role-Based without Structure**

```
You are an instructional designer tasked with creating a Student Perception of Instruction (SPoI) form for [Course Name].

Follow the structure below:
- Group questions into quantitative (Likert) and qualitative (open-ended)
- Provide a 5-point Likert scale
- Maintain clarity, order, and labeling

[Insert SPoI questions here]

Return full SPoI instrument ready for use in Microsoft/Google Forms.
```

#### Use Case 2: Use GenAI to analyze the students feedback data

**Prompt Template — Instructional Prompt**

```
Given the student feedback provided, summarize:
- Key strengths
- Key weaknesses
- Patterns across comments
- Teaching strategies that worked well
- Areas needing improvement

Generate:
- Charts or graphs
- Key performance indicators (KPIs)
- A short narrative interpreting results
```
