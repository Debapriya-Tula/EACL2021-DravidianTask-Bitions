# EACL2021-DravidianTask-Bitions and SN Computer Science Journal
This repo contains implementation for the paper <a href="https://aclanthology.org/2021.dravidianlangtech-1.42/"> <b>"Bitions@DravidianLangTech-EACL2021: Ensemble of Multilingual Language Models with Pseudo Labeling for Offence Detection in Dravidian Languages"</b></a> presented at EACL-2021, and the paper <a href="https://doi.org/10.1007/s42979-022-01190-1"><b>"Offence Detection in Dravidian Languages Using Code-Mixing Index-Based Focal Loss"</b></a> accepted to SN Computer Science Journal.

In this paper, we propose use of ensembled multilingual models (transformers) with focal loss and inverse class weights. Further, we make use of pseudo labelling to improve our results. A novel loss based on the focal loss is proposed to cater to code-mixing in the data. A cosine normalization classifier is used to cater to few-shot classes as well.

To replicate the EACL 2021 results, use the output files from ```DistilmBERT/DistilmBERT(class_weightiing+pseudo_labelling).ipynb``` and ```ULMFiT/{lang}_PseudoLabelling_AggressionNLP.ipynb``` to feed to ```Soft Ensemble/Soft_Ensembling.ipynb```

To replicate the SN Journal results, use the output files from ```DistilmBERT(cmi_loss+cosnorm+pseudo_labelling).ipynb``` and ```IndicBert(cmi_loss+cosnorm+pseudo_labelling).ipynb``` to feed to ```Soft Ensemble/Soft_Ensembling.ipynb```

If you find this repo useful, please cite our papers :
```
@inproceedings{tula2021bitions,
   title={Bitions@DravidianLangTech-EACL2021: Ensemble of Multilingual Language Models with Pseudo Labeling for offence Detection in Dravidian Languages},
    author = {Tula, Debapriya  and
      Potluri, Prathyush  and
      MS, Shreyas and
      Doddapaneni, Sumanth and
      Sahu, Pranjal and
      Sukumaran, Rohan   and
      Patwa, Parth},      
    booktitle = {Proceedings of the First Workshop on Speech and Language Technologies for Dravidian Languages},
    month = {April},
    year = {2021},
    publisher = {Association for Computational Linguistics}
    url = {https://aclanthology.org/2021.dravidianlangtech-1.42/}
}
```

```
@Article{Tula2022,
author = {Tula, Debapriya
and Shreyas, M. S.
and Reddy, Viswanatha
and Sahu, Pranjal
and Doddapaneni, Sumanth
and Potluri, Prathyush
and Sukumaran, Rohan
and Patwa, Parth},
title = {Offence Detection in Dravidian Languages Using Code-Mixing Index-Based Focal Loss},
journal = {SN Computer Science},
year = {2022},
month = {Jun},
day = {13},
volume = {3},
number = {5},
pages = {330},
issn = {2661-8907},
doi = {10.1007/s42979-022-01190-1},
url = {https://doi.org/10.1007/s42979-022-01190-1}
}
```
