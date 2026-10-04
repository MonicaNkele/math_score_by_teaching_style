# math_score_by_teaching_style

> [!NOTE]
> <i>This project is a simulation based on a fictional educational dataset sourced from [Kaggle.com]</i>

## Objective
Analyze recent standardized math test scores to officially recommend the most effective teaching method (Traditional vs. Standard).

<details>
  <summary><b>Click here to read the full context & scenario</b></summary>
  <br>
  As the newly appointed principal of a diverse middle school, I am facing a structural conflict within the math department. Currently, students are assigned to classes randomly, but the three math teachers utilize completely different pedagogical approaches:
  <ul>
    <li><b>Mrs. Wesson</b> employs a traditional, highly structured, vertical teaching method. She advocates for separating students by skill level and matching students to teachers based on ethnicity.</li> 
    <li><b>Mrs. Ruger & Mrs. Smith</b> employ a standard, constructivist approach (problem-solving and exploration). They reject the discriminatory ethnic grouping idea and wish to standardize the constructivist method across the department.</li>
  </ul>
</details>

## Hypotheses

1. **Teaching Method Impact:** H0: The teaching method has no significant impact on scores. H1: There is a significant difference (p < .05) in scores between the two methods
2. **Teacher Impact:** H0: The individual teacher has no significant impact on scores. H1: There is a significant difference in student scores depending on the teacher.
3. **Ethnic Matching Impact:** H0: Matching the student's ethnicity with the teacher's ethnicity has no impact on scores. H1: Students perform significantly better when taught by a teacher of the same ethnicity.

## Dataset Description
The dataset contains 216 observations and 7 variables: `Student`, `Teacher`, `Gender`, `Ethnic`, `Freeredu` (Socioeconomic indicator), `Score`, `Teaching_style`.

## How to Reproduce this Analysis
1. Clone this repository.
2. Open the `math_scores_teaching.Rproj` file in RStudio
3. Run the scripts in the `scripts/` folder sequentially
