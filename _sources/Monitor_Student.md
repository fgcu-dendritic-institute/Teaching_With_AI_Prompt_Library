## Monitor Student Success

### Purpose

Use engagement data or AI-generated insights to detect patterns that indicate a need for support.

**Prompt Template - Design a Student Success Table**

```
I am the instructional designer of the course [Course Name] and want to design a table to collect student information in the course.
The goal is to use the data to calculate a "Student Success Score".

1. Propose a matrix with at least 5 student variables (e.g., attendance, assignment completion, grades, engagement, self-assessments).
2. For each variable, define:
   - Data type (numeric, categorical)
   - Measurement method
   - Weight or influence on success

3. Propose a formula to compute a success score from these variables (e.g., weighted average or custom equation).
4. Explain how this score can be used to monitor or support students throughout the course.
5. Save this matrix as a table in XLSX, CSV, or Google Spreadsheet format.
```

> **Note:** Not all models will be able to generate the output in the specific format you prompted. In such cases, choose another format or try a different model.

**Additional Prompt Variant - Using a Pre-Specified Score Matrix**
Provide the following details to create a matrix or table for collecting student information and calculating a success score.

```
Create a table for calculating anonymized student success indicators.
Do NOT use or request any personally identifiable information (PII).
Use anonymous labels such as **Student 01, Student 02**, etc.

### Learning Indicators (All Non-PII)
Use only the following non-identifying metrics:

- Anonymous Student ID
- Attendance Rate (%)
- Assignment Completion Rate (%)
- Quiz Average Score (%)
- Discussion Participation (# posts)
- LMS Engagement (Hours/Week)

## Table Structure

| Student ID | Attendance (%) | Assignment Completion (%) | Quiz Avg (%) | Discussion Posts (#) | LMS Engagement (Hours/Week) | Success Score |
|------------|----------------|----------------------------|--------------|------------------------|------------------------------|---------------|
| Student 01 | [Value]        | [Value]                    | [Value]      | [Value]                | [Value]                      | [Calculated]  |
| Student 02 | [Value]        | [Value]                    | [Value]      | [Value]                | [Value]                      | [Calculated]  |

Ensure the table includes a column for the Success Score, which will be calculated.

## Success Score Equation
Success Score =
(0.2 × Attendance Rate) +
(0.3 × Assignment Completion Rate) +
(0.3 × Quiz Average Score) +
(0.1 × Normalized Discussion Participation) +
(0.1 × Normalized LMS Engagement)

### Weight Explanation
- Attendance Rate: **20%**
- Assignment Completion: **30%**
- Quiz Average Score: **30%**
- Discussion Participation: **10%**
- LMS Engagement: **10%**

## Normalization
- Normalized Discussion Participation = (Posts / Max Expected Posts) × 100
- Normalized LMS Engagement = (Hours / Max Expected Hours) × 100

## Score Interpretation
- **80–100:** Strong performance
- **60–79:** Moderate performance
- **Below 60:** Needs intervention

Additional Notes:
- Ensure all percentages are on a 0-100 scale for consistency.
- The Success Score should range from 0 to 100, with higher scores indicating greater likelihood of success.
- Include a brief explanation of how to interpret the score (e.g., “Scores above 80 indicate strong performance, 60-79 suggest moderate success with room for improvement, below 60 indicate a need for intervention”).

## Output Requirements
1. Generate the anonymized table
2. Export as XLSX or CSV
3. Create a normalized bar chart per learner (green/yellow/red for interpretation)

## Privacy Constraints (Strict)
- Never include PII
- Never attempt to infer identity
- Ensure FERPA compliance at all times
```
