# Dsan 6600 Project - Group 16

Mingqian Liu, Xin Xiang, Tianqi Zhou, Yanfeng Zhang

## Project - Neural Image Style Transfer

This project presents a study on image style transfer using the pre-trainedVGG19 network, focusing on applying the aesthetic styles of celebratedartworks to photographic images. The VGG19's layers were selectivelyemployed and fine-tuned with optimal content and style weight parametersto achieve the desired synthesis. Van Gogh's "Starry Night" and GeorgetownUniversity's Healy Hall were the primary images used for demonstratingthe technique. Extensive hyperparameter tuning and a training regimen of1000 epochs yielded a stylized image with markedly reduced loss, showcasing the model's ability to effectively blend artistic styles onto real-worldstructures while preserving the integrity of the content image. The resuliis a synthesized image that exhibits a harmonious fusion of art and reality,illustrating the potential of CNNs in creative image transformation.

## Repository structure

The repository has the following structure:
```.
├── LICENSE
├── README.md
├── code/
├── data/
├── images/
└── docs/
```

## Description

- The `code/` directory includes all of the scripts. 
- The `data/` directory contains all the data files. 
- The `images/` directory where the input and output images will be built. 
- The `docs/` directory contains the presentation slides and report published to the Github page.

## Contributions

- Mingqian Liu is responsible for literature search, model design, and report writing, and is the team leader.
- Xin Xiang is responsible for data and image preprocessing, visualization process and report writing.
- Tianqi Zhou is responsible for literature search, model introduction, and report writing.
- Yanfeng Zhang was responsible for model tuning, result presentation, and report writing.
