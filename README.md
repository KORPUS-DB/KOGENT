# KOGENT

KOGENT (KOrean GENder-sensitivity Tagged dataset) is a benchmark dataset for evaluating gender sensitivity in Korean political discourse using large language models.

## Features

* **1,222 transcripts** from the Korean National Assembly (1948-2024) spanning 76 years of legislative history
* **6,024 human-annotated utterances** labeled for gender sensitivity levels (high or low)
* Coverage of plenary sessions, standing committees, special committees, and hearings
* **Inter-annotator agreement**: Cohen's κ = 0.96, Krippendorff's α = 0.95
* Target groups: women, men, sexual minorities, all genders
* Context-sensitive annotations accounting for historical and cultural nuances

## Benchmark Performance

When evaluated on KOGENT, GPT-4 models achieved:
- **GPT-4.1**: F1-scores of 87.5% (zero-shot) and 91.2% (18-shot)
- **GPT-4o**: F1-scores of 90.4% (zero-shot) and 91.1% (18-shot)
