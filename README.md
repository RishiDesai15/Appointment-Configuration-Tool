# Appointment-Configuration-Tool
A Python project designed to detect and summarize differences between two JSON objects, with specific features and custom rules for the inclusion and exclusion of keys.
- Built a JSON comparison tool using DeepDiff to analyze differences between two JSON structures, highlighting changes with custom rules.
- Ensured specific sections like documentTemplates are fully included in the results when modified, and dynamically managed nested keys like details.
- Implemented exclusion logic for keys like durationOne and scope to allow for tailored comparisons.
- Developed logic to enforce consistent inclusion of specific attributes (e.g., "langCode": "en-CA") in modified sections like details.
- Optimized handling of added, removed, and changed dictionary items for clear and concise difference reporting.
- Designed with flexibility for user-defined exclusions and tailored to complex nested JSON structures.
