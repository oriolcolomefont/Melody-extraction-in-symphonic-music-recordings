# Melody Extraction in Symphonic Music Recordings

This repository contains research and implementation of algorithmic predominant melody extraction in symphonic music recordings, using state-of-the-art MIR techniques.

## Project Overview

This study evaluates the performance of current state-of-the-art melodic tracking algorithms while discussing results from both scientific and musicological perspectives. The work highlights the complexity of analyzing and evaluating computational musicological tools, particularly in classical music where human performance adds subtle nuances and variations.

### Key Features

- Implementation of the MELODIA algorithm for predominant melody extraction
- Evaluation using the ORCHSET dataset (64 orchestral music excerpts)
- Integration with essential MIR tools:
  - ESSENTIA for audio analysis
  - MIRDATA for dataset handling
  - MIR_EVAL for standardized evaluation metrics

## Technical Implementation

The project uses:
- Python with Jupyter Notebooks
- ESSENTIA library for audio processing
- MELODIA algorithm for pitch detection
- Comprehensive evaluation metrics including:
  - Voicing Recall
  - Voicing False Alarm
  - Raw Pitch Accuracy
  - Raw Chroma Accuracy
  - Overall Accuracy

## Results

The implementation achieves:
- Mean Raw Pitch Accuracy: 0.199
- Mean Raw Chroma Accuracy: 0.383
- Overall Accuracy: 0.226

For detailed results and analysis, please refer to the Jupyter notebook.

## Repository Structure

- `Algorithmic_predominant_melody_extraction_in_symphonic_music_recordings_MIR_Course_Project_Oriol_Colomé_2022.ipynb`: Main implementation notebook
- `LaTeX/`: Contains the research paper and documentation
  - Comprehensive analysis of the methodology
  - Detailed results discussion
  - Technical implementation details

## Getting Started

1. Clone the repository
2. Install dependencies (requirements.txt coming soon)
3. Open the Jupyter notebook to explore the implementation

## Citation

If you use this work in your research, please cite:

```bibtex
@misc{colome2022melody,
  author = {Colomé Font, Oriol},
  title = {Algorithmic predominant melody extraction in symphonic music recordings},
  year = {2022},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/oriolcolomefont/Melody-extraction-in-symphonic-music-recordings}}
}
```

## License

This project is licensed under the MIT License - see the LICENSE file for details. 