# EACL2021-DravidianTask-Bitions
This repo contains implementation for the paper <b>"Bitions@DravidianLangTech-EACL2021: Ensemble of Multilingual Language Models with Pseudo Labeling for Offence Detection in Dravidian Languages"</b> to be presented at EACL-2021 

In this paper, we propose use of ensembled multilingual models (transformers) with focal loss and inverse class weights. Further, we make use of psuedo labelling to improve our results.

To replicate the results, use the output files from ```DistilmBERT/DistilmBERT(class_weightiing+pseudo_labelling).ipynb``` and ```ULMFiT/{lang}_PseudoLabelling_AggressionNLP.ipynb``` to feed to ```Soft Ensemble/Soft_Ensembling.ipynb```

If you find this repo useful, please cite our paper :
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
}
```