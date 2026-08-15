# Adaption Methodology

## 1. Dataset Preparation
A tone-marked Igbo lexical dataset was prepared at word level. Each lexical item was associated with an English meaning, tone information, and source information. Igbo-specific orthographic characters were retained.

## 2. Adaptation-ready Format
The lexical data were represented as instruction-style prompt–completion pairs. The prompt requested the Igbo equivalent while requiring preservation of the original tone marking and Igbo orthography. The completion supplied the corresponding lexical item.

## 3. Pilot
A four-row pilot was run to verify the column mapping, prompt/completion structure and adaptation workflow before the larger run.

## 4. Main Adaptation
The prepared prompt–completion dataset was processed in Adaption Labs. The adapted output was exported for analysis. The raw dataset was preserved separately.

## 5. Evaluation
The adapted responses were compared against the original completions using two principal preservation measures:
1. Exact occurrence of the original tone-marked lexical form.
2. Presence of the underlying lexical form after ignoring tone marks.

A descriptive measure recorded whether any acute/grave tone-marked character appeared somewhere in the response. This was not treated as a preservation score.

## 6. Results
The exported output contained 703 rows:
- Exact tone-marked preservation: 21 (2.99%)
- Lexical preservation without exact tone: 280 (39.83%)
- Lexical form not found: 402 (57.18%)

## 7. Reproducibility
The raw dataset, adapted export, row-level comparison, summary statistics, figures and screenshots of the adaptation process should be retained together.
