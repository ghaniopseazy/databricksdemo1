# Simple Retail Databricks Student Project

Flow:
ADLS Raw -> Bronze -> Silver -> Data Quality -> Gold -> Lakeflow Job -> GitHub -> CI/CD

Notebooks:
01_Raw_to_Bronze
02_Bronze_to_Silver
03_Silver_to_Gold
04_Data_Quality

Replace RAW_PATH in notebook 01 and workspace URL in databricks.yml.

For the classroom demo, create the Lakeflow Job in the UI first. Then show the same Job as YAML and commit the project to GitHub.
