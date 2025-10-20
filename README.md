# Automatic Face Analysis

This repository shall provide a collection about databases and tools for the analysis of faces. 
Please note that this repo is under development. Feel free to reach out for additions, and/or corrections. If you find a link or reference is outdated, I am happy to receive your feedback for corrections. 
Access rights to the databases might change or licenses might run out. 

**Important note:** 
I do not own any of the following databases. For questions about access and details, please contact the respective authors. 


## Facial Expression - Image and Video Datasets
In the following datasets contain images or video with labels of facial expression in no particular order, in the folowing pattern:

- name + link
  - short description
  - reference: tbd
  - available: tbd

- [Aff-Wild2 database](https://ibug.doc.ic.ac.uk/resources/aff-wild2/)
  - 541 videos of around 2.6M frames (in the wild) (big diversity in terms of subjects' ages, ethnicities and nationalities)
  - 554 subjects (326 of which are male and 228 female)
  - annotations: seven basic expressions (i.e., happiness, surprise, anger, disgust, fear, sadness and the neutral state), twelve action units (AUs 1,2,4,6,7,10,12,15,23,24,25,26) and valence and arousal
  - reference: several papers are listed on the webpage "must cite all following papers"
  - availability: upon request
- [AffectNet](https://www.mohammadmahoor.com/pages/databases/affectnet/) 
  - <1M facial images
  - annotations: ca. half (~440K) annotated presence of seven discrete facial expressions
  - reference: "AffectNet: A New Database for Facial Expression, Valence, and Arousal Computation in the Wild," Mollahosseini et al., 2017 
  - available: upon request for academics
- [The Japanese Female Facial Expression (JAFFE) Dataset](https://www.kasrl.org/jaffe_download)
   - 213 images, 10 Japanese women, gray scale (Several images of each expression for each expresser)
   - annotations: averaged semantic ratings on 6 facial expressions by 60 Japanese viewers, 7 Posed Facial Expressions (6 basic facial expressions + 1 neutral) 
   - reference: "Coding Facial Expressions with Gabor Wavelets," Lyons, Michael J., Miyuki Kamachi, and Jiro Gyoba, 1998
   - available: upon request for academics
- [RAVDESS](https://zenodo.org/record/1188976#.ZCPaFC8Robx) (2018):
  - The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) 
  - 7356 recordings were each rated 10 times on emotional validity, intensity, and genuineness. Ratings were provided by 247 individuals 
  - to verify: [kaggle link](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio)
  - subjects: 24 professional actors (12 female, 12 male), vocalizing two lexically-matched statements in a neutral North American accent
  - annotations: emotion + intensity
    - Speech emotions: calm, happy, sad, angry, fearful, surprise, and disgust, each at two levels intensity (normal, strong) + neutral expression.
  - available: under a Creative Commons Attribution 
- SAMM: A Spontaneous Micro-Facial Movement Dataset
  - available: tbd
   
### Infant Databases
- [The City Infant Faces Database: A validated set of infant facial expressions](https://pmc.ncbi.nlm.nih.gov/articles/PMC5809537/)
  - 60 photographs of positive infant faces, 54 photographs of negative infant faces, and 40 photographs of neutral infant faces.
  - reference: Webb R, Ayers S, Endress A. The City Infant Faces Database: A validated set of infant facial expressions. Behav Res Methods. 2018 Feb; 50(1):151-159. doi: 10.3758/s13428-017-0859-9. PMID: 28205132; PMCID: PMC5809537 
  - available upon request (for researchers)
- [Tromsø Infant Faces Database )(TIF)](https://uit.no/project/norbaby/database)
  - 119 images of infant facial expressions
  - 18 subjects (age 4-12 months)
  - annotations: 4-7 facial expressions (happy & sad for all, for some: anger, fear, suprise or disgust) validated by over 700 participants 
  - reference: "The Tromso Infant Faces database (TIF): development, validation and application to assess parenting experience on clarity and intensity ratings", Maack JK, Bohne A, Nordahl D, Livsdatter L, Overvoll M, Wang CA and Pfuhl G (2017)
  - available: upon request for academics
- [The Child Affective Facial Expressions Set (CAFE)](https://www.childstudycenter-rutgers.com/the-child-affective-facial-expression-se)
  - 1200 photographs
  - subjects: over 100 children (ages 2-8)
  - annotations: 7 different facial expressions - happy, angry, sad, fearful, surprise, neutral, and disgust.
  - reference: "The Child Affective Facial Expression (CAFE) Set: Validity and reliability from untrained adults", LoBue, V. & Thrasher, C., 2015
  - available: upon request for academics


## Interaction

- [Cardiff Conversation Database (CCDb)](https://ccdb.cs.cf.ac.uk/)
  - audio-visual natural conversation database with 2D and 3D data.
  - annotations: tbd
  - reference: tbd, 2013
  - available: upon request for academics


## (Mental) Health Labels

- [YouTube Facial Palsy (YFP) Database](https://sites.google.com/view/yfp-database#h.p_DaUvW9mE7B_g) (2018)
  - 32 videos of 21 patients from YouTube, and a few patients have multiple videos
  - annotations: tbd
  - reference: tbd
  - available: upon request for academics
- [Wizard of Oz](https://dcapswoz.ict.usc.edu/)
  - features extracted from video (not actual image and video footage)
  - subjects: 
  - annotations: tbd
  - reference: tbd
  - available: upon request for academics


### Beyond Visual

- Audio [speech data with depression labels](https://github.com/speechandlanguageprocessing/ICASSP2022-Depression)
- [EMU: Early Mental Health Uncovering](https://github.com/mltlachac/EMU) (2021)
  - availibility: ?
- [Depresjon](https://datasets.simula.no/depresjon/) [kaggle](https://www.kaggle.com/datasets/arashnic/the-depression-dataset) (2018):
  - A Motor Activity Database of Depression Episodes in Unipolar and Bipolar Patients:  motor activity recordings of 23 unipolar and bipolar depressed patients and 32 healthy controls.
  - freely available
- [DASPS database ](https://ieee-dataport.org/open-access/dasps-database) (2021):
  - raw EEG data collected from the 23 participants during anxiety. "We provided a matlab script for the segmentation of each EEG signal into 6 segments corresponding to the 6 situations.".
- "The Turkish Audio-Visual Bipolar Disorder Corpus", Ciftci, Kaya (2018). audio-visual Bipolar Disorder (BD) corpus for the affective computing and psychiatric communities
  - has become unavailable. (Permitted use ran out, listed for completeness.)
<!-- Files have not yet been uploaded: for "Facial Paralysis Dataset" https://ieee-dataport.org/documents/facial-paralysis-dataset#files-->



### Infant Databases
- [A Dataset of Eye Movements for the Children with Autism Spectrum Disorder](https://zenodo.org/records/2647418)
  - 300 natural scene images and the corresponding eye movement
  - 14 children with ASD and 14 healthy controls
  - reference: H. Duan, G. Zhai, X. Min, Z. Che, Y. Fang, X. Yang, J. Gutiérrez, P. Le Callet, "A Dataset of Eye Movements for the Children with Autism Spectrum Disorder", ACM Multimedia Systems Conference (MMSys'19), Jun. 2019.
  - available: free to download
- [The Craniofacial microsomia: Longitudinal Outcomes in Children pre-Kindergarten (CLOCK)](https://pubmed.ncbi.nlm.nih.gov/30621445/) (2019)
  - study is a longitudinal cohort study of neurobehavioral outcomes in infants and toddlers with craniofacial microsomia (CFM)
  - 108 cases and 84 controls
  - reference: Luquetti DV, Speltz ML, Wallace ER, Siebold B, Collett BR, Drake AF, Johns AL, Kapp-Simon KA, Kinter SL, Leroux BG, Magee L, Norton S, Sie K, Heike CL. Methods and Challenges in a Cohort Study of Infants and Toddlers With Craniofacial Microsomia: The Clock Study. Cleft Palate Craniofac J. 2019 Aug;56(7):877-889. doi: 10.1177/1055665618821014. Epub 2019 Jan 8. PMID: 30621445; PMCID: PMC6996714.
  - available: ?
- [MIAMI](https://pubmed.ncbi.nlm.nih.gov/26640622/) (2015)
  - head movement in mothers and infants during the Still Face paradigm
  - 42 infants: 4-month-old infants and their mothers
  - reference: Hammal Z, Cohn JF, Messinger DS. Head Movement Dynamics During Play and Perturbed Mother-Infant Interaction. IEEE Trans Affect Comput. 2015 Oct-Dec;6(4):361-370. doi: 10.1109/TAFFC.2015.2422702. Epub 2015 Apr 13. PMID: 26640622; PMCID: PMC4666546.
  - available: ?


## Tools
### Facial Action Units and more
- [OpenFace](https://openface-api.readthedocs.io/en/latest/)
- [Python Facial Expression Analysis Toolbox (Py-Feat)](https://py-feat.org/pages/intro.html)
- PyAFAR: Python-based Automated Facial Action Recognition library for use in Infants and Adults: [website](https://pyafar.org/), [github](https://github.com/AffectAnalysisGroup/PyAFAR)

### Facial Landmarks only
- [dlib](http://dlib.net/)
- [Mediapipe](https://developers.google.com/mediapipe/)

## Some Face Models
Publicly available models.
- [Candide-3](candide3.md): 3D wireframe model: 113 3D vertices connected with triangles, parameters for changing of the shape and expression of the 3D face
- [Basel Face Model](https://faces.dmi.unibas.ch/bfm/) - 3D Morphable Face Model (Shape and Texture)



## 2DO
- check all AVEC, e.g. [AVEC2013](https://github.com/chkche1/avec2013), [AVEC2019](https://sites.google.com/view/avec2019/home) for availabilty
- [Binghamton Face Databases](https://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html)

### Human Motion Databases
2do: add to another repo
- [AIFit: Automatic 3D Human-Interpretable Feedback Models for Fitness Training](https://fit3d.imar.ro/)
- [Human3.6M](http://vision.imar.ro/human3.6m/description.php) 


## Related Sources
- [Affective Computing](https://github.com/alexandrainst/AffectiveComputingKnowledgeExchange)
- more datasets: [here](https://emutivo.wpi.edu/index.php/data/)
- [promising survey](https://www.mdpi.com/1424-8220/22/4/1524)
- more [face rec databases](https://www.face-rec.org/databases/)

## Contact
[Stella Grasshof](https://pure.itu.dk/en/persons/stella-grasshof) - IT University of Copenhagen

<p align="right">[<a href="#readme-top">back to top</a>]</p>
