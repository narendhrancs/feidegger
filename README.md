# Feidegger

A Multi-modal Corpus of Fashion Images and Descriptions in German

## What is it? 

The FEIDEGGER (fashion images and descriptions in German) dataset is a new multi-modal corpus that focuses specifically on the domain of fashion items and their visual descriptions in German. The dataset was created as part of ongoing research at Zalando into text-image multi-modality in the area of fashion.

![Alt text](docs/example.jpg?raw=true "Title")

The dataset itself consists of **8732 high-resolution images**, each depicting a dress from the available on the Zalando shop against a white-background. For each of the images we provide **five textual annotations in German**, each of which has been generated by a separate user. The example above shows 2 of the 5 descriptions for a dress (English translations only given for illustration, but not part of the dataset).

## Background

Unlike other tasks typically encountered in multi-modal learning, in fashion the informative information in the visual data often consists of very fine-grained details that needs to be reflected in the textual descriptions. Furthermore in order to generate such detailed descriptions, users must often rely on a domain-specific vocabulary. These particularities make the creation of a multi-modal fashion-related dataset a challenging task.

In order to create FEIDEGGER we leveraged crowd-sourcing while developing a novel annotation and assessment pipeline in order to ensure the high-quality of the final dataset. The pipeline and motivation behind various design decisions can be found in our published work.

## More Background

For more information on the dataset, please check out [LREC 2018 paper](http://aclweb.org/anthology/L18-1070). 

## Citing FEIDEGGER

Please cite the following paper when using FEIDEGGER: 

```
@inproceedings{lefakis2018feidegger,
  title={FEIDEGGER: A Multi-modal Corpus of Fashion Images and Descriptions in German},
  author={Lefakis, Leonidas and Akbik, Alan and Vollgraf, Roland},
  booktitle = {{LREC} 2018, 11th Language Resources and Evaluation Conference},
  year      = {2018}
}
```
