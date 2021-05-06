# hdBPMN - hand-drawn BPMN dataset

This repository contains the hand-drawn BPMN dataset published jointly with our CAiSE 2021 paper `Sketch2BPMN: Automatic Recognition of Hand-drawn BPMN Models` by Bernhard Schäfer, Han van der Aa, Henrik Leopold and Heiner Stuckenschmidt.

Releases:
- [v0.0.1](../../releases/tag/v0.0.1): dataset version used in CAiSE 2021 paper
- [v0.0.2](../../releases/tag/v0.0.2): dataset version used in ICDAR 2021 paper

Check out the [pybpmn](https://github.com/dwslab/pybpmn) repository if you are interested in using the dataset for diagram recognition research.
[pybpmn](https://github.com/dwslab/pybpmn) contains a BPMN XML parser and a script for creating a COCO dataset.

## Project Organization

```
├── data
│   ├── annotations         <- ex00-ex10 .bpmn files.
│   ├── images              <- ex00-ex10 .png/.jpg images.
│   ├── exercises.pdf       <- modeling tasks ex00-ex10 that the hand-drawn models correspond to.
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

## Citing hdBPMN

```BibTeX
@inproceedings{schaeferSketch2BPMN2021,
  title = {Sketch2BPMN: Automatic Recognition of Hand-drawn BPMN Models},
  author = {Sch{\"a}fer, Bernhard and {van der Aa}, Han and Leopold, Henrik and Stuckenschmidt, Heiner},
  booktitle = {Advanced Information Systems Engineering},
  year = {2021},
  publisher = {{Springer International Publishing}},
  language = {en},
  series = {Lecture {{Notes}} in {{Computer Science}}}
}
```

```BibTeX
@inproceedings{schaeferDiagramNet2021,
  title={DiagramNet: Hand-drawn Diagram Recognition using Visual Arrow-relation Detection},
  author = {Sch{\"a}fer, Bernhard and Stuckenschmidt, Heiner},
  booktitle={2021 International Conference on Document Analysis and Recognition (ICDAR)},
  year={2021},
  month = sep,
  language = {en}
}
```
