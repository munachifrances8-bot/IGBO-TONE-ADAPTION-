# Development and Adaptation of a Tone-Marked Igbo Lexical Dataset

## Dataset Summary
This dataset contains Igbo lexical items annotated for explicit tone information. It was developed to examine how an adaptation workflow affects the representation of tone in a low-resource African language dataset.

- **Language:** Igbo
- **Phenomenon:** Tone
- **Unit:** Word / lexical item
- **Prepared size:** 706 lexical items
- **Adaption export evaluated:** 703 rows

## Research Question
To what extent does Adaption Labs preserve tone information in a tone-marked Igbo lexical dataset?

## Fields
The prepared lexical dataset used:
- `ID`
- `igbo_word`
- `meaning`
- `tone_pattern`
- `source`

The adaptation-ready representation used prompt and completion fields.

## Orthography
The dataset preserves Igbo-specific letters including `ị`, `ọ`, `ụ`, and `ṅ`, as well as explicit acute/grave tone marks where represented in the source data.

## Adaptation
A pilot was conducted before the main adaptation. The adapted output was exported from Adaption Labs and compared with the original lexical forms.

## Evaluation
The exported output contained 703 processed rows. Exact preservation was defined as the original tone-marked lexical form occurring in the adapted response. A second measure checked whether the lexical form remained when tone marks were ignored.

### Results
- Exact original tone-marked form preserved: **21/703 (2.99%)**
- Lexical form preserved but tone not exact: **280/703 (39.83%)**
- Original lexical form not found: **402/703 (57.18%)**

The presence of some tone-marked characters somewhere in a response (585/703; 83.21%) is descriptive only and is not treated as tone preservation.

## Limitations
The prepared dataset contained 706 items but the exported Adaption output contained 703 processed rows. Results are therefore based on the 703 exported rows. Exact string preservation also does not determine whether an alternative form is linguistically acceptable in every Igbo dialect or orthographic convention.

## Intended Use
The dataset is intended for research, educational and computational-language-resource purposes, especially investigation of tone representation in Igbo.
