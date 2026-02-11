Business Overview data files

These are the Excel files the dashboard expects in a /data folder (or for upload):
- population.xlsx
- avg_years_service.xlsx
- avg_time_in_grade.xlsx
- likely_to_retire.xlsx

Format requirements:
- Sheet name: Data
- Header row (row 3): Year | Value
- Year values can be YYYY or YYYY-MM. This set uses YYYY-MM monthly points.
- likely_to_retire.xlsx should be COUNTS (not %). The site converts to a % rate using population.

Templates are in /templates.
