MCU Superhero Fatigue: Python Analysis

Python notebooks for my case study on MCU box office performance, which tests whether audiences are tired of superheroes or just more selective.

Notebooks
mcu_analysis_SETUP_&_PROCESS.ipynb cleans the raw data (62 MCU films and Disney+ series, 2008–2026) and adds a recovery_ratio column (worldwide box office ÷ budget).
mcu_analysis_ANALYZE_FINAL.ipynb compares recovery ratios by saga, by phase, for event vs. standard films, and for films that depend on a Disney+ series.

Run them in order in Google Colab using pandas.

Result

Median recovery fell from 4.35× in the Infinity Saga to 2.88× in the Multiverse Saga. Films that depended on a Disney+ series did worst.
