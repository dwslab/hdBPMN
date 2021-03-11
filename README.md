# hdBPMN - hand-drawn BPMN dataset

This repository contains the hand-drawn BPMN dataset published jointly with our CAiSE 2021 paper `Sketch2BPMN: Automatic Recognition of Hand-drawn BPMN Models` by Bernhard Schäfer, Han van der Aa, Henrik Leopold and Heiner Stuckenschmidt.

Releases:
- [v0.0.1](../../releases/tag/v0.0.1): dataset version used in CAiSE paper

## Project Organization

```
├── data
│   ├── annotations         <- ex01-ex09 .bpmn files.
│   ├── images              <- ex01-ex09 .png/.jpg images.
│   ├── exercises.pdf       <- modeling tasks ex01-ex09 that the hand-drawn models correspond to.
│   ├── writer_split.csv    <- maps each writerID to one of train/val/test split
└── README.md               <- Current file
```

## License

The dataset is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
