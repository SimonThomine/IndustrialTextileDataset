
# IndustrialTextileDataset

Introduction of new dataset for unsupervised fabric defect detection 
This dataset aims to provide a color dataset with real industrial fabric defect gathered in a visiting machine with several industrial cameras.
It has been designed with the same nomenclature as MVTEC AD dataset (https://www.mvtec.com/company/research/datasets/mvtec-ad) for unsupervised anomaly detection. 

![Capture d'écran](images/Samples.png)

## Download 

The dataset can be downloaded in google drive with this link : LIEN DRIVE 

## Citation
If you use this dataset, please cite
```
@inproceedings{Thomine_2023_Knowledge,
    author    = {Thomine, Simon and Snoussi, Hichem},
    title     = {Distillation-based fabric anomaly detection},
    booktitle = {Textile Research Journal},
    month     = {August},
    year      = {2023}
}
```

## Utilisation
This dataset is designed for unsupervised anomaly detection task but can also be used for domain-generalization approach.
The nomenclature is designed as : 

![Capture d'écran](images/Nomenclature.png )

- category/
  - train/
    - good/
      - img1.png
      - ...
  - test/
    - anomaly/
      - img1.png
      - ...
    - good/
      - img1.png
      - ...

As in any unsupervised training, train data are defect-free. Defective samples are only in the test set.

## Exemples

Exemple of defect segmentation obtained with our knowledge distillation-based method
![Exemple d'utilisation 1](images/DefectITDB.png)

## Documentation

List of articles related to the subject of textile defect detection

- MixedTeacher : Knowledge Distillation for fast inference textural anomaly detection (https://arxiv.org/abs/2306.09859)
- FABLE : Fabric Anomaly Detection Automation Process (https://arxiv.org/abs/2306.10089)


## Auteurs

- Simon Thomine <sup>1</sup>, PhD student - [@SimonThomine](https://github.com/SimonThomine) - simon.thomine@utt.fr
- Hichem Snoussi <sup>1</sup>, Full Professor

<sup>1</sup> University of Technology of Troyes, France

## Licence


This project is under the MIT license [MIT](https://opensource.org/licenses/MIT).
