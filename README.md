# TransformerCRF (from UoM, MCR)

<img src="https://github.com/poethan/TransformerCRF/blob/main/TransformerCRF-UoM-logo-.png" width="100">

A Transformer-based Machine Learning Framework using Conditional Random Fields as Decoder for Clinical Text Mining

Place-holder for our project/poster presentation in HealTAC2022 conference and follow-up work: code and data sharing

Conference program: https://healtac2022.github.io/programmes/

Our poster and presentation are shared in the files under this repository
https://github.com/poethan/TransformerCRF/blob/main/Healtac22_poster_transformerCRF.pdf  
alternatively this link also fine [folder-address](https://drive.google.com/drive/folders/1ooyUP91Z5N-LPRsjDhOPZYrp5WpDunLw?usp=sharing).



# News: New [Pre-Print](https://github.com/HECTA-UoM/TransformerCRF/blob/main/view_TransformerCRF.pdf) with Amazing New Results, Accepted to Big Data Analytics for Health and Medicine (BDA4HM 2023) at IEEE BigData 2023! [saved models hosted here - link](https://drive.google.com/drive/folders/1tDo18m_kJyw8cobLNzZMgsDtDLUUx6kI?usp=sharing)
"Exploring the Value of Pre-trained Language Models for Clinical Named Entity Recognition" 2023 ArXiv pre-print https://doi.org/10.48550/arXiv.2210.12770 [Link](http://arxiv.org/abs/2210.12770). [BDA4HM2023-link](https://bda4hm.github.io)

| New models included |
|---|
From this repository: new version - fine-tuned PLMs and LLMs 
- BERT-Apt
- BERT-CRF
- BioBERT-Apt
- BioBERT-CRF
- ClinicalBERT-Apt
- ClinicalBERT-CRF

Learning from Scratch:
  
- TransformerApt
- Transformer-CRF

# TransformerCRF+
we will combine NER+RE and generate a representation table on this. stay tuned, or why not get in touch with us!


| older version |
 
https://github.com/poethan/TransformerCRF/blob/main/TransformerCRF_dev-main.zip


| Experimental Trials from Pilot Study using n2c2-2018 challenge set in data-constrained fine-tuning/learning|
|---|

**TransformerCRF**
- learning from scratch using 303 EHR letters from n2c2-2018

**BioformerApt**
- Adaptation layer on top of Bioformer testing its performance on n2c2-2018 test set of 200 EHR letters

**BioformerApt, ClinicalBERT-CRF, BioformerCRF**
- Continuous learning useing data constrained setting of 303 EHR letters

| other posters related to this project |
On clinical Text Mining: another project/poster presentation from HealTAC2022 is also uploaded on this github page
'Diagnosis Certainty and Progression: A Natural Language Processing Approach to Enable Characterisation of the Evolution of Diagnoses in Clinical Notes'
[poster](https://github.com/poethan/TransformerCRF/blob/main/HealTAC22_poster14_centainty_progression.pdf)


| Citation Assistant |
|---|

**Bibtex**

@misc{belkadi2023exploring,
      title={Exploring the Value of Pre-trained Language Models for Clinical Named Entity Recognition}, 
      author={Samuel Belkadi and Lifeng Han and Yuping Wu and Goran Nenadic},
      year={2023},
      eprint={2210.12770},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}


**Plain**

- Samuel Belkadi, Lifeng Han, Yuping Wu, and Goran Nenadic. 2023. "Exploring the Value of Pre-trained Language Models for Clinical Named Entity Recognition". Forth-coming. BDA4HM2023 at IEEE Big Data 2023. Sorrento, Italy, December 15-18. arXiv:2210.12770 [cs.CL] https://doi.org/10.48550/arXiv.2210.12770 

- Lifeng Han, Valerio Antonini, Ghada Alfattni, Alfredo Madrid, Warren Del-Pinto, Judith Andrew, William G. Dixon, Meghna Jani, Ana María Aldana, Robyn Hamilton, Karim Webb, Goran Nenadic. 2022. A Transformer-based Machine Learning Framework using Conditional Random Fields as Decoder for Clinical Text Mining. Posters in HealTAC 2022: the 5th Healthcare Text Analytics Conference. June 15-16th. Virtual and Local Hubs in UK.

- Alfredo Madrid, Caitlin Bullin, Lifeng Han, Judith Andrew, Warren Del-Pinto, Ghada Alfattni, Oswaldo S. Pabón, Ernestina M. Ruiz, Luis Rodríguez, Ana María Aldana, Robyn Hamilton, Karim Webb, Meghna Jani, Goran Nenadic, William G. Dixon. 2022. Diagnosis Certainty and Progression: A Natural Language Processing Approach to Enable Characterisation of the Evolution of Diagnoses in Clinical Notes. Posters in HealTAC 2022: the 5th Healthcare Text Analytics Conference. June 15-16th. Virtual and Local Hubs in UK.


| Acknowledgement |
|---|

- We thank Viktor Schlegel for helping on debugging and Hao Li for discussion during the development stage. We thank Alfredo Madrid Garcia on the co-work regarding clinical annotation and computational model guidlines. We are grateful to *Manchester Open Research Fund* (OR) for supporting this on-going open source project.

| Contact, welcome to reach out |
|---|

- firstname.lastname@manchester.ac.uk (Firstname: Lifeng; Lastname: Han)|(Firstname: Yuping; Lastname: Wu)
- firstname.lastname@student.manchester.ac.uk (Firstname: Samuel; Lastname: Belkadi)

| Read More about Our Work |
|---|
[Samuel Belkadi](https://scholar.google.co.uk/citations?hl=en&user=OMoa6IoAAAAJ)
[Yuping Wu](https://scholar.google.com/citations?user=vZV_HuEAAAAJ&hl=en)
[Lifeng Han, PhD](https://scholar.google.com/citations?user=_vf3E2QAAAAJ&hl=en)
[Goran Nenadic, Prof](https://research.manchester.ac.uk/en/persons/gnenadic)
