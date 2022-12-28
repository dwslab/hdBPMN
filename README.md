## hdBPMN - hand-drawn BPMN dataset

This repository contains the hand-drawn BPMN dataset published jointly with our CAiSE 2021 paper `Sketch2BPMN: Automatic Recognition of Hand-drawn BPMN Models` by Bernhard Schäfer, Han van der Aa, Henrik Leopold and Heiner Stuckenschmidt.

![hdBPMN Example Image](https://github.com/dwslab/hdBPMN/raw/main/data/images/ex03/ex03_writer0088.jpg)

### Releases

- [v0.0.1](../../releases/tag/v0.0.1): dataset version used in [Sketch2BPMN paper](https://link.springer.com/chapter/10.1007/978-3-030-79382-1_21)
- [v0.0.2](../../releases/tag/v0.0.2): dataset version used in [DiagramNet paper](https://link.springer.com/chapter/10.1007/978-3-030-86549-8_39)
- [v1.0.0](../../releases/tag/v1.0.0): dataset version used in [Sketch2Process paper](https://ieeexplore.ieee.org/document/9980425)


### Related Repositories

- [pybpmn-parser](https://github.com/dwslab/pybpmn-parser): contains a BPMN XML parser and a script for creating a dataset in the COCO format (COCO is a common format for computer vision datasets).
- [handwritten-diagram-datasets](https://github.com/bernhardschaefer/handwritten-diagram-datasets/): hosts the generated COCO datasets among other diagram datasets and features a demo that shows how to parse and visualize the COCO annotations
- [bpmn-image-annotator](https://github.com/dwslab/bpmn-image-annotator): Annotation tool that has been developed to annotate hand-drawn images with ground-truth BPMN models.

### Demo

Also check out our [Sketch2BPMN](http://sketch2bpmn.informatik.uni-mannheim.de/) demo where you can try our method with your own images and download the generated BPMN XML.

### Project Organization

```
├── data
│   ├── annotations         <- ex00-ex10 .bpmn files.
│   ├── images              <- ex00-ex10 .png/.jpg images.
│   ├── words               <- ex00-ex10 Pascal VOC word annotation .xml files.
│   ├── exercises.pdf       <- modeling tasks ex00-ex10 that the hand-drawn models correspond to.
│   ├── writer_split.csv    <- maps each writerID to one of train/val/test split
└── README.md               <- Current file
```

### License

The dataset is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

### Citing hdBPMN

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
