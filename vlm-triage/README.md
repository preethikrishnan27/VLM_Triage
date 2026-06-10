# Prompt Template

1. Input image type: 2-hour vital-sign trend panel.
2. Symbol mapping:
   - SpO2: triangles
   - Respiratory rate: squares
   - Heart rate: circles
   - Blood pressure: vertical bars
3. Blood pressure interpretation:
   - Upper bar edge = systolic BP
   - Lower bar edge = diastolic BP
   - Bar height = pulse pressure
4. Vital-sign thresholds:
   - SpO2: severe <80%, moderate 80-89%, normal >90%
   - HR: severe <=39 or >=131, moderate 40-49 or 121-130, normal 50-120
   - RR: severe <=5 or >=36, moderate 6-9 or 26-35, normal 10-25
   - SBP: severe <=79 or >=181, moderate 80-99 or 161-180, normal 100-160
5. Missing-data handling.
6. Artifact and data-quality interpretation.
7. Triage classification rules.
8. Required output structure.

The exact prompt used in this repository is available in: src/vlm_vitals_triage/prompts.py

