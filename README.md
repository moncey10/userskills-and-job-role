# userskills-and-job-role
# Skills Intelligence Project: Sprints 1-3
## Sprint 1: Data Validation & Schema Definition
Objective: Enforce strict data types and identify unique records.

Key Tasks:

- Defined proficiency_level as an integer (1-6).

- Validated skill_code as a unique string identifier.

- Checked for primary key duplicates in the (jobrole, skill_code) combination.

## Sprint 2: ETL Pipeline & Standardization
Objective: Transform raw data into a model-ready format.

Key Tasks:

- Stripped whitespace from skill names for consistency.

- Normalized created_at and updated_at into ISO-8601 datetime objects.

- Implemented error handling to log corrupt rows (missing skill_code) to etl_errors.log.

## Sprint 3: Exploratory Data Analysis (EDA)
Objective: Identify statistical patterns in sectors and proficiency levels.

Key Tasks:

- Generated a heatmap to visualize skill frequencies across sectors.

- Analyzed proficiency distribution to identify high-expertise job roles.

- Calculated Jaccard similarity to cluster tracks with identical skill sets.
