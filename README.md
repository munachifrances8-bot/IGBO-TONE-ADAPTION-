# IGBO-TONE-ADAPTION-
# Development and Adaptation of a Tone-Marked Igbo Lexical Dataset Adaption Labs

## Project
- Language: Igbo
- Phenomenon: Tone
- Unit of analysis: Word
- Prepared dataset: 706 lexical items
- Evaluated Adaption export: 703 rows

## Research Question
**To what extent does Adaption Labs preserve tone information in a tone-marked Igbo lexical dataset?**

## Workflow
1. Dataset design and lexical data preparation
2. Prompt–completion preparation
3. Pilot adaptation
4. Main adaptation in Adaption Labs
5. Export of adapted output
6. Raw vs adapted comparison
7. Tone-preservation evaluation
8. Results, figures and interpretation

## Main Evaluation Results
| Outcome | Frequency | Percentage |
|---|---:|---:|
| Exact original tone-marked form preserved | 21 | 2.99% |
| Lexical form preserved, but tone marking not exact | 280 | 39.83% |
| Original lexical form not found | 402 | 57.18% |
| Some tone-marked character somewhere in response | 585 | 83.21% |
| Total evaluated | 703 | 100% |

The 83.21% figure is **not** a tone-preservation score. It only indicates that some tone-marked characters occurred somewhere in the generated response.

## Important Dataset Note
The prepared dataset contained 706 lexical items, while the exported Adaption result contained 703 processed rows. The evaluation therefore reports results for the 703 rows available in the export and does not invent results for the three missing rows.

## Repository Structure
```text
data/
  raw/
  adapted/
analysis/
  Igbo_Adaption_Raw_vs_Adapted_Analysis.csv
  Igbo_Adaption_Evaluation_Summary.csv
figures/
  igbo_adaption_outcomes.png
  igbo_tone_preservation.png
docs/
  Igbo_Adaption_Final_Report.docx
  dataset_card.md
  methodology.md
social/
  linkedin_post.txt
```

